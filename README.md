# Bangalore-House-Price-Prediction-using-DecisionTreeRegressor
bangalore data is given in form of csv format and based on feature given in data we have to
We have to predict the house prices in bangalore using Decision Tree
Features of Dataset
Data
   Column                             Dtype  
---  ------                             -----  
 0   bath                               float64
 1   balcony                            float64
 2   price                              float64
 3   total_sqft_int                     float64
 4   bhk                                int64  
 5   price_per_sqft                     float64
 6   area_typeSuper built-up  Area      int64  
 7   area_typeBuilt-up  Area            int64  
 8   area_typePlot  Area                int64  
 9   availability_Ready To Move         int64  
 10  location_Whitefield                int64  
 11  location_Sarjapur  Road            int64  
 12  location_Electronic City           int64  
 13  location_Marathahalli              int64  
 14  location_Raja Rajeshwari Nagar     int64  
 15  location_Haralur Road              int64  
 16  location_Hennur Road               int64  
 17  location_Bannerghatta Road         int64  
 18  location_Uttarahalli               int64  
 19  location_Thanisandra               int64  
 20  location_Electronic City Phase II  int64  
 21  location_Hebbal                    int64  
 22  location_7th Phase JP Nagar        int64  
 23  location_Yelahanka                 int64  
 24  location_Kanakpura Road            int64  
 25  location_KR Puram                  int64  
 26  location_Sarjapur                  int64  
 27  location_Rajaji Nagar              int64  
 28  location_Kasavanhalli              int64  
 29  location_Bellandur                 int64  
 30  location_Begur Road                int64  
 31  location_Banashankari              int64  
 32  location_Kothanur                  int64  
 33  location_Hormavu                   int64  
 34  location_Harlur                    int64  
 35  location_Akshaya Nagar             int64  
 36  location_Jakkur                    int64  
 37  location_Electronics City Phase 1  int64  
 38  location_Varthur                   int64  
 39  location_Chandapura                int64  
 40  location_HSR Layout                int64  
 41  location_Hennur                    int64  
 42  location_Ramamurthy Nagar          int64  
 43  location_Ramagondanahalli          int64  
 44  location_Kaggadasapura             int64  
 45  location_Kundalahalli              int64  
 46  location_Koramangala               int64  
 47  location_Hulimavu                  int64  
 48  location_Budigere                  int64  
 49  location_Hoodi                     int64  
 50  location_Malleshwaram              int64  
 51  location_Hegde Nagar               int64  
 52  location_8th Phase JP Nagar        int64  
 53  location_Gottigere                 int64  
 54  location_JP Nagar                  int64  
 55  location_Yeshwanthpur              int64  
 56  location_Channasandra              int64  
 57  location_Bisuvanahalli             int64  
 58  location_Vittasandra               int64  
 59  location_Indira Nagar              int64  
 60  location_Vijayanagar               int64  
 61  location_Kengeri                   int64  
 62  location_Brookefield               int64  
 63  location_Sahakara Nagar            int64  
 64  location_Hosa Road                 int64  
 65  location_Old Airport Road          int64  
 66  location_Bommasandra               int64  
 67  location_Balagere                  int64  
 68  location_Green Glen Layout         int64  
 69  location_Old Madras Road           int64  
 70  location_Rachenahalli              int64  
 71  location_Panathur                  int64  
 72  location_Kudlu Gate                int64  
 73  location_Thigalarapalya            int64  
 74  location_Ambedkar Nagar            int64  
 75  location_Jigani                    int64  
 76  location_Yelahanka New Town        int64  
 77  location_Talaghattapura            int64  
 78  location_Mysore Road               int64  
 79  location_Kadugodi                  int64  
 80  location_Frazer Town               int64  
 81  location_Dodda Nekkundi            int64  
 82  location_Devanahalli               int64  
 83  location_Kanakapura                int64  
 84  location_Attibele                  int64  
 85  location_Anekal                    int64  
 86  location_Lakshminarayana Pura      int64  
 87  location_Nagarbhavi                int64  
 88  location_Ananth Nagar              int64  
 89  location_5th Phase JP Nagar        int64  
 90  location_TC Palaya                 int64  
 91  location_CV Raman Nagar            int64  
 92  location_Kengeri Satellite Town    int64  
 93  location_Kudlu                     int64  
 94  location_Jalahalli                 int64  
 95  location_Subramanyapura            int64  
 96  location_Bhoganhalli               int64  
 97  location_Doddathoguru              int64  
 98  location_Kalena Agrahara           int64  
 99  location_Horamavu Agara            int64  
 100 location_Vidyaranyapura            int64  
 101 location_BTM 2nd Stage             int64  
 102 location_Hebbal Kempapura          int64  
 103 location_Hosur Road                int64  
 104 location_Horamavu Banaswadi        int64  
 105 location_Domlur                    int64  
 106 location_Mahadevpura               int64  
 107 location_Tumkur Road               int64 
 
 Used decision tree regressor
 DecisionTreeRegressor(criterion='mse',max_depth=5)
 
 Conclusion 
 RMSE=47.79612031076121
 Accuracy=88.63048678977661
