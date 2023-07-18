![image](https://github.com/TCLynx/NPCTool/assets/108405567/ebba786a-4d64-4eb5-a01b-85df6bfabd53)# NPCTool
This will be for the Minecraft NPC tool where Map creators can use an excel file to create the dialogues for npcs in game.

NPC Tool 1.0.01 Beta test copy
By Aleece B. Landis (otherwise known as TCLynx)
"This tool is still under development and comes with no warranty or guarantee. 

Discussion on this tool can be found here
https://discord.com/channels/412297987210084353/1126162935094464522
Invite to the Server is
https://discord.gg/7fSQBdx
I recommend making a copy of the NPCToolTest_blank sheet.  (Right click on the sheet tab at bottom and choose Move or Copy and be sure to check the box make copy.) Then you can rename it to whatever you like as your filename.  If you want to create more than one file, just do more than one sheet.
Fill in any of the fields you want to use.  Green Header means mandatory.  Red Header means the macro will auto fill those fields and you shouldn't.
When you fill any of the Commands Fields (Headers in Yellow), you Must use "" aroun your commands and you must use the / before the command.  See Examples.
If you would like to use more than one command in any of the command fields you may do that, simply put a , after the previous command and then alt + Enter to add a line break into the field so that each command will be on it's own line.  The like break is NOT mandator though it will make the dialogue file easier to read.  The comma between multiple commands in the cell IS MANDATORY.  Do not add a comma after the last command in the cell.
When you are finished entering your content, Make sure the Spreadsheet is saved in the folder that you want to have the diag.json and the .lang files saved.  They will be saved with the sheet name to the same folder where your workbook is saved.
When ready, click the Macro button in the top Left of the sheet to create your files. The Macro works on one Sheet at a time.
Viewing and editing the files can be done in a text editor.  Make sure to rename or move the files if you want to save them but need to re-run the macro as it will overwrite the files in the same directory with the same name.
Once all is said and done, the filename.diag.json file/s will need to be placed into a dialogue folder within a behavior pack that needs to be active on a world in order for the dialogue scenes to be available for use within the world via the /dialogue open or /cialogue change commands.  The .lang file will need to be placed in the resource pack texts folder.  And it will need to be titled with the language code.  For example en_US.lang is what I would use for US English.  The Language files for any single language will need to be consolidated into a single .lang file and any duplicate buttons can be removed (as in the same button name could be used for more than one scene or even dialogue file.)
