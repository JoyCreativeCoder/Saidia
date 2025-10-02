# Saidia - AI Teacher's Assistant

Saidia is an AI-powered desktop application designed to empower educators in low-connectivity regions with powerful AI capabilities. It provides an intuitive interface for uploading documents and automatically generating various types of questions - all running locally on your device without requiring internet connectivity.

<img width="1697" height="1198" alt="Screenshot 2025-08-02 at 10 49 33 am" src="https://github.com/user-attachments/assets/54a7d824-faad-478c-8c9d-220005ebb74e" />

[How it works](https://www.youtube.com/watch?v=kvl7-pNIIQc)

## 🚀 Features

- **🌐 Offline-First Design**: Works completely offline - perfect for low-connectivity regions
- **📚 Document Upload**: Support for multiple file formats (PDF, DOC, DOCX, TXT, MD, ODT)
- **🤖 AI-Powered Question Generation**: Automatically generates questions from uploaded materials
- **📝 Multiple Question Types**: Multiple choice, true/false, and fill-in-the-blank questions
- **📊 Difficulty Levels**: Easy, medium, and hard difficulty settings
- **📁 Subject Organization**: Organize materials and questions by subject
- **💻 Local AI Processing**: Uses Ollama for on-device AI processing - no cloud dependencies
- **🖥️ Cross-Platform**: Works on Windows, macOS, and Linux
- **🔒 Privacy-First**: All data stays on your device - no data sent to external servers

### Ideal Use Cases:

- **Rural Schools**: Where internet connectivity is unreliable
- **Remote Classrooms**: Areas with limited infrastructure
- **Budget-Conscious Institutions**: Avoiding cloud service costs
- **Privacy-Focused Environments**: Where data security is paramount

  ## 🧩 My Role & Contributions
- Led the frontend in **React + Electron + Mantine**, delivering a clean, responsive UI.
- Built key features: **question editing**, **bulk selection with checkboxes**, and **printable modal views**.
- Collaborated on integrating **Ollama** and **Gemma 3n** for fully offline Q&A.
- Optimized UX and performance for **low-spec devices** and unreliable connectivity.


## 📖 Documentation

For detailed technical information about the project architecture, implementation details, and development decisions, see the [Technical Writeup](technical-writeup.md).

## 👥 Authors

- **Joy** - [LinkedIn](https://www.linkedin.com/in/joy-nk/)
- **Udo** - [LinkedIn](https://www.linkedin.com/in/thisisudo/)

## 🆘 Troubleshooting

### Common Issues

**Ollama not found:**

- Ensure Ollama is installed and running
- Check that the required models are pulled

**Build errors:**

- Clear node_modules and reinstall: `rm -rf node_modules && npm install`
- Ensure you're using the correct Node.js version

**Electron build issues:**

- On macOS, you may need to install Xcode Command Line Tools
- On Windows, ensure you have Visual Studio Build Tools

**Offline usage:**

- Once models are downloaded, the app works completely offline
- No internet connection required for question generation or document processing
- All data is stored locally on your device

---

Built with ❤️ for educators everywhere.
