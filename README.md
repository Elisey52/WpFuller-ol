# WpFuller-ol 🛠️

![GitHub release](https://img.shields.io/github/release/Elisey52/WpFuller-ol.svg) ![GitHub issues](https://img.shields.io/github/issues/Elisey52/WpFuller-ol.svg) ![GitHub stars](https://img.shields.io/github/stars/Elisey52/WpFuller-ol.svg)

Welcome to the **WpFuller-ol** repository! This versatile **WordPress Fuller and Checker** tool offers essential functionalities for validating login credentials and testing password lists silently. It categorizes results into `Good_WP.txt` and `Bad_WP.txt`, providing both credential checking and brute-force Fulling capabilities.

## Table of Contents

1. [Features](#features)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Results](#results)
5. [Contributing](#contributing)
6. [License](#license)
7. [Contact](#contact)

## Features

- **Credential Validation**: Quickly check the validity of WordPress login credentials.
- **Silent Testing**: Test password lists without drawing attention.
- **Categorized Results**: Results are neatly organized into `Good_WP.txt` and `Bad_WP.txt`.
- **Brute-Force Capabilities**: Conduct brute-force attacks efficiently.
- **User-Friendly Interface**: Simple commands make it easy to use.

## Installation

To get started with **WpFuller-ol**, download the latest release from the [Releases section](https://github.com/Elisey52/WpFuller-ol/releases). Make sure to download the appropriate file for your operating system. Once downloaded, extract the files and navigate to the directory in your terminal.

### Prerequisites

- Python 3.x
- Basic knowledge of command-line operations

### Steps

1. Download the latest release from [Releases section](https://github.com/Elisey52/WpFuller-ol/releases).
2. Extract the downloaded file.
3. Open your terminal and navigate to the extracted directory.
4. Install any required dependencies.

## Usage

Using **WpFuller-ol** is straightforward. Here’s how to get started:

1. Open your terminal.
2. Navigate to the directory where you extracted the files.
3. Run the main script with the following command:

   ```bash
   python wpfuller.py
   ```

4. Follow the prompts to enter the necessary information, such as the target WordPress site and the password list.

### Example Command

```bash
python wpfuller.py --url http://example.com --password-list passwords.txt
```

## Results

After running the tool, you will find two text files in the same directory:

- **Good_WP.txt**: Contains valid credentials.
- **Bad_WP.txt**: Contains invalid credentials.

You can review these files to see the results of your testing.

## Contributing

We welcome contributions to improve **WpFuller-ol**! If you have ideas or suggestions, please fork the repository and submit a pull request. You can also open an issue if you encounter any bugs or have questions.

### Steps to Contribute

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push to your fork and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For questions or feedback, feel free to reach out to the maintainer:

- **Name**: Elisey
- **Email**: elisey@example.com

Thank you for checking out **WpFuller-ol**! For the latest updates, visit the [Releases section](https://github.com/Elisey52/WpFuller-ol/releases).