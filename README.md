## Welcome to JAMA Digest

You can use the [editor on GitHub](https://github.com/JavaMahileu/digest/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

## How to make a post

- Put new page under _posts/YYYY folder
  - you can use .md or .html format
  - filename should be in format: YEAR-MONTH-DAY-title (more info [here](https://jekyllrb.com/docs/posts/))
  - add standard [Front Matter](https://jekyllrb.com/docs/front-matter/) header to you page (even if it is an html page)
    - it should have layout: default item in order to use default template for post page.
    - other headers are optional
- If you want to include image:
  - place it in /assets/posts/YYYY folder
  - add link to it on your post page
  - prefix link with '{{site.baseurl}}' so that it is correctly resolved on published site. (More info about [templating](https://jekyllrb.com/docs/variables/))

### Markdown basics

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

Another tutorial on [Basic writing and formatting syntax](https://help.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax)

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/JavaMahileu/digest/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.  


