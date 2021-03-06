# Move transition for OBS Studio

Plugin for OBS Studio to move source to a new position during scene transition

Unzip the download in the OBS folder for example:
C:\Program Files (x86)\obs-studio\
or
C:\Program Files\obs-studio\

Start OBS Studio 64 bit
Add a Move transition.

# Move transition
Transition that moves all sources to a new position
## Properties
* **Easing**
  * **No easing**
  Linear movement of the sources.
  * **Ease in**
  Eases the start of the movement of the sources.
  * **Ease out**
  Eases the end of the movement of the sources.
  * **Ease in and out**
  Eases the start and end of the movement of the sources.
* **Easing Function**

  See https://easings.net
* **Zoom in**
New sources are zooming in on appearing, instead of staying the same size.
* **Position in**
The position new sources are coming from.
* **Ease out**
Eases the end of the movement of the sources.
* **Zoom out**
Old sources are zooming out on disappearing, instead of staying the same size.
* **Position out**
The position old sources are going to.
* **Curve**
The amount of curve for the path between the start and end position. 0.00 is no curve. Postive is curve away from canvas center. Negative is curve towards canvas center.
* **Transition in**
New sources are transitioning in using this transition on appearing.
* **Transition out**
Old sources are transitioning out using this transition on disappearing.
* **Match if source name contains the other source name**
Match sources that contain the name of an other source.
* **Transition move**
Matched sources are transitioning in using this transition.
* **Transition move scale type**
  * **Max only**
  Scale to aspect ratio, but only to the maximum size of each source
  * **Aspect**
  Always scale the sources, but keep aspect ratio
  * **Stretch**
  Scale and stretch the sources to the size of the transition