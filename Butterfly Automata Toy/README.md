## Butterfly Automata Toy

For the final project I chose to make the ***Butterfly Automata Toy***. It is a mechanism that simulates the flight of the butterfly. I chose this mechanism because I was always fascinated by the graceful flight of butterflies.

### Components
The main components are:
- box (stand, holder)
- main axe (axe, contact piece)
- 3 disks
- handle
- 3 connection rods
- butterfly (body, right wing, left wing)

### How it works?
When the handle is rotated, the axe and the disks also begin to rotate. They move the butterfly through the connection rods that join them. The rotational motion (revolute join placed on handle) is transformed into linear motion (slider joints placed on connection rods) and the butterfly gives the impression that it is flying.

The component that had to be powered to see the motion was the **handle**, but I simulated the movement using Motion Study. So, you have to play the Motion Study named '***PlayMotion***' to see how the butterfly flap its wings.

### Steps followed
- begin with sketches
- make box, axe, handle
- make disks and connection rods
- make butterfly
- add joints, joint limits, motion study 
- at the end, add appearance and render the mechanism

I split the box into two components, so that I don't need additional material when printing it. I tried to do the same for connection rods (to split each connection rod into 2 components), but the movement was affected so I combined each rod into a single component. I split the butterfly into three components: body, right wing, left wing. I combine the body with the middle connection rod. The wings are supported by circles that surround the body of the butterfly. For the axe, I added a contact piece and a lid.

### File types
I uploaded the following file types:
- .f3d
- .stl
- .jpg (rendering photo)
- .mp4 (rendering video)

To make the butterfly I used this png file as canvas:

![butterfly-shape](https://user-images.githubusercontent.com/79320751/119256096-9c4b5200-bbc7-11eb-8b35-1ce31bf701a7.png)

### Software used
To design and render the project resources I used ***Fusion 360***. 

### Mechanism's author
I couldn't find any information about the author of the mechanism, but the main source of inspiration was [this video](https://www.youtube.com/watch?v=PHzZjUK9BuQ) made by EHC Gear.
