## Tools for the workplace

I've been working on a single tool (more to come) that I would like to share with others. Github is a pretty easy (and free) space for me to share and manage these, so you will be able to find any bookmarklets that make the job easier here.

## What is a bookmarklet?

It's just a few lines of javascript that you can run from the bookmark bar. These should allow us to access information that is stored on any website, you just have to click the bookmarklet to run it.

## How do I add a bookmarklet to my browser?

Visit this site then click and drag any of the bookmarklet links into your bookmark bar.

![ ](https://giphy.com/gifs/cC9lrZ4Y0Xij0O22iL.gif)

## Bookmarklet(s)

#### Quick-Copy for theme ID.

[Copy Theme Name + ID](javascript:(function()%7Bvar themeID%3DShopify.theme.name%2B" ("%2BShopify.theme.id%2B")"%3Bvar el%3Ddocument.createElement(%27textarea%27)%3Bel.value%3DthemeID%3Bdocument.body.appendChild(el)%3Bel.select()%3Bdocument.execCommand(%27copy%27)%3Bdocument.body.removeChild(el)%3B%7D)())

#### Copy Shopify URL

[Copy Shopify URL](javascript:(function()%7Bvar shopName%3DShopify.shop%3Bvar el%3Ddocument.createElement(%27textarea%27)%3Bel.value%3DshopName%3Bdocument.body.appendChild(el)%3Bel.select()%3Bdocument.execCommand(%27copy%27)%3Bdocument.body.removeChild(el)%3B%7D)())




## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/JordanDysart/work-tools/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/JordanDysart/work-tools/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

This is the end of this page.
