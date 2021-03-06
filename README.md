# Pre-work - Tip$Cal

Tip$Cal is a tip calculator application for iOS.

Submitted by: Devon Maguire

Time spent: 10 hours spent in total

## User Stories

The following **required** functionality is complete:

* [X] User can enter a bill amount, choose a tip percentage, and see the tip and total values.
* [X] Settings page to change the default tip percentage.

The following **optional** features are implemented:
* [ ] UI animations
* [ ] Remembering the bill amount across app restarts (if <10mins)
* [ ] Using locale-specific currency and currency thousands separators.
* [X] Making sure the keyboard is always visible and the bill amount is always the first responder. This way the user doesn't have to tap anywhere to use this app. Just launch the app and start typing.

The following **additional** features are implemented:

- [X] Users can change what percentages are displayed in the segmented control options.

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='http://i.imgur.com/WtFsuXV.gif' title='Video Walkthrough' width='' alt='Video Walkthrough'/>

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

Describe any challenges encountered while building the app.
The biggest challenge was my lack of knowledge of the language. For almost everything I had to do a bit of research to find out what code to use to
get the application to do what I wanted it to. There were a couple of issues that took more searching to find. One was getting element of the UI to
match the colorscheme, as some things could be manipulated using the custom toolbar in xcode while others had to be altered progmatically. Another
was the NSDefault library and checking for nil.

## License

    Copyright [2015] [Devon Maguire]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
