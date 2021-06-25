# Project: Memories Social Media App

_Current Version:_ 1.0.3

# Description: This app utilizes the MERN stack to create a small-scale social media application.

Users can create an account or login using their google account. Once they've
chosen an account option, the user can create a post that is saved in a MongoDB
Atlas cluster.

Only users who're signed in can like the posts and only the post's creator can
edit/delete the post.

# Future Plans:

For the next version of the app, I will be adding client side routing and
pagination. I will alos likely update the general theme of the site to make it
more interesting.

# Version History:

_Version 1.0.3:_

Finished implementing the search posts feature. It will now update the browser
url to the specified query, dispatch the query to the database, and render the
results.

_Version 1.0.2:_

Implemented search request functionality. This feature allows the user to search
for a post by either it's title or by its tags.

Currently, the results are simply printed to the browser console. However, I
felt this was a good milestone as I had to create a new route
(getPostsBySearch()) and implement the necessary backend logic (find the posts
by their title or a tag present in their tags array.)

_Version 1.0.1:_

Implemented pagination and search bar functionality.

I also updated the client routes. The home route "/" will now redirect to
"/posts". The "/auth" route will now redirect users who're logged in to the
"/posts" route.

_Version 1.0.0:_

This version of the project builds upon a previous app that had basic CRUD
functionality. In this update, the app now has an authorization feature that
only allows users with an account to interact with the posts.
