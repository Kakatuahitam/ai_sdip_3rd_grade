---
jupytext:
  formats: md:myst
  text_representation:
    extension: .md
    format_name: myst
    format_version: 0.13
    jupytext_version: 1.11.5
kernelspec:
  display_name: Python 3
  language: python
  name: python3
---

# [03] Move Your Body! [I]
<!--  -->
Hi, we recite Basmallah together before start our session

> **Bismillahirrahmanirrahim**

## We are able to shoot! What we gonna do now?
<!-- Introduction -->

On the last session, we already made our Shooter character with the ability of shooting some projectiles. Unfortunately, we need more time to make it move to the right and to the left. In this session, we will make it happen after we do another 'magic trick' to make our Shooter able to jump!

Long story short, let's do it now!

---
## Jumping? What are the step for it?
<!-- Connection -->
```{figure} ../_static/images/content/jumping_mario.webp
:label: Limitless Jump!
:alt: Jumping Mario
:height: 200px
:align: center

He is jumping to the top endlessly! But, let's think about it. There must be a button that player needs to press!
```

Jumping needs some movement in a sequence. The character jumps after we push a button, like {kbd}`Up` or {kbd}`Space`!

Let's break it down 👇🏻:
```{figure} ../_static/images/content/breakdown.webp
:label: Limitless Jump!
:alt: Jumping Mario
:height: 200px
:align: center
```

1. Player presses the jump button
1. The character starts to move up
1. The character then move down to the ground

That's it!

---
## Let's break the leg!
<!-- Application -->

Determine what components/blocks we need first, Lets jump into Scratch app to see it live!

:::{tip} 1. Add starter code for our 😺 `cat` to make it safe when everything is messy
:class: dropdown
```{figure} ../_static/images/content/03/starter.png
:align: center
```
:::

:::{tip} 2. Add an up arrow like we did in the previous meeting
:class: dropdown
```{figure} ../_static/images/content/03/add_arrow.png
:align: center
```
:::

:::{tip} 3. Put this code for the ⬆️ arrow
:class: dropdown
```{figure} ../_static/images/content/03/create_variable.png
:align: center
```

Tap on the message1 to create new variable and we name it `jump`

```{figure} ../_static/images/content/03/name_jump.png
:align: center
```

Then, this is the result if you do it correctly
```{figure} ../_static/images/content/03/jump_variable.png
:align: center
```
:::

:::{tip} 4. And do not forget to add starter code. Here is the final code for the ⬆️ arrow
:class: dropdown
```{figure} ../_static/images/content/03/up_arrow_code.png
:align: center
```
:::

:::{tip} 5. Then, we make a custom object named `ground` for the in game ground. Select Paint from the lower right of your screen
:class: dropdown
```{figure} ../_static/images/content/03/select_paint.png
:align: center
```

Here is what on your screen right now
```{figure} ../_static/images/content/03/screen_after_choose_paint.png
:align: center
```

Choose rectangle icon like shown below
```{figure} ../_static/images/content/03/choose_rectangle.png
:align: center
```

Then, draw a very long rectangle like this on the bottom part
```{figure} ../_static/images/content/03/draw_rectangle.png
:align: center
```

Here is the result. And but, we need to move our ⬆️ button to the top layer, go to the next step!
```{figure} ../_static/images/content/03/current_screen_after_ground.png
:align: center
```
:::

:::{tip} 6. Get back to the code of ⬆️ button to add this code. The goal is to bring it to the front layer, so it appears on the front!
:class: dropdown
```{figure} ../_static/images/content/03/go_to_front_layer.png
:align: center
```

Then, click our flag/start button to see this effect
```{figure} ../_static/images/content/03/current_screen_after_move_front.png
:align: center
```
:::

:::{tip} 7. Next, we go to the `ground` code and put these blocks
:class: dropdown
```{figure} ../_static/images/content/03/ground_code.png
:align: center
```
:::

:::{tip} 8. The final step before everything works, let's put this code for our beloved 😺 `cat` object!
:class: dropdown
```{figure} ../_static/images/content/03/cat_code.png
:align: center
```
:::

:::{tip} 9. Finally, here are our final code
:class: dropdown
```{figure} ../_static/images/content/03/final_code_cat.png
:align: center
```
```{figure} ../_static/images/content/03/final_code_ground.png
:align: center
```
```{figure} ../_static/images/content/03/final_code_up.png
:align: center
```
:::

---
## Huft, that was soooo exciting!. We can make it jump now!

Yes, we did it. The result is same with our preview before
```{figure} ../_static/images/content/03/final_result.gif
:align: center
```

---
## For the next thing

After we do code like shown before, you may create various decoration like adding background or another object!

And, see ya on the next session!
