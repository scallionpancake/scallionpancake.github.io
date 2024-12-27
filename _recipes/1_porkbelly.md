---
layout: page
title: project 1
description: hong shao rou
img: assets/img/recipes/porkbelly_bowl2.jpg
importance: 1
category: food
related_publications: true
---

---
layout: single
title: "braised pork belly"
permalink: /recipes/hongshaorou/
author_profile: true
categories:
  - recipes
  - food
tags:
  - recipes
  - food
feature_row:
  - url: "/nom/"
    btn_class: "btn--primary"
    btn_label: "back to recipes"
---

紅燒肉 | braised pork belly
and related: 滷肉飯, 東坡肉, 割包

this is one of my favorite and most commonly cooked recipes, as it is perfect for meal prepping - pork belly is a fairly cheap cut of meat, braising is relatively easy to do in bulk, and it tastes just as good, if not better, after a few days in the fridge. also, the recipe is really forgiving, so it is easy to adjust for personal taste.
references:

* [the red cook](https://redcook.net/2009/03/01/red-cooked-pork-redux/)
* [woks of life](https://thewoksoflife.com/braised-pork-belly-dong-po-rou/)
* [my insta](https://www.instagram.com/kuei.kitchen/)

## ingredients

* pork belly - hmart and similar often sell it as two big hunks, ~3 lbs

### braising liquid
* coca-cola, ~2 bottles
* soy sauce (生抽), ~2-3 tbsp
* dark soy sauce (老抽), ~2 tbsp
* shaoxing wine, ~1/4 cup
* sesame oil, ~1 tbsp

### spices
* star aniseed ~2 pieces
* ginger ~5 slices or so
* scallions, cut in big chunks
* 2-3 cloves garlic

### optional
* thai chilis and sichuan peppercorn (my taiwanese friends called me a heretic for this though hah)
* hard boiled eggs (I've had the most success soft-boiling them, and adding them to the braise partway)
* potatoes, carrots, radishes, pineapples all braise really well.
* fried shallots. 滷肉飯 recipes tend to use this.

## Directions

1. start by boiling water in a pot. add a few slices of ginger, and blanch the pork belly ~15-20 minutes. drain the pork belly on a plate, and put in the freezer for ~1/2 hour to firm up.
2. the chilled pork belly should be easier to cut, and you have a wide choice of form - for normal hong shao rou, go with cubes around 1-2 inches, for dong po rou, go with giant squares, for lu rou fan, cut into small slivers. The key is for each piece to have some skin, some fat, and some lean meat.
3. add all the spices and braising liquid into a pot. pad the bottom of the pot with scallions, particularly for larger pork belly chunks. make sure all the meat is submerged; if you need more liquid, add more soda or water.
4. bring to a boil, then cover and simmer for about 1 hour
5. remove the lid, then bring heat to med-high or so, reducing the sauce until desired consistency (the flavor and color will concentrate significantly, so keep an eye on it/taste as you go)
6. garnish with scallion, usually. I'd also recommend something sour-ish, like pickled mustard, the yellow pickled radishes, etc. to complement it too.

## tips:

* classic recipes caramelize the meat first, but as I am using soda, I skip this.
* you don't really need to stir the meat, if you pad the pot with scallions well. be careful at the end of the reducing though, you don't want to burn it.
* pork belly just gets more tender/melt-in-your-mouth if you braise longer, so adjust depending on what texture you like. I like it around ~1 hr; I've gone over 3 hrs and it works fine!
* you can swap out most of the ingredients. the classic is water, sugar, and shaoxing wine, but jack and coke works just as well. sweeter sodas (apple sidra) will lend a sweeter taste, if you like that. mirin is great too.

these go great on rice, but my favorite way to eat pork belly is in gua bao with cilantro, peanut powder (with some sugar), and some pickled mustard or pickled cabbage type deal. In one of Ken Liu's stories, a character says, “It’s all about the balance of the flavors. The Chinese know that you cannot avoid having things be sweet, sour, bitter, hot, salty, mala, and whiskey-smooth all at the same time — well, actually the Chinese don’t know about whiskey, but you understand my point"; I think a good 割包 hits all of those notes. 

## Picture references

![]({{ site.url }}{{ site.baseurl }}/images/recipes/porkbelly_bowl.jpg)

Every project has a beautiful feature showcase page.
It's easy to include images in a flexible 3-column grid format.
Make your photos 1/3, 2/3, or full width.

To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}.
Say you wanted to write a bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
