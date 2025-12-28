# ESPHome ColorShadowRGB
[ESPHome](https://esphome.io/) yaml config for RCTESTFLIGHT Color Shadow LED Lamp to allow the device to be controlled by [Home Assistant](https://www.home-assistant.io/).

RCTESTFLIGHT product page: https://www.rctestflight.com/store/p/color-shadow-lamp

Youtube: https://youtu.be/R5_rlyRI9C4?t=1037

## Physical Controls
- dials set R/G/B *percentage*
- button press switches between effects (none/pulse/random/flicker)
- double click button to turn off

## Bugs
- double press turns on too, but that is silly, single press also turns on but selects an effect mode too
- the dials should adjust the *absolute* R/G/B value not the percent

## Todo
- support original direct/mixed modes
- move effects selection to long press since short press will do modes

Feel free to submit issues or pull requests.
