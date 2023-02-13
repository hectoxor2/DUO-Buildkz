# Introduction to Motion

**Transmitting Motion** is the act of getting motion from one part of the robot to another using shafts, sprockets, gears, etc.

**Transforming Motion** is the act of changing the turning force (torque) and speed. Torque and speed are inverse to each other, meaning when one increases the other decreases.

![](https://2589213514-files.gitbook.io/\~/files/v0/b/gitbook-legacy-files/o/assets%2F-M5yw0n8IneF5-9ybLjT%2F-M8M-iSitDoKjhGR06-t%2F-M8M70BxFPkIW1BBwerA%2FHex%20Shaft.png?alt=media\&token=07cad107-0578-4e4a-9aa8-c89975141b07)

The core to transmitting motion in the REV DUO Build System is the 5mm hex (hexagonal, six sided) shape. This hex shape is incorporated into the other main motion components, such as: sprockets, gears, wheels, and shafts.

[Shafts](https://www.revrobotics.com/ftc/motion/bearings-linear-slides-pillow-blocks/)

are available in a number of different lengths up to 400mm, and can be cut to length if needed.

![](https://2589213514-files.gitbook.io/\~/files/v0/b/gitbook-legacy-files/o/assets%2F-M5yw0n8IneF5-9ybLjT%2F-M8M-iSitDoKjhGR06-t%2F-M8M7Nnyzrz2NVwY8qr6%2FSprockets%20vs%20Gears.png?alt=media\&token=434a77c8-471f-4a01-8749-1e6dd4840779)

|                                                            |                                                |
| ---------------------------------------------------------- | ---------------------------------------------- |
| Better for transmitting motion over long distances         | Can be used for changing rotation direction    |
| Changing sprocket sizes requires changing the chain length |                                                |
| Chain is more forgiving in construction accuracy           | More flexibility in adjusting speed and torque |
| Chain tension and wrap are important                       | Gear spacing is important                      |

### Motion Component Features <a href="#motion-component-features" id="motion-component-features"></a>

Most REV DUO motion parts, mainly plastic sprockets and gears, all have a uniform thickness of 15mm. This helps to improve the iterative design experience. Changing from a gear reduction to a chain and sprocket, or going direct drive, will not require many frame or spacer changes.

![](https://2589213514-files.gitbook.io/\~/files/v0/b/gitbook-legacy-files/o/assets%2F-M5yw0n8IneF5-9ybLjT%2F-M8prG9OBqZu3a21qRCA%2F-M8pu2nOq\_GBUp1NvSAL%2F15mm%20Thickness.png?alt=media\&token=c82c552b-15b5-4205-a131-2d5d7fb464f8)

Product material selection is noted below.

[Traction wheels](https://www.revrobotics.com/rev-for-ftc/motion/wheels-hubs-adapters/wheels/)

and Grip Wheels (

[REV-41-1267](https://www.revrobotics.com/rev-41-1267/)

) are co-molded with a polyurethane tread for increased traction.

#### Motion Components Materials <a href="#motion-components-materials" id="motion-components-materials"></a>

| Component   | Material                         |
| ----------- | -------------------------------- |
| Sprockets   | Acetal (Delrin/POM)              |
| Gears       | Acetal (Delrin/POM)              |
| Pulley      | Acetal (Delrin/POM)              |
| Wheel Body  | Nylon(PA66)                      |
| Wheel Tread | Thermoplastic polyurethane (TPU) |

REV DUO wheels, sprockets, and gears have a M3 bolt hole mounting pattern that is on an 8mm pitch as shown below. This makes it easy to directly mount to REV Robotics brackets, extrusion, and channel. The 8mm pitch is also compatible with many other building systems.

![](https://2589213514-files.gitbook.io/\~/files/v0/b/gitbook-legacy-files/o/assets%2F-M5yw0n8IneF5-9ybLjT%2F-M8prG9OBqZu3a21qRCA%2F-M8puR5vCAlKum6AwcSk%2F8mm%20pitch%20motion%20components.png?alt=media\&token=a15a6157-6dad-4764-a4d9-9f80ea1b6ebb)

Sometimes, it may be desirable to stack together multiples of the same gear or sprocket on a shaft. As a best practice, all components should have the **alignment notch** oriented the same direction on the shaft. The alignment notch can be found on the raised hub on either side of the gear or sprocket.

![](https://2589213514-files.gitbook.io/\~/files/v0/b/gitbook-legacy-files/o/assets%2F-M5yw0n8IneF5-9ybLjT%2F-M8prG9OBqZu3a21qRCA%2F-M8puTGPp9YhNFgvhZ0h%2Fmotion%20component%20notch.png?alt=media\&token=e2f3c69a-59e0-4d22-88d9-e053512f40f2)

In many cases the number of teeth on the gear or sprocket is not divisible by six, the number of sides on the hex shaft, and therefore the relative rotation between two of the same part will result in the teeth being out of alignment with each other. If the first sprocket was put on a shaft with the alignment notch facing upwards, there would be a valley at the top of the sprocket. If the second sprocket was added to the shaft, but rotated clockwise by 60 degrees (by the turn of one flat side), there would be most of a sprocket tooth at the top of that sprocket.

![](https://2589213514-files.gitbook.io/\~/files/v0/b/gitbook-legacy-files/o/assets%2F-M5yw0n8IneF5-9ybLjT%2F-M8prG9OBqZu3a21qRCA%2F-M8pubv0wpi7aytPw2Rq%2Falignment%20notch.png?alt=media\&token=66991c98-64f6-4272-8379-ffb4b3a67248)

It’s possible to build a working system without aligning stacked parts, but it’s not recommended.
