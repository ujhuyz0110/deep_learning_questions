### Week1 Practical aspects of deep learning
**Q1. If you have 10,000,000 examples, how would you split the train/dev/test set?**  
A1. 98% train, 1% dev, 1% test  
  
**Q2. The dev and test set should:**  
A2. 
- \[x] Come from the same distribution
- \[ ] Come from different distributions
- \[ ] Be identical to each other (same (x,y) pairs) 
- \[ ] Have the same number of examples 
  
**Q3. If your Neural Network model seems to have high bias, what of the following would be promising things to try? (Check all that apply.)**  
A3.  
- \[ ] Get more training data
- \[x] Increase the number of units in each hidden layer
- \[ ] Add regularization
- \[x] Make the Neural Network deeper
- \[ ] Get more test data  
  
**Q4. You are working on an automated check-out kiosk for a supermarket, and are building a classifier for apples, bananas and oranges. Suppose your classifier obtains a training set error of 0.5%, and a dev set error of 7%. Which of the following are promising things to try to improve your classifier? (Check all that apply.)**  
A4. 
- \[x] Increase the regularization parameter lambda
- \[ ] Decrease the regularization parameter lambda
- \[x] Get more training data
- \[ ] Use a bigger neural network
  
**Q5. What is weight decay**
A5.  
- \[ ] A technique to avoid vanishing gradient by imposing a ceiling on the values of the weights
- \[ ] Gradual corruption of the weights in the neural network if it is trained on noisy data. 
- \[ ] The process of gradually decreasing the learning rate during training. 
- \[x] A regularization technique (such as L2 regularization) that results in gradient descent shrinking the weights on every iteration.  
  
**Q6. What happens when you increase the regularization hyperparameter lambda?**  
A6.  
- \[x] Weights are pushed toward becoming smaller (closer to 0) 
- \[ ] Weights are pushed toward becoming bigger (further from 0)
- \[ ] Doubling lambda should roughly result in doubling the weights
- \[ ] Gradient descent taking bigger steps with each iteration (proportional to lambda)
  
**Q7. With the inverted dropout technique, at test time:**
A7. You do not apply dropout (do not randomly eliminate units) and do not keep the 1/keep_prob factor in the calculations used in training  
  
**Q8. Increasing the parameter keep_prob from (say) 0.5 to 0.6 will likely cause the following: (Check the two that apply)**
A8.  
- \[ ] Increasing the regularization effect
- \[x] Reducing the regularization effect
- \[ ] Causing the neural network to end up with a higher training set error
- \[x] Causing the neural network to end up with a lower training set error
  
**Q9. Which of these techniques are useful for reducing variance (reducing overfitting)? (Check all that apply.)**
A9.  
- \[ ] Vanishing gradient
- \[ ] Gradient Checking
- \[x] Data augmentation
- \[x] Dropout
- \[ ] Exploding gradient
- \[ ] Xavier initialization
- \[x] L2 regularization  
  
**Q10. Why do we normalize the inputs?**
A10. It makes the cost function faster to optimize  
  
### Week2

### Week3