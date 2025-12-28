# React + Tailwind CSS Chatbot Project

This is a unified project that combines React and Tailwind CSS for a modern, responsive chatbot interface.

## 🚀 Quick Start

### For the Chatbot (HTML):
1. Open `public/chatbot.html` in your browser or live server
2. The chatbot will work with full Tailwind CSS styling
3. All Tailwind classes are automatically included

### For React Development:
1. `npm start` - Start React development server
2. `npm run css` - Build Tailwind CSS once
3. `npm run watch:css` - Watch for CSS changes and auto-rebuild
4. `npm run dev` - Build CSS and start React server

## 🎨 Tailwind CSS

- **Input**: `src/index.css` (contains Tailwind directives)
- **Output**: `public/tailwind.css` (compiled CSS)
- **Config**: `tailwind.config.js` (Tailwind configuration)

## 📁 Project Structure

```
my-react-ts-app/
├── src/
│   ├── index.css          # Tailwind directives + custom styles
│   ├── App.tsx            # Main React component
│   └── ...
├── public/
│   ├── chatbot.html       # Standalone chatbot with Tailwind
│   ├── tailwind.css       # Compiled Tailwind CSS
│   └── ...
├── tailwind.config.js     # Tailwind configuration
└── package.json           # Dependencies and scripts
```

## 🔧 Available Scripts

- `npm start` - Start React dev server
- `npm run css` - Build Tailwind CSS
- `npm run watch:css` - Watch and auto-rebuild CSS
- `npm run build:css:prod` - Build minified CSS for production
- `npm run dev` - Build CSS + start React server

## ✨ Features

- **Unified Setup**: React + Tailwind in one project
- **Standalone Chatbot**: Works independently with `chatbot.html`
- **Modern UI**: Beautiful, responsive design with Tailwind
- **Easy Development**: Simple commands for both React and CSS
- **Live Reload**: CSS automatically rebuilds on changes

## 🎯 Usage

1. **For Chatbot**: Just open `chatbot.html` - it's fully styled and ready!
2. **For React**: Use `npm start` for development
3. **For CSS Changes**: Use `npm run watch:css` to auto-rebuild

Your chatbot now has perfect Tailwind CSS integration! 🎉
