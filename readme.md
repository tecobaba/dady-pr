DaddyLive Proxy Server (Formally Pigzillaaaaa)<br>
Usual upload to hugging face etc<br>
<b>The playlists will not download but the proxy still runs the direct urls, Using the example below</b><br><br>
How To Use EXAMPLE:<br>
https://your.hugging.hf.space/proxy?url=https://new.newkso.ru/ddy6/***/mono.m3u8<br>
See the json file for the stream urls,br>or use the urls from the quick setup guide below<br>

<b>HuggingFace Setup</b><br>
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
11, Choose 'Embed this Space'. It will show you the url of the space. Your own proxy url, Copy The Url & Keep Safe<br><br>
====================================================================================<br>
<b>Quick Setup on huggyface</b><br>
The easiest way to get pigzilla/daddylive 'Proxy' (see the huggingface url below) and click the 3 dots next to settings and select 'Duplicate Space' Give it a 'Name' & change it from 'Private to Public'<br>
https://huggingface.co/spaces/markmcfc/testerrer<br><br>
To get the Stream urls in an m3u list see here<br>
https://dadurls.netlify.app/<br>
====================================================================================<br><br>
<b><u>Self Hosting Tested & Working on Ubuntu20</u></b><br>

1, Clone the repo:<br>
git clone https://github.com/MarkMCFC/tfms.xyz<br>

2, SSH into the daddy folder (which is called tfms.xyz):<br>
cd tfms.xyz<br>

3, Launch the service:<br>
docker-compose up -d --build<br>

Visit the proxy at<br>
http://localhost:7860<br>
http://localhost:7860/proxy?url=https://new.newkso.ru/ddy6/***/mono.m3u8<br>

If You Need To Install Docker On Ubuntu:<br>
snap install docker<br><br>
<b>Full credit must go to:</b> <b><u>Pigzillaaaaa</u></b>
