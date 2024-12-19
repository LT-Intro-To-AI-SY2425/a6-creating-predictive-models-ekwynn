# Part 4 - Classification Writeup

After completing `a6_part4.py` answer the following questions

## Questions to answer

1. Comment out the StandardScaler and re-run your test. How accurate is the model? Why is that?
    Commenting out the StandardScaler caused the model to become a lot less accurate. The model turned from an accuracy of 0.88 to 0.57 without the StandardScaler. The standard scaler removes variance, making it a lot more accurate. Without it, the variance affects the accuracy.

2. How accurate is the model with the StandardScaler? Is this model accurate enough for the given use case? Explain.
    I would say that this model is extremely accurate with the StandardScaler. I do think tha this model is accurate for the given use case.

3. Looking at the predicted and actual results, how did the model do? Was there a pattern to the inputs that the model was incorrect about?
    Predictions matched the actual results and I didn't see a consistent pattern of inaccuracies. 
4. Would a 34 year old Female who makes 56000 a year buy an SUV according to the model? Remember to scale the data before running it through the model.
    The female wouldn't buy a SUV according to this model.

