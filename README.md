Vault
=====

Vault is a free folder locking app for Mac OS X

Step One 
========
Create folder in your Desktop(for default) or to a specific file path. create a folder in that Volume you want 
just giving a space as name then change its icon to invisible !
for that do following steps
download invisible.icns to your mac then right click invisible folder which named " " and select Get info. then drag 
dowloaded invisible.icns to folder icon of " " folder
which you can see on top most left of get info window 
screen shot >>> http://cl.ly/image/2q1D3k2C272E


Step Two
========
then open main.scpt with  AppleScript Editor.app  from your (launcher or application/Utilities folder)
then edit password "yourpass" to "yournewpassword"


Step Three
==========
(This feature enable users to add specific file path to vault to enable stealth mode <(O_O)> :D )
if you want a specific file path then replace this line from default script ! ( open folder " " ) to 
(    open folder ("/Volumes/Machintosh HD/ " as POSIX file)     )


*NOTE
=====
here ( Machintosh HD/ " )may vary depend on your hdd name &
in between ( / " ) you always remember to give a space as it is our folder name 


Step Four
=========

then save it 
then select file > Export > change fileformat to Application
done
now you have created Vault.app !


Step Five 
=========

copy it to your Application folder , add it to your dock :)

when you click it to open it will ask your password type your password with in 5 Sec other wise it will time out ! 

this is just a small trick to fool your friends ....

always hide your folder "Finder" path bar screen shot here >>> http://cl.ly/image/0W0q1s1t0l0k ! :D 
