# digital_banking_landing_page
A simple layout for a banking service landing page made from html and css

## Challenges 

1. How to add background-image behind an already exisiting background-image

2. How to manipulate position of background-image

3. How to make anchor tag direct to new tab

4. How to limit growth of the image as screen expands

## Solutions
1. The image itself had a clear background allowing the background image to show behind it

2. Turns out it was an image, not a bg-image, one solution was to use `position: rellative` and set it points using non-fixed units to help keep that resposiveness

3. To make anchor direct to new tab include the `rel='noopner noreferer'` attribute

4. Use the max-block-size and set height to auto, it allows image to grow and not pass constraints

# Technologies

- HTML
- CSS
- Git