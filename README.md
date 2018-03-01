# Audio Bible
I am Manav Lakhwani and i'm doing a research for my University project on how to create an Audio Bible document correctly when designing a game. 

## What is an Audio Bible?
An Audio Bible is a document that containes the main audio clips and the general idea of how the sound is going to be in the videogame you are developing. The objective is for the person reading it to understand how the sounds and music will be perfomed in every aspect of the game; the environment, the style, the genre, the character voice and animations, etc, and for that, the document must be very descriptive, specially as the audio is not already fully created yet. 

## How to create a good Audio Bible

### <i><b>1. Description</b></i>

Before starting anything, the first thing to do is to analyse the game itself, know its genre, the type of impact you want to give to the public and how you are going to do it. The objective is for the consumer to be as immersive as possible, so you dont want to add a suspense theme into an innocent animal pet game. With just the game pillars of a game you can already tell what type of audio you would be able to use and which of them not, inside the ones that can be used, you should evaluate what are the best options that will make a better immersion to improve the experience of the game in the eyes and ears of the player.

In this description you should implement this analysation on what type of style and genre of music and sounds will be used, it is basically corresponding to the main setting of the game. This explanation will be distributed into 4 main points, **Sounds, Music, Dialogue and Animations**, where in each one of them, there should be descriptive text on how these points will be reflected in the game in terms of style. Note: No audio clips should be added in this section.

**Sound** should have a short description of:
* <i>Ambience:</i> The type of environment sound the game has, this normally is a regular sound during the whole game (rain sounds, blinking lights in a scary room, etc), it is basically the general sound that appear in the surroundings. This is important as the player has to feel like he is in that environment, there can not be a very high sound of big waves when in the screen you can see that it is just a calm day at the beach. Every aspect of the environment matters, so a good description is needed to understand the feeling you want to give to the consumer.
* <i>Main Character:</i> This is for the main character or characters, it is really important that the consumer feels like he/she is the main character, immersion in this aspect is essential. For that, it is important to understand who your main character is and represent that exactly through the sound it makes. The voices it makes, grunting, movement and especially, footsteps. Footsteps are much more important in videogames that it seems, as the player is going to control and move the character around for a long amount of time. With all these sounds you should be able to tell some aspects of the character, giving for example the feeling of heaviness or lightness on them (by the footsteps and movement or jumping sounds).
* <i>Enemies:</i> The same thing goes for the enemies and other characters, but as the focus of the game does not go on them, these will appear and disappear during the game. So, apart from the basic sounds that the enemies would have in the scene and give them a special sound to them so you can identify them by their sound, the aspect of surround sound comes into place. Surround sound is when you an enemy is coming through one side and you hear him in that side of your headphones, depending on your game this will be a very important factor (for example shooters).
* <i>Impact:</i> This explains how big of an impact you want the sound to be for your game (for example sound is extremely important when it comes to scary games).

**Music** should have a short description of:
* <i>Genre:</i> As commented before, the genre should be involved in this description to indicate the appropiate type of music that will be involved in the game.
* <i>Style:</i> The type of music in terms of multiple amounts of sounds at once to make a feeling of chaos, or small slow music to add suspense, tension or calmness. The style of the music will change depending on what is happening in the game, audio should reflect in the same way to give the same feeling that the consumer visually experiences.
* <i>Implementation:</i> The time when certain music will be used, whether if there is a same minimum music during the whole game, when just one character appears, when something is completed, etc. This will be explained in a much detailed way later on in the document.
* <i>Instrumentation:</i> The instruments that are going to be used to produce the music.
* <i>Recording:</i> How and where will the music be recorded to assure a good sound production. 
* <i>Flow:</i> This is the "flow" of the game music, sometimes complete moments of silence help to the experience of the game (to add suspense for example), but it is important to find the right time to use that.

**Dialogue** should have a short description of:
* <i>Style:</i> The way the dialogue is going to be represented (cinematics, voice-over, etc).
* <i>Types:</i> The type of voices you will need to create these sounds (a deep angry voice for an enemy for example).
* <i>Control:</i> The way you plan to control the dialogue over the music/sounds that are being played, or if you plan to stop them to add importance to the dialogue.

**Animations** should have a short description of:
* <i>Weapons and Items of the Player:</i> Depending on what weapons and/or items the characters has, there should be a brief description on how the animations would sound when they are in use.
* <i>SFX:</i> The type of effects, according to the visuals, that there will be and the style that are going to be made of (for example explosions or lasers).

### <i><b>2. References</b></i>

This part will be for information found in other games that are somehow helpful for the audio production or implementation in your game. These could be audio clips that have a similar style you want to use, documentation of any interesting videogame that could help understand the concept of the audio you want to use, or the way some games integrate any type of music or sound as a reference on how you want to do it to your own game.

### <i><b>3. Implementation</b></i>

