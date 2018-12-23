# trisimix.github.io
Resume based on jsonresume, and two associated themes.

Specifically, files were used from the following repositories:

https://github.com/nderkach/jsonresume-theme-onepage-nderkach
https://github.com/varjmes/jsonresume-theme-class

Resume-cli is required to run these themes:

https://github.com/jsonresume/resume-cli

All of this is based on the json-resume format:

https://jsonresume.org/



Instructions:

Pre-usage:
1. Install resume-cli
2. Edit the resume.json in either directory to your liking based on jsonresume's specifics.

Usage:

1. Enter either directory, currently onepage-nderkach is for pdf, and class is for html.
2. run:
    npm install -g
3. Now that it's ran, assuming you have resume-cli installed you can type "resume serve" for a webpage on your localserver or "resume export MyResume.pdf -t onepage-nderkach" for a pdf.
