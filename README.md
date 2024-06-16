# Twisted-belt-reducer

## Summary

A concept for a twisted timing belt reducer with a concentric ouput. The idea was to made something small, simple and affordable, using off the shelf pieces. The parts files are [HERE](https://grabcad.com/library/twisted-belt-reducer-1), and the list for this version is [HERE](Parts list.md). This is a link to a [Youtube short](https://www.youtube.com/shorts/Pv9ziZspq7c) showing a simpler version. 

<img src="/imgs/iso1.png" width="400">

The belt goes from the pulley on the shaft of the motor to the idle pulleys in the back, and then to the output pulley just on top of the input pulley. The pulleys ares slightly separated, and in this case the ratio is 1:3.75.

The idle pulleys are mounted on the tensor, which can be pulled back (tensioning the belt) using a couple of bolts.

The output shaft is supported by two radial bearings (688-2RS, pretty common). To prevent it from falling inwards, you can use a collar (as the image shows), a shoulder or a interference fit.

<img src="/imgs/insides.png" width="400">

The holes in the mounting plate are distributed as the ones on a NEMA17.

## Open belt version

In my first design, this project used an open belt, as I dont have a big assortment of closed belts. The printed output pulley was as the image below shows. It has no teeths, but a couple of holes where the timing belt ends pass through and are attached to each other using a zip tie.

<img src="/imgs/pul1.png" width="400">

In this case, the output cannot rotate 360° degrees, so watchout. The printed output pulley gives the chance to put a potentiometer or an angle sensor in between the pulleys

## Future work

- To do some torque tests
- Using this in a project, probably a robotic arm.
- To use this in a DC or brushless motor. 
- To implement position control using this system with a DC or brushless motor.






