# Flask-MongoDB Web App

The web app I created is called [Safe Space Blog For All](https://i6.cims.nyu.edu/~xx2033/web-app-XYCrus/flask.cgi).

Essentially it is a website where people can make blog posts. It is mainly created with Flask, Pymongo and HTML.

User can [create a blog](https://i6.cims.nyu.edu/~xx2033/web-app-XYCrus/flask.cgi/create) by entering their username, the content. A key is also required which will be used in editing and deleting posts.

User can [read all blogs](https://i6.cims.nyu.edu/~xx2033/web-app-XYCrus/flask.cgi/read) on this website. They can like or dislike a post, and the total likes for each posts will be presented below each blog. 

On the read page, users also have the right to edit and delete blogs as long as they have the key. Whenever a post is edited, its likes will be reset to 0. 

User can [find history blogs](https://i6.cims.nyu.edu/~xx2033/web-app-XYCrus/flask.cgi/findhistory) posted by a specific user in descending or ascending order. 

*Most of the keys for blog posts already on the website are 111