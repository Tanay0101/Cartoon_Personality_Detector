# Cartoon_Personality_Detector
This model predicts the personalities(Albert Einstein, Mahatma Gandhi, Abraham Lincoln, Barack Obama, Steve Jobs, Donald Trump) in cartoon images
The data is taken from Kaggle, but I cannot find the dataset again, ping me if you want it.
To improve performance clean the data first, this increased the validation and test accuracy by 8% and 6% respectively. The uploaded notebook trains the model with val_accuracy of 96% and test_accuracy of 75%.
I initially used a pre-trained inception network as base, but found that training a simpler network from scratch was giving much better results and hence I switched to the new network. 
Please checkout the test file, it shows that the model works on real life images too.
