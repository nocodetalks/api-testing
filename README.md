# LLM Key Tester

A simple, secure, and user-friendly web application for testing and validating API keys from popular Large Language Model (LLM) providers. Test your API keys for OpenAI, Anthropic, Google Gemini, and OpenRouter to ensure they're working correctly before integrating them into your applications.

## 🔒 Privacy & Security

**Your API keys are completely secure and private:**
- All testing is performed client-side in your browser
- No API keys are stored, logged, or transmitted to any servers
- Your keys never leave your device
- No data collection or tracking

## ✨ Features

- **Multi-Provider Support**: Test API keys for 4 major LLM providers
  - OpenAI (GPT models)
  - Anthropic (Claude models)
  - Google Gemini
  - OpenRouter (access to multiple models)

- **Real-time Validation**: Instant feedback on API key validity
- **Detailed Results**: Comprehensive error messages and success details
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional interface with smooth animations
- **Format Validation**: Validates API key format before making network requests
- **Error Handling**: Graceful handling of network errors and CORS restrictions

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- API keys from the providers you want to test

### Installation

1. Clone or download this repository
2. Open `index.html` in your web browser
3. That's it! No additional setup required.

### Usage

1. **Open the application** in your web browser
2. **Enter your API key** in the appropriate field for the provider you want to test
3. **Click the "Test" button** to validate your key
4. **View the results** - you'll see either a success message with details or an error message explaining what went wrong

## 🔑 API Key Formats

The application validates the following API key formats:

- **OpenAI**: `sk-...` (starts with "sk-")
- **Anthropic**: `sk-ant-...` (starts with "sk-ant-")
- **Gemini**: `AIza...` (starts with "AIza")
- **OpenRouter**: `sk-or-...` (starts with "sk-or-")

## 🌐 Supported Providers

### OpenAI
- Tests against the `/v1/models` endpoint
- Validates access to available models
- Shows count of accessible models

### Anthropic
- Tests against the `/v1/models` endpoint
- Validates API key format and permissions
- Handles CORS restrictions gracefully

### Google Gemini
- Tests against the `/v1beta/models` endpoint
- Validates API key format and permissions
- Shows available model count

### OpenRouter
- Tests with a minimal chat completion request
- Validates API key and model access
- Confirms successful connection to OpenRouter API

## 🛠️ Technical Details

- **Frontend**: Pure HTML, CSS, and JavaScript (no frameworks required)
- **API Testing**: Uses Fetch API for HTTP requests
- **Styling**: Custom CSS with modern design principles
- **Responsive**: Mobile-first design with breakpoints for different screen sizes
- **Browser Compatibility**: Works in all modern browsers

## 📱 Browser Compatibility

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 🤝 Contributing

Contributions are welcome! If you'd like to add support for additional LLM providers or improve the existing functionality, please:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📞 Support

For support, questions, or feature requests:

- **Email**: nocodetalks@gmail.com
- **GitHub**: [View on GitHub](https://github.com/nocodetalks/api-testing)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🔄 Changelog

### Version 1.0.0
- Initial release
- Support for OpenAI, Anthropic, Gemini, and OpenRouter API key testing
- Responsive design
- Client-side security implementation
- Comprehensive error handling

## ⚠️ Important Notes

- This tool is for testing purposes only
- Always keep your API keys secure and never share them publicly
- Some API providers may have CORS restrictions that prevent browser-based testing
- For production applications, always implement proper server-side API key validation
- The tool provides format validation and basic connectivity testing, but comprehensive testing should be done in your actual application environment

## 🎯 Use Cases

- **Development**: Quickly test API keys during development
- **Debugging**: Troubleshoot API key issues
- **Onboarding**: Help team members verify their API keys
- **Documentation**: Demonstrate API key setup to clients or users
- **Quality Assurance**: Validate API keys before deployment

---

Made with ❤️ by [NoCodeTalks](https://github.com/nocodetalks)
