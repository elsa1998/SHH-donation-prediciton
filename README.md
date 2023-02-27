# Hunger Relief Donation Prediction 

# Goal
Helping our client - SHH (Second Harvest Heartland), a US leading hunger relief agencies to better prioritize resource investment in earned media within the next year.

# Data Preprocessing
1. Data merging (media data + gift data)
- Media data (20k+ rows): Filter the media type and get the rolling sum
- Gift data (200k+ rows): Sum the donation$ by date 
2. Sum donation$ & media reach by date 
3. Aggregated to a merged data set (key = date)

<img width="718" alt="image" src="https://user-images.githubusercontent.com/59221097/221467091-4e3cf5fb-8ca8-4f8a-8395-d83ac2c9062b.png">

# How does it work?
When keywords such as 'kitchen' and 'hunger' appear in a news (headline, hit sentence, keyword), after 7 days we will see a fund raised for [MN Central Kitchen] & [Child Hunger Initiative]

<img width="659" alt="image" src="https://user-images.githubusercontent.com/59221097/221468218-66b499d6-7288-4579-988a-981c0cb98ed4.png">

# Modeling
We built predictive models (KNN) using data from 2020 to 2022 to find the donation amount generated from each media channel.

# Key findings
1. For facebook echo, focuses on these media channels:
<img width="687" alt="image" src="https://user-images.githubusercontent.com/59221097/221470541-b53047aa-1992-4594-862e-e48b5ff36769.png">
2. For Twitter echo, focuses on these media channels:
<img width="687" alt="image" src="https://user-images.githubusercontent.com/59221097/221470598-b1735fbd-1303-4af1-80e4-ee1a728394f3.png">
