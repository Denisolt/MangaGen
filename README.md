# Manga Gif Generator
## Project Scope:
I was interested in checking weather its possible or not to turn an anime/video </br>
into a manga/comics like template preserving the animation. </br>
Ultimately, the first thing that came into my mind was a gif. </br>
This project takes video as input and creates gifs in a folder called 'gifs' </br>
___________
## The procedure:
ffmpeg is used to decode the video, first the video is turned into frames. </br>
then, frames are extracted, resized and added into the template and new images are generated </br>
Now there are frames (images) of manga with 3 windows in them. In order to generate a gif out of them, </br>
they have to be turned into a video and then video into gif using ffmpeg. 
Note:</br>
All the generated files and directories are deleted after the gifs are generated. 
___________
## Dependancies:
ffmpeg
____________
## Execution:
This is a Jupyter Notebook, so make sure jupyter is installed on Python3. 
if they aren't:
```bash
pip install jupyter
pip install pandas
```
then:
```bash
git clone https://github.com/Denisolt/Manga_Gen.git
cd Manga_Gen-master
jupyter notebook
```
Find the .ipynb file and run it. 
___________
## My tests:
I have ran it with a [commercial of McDonalds I found on youtube](https://www.youtube.com/watch?v=ZTrC86mmPaw) </br>
The resulting gifs are:
![alt tag](https://github.com/Denisolt/MangaGen/blob/master/gifs/manga_page1.gif) </br>
![alt tag](https://github.com/Denisolt/MangaGen/blob/master/gifs/manga_page2.gif) </br>
![alt tag](https://github.com/Denisolt/MangaGen/blob/master/gifs/manga_page3.gif) </br>

_____
## What needs to be done:
The frames are still not optimized to comfortably read and understand the material. </br>
As well as, there are few issues I have faced, described in the notebook itself. </br>
Also, It would be nice to have mutliple templates and figuire out how to create bubbles with text, </br>
instead of just using subtitles.
## Credits:
Thanks to warsh for telling me about Syrians on Freenode #anime channel, who can not watch anime because of the bandwith. 
