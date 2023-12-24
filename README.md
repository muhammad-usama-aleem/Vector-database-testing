# Vector Database Testing

Welcome to the Vector Database Testing project! This project focuses on evaluating and testing various vector databases, aiming to provide insights into their performance, scalability, and ease of use. The results of these tests will be shared along with code examples in Colab notebooks for the community to benefit from.

## Objective

The primary goal of this project is to assess the capabilities of different vector databases in handling large-scale vector data efficiently. We aim to explore aspects such as indexing methods, query performance, and overall suitability for various applications that involve vector data.

## Tested Vector Databases

1. **Faiss**
    - **Description:** Faiss, developed by Facebook AI Research, is a widely-used vector database renowned for its high-performance similarity search capabilities. It provides a range of indexing methods optimized for efficient retrieval of nearest neighbors, including IVF (Inverted File) and HNSW (Hierarchical Navigable Small World). Faiss also supports GPU acceleration, enabling fast computation on large-scale embeddings. One of Faiss' notable features is its support for multi-index search, which combines different indexing methods to improve search accuracy and speed. Additionally, Faiss offers a Python interface, making it easy to integrate with existing NLP pipelines and frameworks. With its focus on search performance and versatility, Faiss is a go-to choice for projects demanding fast and accurate similarity search over vast embedding collections.
    - **Scalability:** High
    - **Query Speed:** High
    - **Search Accuracy:** High
    - **Flexibility:** Medium
    - **Persistence:** No
    - **Storage Location:** Local/Cloud
    - **Test Status:** ✅ Completed with Image retrival
    - **Colab Notebook:** [GIve it a try](https://github.com/muhammad-usama-aleem/Vector-database-testing/blob/main/dinov2-image-retrieval.ipynb)

More Coming Soon.


## How to Contribute

If you would like to contribute to this project, feel free to:

- Suggest additional vector databases for testing.
- Provide insights, feedback, or improvements on the existing tests.
- Share your experiences or suggest best practices for working with vector databases.

## Getting Started

To get started with the Vector Database Testing project, follow these steps:

1. Clone the repository:

```bash
https://github.com/muhammad-usama-aleem/Vector-database-testing.git
```

2. Navigate to the project directory:

```bash
cd vector-database-testing
```

3. Explore the `notebooks` directory:

- Choose the vector database you want to test.
- Open the corresponding Colab notebook.
- Execute the cells in the notebook to run the tests.


Happy Learning
