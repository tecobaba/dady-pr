<b>DaddyLive Proxy Server (Formally Pigzillaaaaa) - WORKING Install on huggingface or local to get it working.</b><br>

EXAMPLE HOW TO USE URL<br>
https://your.hugging.hf.space/playlist/channels<br>
https://your.hugging.hf.space/playlist/events - Events List Will NOT UPDATE<br>
OR<br>
https://your.hugging.hf.space/proxy?url=https://new.newkso.ru/ddy6/***/mono.m3u8<br>
See the list.of.direct.urls.txt or json file for the direct stream urls<br><br>
===========================================================================<br><br>
<b>QUICK SETUP GUIDE<br>
Sign-in/up to huggingface first - https://huggingface.co</b><br>

Click the url below then Click the 3 dots (top right side) & select <b>'Duplicate this space'</b><br>
Give it a <b>Name</b> and change it to <b>Public</b><br>
https://huggingface.co/spaces/dadproxy-tfms-xyz/tfms-xyz-newworkingdad<br>

<b>When the build says running</b><br>
Click the '3 Dots' next to settings<br>
Choose 'Embed this Space'. It will show you the url of the space. Your own proxy url, Copy The Url & Keep Safe<br>

EXAMPLE HOW TO USE URL, Load into a browser to download the playlist<br>
https://your.hugging.hf.space/playlist/channels<br>

===========================================================================<br><br>
<b>HuggingFace Self Setup for more advanced users</b><br>

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
===========================================================================<br><br>
<b><u>Self Hosting Tested & Working on Ubuntu20</u></b><br>Note: The playlists do not download when your are self hosting you will need to use the urls from here - (https://dadurls.netlify.app/)<br>

1, Clone the repo:<br>
git clone https://github.com/MarkMCFC/tfms.xyz<br>

2, SSH into the daddy folder (which is called tfms.xyz):<br>
cd tfms.xyz<br>

3, Launch the service:<br>
docker-compose up -d --build<br>

Visit the proxy at<br>
http://localhost:7860<br>
http://localhost:7860/proxy?url=https://new.newkso.ru/ddy6/***/mono.m3u8<br>
You can also use the urls from the quick setup guide above<br><br>
===========================================================================<br><br>
If You Need To Install Docker On Ubuntu:<br>
snap install docker<br><br>
===========================================================================<br><br>
<b>Full credit must go to:</b> <b><u>Pigzillaaaaa</u></b><br><br>
See Forum, Join Up! Plenty of goodies will be offered - https://forum.tfms.xyz<br>
Join our discord: https://discord.gg/F3MzfJAffG (#iptv)
