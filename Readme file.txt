1-first step you will do to get access token
http://localhost:8090/oauth/token
send body below  parameters 
grant_type password 
username=oauthappUser
password=oauthappUserPass to get token and then use this as bearer in authorization get all users, comments and posts using below urls

http://localhost:8090/api/comments/all
http://localhost:8090/api/posts/all
http://localhost:8090/api/users/all