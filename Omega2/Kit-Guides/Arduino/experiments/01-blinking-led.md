---
title: Blinking an LED
layout: guide.hbs
columns: two
devices: [ Omega , Omega2 ]
order: 1
---

## Blinking an LED {#blink-led-arduino-kit}

// little intro about our first sketch that we'll run on the arduino dock


// TODO: include shared content on LEDs

## Building the Circuit

Before we start building our experiment, let's first go over some of the building blocks when it comes to experimenting with electronics.

// TODO: insert jumper wires section

// TODO: insert breadboard section

### Hooking up the Components
// can copy from the starter kit, but adapt it for the Arduino Dock

## Writing the Code

First, prepare your computer by following [our guide to flashing sketches wirelessly to the Arduino Dock](#flash-arduino-dock-wirelessly).

Then fire up the Arduino IDE on your computer and paste the following:

```arduino
void setup() {
    
}
```

// write an arduino sketch to blink an LED

### What to Expect

// flashing wirelessly using the IDE

### A Closer Look at the Code

// highlight something interesting about the code

#### Setting GPIOs to Output

// go through the setup commands we used to use a gpio as an output

#### Variable Scope

// talk about how we defined the LED gpio globally, and can therefore use it everywhere in the program
// give an example of a local variable