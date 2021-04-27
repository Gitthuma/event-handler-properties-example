Event handler properties

There are many different event handler properties available. Let's experiment.

First, make a local copy of random-color-eventhandlerproperty.html, and open it in your browser. It's just a copy of the simple random color example we've played with already. Now try changing btn.onclick to the following different values in turn, and observing the results in the example:

- btn.onfocus and btn.onblur — The color changes when the button is focused and unfocused; try pressing the tab to focus on the button and press the tab again to focus away from the button. These are often used to display information about filling in form fields when they are focused, or displaying an error message if a form field is filled with an incorrect value.
- btn.ondblclick — The color changes only when the button is double-clicked.
- window.onkeypress, window.onkeydown, window.onkeyup — The color changes when a key is pressed on the keyboard. The keypress event refers to a general press (button down and then up), while keydown and keyup refer to just the key down and key up parts of the keystroke, respectively. Note: It doesn't work if you try to register this event handler on the button itself — we've had to register it on the window object, which represents the entire browser window.
- btn.onmouseover and btn.onmouseout — The color changes when the mouse pointer hovers over the button, or when the pointer moves off the button, respectively.

Ref: https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events

Live web: https://gitthuma.github.io/event-handler-properties-example/
