## AR for the masses

===>> Question: Does React Native support ARkit or ARCore?
===> Find React Native limitation

ARkit - iOS
ARCore - Android

* GPS markers
* Feducious markers?

Use QCard SDK for surface location.

2018: AR in real time.
* ARCore example from Google.

ARise
  * Use perspective (angle) to open paths for character.

Tango 3D mapping
  * Unity SDK
  * Java / C SDK
  * Localization - drones
=> Google killed this project 1 mo within release

ARCore (regular camera): (pixel and S8)
* motion tracking
* environmental understanding
* light estimation

ARCore are supporting Tango.

IMU: inertial measurement unit
SLAM:

Dead reckoning: calculate distance between frames

Java, Unreal, Unity, OpenGL

* Motion tracking
* environmental understanding
* light estimation

UI Scene => Planes => Anchors => Model (assets)

https://github.com/google-ar/arcore-android-sdk

Starting: Unity or Unreal

AR Tools:
Models: Blocks & Tilt Brush

ARKit is more mature

iPhone X depth camera is only the user facing one.

Build once on Unity and deploy to ARCore and ARkit

ARKit => SceneKit

Mobile: always build with native (Kotlin & Swift)
=> except Unity for AR

AR Unity (new) / Unreal
* iOS ARkit plugin
* Google ARCore
* Vuforia

SceneKit => experience with this.

Native: OpenGL (expert)

* ARKit course at Udacity
  * ARCore might be coming soon

## Facebook: Scaling Developer Tools and teams

Production growth complexity O(n^2) where n is # developers.

* Performance is tough at scale

Build speeds => developer happiness
Type systems => not dynamically typed

Find the right people,
* tell the story to make them believe
* Make them do important things
* Practice it => bootcamp

Internal developer tools are products too.

* Round table meetings: listen to other developers
* Customer surveys
* Data science

Keep questioning
* Where do we focus?
* What's going to break in n years?
* Who's our competition? - dev tools: competitions are startups - quick, small environments

* Training and mentoring in soft skills

Manager: support

Infer and static analysis
* Find bugs in code during code review (without testing or running the code)
  * Saves time

Litho and Infer => Android

## Enhancing the VR/AR experience with voice interaction

mludden@us.ibm.com
LinkedIn.com/in/mludden

Watson developer labs

IBM Code Bot Asset Exchange

IBM Code
https://developer.ibm.com/code/
https://developer.ibm.com/code/patterns/

Star Treck bridge VR (Ubisoft)
VR speech sandbox IBM

* Support for Unity

Voice as a way to control in AR/VR experience in combination with another type of control.

Voice is a way to replace repetitive menu option choice.

Not a voice command, but by getting the info from what you are speaking of (reactions)
  * swearing, means you're frustrated,
  * "Wow": you are amazed
  * Laughing: you are having fun

Voice + gesture (ex: Harry Potter)

AR's missing control mechanism

Game Design principle: Everything is on rails, but the user doesn't feel like it.
  * "Sorry, I can't understand" repeating is frustrating.
  * "Go away, I'm busy!" (while looking busy): looks more plausible.

Use voice when the user doesn't want to use hands and gestures.

Test with more than your own developers (edge cases).

## APIs & Microservices

AR/VR integrating with IoT
  => Software + hardware

Shopping => Virtual mirror
Hospitality => Walk through a boutique AirBnb to check out the place before booking
Robots => Amazon warehouse
Security => Autonomous Drones + security cameras (over forests)

Medical field
  * Training

API Security
* Be mindful of security before shipping
* Security fault could destroy a company

Local vs. Cloud

futureproof hardware
* over the air updates
* users don't expect to upgrade hardware as often

backwards compatibility
