## Fit-Finder

A Deep Learning Project that aims to recommend size (dimension) of a dress or product that a user is going to purchase on the basis of the size provided by the company and customer feedback.


### Table of Contents
1. [ About. ](#about)
2. [ Data. ](#data)
3. [ Dependencies. ](#dependencies)
4. [ Additional Information. ](#info)


<a name="about"></a>
### About
Personalized size and fit recommendations bear crucial significance for any fashion e-commerce platform.To avoid the busness loss due to unsatisfactory article returns, Collaborative models (which look at the previous orders, or similar orders) are not the best recommenders. What if, we could embedd customer features (their reviews and expectations) and the article features into a latent space and then give personalized recommendation? 
(Customer features can contain the preferences of what type of fitting the customers like, and Product's feature can capture properties, like article type, style or size.)

SFNET is a deep learning based architecture (by Zalando Research, Shopify and OLX) which combines collaborative and content-based modeling techniques to learn input and latent representations of customers
and articles for size and fit prediction. For details please refer to [this](https://arxiv.org/pdf/1907.09844.pdf) article.


<a name="Dependencies"></a>
### Dependencies
Download the dependencies from requirement.txt.
```
pip install requirement.txt
```

<a name="data"></a>
### Data 
Modcloth dataset is used to build this recommender system. The dataset contains 47,958 customer data, 1,378 products and 82,790 transactions.
Data can be found from [kaggle](https://www.kaggle.com/rmisra/clothing-fit-dataset-for-size-recommendation)

<a name="info"></a>
### Additional Information
In case of error, feel free to contact us over Linkedin at [Adnan](https://www.linkedin.com/in/adnan-karol-aa1666179/) and [Niloy](https://www.linkedin.com/in/niloy-chakraborty/).
)
