# HTML Gurus

<img src="https://s3.amazonaws.com/after-school-assets/ryan-gosling-programmer-html.jpg" height="225px" align="right" hspace="10">

Without HTML, the internet today as we know it would not exist. While there are many many computer programming languages, HTML is one of three that are universal across every single website. Because of this, HTML is incredibly important to learn. And the best way to learn it? Practice!

Take a stab at the Album Cover lab, and use the resources below for some extra help! The first section below will walk you through how to get the lab into Nitrous so you can start coding, and the following section will walk you through some very useful HTML tags.

## Opening The Lab

###Step 1:

In Learn, view the Album Cover lab. Click on `Open` in the top left corner:

<img src="https://s3.amazonaws.com/after-school-assets/new-open-in-nitrous.png">


### Step 2

You'll want to look on the left side of Nitrous (the file navigator) and look at `Nitrous < Code < Labs < Album Cover`. To open the files to edit them, you can use the file navigator on the left side. Double click on `index.html` and it will open in the text editor.

### Step 3

You'll want to keep the `index.html` file open in both the Nitrous text editor, and the browser. To view the file in the browser, enter

```
python -m SimpleHTTPServer 3000
```

Once you have the server running, select `preview` and then `port 3000`.

<img src="https://s3.amazonaws.com/after-school-assets/nitrous-preview.png" alt="nitrous preview">

## Step 4

When you're done with you're work, it's important to push your work to GitHub. Remember, that's your online developer portfolio. In Nitrous, in terminal in the `Album Cover` directory, enter `learn submit`. This will push your code to GitHub (you can see it if you look at your repositories!) and mark the lab as complete.


## Share Share Share!

When you're done, don't forget to share your amazing work! Screenshot your completed album cover or code and share with **\#flatironcodeclub** and **\#pharrellneedsme

## Most Frequently Used Tags

### `h1` through `h6` tags


This tag is used for headings. There are 6 different levels of header tags,  with `<h1>` being the most important and `<h6>` being the least (in between are `<h2>`, `<h3>`, `<h4>` and `<h5>`. Headings are great for introducing sections in your website.

These different header tags require an opening tag `<h1>` and a closing tag `</h1>`. These opening and closing tags should surround the text you want to be the header of your site.

Here are all the header tags side by side so you can see the difference:

<img src="https://after-school-assets.s3.amazonaws.com/h1-h6.png">

### `p` tag

Use this tag for chunks of normal text. The `p` stands for paragraph. Again, this tag needs both and opening and a closing tag surrounding the paragraph.

### `br` tag

HTML doesn't understand whitespace, which means if in your HTML file you press the return key a bunch of times and have a lot of empty lines, your browser won't recognize those empty lines. Use `<br>` to manually create those empty lines. Notice how `<br>` is one of the only tags that doesn't require a closing tag.

### `a` tag

The `<a>` tag is a link tag. The `href` part is an **attribute** of the `<a>` tag. `href` stands for "hyperlink reference". An attribute gives more information about the tag. In the quotes following the `=` is where you would put the website you are linking to. For example, if you were trying to link to Google, you would write `<a href="http://www.google.com">Click here to go to Google</a>`.

The `a` tag also has an opening and a closing tag. The text between the two is the text of the link.

### `img` tag

The `<img>` tag is for images. `src` is an attribute of the `<img>` tag, where you list the source of the image you want to display on your website.  The `alt` attribute stands for alternate text. This text will display on your website if for some reason the image can't. You can link directly to an image you found on a separate website, in which case you would list the URL to the image. 

```html
<img src="http://cdn.sheknows.com/articles/2013/04/Puppy_2.jpg" alt="puppies"> 
```

Or you can link to images stored on your computer, in which case you would list the path to the image. If I was working on a website (stored in a directory called `my_website`), I would have an `index.html` to build the HTML of my website, and a directory called `images` to store my images. Let's say inside of `images`, I had a picture called `puppies.jpg`, which was a picture I took of some puppies in the park. Take a look at that file structure below:

```bash
my_website/
├── images
│   └── puppies.jpg
└── index.html
```

If I wanted to display that picture in my website, the `img` tag would look like this:

```html
<img src="images/puppies.jpg">
```


The `img` tag does not have a closing tag; it's the rare exception.

### `title` tag

The `<title>` tag is used for the title of your site. This is the text that will be displayed in the browser tab.

Your code will look something like this:

<img src="https://s3.amazonaws.com/after-school-assets/title-tag.png">

And in the browser like this:

<img src="https://s3.amazonaws.com/after-school-assets/title-tag-in-browser.png">

### `span` tag

The `<span>` tag is used as a container to group lots of HTML elements together, or text. This is important if I want to group together an `h1`, `h2` and a  `p` tag so that we could eventually make them all have the same font color and font size, it would be easier to group them in a `span` and then apply styling. Don't worry too much if that was a confusing explanation, we'll get into styling next lesson!

```html
<span>
  <img src="http://cdn.sheknows.com/articles/2013/04/Puppy_2.jpg"> 
  <p> Puppy kitty ipsum dolor sit good dog cockatiel wag tail ball finch bedding kitty walk fleas wagging kitty fish bed. Stripes vaccine ferret mouse dinnertime house train litter box pet gate slobber pet food pet supplies pet gate meow play dead roll over teeth warm. Finch catch house train lol catz Spike finch parrot feathers chow bark furry pet supplies treats.</p>
</span>
```

### `div` tag

The `<div>` tag is very similar to the `<span>` tag and is used to group other HTML elements together. The difference between `div` and `span` is only apparent when you start to get into page layout with CSS. For now, don't worry about it. Just know they operate the same!

```html
<span>
  <img src="http://cdn.sheknows.com/articles/2013/04/Puppy_2.jpg"> 
  <p> Puppy kitty ipsum dolor sit good dog cockatiel wag tail ball finch bedding kitty walk fleas wagging kitty fish bed. Stripes vaccine ferret mouse dinnertime house train litter box pet gate slobber pet food pet supplies pet gate meow play dead roll over teeth warm. Finch catch house train lol catz Spike finch parrot feathers chow bark furry pet supplies treats.</p>
</span>
```


