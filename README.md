# Easy-Imgur-Upload

A pure Javascript web app to upload imgur albums to imgur

It's perfect if you're creating large galleries of comics / manga / etc. This app allows users with an imgur account to quickly upload a .zip file of images to an album they have created. This is much easier than dragging and dropping when you have 50+ images you would like to upload. It's also great for keeping your images in the same order as they are in your folder. Imgur used to allow you to sort album images, but for some reason they removed that feature years ago and [don't seem to care about bringing it back](https://community.imgur.com/t/how-do-i-sort-by-filename/44312)

I made it for my personal use, as I [upload and share](https://www.reddit.com/user/ieatbabiesmaybe/) doujinshi from my website [hentaku.org](http://hentaku.org) (nsfw)

Another useful github for downloading large imgur albums: [Imgur Album Downloader](http://dschep.github.io/imgur-album-downloader)

Go to https://fluffy9.github.io/Easy-Imgur-Upload/ to use it!

**It's important to note that I have not added any error checking yet. The application will fail silently**
I will add error messages as soon as possible. The most common issue is that the imgur api will deny your request because you have used up all of your quota for the day/hour. If the loading bar stops loading for a while, check the console for an error
