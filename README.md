# ytdl
A GUI program that runs on top of yt-dlp and ffmpeg to download videos and audio.**This project is only for educational purpose DO NOT SELL . USE AT YOUR RISK .**<br />

![ytdl new 1](https://user-images.githubusercontent.com/55890376/143569133-6d465e8f-b632-4cc1-b093-2adc76c03fcf.jpg)



paste url and hit enter/GO to view streams and thumbnail<br />
TO download thumbnail click **Download thumbnail**<br />
![ytdl new 2](https://user-images.githubusercontent.com/55890376/143569182-896f5646-3ae4-40d2-b027-cb5a01a998d1.jpg)




Select audio ,video and caption stream(s).<br />
Click **Browse** to browse the location where video/audio will be saved **if not clicked default browse location is downloads**<br />

<h2>Stream selection</h2>
If you have VLC not installed try using these combination.
Recommended combination of audio and video codecs<br />
MP4 -->   video: avc1 & audio: m4a <br />
WEBM -->  video: webm & audio :webm  **This combination does not support embeded subtitles**<br />
NOTE : If audio and video codecs are webm then output is webm else it is mp4<br />

<h4>Music</h4>
mp3 64K, mp3 320K, m4a, wav, flac available<br />
m4a,mp3 320K includes thumbnail and Metadata<br />
flac , wav formats takes more space than mp3 and m4a
<br />
New version demo[watch demo here](https://drive.google.com/file/d/1OaQTnjXC8wvLKSkWYx_8j8pEyUu7IYXq/view?usp=sharing)</br>

Older version [watch demo here](https://user-images.githubusercontent.com/55890376/114445050-398c9100-9bed-11eb-9b17-aea0be0704d8.mp4)</br>

<h2>INSTALLATION</h2>

Download youtube-dl GUI latest installer [here](https://github.com/sourabhkv/ytdl/releases/latest)<br />

![ytdl3](https://user-images.githubusercontent.com/55890376/141781730-445d6ec8-fb01-4d82-a45c-8f182d08b8a3.jpg)

![ytdl4](https://user-images.githubusercontent.com/55890376/141781775-ca0e0b5d-d869-403d-aba4-30a1c448767e.jpg)

![ytdl5](https://user-images.githubusercontent.com/55890376/141781804-461d41f5-4f6c-487d-92f7-74fa28d92e01.jpg)

![ytdl6](https://user-images.githubusercontent.com/55890376/141781963-69e2b0e4-c0bc-4996-8491-d5244c314010.jpg)




Click Launch button after downloading.<br />
You are ready to go 🤘.<br />

<h2>WORKING</h2>

yt-dlp (youtube-dl for older version) searches streams available in website and displays streams.
*sometimes there may only be only video stream(s) available or no streams at all.Using VPN might help.*
User selects streams and browse location *(default location in downloads could be changed)*.
ffmpeg converts it into videos/audios.
if m4a is selected audio format ffmpeg uses AtomicParsley to write metadata in m4a file.
Pygame window displays live download progress(for older version).<br />

<h2>How development started and was carried?</h2>
This project development started with wish to download youtube physics video(Center of mass) at 240p in March,2021 because 240p quality was managable and took decent amount of data compared to 360p.</br>
Initially it was a very basic program which lack many features as time passed encountered many bugs and fixed it specially giving the live download progress in main window statusbar took almost 2 months to fix this , black console screen at startup also was challenging to fix without using --noconsole option</br>
Threading helped execute many function at same time</br>
The function popens(cmd) never executed with object oriented programming</br>
Tkinter was easy to use and took less space compared to PySide2/PyQt5</br>
After june,2021 there was no update to youtube-dl. Development stopped for 3 months finally backend changed to yt-dlp</br>
During this development period many bugs were encountered and fixed , many features were added hope this project will be active in future...</br>
Need help to make this better so that everyone who has poor internet connctivity can learn somthing.</br>

<br></br>
<h2>Useful links</h2>
<br></br>
[Supported Websites](http://ytdl-org.github.io/youtube-dl/supportedsites.html)<br />
[youtube-dl](https://github.com/ytdl-org/youtube-dl)<br />
[yt-dlp](https://github.com/yt-dlp/yt-dlp)<br />
[ffmpeg](https://ffmpeg.org/ffmpeg.html)<br />
[AtomicParsley](http://atomicparsley.sourceforge.net/)<br />
[Pygame](https://www.pygame.org/wiki/about)<br />
[try VLC for better playback](https://www.videolan.org/)<br />
