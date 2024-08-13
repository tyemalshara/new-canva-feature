# new-canva-feature
This Repo demonstrates a better way than Canva to turn objects in image into a mockup-able, after witnessing a weird behavior (inconsistency of the image to be added to the mockup) when trying to change the background of a window by using the Click feature of Magic Edit in the Magic Studio.

![empty mockup](base_image.png "empty/unedited Mockup - Goal is to change the view of the window" =50%x) ![inserted mockup](filled_polygon_image_starrysky.jpg "inserted/edited Mockup - see window!" =50%x)

empty mockup             |  inserted mockup
:-------------------------:|:-------------------------:
![empty mockup](base_image.png "empty/unedited Mockup - Goal is to change the view of the window")  |  ![inserted mockup](filled_polygon_image_starrysky.jpg "inserted/edited Mockup - see window!")

<p align="middle">
  <img src="/base_image.png" alt="empty mockup" title="empty/unedited Mockup - Goal is to change the view of the window"  />
  <img src="/filled_polygon_image_starrysky.jpg" alt="inserted mockup" title="inserted/edited Mockup - see window!"  /> 
  <img src="/window box prompt for sam.jpg" alt="image with SAM point and box Prompts for smart area selection" title="image with SAM point and box Prompts for smart area selection"  />
</p>

## Features

- Turn any image to a mockup, and insert any image to the photo of your choice — wether on a window or a t-shirt.
- Drag and drop images (will be added to new releases when asked for)
- No need to browse endless catalog of customizable mockup templates and end up not finding one. create your very own template, cause your image can be turned onto a mockup template with one click of a button! (WebApp will be devoloped when asked for)
- inserted Images into mockups look magical and natural.

## Tech

- [PyTorch] - A Machien Learning framework
- [Ikomia] - Streamlining ML workflows and deployment 
- [Stable Diffusion] - Generate images with text prompts
- [OpenCV] - process images library
- [Google Colab] - An invironment for running GPU instensive workflows 
- [SAM] - Segment Any Thing by Meta, hence the name, segment objects in images through point or/and box prompts.

## Installation

GPU with 12.5 GB of VRAM. 
Simply Copy Colab Notebook, add your image and the image to be inserted and run it. 

Install the dependencies -> Ikomia

```python
!pip install ikomia
```

## License

MIT

**Free Software, Hell Yeah!**
