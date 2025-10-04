---
layout: post
title: FSAE Mk. 11 Competition EV
description: 
    My contributions to my team's FSAE car, the "Mk. 11," involves the design of a series of robust standardized enclosures meant to house low-voltage electronics such as printed circuit boards (PCBs) and the low-voltage battery, as well as the physical layout of the wire harness throughout the chassis.
skills: 
  - CAD
  - 3-D Printing
  - Rapid Prototyping
  - Development of manufacturing processes
  - Verification & Validation

main-image: /project2.jpg
---

---
## Header 2  
Use this for the header of each section
### Header 3 
Use this to have subsection if needed

## Enclosure Requirements
The initial stages of the design cycle required a robust first-principles approach on my end, as these proposed enclosures were a completely new structure to be added to the vehicle. Anything I did for these enclosures would set a precedent for the team going forward, so it was imperative that I set a quality standard backed by testing and research to allow future team members more room to innovate. I began by establishing a list of criteria the enclosures had to fulfill based on the team's prior experience with our previous EV, "Mk. 10." Those criteria were:
1. Simplicity - Wherever possible, I wanted to implement the simplest solution possible; simplicity was key.
2. Serviceability - Due to the nature of FSAE, my team would require constant access to any component my enclosures contained for maintenance. For this reason, the serviceability of the enclosure needed to be well-developed, providing easy access to my team whenever they needed it.
3. Weatherproofing - At competition, one of the static events is an inspection known as the rain test, where the car is subjected to a few minutes of jets of water meant to simulate a rainy environment. One of the chief concerns on my end would be preventing any of that water from potentially leaking into any of my enclosures, protecting the sensitive electronics inside. 
4. Decentralization - Some electronics are positional and function in many different areas of the car, such as the wheels or dashboard. Instead of running wires from a centralized electronics box, I decided to opt for a decentralized approach, mounting electronics as close to the relevant areas of the car as possible.
5. Form Factor - Enclosures needed to be as small and light as possible.
6. Standardization - I decided to push for standardization of the hardware and design of the enclosures, and maintain maximal uniformity of the design across the car.
7. Redundancy - In case of potential failure, I wanted to account for that by adding some redundancy to the design,
8. Reliability - Minimizing the amount of maintenance required is also a quality I wanted to have in my design.


## Design Choices and Justification
### Simplicity
Generally, simpler solutions to problems would be preferred, as they save on costs, are easier to implement and maintain, and are often more elegant.
### Servicability
### Weatherproofing
### Decentralization
I decided to opt for a decentralized grid mainly because the team and I decided it would be best to shorten the wire lengths wherever possible. The justification for this decision is that shorter wires would save weight and provide less potential for failure through disconnection, as shorter wires would naturally have less areas for any potential wire severance.
### Form Factor
### Standardization
### Redundancy
### Reliability


## Testing and Analysis


## Embedding images 
### External images
{% include image-gallery.html images="https://live.staticflickr.com/65535/52821641477_d397e56bc4_k.jpg, https://live.staticflickr.com/65535/52822650673_f074b20d90_k.jpg" height="400"%}
<span style="font-size: 10px">"Starship Test Flight Mission" from https://www.flickr.com/photos/spacex/52821641477/</span>  
You can put in multiple entries. All images will be at a fixed height in the same row. With smaller window, they will switch to columns.  

### Embeed images
{% include image-gallery.html images="project2.jpg" height="400" %} 
place the images in project folder/images then update the file path.   


## Embedding youtube video
The second video has the autoplay on. copy and paste the 11-digit id found in the url link. <br>
*Example* : https://www.youtube.com/watch?v={**MhVw-MHGv4s**}&ab_channel=engineerguy
{% include youtube-video.html id="MhVw-MHGv4s" autoplay= "false"%}
{% include youtube-video.html id="XGC31lmdS6s" autoplay = "true" %}

you can also set up custom size by specifying the width (the aspect ratio has been set to 16/9). The default size is 560 pixels x 315 pixels.  

The width of the video below. Regardless of initial width, all the videos is responsive and will fit within the smaller screen.
{% include youtube-video.html id="tGCdLEQzde0" autoplay = "false" width= "900px" %}  

<br>

## Adding a hozontal line
---

## Starting a new line
leave two spaces "  " at the end or enter <br>

## Adding bold text
this is how you input **bold text**

## Adding italic text
Italicized text is the *cat's meow*.

## Adding ordered list
1. First item
2. Second item
3. Third item
4. Fourth item

## Adding unordered list
- First item
- Second item
- Third item
- Fourth item

## Adding code block
```ruby
def hello_world
  puts "Hello, World!"
end
```

```python
def start()
  print("time to start!")
```

```javascript
let x = 1;
if (x === 1) {
  let x = 2;
  console.log(x);
}
console.log(x);

```

## Adding external links
[Wikipedia](https://en.wikipedia.org)


## Adding block quote
> A blockquote would look great if you need to highlight something


## Adding table 

| Header 1 | Header 2 |
|----------|----------|
| Row 1, Col 1 | Row 1, Col 2 |
| Row 2, Col 1 | Row 2, Col 2 |

make sure to leave aline betwen the table and the header
