# recommendation-system
A Two-Tower Recommendation Model

## Result
+ Number of customers predicted by the model as “will purchase”: 1,714
+ Number of correct “will purchase” predictions (True Positives): 112

## Analysis of Actual Promotion Cost vs. Effectiveness
Suppose a company have 100,000 existing users and select 1,714 of them for targeted recommendations or email promotions:
For every 100 users recommended, about 6–7 will make a purchase (precision).


## Highlights
+ Two-Tower Retrieval Recommendation Model: Built a recall system incorporating user/item embeddings, enriched with contextual information such as time, location, and company.
+ New Product Cold-Start Prediction Task: Modeled purchase likelihood for unseen products by reusing user embeddings in combination with an MLP and Focal Loss.
+ Data Engineering & Sample Construction: Generated positive/negative samples from historical user behaviors, addressed class imbalance, and evaluated model performance using metrics such as HitRate@K, Precision, and Recall.
+ Comparative Analysis with Multiple Models: Evaluated and compared models including Logistic Regression, MLP, and PyTorch-based implementations, clearly demonstrating the cold-start challenges and the impact of model choice on results.
+ High Extensibility: The project can be further extended to support ranking models, item-to-item recall, and advanced features such as multimodal inputs (product text/images).
