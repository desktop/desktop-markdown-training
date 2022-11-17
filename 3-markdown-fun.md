
- [Markdown resources](#markdown-resources)
- [Markdown links](#markdown-links)
- [Markdown headers](#markdown-headers)
- [Markdown Images](#markdown-images)
- [Commit your Octocat](#commit-your-octocat)
 ⬅️ [**Back to Contribute**](2-contribute.md)

## Markdown resources

- [Quickstart guide to writing on GitHub](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/quickstart-for-writing-on-github)
- [Basic writing and formatting syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- [Markdown Guide](https://www.markdownguide.org/getting-started/)
- [Markdown All In One documentation](https://markdown-all-in-one.github.io/docs/guide/#features)

## Markdown links

Let's link your GitHub handle in the header of your markdown file.

Go to your github profile. The url will look something like `https://github.com/yourgithubhandle`. For example, mine is `https://github.com/rmw`

- Go to your github profile and copy the url
- In your markdown file, select your github handle
- Pressing `command` + `v` to paste the url on to the text to create a link

Once done, this will look like

```
# [@rmw](https://github.com/rmw)'s contributions!
```

## Markdown headers

In the [last section](2-contribute.md), we created a markdown file and added a [header](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#headings).

How, you ask? 

We added `#` in front of text.

The more `#` we add in a row, the smaller the header size. So `##` is smaller than `#`.

Let's add a secondary header to our markdown file. Below your first title, type:

```
## My favorite Octocat
```

## Markdown Images

Who doesn't love Ocotcats? Let's find out favorite.

- Got to the [octodex](https://octodex.github.com/)
- Find your favorite Octocat
- Right-click on the image
- Select "Open image in new tab"
<br />![open octocat in new tab](images/octocat-open-new-tab.png)
- Copy the URL of the new tab that was opened
<br />![copy url of octocat](images/octocat-url.png)

Now below the header we just added, let's add an image. Replace the URL with the one you just copied.

```
## My favorite Octocat

![Cherryontop-o-cat is my favorite](https://octodex.github.com/images/cherryontop-o-cat.png)
```

## Commit your Octocat

- Go to GitHub Desktop
- Add a commit message, such as "Added my favorite Octocat"
- Click the `Commit` button
- Click `Push origin`
- Click `View on github`
- Once in the browser, click on `Pull requests`
- Find and click on your pull request
- Click on `Commits`
- See that your latest commit is in your pull request!


