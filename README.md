# Augemented-Reality-Campaign
The Augmented Reality project was a project that I had initially began working on as a way to pitch a new sector marketers can begin taking more advantage of, Virtual Reality (VR) and Augmented Reality (AR).

The unique element to this project is that its super light-weight. This is a mobile experience that anyone with a mobile device can access via the web. Accessibility is a very important factor that should always be considered when coming up with a marketing initiative. How can I make this experience accessible to as many users as possible without requiring too much actions from them? 

To view the demo, follw the instructions below. 

1. Visit the [Demo Page](https://sofit.us/Augemented-Reality-Campaign/)
2. Click the "Enter" button and allow the site to access your device.
3. Once your camera is on, point the camera to any of the following images in the [img folder](https://github.com/felixabreu/Augemented-Reality-Campaign/tree/main/img) and the video should begin playing. 

`**dalex marker.png**, **flow marker.png**, **justin marker.png**, or **sech marker.png**`

You should be able to use your camera after allowing the website access to your device and point to one of the images above. The video will begin playing, make sure that your device is not Silenced and audio is up to hear the videos. 

### AFrame JS

To create this project I used the AFrame.js library. A-Frame is a powerful three.js framework, providing a declarative, composable, reusable entity-component structure. HTML is just the tip of the iceberg; developers have unlimited access to JavaScript, DOM APIs, three.js, WebVR, and WebGL.

With this tool, I had a foundational framework that had components I can use specifically for creating this experience. The components were `a-marker, a-video, and a-entity`

### a-marker, a-video, and a-entity

These three components were the components I needed to be able to give users the ability to scan an image and once scanned, play a video within the frames of the image, all through the users camera. 

1. `<a-entity>` was the component that allowed us to request access to the users camera device. This was the most essential component as it allowed us to use the users camera to scan for the marker.

2. `<a-marker>` was the component that created and stored a marker that would be used to contain the video. Once provided access to the users camera, the camera will scan to see if a marker image is in the camera view and if so, trigger an event. In this case, the event that is triggered is the automatic rendering and playing of a video within the marker image frames. 

3. `<a-video>` was the component that rendered the video upon the successful scan of a marker. 

### Reference

![Alt Text](https://media.giphy.com/media/zmH7XfhFYlTeXf8A5s/giphy-downsized-large.gif)

