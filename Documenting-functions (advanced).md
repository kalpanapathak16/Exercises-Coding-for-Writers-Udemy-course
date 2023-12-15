# safeMode(enable)
Enables or disables the safe mode based on the specified parameter.
## Parameters
**enable**

Type: Boolean

true to enable the safe mode; false to disable safe mode.
## Returns
None

# getPremiumMode()
Returns whether the user has paid for premium mode.
## Parameters
None
## Returns
Type: Boolean

true if the user has paid for premium mode; otherwise, false.

# setTimeout(timeout)
Sets the time to wait for a response before timing out.
## Parameters
**timeout**

Type: Number

Time to wait for a response before timing out, in milliseconds
## Returns
None

# newEvent(calendarId)
Creates a new event for the specified calendar. 
## Parameters
**calendarId**

Type: Number

The ID of the calendar.
## Returns
Type: Number

The ID of the new event.

# getDirections(latitude, longitude, directionsCallback)
Returns the directions from the current location to the destination location.
## Parameters
**latitude**

Type: Number

Latitude of the destination, in degrees

**longitude**

Type: Number

Longitude of the destination, in degrees

**directionsCallback**

Type: function

Called when the directions are returned from the server. Contains a String parameter
named **directions** that provides guidance on navigating from the current location to the destination.

# createTransaction(amount)
Creates a new transaction.
## Parameters
**amount**

Type: Number

Amount of the transaction, in the default currency
## Returns
Type: String
The ID of the new transaction.

**See Also:**

getTransaction

deleteTransaction
