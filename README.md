# webcamKnn

Base project for using the webcam and running the results through mobileNet, and the results of that through a KNN to allow for arbitrary classes to be discovered based off a small example set.

# Future work

This is the base for the class project there/not there, and light/dark sensor.


## Base of this project

This is heavily based off of the teachable machine Google tool, however simplified for easy addition to personal projects.


## TODO

- [ ] Fix the load button, currently we can save out to a file, however loading the file does not currently work due to an error.
  - The error is likely something to do with the location of the file when uploaded.
- [ ] Create a better way to index the labels and text
  - Potentially use a loop over some variables

## Done

- [x] Add another KNN with a different set of classes
- [x] Add a third KNN with the input being the two previous KNN's
- This will be the base for the overall solution
- [x] Migrate application to a flask service
- This will allow us to serve the application on something like heroku easily in the future
