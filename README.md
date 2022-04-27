## GlideJs Template

<img src="https://j.gifs.com/GRxnOL.gif"/>

## Intention

The purpose of this 'template' is to allow anyone to implement this elegant and responsive carousel in less than 1 minute without having to configure anything.
<br>
see in practice: <a href="https://glide-template.netlify.app/">Glide Template.</a>

## How to use

**Step 1**
clone the repository using:

```bash
$git clone https://github.com/kevenalves/glideTemplate.git
```
or
<a href="Glide.rar">Download the .zip file</a>

**Step 2**
... provide `<link>` to the required stylesheet. 
 ...

```html
<!-- Required stylesheet -->
<link rel="stylesheet" href="Glide\css\glide.css">
```

**Step 3**
... provide `<script>` to the required Javascript. 
 ...

```html
<!-- Required Javascript -->
  <script src="/Glide/js/glide.js"></script>
  <script src="/Glide/js/glideAnimation.js"></script>
```

**Step 4**
In the file `GlideCarousel.html` copy 'Glide Carousel' and paste in your HTML file.
In css you can edit the placement of the carousel by manipulating the class .container-Glide

```html
<div class="demoCode">
<!-- GLIDE CAROUSEL -->;
<div class="container-Glide">...
</div>    
<!-- END GLIDE CAROUSEL -->
```

**Step 5**
*Editing the elements*,
each `<li>` represents an element on the slide.
By editing the `<div>` 'center' / 'right' / 'left' you can change their content.

```html
<li class="frames__item glide__slide">
    <div data-ref="slidereveal[el]">
        <div class="frame" data-ref="hero[el]">
            <div center></div>
             <div right></div>
             <div left></div>
        </div>
    </div>
</li>
```

**Bonus**
The `glideAnimation.js` file is customizable.
You can configure the carousel according to your project.
To learn how to change properties, access the <a href="https://glidejs.com/docs/options/" target="_blank">documentation</a>.