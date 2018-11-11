# Space Saloon
We figured we wanted to make a game maybe or whatever

## Installation
Clone the reposity, open it in Unity, and open a scene.

### Importing Sprites
Since this is a 2D pixel art game, we need to consider keeping things scaled properly and such. The Pixel Perfect camera component takes care of many aspects of this, but we still need to import our sprites properly. These steps are take from the [Unity documentation](https://docs.unity3d.com/Packages/com.unity.2d.pixel-perfect@1.0/manual/index.html).

- Set the pixels per unit value to 32
- Set the filter mode to Point (no filter)
- Set compression to None
- Make sure the sprite's pivot is set to a pixel, not normalized.
