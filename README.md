# Module 14 Challenge

Recording Results :  
Step 1 : Adjusting the size of Training Dataset :  
with the original training data (offset months = 3) , the accuracy with SVM model is 0.55 : image saved as Resources/svm_actual_strategy_plot[sw=4,lw=100]++TD_offset=3.png
with changing the training data (offset months = 6) , the accuracy with SVM model is 0.56 : image saved as Resources/svm_actual_strategy_plot[sw=4,lw=100]+TD_offset=6.png
with changing the training data (offset months = 12) , the accuracy with SVM model is still 0.56 : image saved as Resources/svm_actual_strategy_plot[sw=4,lw=100]+TD_offset=12.png

The impact of changing training window is we can safely say offset months = 6 is the best offset we can have

Step 2 : Adjusting SMA input features:  
with the original SMA window size (short_window=4,long_window=100) , the accuracy with SVM model is 0.55 : image saved as Resources/svm_actual_strategy_plot[sw=4,lw=100].png
with the changed SMA window size (short_window=10,long_window=200) , the accuracy with SVM model is 0.55 : image saved as Resources/svm_actual_strategy_plot[sw=10,lw=200].png
with the changed SMA window size (short_window=50,long_window=300) , the accuracy with SVM model is 0.56 : image saved as Resources/svm_actual_strategy_plot[sw=50,lw=300].png

The SMA input features in original window size is very optimum in the original size (short_window=4,long_window=100) and training data offset as 3.     
        Evident in the image image saved as Resources/svm_actual_strategy_plot[sw=4,lw=100]+TD_offset=3.png


Between the SVM and LR model , SVM model performed lot better as evident in svm_actual_strategy_plot.png compared to lr_actual_strategy_plot.pnd inside Resources folder


