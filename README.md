# in-class-activities
## Devlogs
### W1
Hello world!

### W2
The r, g, and b variables are floats rather than ints, bools, or strings as they are both number variables, and fractional numbers. It is the fact that the variables are fractional numbers instead of whole numbers that keeps them from being ints. In contrast, the __bounce variable is an int as the number of bounces are whole numbers. The error I recieved after Step 8 of Part 2 told me that my line of code was broken because I had not assigned a variable type for the brightness variable, which needed a float typing.

### W3
Table #4: If we were building a rhythmn game, and were writing a method named DidPlayerHitBeat that tells you whether or not the player accurately hit a beat based on the time that they pressed a key, we decided to have our parameters be floats. We additionally decided our return type or output would be a boolean. However, we did not come up with specific numbers for our floats. A metaphor to explain the relationship between classes and Components would be that classes are the instruction manual to components. In this case the components may be the object that the classes are a manual to, such as, perhaps, Ikea furniture pieces. I believed the balls in the scene get extremely bright after bouncing too many times as there is not a cap on the level of brightness that the balls can reach, and their brightness is never reset by the code.

### W4
Table #1: Line 5 is a member variable of the class CatW4, and the type is a float. Line 22 is calling a method, "Get.Axis", in order to call the vertical axis;it is recieving input from the player. Line 25 is moving the game object that it is being called on. We decided to add rigid bodies to the cat and the ball, as both need to collide, and the ball must bounce off the cat. Additionally, we checked Is Trigger on the goal as we wanted to know when the ball would has reached the goal zone. We did have to adjust the constraints on the cat and ball, as they initially were rotating into space.

### W5
My question about vectors was in relation to how the positive and negative infinity vectors worked. The answer I recieved from a tablemate was that the vectors determined that they would extend infinitly in either a negative or positive direction. For our variables we will need a transform, speed, and movement variable that will each have to be serialized. Many of the variables may be similar to those existing in the Cat class. There should also be an Update() method and Start() method in use as the AI should begin moving at the start of the game, and so that its movement is updated every frame.

### W6
My category assignment was "Other Tools" and here is my [finished doc](https://docs.google.com/document/d/1_oQY0junK3b37PITxN8uItEEPKJGHvci47NArvtUxiQ/edit?tab=t.0)
For the Batw6 Class activity we decided that the one of the member variables we would need would be a speed variable, and for methods we would need the Start() and Update() methods. Additionally, we may use the GameObject.SetActive() method as well. The Start() method should allow for an action to occur as the game starts, the Update() method should should allow us to record and update the bat's movement in real time or every frame, and the GameObject.SetActive() method will allow us to enable and disable sprites as necessary.

### W7
In my group my category assignment for our game was the environment. Here is a link to [the doc](https://docs.google.com/document/d/1RbOJV14KBQmt5sQBiYGuODTakWBMyocLs59OTx8vLRQ/edit?usp=sharing)
The issue we found in step 2 was that the transform.position part of the line of code was supposed to be a transform.Translate. This is done in order to prevent the W and S keys from controlling the muskrat to the left and right. The transform.position moves the game object on the world's plane preventing the muskrat from moving properly.

## Open-Source Assets
### W1
- Animals: https://assetstore.unity.com/packages/3d/characters/animals/animals-free-animated-low-poly-3d-models-260727 
- Low-poly environment: https://assetstore.unity.com/packages/3d/environments/landscapes/low-poly-simple-nature-pack-162153 