# SpectraStrobe-Envelope-Follower
AudioUnit and VST plugins for Mac to create SpectraStrobe as a color organ from audio files

The SonicBirth 1.3.1 framework must be installed. You can deselect all of the extra example plugins and only install the SonicBirth.app and the Sonic Birth Framework using the checkboxes in the installer. Version 1.3.1 beta2 is included in download.

Also this will not work in 64bit hosts like Logic Pro X or it may with a 32bit bridge but that is untested.

To install go to your hard drive (likely Macintosh HD)/Library/Audio/Plug-ins/Components and copy the .component file there to intall the AudioUnit plugin. If you want to install the VST plugin go to hard drive/Library/Audio/Plug-ins/VST and put the .vst file there. You don't need both but some audio software prefers one over the other.

These plugins work well with Audacity especially the new version 2.1.0 here <http://web.audacityteam.org/download/mac> . Also install the Audacity LAME and FFMPEG plugins further down on the page to output MP3 files.

Once the plugins are installed, turn on the Kasina and select USB mode to connect it to your computer. Open Audacity and in the toolbar next to the little speaker icon select Kasina MMS Audio as your sound output device from the menu. Then simply load any song that you like and select the SS Envelope Follower plugin from the Effects menu. 

Once the plugin window is open be sure the Monitor Source and Include Reference checkboxes are selected. There are a bunch of sliders don't be overwhelmed as you are mainly concerned with the low and high settings for each color and each eye, right and left. The default gain is usually ok at defaults, the white noise is a preview to hear the tracker, the attack makes colors fade into each other, and the delay puts space between them. Use post gain if the colors aren't bright enough but be sure you don't hear clicking as then the light signal is clipping. 

Tweak a few settings and press the Start Playback button at the bottom of the plugin window. You should now hear your song on the Kasina headphones and see the lights flash along with audio bands you have the sliders set to. So for instance try Red R and L from 0hz to 200 hz and it should flash along with bass in the song. The onboard ColorOrgan does similar but the plugin gives much more control.

When you get some settings you like press the Apply button and the light settings will be written into the audio file. Save a copy of this to your Kasina as an mp3. Use Export Audio under the File menu and choose MP3 from the list. Use the settings 320 kbps for Quality, Constant for Bit Rate Mode, and Stereo for Channel Mode.

There you go! Instant (nearly so) light show for your enjoyment. Other audio editors or DAWs will work in a similar way.
