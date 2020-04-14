**Instance of Table Options:**
4-top table at Hamburger Haven

**Attributes**
* tableNumber: "Table 1"
* tableType: "4-top"
* numberOfChairs: 3
* serversAvailable: ["Diana" "Johnny", "Lucy"]
* maxChairs: 4
* countGuests: 3

**Methods**
* assignServer: serversAvailable.shift to assign "Diana" to "Table 1", leaving ["Johnny", "Lucy"] left as available servers
* addChair: since 3 < 4 (maxChairs), you can add 1 more chair to the table, bringing numberOfChairs to 4.
* removeChair (modify numberOfChairs from 4 to 3)
* seatGuests: countGuests is 3 and numberofChairs is 3 - since 3 = 3, seatGuests = true
