# Paddle-Ball-Processing-JS

If you don't already have a Khan Academy account, [create one here](https://www.khanacademy.org/signup).

## Ball Movement
First, spend some time going through [this tutorial about animations in ProcessingJS](https://www.khanacademy.org/computing/computer-programming/programming/animation-basics/p/making-animations), with the goal of animating a bouncing ball in mind.

Then, once you feel like you can do a bouncing ball, spin off an animation, call it "<Your name>'s Paddle Ball Game" and work on getting a ball that moves and bounces off the walls.  For reference, the screen is 400 pixels wide.

### Clean up your code!
Now that you've gotten the ball bouncing, clean up your code!  

* Make sure you don't have any "magic numbers" -- your code should not have numbers directly embedded in it!  They should all be defined as constants (variables that you never change).
* Do you have any code that looks exactly the same as something else but with different variables? If so, create a function and call it with different parameters!
* Are your variable names meaningful? If not, change the names! (Note that `x` and `y` can be meaningful names, but try to be more descriptive.  The `x` position of what?  Maybe use `ballX` instead.)
* Are there any tricky lines of code?  If so, add a brief comment explaining it. (The more concise the better!)
* Is your indentation and bracket use consistent?  Remember that the opening `{` should be at the end of the line, everything inside of the curlies should be indented one tab, and the closing `}` should be at the same indentation level as the statement that opened block it's closing.  See below for a nonsense example with the proper formatting.

```
function funName(param) {
  console.log("hi");
  for(var i = 0; i < 10; i++) {
    console.log(i);
  }
}
```

Once your code is cleaned up and you're proud of it, show it to one of the teaching staff before moving on!

## Paddle Movement
Once your ball animation code has been approved by teaching staff, go through the [mouse interaction tutorial](https://www.khanacademy.org/computing/computer-programming/programming/interactive-programs/p/mouse-interaction), with the goal of getting a paddle to follow your mouse in mind.

Once you feel like you can get a paddle to follow your mouse left and right (while staying in the same vertical position), go back to your spin off and work on that.

### Clean it up!
Again, clean up your code!  Use the bullets above to check if your code is clean, and again, get one of the instructors to check it over before moving on.

## Ball/Paddle Interaction
Once you have the paddle following your mouse, it's time to make it interact with the ball!

Use all your knowledge of ProcessingJS to get the ball to bounce when it hits the paddle!

### Clean it up!
Again, clean up your code!  No need to get it checked this time, you know the drill :)

## Lose condition

Now, if your ball goes all the way to the bottom of the screen, we want the user to lose.  So we should give the user a "Sorry, you lost!" message and reset the ball to the middle of the screen.

### Clean it up!
Again, clean up your code!

### Update this repo!

Make a fork of this repository if you haven't already.  Go into the `paddle-ball-code.js` file and paste in your code, along with a comment with the link to your spin-off.  

Get one of the teaching staff to check your code!

# Breakout!

Now you're ready to upgrade your game into a version of Breakout (or Brick Breaker).  This time, instead of continuing to update the same spin-off, make a new spin-off based on your Paddle Ball game, and call this one "<Your name>'s Breakout Game". 

At each step, clean up your code and get it checked as above!

## Add bricks

In your new spin-off, add 3 rows of 5 bricks near the top of the screen.

## Ball/Brick interaction

If the ball hits a brick, have it disappear.

## Score

Create a scoring system and display the current score at all times

## 3 lives

Let the user have 3 lives before they lose.
