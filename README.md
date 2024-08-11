
# 🎵 Music Tag and Cover Art Editor Bot

This is a **Telegram bot** built with **Pyrogram** that allows users to upload music files and edit their tags (metadata) and cover art before sending them back. This bot is perfect for users who want to ensure their music files have correct metadata and appealing cover art. 🌟

## ✨ Features

- 🏷 **Edit Audio Tags**: Supports editing of various audio tags including title, artist, album, year, genre, and cover art.
- 🎨 **Cover Art**: Easily upload and set custom cover art for your music files.
- 🔐 **Secure Access**: Authorized user access control ensures security.
- 🗑 **Automatic Cleanup**: Automatically deletes temporary files after processing.
- 😄 **Fun Interface**: Incorporates random emojis for an enjoyable user experience.

## 🚀 Getting Started

### Prerequisites
Ensure you have the following installed:
- **Python 3.x**
- **Telegram Bot API credentials**

### Installation

1. **Clone the Repository**: 
   ```bash
   git clone https://github.com/ariyagoudarzi/music-tag-editor-bot.git
   ```

2. **Navigate to the Project Directory**: 
   ```bash
   cd music-tag-editor-bot
   ```

3. **Install Dependencies**: 
   ```bash
   pip install -r requirements.txt
   ```

4. **Configure the Bot**: 
   - Set up your **Telegram Bot API credentials** in the `music.py` file.

5. **Run the Bot**: 
   ```bash
   python music.py
   ```

6. **Interact with the Bot**: 
   - Start chatting with the bot on Telegram and follow the instructions to edit your music tags and cover art.

## 📂 Project Structure

```bash
music-tag-editor-bot/
├── music.py              # Main bot script
├── requirements.txt      # Required Python packages
├── database.py           # Database management script
├── user_database.db      # SQLite database for storing user data
├── chnl.png              # Example cover art image
├── error.log             # Log file for errors
├── chat_ids.txt          # Authorized users' chat IDs
└── README.md             # Project documentation
```

## 🤝 Contribution

Contributions are welcome! Feel free to submit a pull request or open an issue to improve the project.

1. Fork the project.
2. Create a new branch.
3. Make your changes and commit them.
4. Push to your branch and submit a PR.

## All Features

- You can allow your specific people to use the robot, for this you can change the list of IDs allowed to use the robot in the config.ini file.
- The robot will put your Instagram channel or page ID in almost all the robot tags so that you can rest assured that everyone will know that you edited this song. To change it, you can refer to the codes related to the edit tag and see that, for example, I put my Telegram channel ID.
- The robot takes the photo you send to the size of 1080x1080 and puts your logo, which is chnl.png file, on it with a ratio of one eighth.
- The robot will automatically set the year you are in as the date of the song, but in the next versions I will provide the ability to set it manually.

## 📜 License

This project is licensed under the MIT License.

---

🎶 **Enjoy Editing Your Music Tags!** 🎧
