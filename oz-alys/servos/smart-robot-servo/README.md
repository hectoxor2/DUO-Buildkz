# Smart Robot Servo

The REV Robotics Smart Robot Servo (SRS) (

[REV-41-1097](https://www.revrobotics.com/rev-41-1097/)

) is a configurable metal-geared servo that takes the guesswork out of aligning and adjusting servo based mechanisms. One SRS can be used as a standard angular servo, a custom angular servo, and a continuous rotation servo by simply changing its settings.

![](https://2589213514-files.gitbook.io/\~/files/v0/b/gitbook-legacy-files/o/assets%2F-M5yw0n8IneF5-9ybLjT%2F-M95GquH9Q5xxbGh4P4K%2F-M95GvywvJjRnMyKX-5f%2FAA\_Smart\_Robot\_Servo\_Single.png?alt=media\&token=719199e1-3ba3-4319-b564-a2521792bcde)

The REV Robotics Smart Robot Servo includes the following features:

*
  * 270° motion over full input pulse range
*
  *
    * Set right and left angular limits
    * SRS will not move past limits
  *
    * Speed and direction set by input pulse

**Mechanical Specifications**

| ​                         | ​                        |
| ------------------------- | ------------------------ |
| **Stall torque (at 6V)**  | 13.5 kg-cm / 187.8 oz-in |
| **Speed (at 6V)**         | 0.13s/60º                |
| **Maximum angular range** | 270º                     |
| **Gear Material**         | Brass                    |
| **Spline Type**           | 25T                      |
| **Dimensions**            | 40.2mm x 20.0mm x 38.0mm |
| **Weight**                | 2.05oz.                  |

**Electrical Specifications**

| ​                         | Min  | Nominal | Max  |
| ------------------------- | ---- | ------- | ---- |
| **Voltage Rating**        | 4.8V | 6.0V    | 7.4V |
| **Stall Current (at 6V)** | ​    | ​       | 2.0A |

The REV Robotics SRS comes with the following:

* Servo horn (arm) assortment
* Servo horn mounting hardware

_Is a servo the right actuator for your mechanism? See the_

_Choosing an Actuator_

_section to learn more._

Out of the box, the SRS operates as a 270° servo. However, the REV SRS Programmer can reconfigure the SRS to set angular limits or switch it into a continuous rotation mode.

_For more information on how to use the SRS programmer to change the servo modes see the_

[_SRS Programmer_](broken-reference)

_section_

The default range for the SRS is 270°. This range is mapped to an input pulse range of 500μs to 2500μs with 1500μs as the center point. The image below describes the pulse-to-angle relationship.

![](https://2589213514-files.gitbook.io/\~/files/v0/b/gitbook-legacy-files/o/assets%2F-M5yw0n8IneF5-9ybLjT%2F-MB\_vrFI\_mJbhAOGXIO5%2F-MB\_yzhf7dnGkYfx6zkp%2FServo\_270\_Range\_Full\_Green-01.png?alt=media\&token=db791fac-0f86-42d8-9651-1c0e42ae87ad)

The SRS can be configured with the SRS Programmer to operate in a continuous rotation mode. In this mode, the same input pulse range is mapped to direction and speed. The table below lists the pulse mapping for direction and speed.

![](https://2589213514-files.gitbook.io/\~/files/v0/b/gitbook-legacy-files/o/assets%2F-M5yw0n8IneF5-9ybLjT%2F-M8WQp\_aU3jlfmzyZA5V%2F-M8WUtfWcre4DktYBnv0%2FScreenshot%20\(13\).png?alt=media\&token=0483c54f-8ec2-4be0-a3e8-b5dd3374655a)

The SRS can be easily configured with the SRS Programmer to limit right and left motion at two user-defined angles. Input pulses that occur past the limits will be ignored and the SRS will hold the limit angle. Any two angles can be set as limits as long as the left limit is left of the center dead band and the right limit is to the right of the center dead band. The table below shows the valid regions for left and right limits.

![](https://2589213514-files.gitbook.io/\~/files/v0/b/gitbook-legacy-files/o/assets%2F-M5yw0n8IneF5-9ybLjT%2F-MB\_vrFI\_mJbhAOGXIO5%2F-MB\_z21vt7t6VYO6gk0T%2FServo\_270\_Range\_Limit\_Too\_Close.png?alt=media\&token=05207ceb-7734-400f-9423-eed9fd439aab)

Once valid limits are programmed, the SRS will ignore any pulses that exceed the limits and hold the limit angle. For example, the image below exhibits what would happen if a left limit of -30° and a right limit of +60° was set.

![](https://2589213514-files.gitbook.io/\~/files/v0/b/gitbook-legacy-files/o/assets%2F-M5yw0n8IneF5-9ybLjT%2F-MB\_vrFI\_mJbhAOGXIO5%2F-MB\_z3iQG92g4sFKXPuk%2FServo\_Full\_270\_Range\_And\_Limits-01.png?alt=media\&token=b86e324d-b901-48dc-af88-fca499bb04f7)
