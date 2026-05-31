# Blog-Platform
The Blog Platform with Comments is a full-stack web application that allows users to create, edit, view, and delete blog posts. It includes secure user registration and login for authentication and access control. Users can interact with blog posts by adding comments, making the platform more engaging and interactive. 
Fully functional with all the required features:


What's included:


1.Auth — Register, login, logout with session persistence. Demo account: alice@blog.com / alice123
2.Posts — Create, edit, delete blog posts with a tag system and excerpt generation
3.Comments — Leave comments on any post; authors/post owners can delete them
4.Likes — Like/unlike posts
5.Profile page — View your posts and comment history
6.Tag filtering — Filter the feed by category (Culture, Design, Tech, Life, etc.)
7.Persistent data — Everything is stored in localStorage, so it survives page refreshes


To deploy this as a real app with a backend, you'd swap the localStorage DB layer for API calls to a Node/Express + PostgreSQL backend.
