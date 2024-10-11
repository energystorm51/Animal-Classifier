# Animal-Classifier
Building An Accurate And Efficient Animal Classification Application. <br/>
Training ML models to classify animals into one of 151 categories using the Animal dataset containing over 6000+ animal images.

## Code
The model is trained in Python using Jupyter Notebook and run in the Google Colab Environment.
The dataset can be found here: https://drive.google.com/drive/folders/1_nn9bt9pn9rwWyWIG2vKf377O-C9Oa1b?usp=sharing. Note that significant image filtering has occurred to remove 'poor' images that would negatively impact the performance of the model, e.g. unrealistic animal drawings, heavy watermarks, etc.

## Performance Measure
Accuracy is determined by using a function that computes the accuracy over the top-k predictions for the
specified values of k. For example, in top-3 accuracy the output is considered the ‘right answer’ if the right
answer appears in the top 3 guesses. Meanwhile, efficiency is determined using FLOPS (Floating-Point
Operations per Second). This is a unit of measurement used to quantify the computing power (Sheldon, R.2023). 
Efficiency is calculated by dividing accuracy by the FLOPS count.

## Report Analysis
Realistically, an animal classification program available to the general public would be more popular with a high
accuracy. Therefore, the most optimal model is Model 8, which uses Transfer Learning to achieve this. The
efficiency is also at an acceptable level, close to 80%. A tradeoff between accuracy and efficiency was favored,
as efficiency may vary depending on the device being used

**Authored by Jingyi Qiu and Toyesha Kaushik**
