<h1>Selling Music with Shopify</h1>

<p>Here's a few things I learned modifying shopify to sell music at <a href="http://theghostlystore.com/collections/frontpage/products/com-truise-galactic-melt">The Ghostly Store</a></p>

<h2>1. Music is a Product</h2>

<p>In Shopify, music should be thought of as a product, with different formats variants of that product.
There are two main types of variants that we use, and this is probably true for you as well: Physical Music and Digital Music.</p>

<h2>2. Properties</h2>

<p>In order to differentiate between Physical and Digital music, we'll first need to create some custom Properties. Shopify allows for up to 3 custom properties, and we'll have to use all three.</p>

<ol>
<li>FORMAT - what version is the customer buying, CD, Vinyl, 2xLP, etc.</li>
<li>NAME - what is the name of the thing they're buying. If Physical, this is the name of the release. If digital, this is the name of the song.</li>
<li>AUDIO - a url to your mp3 clip (IMPORTANT - whatever you link to can be grabbed right from the page, so don't link the whole song, link to a snippet)</li>
</ol>
<br><br>
<p><strong>It will look like once you get it set up:</strong><br /><img src="http://content.screencast.com/users/htmiguel/folders/Jing/media/3f533b10-e58c-49a7-be1e-556cfc298c64/00000294.png" width="500" /></p>
<br><br>
<p><strong>Then your product variants will look like this:</strong> <br /><img src="http://content.screencast.com/users/htmiguel/folders/Jing/media/5d1540fd-3903-4ee2-a82f-fa93d998cb27/00000291.png" width="500" /></p>

<h2>3. Templates</h2>

<p>Another critical part of this is the template you use. In order to render the player and tracklisting, you'll need to use the template with this code. I've created it as a separate template rather than baking it into your main template so you have flexibility to create different layouts for different products.<br /><img src="http://content.screencast.com/users/htmiguel/folders/Jing/media/8f93255b-3448-4cad-a7df-6ed83fe97661/00000295.png" width="" /></p>