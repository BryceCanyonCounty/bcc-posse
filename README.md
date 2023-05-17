# bcc-posse
This script offers players the ability to form a posse and provides various functionalities such as managing members, sending invitations, and more.

To check if any individuals within a specific area are part of your posse, you can utilize the following export:

local posseMembers, posseSize = exports['bcc-posse']:CheckPosseArea(coords, radius)

This export will retrieve the server IDs of all posse members present within the designated radius. Additionally, it returns the length of the table containing the IDs, which can be useful for implementing reward systems.

For example, you can multiply rewards based on the posse size using the following code:

Character.addCurrency(0, 100 * posseSize) -- Assuming 'vorp' is the currency system being used

By multiplying the base reward amount (100 in this case) with the posse size, you can adjust the rewards dynamically according to the number of posse members using the VORP currency system.
