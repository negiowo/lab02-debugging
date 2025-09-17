# lab02-debugging

Name: Joshua Zhang

Link: [Shadertoy link](https://www.shadertoy.com/view/3cffDl)

Bugs found: 
  1. line 97, changed uv to uv2 (compiler warning)
  2. line 100, changed uv to uv2 (objects out of position)
  3. line 11, changed the second iResolution.x to iResolution.y (ovals instead of spheres)
  4. line 75, changed eye to dir (reflection not working properly)

# Setup 

Create a [Shadertoy account](https://www.shadertoy.com/). Either fork this shadertoy, or create a new shadertoy and copy the code from the [Debugging Puzzle](https://www.shadertoy.com/view/flGfRc).

Let's practice debugging! We have a broken shader. It should produce output that looks like this:
[Unbelievably beautiful shader](https://user-images.githubusercontent.com/1758825/200729570-8e10a37a-345d-4aff-8eff-6baf54a32a40.webm)

It don't do that. Correct THREE of the FIVE bugs that are messing up the output. You are STRONGLY ENCOURAGED to work with a partner and pair program to force you to talk about your debugging thought process out loud.

Extra credit if you can find all FIVE bugs.

