# RC-Terminal Portfolio

**[Link](https://www.ramanchaudhary.com.np)**

A modern, interactive terminal-style portfolio website built with Next.js, featuring both terminal and visual interface modes.

## 🚀 Features

### Dual Interface Modes
- **Terminal Mode**: Interactive command-line interface with real terminal experience
- **Interface Mode**: Modern web UI with dark theme and responsive design
- Seamless switching between modes with persistent state

## Terminal
![alt text](img/image.png)

### Terminal Features
- Real-time command execution with typing effects
- Command history and autocompletion
- Variable assignment and data manipulation
- Print functionality for generating PDFs
- Session-based state persistence

## Interface
![alt text](img/image-2.png)

### Interface Features
- Responsive gallery with keyboard navigation
- Interactive feedback form
- Mobile-optimized layout (2 images per row on mobile)
- Dark theme with professional styling

## 🛠️ Tech Stack

- **Framework**: Next.js 14 with TypeScript
- **Styling**: Tailwind CSS with custom dark theme
- **UI Components**: Custom components with shadcn/ui
- **State Management**: React hooks with session storage
- **Icons**: Lucide React

## 📁 Project Structure

```
src/
├── components/            # React components
│   ├── Terminal.tsx       # Terminal interface
│   ├── InterfaceView.tsx  # Visual interface
│   └── FeedbackForm.tsx   # Contact form
├── data/                  # JSON data files
├── hooks/                 # Custom React hooks
├── lib/                   # Utilities and command handler
└── app/                   # Next.js app router
```

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/RmnRj/RC-Terminal.git
   cd RC-Terminal
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Run the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:9002`

## 💻 Terminal Commands

| Command | Description |
|---------|-------------|
| `help` | Show all available commands |
| `open(section)` | Open specific sections (projects, skills, etc.) |
| `downloadCV` | Download CV/Resume PDF file |
| `printCopy(sections)` | Generate PDF of selected sections |
| `clear` | Clear terminal screen |
| `interface` | Switch to visual interface mode (preserves history) |
| `varName -> command` | Store command output in variable |

## 🎨 Features Showcase

- **Responsive Design**: Works seamlessly on desktop and mobile
- **Keyboard Navigation**: Full keyboard support in gallery and terminal
- **Print Functionality**: Generate clean PDFs of portfolio sections
- **Real-time Feedback**: Interactive forms with validation
- **Command Autocompletion**: Smart command and argument suggestions

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

**Built with ❤️ by Raman** | [GitHub](https://github.com/RmnRj) | [LinkedIn](https://linkedin.com/in/rmnrj)
