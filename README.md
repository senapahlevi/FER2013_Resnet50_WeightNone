# FER2013_Resnet50_WeightNone
Contain 5 models:
1.Model A : model = Sequential([resnet50_models, 
                    Dense(256, activation='relu'),
                    Dense(7, activation='softmax', name = 'classifer')])
