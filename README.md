# E-Bookstore Recommendation Engine Solution - Leadership & Consulting for Data Science Final Project

### Team Members

Yash Bhardwaj, Nathan Chen, Daichi Ishikawa, Siobhan McDermott and William DeForest

### Project Description

The primary objective of this project is to develop a book "Recommendation Engine" for our E-Bookstore client using an unsupervised segmentation/clustering approach. Our client is skeptical of the improvements a better recommendation system can bring, so our presentation must be clear and compelling. This project also gives us the chance to practice developing solutions to enterprise problems using modern machine learning models as well as delivering successful project presentations.

### Business Problem

- The E-commerce bookstore’s current recommendation system does not tailor recommendations to each customer’s specific purchasing habits which is limiting average transaction size.

### Solution

- By identifying and understanding the purchasing behavior of various user groups, your company can increase the average size of each transaction by providing more targeted recommendations.

### Data

- Customer purchase frequency, monetary value, and recency for each book genre.

### Methodology

- Recency-Frequency-Monetary Value (RFM) Segmentation. Suitable for this scenario because it is designed specifically for segmentation based on transactional behavior.
- Segment customers based on their standardized, composite RFM score
- Develop unique promotions tailored to each segment
- K-Nearest Neighbors (KNN) model to recommend a new book from a category preferred by similar (computed using cosine similarity) customers.
- Example: Our model identifies that people who bought sports category items also tend to buy items from the health category.
- Model financial impact of implementing the proposed recommendation engine
- Provide detailed project timeline

### Final Presentation Deck
- [Technical Presentation (for CTO)](./"Final Technical Presentation.pdf")
- [Non-technical Presentation (for CMO)](./"Final CMO Presentation.pdf")





