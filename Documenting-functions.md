# logout()
Logs out the current user.
## Parameters
None
## Returns
None
# getNumberFriends()
Retrieves the count of friends for the current user.
## Parameters
None
## Returns
Type: Number

Number of friends belonging to the current user.
# requestFriend(username)
Sends a friend request to the specified user.
## Parameters
`username`

Type: String

Name of the user to whom the friend request is sent.
## Returns
Type: Boolean

Returns **true** if the user accepts the friend request; **false** if the user rejects the friend request.
# post(statusUpdate)
Posts a status update. 
The status update can be up to 1000 characters long. Returns whether the `post` succeeded.
## Parameters
`statusUpdate`

Type: String

Status update to post
## Returns
Type: Boolean

Returns **true** if the post succeeds; **false** if the post fails.
# like(postId, likeType)
Likes the specified post. 

Returns whether the `like` succeeded.
## Parameters
`postId`

Type: Number

A unique identifier number of the post.

`likeType`

Type: String

The type of the `like` action. Valid values: **Like**, **Love**, and **Empathy**.
## Returns
Type: Boolean

Returns **true** if the `like` succeeds; **false** if the `like` fails.

