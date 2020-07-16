# liblec
The liblec C++ libraries

## ABOUT THE LIBRARY
The liblec library is a set of C++ libraries designed for the rapid development of modern, efficient, and easy to maintain C++ applications.

## NAMING
The name is a pun on the name of the original author: a set of libraries by Alec, hence liblec. So it is with the name of the libraries contained within liblec, e.g. lecnet stands for Alec's network library.

## ABOUT THE AUTHOR
More information on the author, Alec T. Musasa, can be obtained at https://github.com/alecmus

## THE LIBRARIES
Below is a list of the libraries that are part of liblec:

Library Name | Description          | Repository                        | Status
------------ | -------------------- | --------------------------------- | -------------
lecnet       | A networking library | https://github.com/alecmus/lecnet | Released
cui          | A gui framework      | https://github.com/alecmus/cui    | Released
lecui        | A gui library        | Private repository                | Pending initial release
lecpub       | A publishing library | Private repository                | Pending initial release

## ADDITIONAL NOTES
The following libraries, while currently private, are being actively developed and will be made public once the initial release is ready
1. lecui (currently in alpha status, stage 3 of 4)
2. lecpub (currently in alpha status, stage 1 of 4)

## lecui versus cui
The lecui library is a complete rebuild and does not inherit from cui. It is a more modern, and more advanced library with many features that are not supported in the cui library. Furthermore, it offers hardware acceleration.

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
 
 Development of the lecui library started in late 2018 and the expected date for beta release is late 2020.
