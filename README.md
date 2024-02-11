# Kali iOS

This project is exciting and aims to bring the power and flexibility of Kali Linux to iOS devices. It enables users to access Kali Linux in text mode through a terminal emulator on their iOS devices. It opens up a whole new realm of possibilities for security professionals, enthusiasts, and researchers, allowing them to conduct security assessments and investigations seamlessly on the go.

## Requirements

- Device: iPhone 12 and higher
  
- Memory: A minimum of 7 GB of memory is required.
  
- Terminal emulator: You MUST download the iSH Shell from the App Store using the following link: [iSH Shell Download](https://apps.apple.com/gb/app/ish-shell/id1436902243)
  
- OS: To run our custom Kali rootfs, which contains bug fixes, please download it from the following link: [Custom Kali rootfs Download](https://drive.google.com/file/d/1XP5bsMfXF_YKOlYMN7uqHle1QOgwn8mc/view?usp=drivesdk) Or download official one from Kali website.

Please ensure that your device meets the specified requirements before proceeding with the installation and usage of the iSH Shell and custom Kali rootfs.

If you have any further questions or require assistance, please feel free to ask.

## Features

- Access Kali Linux: Utilize the complete suite of penetration testing and security tools that Kali Linux offers, directly from your iOS device.

- Text Mode: Interact with Kali Linux in text mode, enabling quick and efficient command-line operations.

- Terminal Emulator: The project provides a terminal emulator specifically designed for iOS, ensuring a seamless and intuitive user experience.

- Portability: Take advantage of the portability of iOS devices to perform security assessments and investigations wherever you go.

## Getting Started

To use Kali iOS, follow these steps:

1. Install ISH terminal emulator app on your iOS device from Appstore (see link in Requirements field)

2. Download our custom Kali rootfs tar archive of ~ 3GB (see link in Requirements field)

3. Launch ISH from your device

4. From ISH app :
   - Go to <Settings>
   - Click on <Filesystems>
   - Click on <Import>
   - Navigate to the directory you stored the Kali rootfs tar archive (only .tar.gz is compatible) and select it
   - Wait for ISH app to fully import it
   - Select your Kali importation
   - And, finally click on <Boot From This Filesystem>
   - ISH app will crash and doooon't worry, it's normal! launch ISH app again and wait until it boots to the new filesystem

5. Now you're in Alpine, which serves as recovery os. From here, run the startup script to initiate the Kali Linux environment:   ```   ./kali.sh   ```

6. CONGRATULATIONS!!! You are now ready to use full Kali Linux in text mode on your iOS device

7. To exit Kali environment, simply type  ```   exit   ```

## Contributing

We welcome contributions to the Kali iOS project! If you would like to contribute, follow these steps:

1. Fork the repository on GitHub.

2. Create a new branch from the main branch with a descriptive name:   ```   git checkout -b feature/new-feature   ```

3. Make your desired changes, ensuring adherence to coding standards and best practices.

4. Commit your changes with clear and concise commit messages:   ```   git commit -am 'Add new feature'   ```

5. Push your branch to your forked repository:   ```   git push origin feature/new-feature   ```

6. Open a pull request on the main repository to merge your changes.


Please ensure that your contributions align with the project's goals and follow the code of conduct.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

We would like to express our gratitude to the open-source community and the developers who have contributed to the tools and technologies utilized in this project.

## Contact

For any inquiries or feedback regarding Kali iOS, please reach out to us at (mailto:mewl.team@outlook.com).

## Disclaimer

Kali iOS is intended for educational and security assessment purposes only. Usage of the tools and techniques provided within this project on any unauthorized systems is strictly prohibited. The developers and maintainers of Kali iOS are not responsible for any misuse or damage caused by the utilization of this project.


## Donations

We greatly appreciate your interest in supporting the development and advancement of the Kali iOS project. Donations and sponsorships play a vital role in helping us sustain and enhance the project, allowing us to dedicate more time and resources to its ongoing growth.

By making a donation or becoming a sponsor, you contribute directly to the continued improvement and accessibility of Kali iOS. Your generous support enables us to invest in refining the user experience, expanding the range of supported devices, and incorporating new features and functionalities.

As a donor or sponsor, you become a valued member of our community, playing a significant role in driving the project forward. Your contribution not only helps us maintain the project but also demonstrates your commitment to fostering innovation in the realm of mobile security.

To show our gratitude, we will prominently feature the names or logos of our sponsors on the project's documentation and website, highlighting your support and recognition within the cybersecurity community.

If you would like to make a donation or discuss sponsorship opportunities, please reach out to us at (mailto:mewl.team@outlook.com). We are excited to explore potential partnerships and welcome the chance to discuss how your contributions can make a difference.

Together, let's push the boundaries of mobile security and empower individuals to bring the power of Kali Linux to iOS devices. We sincerely thank you for considering supporting Kali iOS and look forward to the possibility of collaborating with you.

Crypto Addresses for donations :

Bitcoin (BITCOIN) [13eYrb98CaJGqc741tYP5Y8YEma82HjBw5]

Ethereum (ERC20) [0x8ae76163fa0406d753b7b77b2d737f5493be3734]

Usdt (TRC20) [TM6CJPGbzG7CbKxPJztUiXYoHcGncAb9jA]

Bnb (BEP20) [0x8ae76163fa0406d753b7b77b2d737f5493be3734]


(Note: Please exercise caution when making donations and ensure you are following the necessary security measures to protect your funds.)

## THANK YOU
