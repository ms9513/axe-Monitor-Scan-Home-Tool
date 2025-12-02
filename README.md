# axe Monitor Scan Home Tool

A browser extension/user script for enhancing the axe Monitor interface with additional scanning and reporting capabilities.

## Description

This tool provides enhanced functionality for axe Monitor users, including:
- Custom scan summaries and reports
- Quick actions for issues
- Enhanced page and scan list views
- Real-time monitoring of scan progress
- Visual feedback and status indicators

## Features

- **Scans List Page Enhancement**: View detailed scan summaries and progress
- **Issues Quick Actions**: Rapid issue management and filtering
- **Pages List Management**: Enhanced page listing with status indicators
- **Real-time Updates**: Monitor scan progress with live updates
- **Visual Reports**: Generate comprehensive accessibility reports

## Installation

### As a Browser Extension

1. Clone this repository
2. Load the extension in your browser:
   - **Chrome/Edge**: Go to `chrome://extensions/`, enable Developer Mode, click "Load unpacked", and select the extension directory
   - **Firefox**: Go to `about:debugging#/runtime/this-firefox`, click "Load Temporary Add-on", and select the `main` file

### As a Userscript

1. Install a userscript manager (e.g., Tampermonkey, Greasemonkey)
2. Copy the contents of the `main` file
3. Create a new userscript and paste the code

## Usage

The tool automatically activates when you visit supported axe Monitor pages:
- `/monitor/scans` - Scans list page
- `/monitor/pages` - Pages list page
- `/monitor/issues` - Issues page with scan run parameter

## Supported Domains

- `*.dequecloud.com`

## Development

### Prerequisites

- Modern web browser (Chrome, Firefox, Edge, etc.)
- Access to axe Monitor

### File Structure

```
axe-Monitor-Scan-Home-Tool/
├── main                    # Main script file
├── README.md              # This file
└── .gitignore            # Git ignore rules
```

## License

[Specify your license here]

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Support

For issues, questions, or suggestions, please open an issue in the GitHub repository.

## Author

[Your name/organization]

## Acknowledgments

- Built for use with [axe Monitor](https://www.deque.com/axe/monitor/)
- Powered by accessibility testing best practices