This is an important part of the document as it is a descriptive and detailed explanation on how the music and sounds are going to be perfomed in the game. The majority of the time, in a game, there are several sounds playing at the same time, it is essential to control these at all times. This includes knowing how many sounds can be played at once (what is too much to the point where it brakes with the style or it turns into chaos), the volume the sounds are being played at so it does not interfere with all the combination of the ambient music and basically a detailed concept vision on how the layers of audio are going to be.

Layers are a type of way to describe the amount of sounds playing at the same time, this way everyone can tell what is playing in the background in an organized way and what can be easily added. In each layer there should be an explanation on what is played and on what can and can not be added to it. This finds a solid balance between music and sounds (including animations and dialague) during all the game and serves as a guide for the rest to assure that no additions can brake the stability of any music or sound style.
This <a href="http://www.dreamquakestudios.com/ADD.html">documentation</a> has a great example about the use of the layers:
~~~
"
Layer 0 
An ambient sound effect layer. As the player passes over certain terrain types on
the map, that terrain type's ambient sound loop begins to play. As the player 
passes over a second terrain type, the first ambient track gently fades out while
the second fades in. There can be no more than two ambient sound effects 
cross-fading into one another at a time. 
Layer 1 
A 3D sound engine, where monaural sounds can travel through a four-speaker system,
complete with a parameter list defining each sound's path, traveling speed, special
effects, and so on. The goal here is not to have in-game dependent sounds, as the 
game itself is isometric, not 3D; but rather, to provide "enhancement" to the
gaming experience, further immersing the player in an ancient, mythological setting. 
Layer 2 
Ambient sounds generated from terrain and buildings, which play only occasionally,
and are randomly selected. Terrain played here is separate from the terrain played
in Layer 0, which is a more of a "global" sound. Here, the sound played is more 
specific and complementary to the ambient terrain track being played in Layer 0. 
Layer 3
Civilian, animal, monster, and all combat-related sounds are played here, including
disaster sounds, user interface sounds, and so on. 
Layer 4 
Interactive music categories based on game events: 
1. "General" music played when mundane activity is going on, 
2. "Action" music played when in combat, 
3. "Special" music played during various important events in the game. 
All of this music segues from one category to next as needed. 
Layer 5 
All narration and in-game dialogue for all characters. Narration is provided at the
beginning and end of campaigns and/or missions; in-game dialogue is heard by moving 
the mouse over an on-screen character and right-clicking on it.    
"
~~~

### <i><b>4. Samples</b></i>

This section is where all the audio files and clips are put in an organized way, remember that these are concepts so they won't be definitive samples, if anything has to be explained about the audio clip a brief description can be added next to it.
The best organized way would be:

* <b>Music:</b> All the theme and background music should appear in this section.

* <b>Environment:</b> Every single one of the environmental music and sound should appear in this section. This should be separated in different bullet points that could be the names of the locations your game is set on, sounds that are heard in the setting and so on, it could also be distributed by layers. These obviously may vary depending on your game and on how you intend to implement the ambient audio on it.

* <b>Characters:</b> Separated by each character, this should include everything about them: general sounds, voices (includes their dialogue if they have one) and animation sounds of the character.

* <b>Weapons and Items:</b> All the animation sounds involving the weapons and items of the game, if there are not a lot of these in your game, it may be a better idea to put them as a subsection on the corresponding characters.

* <b>Sounds:</b> These are the sounds involving UI, recompensation sounds on winning or losing something, animation sounds that do not involve: characters, weapons or environment, and just other sounds effects that you might add like explosions or lasers.

* <b>Narration:</b> This will involve all the external narration in the game, remember that the dialogue of each character is included in the section before. Depending on how all the dialogue is going to be implemented on your game, it could be a better idea to include the dialogue of each character in this section and organize it cronologically (for example a story telling game).

* <b>Extra Audio:</b> Any additional music or sound that does not correspond to either of the sections indicated above and might be interesting to include.

### <i><b>5. Technical Guidelines</b></i>

The last point of the document includes some rules on the type of file formats and the program or programs that will be used. This helps to stay organized and not confuse someone that is not responsable of the audio when given a file in an unexpected format. It is a way to mantain the harmony between the group as no problems would appear if files are sent correctly and there is an easy access to the program used by everyone to change anything as quick as possible. The best recommendation in terms of file formats for videogames would be .wav for SFX and .ogg or .mp3 for ambient music or themes because of their properties; and to operate with the program "Audacity" as it is a very easy functional way to use and access in windows computers, but obviously everyone prefers using what they are used to already, this is just a recommendation.

After all these points, you will have successfully completed an audio bible for your videogame.


### Links

<a href="http://www2.iiia.csic.es/~claudio/papers/Baccigalupo-2003-MasterThesis-Section1.pdf">Design and Production of Audio Technologiesfor Video Games Development</a>

<a href="http://www.dreamquakestudios.com/ADD.html">Example</a>

<a href="https://www.w3schools.com/html/html5_audio.asp">Audio Formats</a>

<a href="https://www.asoundeffect.com/game-audio-design-document/">Game Audio Guide</a>

<a href="https://developer.mozilla.org/en-US/docs/Games/Techniques/Audio_for_Web_Games">Audio for Web games</a>


