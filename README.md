![image](https://github.com/TCLynx/NPCTool/assets/108405567/9119cbd6-6e89-4761-93f8-a0209caa1dfa)NPC Tool 1.1.02 BetaPacks test copy
By Aleece B. Landis (otherwise known as TCLynx) tclynx@aquaponiclynx.com
"This tool is still under development and comes with no warranty or guarantee. 

"
Discussion on this tool can be found here https://discord.com/channels/412297987210084353/1126162935094464522
https://discord.com/channels/412297987210084353/1126162935094464522
Invite to the Server is
https://discord.gg/7fSQBdx

Before you start, make sure you save your workbook in the location where you want your files created.  XL has a habit of saving to strange places for me and I've discovered stuff being saved into the templates folder as I've been working on this.  Double Check where yoru workbook is saved before you run the macro.  I will create a macro button that will simply save the workbook in the same folder as the template you just used to create it.  This current Packs update is set up to create the folders you will need in your behavior pack and your resource pack.  The Lang file will still need editing because I have not yet written code to handle duplicates.
"The Folders created can have a manifest file added and then simply place them in the development_resource_packs or development_behavior_packs folder based on if it ends in RP for resource pack or BP for behavior pack.  If you don't know how to handle creating the manifest.json files for these, I have packaged the Tool in a zip file that already has the folders created and I have included a set of manifest.json files for the BP and RP folders.  If you are creating more than one addon with these you will need to update names, version numbers and/or uuids for the manifest files but what I supplied should at least get you started exploring the use of dialogue files.
"
I recommend making a copy of the NPCToolTest_blank sheet.  (Right click on the sheet tab at bottom and choose Move or Copy and be sure to check the box make copy.) Then you can rename it to whatever you like as your filename.  If you want to create more than one file, just do more than one sheet.
Fill in any of the fields you want to use.  Green Header means mandatory.  Red Header means the macro will auto fill those fields and you shouldn't.
When you fill any of the Commands Fields (Headers in Yellow), you Must use "" aroun your commands and you must use the / before the command.  See Examples.
If you would like to use more than one command in any of the command fields you may do that, simply put a , after the previous command and then alt + Enter to add a line break into the field so that each command will be on it's own line.  The like break is NOT mandator though it will make the dialogue file easier to read.  The comma between multiple commands in the cell IS MANDATORY.  Do not add a comma after the last command in the cell.
When ready, click the Macro button in the top Left of the sheet to create your files. The Macro works on one Sheet at a time.
Viewing and editing the files can be done in a text editor.  Make sure to rename or move the files if you want to save them but need to re-run the macro as it will overwrite the files in the same directory with the same name.
Once all is said and done, the filename.diag.json file/s will need to be placed into a dialogue folder within a behavior pack that needs to be active on a world in order for the dialogue scenes to be available for use within the world via the /dialogue open or /cialogue change commands.  The .lang file will need to be placed in the resource pack texts folder.  And it will need to be titled with the language code.  For example en_US.lang is what I would use for US English.  The Language files for any single language will need to be consolidated into a single .lang file and any duplicate buttons can be removed (as in the same button name could be used for more than one scene or even dialogue file.)
