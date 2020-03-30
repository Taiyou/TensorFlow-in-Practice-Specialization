- 1. What is a windowed dataset?
Answer: A fixed-size subset of a tiime series

- 2. What does ‘drop_remainder=true’ do?
Answer: It ensures that all rows in the data window are the same length by adding data.

- 3. What’s the correct line of code to split an n column window into n-1 columns for features and 1 column for a label
Answer: dataset = dataset.map(lambda window: (window[:-1], window[-1:]))

- 4. What does MSE stand for?
Answer: Mean Squared error

- 5. What does MAE stand for?
Answer: Mean Absolute Error

- 6. If time values are in time[], series values are in series[] and we want to split the series into training and validation at time 1000, what is the correct code?
Answer:
time_train = time[:split_time]
x_train = series[:split_time]
time_valid = time[split_time:]
x_valid = series[split_time:]

- 7. If you want to inspect the learned parameters in a layer after training, what’s a good technique to use?
Answer: Assign a variable to the layer and add it to the model using that variable. Inspect its properties after training.

- 8. How do you set the learning rate of the SGD optimizer? 
Answer: Use the lr property

- 9. If you want to amend the learning rate of the optimizer on the fly, after each epoch, what do you do?
Answer: Use a LearningRateScheduler object in the callbacks namespace and assign that to the callback.
