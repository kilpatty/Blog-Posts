Last month, I converted my personal website to React after gaining a lot of experience with it in the workplace. I used my website as a guinea pig to stretch React to the limits and see what I could achieve with it technically.

If you venture to the depths of Hackernews, Reddit, or one of the many programming news websites - You most likely will have heard of one of the many "React killers" - VueJS, Inferno, or Preact. Over the holidays I decided it was time to try some of the React alternatives.


####Converting Made Easy?

For both Preact and Inferno the conversion from React is touted be very simplistic - simply alias React and React-dom in your bundler to (Preact or Inferno)-compact, and boom, your bundle just got 30kb smaller.

The conversion to these frameworks turned out to be nothing be easy.

While I understand that both of these frameworks are still very much under construction, the stability that React provides my applications is too good to give up.

##Stability


With both Inferno and Preact, there was no solution for my custom CSS transitions - the infrastructure just wasn't there yet. With Preact, I found that my SVG's randomly would choose not to render sometimes, which is unfortunate as my entire front page is one SVG.

![](/content/images/2016/12/Screen-Shot-2016-12-28-at-11.09.14-AM-1.png)

Is Preact trying to tell me to shave?

To be fair, Preact is currently aware of this issue and they are working on it, but it's this level of stability that needs to be achieved before transitioning to a new framework.

On top of a base level of stability, React also provides it's synthetic event handling system, which contributes to it's larger size compared to the other frameworks. While working with React, you likely won't even notice what this system is doing for you, and I believe that this is a sign of great development.

##Ecosystem

I used a package for React to handle my CSS transitions because they are difficult to implement when working with a virtual dom. Preact had somewhat converted this package for Preact, but it is missing a lot of the functionality that React's has. Inferno had no solution yet for CSS transitions.

The biggest benefits of React is the incredible ecosystem. In one quick google you can find any package for React written as a component. Everyday i see newer and more creative utilities and components built for React.

While the Preact and Inferno communities are working hard to support a lot of these main packages such as Redux, it is the obscure packages that I believe give React a leg up.

Here are some of my favorite more obscure React packages:

* [React-VR](https://github.com/facebookincubator/react-vr)
* [React Date Picker](https://github.com/airbnb/react-dates)
* [Victory Data Visualization](https://github.com/FormidableLabs/victory)
* [React Sound](https://github.com/leoasis/react-sound)
* [React Video](https://github.com/pedronauck/react-video)

Additionally, none of these frameworks have any support for React Native which to those who like to share code between React and React Native can be a major downside.

##React Team is Full of Superstars

React has found a way to stack their development team with some pretty impressive coders. Here's a quick rundown of some of the members, and their contributions to the React community:

Dan Abramov aka [gaearon](https://github.com/gaearon):

* Co-creator of [Redux](https://github.com/reactjs/redux)
* [React Hot Loader](https://github.com/gaearon/react-hot-loader)
* [Create React App](https://github.com/facebookincubator/create-react-app)
* [React DnD](https://github.com/gaearon/react-dnd)

Andrew Clark aka [acdlite](https://github.com/acdlite):

* Co-creator of [Redux](https://github.com/reactjs/redux)
* [Recompose](https://github.com/acdlite/recompose)

Cheng Lou aka [chenglou](https://github.com/chenglou):

* [React Motion](https://github.com/chenglou/react-motion)
* [React Tween State](https://github.com/chenglou/react-tween-state)

The team at Facebook also just added the creator of Inferno Dominic Gannaway.

![](/content/images/2016/12/Screen-Shot-2016-12-26-at-3.22.26-PM.png)


React has a fantastic community and team behind it that are constantly pushing it forward. It's hard to ignore the amount of brainpower that currently exists in the community.

##Momentum
This isn't to say that the other two frameworks don't have any momentum in the community, but rather that React feels like an unstoppable steam roller.

React is currently undergoing an entire re-write to be released as React Fiber. This new code will undoubtedly use some of what the React team has learned from Preact and Inferno.

For a good briefing on React Fiber I recommend [What is React Fiber?](https://gist.github.com/duivvv/2ba00d413b8ff7bc1fa5a2e51c61ba43)


For now, I'm sticking with React. It seems as though it's just the most stable framework, and certainly isn't losing any momentum.

In the meantime I'm keeping my eye on Vue, Preact, Inferno and Svelte. I hope that the competition will allow for an overall better development and user consumption experience.
