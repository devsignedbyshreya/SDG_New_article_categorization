<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
</head>
<body>

  <h1>SDG News Article Categorization</h1>

  <h2>Project Overview</h2>
  <p>
    This project focuses on categorizing news articles based on the 
    <strong>United Nations Sustainable Development Goals (SDGs)</strong> using traditional machine learning techniques. 
    The goal is twofold:
  </p>
  <ul>
    <li><strong>Article → SDG</strong>: Predict the most relevant SDG based on the content of a news article.</li>
    <li><strong>SDG → Articles</strong>: Retrieve all news articles related to a selected SDG.</li>
  </ul>
  <p>
    This dual functionality can help individuals, researchers, and organizations explore how different media narratives align with global development themes such as 
    <em>Climate Action (SDG 13)</em>, <em>Quality Education (SDG 4)</em>, or <em>Industry Innovation (SDG 9), etc</em>.
  </p>

  <h2>Project Motivation</h2>
  <p>
    With thousands of articles published daily, making sense of this information through the lens of sustainable development is increasingly valuable. 
    SDG-based categorization allows us to go beyond surface-level tags and view news content in the context of global goals.
  </p>
  <p>
    By training machine learning models on BBC news data and mapping the original categories 
  to relevant SDGs, this project builds a foundation for automated, goal-oriented content classification.
  </p>

  <h2>Dataset</h2>
  <ul>
    <li><strong>Source</strong>: <a href="https://www.kaggle.com/datasets/gpreda/bbc-news" target="_blank">BBC News Dataset</a></li>
    <li><strong>Articles</strong>: ~20,000 articles</li>
  </ul>
  <h2>Functionalities</h2>

  <h3>1. News Article → SDG</h3>
  <p>
    Given a raw news article, the model predicts the SDG it most aligns with using text classification.
  </p>
  <p><em>Example</em>:</p>
  <blockquote>
    “The government launched a new clean energy initiative to reduce carbon emissions...”<br>
    → <strong>Predicted SDG</strong>: 13 - Climate Action
  </blockquote>

  <h3>2. SDG → News Articles</h3>
  <p>
    Given an SDG goal (e.g., SDG 9), retrieve a list of articles from the dataset that are associated with that SDG based on mapping.</p>
