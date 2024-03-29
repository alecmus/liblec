# liblec
The liblec C++ libraries

<p>
  <img alt="GitHub issues" src="https://img.shields.io/github/issues-raw/alecmus/liblec">
  <img alt="GitHub closed issues" src="https://img.shields.io/github/issues-closed-raw/alecmus/liblec">
</p>

### About the Library
The liblec library is a set of C++ libraries designed for the rapid development of modern, efficient, and easy to maintain C++ applications. Development of the library started in 2018.

### Naming
The name is a pun on the name of the original author: a set of libraries by Alec, hence liblec. So it is with the name of the libraries contained within liblec, e.g. lecnet stands for Alec's network library.

### About the Author
More information on the author, Alec Musasa, can be obtained at https://github.com/alecmus

### The Libraries
Below is a list of the libraries that are part of liblec:

Library Name | Description          | Repository                         | Status
------------ | -------------------- | ---------------------------------- | -------------
lecui        | A gui library        | https://github.com/alecmus/lecui   | Released
lecnet       | A networking library | https://github.com/alecmus/lecnet  | Released
cui          | A gui framework      | https://github.com/alecmus/cui     | Released
leccore      | Core liblec library  | https://github.com/alecmus/leccore | Released
lecpub       | A publishing library | Private repository                 | Pending initial release

### Additional Notes
The following libraries are being actively developed. The latter is yet be made public once an important threshold is reached
1. leccore (currently in alpha status, stage 2 of 4)
2. lecpub (currently in alpha status, stage 1 of 4)

### lecui versus cui
The lecui library is a complete rebuild and does not inherit from cui. It is a more modern, and more advanced library with many features that are not supported in the cui library. It features newer technologies, greater flexibility and a more robust architecture.

Below is a summary of some of the features supported by lecui that are not supported by cui:

 * hardware acceleration (when platform supports it)
 * transparency channel in all widgets
 * text formatting in labels
 * an html text editor (in place of a richtext editor in cui)
 * panels
 * the ability to close widgets at runtime
 * tab panes support 8 different orientation versus a single orientation (tabs on the left) in cui
 * progress indicator widget (in addition to the progress bar)
 * slider widget
 * the ability for the user to make custom widgets in which they can define their own drawing

 ... and more.

 Development of the lecui library started early 2019, first alpha release was in mid-2021, and the expected date for the first beta release is late 2021.
