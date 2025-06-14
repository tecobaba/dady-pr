DaddyLive Proxy Server (Formally Pigzillaaaaa)<br>
Usual upload to hugging face etc<br>
The playlists will not download but the proxy still runs the direct urls, Using the example below<br><br>
How To Use EXAMPLE:<br>https://your.hugging.hf.space/proxy?url=https://new.newkso.ru/ddy6/***/mono.m3u8

HuggingFace Setup<br>
1, Download the docker file <a href="https://github.com/MarkMCFC/tfms.xyz/blob/main/Dockerfile">Dockerfile</a><br>
2, Now sign up for a FREE ACCOUNT - https://huggingface.co - This is going to host your proxy<br>
3, On HuggingFace look to the top‑rightish corner & click 'Spaces' Then Click 'New Space'<br>
4, Name: Enter any name you want<br>
5, Select the Space SDK: Choose 'Docker'<br>
6, Visibility: Select/Leave Public<br>
7, Click Create Space<br>
8, Click The Files Tab Then click 'Contribute' now click 'Upload Files' & upload the 'Docker file' from 'Part 1' (Drag & Drop)<br>
9, Now Click 'Commit New File To Main' (Its at the bottom) & WAIT.... for the build to say 'RUNNING'<br>
10, Click the '3 Dots' next to settings<br>
11, Choose 'Embed this Space'. It will show you the url of the space. Your own proxy url, Copy The Url & Keep Safe<br><br><br><br>

SelfHost TESTING<br>

1, Clone the repo:<br>
git clone https://github.com/MarkMCFC/tfms.xyz<br>

2, SSH into the daddy folder (which is called tfms.xyz):<br>
cd tfms.xyz<br>

3, Launch the service:<br>
docker-compose up -d --build<br>

Visit the proxy at<br>
http://localhost:7860<br>

If You Need To Install Docker On Ubuntu:<br>
snap install docker
