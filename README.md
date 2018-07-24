# Easy-Imgur-Upload

A pure Javascript web app to upload imgur albums to imgur

It's perfect if you're creating large galleries of comics / manga / etc (I use it to upload hentai on my very nsfw [subreddit](https://www.reddit.com/r/Hentaku/) for my very [nsfw website](http://www.hentaku.org)). This app allows users with an imgur account to quickly upload a .zip file of images to an album they have created. This is much easier than dragging and dropping when you have 50+ images you would like to upload. It's also great for keeping your images in the same order as they are in your folder. Imgur used to allow you to sort album images, but for some reason they removed that feature years ago and [don't seem to care about bringing it back](https://community.imgur.com/t/how-do-i-sort-by-filename/44312)

## Documentation
**Please Read Before Use**

This project is very much a work in progress. It works, but there are quite a few bugs that make it unintuitive. I haven't had enough time to polish everything, so it would be very helpful if anyone wants to contribute.

* Imgur has a limit to how many images / how many mb you can post per day / per hour. The 2500 images a day is taken from imgur's description. It's very likely that your request will be denied after posting 2-3 galleries with about 20-30 images of moderate resolution.

* Before you upload, please rename your images in the format 0001.png, 0002.png, etc (notice the file names not the extensions, you do not have to upload them as png). There are some issues with how images are sorted, but it works for my purposes (aka using that naming scheme). Otherwise it might not order the images correctly.

* Wait approximately 10-30 seconds for the images to load before pressing the "Upload to Imgur Button". The check mark animation can be misleading in that I didn't put it to wait until the files have been properly uploaded. Alternatively, if you open the console, you can see when all the blobs have uploaded.

That's all. Follow the instructions shown on the uploader. 


