![](https://media0.giphy.com/media/xT9IgG50Fb7Mi0prBC/giphy.gif)


This is the first blog post from the GitHub CMS. 🚀

What? GitHub CMS 🤔
<br/>
(_Actually, there's no such thing. But we use GitHub as a data source._)

### How?

We use the GitHub API to fetch this file inside a Next.js app. But we cannot use the API directly because GitHub has a strict rate limit.
So, we use some static optimizations that come with Next.js to get around with that.

### Batteries Included

This project not only load blog posts from GitHub, but it has some other cool features as well:

* Store comments inside GitHub
* Login with GitHub to add comments
* Live production reload as you change the content in GitHub
* Built-in preview mode all the changes you made with Pull Requests
* You can use a private or public repository as the data source
* Optimistic UI support
