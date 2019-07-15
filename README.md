# Flexbox

![alt text](https://raw.githubusercontent.com/AltCampus/flexbox/master/media/banner.png)

## Introduction

I hope we all have the basic knowledge of HTML and CSS now. In the last few days, we have learned how to position an element in a page according to the layout. We have learned about the floats and inline-block as well as a few advanced properties to position the elements. I am sure you all have been through the pains while working with the floats and a few other properties of positioning. Because I also have been the same problem as you guys are facing now.

We always had been doing all those hackish methods of floats, table displays, inline-block for positioning the elements. But we can ditch all the hacky methods now. We are ready to go with flexbox. Flexbox is one of the most interesting topics of CSS. I am sure while working flexbox you will enjoy and will have a lot of fun.

## What is flexbox?

Flexbox provides us a more efficient way to lay out elements. It gives us the ability to align the items and distribute space among the items in a container - even though the size of the elements are unknown or dynamic. With the flexbox we get the power of flexibility(as the word flex says) in order fill the available space. So that elements can easily accommodate according to the size of screens. In a flexbox container, item expands to fill the free space as well as shrinks to prevent overflow.

## How does the flexbox model work?

Flexbox model comes with some sets of properties and values. In that few properties can be applied to parent container and few can be applied only on children items. So to make use of those flexbox model properties and values we will have to go into the zone of flexbox. So how do we go into that?

To do so, we start with `display: flex` property and value. We set the parent's styles as `display: flex`. Once we do so we are in the zone of the flexbox model. Now we can get benefitted with the properties of the flexbox model. Without setting the parent element's style as `display: flex`, we cannot make use of any property related to the flexbox model.

So what happens we set the parent's style as `display: flex`. Let's check it out:

```
  <div class="container">
    <div class="item">1</div>
    <div class="item">2</div>
    <div class="item">3</div>
  </div>

  * {
    margin: 0;
    padding: 0;
  }
  .container {
    display: flex;
    background: #FAFFFC;
    border: 5px solid #182945;
  }
  .item {
    background: #9EDDEB;
    padding: 40px 50px;
    font-size: 34px;
    margin: 10px;
  }
```

![alt text](https://raw.githubusercontent.com/AltCampus/flexbox/master/media/intro.png)

This is how a simple flexbox model looks like. Once we say display flex to a parent element, it automatically becomes `flex container` and the children inside it becomes `flex-item`.

### Terminology:

While working with flexbox model, there are few basic terminologies that you need to keep in mind. For example `flex container and flex-item`, as I have used just a few lines above. I will explain all the terminologies as it comes in our flow.

For now, let's see what is `flex container and flex-item`?

1. https://css-tricks.com/snippets/css/a-guide-to-flexbox/

2. https://flexbox.io/
