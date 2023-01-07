# Crosshair-Generator

A Rust application for drawing a crosshair over a target process in Windows.

## Installation

### Option 1: Download Latest Release

To install Crosshair-Generator, you can download the latest release from the [releases page](https://github.com/itscrabs/crosshair-generator/releases). Once the download is complete, you can run the executable to launch Crosshair-Generator.

### Option 2: Compile from Source

Alternatively, you can clone the GitHub repository and compile the executable yourself. To do this, you will need to have the latest version of Rust installed on your system.

First, clone the repository:

git clone https://github.com/itscrabs/crosshair-generator.git

Copy code

Then, navigate to the project directory and run the following command to build the executable:

cargo build --release

Copy code

The compiled executable will be located in the `target/release` directory.

## Usage

To launch Crosshair-Generator, run the executable file. The program will open a graphical user interface (GUI) where you can select the target process and customize the appearance of the crosshair.

## Examples

To draw a red crosshair of size 10 pixels over the process "notepad.exe":

1. Open Crosshair-Generator and select "notepad.exe" from the process dropdown menu.
2. Select "red" from the color dropdown menu.
3. Enter "10" in the size field.
4. Click the "Apply" button to draw the crosshair.

To draw a blue crosshair of size 5 pixels over the process "mspaint.exe":

1. Open Crosshair-Generator and select "mspaint.exe" from the process dropdown menu.
2. Select "blue" from the color dropdown menu.
3. Enter "5" in the size field.
4. Click the "Apply" button to draw the crosshair.