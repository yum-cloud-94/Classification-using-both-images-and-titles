# Classification model using both images and text data.

: For classifying categories which video's are actually in, used both 'thumbnail images' and 'video text names'

- Dataset : crawling youtube data (thumbnail url/video names) / 7 categories / 12,000
- ① Generate classification model with only texts + Extract text features for the last model
- ② Generate classification model with only images + Extract image features for the last model
- ③ Generage classification model using both texts features and images features
- Compare ③ model's improvement to ①② models
