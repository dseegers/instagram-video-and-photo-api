#Composer package for 
instagram-video-and-photo-api

Originally code written by [LookHin](https://github.com/LookHin/instagram-photo-video-upload-api)


If you want to use the class, you can do this

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
