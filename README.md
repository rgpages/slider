# slider

This is an image comparison slider.

**[Working example](http://pages.registerguard.com/slider/)**

**[Working story example](http://registerguard.com/rg/staging/31724631-110/fair-bob-indya-oregon-says.html.csp)**

Code tutorial: [Mobile-friendly, responsive scrubber](http://demosthenes.info/blog/842/A-Mobile-Ready-Before-And-After-Image-Comparison-UI)

Lightning implementation:

```html

<!-- This sets the height of the container. Set value depending on max height of image. -->
<div style=”max-height:980px!important;”>

    <!-- .mm makes it responsive and the padding-bottom makes it fill the full image -->
    <div class=”mm” style=”padding-bottom:100%;”>

        <!-- This is the iframe to the github page. Height is max height -->
        <iframe src=”http://pages.registergaurd.com/slider/” width=”100%” height=”980” frameBorder=”0” scrolling=”no”></iframe>

    </div>

</div>


```


See https://github.com/registerguard/tracker/issues/455 for more info.