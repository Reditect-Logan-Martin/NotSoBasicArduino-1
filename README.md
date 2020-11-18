# NotSoBasicArduino
 - Logan Martin
 
 
## Table of Contents
* [Table of Contents](#TableOfContents)
* [LED_Fade](#LED_Fade)
* [Hello_LCD](#Hello_LCD)
* [FillMeInLAter](#FillMeInLAter)
---

## LED_Fade

### Description & Code
An LED that slowly faded in and then out using the code below:

```C++
void loop() {
  // fade in from min to max in increments of 5 points:
  for (int fadeValue = 0 ; fadeValue <= 255; fadeValue += 5) {
    // sets the value (range from 0 to 255):
    analogWrite(ledPin, fadeValue);
    // wait for 30 milliseconds to see the dimming effect
    delay(30);
  }

  // fade out from max to min in increments of 5 points:
  for (int fadeValue = 255 ; fadeValue >= 0; fadeValue -= 5) {
    // sets the value (range from 0 to 255):
    analogWrite(ledPin, fadeValue);
    // wait for 30 milliseconds to see the dimming effect
    delay(30);
  }
}
```
The led fades because it is getting stronger (max 250) and then getting weaker (least 0). Going 0 to 250 makes it appear like it is fading.

### Evidence
{Code}https://create.arduino.cc/editor/lmartin27/34820046-7d25-45f2-8caa-2fdb87085645
### Images
<img src="/Led Images/IMG_20201117_132923.jpg/" alt="Fading LED" width="300" height="300">
### Reflection

I was confused on how to code it at first,but most of the time I was struggling with just trying to put a wire where it needs to be.

## Hello_LCD

### Description & Code
Description goes here

Here's how you make code look like code:

```C++
Code goes here
```
Talk about how the code works, here....

### Evidence
link goes here

### Images
draw it yourself, take a picture, make a fritzing, whatever you want to EFFECTIVELY communicate how its put together.

### Reflection

