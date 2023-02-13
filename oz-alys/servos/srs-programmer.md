# SRS Programmer

The REV Robotics SRS Programmer (

[REV-31-1108](https://www.revrobotics.com/rev-31-1108/)

) is the key to unlocking all the smart features of the Smart Robot Servo (SRS) (

[REV-41-1097](https://www.revrobotics.com/rev-41-1097/)

).

Switching between continuous rotation, standard servo, and custom angular modes is easy as pressing a button. The SRS Programmer can not only program the SRS, but it is also acts as a standalone servo tester for any standard RC servo.

![](https://2589213514-files.gitbook.io/\~/files/v0/b/gitbook-legacy-files/o/assets%2F15mm%2F-M8WcLi6koTauMV2xJ63%2F-M8WdOZiJLaHBzbA2oeW%2F1.png?generation=1590776144189561\&alt=media)

The REV Robotics SRS Programmer includes the following features:

*
  * Reset to factory defaults
*
  * Manual position/direction
* Intuitive operation with LED feedback

| **Mechanical Specifications** |   |
| ----------------------------- | - |
|                               |   |
|                               |   |

| **Electrical Specifications** | ​              |
| ----------------------------- | -------------- |
| **Power Source**              | 4 AA batteries |
| **Power Output**              | 6V nominal     |
| **Logic Level (Signal Out)**  | 3.3V           |
| **Output Pulse Width Range**  | 550μs – 2450μs |
| **Center Pulse Width**        | 1500μs         |

The SRS Programmer has several operating modes for configuring and testing the REV Smart Robot Servo. The following sections describe each operating mode in detail.

Before using the SRS Programmer to switch modes or program your servo motor, check that the batteries are not low. If your SRS Programmer has not been used in a while, please put in a fresh set of batteries to avoid potentially corrupting the firmware of your servo motor.

Follow the steps below to switch a REV Smart Robot Servo between Continuous Mode and Servo Mode. The figure below shows the process to select Continuous Mode.

![](https://2589213514-files.gitbook.io/\~/files/v0/b/gitbook-legacy-files/o/assets%2F-M5yw0n8IneF5-9ybLjT%2F-M8WcLi6koTauMV2xJ63%2F-M8Wf8PNHBydvaPKp5Ax%2FScreenshot%20\(25\).png?alt=media\&token=74baa009-be7d-4cde-9334-a68fd7beaa35)

1.  1\.

    Connect the SRS to the programmer.
2.  3\.

    Slide the mode switch to the desired mode: C - Continuous, S - Servo.
3.  4\.

    Press and release the PROGRAM button once.
4.  5\.

    The PROGRAM LED should blink and then stay solid indicating success.

Follow the steps below to set the angular limits for the Servo Mode. The figure below shows an example of setting a left and right limits at -30° and +60° respectively.

![](https://2589213514-files.gitbook.io/\~/files/v0/b/gitbook-legacy-files/o/assets%2F-M5yw0n8IneF5-9ybLjT%2F-MlCNxlQ-LJofBQhcpVW%2F-MlCO4tB8H8Yu0ojscjH%2FServo\_Full\_270\_Range\_And\_Limits-01%20\(1\).png?alt=media\&token=7a2475d6-978c-4c1e-bfa6-2ecbd2194372)

Start with the SRS already configured in Servo Mode, see section

[Switching Modes](broken-reference)

for instructions.

1.  1\.

    Connect the SRS to the programmer.
2.  3\.

    Slide the mode switch to S position.
3.  4\.

    This step is optional, but recommended to make it easier to see the valid limit ranges. Please refer to the SRS User's Manual for more information about the valid limit ranges.

    1.  1\.

        Press and release the TEST button twice to enter Manual Test Mode (see

        [Test Modes](broken-reference)

        for more information).
    2.  2\.

        Press the PROGRAM button to center the servo at 0°.
    3.  3\.

        Press and release the TEST button once to leave the test mode.
4.  5\.

    Manually rotate the servo to the desired left limit position.
5.  6\.

    Press and release the LEFT button. The LEFT LED will illuminate if the position is valid.
6.  7\.

    Manually rotate the servo to the desired right limit position.
7.  8\.

    Press and release the RIGHT button. The RIGHT LED will illuminate if the position is valid.
8.  9\.

    After both limits are set, press and release the PROGRAM button. The PROGRAM LED should blink and then stay solid indicating success.

Follow the steps below to reset the Smart Robot Servo to its default mode and limits. The figure below shows the process to reset to defaults.

![](https://2589213514-files.gitbook.io/\~/files/v0/b/gitbook-legacy-files/o/assets%2F-M5yw0n8IneF5-9ybLjT%2F-MlCNxlQ-LJofBQhcpVW%2F-MlCO9d65k3icfZQy7og%2FServo\_270\_Range\_Full\_Green-01.png?alt=media\&token=864f82de-bf70-4fde-acef-28119fa689d8)

1.  1\.

    Connect SRS to the programmer.
2.  3\.

    Slide the mode switch to S position.
3.  4\.

    Press and hold the PROGRAM button for at least 5 seconds.
4.  5\.

    The LEDs will blink and then the PROGRAM LED will stay solid indicating success.

In either Continuous or Servo Modes, pressing and releasing the TEST button cycles through the two test modes:

* 1st press - Automatic Sweep Mode
* 2nd press - Manual Test Mode
* 3rd press - Return to default state

The section below will cover the two different test modes.

In Automatic Sweep Mode, the SRS Programmer will automatically sweep the SRS through motions appropriate for its configuration. the table below describes the behavior based on the configured mode.

| **Servo and Programmer Mode** |                              |
| ----------------------------- | ---------------------------- |
|                               | Sweeping direction and speed |
|                               |                              |

In Manual Test Mode the LEFT, PROGRAM, and RIGHT buttons control the movement of the SRS. The table below describes how the SRS will behave based on the configured mode.

![](https://2589213514-files.gitbook.io/\~/files/v0/b/gitbook-legacy-files/o/assets%2F-M5yw0n8IneF5-9ybLjT%2F-M8WcLi6koTauMV2xJ63%2F-M8X2TsbB\_7Qw9nIftaL%2FScreenshot%20\(29\).png?alt=media\&token=dcd83621-acbb-448f-88d6-929f9d7a120a)

If the SRS Programmer is left on for an extended period of inactivity, it will blink every LED as a reminder to shut off power.
