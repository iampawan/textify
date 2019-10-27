# Textify

![language Kotlin](https://img.shields.io/badge/language-Kotlin-brightgreen.svg) ![Platform Android](https://img.shields.io/badge/platform-Android-lightgrey.svg) ![Release v0.1](https://img.shields.io/badge/release-v0.1-orange.svg)

## Android Developer Challenge: helpful innovation, powered by On-Device Machine Learning + you!

#### Tell us what your idea is. 
My idea is to write a document scanning app using live object detection when the camera is pointed to a document and then:
1. Exporting the scanned document asPDF
2. Detecting font, text, and text size for heading and body and creating a digitized PDF to export.
3. Enabling the digitized document to be edited in a text editor before export.
4. Translating the document to other languages and exporting the translated document with the same structure of headings and body as the original document.

My long term plan for the idea is to enable the app to scan and digitize hardcopy of books which are not available as ebooks simply by pointing and scanning pages, translating them into different languages, and then exporting them to ebook formats like EPUB, MOBI, etc.

#### Tell us how you plan on bringing it to life.
I plan to start working on the project right away and writing the major parts of the app to make it functional before working on the tiny details and the little features that would make the app stand out, so that the app is ready to be shipped after Phase I while I work on the other features.

The first phase that I’d like to focus working on is:
1. Live object detection through camera, perfecting the edge detection of the document, figuring out the size of document and then cropping and adjusting the distortion in the captured picture to create a readable scanned document (Using Vision in ML Kit).
2. Exporting the document as PDF.

The second phase of the project would be:
1. Training an ML models to train to detect fonts and text sizes and using (Custom Models in ML Kit).
2. Converting the scanned document to digital.
3. Exporting the digitized document as PDF.

The third phase:
1. Implementing a text editor in the app (this is where I’d need Google’s help to implement an in-app Google Docs).
2. Translate the document to different languages. (Using Natural Language in ML Kit).

Fourth phase (the future):
1. Implement scanning and translating hardcopy books to ebooks by introducing export as EPUB, MOBI, etc.

In making the app possible, I think of a few areas where I could really use Google’s help:
1. Implementing an in-app Google Docs (as mentioned in the third phase).
2. The mentorship in app design using Motion and Material Design.
3. The mentorship needed for a proper offering in Google Play, and also
4. To test whether such features could have the potential to be part of the Android’s native camera, Google Docs, or Google Translate in the near future.

Now that everything is nicely organized, here’s my planned timeline to complete the project before May 1, 2020:
1. Nov 19 - Dec 19: Work on Phase I and shipping the basic functional app to Google Play.
2. Jan 20 - Feb 20: Work on Phase II and work on branding and promotion.
3. Mar 20 - Apr 20: Work on Phase III and finalizing the app for showcasing and spotlighting.

#### Tell us about you. 
My name is Waseef Akhtar and I’m a native of Pakistan’s picturesque province, Khyber Pakhtunkhwa. I currently work as an Android Developer with a swedish-based startup, Degoo Backup AB. I have over two years of experience with writing iOS and Android applications, and pride myself on having an artistic eye despite being “just” a developer. I love the opportunity to utilize both the artistic and the technical aspects of my brain.

One of the major side projects that I’ve carried with myself since graduating university is a social network for music that I still work on in my spare time.  When I first started working on it as a final year project in university, I had plenty of ideas that I didn’t think I’d be able to achieve. Few of them were: Auto-tagging a song like Shazam, curating a recommended list for each user, implementing gamification, etc. However, by the end of the year, I noticed that I successfully completed the features of the app that I thought wasn’t achievable.

Having been the only team member, I’m looking after everything from designing graphical assets to developing back-end using Google Firebase and writing front-end using Swift. To learn more about it, here’s a landing page with an invitation for testing the pre-release app: canarymusicapp.com.


