# Reordering mobile content with flexbox

Built for Wes Bos' [Flexbox course](https://flexbox.io/).

The page uses flexbox's `order` property to reorder content for mobile screens without reordering the elements in the DOM.

See the page live [here](https://gk-hynes.github.io/flexbox-mobile-reordering/)

Two things to remember:

It's good to wrap your page in a wrapper to give you something you can use as your flex container.

jQuery's `slideToggle()` doesn't work well with flexbox because it sets things to `display: block` when you might want them set to `display: flex`.

![Screenshot of flexbox ordering page on screens 500-1000px](https://res.cloudinary.com/gerhynes/image/upload/q_auto/v1540154904/Screenshot_2018-10-21_Flexbox_Reordering_1_j74zoh.png)

![Screenshot of flexbox ordering page under 500px](https://res.cloudinary.com/gerhynes/image/upload/q_auto/v1540154921/Screenshot_2018-10-21_Flexbox_Reordering_qnwqmb.png)
