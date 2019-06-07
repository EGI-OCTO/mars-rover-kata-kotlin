# Mars Rover's kata in Kotlin

A Kotlin implementation of the Mars Rover's Kata. 
<p align="center">
    <img src="/res/rover.gif" />
</p>
 
## Kata Description

### Main features
 - Display the Mars Rover's movements on a grid
 - The Mars rover can receive four different commands:
   - Move Forward
   - Move Backward
   - Rotate Right
   - Rotate Left
 - The grid is squared and its size is configurable
 - The grid may contains rocks
 - If the rover encounters a rock while performing a move, it should notify Houston and stop. 
 > Mars rover to Houston : Mission aborted STOP. Rocks on the route STOP. Houston Do you copy ? OVER.

  
 
### Additional features
- Generate random maps (random rocks coordinates, random rover initial coordinates)
- Set a random target on the map
- If the rover reaches the target, it should notify Houston and stop.
> Mars rover to Houston : Mission achieved OVER.
> Houston to Mars rover : Well played Mars Rover STOP. Congratulations OVER AND OUT.")
    
- Given the rover initial coordinates, rocks coordinates and target coordinates, compute its route (see GIF above) 

## Disclamers
- I tried to rely on functions rather than classes 
  - I am just starting to look into functionnal programming so the result might not be very conclusive !
- The `computeRoute` algorithm is not really clever (it does not always find a path and when it does it does not necessarily find the shortest path). It has been developed empirically just for fun :)
  - It is property-based tested
- It tried to use some [currying](https://realjenius.com/2017/08/24/kotlin-curry/) (might not be very conclusive either !)
  
