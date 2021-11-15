# ytdl
A GUI program that runs on top of youtube-dl and ffmpeg to download videos and audio.**This project is only for educational purpose DO NOT SELL .**<br />

![ytdl2](https://user-images.githubusercontent.com/55890376/141780875-f012dce0-c85e-4b61-9d2e-def9331dbc02.jpg)


paste url and hit enter to view streams and thumbnail<br />
TO download thumbnail click **Download thumbnail**<br />
![ytd1](https://user-images.githubusercontent.com/55890376/141780921-ade41962-d4e9-4c37-9067-7d46c74547ac.jpg)



Select audio ,video and caption stream(s).<br />
Click **Browse** to browse the location where video/audio will be saved **if not clicked default browse location is downloads**<br />

<h2>Stream selection</h2>
If you have VLC not installed try selecting video with codec avc1 and audio with m4a it will work and webm audio and webm video.
If audio and video codecs are webm then output is webm else it is mp4<br />

<h4>Music</h4>
mp3 64K, mp3 320K, m4a, wav, flac available<br />
m4a,mp3 320K includes thumbnail and Metadata<br />

[watch demo here](https://user-images.githubusercontent.com/55890376/114445050-398c9100-9bed-11eb-9b17-aea0be0704d8.mp4)

<h2>INSTALLATION</h2>

Download youtube-dl GUI installer [here](https://github.com/sourabhkv/ytdl/releases)<br />
![setup](https://user-images.githubusercontent.com/55890376/118402262-c57b5800-b686-11eb-9eed-61a32933748b.JPG)<br />
![setup2](https://user-images.githubusercontent.com/55890376/118402273-d3c97400-b686-11eb-8aca-445a2d26cacc.JPG)<br />
![start](https://user-images.githubusercontent.com/55890376/118402353-3884ce80-b687-11eb-91a6-d999a675d288.JPG)<br />


Click Launch button after downloading.<br />
You are ready to go 🤘.<br />

<h2>WORKING</h2>

youtube-dl searches streams available in website and displays streams.
*sometimes there may only be only video stream(s) available or no streams at all.Using VPN might help.*
User selects streams and browse location *(default location in downloads)*.
ffmpeg converts it into videos/audios.
if m4a is selected audio format ffmpeg uses AtomicParsley to write metadata in m4a file.
Pygame window displays live download progress(for older version).<br />


[Supported Websites](http://ytdl-org.github.io/youtube-dl/supportedsites.html)<br />
[youtube-dl](https://github.com/ytdl-org/youtube-dl)<br />
[yt-dlp](https://github.com/yt-dlp/yt-dlp)<br />
[ffmpeg](https://ffmpeg.org/ffmpeg.html)<br />
[AtomicParsley](http://atomicparsley.sourceforge.net/)<br />
[Pygame](https://www.pygame.org/wiki/about)<br />
[try VLC for better playback](https://www.videolan.org/)<br />
