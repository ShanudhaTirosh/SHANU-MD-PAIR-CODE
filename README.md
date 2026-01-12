# 🤖 Shanu Bot - WhatsApp Pairing Code Generator

A web-based session generator for Shanu WhatsApp Bot. Generate your pairing code instantly and connect your bot to WhatsApp Web.

---

## 🚀 Quick Start

Get your bot up and running in 3 simple steps:

### **Step 1: Generate Your Pairing Code**

Click the button below to access the pairing code generator:

[![Generate Pair Code](https://img.shields.io/badge/Generate%20Pairing%20Code-Click%20Here-brightgreen?style=for-the-badge&logo=whatsapp)](https://knight-bot-paircode.onrender.com)

### **Step 2: Set Up Mega.nz Storage**

Your bot uses Mega.nz to securely store session data.

1. **Create a free Mega.nz account:**  
   [![MEGA - Sign Up](https://img.shields.io/badge/MEGA-Create%20Free%20Account-red?style=flat&logo=mega&logoColor=white)](https://mega.nz/register)

2. **Configure your credentials** in `mega.js`:

```javascript
// mega.js
const auth = {
  email: 'your-email@mega.nz',
  password: 'your-secure-password',
  userAgent: 'Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36'
};
```

### **Step 3: Deploy Your Bot**

Deploy the bot to a hosting service:

[![Deploy to Render](https://img.shields.io/badge/Deploy%20to%20Render-46E3B7?style=for-the-badge&logo=render&logoColor=white)](https://render.com)

---

## 📱 How to Connect

1. Visit the pairing code generator link
2. Enter your WhatsApp phone number (with country code)
3. Click "Generate Code"
4. Open WhatsApp on your phone
5. Go to **Settings → Linked Devices → Link a Device**
6. Enter the 8-digit pairing code
7. Your bot is now connected! 🎉

---

## 🔧 Configuration

### Environment Variables

Set these variables in your hosting platform:

```env
MEGA_EMAIL=your-email@mega.nz
MEGA_PASSWORD=your-password
```

### Security Notes

- Never share your pairing code publicly
- Keep your Mega.nz credentials secure
- Use a strong password for your Mega account
- Regenerate codes if compromised

---

## 💡 Features

- ✅ Instant pairing code generation
- ✅ Secure session storage with Mega.nz
- ✅ Easy deployment process
- ✅ No QR code scanning needed
- ✅ Multi-device support

---

## 🆘 Troubleshooting

**Code not working?**
- Ensure you entered the correct phone number with country code
- Try generating a new code
- Check your internet connection

**Bot not responding?**
- Verify Mega.nz credentials are correct
- Check deployment logs for errors
- Ensure the bot service is running

---

## 📞 Support

Having issues? Need help?

- Open an issue on GitHub
- Check existing issues for solutions
- Contact the maintainer

---

## ⚠️ Disclaimer

This bot is for educational purposes. Use responsibly and comply with WhatsApp's Terms of Service.

---

## 📄 License

This project is open source and available under the MIT License.

---

**Made with ❤️ for the WhatsApp Bot Community**