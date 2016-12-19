#User Focus

Understanding what your user is focused on and when can be one of the most important things to understand in modern web development.


##The Animation

Imagine this:

You have just been hired as the brand new junior developer for an emerging startup. They loved your Dribbble work so much that they have tasked you with creating the most amazing animation for a new user signing up to the service.

For three weeks you work understanding the furthest depths of CSS creating the most seamless animation for a signup yet.

For three weeks you dive deep into CSS3, understanding selectors that your coworkers have never even heard of. The animation is a work of art. With multiple moving parts, timing down to the millisecond, it couldn't get much better.

The day has finally come to show your boss the beautiful work you have done. You couldn't be more proud with this animation, and you think you have tracked down everything - full browser support with fallbacks if need be, a toggle for colorblind colors, and full accessibility support.

Your boss calls you over to his desk to demo this brand new animation. He pulls up the staging site and it goes off seamlessly. Everything is going perfect...

Until he tabs away to his email.

"What are you doing? You are going to miss the best part!"

"Sorry I just have to respond to this email quickly, it's very important"

He tabs back to the animation, and it's finished. He missed the most important part.

"How can you expect a user to sit on our page for 3 seconds without being distracted? We can't expect the user to wait for the animation, we need the animation to wait for the user."

##React-User-Focus

Today's web users are a very fickle group of people that have strange viewing habits. As a developer, I find myself constantly opening links in new tabs and saving things for later. If any site has an attention grabbing opening that doesn't wait for me to engage it, then it is completely lost on me.

*Before a website tries to grab my attention, it should know that it has my focus.*

To combat this, I built a component in React to help a website understand when a user is focused on that site. It is a very simplistic component. It simply returns whether or not the user is focused as well as whether or not the user is idle.

It does this by tracking the state of the page. If a user tabs away, minimizes the window, or focused on a different window then the react-user-focus component will know.

It also tracks the idle state of the user. If the user has no movement or engagement within a set period of time, then the react-user-focus will consider that user idle.


It's as simple to use as this:


```
 import ReactUserFocus from 'react-user-focus';

<ReactUserFocus
  onFocusChange={onFocusChange}
  onIdleChange={onIdleChange}
  idleTime={2}
/>
```

It works on a global scope, so as long as this component is being rendered, then it will be listening.


![](/content/images/2016/11/RUFDemo.gif)
It's not the best quality, so to see a full demo go to my [ Website Demo](https://seankilgarriff.com/ReactUserFocusDemo).

Check out the source code on [Github](https://github.com/Skilgarriff/react-user-focus)!
