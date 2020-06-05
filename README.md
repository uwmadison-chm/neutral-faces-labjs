# Neutral Faces Task for lab.js

A neutral faces task in lab.js, with faces from the [RADIATE set](https://www.sciencedirect.com/science/article/pii/S0165178117321893). [TODO: verify source]

## Hosting in Qualtrics

See the [Lab.js documentation on working with Qualtrics](https://labjs.readthedocs.io/en/latest/learn/deploy/3a-qualtrics.html).

Then, when pasting the embed source, change the iframe src to pass participant 
id and session variables like this:

    <iframe
      src="//some-location?PPT=${e://Field/PPTID}&session=${e://Field/session}"
      style="width: 100%; min-height: 600px; border: none;"
    ></iframe>


