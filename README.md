# Book Recommendation System

## Abstract
In today’s digital world, there is a lack of standardized book recommendation systems similar to those for movies, products, or music. This project aims to address this gap by developing a book recommendation system based on the genre, author, and ratings of books. The system utilizes the goodreadsbooks dataset from Kaggle, containing information about over 11,000 books, including titles, authors, ratings, and more. Various methods such as Unsupervised Nearest Neighbor, Cosine Similarity, and Content-based filtering are implemented to recommend books to users based on their preferences.

## Dataset
The project utilizes the goodreadsbooks dataset from Kaggle, which contains information about over 11,000 books. The dataset includes features such as book title, author, average rating, number of pages, ratings count, and more.

### Column Description
- **bookID:** Unique identifier for each book record.
- **title:** Title of each book.
- **authors:** Author/authors of each book.
- **average_rating:** Mean rating by users for each book.
- **isbn & isbn13:** International Standard Book Number for identifying additional information about books.
- **language_code:** Language in which the book is published.
- **num_pages:** Number of pages in the book.
- **ratings_count:** Total number of ratings given to the book.
- **text_reviews_count:** Total count of textual reviews given to the book.
- **publication_date:** Publishing date of the book.
- **publisher:** Name of the publisher.

## Methods
- **Unsupervised Nearest Neighbor:** Implemented nearest neighbors learning without supervision to recommend books to users based on similarity.
- **K-D Tree:** Utilized K-D trees for spatial point division to find nearest neighbors efficiently.
- **Cosine Similarity:** Calculated cosine similarity to measure similarity between books based on their attributes.
- **Content-based Filtering:** Developed a recommendation system based on the description or features of books.

## Discussion
### Data Preprocessing
- Conducted data cleaning to handle missing data, duplicates, and noisy data.
- Transformed data by standardizing author names and reducing unnecessary features.
- Explored data through exploratory data analysis to understand distribution and trends.

### Exploratory Data Analysis
- Analyzed basic statistics, language distribution, ratings count, and popular authors/publishers.
- Visualized data through plots to identify patterns and insights.

## Model Building
- Cleaned and formatted data for model building.
- Utilized nearest neighbors algorithm and cosine similarity for book recommendations.
- Built recommendation system based on genre, author, and ratings.

## Key Results
### Recommendation System
- Provided recommendations using nearest neighbors algorithm and cosine similarity.
- Outputted similar genre books and books containing keywords from the input.

## Conclusion
The book recommendation system developed in this project offers personalized recommendations to users based on their preferences and reading habits. By leveraging various algorithms and data preprocessing techniques, the system aims to enhance the user experience and promote exploration of diverse literature.

## References
1. [goodreadsbooks Dataset](https://www.kaggle.com/datasets/jealousleopard/goodreadsbooks)
2. [Scikit-Learn Nearest Neighbors](https://scikit-learn.org/stable/modules/neighbors.html#unsupervised-neighbors)
3. [Scikit-Learn Neighbors Documentation](https://scikit-learn.org/stable/modules/neighbors.html)
4. [Content-Based Filtering](https://www.upwork.com/resources/what-is-content-based-filtering)
5. [Cosine Similarity](https://www.hindawi.com/journals/wcmc/2021/7036357/)
6. [MinMaxScaler](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.MinMaxScaler.html)
7. [Tree Algorithms Explained](https://towardsdatascience.com/tree-algorithms-explained-ball-tree-algorithm-vs-kd-tree-vs-brute-force-9746debcd940)

