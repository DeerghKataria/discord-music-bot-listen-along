# Slash Listen-Along Discord Bot

The Slash Listen-Along Discord bot allows users to play music in voice channels using commands. It utilizes the Discord.py library and the YouTube Data API to search for and play songs from YouTube.

## Features

- Play songs from YouTube in your current voice channel
- Pause and resume the currently playing song
- Skip to the next song in the queue
- View the current music queue
- Clear the music queue
- Disconnect the bot from the voice channel

## Requirements

- Python 3.7 or higher
- discord.py library
- youtube_dl library

## Installation

1. Clone this repository to your local machine.
2. Install the required dependencies using the following command:

pip install -r requirements.txt


3. Obtain a Discord bot token by creating a new bot on the Discord Developer Portal.
4. Set the bot token as an environment variable named `TOKEN`. You can do this by creating a `.env` file in the root directory of the project and adding the following line:

TOKEN=your_bot_token_here


5. Run the bot by executing the following command:

python main.py


## Usage

1. Invite the bot to your Discord server using the OAuth2 URL generated in the Discord Developer Portal.
2. Connect to a voice channel in your server.
3. Use the following command to play a song:

//play <keywords>


Replace `<keywords>` with the desired song or video keywords to search on YouTube.

4. Use other available commands such as `//skip`, `//pause`, `//resume`, `//queue`, `//clear`, and `//leave` to manage the music playback and queue.

## Contributing

Contributions are welcome! If you encounter any issues or have suggestions for improvements, please open an issue on the GitHub repository.

## License

This project is licensed under the [MIT License](LICENSE).

Feel free to customize the content according to your specific bot and requirements.