# ML_CA02
# I was interested what it's  like to turn text into Dataframe, So I tried to write a loop creating a DataFrame, but I think it is not right, anything is look like chaotic, but no worry, you can just ignore it
# For the make_Dictionary, this is a loop structure to help us processing data like This dictionary read the data, splited string and judged true or false features in item for the freature selection.
# Then make_Dictionary(root_dir) and extract_features(mail_dir) both functions are features selections for model tranning, the make_Dictionary is served for extract_features(mail_dir). In extract_features(mail_dir),features_matrix made the dataframe, and train_labels help machine to find out count and docID. In the for loop, from the 2th row that would be splited, and the loop will find out key words and numbers that will be imported into freatures_martix. About the train_label, it help freatures_martix to define what is good emails and what is junk email. If text name is "spmsg", it will become junk email, the opposite is good
# I imported data in TRAIN_DIR="./train-mails" and TEST_DIR="./test-mails"
# In make_Dictionary(TRAIN_DIR), it distributed the main train data and test data, the features_matrix, labels are like X and y to train the model, test_features_matrix, test_labels need to create the prediction for testing the accuracy of the train model.
# In the final part, just build model, train model, and test the result by GaussianNB, that's easy, and I got the right accuracy 0.9615384615384616.
