# Airbnb_price_category_prediction
One of the biggest problems when people prepare to post a new listing on Airbnb is, how much should one ask for? Of course, the most intuitive way is to check how other similar postings price their apartment/house. So in this project, we are going to predict the listing price based on the listing characteristics, in this way to optimize the user experience and lower the bar to be a new host!

Predicting the actual price could be simple, so we cut the pricing into 3 different bins for classification. For each listing, we recommend a pricing range to the new host rather than a fixed price (how nice is that!). So we define 3 categories: beginner, plus, premium based on the created listing. Respectively we use 0, 1, 2 to denote these 3 categories.
## steps:
1. loading data:
   - import required libraries.
   - load train and test data.
     
2. preprocessing the data:
   - translate text data. (summary feature).
   - remove null and duplicated values from the summary feature in the training dataset.
   - translate summary feature (because it's multilingual data).
   - resize images into (64643) shape (to preserve more features as we could).
   - tokenize each text data in the summary feature.
   - convert each text into a unique id sequence.
   - solve the imbalance problem.
   - preprocessing the data to build a pre-trained model.
   - translate text data. (summary feature).
   - remove null and duplicated values from the summary feature in the training dataset.
   - translate summary feature (because it's multilingual data).
   - tokenize each text data in the summary feature with a pre-trained tokenizer.
   - convert each text into a unique id sequence.

3. build models and plot them:
    - train each model.
    - plot each model on training loss and validation loss.
    - plot each model on training accuracy and validation accuracy.
  
      
- Data from: https://www.kaggle.com/competitions/copy-of-cisc-873-dm-w23-a4/data?select=a4

  
