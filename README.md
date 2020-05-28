# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 3: Sharing Dataset on Kaggle

# Scraping Sephora website with Beautifulsoup


<img src="https://i.insider.com/5838406765edfed40a8b49b1?width=2500&format=jpeg&auto=webp" style="height: 400px; width: 1000px">


Name: Raghad Alharbi

---

### Description

We have been using various datasets in the course that are either model/toy datasets or collected in conditions fairly remote to local relevance. With the newfound API and webscraping skills that you learned, this project challenges you to create a dataset revolving around a topic, problem, or theme of your choice, clean it, properly document it, and submit it to the Kaggle dataset repository. Curating and sharing a dataset is an integral part of your skills and practice as a data scientist that should not be overlooked!

For project 3, your goal is three-fold:

1. Define a domain, issue, and problem that you are interested in (preferably with local/regional relevance).
2. Collect, clean, and submit the data the Kaggle datasets repository under the course's organization.
3. Submit the data collection and a starter kernel in public associated to the published dataset.


#### Readings

To help you get started, please read [this blog post](http://blog.kaggle.com/2016/10/21/a-guide-to-open-data-publishing-analytics/) by Kaggle.

For some good examples, tutorials, and steps to publish your dataset, read [this page](https://www.kaggle.com/about/datasets-awards/datasets)

For inspiration on how a company successfully published a dataset on Kaggle read [this story](https://towardsdatascience.com/how-we-published-a-successful-dataset-on-kaggle-2945de537597).

More information and documentation on the Kaggle datasets platform see [this page](https://www.kaggle.com/docs/datasets)

---

### Requirements

- Gather and prepare your data using API or webscraping. A ready-made dataset is *NOT* allowed.
- Make your data accessible and readable by using common open file formats like CSV.
- Take the time to describe your dataset thoroughly.
- Pick a clear, open license ensuring your dataset is reusable.
- Minimum records or rows should be 1000 after cleaning your data.
- Publish a kernel on your dataset to help others learn how they can work with the data. The kernel should show features of the dataset with a plot or two to showcase some variables in the dataset. Also raise potentially interesting questions that could be answered using this dataset.
- Put your data collection and cleaning scripts in a repo.

---

### Submission
- Due date:  Thursday 16th April 2020

- The link to the dataset (and the associated starter kernel) on Kaggle add it your Note Book and Of course submit your code using pull command.

- Link to dataset: https://www.kaggle.com/raghadalharbi/all-products-available-on-sephora-website
- Link to starter kernel: https://www.kaggle.com/raghadalharbi/sephora-starter-code
- Second starter kernel: https://www.kaggle.com/kerneler/starter-sephora-website-779abf66-7

### Context
This dataset is the result of my third project in Data Science Immersive Course with General Assembly and Misk academy. The project was about using web scraping methods like selenium and beautiful soup to collect more than 1,000 useful records from any website of our choice. I chose this Sephora website because we need to think about beauty even if we were to busy thinking about COVID-19.  

### Content
| Feature | Type | Description |
| --- | --- | --- |
| id  |  int | The product ID at Sephora's website|
| brand  |  object | The brand of the product at Sephora's website|
| category|  Object | The category of the product at Sephora's website|
| name |  Object | The name of the product at Sephora's website|
| size |  Object | The size of the product |
| rating |  float | The rating of the product |
| number_of_reviews|  int | The number of reviews of the product |
| love |  int | The number of people loving the product |
| price |  float | The price of the product |
| value_price |  float | The value price of the product (for discounted products|
| URL |  object | The URL link of the product |
| MarketingFlags |  bool | The Marketing Flags of the product from the website if they were exclusive or sold online only|
| MarketingFlags_content |  object | The kinds of Marketing Flags of the product |
| options |  object | The options available on the website for the product like colors and sizes |
| details |  object | The details of the product available on the website|
| how_to_use |  object | The instructions of the product if available  |
| ingredients|  object | The ingredients of the product if available|
| online_only | int |If the product is sold online only|
| exclusive |  int | If the product is sold exclusively on Sephora's website|
| limited_edition|  int | If the product is limited edition|
| limited_time_offer|  int | If the product has a limited time offer|

### Acknowledgements
I would like to thank my laptop for its strength and patience, my friends for supporting me, and myself for continuing to work even if I do not feel like it. Also, I would like to thank my instructors for keeping up with my complaints and pushing me to work harder.  

### Inspiration
It would be a cool idea to see the effect of some ingredients on the number of loves or ratings a product would get. Also, to see the effects of the brand name on the ratings despite the quality of ingredients list. 

