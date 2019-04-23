# Demonstrate a Front-End Web Programming Example

## Learning Goals

- Define web programming
- Identify reference example
- Identify the "Three Pillars of Web Programming"

## Introduction

"Front-End Web Programming" is a phrase that gets used in a lot of places by a
lot of people. In this lesson we're going to create a common definition of "web
programming" and show one example that demonstrates all of "web programming's"
parts.

### Define Web Programming

Web programming, at its heart, is:

> Creating documents with HTML, styling / positioning the document's content
> with CSS, and using JavaScript to provide interactivity / notify remote
> servers.

When a document has a lot of JavaScript code so that the page feels closer to a
computer application, people call it a "**web application**." There's no clear
line like "When there's three or more actions it's a web application!" That means
individuals' boundaries are different, but it's an application when it feels
"rich."

## Identify Reference Example

While this might be your first introduction to looking at some of your favorite
sites with "web programmer" eyes, you've probably experienced plenty of web
interactions that someone else programmed for you. As you move through the rest
of this material, we're going to use _one, tiny_ interaction as our shared
example.

> **Web Programming Example**: "Favoriting" a social media post.

Regardless of the social media site (Instagram, Pinterest, Facebook, LinkedIn,
Twitter), the interaction went something like this:

1. The site renders some HTML content that is styled using CSS
2. You see the content and decide to show your approval of it
3. You _click_ some visual element meant to show approval (heart,
   thumbs-up, +1, etc.). For example: <img src="https://curriculum-content.s3.amazonaws.com/fewpjs/fewpjs-fewp-example/empty.png" alt="Twitter empty heart">
4. The visual element _updates_ (animates, goes from empty to full, jiggles, etc) like:  <img src="https://curriculum-content.s3.amazonaws.com/fewpjs/fewpjs-fewp-example/full.png" alt="Twitter full heart">
5. Behind the scenes, the application _tells the provider_ that this
   post has gained your approval so that the central provider can notify 
   the creator or something similar

If all goes as it should, the entire process only takes a second or two. But
in this moment we did _all_ the work of front end web programming.

### Flatiron's "Three Pillars of Web Programming"

We can break down web programming into three essential "pillars": In the
previous list, we _italicized_  the characteristic verb in steps 3-5. Each of those
words exemplifies the activity of one of the "pillars" we must learn in order to be
web programmers.

  - Step 3 showed "**Recognizing JS events**:" Your _click_ action on the empty heart
    tells JavaScript to do work
  - Step 4 showed "**Manipulating the DOM**:" the work JavaScript was told to
    do was to _update_ the screen to make the heart "look clicked"
  - Step 5 showed "**Communicate with the server**:" the work JavaScript was
    told to do was to _tell the social media company_ that you approved of this
    content

Now you know what's going on when you click that heart! The next lessons will
focus on explaining each of the "pillars" to you. After you've worked your way through them, your new "web
programmer" eyes will have you looking at your favorite sites very differently.

## Conclusion

Web Programming is creating documents with HTML, styling / positioning the
documents' content with CSS and updating that content and servers based on
events using JavaScript. We can break down web programming into three pillars
that involve working with the DOM, JavaScript eventing and communication with
the server. Now that we've seen how these elements are connected in principle,
we can now move on to seeing how they work together in practice.

<p class='util--hide'>View <a href='https://learn.co/lessons/fewpjs-fewp-example'>Front-End Web Programming Example</a> on Learn.co and start learning to code for free.</p>
