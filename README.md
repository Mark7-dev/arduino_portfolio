# ESP32 Web Server with GPIO Control

This is a simple ESP32 web server example that allows you to control two GPIO pins using a web interface. You can use this code as a starting point to build your own IoT projects using the ESP32 microcontroller.

## Table of Contents

- [Hardware Setup](#hardware-setup)
- [Software Setup](#software-setup)
- [Web Interface](#web-interface)
- [GPIO Control](#gpio-control)
- [License](#license)

## Hardware Setup

Before you start using this code, you need to connect the ESP32 to your Wi-Fi network and configure the GPIO pins you want to control. Here's how to do it:

1. Connect the ESP32 to your computer using a USB cable.
2. Open the Arduino IDE and install the necessary libraries for the ESP32.
3. Configure your network credentials by replacing the `ssid` and `password` variables with your Wi-Fi network name (SSID) and password.
4. Configure the GPIO pins you want to control by changing the `output26` and `output27` variables.

## Software Setup

Make sure you have the Arduino IDE installed and configured for the ESP32. You can follow [official documentation](https://docs.espressif.com/projects/arduino-esp32/en/latest/installing.html) for installation and setup instructions.

## Web Interface

The ESP32 hosts a simple web page that allows you to control the state of two GPIO pins. You can access the web interface by entering the ESP32's IP address in a web browser.

1. Upload the code to the ESP32 using the Arduino IDE.
2. Open the serial monitor in the Arduino IDE to see the ESP32's IP address once it's connected to the Wi-Fi network.
3. Enter the IP address in your web browser.

You should see a web page that displays the current state of two GPIO pins (26 and 27) and buttons to toggle their states.

## GPIO Control

This code allows you to control the GPIO pins as follows:

- `/26/on`: Turns on GPIO pin 26.
- `/26/off`: Turns off GPIO pin 26.
- `/27/on`: Turns on GPIO pin 27.
- `/27/off`: Turns off GPIO pin 27.

You can customize the GPIO pins and their behaviour by modifying the code to suit your project's requirements.

## License

This code is provided under the [MIT License](LICENSE), allowing you to use and modify it for your own projects. Feel free to fork, contribute, and build upon it as needed.

Please note that this code example is for educational purposes and basic IoT projects. Ensure proper security measures and access controls if you plan to use it in a production environment.
