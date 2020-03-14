# Sentiment Analysis
<br>
<summary>
Suppose an online dating application company releases a package/ promotion called "relationship evaluate" to improve the revenue and attract the old users beside with traditional promotion packages. This feature would help users have more insight about their conversation in a privacy way. 
</summary>

I implemented it with 2 environments of Python: 2.7 and 3.6 because graphlab did not support for Python 3.6 version. <br>
The `sentiment_analysis_preprocess_py3.6.ipynb` includeds 2 parts: `Simple Statistic` and `Explore, process the data and make the csv file before do the sentiment analysis`. It did the pre-process Vietnamese text (I did not do some processes such as the acronyms, emoticon, uninteresting/ irrelevant words - update later'), then I change it into English and will export the test.csv file. Then the `sentiment_analysis_py2.7.ipynb` will analyse the test.csv. The model has improved from 81% to 85%. Due to the privacy reason, I will not publish the test.csv file.



* Free module and API: 
1. <a href="https://turi.com/">graphlab module</a> 
2. <a href="https://tech.yandex.com/translate/">Yandex Translate API </a> 
3. <a href="https://cloud.google.com/translate/?utm_source=google&utm_medium=cpc&utm_campaign=japac-VN-all-en-dr-skws-all-all-trial-b-dr-1008074&utm_content=text-ad-none-none-DEV_c-CRE_252507584784-ADGP_Hybrid+%7C+AW+SEM+%7C+SKWS+~+T1+%7C+BMM+%7C+ML+%7C+M:1+%7C+VN+%7C+en+%7C+Translation+%7C+API-KWID_43700011073087841-kwd-34473296586&userloc_1028581&utm_term=KW_%2Btranslator%20%2Bapi&gclid=CjwKCAjwgbLzBRBsEiwAXVIygBzAE0zQczAKa7a1MJKmV8Ad5bvDOgwlaGtx-NgkaFPnJOLzF7oluhoCX_YQAvD_BwE">Google translate API </a>