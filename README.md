# trans.blahaj.community

trans@blahaj is a growing resource hub dedicated to supporting the trans@lemmy.blahaj.zone community. Here, you'll find guides and resources tailored to assist with various stages of transition, along with a developing local community directory to help connect locally and support one another.

This site is a collaborative, evolving project, and we value contributions that help expand and enhance our offerings. If you have ideas, resources, or other information to share, please consider contributing.

## Contributing
To directly contribute to this site you must have a GitHub account. We accept contributions in the form of [issues](https://github.com/trans-blahaj-lemmy/trans-blahaj-lemmy.github.io/issues/new) or, preferably, pull requests. To make a pull request, you must first [fork this project](https://github.com/trans-blahaj-lemmy/trans-blahaj-lemmy.github.io/fork), which means you create a copy of the project on your own account. Make any changes there, then click the button labeled "Contribute" on the main page. Write a title and summary and then click "Create pull request".

### Writing content

Content authored on this project uses [Markdown](https://www.markdownguide.org/). Our project adds some extra layers on top of this, but this is not necessary to know to write content. 

If you're creating a new page, including the following text above any content you write will properly add it to the site and give it a title and table of contents:
```md
---
title: <title>
layout: page
parent: <optional, online include this line if your page is the child of a category. If you include this, use the title of the category>
nav_order: <This field sets the position of the page in the navigation menu. some categories do not have a nav_order, do not use this field if that is the case.>
---
{% include page_header.md %}
```

For more advanced changes and components, look at the [documentation for the theme we use](https://just-the-docs.com/).