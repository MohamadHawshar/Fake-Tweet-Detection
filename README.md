# Fake-Tweet-Detection

The objective of this project is to perform a comparative analysis of five supervised classification methods. These methods are implemented to distinguish regular Twitter users from polluting users based on data from 2006. The analysis involves calculating attributes that potentially influence user categorization, applying classification methods, and evaluating their performance using two tests: the Chi-2 test and information gain.

The methodology consists of several steps. Firstly, the input files are read and associated with respective dataframes using the Pandas library. Next, 15 attributes that may influence user categorization are computed using specific functions, and the resulting dataframes are merged based on user type, assigning binary classes for polluting (1) and non-polluting (0) users. Data preprocessing is then conducted to handle missing values and normalize the data using Z-Score.

Subsequently, the five classifications are generated and compared using confusion matrices and ROC curves. Two tests, information gain and Chi-2, are performed on seven attributes with the strongest results. The optimal classification method is found to be Random Forests.

The project methodology involves data collection and processing, as well as the creation of specific functions for attribute calculation. The attributes include user name length, profile description length, account longevity, number of followings, number of followers, standard deviation of unique numerical IDs of followings, following-to-follower ratio, and total number of tweets sent.

For more details, refer to the shared report or the code comments.
![image](https://github.com/MohamadHawshar/Fake-Tweet-Detection/assets/60289580/47b8fd45-00a4-4973-b00a-a62a991841ac)
![image](https://github.com/MohamadHawshar/Fake-Tweet-Detection/assets/60289580/187a3416-69be-428c-98b6-4d0253e2c772)
![image](https://github.com/MohamadHawshar/Fake-Tweet-Detection/assets/60289580/ddb2875c-4024-4db9-860b-40a2b6c5ea59)



