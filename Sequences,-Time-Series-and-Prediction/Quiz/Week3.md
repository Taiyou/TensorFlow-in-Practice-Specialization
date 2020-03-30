- 1. If X is the standard notation for the input to an RNN, what are the standard notations for the outputs?
Answer: H and Y(hat)

- 2. What is a sequence to vector if an RNN has 30 cells numbered 0 to 29?
Answer: The Y(hat) for the last cell

- 3. What does a Lambda layer in a neural network do?
Answer: Allows you to execute arbitarary code while traning

- 4. What does the axis parameter of tf.expand_dims do?
Answer: Defines dimension index at which you will expand the tensor.

- 5. A new loss function was introduced in this module, named after a famous statistician. What is it called?
Answer: Huber loss

- 6. What’s the primary difference between a simple RNN and an LSTM?
Answer: In addition to the H output, LSTMs have a state cell that run across all cells.

- 7. If you want to clear out all temporary variables that tensorflow might have from previous sessions, what code do you run?
Answer: tf.keras.backend.clear_session()

- 8. What happens if you define a neural network with these two layers?
Answer: Your model will fail because you need return_sequence = True after the first LSTM layer.
