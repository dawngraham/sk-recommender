# Stay Kind! Collaborative Recommender System
> Author: [Dawn Graham](https://dawngraham.github.io/)

Purchase-based collaborative recommender system for Stay Kind! distro.

## Data Dictionary

### `items.csv`
This contains all items available in the Stay Kind! catalog.

| Name | Description |  
| --- | --- |  
| SKU | Unique identification code for item. |
| Item | Item title. |

### `purchased.csv`
Each row matches a single item with a person who has purchased it.

| Name | Description |  
| --- | --- |  
| SKU | Unique identification code for item. |
| Item | Item title. |
| Customer | Unique identification number for each customer. |


## Notebooks
The data cleaning and preprocessing notebook is not being shared out of respect for privacy.

The [Recommender notebook](/notebooks/01_sk_recommender.ipynb) walks through all the steps needed to build this purchase-based recommender.