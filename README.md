googleCite
==========

googleCite is a function for creating a wordcloud of your google scholar citations page. See [here](http://simplystatistics.tumblr.com/post/13203811645/an-r-function-to-analyze-your-google-scholar-citations) 
for a longer description. The basic use is: 


```S
source("")

```

Go to a google scholar citation page, this is [Rafa's](http://scholar.google.com/citations?user=nFW-2Q8AAAAJ&hl=en)

Call googleCite like this:

```S
out = googleCite(“http://scholar.google.com/citations?user=nFW-2Q8AAAAJ&hl=en”,pdfname=”rafa_wordcloud.pdf”) 
```
