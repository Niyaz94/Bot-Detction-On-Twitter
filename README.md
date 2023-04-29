This project contains four datasets as follows:

1 - /PREPROCESS_SAMPLES/Dataset_Classified_With_BotometerLite_1000.csv.gz:- This dataset contains 1000 samples from our dataset, selected randomly. The dataset is classified with Botometer Lite API, and the features are removed/added/edited based on our paper [https://scholar.google.com/citations?view_op=view_citation&hl=en&user=fQo-gkAAAAAJ&citation_for_view=fQo-gkAAAAAJ:u5HHmVD_uO8C]

2 - /PREPROCESS_SAMPLES/Dataset_Classified_With_BotometerV4_1000.csv.gz:- This dataset contains 1000 samples from our dataset, selected randomly. The dataset is classified with Botometer V4 API, and the features are removed/added/edited based on our paper [https://scholar.google.com/citations?view_op=view_citation&hl=en&user=fQo-gkAAAAAJ&citation_for_view=fQo-gkAAAAAJ:u5HHmVD_uO8C]


3 - /ROW_SAMPLES/Row_samples_classified_with_botometerLite_1000.csv.gz:- This dataset contains 1000 samples from our dataset, selected randomly. All the features are original features received from Twitter API; however, we add:

A - the score of Botometer Lite API [botometer_lite_score feature]
B - The date of collecting Sample from Twitter API [data_collected_at feature]

4 - /ROW_SAMPLES/Row_samples_classified_with_botometerV4_1000.csv.gz:- This dataset contains 1000 samples from our dataset, selected randomly. All the features are original features received from Twitter API; however, we add:

    A - the score of Botometer V4 [botometer_v4_score feature]
    B - The date of collecting Sample from Twitter API [data_collected_at feature]
