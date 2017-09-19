---
title: "Automated Sheet Music Translation"
showDate: False
thumbnailImage: "/img/OpticalMusicReader.jpg"
thumbnailImagePosition: left
metaAlignment: center
coverMeta: out
date: 2017-12-27

---
This was a group project where our goal was to build a Optical Music Recognition (OMR) system from scratch using the skills we learned in Computer Vision class.

<!--more-->

Utilizing OpenCV, we built our system to recognize staff lines and notes in music sheets. After detecting and removing the staff lines from the original image. We were able to determine the measure and pitch of our music sheets by performing template matching to the symbols used in music.

Our system was also able to handle a moderate amount of noise in regards to scanned music sheets to allow proper detection. In addition, the system is able to output a computer generated music sheet after performing OMR on the scanned music sheets.

![Staff Lines Removed](/img/OpticalMusicReader.jpg)

More information can be found at our GitHub at https://github.com/christophertfoo/OpticalMusicReader

