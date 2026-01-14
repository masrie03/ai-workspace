# Purpose
4 pillars of prediction 
The purpose of this exercise is : 
 1. Can price be explained using available information? 
    (Signal: Is the answer hidden in this data?)
    if R2 = 0: the assumption is failing

2. Which factors matter more than the others?
    (What is the strongest clue?)
    the weight tells us how much a factor can influence
    big weight = affect a lot
    small weight = affect not much 

3. How much uncertainty exists even with good features? 
   (How much should I trust this guess?)
   noise or error

4. How do we know when a model is lying to us?
   evaluation & overfitting

# Problem Definition 
Given some information about the housing market, predict the median house price.

# Process
### Step 1: Data collection
    Data are retrieved from kaggle 

### Step 2: Understand the data
    - text columns = needs encoding
    - numeric columns = can be used directly
    - one numeric column = choose as target

### Step 3: Choose meaningful features
    out of the 8 columns, i didnt choose all. I only chose which is meaningful.
    We selected: 
     - state 
     - Type  
     - Tenure
     - Median_PSF
     - Transactions

### Step 4: Encode categorical variables
    Because model cant understand the data so we have to change it to numeric indicators using one hot encoding
    this allow the model to compare categories mathematically

### Step 5: Split data
    we separated: 
    80% training
    20% testing
    
    The reason is to prevent fake performance and memorizations

### Step 6: train the data

### Step 7: Evaluate on unseen data






 
