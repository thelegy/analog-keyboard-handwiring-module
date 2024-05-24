# Analog Keyboard Handwiring Module

Check out the [Void Switch](https://github.com/riskable/void_switch) by Riskable.

There are resources available how you can build your own compatible PCBs for a custom keyboard.
Unfortunally I have two problems with this approach:
- I want to play around with sculpted keyboards. Iterating with pcbs is not fun, so I want a module, that I can handsolder.
- I do not really like the WS2812 or SK6812 and very much prefer the SK9822 leds. They use an SPI protocol which makes them less sensitive to timing and they have a common brightness, which allows them to be dimmed way down without loosing any color resolution.

The only sensible way was to start this project.

I stumbled over [Atopile](https://atopile.io/) and it looks quite nice, so I figured this would make for a nice small project to evaluate it.
