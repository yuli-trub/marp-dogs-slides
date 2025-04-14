---
marp: true
# init marp
theme: my-theme
# configure custom theme linked to css file (for the VS code extention had to add path, for the npm run - wrote a script that included customed theme configuration)
---

<!-- first slide - just a tittle - h1 -->

# Different Dog Breeds

---

<!-- image positioning with  md image syntaxt to try it out - this one has label if it doesn't render the image correctly and setting it to basic split background positioned to the right with split size 60% -->

![ Australian Shepherd bg right:60%](./images/australian-shepherd-1.jpg)

<!-- adding a class that will work on this slide and the next ones - this class is used to style the header to have text-align: center property-->
<!-- class: centered -->

## Australian Shepherd

<!-- this is h2 -->

---

<!-- new slide -->

## Bulldogs

<!-- h2 -->

<!-- to use flex layout
- creating a wrapper div with class flexed and divs inside (initially these were just images but then added the labels (<p>) so had to wrap them in div to have nicer layout)
- then having an image tag  (now realised that all of the images need alt attribute for accesibility)
 -->
<div class="flexed">
    <div>
    <img src='./images/english-bulldog-1.jpg' alt='English bulldog'>
    <p class="caption">English</p>
    </div>
    <div>
    <img src='./images/french-bulldog-1-1.jpg' alt='French bulldog'>
    <p class="caption">French</p>
    </div>

</div>

---

<!-- _class: side -->
<!-- this class is local in marp and is only gonna be applied to this slide, this is to align the text on the left
- here usng html to align the image on the left also using flex
-->

<div class="split-side">
  <img src="./images/yorkshire-terrier-1.jpg" alt='Yorkshire Terrier' />
  <div>
    <h2>Yorkshire Terrier</h2>
    <p>Yorkies, are small dogs with big attitudes. Despite their small size, Yorkies are brave and confident, often acting as little watchdogs to their owners.</p>
  </div>
</div>

---

## More of the dogs

<!-- h2 -->

<!-- here aligning the images with grid, so wrapping everything in div as a parent container with class grid, then using figure as a wrapper of the iage and the caption for it -->
<div class="grid">
    <figure>
        <img src="./images/beagle-1.jpg" alt='Beagle'>
        <figcaption class="caption">Beagle</figcaption>
    </figure>
    <figure>
        <img src="./images/boxer-1.jpg" alt='Boxer'>
        <figcaption class="caption">Boxer</figcaption>
    </figure>
    <figure>
        <img src="./images/cane-corso-1.jpg" alt='Cane Corso'>
        <figcaption class="caption">Cane Corso</figcaption>
    </figure>
    <figure>
        <img src="./images/cavalier-king-charles-1.jpg" alt='Cavalier Spaniel'>
        <figcaption class="caption">Cavalier Spaniel</figcaption>
    </figure>
    <figure>
        <img src="./images/dachshund-1.jpg" alt='Dachshund'>
        <figcaption class="caption">Dachshund</figcaption>
    </figure>
    <figure>
        <img src="./images/miniature-schnauzer-1.jpg" alt='Miniature Schnauzer'>
        <figcaption class="caption">Miniature Schnauzer</figcaption>
    </figure>

</div>
