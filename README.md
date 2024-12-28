# TheOffice
The Office NLP Analysis

import pandas as pd
import numpy as np 
import scipy as sc
import plotly 
import matplotlib.pyplot as plt
from wordcloud import WordCloud, STOPWORDS
from collections import Counter
import seaborn as sns

from nltk.sentiment import SentimentIntensityAnalyzer
import nltk

# Download NLTK resources
nltk.download('vader_lexicon')

from PIL import Image
from wordcloud import WordCloud, STOPWORDS, ImageColorGenerator
