# Garmin Monkey C Watchface App - Venu 2 - Pedro

Welcome to the Garmin Monkey C Watchface - Pedro for Venu 2! This README will guide you through the installation process for the Monkey C extension for VS Code, building the app, and running it with debug.

This application displays "pedro" racoon dancing around you watchface.

![screenshot](screenshot.png)

## Adding the Watchface to the Watch Using USB

To install your Monkey C watchface app on your Garmin Venu 2 using USB, follow these steps:

1. Connect your Garmin Venu 2 to your computer using a USB cable.
   
2. Once connected, your Garmin Venu 2 should appear as a storage device on your computer.

3. Locate the `.prg` file generated after building your Monkey C project. This file is typically located in the `build` folder of your project directory.

4. Copy the `.prg` file to the `APPS` folder on your Garmin Venu 2. If the `APPS` folder doesn't exist, you may need to create it.

5. Safely eject your Garmin Venu 2 from your computer.

6. On your Garmin Venu 2, navigate to the watchface selection screen.

7. Find and select your Monkey C watchface app from the list of available watchfaces.

8. Your Monkey C watchface app should now be installed and ready to use on your Garmin Venu 2.

## Monkey C Extension for VS Code

To develop Garmin Monkey C watchface apps efficiently, you'll need the Monkey C extension for Visual Studio Code. Follow these steps to install it:

1. Open Visual Studio Code.
2. Go to the Extensions view by clicking on the square icon in the Sidebar or by pressing `Ctrl+Shift+X`.
3. Search for "Monkey C" in the Extensions marketplace.
4. Click **Install** to install the "Monkey C" extension provided by Garmin Ltd.
5. Once installed, you'll have access to Monkey C language support, syntax highlighting, IntelliSense, and more in Visual Studio Code.

## Building the App

1. Press `Ctrl+Shift+B` or open the Command Palette (`Ctrl+Shift+P`) and search for "Monkey C: Build Project".
2. This will compile your Monkey C code into a `.prg` file, ready to be installed on your Garmin Venu 2.

## Running with Debug

Running your Monkey C watchface app with debug capabilities can help you identify and fix issues more efficiently. Here's how to run your app with debug:

1. Connect your Garmin Venu 2 to your computer via USB.
2. Open the Monkey C project folder in Visual Studio Code.
3. Ensure your Monkey C project is open and focused in VS Code.
4. Press `F5` to start debugging or open the Command Palette (`Ctrl+Shift+P`) and search for "Debug: Start Debugging".
5. Your Monkey C watchface app will be installed on your Garmin Venu 2, and you can debug it directly from VS Code.
   
   **Note:** You may need to set breakpoints in your code to pause execution at specific points and inspect variables.

## Additional Resources

For more information on developing Monkey C watchface apps for Garmin devices, refer to the [Garmin Developer Documentation](https://developer.garmin.com/connect-iq/monkey-c/). 

Enjoy building your custom watchface for the Garmin Venu 2! If you encounter any issues, feel free to consult the documentation or reach out to the Garmin developer community for support.