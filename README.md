# Cartoonize Your Image!

This is a web app to turn your photo into a cartoon-like image. There are four filters that you can choose from: Pencil Sketch, Detail Enhancement, Pencil Edges, and Bilateral Filter.

## Files
There are five files necessary to build this web app:

1)cartoon_app.py: main Python file of the app.

2)setup.sh: file to setup your configuration on Heroku.

3)requirements.txt: the file to tell Heroku which dependencies you need to build the app.

4)Procfile: file to tell Heroku which and how the command and file should be executed.

5)Aptfile: additional file for buildpacks to enable OpenCV to operate within Heroku.


With Heroku CLI you can use this command to add the buildpacks:heroku create --buildpack https://github.com/heroku/heroku-buildpack-apt.git
