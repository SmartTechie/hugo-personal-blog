---
title: "Collaborative Plotting With R"
date: 2017-09-19T16:56:18+05:00
draft: false
---

The Plotly R graphing library  allows you to create and share interactive, publication-quality plots in your browser. Plotly is also built for working together, and makes it easy to post graphs and data publicly with a URL or privately to collaborators.

In this post, we will demo Plotly, make three graphs, and explain sharing. As we are quite new and still in our beta, your help, feedback, and suggestions go a long way and are appreciated. We are especially grateful for Tal's help and the chance to post.

#### Installing Plotly

From within the R console:

```
install.packages("devtools")
library("devtools")
```

Next, install plotly (a big thanks to Hadley, who suggested the GitHub route):

```
devtools::install_github("plotly/R-api")
# ...
# * DONE (plotly)
```

Then sign-up like this or at https://plot.ly/:

```
>library(plotly)
>response = signup (username = 'username', email= 'youremail')
...
Thanks for signing up to plotly! 
 
Your username is: MattSundquist
 
Your temporary password is: pw. You use this to log into your plotly account at https://plot.ly/plot. Your API key is: "API_Key". You use this to access your plotly account through the API.
 
To get started, initialize a plotly object with your username and api_key, e.g. 
>>> p <- plotly(username="MattSundquist", key="API_Key")
Then, make a graph!
>>> res <- p$plotly(c(1,2,3), c(4,2,1))
```

And we're up and running! You can change and access your password and key in your homepage.