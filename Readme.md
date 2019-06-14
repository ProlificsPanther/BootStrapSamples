# How to use a Bootstrap Progress bar in Panther to display results

1) Use {{emit:widgetname}} to emit all the single line text fields which are in your screen.

2) Pass your values to next screen using “send BUNDLE” in the JPL from the first screen and use sm_jform to call the next screen in which you will receive the bundle.

3) Now the received value will be used in the style tag for setting the width of your div by using {{value:widgetname}}

### Example

<div class="progress">

<div class="progress-bar progress-bar-info progress-bar-striped" role="progressbar" aria-valuenow="70" aria-valuemin="0" aria-valuemax="100" style="width:{{value:chemistry}}%">

4) Here “chemistry” is the name of widget which contains a value.

5) Enter the values you wish to in the fields on the first screen and press the Percentage button.

6) You will notice that the values are displayed on the next screen with progress bars.
Need a Panther Web 551 Redhat Image? [Click Here](https://hub.docker.com/r/prolificspanther)

[Click Here](https://www.prolifics.com/panther-trial-license-request) for a 45 day license.

How to setup a Panther Servlet Web Application? [Click Here](https://github.com/ProlificsPanther/PantherWeb/releases)
