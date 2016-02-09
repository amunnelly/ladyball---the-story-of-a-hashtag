# &#35;ladyball - The Story of a Hashtag
Presentation on using Python's Tweepy module to analyse tweet data

Delivered to [Python Ireland on February 10th, 2015](http://www.meetup.com/pythonireland/events/226191290/)

##### Precis
Lidl Ireland and the Ladies' Gaelic Football Association decided to do some guerrilla marketing to announce Lidl's sponsorship of the sport of ladies' Gaelic football. It got people talking, but a lot of people just didn't think it was funny.
I thought it would be interesting to mine Twitter data that featured the `#ladyball` hashtag and see what we can conclude from it. I used Python's `Tweepy` module to work with the data, and an `ipython notebook` to put some sort of shape to it.
The presentation is in four parts, viz:

1. Intro to Tweepy
2. Using Tweepy to mine tweet data
3. Cleaning up that data for analysis
4. Searching for patterns in the data

All with a view to answering the question: is there really no such thing as bad publicity?

##### Downloading the Material
There is a .pdf presentation but the material is presented in its best light as an `ipython` slideshow. To create the slideshow,

1. Download the [Anaconda Python Distribution](https://www.continuum.io/downloads) if you don't have it already.
2. Download the zipped file
3. Unzip the file
4. Open a terminal / command line window at the unzipped file's location
5. At the prompt, run `ipython nbconvert plotting_with_matplotlib.ipynb --to slides --post serve` to view the presentation.
