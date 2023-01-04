# Practical 5: Prototyping Augmented Reality with Vuforia and Unity

In this week's lecture we saw a range of different approaches for creating augmented reality experiences, which overlay digital content onto the physical world. In this practical, we're going to use a tool called Vuforia within Unity to make some experiences using some of those approaches.

## Task 1: Getting Vuforia Setup in Unity

I've created a template Unity project with some assets that you can use for the practical today already included. To get started, you should create a copy of this repository in your personal GitHub account by pressing the ```Use This Template``` button, and then clone it onto your local machine.

To use Vuforia AR functionality in Unity we need to add it to our project as a package. There are a few ways to do this, which are described in the tutorial below. I'd reccomend you use the third one ```Add Vuforia Engine from the Asset Store```, but you can try the others if you'd prefer.

- https://library.vuforia.com/getting-started/vuforia-engine-package-unity

Next you need to create a license key for your app. You can do this by following the two tutorials below. It’s a bit fiddly, but its worth it trust me!

1. [Create a Vuforia Account](https://developer.vuforia.com/vui/auth/register)
2. [Create a free development license key](https://library.vuforia.com/articles/Training/Vuforia-License-Manager.html)
3. [Add your license key to your app](https://library.vuforia.com/articles/Solution/How-To-add-a-License-Key-to-your-Vuforia-App.html)

Once you’ve done this, you should have an AR-enabled project. You can check if it worked by looking in the ```Game Object``` menu. If there is a new option in the list called ```Vuforia Engine``` then it’s worked.


