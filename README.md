# Terminal Chat v2.0

A minimal terminal-style chat application with real-time messaging and unique room URLs.

## Features
- Terminal-like UI with green text on black background
- **Real-time messaging** - Chat with friends instantly
- **Unique room URLs** - Each session gets a unique room ID
- Username customization with `/nick <name>`
- Clear local chat with `/clear`
- Room info with `/room`

## Usage
1. Visit https://pre04.github.io/terminal-chat/
2. App automatically creates a unique room URL (e.g., `?room=abc123`)
3. Share the full URL with friends to join the same chat room
4. Type messages and press Enter to chat in real-time

## Commands
- `/nick <name>` - Change username
- `/clear` - Clear local chat history
- `/room` - Show current room info and shareable URL

## How it works
- Each visit creates a unique room ID
- Friends using the same URL join the same chat room
- Messages are shared in real-time via WebSocket
- No registration required - just share the URL!
