# INTRODUCING JAM 🎶
Jam is a Music Bot for Discord, rich in taste and faster than ever!

### Jam Permission Granting
While there are no necessary permission's for user's to use command's, you do need to ensure that Jam is granted the following:
- `CONNECT` _Required for joining Voice Channel's_
- `SPEAK` _Required for Music Streaming in the Voice Channel's_
- `SEND_MESSAGES` _Required for responding to Command's_
- `USE_EXTERNAL_EMOJIS` _Required for custom emoji usage_
- `PRIORITY_SPEAKER` _Optional if you want to hear music over everyone else_

### How does Jam work?
Jam is programmed using the `yt_dlp`, `spotipy` and `ffmpeg` modules. Spotipy is required to search for tracks using a link that you provide, yt_dlp is required to convert the information of both YouTube and Spotify tracks into playable MP3 Files, and FFMPEG is required in order to play the MP3 Files via the Bot Application.

### Jam Setup
Setting up a Discord Bot has never been easier. There is no need for any fancy command's as the permissions that are granted to Jam do all of the work for you. Jam's functionality relies purely on the functions and features provided by Discord. Say goodbye to the hassle of several setup command's!

### Command List
Jam only requires a few command's to function properly, however more may be added in the future.
| Command | Description | Image
| --- | --- | --- |
| /join | Jam will join the VC that you are in. | ![image](https://github.com/user-attachments/assets/764102c6-a20a-44da-93ff-3de5324d7d13) |
| /play [source] [url] | Jam will play Music from a YouTube, Spotify, Soundcloud, Deezer or Apple Music URL. If a song is already playing, the new song will automatically be added to the queue. | ![image](https://github.com/user-attachments/assets/03d13d42-ea4a-4670-871d-dd0f82af580d) ![image](https://github.com/user-attachments/assets/ab6a7562-567c-4d35-9bbe-e65a139edb0d) |
| /clearqueue | Jam will clear the music queue completely. | ![image](https://github.com/user-attachments/assets/d8fe4e4f-9051-45db-a54d-269e38a76d41) |
| /stop | Jam will stop the current Music Track. | ![image](https://github.com/user-attachments/assets/e3690d3c-2f09-41b2-abe5-f9469c26b1c7) |
| /leave | Jam will leave the VC that it is in. | ![image](https://github.com/user-attachments/assets/64d2d9e7-d188-4268-ad3a-dc5f69974093) |
