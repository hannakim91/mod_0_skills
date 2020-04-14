**Class:**
Table Options

**Attributes**
* tableNumber (string)
* tableType (string)
* numberOfChairs (integer)
* serversAvailable (array of strings)
* maxChairs (integer)
* countGuests (integer)

**Methods**
* assignServer (modify serversAvailable by using first server available and printing that string as the server at tableNumber)
* addChair (modify numberOfChairs at tableNumber if it is lower than maxChairs )
* removeChair (modify number)
* seatGuests (if countGuests is <= numberOfGuests, seatGuests = true)
