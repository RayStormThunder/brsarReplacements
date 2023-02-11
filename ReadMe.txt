Get your WZSound.brsar and place it in the root folder which is the folder this ReadMe is in. 

Now export the audio files that you want to change from the WZSound.brsar and place them in Original Audio > exported.

They must be named Audio[{Any number between 1 and 200}] eg. Audio[12], Audio[1], Audio[199]

Finally place the files that you want to replace those files with in Replacement Audio > exported

The file Original Audio file will be replaced in WZSound.brsar with every Replacement Audio file that shares the same name. So if you have Audio[1] in Original Audio, it will be replaced with the corresponding Audio[1] file in Replacement Audio

When you run the program. It will create a copy of every file as a .txt

Keep in mind if you that it will not generate another txt file if there is a txt file with that name. So if there already is WZSound.brsar.txt it won't generate another one. This also applies to Audio[#].txt in Original and Replacement Audio.

When you start the program a window will pop up saying it started. If it finishes it will pop up a window saying it is done. If it fails a window will not pop up.

Your new WZSound.brsar will be in the Output folder along with 2 output.txt which will tell you some information if some files were too big or if there were other errors that caused replacements to fail.

THIS PROGRAM IS NOT OPTIMIZED! It could take a while to finish. Especially when it generates the WZSound.brsar.txt for the first time.


