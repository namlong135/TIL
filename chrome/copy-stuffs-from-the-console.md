# Copy Some Data From The Console

Sometimes when you tried to console.log something and wanted to share those. There
are a couple hacky ways of doing this, but Chrome supports a really smooth
way.

Use the `copy` function.

```javascript
characters
> (8) [{…}, {…}, {…}, {…}, {…}, {…}, {…}, {…}]
copy(characters[1])
```

My system copy buffer now contains the entire object that makes up the
second entry in that list. I can then paste it into Slack or wherever.

[source](https://twitter.com/addyosmani/status/1092686766375616517)