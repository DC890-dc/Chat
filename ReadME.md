# Discord Clone - Friends Chat

A lightweight, real-time chat application built with vanilla JavaScript that mimics Discord's UI and functionality.

## Features

✨ **Real-Time Updates** - Messages appear instantly across all open tabs without page refresh  
🔐 **Secure Authentication** - PIN-based login system with subscription management  
💾 **Session Persistence** - Automatically logs you back in after page reload  
📱 **Responsive Design** - Discord-like dark theme with sidebar and channels  
🎨 **User Differentiation** - Each user has a unique color and avatar  
📝 **Multi-Channel Support** - Switch between #general, #announcements, and #off-topic  
⌨️ **Quick Send** - Press Enter to send messages, Shift+Enter for new line  

## Getting Started

1. **Open the app** - Simply open `code.html` in your browser
2. **Select your identity** - Choose your name from the dropdown
3. **Enter your PIN** - Use one of the predefined test credentials below
4. **Start chatting** - Messages sync across all open tabs in real-time

## Test Credentials

| Username | PIN | Status |
|----------|-----|--------|
| Dev | 18234567890 | ✅ Active |
| Alex | 2222 | ✅ Active |
| Sam | 3333 | ❌ Inactive |
| Jordan | 23234 | ✅ Active |
| Sparsh | 8874 | ✅ Active |
| Drake | 7777 | ✅ Active |
| Fali | 8888 | ✅ Active |
| John | 9999 | ✅ Active |
| GoodBoi | 0000 | ✅ Active |

*(Inactive accounts cannot send messages)*

## How It Works

- **Local Storage** - All messages are stored in your browser's localStorage
- **Real-Time Polling** - Updates check every 500ms for new messages
- **Cross-Tab Sync** - Open multiple browser tabs to see messages sync in real-time
- **Session Storage** - Your login persists even after closing and reopening the page
- **Security** - Message content is sanitized to prevent injection attacks

## Usage

### Sending Messages
- Type your message and press **Enter** to send
- Use **Shift+Enter** to write multi-line messages
- Maximum message length: 2000 characters

### Channels
- Click on any channel in the sidebar to switch between conversations
- Each channel maintains separate message threads

### Logout
- Click the **Logout** button to clear your session and return to login

## Files

- `code.html` - Complete standalone chat application
- `.gitignore` - Git configuration for version control
- `README.md` - This documentation file

## Technology Stack

- **Frontend**: Vanilla JavaScript (no frameworks)
- **Storage**: Browser localStorage API
- **Styling**: Bootstrap 5 + Custom CSS
- **Icons**: Bootstrap Icons

## Browser Support

Works on all modern browsers that support:
- ES6 JavaScript
- localStorage API
- CSS Flexbox

Tested on: Chrome, Firefox, Safari, Edge

## Notes

- Messages are stored locally in your browser only - they don't sync to a server
- Clearing browser data will delete all messages
- Perfect for local team chat, testing, or development
- No backend or database required

## Future Enhancements

- 🔄 Backend server integration for persistent storage
- 👥 Direct messaging between users
- 📎 File sharing support
- 🎙️ Voice/video chat
- ⚙️ User profiles and settings
- 🔔 Notifications and mentions
- 📅 Message timestamps with relative time

## License

Free to use and modify for personal and educational purposes.

---

**Enjoy your Discord clone!** 💬
