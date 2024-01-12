---
title: Shadowseeker
type: docs
---

# Shadowseeker

## Abstract

After a detailed ideation process, considering different ideas for our Chindōgu, we have decided on implementing a moving device that carries a bottle of beer or another desired drink. The goal of the device is to keep the drink cold by driving into the shadow, hence the name "Shadowseeker". THe only small flaw that the Shadowseeker has, is that it can only drive in the sun.

## Introduction

A first phase of finding our solution for the Shadowseeker has led us to this first rough sketch:

{{< figure src="first_sketch.png" caption="*A first sketch of the shadowseeker.*">}}

The shadowseeker should have 4 wheels and 2 axes that are robust enough to hold the weight of a drink as well as the device itself. Moreover, it should have a place to put the beer without being in danger of falling off.

{{< figure src="prototype.jpg" caption="*The first prototype made out of paper.*">}}

At this point it was clear that we would have to use a strong material for the wheels, the axes and the cup holder.

For the prototype we had a motor combined with a solar panel from a LEGO set in use which was supposed to be the Shadowseeker's power source, making sure it can only drive in the sun.

{{< figure src="lego_motor.jpg" caption="*Motor in combination with a LEGO solar panel.*">}}
{{< figure src="high_prototype.jpg" caption="*A driving device.*">}}

Considering the poor feedback that the device gave to the user in the first state, we have decided to have little lights as well as a short beep that indicate that the motor has started as soon as the Shadowseeker hit the sun.

## Related work 

References to related concepts, projects, books, websites, stories, systems, fruits, etc. and their relation to the project at hand.

## Implementation 

The parts we needed to construct were the following:

The body of the device, the wheels, the motor with light sensors, the feedback components (lights and sound).

### Body

For the body of the device we needed to make sure that it was light enough for the wheels to carry it and the motor to be able to drive it but also that it was strong enough to hold a beer bottle. The body needed to have just the right amount of depth for the beer bottle not to fall but to be higher than the wheels so it wouldn't touch the ground. After considering different options, we went for a frame made out of aluminium (?) that holds the inner part, which would be a 3D printed model. After carefully meassuring the different components, we created the 3D model in Autodesk Fusion and printed it.

{{< figure src="body_cad01.png" caption="*Top sketch of the body.*">}}

{{< figure src="body_cad02.png" caption="*Lower part sketch of the body.*">}}

We printed the body and were pretty happy with the result.

{{< figure src="body.jpg" caption="*Printed body.*">}}


We decided to glue the beer-holder-ring on the printed objects. This gave us flexibility in trying different ways to fit all the components in the small space.

{{< figure src="glued_innerpart.jpg" caption="*Glued ring.*">}}

We then also created a cup with a slightly smaller radius that could be put into the already existing ring to improbe stability for different sized drinks.

{{< figure src="body_almost_done.jpg" caption="*Smaller radius cup.*">}}

In the end we had to make some adjustment due to the small space, such as creating a hole for cables that did not fit and adding some extra padding to have more space in height.


### Wheels

Getting the right wheels was quiet the challenge. The inner whole of the wheel needed to have the same radius as the connecting part of the motor, which made it very challenging to find something fitting. After not being able to find the right wheel in old lego sets or even online, we have decided to 3D print the wheels ourselves.

Using a wheel that we found in the lab (but unfortunately only had one) as a reference, we built a 3D model in Autodesk Fusion.
{{< figure src="wheel_01.png" caption="*Inner wheel.*">}}
{{< figure src="wheel_02.png" caption="*Outer wheel.*">}}

We sketched different models for only the inner part of the wheel as well, to make sure that the motor fits and prevent to print a wheel that will not even fit.

We then decided to go for different motors and therefore changed the shape of the inner hole.

{{< figure src="wheel_03.png" caption="*New inner part of the wheel.*">}}

{{< figure src="printed_wheel.jpg" caption="*Printed wheel.*">}}

Due to the tiny inaccuracy of the 3D printer or the meassurements, the inner part did not fit perfectly on the motor but some glue fixed that problem.

We also added the rubber part of a lego set to add more friction and stability to the wheels.

{{< figure src="wheels_with_gummi.jpg" caption="*Added rubber for friction.*">}}

We had two lego wheels that fit on a lego axis which we used as the front wheels since only the back wheels are motor powered. So we only had to print one set of two wheels.

{{< figure src="second_wheels.jpg" caption="*Lego wheels.*">}}

{{< figure src="lego_axis.jpg" caption="*Lego axis.*">}}



### Motor
For the motor we had to make some adjustments regarding the power of the motor and the weight of the device.

{{< figure src="elektronik_skizze.jpg" caption="*Add caption.*">}}
{{< figure src="elektronik_skizze02.jpg" caption="*Add caption.*">}}
{{< figure src="motors.jpg" caption="*Add caption.*">}}


#### Iteration №1 Motor

tried lego, was too weak

#### Iteration №2

tried 1 battery, was too weak 

#### Iteration №3

tried 2 batteries, was perfect

### Feedback components

For the feedback components we decided to add some lights and sound. 
The sound is produced by a simple buzzer and it goes off as soon as the shadowseeker hits the light and starts driving. The same logic applies to the lights which are installed at the front of the device. We added two holes in the body to make it easy for us to place them.

{{< figure src="lights.jpg" caption="*Light sensors and light.*">}}

Due to space problems we could not push them in all the way but it still worked out fine. 

Light sensors were installed to be able to only power the device when it is in the light.


## Conclusion

The project was very interesting and successul. There were some challenges involved and it really revealed that investing a lot of time in planning beforehand is eventually very time-saving. The shadowseeker will be continuing to seek shadows and delivering beer. 