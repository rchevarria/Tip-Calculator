# Pre-work - *Tip Calculator*

**Tip Calculator** is a tip calculator application for iOS.

Submitted by: Ryan Chevarria

Time spent: 4 hours spent in total

## User Stories

The following **required** functionality is complete:

* [ ] User can enter a bill amount, choose a tip percentage, and see the tip and total values.
* [ ] User can select between tip percentages by tapping different values on the segmented control and the tip value is updated accordingly


The following **additional** features are implemented:

* [ ] Keyboard appears upon launching the app
* [ ] Numerical values are updated in real time as user types / clears the text field. 


## Video Walkthrough

Here's a walkthrough of implemented user stories:

![](https://i.imgur.com/EztFw4a.gif)


GIF created with QuickTime

## Notes

Two challenges that appeared which have been addressed in the additional features - have been the ability to prioritize the text field. Upon starting the app, the user should be able to begin typing their bill amount. This was solved through a simple swiftUI command - BecomefirstResponder() 
The second challenge was updating the values in the Tip: and Total: sections instantly upon user entry. This was solved through a builder interface feature of the text field. It was changed to "Editing Changed". This now updates values in real time without the user having to necessarily use the segmented bar to cause a change.  

## License

    Copyright [2021] [Ryan Chevarria]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.



