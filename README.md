# SUPER SPAMTON 64 By BWGLite

Release 1.0 (Previous, model only release went by 'Spamton in Super Mario 64')

That's it, it's time for a BIG SHOT!

Featuring Spamton, with lots of changes to the game to fit with him,
and a redone soundtrack featuring DELTARUNE and UNDERTALE songs,
replay Super Mario 64 in an adventure fit for a real BIG SHOT!

Comes with a fully featured, console-compatible Nintendo 64 version,
and a version for the Super Mario 64 PC Port (sm64ex-nightly) with 8 alternate costumes to choose!

# Using the Nintendo 64 Version

Needed

	-Floating IPS (Program version or Online version)
		-Program Version <https://www.smwcentral.net/?a=details&id=11474&p=section>
		-Online Version <https://www.smwcentral.net/?p=onlinetools&tool=flips>
		-Other BPS Patchers should work, as well
	-Super Mario 64 US ROM
	-Nintendo 64 Emulator
		-Recommended Emulators are Project64, Bizhawk using Mupen64Plus core
		-Recommended to use GlideN64 Video Plugin (available in Project64 and Bizhawk)
		-Also fully works with Paralell Launcher, with ParalellN64 and ParaLLEI!

Using The Floating IPS Program:

	1. Open Floating IPS, and click "Apply Patch"
	2. Select the .bps patch (Super Spamton 64.bps), press Open
	3. Select your unmodified Super Mario 64 US ROM, press Open
	4. Navigate to where you want to save the patched ROM, press save

Using Floating IPS Online:

	1. Click the button next to 'Base ROM', and select your unmodified Super Mario 64 US ROM, press Open
	2. Click the button next to 'Patch', and select the .bps patch (Super Spamton 64.bps), press Open
	3. Click the 'Apply Patch' button, and the patched ROM will download!

-The game won't start!

	If using Project64, go to Options>Configuration, and under Config: SUPER MARIO 64,
	check that Memory Size is set to 8MB

-Spamton's face is crooked!

	Certain Video Plugins don't properly emulate the point texture filtering used on Spamton's face.
		If in Project 64, go to Options>Configuration, and under Plugins, set the Video pluging to GlideN64
		
		If in Bizhawk, go to N64>Plugins, and set Active Video Plugin to GlideN64

# Using the PC Port Version

Needed

	SM64pcBuilder2 https://sm64pc.info/sm64pcbuilder2/ (Follow usage instructions on page if it's your first time using SM64 PC)

Compiling and Playing

	1. Open the SM64pcBuilder2 program, and under 'Source', select the 'sm64ex' Repo, and the 'nightly' Branch.
	2. Under 'Options', select 'External Data' as a build option.
		2a. If needed, click the 'Savable Options' button, and make sure the version is set to 'American', 
            and the Renderer API to 'OpenGL'.
		2b. If needed, under 'Patches', make sure 'DynOS' is enabled.
	3. Press the 'Compile' button and wait for building to complete.
	4. Press OK on the 'Congratuations!' window. The game will automatically launch, close the game window.
	5. Locate your 'repos' folder, and inside it, open the 'sm64ex-nightly' folder.
	6. Copy the contents of the Super Spamton 64 PC Port's 'Main Files' folder, into your 'sm64ex-nightly' folder. 
        When the 'Replace or Skip Files' window appears, choose 'Replace the files in the destination'.
	7. Press the 'Compile' button in the SM64pcBulder again; when you do, a window stating that a build folder is already detected will appear. 
        Click on the blue 'Clear us_pc' button. 
        (Do not click the green 'Clear Repo' button! That will reset your sm64ex-nightly repo to vanilla Super Mario 64.)
	8. Wait for building to complete again.
	9. Press OK on the 'Congratuations!' window. The game will launch, and you're all set to go!
	
Using Alternate Costumes on the PC Port Version

	In the Super Spamton 64's PC Port version folder, along with the main files, there is a second folder of different costumes to choose for Spamton. To use them;
		1. Make sure you have already followed the above steps to at least step 6, to make sure all the main Super Spamton 64 files are in your sm64ex-nightly repo.
		2. Open the folder of the costume you want, and copy it's contents into your 'sm64ex-nightly' repo folder.
		3. Press the 'Compile' button in the SM64pcBuilder and wait for building to complete.
		4. If you want to change which costume you're using, make sure to copy the contents of the
		'0 - Default Spamton' folder to your 'sm64ex-nightly' repo before copying the contents of the costume you want, to ensure that it appears correctly.

Note about using CHEATER on the PC Port version

	Using the CHEATER patch may break Super Spamton 64's endgame model swap (the game does not crash, the swap just doesn't happen). This is due to the 'Play As' cheat always setting Mario's model to it's default, breaking the swap. If you want to use CHEATER without breaking the model swap, do either of the following after first compliing your game with CHEATER enabled:
		A.
			1. In your 'sm64ex-nightly' repo, navigate to src\game and open mario_cheats.c (preferabbly in notepad++)
			2. Comment out all lines relevant to the 'Play As Cheat' (currently these lines 1319 to 1455).
		or B.
			1. Inside of Super Spamton 64's PC Port version folder, in the 'Extra Files' folder, copy the mario_cheats.c file into your 'sm64ex-nightly' repo, in src\game.

# 

Of course, DELTARUNE, UNDERTALE, and Spamton all belong to Toby Fox.

Have fun, and thank you for playing!!!

[@BWGLite](https://twitter.com/BWGLite) on Twitter
