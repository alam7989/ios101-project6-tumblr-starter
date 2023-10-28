# Project 6 - *Tumblr Posts*

Submitted by: **Audrey Lam**

**Tumblr Posts** is an app that allows users to scroll through previews (image and summary) of Tumblr posts, and select a preview to read the whole post.

Time spent: **2** hours spent in total

## Required Features

The following **required** functionality is completed:

- [X] Setup navigation to the Detail Screen
- [X] Created the Detail View UI
- [X] Add the ability to pass data to the Detail View Controller
- [X] Made personal finishing touches to the UI


The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app functionality!

## Video Walkthrough

![](https://github.com/alam7989/ios101-project6-tumblr-starter/blob/main/project6_walkthrough.gif)

## Notes

Describe any challenges encountered while building the app.
- I had trouble passing data to the Detail View Controller. I saw a commented hint in the DetailViewController file about a prepare(for: segue), so I thought I needed to implement this function in the DetailViewController file. However, after reading the instructions more carefully, I realized I needed to pass data **to** (not from) the Detail View Controller, so this function actually needed to be implemented in the View Controller file. 

## License

    Copyright [2023] [Audrey Lam]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
