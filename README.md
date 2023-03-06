# Anveo-Vscode-Extension-V1
Date 06.03
This is the 1st version which works and have following running funtionalities 
->Login to the BC instance using basic auth + with SOAP protocol
->Password has been encrypted and saved in windows OS using Keytar package 
->Save the Scripts back to the BC after editing using  normal ctrl + s
->Script data like (Original name and Libraries) are saved globally and can we easily accessed for further use
->When Scripts are downloaded they are downloaded into different folders like Lua , Javascripts and so on.

Things need to be done in the project
->Create different views in sidebar in explorer window in order to show
-->Scripts all together in one view called 'Action Codes'
-->If its a script then show its related libarary in another view 'Libraries'
-->Pages 'Anveo Pages'
-->Sync Packages
-->Main Menus 'Main Menus'
-->Virtual Tables
-->Table triggers
-->Text Constants
-->Users
-->Property Set Groups
-->Sync Managment Rule set 


->OAUTH and basic Auth with NTLM 
->Make fixes for ODATA to be able to work as SOAP
---> Login works but download scripts and save option is not implementated in ODATA.
