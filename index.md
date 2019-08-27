## Tools for the workplace

I've been working on a single tool (more to come) that I would like to share with others. Github is a pretty easy (and free) space for me to share and manage these, so you will be able to find any bookmarklets that make the job easier here.

## What is a bookmarklet?

It's just a few lines of javascript that you can run from the bookmark bar. These should allow us to access information that is stored on any website, you just have to click the bookmarklet to run it.

## How do I add a bookmarklet to my browser?

Visit this site then click and drag any of the bookmarklet links into your bookmark bar.

![ ](https://media.giphy.com/media/cC9lrZ4Y0Xij0O22iL/giphy.gif)

## Bookmarklet(s)

#### Quick-Copy for theme ID.

Instead of navigating in and out of the shop page a few times to grab the current live theme + id for a tier 2 internal escalation, try this bookmarklet that copies the proper format in one go. **Drag the link into the bookmark bar to try it out.** 

[Copy Theme Name + ID](javascript:(function()%7Bvar themeID%3DShopify.theme.name%2B" ("%2BShopify.theme.id%2B")"%3Bvar el%3Ddocument.createElement(%27textarea%27)%3Bel.value%3DthemeID%3Bdocument.body.appendChild(el)%3Bel.select()%3Bdocument.execCommand(%27copy%27)%3Bdocument.body.removeChild(el)%3B%7D)())

#### Copy Shopify URL

If no one has added the proper url to your ticket yet and you don't want to go crawling through the source page this button will automatically copy it for you... i think. **Drag the link into the bookmark bar to try it out.**

[Copy Shopify URL](javascript:(function()%7Bvar shopName%3DShopify.shop%3Bvar el%3Ddocument.createElement(%27textarea%27)%3Bel.value%3DshopName%3Bdocument.body.appendChild(el)%3Bel.select()%3Bdocument.execCommand(%27copy%27)%3Bdocument.body.removeChild(el)%3B%7D)())

#### Clear Cart

Ok not everyone is going to need this one but I don't have the bold extension hub. If you need a button to press in order to clear the cart us this lovely bmrklt. **Drag the link into the bookmark bar to try it out.** 

[Clear Cart](javascript:(function()%7Bconst h %3D new XMLHttpRequest()%3Bvar u%3D'cart%2Fclear.js'%3Bh.open("POST"%2Cu)%3Bh.send()%3Bh.onreadystatechange%3D(e)%3D>%7Bconsole.log(h.responseText)%3Blocation.reload()%3B%7D%7D)())

#### Hide Events

If you are not a fan of the amount of space that previous responses take up and you would like your draft of the message at the top, you can toggle the display with this bookmarklet. **Drag the link into the bookmark bar to try it out.** 

[Hide Events](javascript:(function()%7Bvar%20ec%20%3D%20document.getElementsByClassName('event-container')%5B0%5D%3Bif%20(ec.style.display%20%3D%3D%20%22block%22)%20%7Bec.style.display%20%3D%20%22none%22%3B%7D%20else%20%7Bec.style.display%20%3D%20%22block%22%3B%7D%7D)())

## What am I running?

If you are curious what the javascript code looks like you can right click and edit the bookmarklet. You will find all of the javascript sitting inside of the URL text input box. 

If anyone has any ideas or questions feel free to slack me. 

