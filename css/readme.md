##Core-Grid
The grid I've created here uses a 12 column system and it will be responsive across all devices. You have the typical col classes and push and pull classes for offsets. You can also hide and show certain HTML elements with the hide and show classes listed below.

I will update this section with better wording and clear documentation as I go, but I will give you a simple run down now for those interested...

#####The Naming Convention:
The columns are called with the "col-" name prefix and the shorthand is "c-" the numbers that follow will go from 1-12. 

```HTML
<div class="row">
  <div class="col-12"> This will spam the full grid. </div>
</div>
```
The shorthand alternative:
```HTML
<div class="row">
  <div class="c-12"> This will spam the full grid. </div>
</div>
```

---

#####Just think of the grid visually, anything totally 12 across will be fine. See examples below.

```HTML
<div class="row">
  <div class="col-6"> This will spam half of the grid. </div>
  <div class="col-6"> This will spam half of the grid. </div>
</div>
```
Or something like...
```HTML
<div class="row">
  <div class="col-3"> Perfect for a sidebar menu or something... </div>
  <div class="col-9"> Main content area alongside your side menu :) </div>
</div>
```

#####Now I've included some center classes and offsets too, here is how you would use a center column...

```HTML
<div class="row">
  <div class="col-6-center"> Perfect for an article listing on a blog maybe? </div>
</div>
```
The center classes also use the shorthand varients of "c-" such as "c-6-center"

---

As for the offsets, there are two ways to call them, I decided to include both naming conventions to try to not confuse people with pushing and pulling columns, which is easier to type and use, but for some it seemed to be a little harder to understand (for those not as well versed with html/css frameworks or css in general) so you can call the push and pull classes like this "push-" and "pull-" or alternatively if you don't quite understand those... You can use... "offset-right-" and "offset-left-" and you will be doing the same things :)

Here is an example of both... Push and Pull:
```HTML
<div class="row">
  <div class="col-3 push-3"> This will push the element toward the center towards the right</div>
  <div class="col-3 pull-3"> This will pull the element toward the center towards the left </div>
</div>
<!-- Ultimately the above will center two 3 column grid content sections next to each other, if you do the math it all still totals to 12-->
```
Now for those wanting to use "offsets" within the naming convention:
```HTML
<div class="row">
  <div class="col-3 offset-right-3"> This will push the element toward the center towards the right</div>
  <div class="col-3 offset-left-3"> This will pull the element toward the center towards the left </div>
</div>
<!-- Ultimately the above will center two 3 column grid content sections next to each other, if you do the math it all still totals to 12-->
```

---


###I hope that this covers the basic use of the grid for those capable of using it, I will update the full documentation and upload it to my site as soon as I am able to finish re-building the framework from an accidental delete recently. At least now, it's backed up in Github!
