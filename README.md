## Optimizing with ngrok and PageSpeed Insights

  I was able to create a local host using ngrok to have my project go live and utilize PageSpeed Insights. Upon using PageSpeed I saw that the whole project needed the images compressed and they were the main causes for slowing down the response time for my mobile portion of the project. I also utilized the **async"** function to skip through unnecessary DOM calls.

## Pizza portion

  for this part of the project I had to work a lot more with JavaScript in order to get the page to be 60fps or higher. I was able to do this by removing querySelectors and replaced them with variables that could do the same job just a bit faster.
