# WordCloud-Based Spanish Autonomies Map 🗺️

**Programming Language: Python**

Tools Used: *TfidfVectorizer, WikipediaAPI, Spacy, WordCloud, Pandas, Matplotlib, Seaborn, Geopandas, Numpy, Requests, BeautifulSoup, PIL*

## Project Objective 🎯

My growing interest in NLP led me to undertake this project, inspired by the ["Most Recurring Word on Each Country’s Wikipedia Page"](https://brilliantmaps.com/recurring-wikipedia/) map from the book Brilliant Maps. 

In this project, I aimed to create a map of Spain with word clouds representing each autonomous community. These word clouds highlight frequently occurring words from Wikipedia articles about each autonomy and can help with highlighting the main differences in culture, societal characteristics and key focuses of each spanish autonomy, 

## Project Methodology 📈🧪

### Wikipedia Scrapping 🌐🔗

I obtained links to Wikipedia articles for Spanish autonomies. These links were carefully collected from an official Wikipedia source containing essential information about all Spanish autonomous communities.

### Autonomy Articles Corpus 📚🧹

I used the Wikipedia API and my link list to collect textual content from autonomy articles. Extensive preprocessing was performed, including:

- Removing common Spanish stop words.
- Lemmatization for vocabulary standardization.

This resulted in a comprehensive corpus for future NLP analyses.

### Word Weighting Analysis 📊🧮

To spotlight unique words within each autonomy, I applied Tf-Idf vectorization to the article set. I created a dictionary associating words with scaled Tf-Idf values for word cloud generation.

### Autonomy-Shaped Word Clouds ☁️🗺️

I acquired geospatial data for Spain and its regions to create masks matching autonomy shapes. These masks were used to generate word clouds shaped like Spanish autonomies.

### Integration into Spain Map 🌍🌐

All autonomies were integrated into a unified map using geometry parameters and geographical borders. The maps display word clouds for the Spanish Peninsula, the Balearic Islands, Ceuta, Melilla, and the Canary Islands.

## Additional Content in the Folder 📂🌐

In addition to the Jupyter notebook with the written code, this folder contains essential project components: 

**Autonomy Shapes and Word Clouds**

- CCAA_pngs Subfolder: Contains the generated autonomy shapes, which serve as masks for word cloud creation.

- CCAA_pngs_wc Subfolder: Holds the autonomy-shaped word clouds, representing each autonomy's unique word distribution.

**Geospatial Data**

- canarias and peninbal Folders: These folders store geographical information for Spanish territories, crucial for mapping and shaping autonomies.

**Text Preprocessing Material**

- es_core_news_sm-3.6.0-py3-none-any(1).whl: Required material for spaCy to perform text preprocessing in Spanish.

**Final Maps**

- final_maps Folder: Here, you'll find the high-quality exports of the maps, displaying the autonomy word clouds integrated into the Spanish landscape.

**These additional resources were fundamental in crafting the WordCloud-Based Spanish Autonomies Map.** 🗺️👩‍💻

#

For detailed code and analysis, check the Jupyter notebooks in this folder. 📁👩‍💻