## Tools for the workplace

I've been working on a single tool (more to come) that I would like to share with others. Github is a pretty easy (and free) space for me to share and manage these, so you will be able to find any bookmarklets that make the job easier here.

## What is a bookmarklet?

It's just a few lines of javascript that you can run from the bookmark bar. These should allow us to access information that is stored on any website, you just have to click the bookmarklet to run it.

## How do I add a bookmarklet to my browser?

Visit this site then click and drag any of the bookmarklet links into your bookmark bar.

![ ](https://media.giphy.com/media/cC9lrZ4Y0Xij0O22iL/giphy.gif)

## Bookmarklet(s)

#### Quick-Copy for theme ID.

[Copy Theme Name + ID](javascript:(function()%7Bvar themeID%3DShopify.theme.name%2B" ("%2BShopify.theme.id%2B")"%3Bvar el%3Ddocument.createElement(%27textarea%27)%3Bel.value%3DthemeID%3Bdocument.body.appendChild(el)%3Bel.select()%3Bdocument.execCommand(%27copy%27)%3Bdocument.body.removeChild(el)%3B%7D)())

#### Copy Shopify URL

[Copy Shopify URL](javascript:(function()%7Bvar shopName%3DShopify.shop%3Bvar el%3Ddocument.createElement(%27textarea%27)%3Bel.value%3DshopName%3Bdocument.body.appendChild(el)%3Bel.select()%3Bdocument.execCommand(%27copy%27)%3Bdocument.body.removeChild(el)%3B%7D)())

