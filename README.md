Birthday Slideshow Webpage

This is a customizable birthday greeting webpage featuring animated balloons, a slideshow of images and videos, and a birthday song playing in the background. It uses plain HTML, CSS, and JavaScript.

Features

-Olive background with floating silver and black balloons animation.

-Personalized birthday greeting message with a customizable name.

-Slideshow that supports both images and videos, playing one at a time.

-Automatic slide transitions: images show for 3 seconds; videos play fully before moving on.

-Background music (birthday song) with controls.

-Responsive layout that fits most screen sizes.

How to Use

-Clone or download this repository or save the index.html file.

-Add your own images and videos:

-Replace or add image files (e.g., .jpg, .png) in the project folder.

-Replace or add video files (e.g., .mp4, .webm) in the project folder.

Customize your name and message:

-In the <script> section near the bottom of index.html, update the variables:

Edit
const userName = "Sonal"; // Put your name here
const userMessage = "Wishing you a day filled with love, joy, and celebration."; // Optional custom message
Update slideshow items:

Modify the slidesData array to add or remove images/videos you want to display:

js
Copy
Edit
const slidesData = [
  {type: 'image', src: 'your-image1.jpg', alt: 'Description'},
  {type: 'video', src: 'your-video1.mp4'},
  // Add more items here
];
Balloons images:

Make sure you have these balloon images in the project folder or update their file names in the HTML:

silver.png

Black-Balloons-PNG-Picture.png

Birthday song:

Replace the birthday_song.mp3 file with your favorite birthday tune or remove the <audio> element if not needed.

Open the file:

Open the index.html file in any modern web browser to see your personalized birthday slideshow in action.

# Birthday_video
