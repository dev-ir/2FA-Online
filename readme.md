# 2FA Code Generator
[![GitHub Pages](https://img.shields.io/badge/GitHub-Pages-blue)](https://dev-ir.github.io/2FA-Online)

A client-side Two-Factor Authentication (2FA) code generator that works like Google Authenticator, compatible with GitHub Pages.

![Screenshot](https://github.com/dev-ir/2FA-Online/blob/master/screenshot.png)

## Features

- 🚀 **Pure client-side** - No server needed, works entirely in the browser
- 🔑 **Supports all standard 2FA keys** (both spaced and unspaced formats)
- ⏱ **Real-time countdown** showing code expiration time
- 📱 **QR code generator** for easy setup in authenticator apps
- 🎨 **Clean, responsive interface** works on all devices
- 🔒 **Privacy-focused** - Your secrets never leave your browser

## How to Use

1. Enter your secret key (provided when you set up 2FA)
2. The current verification code will appear automatically
3. Optionally generate a QR code to scan with your authenticator app
4. Use the generated code wherever required

## Supported Key Formats

Both formats work:
- Standard: `ABCDEFGHIJKLMNOP`
- Spaced: `ABCD EFGH IJKL MNOP`

## Hosting on GitHub Pages

1. Upload the `index.html` file to your repository
2. Enable GitHub Pages in your repository settings
3. Select the `main` branch and root folder
4. Your 2FA generator will be live at `https://dev-ir.github.io/2FA-Online`

## Technical Details

- Built with vanilla JavaScript (no frameworks)
- Uses [OTPAuth](https://github.com/hectorm/otpauth) library for TOTP generation
- QR codes generated with [QRCode.js](https://github.com/davidshimjs/qrcodejs)
- Works with all standard TOTP implementations (Google Authenticator, Authy, etc.)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Support with Crypto 
**We don't need financial support, only Star (⭐) is enough, thank you.**
- USDT (TRC20): `TVUqVMoCEe5DVUoxmPg8MwmgcHvZLqLjr4`

## 📧 Join Telegram Channel
TG: https://t.me/+EpErnDsDPhw3ZThk