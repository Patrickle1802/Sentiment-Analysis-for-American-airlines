# Sentiment-Analysis-for-American-airlines

The use of social network data, particularly from platforms like Twitter, has seen significant growth in recent years as organizations aim to leverage this information for political campaigns, product and service quality improvements, and sentiment analysis. This report outlines the findings and implications of a comprehensive analysis conducted by Social Analytics, a company specializing in data gathering and deriving insights from social channels. The business problem at hand is to analyze customer tweets about airlines in America to gain valuable insights for decision-making.

The analytics method applied for analyzing the tweets about American airlines encompasses several key approaches to gain meaningful insights into customer sentiments.

Sentiment Classification: Tweets are classified into positive, negative, and neutral classes based on the sentiments they convey. Sentiment classification is crucial as it allows us to understand the overall sentiment distribution and customer perceptions towards different airlines. This classification provides valuable information for decision-makers to identify areas of improvement and capitalize on positive feedback.

To perform sentiment classification effectively, a variety of machine learning classifiers, such as Logistics Regression and Support Vector Machine, are evaluated. The accuracy, precision, recall, and F1 score are selected as the performance metrics to evaluate the machine learning classifiers. Accuracy provides an overall measure of classifier performance, while precision and recall give insights into the classifier's ability to correctly classify positive and negative tweets. F1 score is a harmonic mean of precision and recall, providing a balanced assessment of classifier effectiveness. By considering multiple performance metrics, the analysis ensures a holistic evaluation of the classifiers' performance.

Feature Extraction Techniques: To enhance sentiment analysis, the impact of feature extraction techniques, specifically CountVectorizer, is investigated. CountVectorizer is chosen because it efficiently transforms text data into numerical vectors based on word frequencies. This process allows machine learning algorithms to process textual data effectively.

In addition to machine learning classifiers, a lexicon-based sentiment analysis approach using Latent Dirichlet Allocation (LDA) is applied. LDA is a widely used topic modeling technique that identifies underlying topics in a corpus of text documents. In this context, LDA is utilized to uncover latent positive and negative sentiments expressed by customers. Comparing the proportions of positive and negative sentiments provides insights into the overall sentiment polarity associated with different airlines.

Last but not least, data and chart visualization is an essential aspect of the analytics approach. Box plots, bar charts, and line charts generated using the Matplotlib library help interpret the data and highlight significant insights from the dataset. Visualizations make it easier for stakeholders to grasp trends, patterns, and distributions in the data, enabling better decision-making and actionable insights.

Together with several analytics approaches were employed, and the following major findings were highlighted:

Through data exploration, the airlines were ranked in terms of their popularity on Twitter (Question A). United emerged as the most popular, followed by US Airways, American, Southwest, Delta, and Virgin America. Furthermore, the analysis identified the most popular states for each airline's customers (Question B): New York is the most popular state for customers of both American and Delta airlines. Texas is the most popular state for Southwest, and Washington, D.C. is the most popular for US Airways. On the other hand, California is the most popular state for both United and Virgin America customers.
The report compared the performance of machine learning classifiers (Question C), specifically Logistics Regression and Support Vector Machine (SVM). The Logistics Regression model outperformed SVM, achieving an accuracy of 0.72 with Count Vectorizer feature extraction, while SVM achieved 0.71.
Lexicon-Based Sentiment Analysis, using Latent Dirichlet Allocation (LDA), sentiment analysis revealed that American Airlines and United Airlines received more positive sentiments from customers, while US Airways received more negative sentiments (Question D).
Topic modelling identified nine negative sentiment topics that customers frequently encountered when dealing with airlines (Question E). They are: Customer Services, Waiting and Customer Support, Ticket Booking Issues, Baggage and Luggage Problems, Gate Agents and Ground Services, Time and Phone Support, Flight Delays, Reservation Issues, and Experience of airport service problem. These topics can help airlines identify common pain points and improve services to enhance customer satisfaction. Based on the insights obtained from the analysis, several practical implications and strategies were suggested to enhance customer satisfaction, build brand loyalty, and gain a competitive edge in the market:
Customer Engagement Strategy: Develop a comprehensive plan to engage with customers on social media platforms, addressing their queries and concerns promptly.
Region-Specific Marketing: Tailor marketing campaigns and services based on the preferences and needs of customers in specific regions.
Predict Sentiments with Machine Learning for Proactive Support: Utilize machine learning algorithms to predict customer sentiments and offer proactive support before issues escalate.
Address Commonly Mentioned Issues to Improve Customer Satisfaction: Address the topics identified in the analysis that commonly lead to negative sentiments among customers.
Proactive Crisis Management: Implement strategies to handle potential crises swiftly and effectively, maintaining a positive brand image.
Employee Training and Recognition for Outstanding Customer Support: Invest in training employees to provide exceptional customer support, and recognize and reward outstanding performance.
Competitor Analysis for Differentiation: Conduct competitive analysis to identify areas where the airline can stand out from competitors.
In conclusion, the analysis conducted by Social Analytics provides valuable insights into customer sentiments about airlines on Twitter. By understanding these sentiments and implementing the suggested strategies, airlines can enhance customer satisfaction, strengthen brand loyalty, and gain a competitive advantage in the market.
