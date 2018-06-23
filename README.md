# Processing

Processing is a flexible software sketchbook and a language for learning how to code within the context of the visual arts. Since 2001, Processing has promoted software literacy within the visual arts and visual literacy within technology. There are tens of thousands of students, artists, designers, researchers, and hobbyists who use Processing for learning and prototyping.

For more information check [Processing.org](https://processing.org/reference/)

This repository contains Processing programs for different applications, change of branch depending of your currently version:

* Programs using Processing [V2.2.1](https://github.com/totovr/Processing/tree/Processing-2.2.1)

* Programs using Processing [V3.3.6](https://github.com/totovr/Processing/tree/Processing-3.3.6)

* Programs using Processing [V3.3.7](https://github.com/totovr/Processing/tree/Processing-3.3.7)

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

* Processing IDE
* A computer with OSX, Windows, Linux

Alternative:

* Kinect V1
* Kinect V2
* Arduino IDE
* Arduino board
* Atom

### Installing

Install the last stable version of Processing IDE, you can download it from this page:

* [Processing IDE](https://processing.org/download/)

For OSX you just need to unzip the folder and paste the App in the applications folder.

## Test a program sample:

Open Processing IDE and upload the next example:
```
void setup() {
  size(480, 120); //Create a window of 480*120
}

void draw() {
  if (mousePressed) {
    fill(0);
    } else {
      fill(255);
    }
    ellipse(mouseX, mouseY, 80, 80); //If we pressed the mouse a Ellipse will be draw
}
```
This is one simple example of how to draw a Ellipse in the sketch window.

## Also you can use the next IDE to build programs:

* [Processing Online Editor](http://js.do/blog/processing/editor/)
* [Atom](https://atom.io/)

## Contributing

Please read [CONTRIBUTING.md](https://github.com/totovr/Processing/blob/master/CONTRIBUTING.md) for details of the code of conduct, and the process for submitting pull requests to us.

## Versioning

I use [SemVer](http://semver.org/) for versioning.

## Author

Antonio Vega Ramirez:

* [Github](https://github.com/totovr)
* [Twitter](https://twitter.com/SpainDice)

## License

This project is licensed under The MIT License (MIT) - see the [LICENSE.md](https://github.com/totovr/Processing/blob/master/LICENSE.md) file for details

### The instructions to Setup the Kinect are written for Mac OS High Sierra users.

<img src="https://github.com/totovr/SimpleOpenni/blob/master/Images/Skeleton_Tracking.png" width="600">
<img src="https://github.com/totovr/SimpleOpenni/blob/master/Images/deep.png" width="600">
