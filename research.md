<link rel="shortcut icon" type="image/x-icon" href="favicon.ico">

# currently...

### Contact-Implicit Balance Recovery for Humanoid Robot ~ [_Biomimetic Robotics Lab (MIT MechE)_](https://biomimetics.mit.edu/)

The current MPC controllers used on BRL's humanoid robot rely on a gait schedule to plan contact for walking, which can be brittle to tripping and certain other disturbances that would require breaking the left-right step pattern or require taking faster/slower steps that are unevenly timed. Our goal is to allow the robot to choose when to make and break contact with the ground as well as other elements of the environment (ex. a nearby wall) - this could possibly offer the option of taking a step forward or backward when disturbed from standing, or reaching out to catch itself on the ground or on a wall and help itself back upright.

Working with Charles Khazoom, I am currently exploring contact-implicit methods of doing this, starting with a complementarity constraint relaxation on contact using SQP.

Using: CasADi, MATLAB, C++

# previously...

### Gripper-Aware Robotic Manipulation ~ [_Improbable AI Group (MIT CSAIL)_](https://people.csail.mit.edu/pulkitag/)

![Illustration of robot demo](/assets/clutter_demo.png)    

In collaboration with Anthony Simeonov, this project explored ways to condition robotic manipulation of novel, cluttered objects on gripper shape and manipulation task. In the way that you wouldn't grab a mug by its rim if you wanted to flip it upside down, we want to generate grasps that depend on (1) gripper reach and extents and (2)  what the robot intends to do with the object. Our approach built off of the existing GraspNet architecture presented by Mousavain et al.

Preliminary results on the gripper-dependent part of this task were presented at the [IPPC Workshop at IROS 2023](https://ippc-iros23.github.io/), and then again at [NERC 2023](https://yale2023.nerc.io/). Read the paper [here](https://ippc-iros23.github.io/papers/sarmiento.pdf), and see the more current version of the poster (NERC) [here](https://drive.google.com/file/d/1dgi6b9WkkfwVaRYsoDJROi0NjcLD59uc/view).
     
Using: PyTorch, ROS, PointNet++ architecture, GraspNet architecture, CVAEs, Docker, PyBullet, RViz

### Computational Design of Soft Robotic Sensors ~ [_Distributed Robotics Lab (MIT CSAIL)_](https://www.csail.mit.edu/research/distributed-robotics-laboratory)

<img src='assets/hsa_screencap.jpg' alt='Screenshot of HSA' width='300'>

I worked with Lilly Chin to create computational design tools and pipelines for pressure based and tactile sensor prototyping. We're focusing on adding sensor capability to her work on handed shearing auxetics (HSAs), as well as iterating on the team's tactile sensors for soft robotic grasping.

Using: Grasshopper, Rhino, Rhinoscript, Carbon3D printer, basic electronics

### Venous Materials ~ [_Tangible Media Group (MIT Media Lab)_](https://tangible.media.mit.edu/)
    
I worked with postdoctoral student Hila Mor and faculty advisor Hiroshi Ishii to help develop a more user intuitive interface for Venous Materials: physical fluidic circuits and veins as pressure and deformation sensors. Prototyped a method to print the designs using a novel type of nonplanar 3D printing, as well as streamlining the user interface of the design tool and prototyping different types of logic gate primitives.

Used: Grasshopper3D, Rhino
