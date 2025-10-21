# Stock Prediction using LSTM 
  Tried to predict the stock price of Microsoft using historical data. I have used tactics from Machine learning and blend them with components of deep learning to create a time Series Analysis Model using LSTM. 


- LSTM (Long short term memory):  
    - It is a type of recurrent neural network(RNN) designed to better handle sequence of data, especially when long term dependencies are important

    - LSTMs have special units called memory cells, which allow them to remember information for longer periods compared to traditional RNNs.

- It has following applications : Time seires prediction, natural lanuage processing, speech recognition

- LSTM uses three types of gates:
  1. Forget Gate: Decides which information to discard from the cell state.
  2. Input Gate: upfates the cell state with new information.
  3. Output Gate: Determines what the next hidden state will be, which infulences the output and the next time step. 


## Model Summary
  1. Create a container
  2. First brain(LSTM Layer1): add a brain that remember things in sequence.
  3. Second Brain(LSTM Layer2): Add another brain that makes decision based on th first brain.
  4. Decision Making(Dense Layer): Add a layer that decides what to do with the brains' thoughts.
  5. Half Helpers Resting(dropout): Let half of the helpers rest to avoid mistakes.
  6. Final Answer(Dense Layer): Add the final decisioon making part.
  7. Toy review(Model Summary): Check how well the toy was built.
  8. Learning Instruction(compile): Teach the toy how to improve its guesses.
