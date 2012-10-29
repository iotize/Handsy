Handsy
======

A bunch of iOS classes and extensions used for simulating gestures.
For example, in order to press a button, the following code example would suffice:

    [button tap];

In order to press at a certain position, the following code could be used:

    [button tapAtPosition:CGPoint(32, 32)];

Or to tap in the center of the button:

    [button tapAtPosition:[button center]];

This library uses private APIs, and so should not be used in production. However, it serves as very useful during testing.
A big thanks to the Square crew, as much of the implementation is extracted from KIF (https://github.com/square/KIF).
This library is very much a work in progress, and so the API may be subject to potentially drastic change and simplification.
