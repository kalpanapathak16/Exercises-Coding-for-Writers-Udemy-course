`logout()`
Logs off the current user.
## Parameters
None
## Returns
None
`getNumberFriends()`
Retrieves the count of friends for the current user.
## Parameters
None
## Returns
Type: Number
Number of friends for the current user
`requestFriend(username)`
Sends a friend request to a user.
## Parameters
`username`
Type: String
Name of the user to whom the friend request is sent.
## Returns
Type: Boolean
Values of the request.
`post(statusUpdate)`
Used to post a status update. The status update can be up to 1000 characters long. Returns true if the post succeeded and false if the post fails.
## Parameters
`statusUpdate`
Description
`like(postId, likeType)`
Likes a post. The post is specified by the ID, which is an integer. The likeType can have one of these values: "Like", "Love", "Empathy". Returns true if the like succeeded and false if the like fails.
## Parameters
`postId`
Description
`likeType`
Description
