## Prologue

Ever wanted to the be master of art?

Well, this tool allows you to upload any image you can think of directly to [starving artists](https://www.roblox.com/games/8916037983).  
If you are interested in more of Node.js, click [here](https://nodejs.dev/learn) to learn more about it

## Installation

Firstly install [Node.js](https://nodejs.org/en/download/)		Ver > 16.

Download and Install the whole repository and export it to a folder.

## Usage

After you installed the repo and extracted it I recommend you adjust the __SETTINGS.json__ to your liking.

#### Settings parameters

```javascript
// Amount of colors used for the conversion of your image
// Max 256 - Min 1 : 256, 128, 64, 32, 16, 8, 4, 2, 1
// Higher number is lesser quality, if the image has a lot of different colors below 32 can get you striked

"colorBitsDevision": 32,

// Mode
// def: Default ( normal image translation )
// bw1: Black & White ( colored image to black and white rgb average valued image )
// bw2: Black & White Alternate ( colored image )

"mode": "def",

// Invert all colors

"invertColors": false,

// Black & White Alternate sensitivity to conversion

"contrastSensitivity": 128

```
