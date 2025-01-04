# CS1515 Binaries

If you’d like to see if your code can interoperate with our code (which is what it will be tested against), feel free to download our binaries from this repo. Running your code against our binaries can be an easy way to isolate which parts of your code may or may not be working as intended.

> [!IMPORTANT]  
> Make sure to download the relevant binary for your architecture. x86 binaries will not work on ARM architecture, and vice versa.

## Usage
1. Download the relevant binary/binaries to your build directory. You may want to rename it to something distinguishable so that your own binaries do not get overwritten. For example, `signal_app` to `signal_app_ta`
2. Make the file executable. Navigate into the build directory and enter `chmod +x <file_name>`
3. Run the binary just as you would your own, paying attention to the file name if you changed it. For example, if you renamed the binary to `signal_app_ta`, you might use the command `./signal_app_ta listen localhost 8080`
