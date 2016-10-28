# Ripple-Cocos2dx

This library was created by **Lars Birkemose** on 02/12/11 and edited by **guanghui** on 7/30/13. Now I have custom it for compatible for both cocos2dx version 2x and version 3x. It work well for iOS 8+ and Android 19+

## What is a Ripple effect ?  

Ripple effect is a situation in which, like ripples expand across the water when an object is dropped into it, an effect from an initial state can be followed outwards incrementally.  

There is really nothing special to the ripple effect, in essence it is just an evaluation of the [sombrero function](http://adrianboeing.blogspot.com/2011/02/ripple-effect-in-webgl.html)  

The WebGL version of Ripple effect can see [here](http://levietquang.com/demo/riple/)  

## How to use this ?

`-` Init Ripple Sprite :

rippleSprite = pgeRippleSprite::create("your image");

`-` Init Update function 

rippleSprite->update(dt);
