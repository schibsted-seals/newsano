# How to contribute?
We are always open for contribution. Read our step by step guide and publish your first article on Newsano!
As organization we follow GitFlow approach so please stick with that.

## Adding new article
Just create new file in `app/public/article` directory with `index.html` file and main image `[pick_your_name].jpg`.
`index.html` should containe pseudo HTML for article as follows:

```
<title>
  [title of article]
</title>
<content>
  [content of article - yes, you can use HTML]
</content>
<content-source>
  [you quoted someone from internet, didn't you? tell the source here]
</content-source>
<main-image>
  [hi-res stock main image]
</main-image>
<main-image-source>
  [similar as with content: put image's author there]
</main-image-source>
```

You can always take a look on [real life example](https://github.com/schibsted-seals/newsano/blob/master/app/public/articles/lillehammer/index.html).

When your pull request be accepted, you will see your work on our [QA environment](http://newsano-dev.seals.schibsted.pl/). Best one will be visible on [production site](http://newsano-prod.seals.schibsted.pl/).
