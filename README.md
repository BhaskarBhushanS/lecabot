# LeCabot 🤖

Welcome to **LeCabot**, a low-cost mobile manipulator mod designed for the SO-100 and Unitree Go2 robots. This project aims to enhance the capabilities of these platforms, making them more accessible for hobbyists and researchers. 

![LeCabot Logo](https://img.shields.io/badge/LeCabot-Ready%20to%20Explore-blue)

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Releases](#releases)
- [Contact](#contact)

## Introduction

LeCabot is designed to provide a cost-effective solution for those looking to explore mobile manipulation. Whether you're a student, researcher, or hobbyist, LeCabot offers a platform to experiment with robotic manipulation in a practical way. The mod enhances the functionality of the SO-100 and Unitree Go2, making them more versatile for various applications.

## Features

- **Cost-Effective**: LeCabot is built with affordability in mind, making it accessible for everyone.
- **Compatibility**: Works seamlessly with SO-100 and Unitree Go2.
- **User-Friendly**: Designed for ease of use, even for those new to robotics.
- **Extensible**: Supports various add-ons and modifications for advanced users.
- **Community Driven**: Built on feedback from users to continuously improve functionality.

## Installation

To get started with LeCabot, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/BhaskarBhushanS/lecabot.git
   cd lecabot
   ```

2. **Download the Latest Release**: 
   Visit [this link](https://github.com/BhaskarBhushanS/lecabot/releases) to download the latest release. Execute the downloaded file to install LeCabot on your device.

3. **Dependencies**: 
   Make sure you have the necessary dependencies installed. You can find a list of required libraries in the `requirements.txt` file in the repository.

4. **Configuration**: 
   Configure your settings by editing the `config.json` file according to your needs.

5. **Run the Application**:
   Execute the following command to start LeCabot:
   ```bash
   python main.py
   ```

## Usage

Once installed, you can begin using LeCabot with your SO-100 or Unitree Go2. Here are some basic commands to get you started:

- **Move the Robot**:
   ```bash
   python move.py --direction forward --speed 1
   ```

- **Manipulate Objects**:
   ```bash
   python manipulate.py --action pick --object box
   ```

- **Check Status**:
   ```bash
   python status.py
   ```

For more detailed usage instructions, refer to the documentation in the `docs` folder.

## Contributing

We welcome contributions from the community. If you'd like to contribute to LeCabot, please follow these steps:

1. **Fork the Repository**: Click on the "Fork" button at the top right of the page.
2. **Create a Branch**: 
   ```bash
   git checkout -b feature/YourFeatureName
   ```
3. **Make Your Changes**: Implement your feature or fix.
4. **Commit Your Changes**: 
   ```bash
   git commit -m "Add your message here"
   ```
5. **Push to the Branch**: 
   ```bash
   git push origin feature/YourFeatureName
   ```
6. **Create a Pull Request**: Go to the original repository and click on "New Pull Request".

## License

LeCabot is licensed under the MIT License. See the `LICENSE` file for more details.

## Releases

For the latest updates and releases, visit [this link](https://github.com/BhaskarBhushanS/lecabot/releases). Download the latest version and execute the file to keep your installation up to date.

## Contact

For questions, suggestions, or feedback, feel free to reach out:

- **Email**: your.email@example.com
- **GitHub**: [Your GitHub Profile](https://github.com/yourprofile)

Thank you for your interest in LeCabot! We look forward to seeing what you create with it.