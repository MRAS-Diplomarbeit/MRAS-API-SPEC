## Server - App API Errocodes

|Code  | Meaning|
|------|---------------------------------------------------------|
|AUTH001 |Missing or Invalid Authorization Header|
|AUTH002 |JWT not found in Redis (Expired)|
|AUTH003 |User not Found in Database (Wrong Username or Password)|
|AUTH004 |User already exists|
|AUTH005 |Invalid RefreshToken|
|AUTH006 |User not found|
|AUTH007 |Wrong Reset Code|
|AUTH008 |Password not Reset|
|AUTH009 |User not Authorized for this Action|
|DBSQ001 |Error Accessing Database|
|DBSQ002 |Error Saving RefreshToken in Database|
|DBSQ003 |Error Accessing Redis|
|DBSQ004 |Error Reseting User Password|
|DBSQ005 |Error Saving new Password|
|DBSQ006 |User ID not Found|
|RQST001 |Error decoding Request|
|RQST002 |Request Body missing fields|
|CLIE001 |Error sending Request to client|
