#Composer package for 
instagram-video-and-photo-api

The original code was written by [LookHin](https://github.com/LookHin/instagram-photo-video-upload-api)

I have changed it in a composer package


If you want to use the class, you can do this.

**You need to autoload composer if you want to use the package**

```

// Upload Photo
$obj = new HelloInstagram\InstagramUpload();
$obj->Login("YOUR_IG_USERNAME", "YOUR_IG_PASSWORD");
$obj->UploadPhoto("square-image.jpg", "Test Upload Photo From PHP");

// Upload Video
$obj = new HelloInstagram\InstagramUpload();
$obj->Login("YOUR_IG_USERNAME", "YOUR_IG_PASSWORD");
$obj->UploadVideo("test-video.mp4", "square-thumb.jpg", "Test Upload Video From PHP");


``` 
