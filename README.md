# Vehicle Builder

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
                 
## Description
  
A node.js program to build custom cars, trucks and motorbikes. Once built, you can execute some simple commands on the vehicle such as starting it, speeding it up or down, and reversing it. On trucks, you can also tow other vehicles. On motorbikes, you can also specify what wheels you want on it, and perform wheelies!
  
## Table of Contents
  
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contributing](#contributing)
- [Credits](#credits)
- [Tests](#tests)
- [Questions](#questions)
  
## Installation
  
Prerequisite: You must have node.js and npm (npm is typically included with node) installed in your local git-compatible command line interface prior to installing this program. If you do not have node & npm installed, please follow the installation instructions [here](https://nodejs.org/).

Download the source code for the project with a <code>git clone</code> on this repository in your CLI using the URL or SSH link provided in the "code" button at the top of this repository. Then, <code>cd</code> in your terminal to the directory that contains the cloned repo, and run an <code>npm i</code> to ensure that you have all required dependencies to run the package successfully.
  
## Usage
  
To use the program successfully: open a CLI window and <code>cd</code> to the directory that contains the code (specifically index.js) for this program. Then run <code>npm run start</code>, which will then start the program. You can first either create your own custom vehicle, or select one of the prebuilt vehicles to use. Once you build or select a vehicle, you will be taken to a menu of options to interact with or list details of your vehicle. 

These options include:
- Print details: shows all the build details of your vehicle
- Start vehicle: "starts the vehicle", which will change the vehicles status to started and allow you to do most of the other actions listed. Logs in the console that the vehicle was started.
- Accelerate 5 MPH: increases the "vehicle speed" by 5 MPH, unless you have reached the top speed. Logs in the console that the speed was increased, or gives an exception message.
- Decelerate 5 MPH: decreases the "vehicle speed" by 5 MPH, unless the vehicle speed is 0. Logs in the console that the speed was decreased, or gives an exception message.
- Stop vehicle: "stops the vehicle", which will change the vehicles status to stopped and will prevent you from doing most of the other actions listed. Logs in the the console that the vehicle was stopped.
- Turn right: "turns the vehicle right", which will log in the console that the vehicle turned right, or gives an exception message.
- Turn left:  "turns the vehicle left", which will log in the console that the vehicle turned left, or gives an exception message.
- Reverse:  'reverses the vehicle", which will log in the console that the vehicle is going in reverse, or gives an exception message.
- Tow a vehicle (only functional with trucks): If the vehicle is a truck and the truck is started, will bring you to a list of cars to be towed, and allows you to "tow" one. Will console log that the vehicle is being towed. If the vehicle is not a truck, you select the same truck you are using to "tow", or the selected vehicle exceeds the trucks towing capacity, will log an exception message in the console.
- Do a wheelie (only funcional with motorbikes): If the vehicle is a motorbike and the motorbike is started, will log in the console that the motorbike is doing a wheelie. If the vehicle is not a motorbike, will log an exception message in the console.
- Select or create another vehicle: Brings you back to the starting menu, where you can create (build) or select a different vehicle to perform actions on.
- Exit: Exits the program.

For a walkthrough on how to use this project, please see the video linked:

## License
This project uses MIT License.

Please refer to LICENSE file for more information.
 
## Contributing
  
No need to contribute as project is already completed. However, feel free to fork and make it your own!
  
## Credits
  
Base code provided by edX and their respective developers, written code by jsparrowio (Josh Garrett).
  
## Tests
  
To test, follow installation and usage instructions above.
  
## Questions
  
If you have any additional questions, please contact me at:
  
[GitHub](https://www.github.com/jsparrowio)
  
[jsparrowio@outlook.com](mailto:jsparrowio@outlook.com)