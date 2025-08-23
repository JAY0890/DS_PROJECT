#  Fake News Detection

**Project Type**: Exploratory Data Analysis (EDA)  
**Contribution**: Individual  
**Name**: Gorasiya Jay

---

## Project Summary

In an age where misinformation spreads rapidly online, detecting fake news has become increasingly important.  
This project aims to explore and analyze news article data to understand patterns and differences between **fake** and **real** news.

The project focuses on using **basic features** such as title length, text length, presence of images, author information, and other metadata — without applying complex Natural Language Processing (NLP) or deep learning techniques. This makes it an ideal **beginner-level** project to learn the fundamentals of **Exploratory Data Analysis (EDA)** and gain insights using simple tools and visualizations.

---

##  About the Dataset

The dataset contains **2,083 news articles**, each with metadata and labels indicating whether the news is real or fake.

| Feature Name    | Description |
|----------------|-------------|
| `author`        | Name of the article's author |
| `published`     | Date and time when the article was published (datetime format) |
| `title`         | Title of the news article |
| `text`          | Full text/content of the news article |
| `language`      | Language of the article (e.g., English) |
| `site_url`      | Source website URL |
| `main_img_url`  | URL of the main image used in the article |
| `type`          | Type/category of the news (e.g., news, opinion, satire) |
| `label`         | **Target variable**: `True` for fake news, `False` for real news |
| `hasImage`      | Whether the article has an image (`1` for yes, `0` for no) |
| `pub_date`      | Publication date in string format |
| `title_len`     | Length of the title (number of characters) |
| `text_len`      | Length of the article content (number of characters) |

---

##  Problem Statements

1. Detect fake news from articles using basic features such as article text, category (`type`), language, and the presence of images.  
2. Analyze patterns in news characteristics, including title length, text length, article type, language, and whether an image is included, to understand differences between real and fake news.  
3. Explore relationships between different features to identify possible indicators or common traits associated with fake news articles.  
4. Identify which features (e.g., article length, presence of images, type of news) are most commonly found in fake news articles.  
5. Compare publishing behavior (such as publishing time, day, or frequency) between fake and real news articles.

---

