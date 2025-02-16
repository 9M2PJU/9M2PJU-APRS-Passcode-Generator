# 9M2PJU APRS Passcode Generator

This is a simple web-based tool to generate APRS passcodes based on the entered callsign. The passcode is generated using the APRS passcode algorithm, and the result is displayed in a user-friendly format. This tool is available online and can be accessed on [pass.hamradio.my](https://pass.hamradio.my).

## Features

- Generate APRS passcodes by entering a valid callsign.
- Display the callsign in blue with uppercase letters.
- Display the passcode in red for visibility.
- Clean, modern, and mobile-friendly design.

## Technologies Used

- **HTML**: The structure of the web page.
- **CSS**: For styling and creating a responsive design.
- **JavaScript**: Used for the APRS passcode algorithm and form functionality.

## What is APRS and APRS Passcode

APRS (Automatic Packet Reporting System) is a digital communication system used by amateur radio operators to transmit real-time data, such as location, weather reports, and messages. APRS uses packet radio to send information that can be received by other stations, displayed on maps, or used for various applications. It enables operators to share data through a decentralized network, improving situational awareness in real time.

The APRS passcode is a unique identifier used to authenticate and secure these transmissions, ensuring that the data is properly linked to the correct callsign and preventing unauthorized access. The passcode is generated from the user's callsign using a specific algorithm, which involves:

- Stripping any SSID (e.g., "-1") from the callsign.
- Converting the callsign to uppercase.
- Using bitwise XOR operations and shifting the ASCII values of the callsign, along with a constant value 0x73, to create a 16-bit passcode.

This passcode is used in several key areas:

- Beacon Transmissions: It is embedded in APRS beacon messages, which broadcast location and other data, ensuring that the information is from an authorized source.
- APRS Stations: It helps digipeaters and iGate stations validate incoming packets, maintaining the integrity of the APRS network.
- Authentication: In global APRS networks like APRS-IS, the passcode verifies that a transmission is legitimate and secure.
- Access to Services: Some APRS-based services and custom gateways may require the passcode for authentication and secure communication.
- By ensuring secure and authenticated communication, the APRS passcode helps maintain the integrity of the APRS network and prevents misuse or unauthorized access.

## License

This project is licensed under the **AGPL 3.0 License**. See the [LICENSE](https://www.gnu.org/licenses/agpl-3.0.html) for more details.

## How to Use

1. Open the web page: [9M2PJU APRS Passcode Generator](https://pass.hamradio.my).
2. Enter your callsign in the input field.
3. Click the "Generate" button to get your APRS passcode.
4. The passcode will be displayed below the form in red, and your callsign will be displayed in blue.

## Development

### Prerequisites

- Basic knowledge of HTML, CSS, and JavaScript.
- A GitHub account to contribute or fork the repository.

### How to Contribute

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add feature'`).
5. Push to the branch (`git push origin feature-name`).
6. Open a pull request.

## License

This project is licensed under the [AGPL 3.0 License](https://www.gnu.org/licenses/agpl-3.0.html).

## Thanks

Made for you by [9M2PJU](https://hamradio.my) and [JollyJolli]([https://hamradio.my](https://github.com/JollyJolli))

## How to Embed

You can easily embed the 9M2PJU APRS Passcode Generator on your website or blog by adding the following HTML iframe code, which you can adjust for width and height:

```html
<p><iframe src="https://9m2pju.github.io/aprs-passcode-generator" style="width: 100%; height: 500px; border: none;" allowfullscreen></iframe></p>
