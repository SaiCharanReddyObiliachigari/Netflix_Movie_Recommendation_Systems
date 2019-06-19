# Netflix_Movie_Recommendation_Systems
This project involves:
1. Exploratory Data Analysis (Data Cleaning)
2. ML Models used:
3. XGBoost with Initial 13 features
4. Surprise Baseline Model
5. XGBoost + Surprise Baseline Model on 13 Features
6. Surprise KNNBaseline Predictor
   6.1) Surprise KNNBaseline with user user similarities
   6.2) Surprise KNNBaseline with movie movie similarities
7. XGBoost + Surprise Baseline + KNNBaseline Predictor 
8. Matrix Factorization Techniques:
   8.1) SVD Matrix Factorization User Movie intractions
   8.2) SVD Matrix Factorization with implicit feedback from user ( user rated movies ) 
9.  XgBoost with 13 features + Surprise Baseline + Surprise KNNbaseline + Matrix Factorization Techniques  
10. XgBoost with Surprise Baseline + Surprise KNNbaseline + MF Techniques
11. Comparision between all models:
    THE ROOT MEAN SQUARE ERRORS FOR ALL THE MODELS AND THEIR COMBINATIONS 
    RESULT:
    1. svd               1.0726046873826458
    2. knn_bsl_u         1.0726493739667242
    3. knn_bsl_m          1.072758832653683
    4. svdpp             1.0728491944183447
    5. bsl_algo          1.0730330260516174
    6. xgb_knn_bsl_mu    1.0753229281412784
    7. xgb_all_models     1.075480663561971
    8. first_algo        1.0761851474385373
    9. xgb_bsl           1.0763419061709816
    10.xgb_final         1.0763580984894978
    11.xgb_knn_bsl       1.0763602465199797
    
