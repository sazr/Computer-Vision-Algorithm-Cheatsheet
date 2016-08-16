# Succinct cheatsheet of computer vision concepts and building blocks

## Colour Spaces
  ### BGR: 
  Standard colour image. Same as RGB image. 
  #### When not use:
  ???
  #### When not to use:
  In most cases (if not all?) you should not perform CV algorithms with BRG/RGB images.
  
  ### HSV:
  Hue, Saturation and value. Hue = dominant color; the names that we give to colors (such as green, yellow, blue, and red) correspond to the different hue values. Saturation = how vivid the color is; pastel colors have low saturation, colors of the rainbow = highly saturated. Brightness/Value = luminosity of a color.
  #### When not use:
  Useful for detecting colours as HSV (*or just hue?*) is better at detecting contrasts between colours than BGR/RGB
  #### When not to use:
  ???
  
  ### LAB:
  ??? anyone able to provide a succinct understandable description 
  #### When not use:
  ???
  #### When not to use:
  ???
  
---

## Channel
  ### Short-Description: 
  Colour images are composed of 3 channels. Each of these channels corresponds to the intensity value of one of the three primary colors. 
  ### Practical application example: 
  A BGR image is said to have 3 channels: a blue channel, a green channel and a red channel. A gray-scale image has 1 channel.
  ### When to use: 
  ### When not to use: 
  ### Related CV topics: 
  
---

## Histogram
  ### Short-Description: Describe 
  ### Practical application example: 
  ### When to use: 
  ### When not to use: 
  ### Related CV topics: 

---

