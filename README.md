# NegahkadehStream

A comprehensive Instagram live streaming tool built in Python that provides automated login, two-factor authentication, and live broadcast management capabilities.

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Dependencies](#dependencies)
- [File Structure](#file-structure)
- [Security Notes](#security-notes)
- [Troubleshooting](#troubleshooting)
- [Contributing](#contributing)
- [License](#license)

## 🎯 Overview

NegahkadehStream is a Python-based Instagram live streaming automation tool that simplifies the process of managing Instagram live broadcasts. The tool provides a user-friendly interface for logging into Instagram accounts, handling two-factor authentication, and managing live streaming sessions.

## ✨ Features

- **Automated Instagram Login**: Secure login functionality with session management
- **Two-Factor Authentication (2FA)**: Support for Instagram's 2FA security feature
- **Live Stream Management**: Tools for creating and managing live broadcasts
- **User Interface**: PySimpleGUI-based interface for easy interaction
- **Data Management**: CSV-based data handling for user/viewer information
- **Session Persistence**: Maintains login sessions across application restarts
- **Request Handling**: Robust HTTP request management with proper headers and authentication

## 🔧 Prerequisites

- Python 3.7 or higher
- Instagram account with appropriate permissions
- Internet connection for Instagram API access

## 📦 Installation

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd NegahkadehStream
   ```

2. **Install required dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

   Or install manually:
   ```bash
   pip install requests pandas PySimpleGUI Pillow pyperclip
   ```

3. **Verify installation**:
   ```bash
   python NegahStream.py --help
   ```

## 🚀 Usage

### Basic Usage

Run the application with the main script:

```bash
python NegahStream.py
```

### Command Line Options

The application supports various command line arguments:

```bash
python NegahStream.py [options]
```

### GUI Interface

The application provides a graphical user interface for:
- Account login
- Two-factor authentication
- Live stream management
- Data viewing and manipulation

## ⚙️ Configuration

### Data Files

- `data.csv`: Contains user/viewer information and data
- Configuration settings can be modified within the application

### Environment Variables

Set up any required environment variables for API access or authentication tokens.

## 📚 Dependencies

### Core Dependencies

- **requests**: HTTP library for API calls
- **pandas**: Data manipulation and analysis
- **PySimpleGUI**: GUI framework for user interface
- **PIL (Pillow)**: Image processing capabilities
- **pyperclip**: Clipboard operations

### Standard Library Dependencies

- **argparse**: Command line argument parsing
- **hashlib**: Cryptographic hash functions
- **hmac**: Hash-based message authentication
- **json**: JSON data handling
- **os**: Operating system interface
- **sys**: System-specific parameters
- **time**: Time-related functions
- **urllib**: URL handling

## 📁 File Structure

```
NegahkadehStream/
├── NegahStream.py          # Main application file (806 lines)
├── data.csv               # User/viewer data file (1890 lines)
├── README.md              # This documentation file
├── requirements.txt       # Python dependencies
└── images/               # Image assets directory
    ├── icon.png
    └── logo.png
```

## 🔒 Security Notes

- **Account Security**: Never share your Instagram credentials
- **2FA Protection**: Always enable two-factor authentication on your Instagram account
- **Session Management**: The application maintains login sessions - log out when not in use
- **Data Privacy**: User data in `data.csv` should be handled according to privacy regulations

## 🛠️ Troubleshooting

### Common Issues

1. **Login Failures**:
   - Verify your Instagram credentials
   - Check if 2FA is properly configured
   - Ensure internet connection is stable

2. **Import Errors**:
   - Install missing dependencies: `pip install <package-name>`
   - Verify Python version compatibility

3. **GUI Issues**:
   - Ensure PySimpleGUI is properly installed
   - Check display settings and resolution

### Getting Help

If you encounter issues:
1. Check the error messages in the console
2. Verify all dependencies are installed
3. Ensure your Instagram account has the necessary permissions

## 🤝 Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues for bugs and feature requests.

### Development Setup

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## ⚠️ Disclaimer

This tool is for educational and personal use only. Users are responsible for complying with Instagram's Terms of Service and applicable laws. The developers are not responsible for any misuse of this software.

---

**Note**: This tool interacts with Instagram's services. Please ensure you comply with Instagram's Terms of Service and use the tool responsibly.
