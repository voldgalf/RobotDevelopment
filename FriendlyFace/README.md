# FriendlyFace

### Overview

A simple customizeable face made with C with SDL

- Customizable face selection
- *Emotion* controlled facial expressions

### Emotion Control

#### What is it?

The Emotion Control Protocol allows the selected face to change depending on value read

#### How does it work?

The FriendlyFace program reads an *emotion* value from a server. This value is then used to determine the current face of FriendlyFace. 

#### A major problem ... and solution

Socket and server latency may cause the FriendlyFace to lag, even crash.

This is fixed by having the Emotional Control Protocol operate in a seperate thread, without interfering with the main thread
