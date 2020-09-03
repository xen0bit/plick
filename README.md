# plick
OS Hosted Audio Control interaction with websites via headphone play/pause button


# Usage

```
plick.registerMainLoop(function (clickDown) {
//clickDown is a bool representing the state of the headphone button
//It can call any function that you want to be triggered by the physical play/pause button
                    alert(clickDown);
                });
```