# WiFi Deauthentication Attack with ESP8266 and ESP8266 Flasher

## Overview

This repository provides a detailed explanation and implementation of a WiFi deauthentication attack using the ESP8266 microcontroller. The deauthentication attack is a network security technique that aims to disconnect devices from a wireless network by sending deauthentication packets.

The project includes the necessary code and instructions to set up the ESP8266 as a deauthentication device and execute the attack on vulnerable networks. Additionally, this guide incorporates the use of the ESP8266 Flasher tool, which simplifies the process of flashing firmware onto the ESP8266.

It is important to note that this project is for educational purposes only and should not be used for any illegal or malicious activities.

## Requirements

To replicate this project, you will need the following components:

- ESP8266 microcontroller (such as NodeMCU or Wemos D1 Mini)
- USB cable for programming and power supply
- Access to a WiFi network for testing
- ESP8266 Flasher tool


## Flashing Firmware with ESP8266 Flasher

1. Download the ESP8266 Flasher tool from the official repository: [https://github.com/nodemcu/nodemcu-flasher](https://github.com/nodemcu/nodemcu-flasher)

2. Extract the downloaded ZIP file to a convenient location on your computer.

3. Launch the ESP8266 Flasher tool.

4. Connect the ESP8266 to your computer using the USB cable.

5. In the ESP8266 Flasher tool, select the appropriate COM port for the connected ESP8266 device.

6. Click the **Config** button and browse to the firmware file (`esp8266_deauther.bin`) from the project repository.

7. Adjust other settings if necessary, such as flash size and baud rate.

8. Click the **Flash** button to begin the firmware flashing process.

9. Wait for the process to complete, and verify that the flash status shows success.

10. Disconnect and reconnect the ESP8266 from the USB cable to reset it.

11. Connect the ESP8266 with the SSID and Password  ( The password for pwned is deauther )


    More Details are in the video - https://www.youtube.com/watch?v=dDzYvKTFfoQ&ab_channel=VNX

## Usage and Legal Considerations

- The deauthentication attack is an intrusive technique and may violate the terms of service of the targeted network. Ensure you have proper authorization or conduct the attack in a controlled environment.

- This project is intended for educational and informational purposes only. The code provided is meant to facilitate learning and understanding of network security techniques.

- Use this project responsibly and do not engage in any illegal activities or cause harm to others.

## Disclaimer

The author of this repository and the contributors cannot be held responsible for any misuse or illegal activities carried out with the information and code provided. Use this project at your own risk and responsibility.

## Contributing

Contributions to this project are welcome. If you find any bugs, have improvements or suggestions, please open an issue or submit a pull request on the GitHub repository.

## License

This project is licensed under the [MIT License](LICENSE). Please review the license file for more information.

## Contact

For any questions or inquiries about this project, feel free to contact the author or contributors via the GitHub repository.

## Acknowledgments

This project builds upon the work of various researchers and developers in the field of wireless network security. Their contributions have been instrumental in advancing the understanding of these techniques.
