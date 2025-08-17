# 📓 Notevia Diary SexrPro

**Notevia Diary SexrPro** is a cutting-edge, encrypted journal application designed for privacy-focused users who value elegance, speed, and control. With a tabbed interface inspired by code editors, multi-user support, and end-to-end encryption, Notevia is your secure space to write, reflect, and organize your thoughts.

---

## 🚀 Features

- 🔐 **End-to-End Encryption**  
  Your entries are encrypted locally using AES-256 before storage or sync.

- 🧑‍🤝‍🧑 **Multi-User Profiles**  
  Each user has isolated data, customizable themes, and secure login.

- 📑 **Tabbed Entry System**  
  Switch between multiple open entries with a sleek tabbed layout.

- 🖋️ **Markdown & Rich Text Editor**  
  Write with full formatting support, including code blocks, lists, and images.

- 🌙 **Dark Mode & Custom Themes**  
  Choose from built-in themes or create your own with CSS variables.

- 📱 **Cross-Platform Support**  
  Works on Windows, macOS, Linux, Android, and iOS.

- 🧠 **Smart Search & Tagging**  
  Filter entries by tags, keywords, or dates with blazing-fast search.

- 📂 **Local & Cloud Sync**  
  Choose between local-only mode or encrypted cloud backup.

- 🔄 **Version History**  
  Restore previous versions of entries with a built-in timeline.

- 🧩 **Plugin System**  
  Extend functionality with plugins for calendar, reminders, voice notes, and more.

- 🔔 **Notifications & Reminders**  
  Set reminders for journaling or specific entries.

- 🔒 **Biometric Login (Optional)**  
  Use fingerprint or face recognition for quick access.

---

## 📦 Installation

### Requirements

- Node.js >= 18
- npm or yarn
- SQLite or MongoDB (configurable)
- Optional: Docker for containerized deployment

### Steps

```bash
git clone https://github.com/yourusername/notevia-diary-sexrpro.git
cd notevia-diary-sexrpro
npm install
npm run dev
```

To build for production:

```bash
npm run build
```

---

## 🛠️ Configuration

Create a `.env` file in the root directory:

```env
PORT=3000
DB_URI=mongodb://localhost:27017/notevia
ENCRYPTION_KEY=your-super-secret-key
SESSION_SECRET=another-secret-key
SYNC_MODE=local # or cloud
```

---

## 🧪 Testing

Run unit and integration tests:

```bash
npm run test
```

Use `jest` or `vitest` for test coverage reports.

---

## 📁 Folder Structure

```
notevia-diary-sexrpro/
├── src/
│   ├── components/
│   ├── pages/
│   ├── utils/
│   ├── styles/
│   └── services/
├── public/
├── tests/
├── .env
├── package.json
└── README.md
```

---

## 📚 Documentation

Full documentation is available in the `/docs` folder or at [notevia-docs.com](https://notevia-docs.com) *(placeholder)*.

Includes:

- API Reference
- Plugin Development Guide
- Theme Customization
- Security Architecture

---

## 🧠 Philosophy

Notevia Diary SexrPro was built with the belief that privacy is a right, not a feature. Your thoughts deserve a space that’s secure, elegant, and empowering. Whether you're journaling daily, documenting your creative process, or managing sensitive notes, Notevia gives you full control.

---

## 🛡️ Security

- AES-256 encryption for all entries
- Optional biometric login
- Encrypted cloud sync with zero-knowledge architecture
- Session management with JWT and refresh tokens
- Regular security audits and open-source transparency

---

## 🌐 Internationalization

Notevia supports multiple languages including:

- English
- Spanish
- Portuguese
- French
- German
- Japanese
- Arabic

You can contribute translations via the `/i18n` folder.

---

## 🤝 Contributing

We welcome contributions! Fork the repo, create a feature branch, and submit a pull request.

```bash
git checkout -b feature/my-awesome-feature
```


---

## 📢 Roadmap

- [x] Tabbed interface
- [x] Multi-user support
- [x] Encryption
- [x] Markdown editor
- [ ] Voice note plugin
- [ ] Calendar integration
- [ ] Offline-first mobile app

---

## 🧑‍💻 Built With

- Java JDK 21-24 (No maven)

---

## 📜 License

This project is licensed under the MIT License. See the Mit file for details.

---

## 💬 Contact

For questions, feedback, or support:

- GitHub Issues
- Email: gabriel643xd@gmail.com


---

## 🌟 Acknowledgments

- Inspired by VS Code, Obsidian, and Standard Notes and my  own Notevia SexrPro anti overload
- Thanks to all open-source contributors
- Special shoutout to the privacy-first community

---

**Notevia Diary SexrPro** — *Your thoughts, encrypted. Your mind, empowered.*
