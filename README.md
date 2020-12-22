# AnotherCvLibForOfxOpenCv

Since the original ofxOpenCv addon bundled to [OpenFrameworks](https://github.com/openframeworks/openFrameworks) doesn't support some basic stuff (cv::imread, cv::imwrite with `.png` or `.jpg` export), here I placed modified version of static libralies.

## Usage

Simply you can download a library file to replace the one in ofxOpenCv, by using `wget` command or downloading the whole repo by `saving as zip` option.

## How to compile OpenCV library for openFrameworks with your own modification

OpenFrameworks project uses [Apothecary](https://github.com/openframeworks/apothecary) to compile third-party libraries to be used along with the library. You can clone the repository to compile opencv library again for your platform. The libraries here are compiled for `x86_64` arch since OF 0.11.0 supports 64bit system.
You can use `opencv.sh` to compile the same library by yourself. Placing it under `apothecary/apothecary/formulas/opencv` to compile opencv.

## TODO

- upload libraries for different platforms rather than osx (windows, RasPi, iOS...)
