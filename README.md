# pxt-apds9960

#### Description
This is the APDS9960 for microbit@makecode editor, for now there is only color detect but should be enough for June 1st children's day workshop.

### TODO:
- proximity engine
- gesture
- more apds9960 config blocks 

#### Install Guide

You may load this package by coping the ulr and paste into the add package panel.

#### User Guide

Read the Chip's ID first, if it return 0x0 or 0xff check your wirings. If it read something other than 0xAB (171) you may got an APDS9930 or 9900 or a cloned chips. 

The gesture engine won't work on 9930 and 9900, but the proximity and color sensing should be ok. 

## License

MIT

## Supported targets

* for PXT/microbit
(The metadata above is needed for package search.)

```package
apds9960=github:Kittenbot/pxt-apds9960
```