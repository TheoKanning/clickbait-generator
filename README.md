# Clickbait Generator
This word-level LSTM model generates clickbait headlines like the following:
- we know your zodiac sign based on your zodiac sign
- the 17 most important canadian celebrity moments of 2015
- here's how to make a vampire
- can you guess your favorite '90s movie based on your favorite kitten
- are you more a canadian or taylor swift or oprah

## Running
`pipenv shell`  
`jupyter notebook clickbait.ipynb`

## Data
This model uses the collection of 17,000 clickbait headlines scraped from the following esteemed publications:  
- BuzzFeed
- Upworthy
- ViralNova
- Thatscoop
- Scoopwhoop
- ViralStories

Taken from the paper "Stop Clickbait: Detecting and Preventing Clickbaits in Online News Media"  
[Data Source](https://github.com/bhargaviparanjape/clickbait)

## Model
### Word Embeddings
This model trains its own 10-dimensional embeddings.

### Architecture
The model's current architecture is a two-layer LSTM with 256 units and a 20% dropout rate.

## Further Work
- Get more data
- Replace all this with a transformer


## Sources

Inspired by Lars Eidnes' [blog post](https://larseidnes.com/2015/10/13/auto-generating-clickbait-with-recurrent-neural-networks/)  
"Stop Clickbait: Detecting and Preventing Clickbaits in Online News Media" [link](https://github.com/bhargaviparanjape/clickbait)  
Excellent RNN intro by Andrej Karpathy [link](http://karpathy.github.io/2015/05/21/rnn-effectiveness/)
