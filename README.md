# FullStack Twitter Clone

Complete React MERN Full Stack Twitter Clone

For users who are looking to contribute, I'm planning to possibly create a separate branch for community contributions and additional features as well as for improvements and fixes.

I haven't decided on the exact workflow I'll be using yet. But we'll get it out there soon!

Implement a user registration and authentication system.
Users should be able to register with a unique username and password.
Users should be able to log in and log out.
Implement authentication using JWT (JSON Web Tokens).
Design and implement the database schema using MongoDB to store user data, tweets and follower information.
Create, edit, and delete tweets.
Follow/Unfollow any user.
View the timeline, which displays tweets from followed users in chronological order.

login : "http://localhost:3001/auth/login"
register : "http://localhost:3001/auth/register"
users : http://localhost:3001/users/${userId}
friends : http://localhost:3001/users/${userId}/friends
tweets/post : http://localhost:3001/posts/${userId}/posts
no of like : http://localhost:3001/posts/${postId}/like
