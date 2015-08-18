# HTML Gurus

<img src="https://s3.amazonaws.com/after-school-assets/ryan-gosling-programmer-html.jpg" height="225px" align="right" hspace="10">

Without HTML, the internet today as we know it would not exist. While there are many many computer programming languages, HTML is one of three that are universal across every single website. Because of this, HTML is incredibly important to learn. And the best way to learn it? Practice!

Take a stab at the Album Cover lab, and use the resources below for some extra help! The first section below will walk you through how to get the lab into Nitrous so you can start coding, and the following section will walk you through some very useful HTML tags.

## Opening The Lab

###Step 1:

In Learn, view the Album Cover lab. Click on `Open in Nitrous` in the top left corner:

<img src="https://s3.amazonaws.com/after-school-assets/open-in-nitrous.png">


### Step 2

To open the files to edit them, you can use the file navigator on the left side. Double click on a file and it will open in the text editor.

### Step 3

You'll want to keep the `index.html` file open in both the Nitrous text editor, and the browser. To view the file in the browser, enter

```
python -m SimpleHTTPServer 3000
```

Once you have the server running, select `preview` and then `port 3000`.

<img src="https://s3.amazonaws.com/after-school-assets/nitrous-preview.png" alt="nitrous preview">

## Most Frequently Used Tags

### `<h1> </h1>` through `<h6> </h6>`

This tag is used for headings. There are 6 different levels of header tags,  with `<h1>` being the most important and `<h6>` being the least. Headings are great for introducing sections in your website.

These different header tags require an opening tag `<h1>` and a closing tag `</h1>`. These opening and closing tags should surround the text you want to be the header of your site.

Here are all the header tags side by side so you can see the difference:

<img src="https://after-school-assets.s3.amazonaws.com/h1-h6.png">

### `<p> </p>`

Use this tag for chunks of normal text. The `p` stands for paragraph. Again, this tag needs both and opening and a closing tag surrounding the paragraph.

### `<br>`

HTML doesn't understand whitespace, which means if in your HTML file you press the return key a bunch of times and have a lot of empty lines, your browser won't recognize those empty lines. Use `<br>` to manually create those empty lines. Notice how `<br>` is one of the only tags that doesn't require a closing tag.

### `<a href="www.google.com"> CLICK HERE </a>`

The `<a>` tag is a link tag. The `href` part is an **attribute** of the `<a>` tag. An attribute gives more information about the tag. In the quotes following the `=` is where you would put the website you are linking to. For example, if you were trying to link to Google, you would write `<a href="www.google.com">Click here to go to Google</a>`.

The `a` tag also has an opening and a closing tag. The text between the two is the text of the link.

### `<img src="http://cdn.sheknows.com/articles/2013/04/Puppy_2.jpg"> `

The `<img>` tag is for images. `src` is an attribute of the `<img>` tag, where you list the source of the image you want to display on your website. You can link directly to an image you found on a separate website, in which case you would list the URL to the image. Or you can link to images stored on your computer, in which case you would list the path to the image. The `img` tag does not have a closing tag; it's the rare exception.

### `<title> </title>`

The `<title>` tag is used for the title of your site. This is the text that will be displayed in the browser tab.

```html
<title> Puppies</title>
```

### `<span> <span>` 

The `<span>` tag is used as a container to group lots of HTML elements together, or text.

```html
<span>
  <img src="http://cdn.sheknows.com/articles/2013/04/Puppy_2.jpg"> 
  <p> Puppy kitty ipsum dolor sit good dog cockatiel wag tail ball finch bedding kitty walk fleas wagging kitty fish bed. Stripes vaccine ferret mouse dinnertime house train litter box pet gate slobber pet food pet supplies pet gate meow play dead roll over teeth warm. Finch catch house train lol catz Spike finch parrot feathers chow bark furry pet supplies treats.</p>
</span>
```


