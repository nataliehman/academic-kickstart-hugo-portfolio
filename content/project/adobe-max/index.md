+++
title = "Prototyping with ProtoPie and LittleBits"
date = 2018-12-24T17:21:39Z
draft = false
weight = 1

# Project summary to display on homepage.
summary = "A project focused on prototyping smart devices using an app and electronic hardware."

# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []
categories = []

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Bottom"
+++

## Overview

This project focused on the tools available for prototyping with smart devices. I had the opportunity to work with Chakib Labidi and Stephanie Howard, whom I met from the UX Playground course.

We prepared this project as part of the [Adobe Max event](https://theblog.adobe.com/three-tips-on-smarter-device-design/?scid=0bffdabd-0987-4f47-b29e-f5d74616e18b&mv=social&mv2=owned_social), which took place on 15-17 October 2018. The project was also showcased in a [UX Playground meetup event](https://www.meetup.com/UX-Playground-The-User-Experience-Meetup-for-Londoners/events/254440446/) on 26 September 2018.

My role was to create interactive prototypes and I will describe my experiences on the tools I have used.

## Project Brief

To create an interactive smart device prototype with Adobe XD, which showcases its features and how it can prototype concepts. 

## Research

Our research covered topics such as UI kits, interfaces, and prototyping. Since I will develop the prototype, I researched on several key points such as:

* What is the difference between prototyping smart device interfaces vs non-smart device interface?
* What are the challenges?

{{< figure class="course-photos text-center" src="imgs/non-smart-ui-research.jpg" title="Research for prototyping with non-smart device interfaces" >}}

{{< figure class="course-photos text-center" src="imgs/smart-ui-research.jpg" title="Research for prototyping with smart device interfaces" >}}

I also researched what prototyping tools Adobe XD can integrate with. However, from my experience with the UX Playground project, we used ProtoPie as the tool for prototyping animation and interaction (this was before Adobe implemented the Auto-animate feature into XD).

We spoke with a staff member from ProtoPie, who suggested us to use Arduino and LittleBits for smart device prototyping. I knew Arduino required programming, so I researched LittleBits as I had no knowledge on what it does.

{{< figure class="course-photos text-center" src="imgs/littlebits.jpg" title="LittleBits is a tool for teaching people from all ages to build, prototype and invent with electronics" >}}


## Ideation

For ideation, we explored how we interact with physical interfaces e.g. light switch, and how they are designed in existing smart devices. This is mainly to help us understand how we can do hardware prototyping. 

{{< figure class="course-photos text-center" src="imgs/ideation-research.jpg" title="One of our ideation session" >}}

Throughout this phase, I was experimenting and testing how LittleBits work with ProtoPie. This exercise allowed us to see what types of interactions we can prototype for the project.

{{< figure class="course-photos text-center" src="imgs/littlebits-experiment.jpg" title="Experimenting with LittleBits" link="https://littlebits.com/" >}}

It was mostly trial and error because of limited resources on integrating LittleBits with ProtoPie. However, it was an interesting challenge as it felt like a programming exercise e.g. logical steps and conditional states for triggering animations,  considering the inputs and outputs for a process and how the inputs may produce the output.

{{< figure class="course-photos text-center" src="imgs/littlebits-protopie-light-off.jpg" title="A light switch prototype for testing ProtoPie and LittleBits (off state)" >}}

{{< figure class="course-photos text-center" src="imgs/littlebits-protopie-light-on.jpg" title="A light switch prototype for testing ProtoPie and LittleBits (on state with dimming)" >}}

## Prototyping

Aside from learning new tools, it was also my first experience creating animations for a UX project. Throughout the process, I was always testing and to keep the prototypes simple, we planned this phase into two parts:

* Create prototypes in ProtoPie
* Integrate LittleBits to show interactions between software and hardware

### Creating prototypes in ProtoPie

From our Ideation, we have created prototypes for the following interactions:

* To control lights by dimming and switching them on/off
* Play music with the option to skip songs
* Monitor and change room temperature on AC unit

For inspiration, we researched animations created by designers on Dribbble. However, we also considered that the animation should feel familiar in relation to the real world e.g. a light switch with a button.

{{< figure class="course-photos text-center" src="imgs/dribbble-adjust-light.gif" title="Adjusting brightness level by Teo Choong Ching" link="https://dribbble.com/shots/3572111-Adjust-the-brightness-level-Principle-working-file">}}

Before prototyping, Stephanie created the designs in Adobe XD. I then imported them into ProtoPie and experimented with different solutions. It was an iterative process until we found a solution that matches the vision we had for each of the prototype.

{{< figure class="course-photos text-center" src="imgs/protopie-slider.jpg" title="A test prototype for creating sliders and switches" >}}

{{< figure class="course-photos text-center" src="imgs/prototype-review.jpg" title="The team reviewing the UI design and prototype" >}}


### Integrating LittleBits with the prototypes

When the prototypes are complete, the next step is to include LittleBits. So far, the only method for connecting ProtoPie and LittleBits together is to have the same message ID. This is like a destination address for sending and receiving messages. The ID is entered into ProtoPie and the bridge app (provided by ProtoPie) to enable communication between the two.

&nbsp;
&nbsp;

{{< vimeo 320971006 >}}

&nbsp;
&nbsp;
&nbsp;
&nbsp;

Again, I had to do many tests and iterations because the hardware can change the states and inputs/outputs of the prototype. The process was time consuming because integrating LittleBits added another layer of complexity.

The following videos are two of the prototypes demonstrated at the Adobe Max event.

&nbsp;
&nbsp;

{{< vimeo 320971419 >}}

&nbsp;
&nbsp;
&nbsp;
&nbsp;
  
{{< vimeo 320973092 >}}


## Conclusion

Creating prototypes with hardware was a fun yet challenging experience. ProtoPie can create high fidelity complex prototypes without coding, which made the process less intimidating. However, it can be time consuming as it requires testing.

When prototyping, there should be a plan on what tasks the team will do. This ensures that the final prototype achieves the vision the team has. It also helps the team to know what research is required and what solutions are possible after reviewing.










