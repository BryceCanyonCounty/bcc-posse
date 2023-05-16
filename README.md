# bcc-posse
The following script allows players to create a posse,  view the members in it, send invites and more!

The following export can be used to check those in the area if they are in your posse

Posselist, length = exports['bcc-posse']:CheckPosseArea(coords,radius)

This will return all server IDs of those in the area radius in the posse as well as the length of the table, which can be used to multiply rewards

ie Character.addCurreny(0,100*legth) for vorp
