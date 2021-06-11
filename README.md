# DEVCam_a_camera_web_app

https://dev-cam-v1.herokuapp.com/ check it out here.
![Screenshot_2021-06-11-19-20-57-80](https://user-images.githubusercontent.com/75971776/121698370-902e2280-caeb-11eb-80ca-1c2031194b3e.jpg)
![Screenshot_2021-06-11-19-22-09-78](https://user-images.githubusercontent.com/75971776/121698383-93c1a980-caeb-11eb-904b-cebf434bdb46.jpg)
![Screenshot_2021-06-11-19-22-00-66](https://user-images.githubusercontent.com/75971776/121698399-96240380-caeb-11eb-8deb-aadbb0b34fc0.jpg)

https://user-images.githubusercontent.com/75971776/121712025-df2e8480-caf8-11eb-96b6-0176f483d00b.mp4



An instant camera web app.
# Mobile (and Desktop) Camera App Template (HTML, CSS, JS and WebRTC)

Release 17-05-2020: Replaced DetectRTC with own code to solve a bug on iOS 13.4.1

I like to experiment with Computer Vision and AI API's (like Azure Cognetive Services, Google Cloud Vision, IBM Watson) to see if I can utilise them for some ideas.

The most easy way to test those scripts and APIs them is by directly making a photo and sending image data to the API/script, instead of uploading files. I didn't find a fast mobile first camera template for HTML5 as a starting point for my prototypes, so I developed one myself. The interface setup is mainly inspired by the standard Android and iOS Cameras.

The template doesn't do anything with the image(canvas) data yet, I'll leave that up to you.
If you need help with integrations or app development (PHP, Vue), feel free to contact me.

Feel free to use it in your next Computer Vision or AI project.

### Requirements

- WebRTC is only supported on secure connections. So you need to serve it from https.
  _You can test and debug in Chrome from localhost though (this doesn't work in Safari)._

- A recent OS and browser. It should work on recent Phones and OS-es. If it isn't, please
  let me know (issue) (including a suggestion to fix it). Also add the debugging info in the console.

### Functionalities

- Fullscreen mode (not on Safari mobile (iOS))
- Take Photo
- Flip Camera (environment / user)
- Supports both portrait and landscape mode
