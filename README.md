<div align="center">
<h1><kbd>🧩 LoadingCar</kbd></h1>
An extension for MIT App Inventor 2.<br>
This is a custom extension developed by TechHamara using Fast. It provides a loading animation for a car.<br><a href='https://t.me/techhamara91/' target='_blank'>Telegram</a> | <a href='https://github.com/TechHamara/' target='_blank'>GitHub</a><br><a href='https://techhamara.blogspot.com/' target='_blank'>Blogger</a> | <a href='https://m.youtube.com/c/TECHHAMARA?sub_confirmation=1' target='_blank'>YouTube</a><br><a href='https://github.com/TechHamara/Th_Free_Extensions' target='_blank'><small><u>Find More Extension</u></small></a><br><a href='https://github.com/TechHamara/Th_Extensions_List/blob/main/LICENSE.md#terms-and-conditions-for-the-extension' target='_blank'><small><u>Terms & Conditions</u></small></a>
</div>

## 📝 Specifications
* **
📦 **Package:** io.th.loadingcar
💾 **Size:** 20.23 KB
⚙️ **Version:** 1.1
📱 **Minimum API Level:** 7
📅 **Updated On:** [date=2025-05-18 timezone="Asia/Calcutta"]
💻 **Built & documented using:** [FAST](https://community.appinventor.mit.edu/t/fast-an-efficient-way-to-build-extensions/129103?u=jewel) <small><mark>v2.8.4</mark></small>

## <kbd>Events:</kbd>
**LoadingCar** has total 11 events.

### ZoomedIn
Event raised when the car is zoomed in.

| Parameter | Type
| - | - |
| oldScale | number
| newScale | number

### ZoomedOut
Event raised when the car is zoomed out.

| Parameter | Type
| - | - |
| oldScale | number
| newScale | number

### ZoomReset
Event raised when the car zoom is reset.

| Parameter | Type
| - | - |
| oldScale | number
| newScale | number

### ScaleChanged
Event raised when the car scale is changed.

| Parameter | Type
| - | - |
| oldScale | number
| newScale | number

### AnimationInitialized
Event raised when the animation is initialized.

### AnimationPaused
Event raised when the animation is paused.

### AnimationResumed
Event raised when the animation is resumed.

### AnimationRestarted
Event raised when the animation is restarted.

### AnimationCycleCompleted
Event fired on each animation cycle.

### TextRevealed
Event raised when the message text is revealed (when zoomed out enough).

### TextHidden
Event raised when the message text is hidden (when zoomed in).

## <kbd>Methods:</kbd>
**LoadingCar** has total 11 methods.

### ZoomIn
Zoom in the car animation by incrementing the scale.

### ZoomOut
Zoom out the car animation by decrementing the scale and revealing text.

### ResetZoom
Reset the car animation scale to its default size.

### Initialize
Initialize inside an arrangement.

| Parameter | Type
| - | - |
| arrangement | component

### Remove
Removes the car animation from its parent.

### PauseAnimation
Pauses the car animation.

### ResumeAnimation
Resumes the car animation.

### RestartAnimation
Restart the car animation.

### ShowMessageText
Show the message text without changing the car scale.

### HideMessageText
Hide the message text without changing the car scale.

### ZoomToRevealText
Zoom out to reveal the message text at optimal visibility.

## <kbd>Setters:</kbd>
**LoadingCar** has total 11 setter properties.

### BackgroundColor
Sets the background color of the loading animation.

* Input type: `text`

### CarColor
Sets the car body color.

* Input type: `text`

### RoadColor
Sets the road markings color.

* Input type: `text`

### LightsColor
Sets the car lights color.

* Input type: `text`

### LicensePlateColor
Sets the license plate background color.

* Input type: `text`

### LicensePlateText
Sets the license plate text.

* Input type: `text`

### AnimationSpeed
Sets the animation speed in seconds (1-10, smaller is faster).

* Input type: `number`

### CarScale
Sets the scale of the car animation (0.2 to 3.0).

* Input type: `number`

### MessageText
Sets the message text to display when zoomed out.

* Input type: `text`

### MessageTextColor
Sets the message text color.

* Input type: `text`

### ShowMessage
Sets whether to show the message text when zoomed out.

* Input type: `boolean`

## <kbd>Getters:</kbd>
**LoadingCar** has total 11 getter properties.

### BackgroundColor
Sets the background color of the loading animation.

* Return type: `text`

### CarColor
Sets the car body color.

* Return type: `text`

### RoadColor
Sets the road markings color.

* Return type: `text`

### LightsColor
Sets the car lights color.

* Return type: `text`

### LicensePlateColor
Sets the license plate background color.

* Return type: `text`

### LicensePlateText
Sets the license plate text.

* Return type: `text`

### AnimationSpeed
Sets the animation speed in seconds (1-10, smaller is faster).

* Return type: `number`

### CarScale
Sets the scale of the car animation (0.2 to 3.0).

* Return type: `number`

### MessageText
Sets the message text to display when zoomed out.

* Return type: `text`

### MessageTextColor
Sets the message text color.

* Return type: `text`

### ShowMessage
Sets whether to show the message text when zoomed out.

* Return type: `boolean`

