# Extracting newspaper articles related to Gender Based Violence in Pakistan

### Folder Key:

- extracted_information.csv: CSV containing link, text and additional information that was extracted from links that were collected
- drf_data.csv: CSV containing link, text and additional information that was extracted from links DRF provided
- plot1_updated.png: Cities mentioned in extracted articles (includes drf data as well) at least once 
- map_labelled_manually.png: Mapped articles
- wordcloud.png: wordcloud based on extracted text from articles
- lda2.html: "Topics" being mentioned in extracted newspaper articles' text (this was created using Topic Modelling in Python). Results are visualized [here](https://rukhshanarifm.github.io/) -- this is created using Python's ```sklearn``` library.

## Methodology (to create extracted_information.csv):

- Shortlisted 2 newspapers (Dawn and The News)
- Searching keywords on each newspaper's website
- Going back 10 pages in search results
- Extracting each link from each page
- Once links are collected, extract newspaper information from each link. This includes variables such as: article text, article title, datetime (this is not available for The News). This information was also collected from links shared by DRF.







