## Trend Talk (Practical Overview - Top Down Approach)

![[Pasted image 20230924114808.png]]
In this session want to get familiar with Tailwind, it's Pros and Cons, to see if we can use it to improve our developer experience and code maintainability, simple if it is good for us or not!

## What exactly Tailwind is?

**[wikipedia.org:](https://en.wikipedia.org/wiki/Tailwind_CSS)**

> **Tailwind CSS** is an open source CSS framework CSS framework. The main feature of this library is that, unlike other CSS frameworks like Bootstrap, it does not provide a series of predefined classes for elements such as buttons or tables. Instead, it creates a list of "utility" CSS classes that can be used to style each element by mixing and matching

## What are the Tailwind pros, and what makes it so popular?

1. **Time saving.**
   Once you learn the classes you can apply it very quickly definitely faster than writing CSS from scratch.
2. **Fully customize**
   With tailwind unlikely to Bootstrap or MUI, you have a huge array of different classes that are going to allow you to style these things exactly like you want. In Bootstrap or MUI or Foundation you're stuck with the particular classes they give you and if you want to change them, you need to go in there and modify your own CSS or overwrite them with inline styles
3. **Flexibility and easy to change**
   Imagen you have a `primary-button` class, and you want to add a new primary button, that is slightly darker then original one, you should add a new class called `button-primary-dark`, then if you want a lighter version you need to add a new class called `button-primary-light`, then if you have a large and small version for each of them, you have `button-primary-dark-lg, button-primary-dark-sm`, `button-primary-light-lg`, `button-primary-light-sm` and so on. it just start to get more complicated as you have all these different expectations. But with Tailwind all you do is you take that background color CSS class and you just change it to be darker or lighter, or make the font size bigger or smaller etc.
4. **Design limitation**
   Tailwind imposes upon you limitations and these limitations make it so that your designs are much more coherent and they look a lot better because instead of using certain amount of `px` to for example `padding-left: 7px; padding-right: 10px`, you can use `p1` or `p2`, and these are actual values. It's forcing you to specify exact sizing that fall within a design system
5. **Entirely configurable**
   You can pretty much change every single one of the preset default values in the design system to be what you want for example, you can set your custom `font-family` instead of default fonts.
6. **Easy to learn**
   Tailwind has a really great documentation. Furthermore Tailwind is nothing more than CSS.
   ![](assets/Pasted%20image%2020230924115019.png)
7. **Removes un-used css classes(minimal css size)**
   ![](assets/Pasted%20image%2020230924115028.png)

## Is Tailwind the best CSS framework in the world, aren't there any cons to it?

1. **Too much classes in html**
   ![](assets/Pasted%20image%2020230924115036.png)
   Solution:
   Inline/tailwind fold
   ![](assets/Pasted%20image%2020230924115041.png)
2. **Hard to maintainability when you don't use any of JavaScript frameworks.**
   because if you have to copy your button styles which is like 8 or 9 different classes to every single button on your page, it's not good. Furthermore, if you want to change some style on these buttons, you should go through all of them and change them one by one. But if you're using one the JavaScript framework like React, you can just create a component for button and use it.
3. **It's not suitable for how is not familiar with CSS**
   in order to fully take advantage of Tailwind, you need to understand how CSS works at a core level because every CSS class in Tailwind is just like applying an individual CSS property and if you don't understand how CSS works and how the different properties work together you're not going to be able to use Tailwind to create a good design.

## Testimony

Maybe it would be better to take a look to testimony, to see who are using the Tailwind and suggesting it:-)

Actually there are a lot of famous people or big companies are which using the tailwind, but to make it quick I just mentioned some of them which I like most:

1. The first one is Kent C Dodds which is a famous person

![](assets/Pasted%20image%2020230924114853.png)

2. The second one is Fireship

![](assets/Pasted%20image%2020230924114902.png)

3. As the 3rd one let's instead of a third person check a very familiar project to you which is Our projects are mostly based on that:
   Yeah Nuxt also uses Tailwind

![](assets/Pasted%20image%2020230924114911.png)

![](assets/Pasted%20image%2020230924114925.png)

- https://openai.com/

- https://www.shopify.com/

- https://react.dev/

- https://vercel.com/

- https://nextjs.org/

- ....

There are a giant list of componies and projects which are adopting tailwind more and more per year as you can see on npmtrends the install per week raised from 1m to 6 m

![](assets/Pasted%20image%2020230924114937.png)

In addition to that, we can see Tailwind kept it's interest rate among the developers Higher than any other solutions through out the years:

![](assets/Pasted%20image%2020230924114956.png)

![](assets/Pasted%20image%2020230924115001.png)

and also it's usage rate is second to bootstrap:

![](assets/Pasted%20image%2020230924115005.png)

![](assets/Pasted%20image%2020230924115010.png)

Resources:
https://www.youtube.com/watch?v=hdGsFpZ0J2E&t=202s&ab_channel=WebDevSimplified
https://www.youtube.com/watch?v=CLkxRnRQtDE&ab_channel=TailwindLabs
