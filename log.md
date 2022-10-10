---
tutorial: TWINE 
---

The biggest technical difficulty I faced was when creating my Twine story "The Odyssey" with my partner in class. The storyline was based around the pov of hero Odysseyus on his return home to Ithaca from the Trojan War. I learned how to create a healthbar (set: $Health to 5) Healthbar: (print: $Health) since our storyline was based on the consequences of the choices the user made which would affect their progression in the game and whether or not they'd reach Ithaca, the final destination.

I had read a background on Twine that was provided before class ("# [Interactive Fiction in the Humanities Classroom: How to Create Interactive Text Games Using Twine](https://programminghistorian.org/en/lessons/interactive-text-games-using-twine)") which helped me with creating the passages, adding multimedia links, the concept of "meaningful choices," which has the same application in life and games, as well as understanding macros, html language and the Twine stylesheet. 

However, I had trouble with adding audio to my Twine story. I realized that my story format was set to Harlowe 3.3.3 and luckily, someone in the Discord chat had mentioned that their was a surefire way to change the story format from **Story > details > Story Format** to SugarCube. 

Link to message: https://discord.com/channels/1019687051286814851/1019688433091870831/1026575863359225946

I was using SugarCube macros based on advice give from the following webpage: [

[Twine media (adamhammond.com)](http://www.adamhammond.com/wp-content/uploads/2016/03/hammond_twineguide_4_imagesmusic.pdf#:~:text=Adding%20media%20to%20your%20Twine%20game%20is%20as,you%20like%2C%20and%20then%20click%20on%20%22View%20Image.%22)

I was using the same folder 'The Odyssey' that I had used to add images to my Twine story, courtesy advice given by Dr. Graham and another classmate via Discord. I created a new passage called Variables, a special passage that executes all the commands before showing the player the first passage of the game and isn't linked to any other passages. I used this space to load my song. 

I used the following code to add two images to my Twine story: 

![[Pasted image 20221009163359.png]]

I then used <<audio hero play>> and inserted it into the passage I wanted the music to play from. I exported the html and dropped it into my folder, but the audio did not play. 

I then decided to use Harlowe-specific macros, thanks to the tutorial game made by Dr. Graham which was my reference point: 

https://discord.com/channels/1019687051286814851/1019688433091870831/1025854474503335936

I created a separate passage called hal.tracks and wrote down the following code: 

hero: ./music/hero.mp3

I then added (track: 'hero', 'play')] into my main passage as introductory music. Unfortunately, even when I exported the file, my music was still not playing. I read in the following online forum that I needed javacript to make harlowe work, but my laptop's Microsoft Edge did not support JavaScript due to being denied administrative access. 

[Playing audio in Harlowe (Twine 2.0) - Twine Forum (twinery.org)](https://twinery.org/forum/discussion/5528/playing-audio-in-harlowe-twine-2-0)


## how it might connect to other research I'm doing

I loved reading books/playing games that let the reader be in charge of the storyline and have the ability to choose how the protagonist would act in certain situations, which leads to alternative ending. The fact that we can make an epic poem interactive generates interest in the actual work. I hope to apply Twine in my Unessay.

TUTORIAL: MURAL 

I created a mural webpage for my visual narrative "Celebrating the Tagwàgi (Fall) Festival at Madahòkì Farm," a description of "my visit to the annual Tagwagi Festival, where we were all given the opportunity to reconnect with the land while learning about Indigenous traditions by witnessing a pow wow, shopping from an Indigenous Makers and Farmers Market, and meeting the rare Ojibwe Spirit Ponies."

I was able to add a full page, 1 minute video, text, picture with a caption, as well as a background video to my mural. I had some difficulties in sizing my video so that it fit the full-screen, but I just cropped my video and it turned out fine. 

I used the information provided on the Discord channel to help me create my mural since I was absent from class that day. I had no difficulty downloading mural from Github as well. 

## how it might connect to other research I'm doing

It's a contest between Twine (for my love of digital, interactive storytelling) and Mural (for visual asthetics) for my Unessay since I love capturing images of revelant moments and compiling them together to tell a story as a young photojournalist. 


