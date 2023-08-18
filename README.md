# auto-mpg
Project of uni
Use PCA and t-SNE for dimention reduction

What is t-SNE?
t-SNE is a dimensionality reduction technique that is commonly used for visualizing high-dimensional data in a lower-dimensional space . It is particularly useful for revealing patterns and structures in complex datasets that may be difficult to perceive using other techniques.

How does t-SNE work?
t-SNE works by constructing a probability distribution over pairs of high-dimensional data points and a similar probability distribution over pairs of their corresponding points in the low-dimensional space. It then minimizes the divergence between these two distributions using gradient descent, resulting in a low-dimensional representation of the data that preserves the local structure and relationships between data points.

Why is t-SNE useful?
t-SNE is a powerful visualization tool because it can effectively capture and represent complex relationships and structures in the data. It can reveal clusters, patterns, and outliers in the data, making it particularly useful for exploratory data analysis and data visualization tasks. t-SNE is commonly used in various domains, such as genomics, image analysis, natural language processing, and more.

Key considerations when using t-SNE:

Perplexity: Perplexity is a hyperparameter in t-SNE that controls the balance between preserving local structure and global structure in the low-dimensional representation. It is important to choose an appropriate perplexity value based on the characteristics of the dataset.
Randomness: t-SNE results can vary between different runs due to its random initialization and optimization process. It is recommended to perform multiple runs and consider the consensus of the results.
Interpretation: While t-SNE is excellent for visualization, it is not suitable for making quantitative comparisons between different points or distances in the low-dimensional space. It is primarily used for exploratory purposes and should be complemented with other analysis techniques.