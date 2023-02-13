# Constraining Motion

### Constraining Motion Basics <a href="#constraining-motion-basics" id="constraining-motion-basics"></a>

Robots need movement to accomplish goals; arms must pivot, wheels must turn, etc. However, movement that isn’t directly related to those actions can affect the accuracy and precision of the robot mechanisms. This unintended motion must be properly restricted, or **constrained**.

Long and thin structures can flex and deform, making it difficult to interact with objects and operate in a repeatable manner. Make use of brackets and additional

[Extrusion](https://www.revrobotics.com/ftc/structure/15mm-extrusion/)

or

[C Channel](https://www.revrobotics.com/competition/ftc/structure/channel/)

to **strengthen** and constrain these structures.

Gears and sprockets must stay aligned or else they won’t work properly.

If two sprockets are not perfectly aligned with each other, the chain between them will run off the sprockets.

Keeping parts aligned on a shaft, and keeping the shaft itself from sliding out is critical for reliably working robot mechanisms. Use a combination of spacers and shaft collars to align and constrain these parts into place.

![](https://2589213514-files.gitbook.io/\~/files/v0/b/gitbook-legacy-files/o/assets%2F-M5yw0n8IneF5-9ybLjT%2F-M7xZrfXp93Fnloi8g1R%2F-M7xgaxdf9RgjLOtNorx%2FThree%20Spacers%20Chart.png?alt=media\&token=d56e0bfe-a930-4214-bf5d-3cd83d84f201)

Another crucial piece to proper motion constraint is joint construction. Places where structural components, like an Extrusion and Channel, meet need to be properly supported in order to avoid structural collapse during motion.

#### **Secure with 2 or More Brackets** <a href="#secure-with-2-or-more-brackets" id="secure-with-2-or-more-brackets"></a>

In most cases joints should have at least two sides joined with brackets for strength and stability. This is especially true for plastic brackets. Commonly this involves taking two of the same kind of bracket and sandwiching the pieces of extrusion, but this can also be two different kinds of brackets such as a 90 Degree Bracket (

[REV-41-1305](https://www.revrobotics.com/rev-41-1305/)

)(

[REV-41-1480](https://www.revrobotics.com/rev-41-1480/)

) and an Inside Corner Bracket (

[REV-41-1320](https://www.revrobotics.com/rev-41-1320/)

)(

[REV-41-1479](https://www.revrobotics.com/rev-41-1479/)

) installed on the same corner.

![](https://2589213514-files.gitbook.io/\~/files/v0/b/gitbook-legacy-files/o/assets%2F-M5yw0n8IneF5-9ybLjT%2F-MlBl-KdeMsqjyFTh34y%2F-MlBteXzWZEYjnRtp-NG%2Fdouble%20up%20bracket.png?alt=media\&token=afa79f5e-6885-40d3-aa4b-fdfa98a563c2)

When using brackets to connect extrusion, the joint will be much stronger if the end of the extrusion is beveled (cut at an angle) so that the end will sit flush with the face of the adjoining extrusion.

![](https://2589213514-files.gitbook.io/\~/files/v0/b/gitbook-legacy-files/o/assets%2F-M5yw0n8IneF5-9ybLjT%2F-MlBl-KdeMsqjyFTh34y%2F-MlBu-9QamQcRqfrMaZw%2Fbeveled%20extrusion%20joint.png?alt=media\&token=e537fe26-68ec-42d3-b59d-aaf1e097201c)

Different bracket angles can be combined to make structures. The joints in this example are all beveled to sit flush against the adjoining extrusion.

![](https://2589213514-files.gitbook.io/\~/files/v0/b/gitbook-legacy-files/o/assets%2F-M5yw0n8IneF5-9ybLjT%2F-MlBl-KdeMsqjyFTh34y%2F-MlBu9LE25g-rel\_sN5R%2Fdifferent%20angle%20brackets.png?alt=media\&token=bd72f2a5-602b-4dc7-a094-2cf14a23af25)

#### Ways to Create 90 Degree Joints <a href="#ways-to-create-90-degree-joints" id="ways-to-create-90-degree-joints"></a>

There are three main ways to create extrusion joints that are at 90 degrees. The most common is the 90° bracket which mates to pieces of extrusion at 90° in the same plane. The second is an inside corner bracket is functionally equivalent to the 90° bracket. The third type is called a lap joint bracket which allows two pieces of extrusion to “overlap.”

![](https://2589213514-files.gitbook.io/\~/files/v0/b/gitbook-legacy-files/o/assets%2F-M5yw0n8IneF5-9ybLjT%2F-MlBl-KdeMsqjyFTh34y%2F-MlBtYVQmzLIEl1laVmD%2F90%20degree%20bracket%20%20REV-41-1305.png?alt=media\&token=8e1daa2f-df33-4ef4-8038-293916a31863)

![](https://2589213514-files.gitbook.io/\~/files/v0/b/gitbook-legacy-files/o/assets%2F-M5yw0n8IneF5-9ybLjT%2F-MlBl-KdeMsqjyFTh34y%2F-MlBtU6x7khT7umhDJt6%2Finside%20corner%20bracket%20REV-41-1320.png?alt=media\&token=21ebb14e-2609-4dcc-95a6-dbc5150e05c7)

![](https://2589213514-files.gitbook.io/\~/files/v0/b/gitbook-legacy-files/o/assets%2F-M5yw0n8IneF5-9ybLjT%2F-MlBl-KdeMsqjyFTh34y%2F-MlBtQ2D5bz8zJjaDYG2%2Flap%20corner%20bracket%20REV-41-1321.png?alt=media\&token=28a57cfd-4375-4ba7-8d34-dab2c3c73508)
