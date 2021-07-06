Campaign Browser
================

# Solution
Please check out this [Pull Request](https://github.com/timdolenko/interviewCaseStudy-westwing/pull/1)

# Summary
Currently, the size of each cell has a fixed height. We want to change this to use a dynamic height based on the cell's content. Additionally, we want to change to position of text which is currently rendered on top of the image. We want to render all text contents below the image.

# Requirements
- Use a dynamic height of the cell and make it dependent on the cell's contents.
- The image should take the full available width of the screen and dynamically adjust its height with an aspect ratio of 4:3.
- The text should go below the image. There should not be any space between the title text and the image, because the image already contains whitespace.
- The text should have a padding of 8 points to the left and to the right.
- There should be 8 points spacing between the title text and the description text.
- The title text should break into two lines at most. Every text which is longer than two lines should be cut after the second line.
- The description text should not have any length restrictions.

![Screenshot of the running app](screenshot.png)

Loads a list of campaigns from the internet and displays them.

# Dependency Management

The project has some dependencies to third-party libraries. They are managed via [CocoaPods](https://cocoapods.org).
