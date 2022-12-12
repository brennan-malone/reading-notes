# Read: 11 - Video and Audio Content

## Visual and Audio content

1. Explain how the ability to use video and audio on the web has evolved since the early 2000s.
   * There are not more proprietary lugin-based technologies like flash and silver light. The industry has moved over to native HTML solutions like \<video> and \<audio>
2. Describe the use of the src and controls attributes in the \<video> element.
   * src works the exact same as it does in the img element. Provides a path to the video to embed. 
   * There must be a way for the user to control the video and audio playback. This can be done with the control element.
3. Why is it important to have fallback content inside the <video> element?
   * In case the browser accesing page does not support the video element. 
4. Write a very short story where \<audio> and \<video> are characters.
   * "hey video I see you are new here. what did you get hired to do." -said audio "hey audio, unlike you I have a visual component and suppoort the width, height, and poster attributes." -said video.
	
## A Complete Guide to Grid

1. How does Grid layout differ from Flex?
   * Grid is a two dimensional layout system. Flexbox is also a layout tool, but it works in one dimension.
2. Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.
   * grid container is refering to the display grid property that allows the css to layout the webpage as a grid
   * a grid container will have grid items that are the children of the display gri property. This determines where the item will be aligned
   * gird lines refer to the columns and rows that are between the grid items. They determine positioning of the grid items and allow for gutters and space between items

## Responsive images

1. Besides making a site visually appealing across different screen sizes, why should developers make images responsive?
   * to resolve issues that arise from art direction problems and resolution switching problems that are introduced when viewing something on a mobile or tablet platform.
2. Define the following \<img> attributes srcset and sizes. Write an example of how they are used.
   * srcset defines the set of images we will allow the browser to choose between based on the size of the image needed.
   * sizes defines a set of media conditions that indicates what image size to use.
3. How is srcset more helpful for responsive images than CSS or JavaScript?
   * This is helpful because images start to preload before the main parser has started to load and interpret the page.

## Things I want to learn more about

* I would like to learn more about grid and how to use it.