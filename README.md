# Matching and finding the most similar items

*Matching* is one of the basic machine learning tasks found in information retrieval, computer vision, recommender systems, etc.

## Project tasks

🔸 Develop an algorithm that for all items from given `validation` dataset will suggest several options of the most similar products from `base`;

🔸 Evaluate the performance using Accuracy@5 metric.

## Results

Overall, a search for the nearest 5 items on `base` for items from the `validation` dataset using `Annoy Index` showed an accuracy@5 metric of $71$%. 

To check the results, you may see `val_5_targets.csv` in the `results` directory. This dataset contains the following features: id for the validation query (`id`), 5 nearest neighbours obtained for each query (`target_0`-`target_4`), and the expected most similar result for a query (`expected`) derived from the given `validation_answers`. 
