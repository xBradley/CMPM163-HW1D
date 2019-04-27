# CMPM163-HW1D
Discuss a Visual Effect

## Intersellar Tesseract Effect

I like the infinite recursive nature of the effect in the final scene of the movie Intersellar (2014). Even though the effect was done with both practical and computer effects, it is still interesting. Another cool thing is apparent when you look at the void of infinity, you can still see the shape (a cube) of the orginial object. 
The effect doesn't change depending on lights or the camera. However, depending on where you look you continue to see the same recursive effect. Each corner of a cube goes to infinity. The center panels just stretch a texture. 
I would think the effect updates geometry and alters textures. Since the player (Matthew McConaughey) can move through the space and the effect continues to flow, then it must either create more geometry or it could just be looping in the same thing in a circle. The player wouldn't actually be moving, just the space around them. But it definitely does alter textures. The base texture is a bookshelf and it stretches it in the x and y direction.
I believe the texturing effect could be made in fragment shader to stretch all the texels in the x and y directions. As far making a geometric space that could produce the recursive effect, I have no idea. But one way I could make a stationary version is by using Blitz and render textures on itself to create the same mirroring effect.
The directors of Intersellar labels the scene as the tesseract scene, which is 4th dimensional cube. So I assume effect is also called the same thing. However, I was unable to find any help that would show how emulate the same effect. The only thing I found was making a literal 4th dimensional cube. They did this by using matrices to make a smaller cube inside a cube and connect the corners.
