# Patient’s Condition Classification Using Drug Reviews

![alt text](https://www.kaggleusercontent.com/kf/93742561/eyJhbGciOiJkaXIiLCJlbmMiOiJBMTI4Q0JDLUhTMjU2In0..p52Fxy2wlJbO456Tg6o7bA.Dmp2yIlmHxAu-L_cYgeWkLCuxwJv6xE8mMUQXdjVNIr0jSNasMnnf39VIE0H_7HfLr4-coYtmUg4GiXzlb8d_oEMyaWWd3IdNudVt-Maq5DBUcREsbdvsyaGydplSgww6Y1bKe6Yge3DdsvdtgLFoq5p19f7-ZTPFJk-HemBtIt_nOtZTShU7P2_TNFznGQfO5zp9Jl6TkY4MA6oaaheso3zxJ3f0RWKyTKOVBiOE044sqHhiGwKV7wDQCezadB-SIMakY1c3rkhbX3tNhcLj1h9V85irfSAfZRnsgi8sPCEgJbM7-PWJ9xJrARGEg6n-EIhvDt0ORn5bNdAv7_TvWxc0lVeXVtrmwLIOYmdNYs_fQCmKOO68zmwd-Gfsyiw4BSz5WYMnNuSWvjU6vdS3uLQkg_t1tZC8CEUThhIURKzm_QVCdyDKtpdpViWs4FXcpcowl6ms4kmHDt60QOGD7at4JzNZchq3TjkY8zDI5qy_8o1ZUhDR4D5esbm8Lvg248okSaFWUpD7NlxvWiQh9bgVlOXzVTzOrpQ2er49EBg9JFX9eKWY-aC0qaaDugV4butNxGxdAGzrfYuF26J8fDwviG5T4GKDbs-bhIvqbDNQbGf-9zbT4hhEBbs5t6gEB3fbBSOBmSZQqriqDGtLRPomZswaLv3050IGy9NsD0O_i2F51swEP2YedqWioB3.wb4NJ9LzZ7OFv9wOOIU0nA/__results___files/__results___15_1.png)

## Table of Contents:
### 1. Description
### 2. Dataset
### 3. EDA - Exploratory data analysis
### 4. Data Preprocessing
### 4. Model
### 5. Evaluation

### 1. Description
We build a system that can identify patient's condition by the help of both `Natural Language Processing(NLP)` and `Machine Learning(ML)` in classifying patient to reduce the efforts and time expanded by the doctors and evaluate the type of patient at an early stage.

### 2. Dataset
The datset is collected from [UCI](https://archive.ics.uci.edu/ml/datasets/Drug+Review+Dataset+%28Drugs.com%29).

### 3. EDA - Exploratory data analysis
      * Statisticaly analysis data

### 4. Data Preprocessing 
1. Sopt Word
2. Lemmatization
3. Split the dataset
    * Split the dataset with `80%` of `training set` and `20%` of `test set`.
4. Creating features and Target Variable

### 4. Model
1. `TF-IDF` - TF-IDF is a very popular feature extraction technique. Text needs to converted into vector or matrix before fed them to the Machine Learning model.
2. `Bag of Words`
3. `Naive Bayes`
4. `Passive Aggressive Classifier`
 
### 5. Evaluation
1. `Confusion Matrix`
2. `Accuracy`
