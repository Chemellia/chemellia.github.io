@def title = "More goodies"
@def hascode = true
@def rss = "A short description of the page which would serve as **blurb** in a `RSS` feed; you can use basic markdown here but the whole description string must be a single line (not a multiline string). Like this one for instance. Keep in mind that styling is minimal in RSS so for instance don't expect maths or fancy styling to work; images should be ok though: ![](https://upload.wikimedia.org/wikipedia/en/b/b0/Rick_and_Morty_characters.jpg)"
@def rss_title = "More goodies"
@def rss_pubdate = Date(2019, 5, 1)

@def tags = ["syntax", "code", "image"]

# More goodies

~~~
<section>
<div class= 'blog-box' >
  <img class='blog-image' src='/assets/posts/julia.png' />
  <div class='blog-description'>
    <h1> sample blog </h1>
    <p> test test </p>
    <a href="/posts/test/index.html"><button> Continue reading </button> </a>
  </div>
</div>

</section>
~~~
