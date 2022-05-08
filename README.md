# Convert Spotify Playlist to YouTube Playlist

A program I created in order to convert your Spotify Playlist to a YouTube Playlist.
- Uses the YouTube Data API in order to automate creating a playlist and adding the videos/songs into the playlist.
- Uses the spotipy library to retrieve the songs that are in one of your playlists that you selected to be converted.


## How to run locally
1. Create an application/project within both the Spotify Developers Console and Google Developers Console.
2. You then have to retrieve the client id and client secret from the Spotify Dashboard and retrieve the client id, client secret, and API key from the Google Developers Console.
3. Input your Spotify client id and client secret into the secrets.json file.
4. Input the Google client id, client secret, and API key into the client_secrets.json file.


## Demo of program with a short Spotify playlist that I created.
1. The program first asks you to visit a URL to authorize the application with oauth2, and you have to enter in an authorization code:
![image](https://user-images.githubusercontent.com/90528127/137650570-9ed85c77-40f0-4189-9b3e-e2021b409f62.png)

2. It then asks for the Spotify playlist URL link for which you would like to convert to a Youtube playlist.
![image](https://user-images.githubusercontent.com/90528127/137650605-ec2bd04c-3851-4c2d-96c3-d959cf2ecce5.png)

3. The program will then print that it found the spotify songs and that it is adding the Youtube video of that song.
![image](https://user-images.githubusercontent.com/90528127/137650642-b5f75de8-b106-4c10-87ab-9a3d3bb3b497.png)

4. You can then check your Youtube playlists and the playlist with all of the songs from that playlist will appear.
![image](https://user-images.githubusercontent.com/90528127/137650685-472c2b4a-6d92-4696-976d-a3b3899d3197.png)
