# Message Replier

Giving suggestions for a message is same as creating a chatbot which will help in replying a message automatically.

A human has to reply to a lot of e-mails everyday. This task takes a lot of valuable time from the user. So to curb this problem, Tthis project is made to automate the task of replying to a given message. This project was made in python and Deep Learning techniques were used. The technique that I used in this project is Seq2Seq modelling using RNN(Recurrent Neural Networks).

A sequence to sequence model aims to map a fixed length input with a fixed length output where the length of the input and output may differ.The model consists of 3 parts: encoder, intermediate (encoder) vector and decoder. Encoder encodes the input sequence. Encoder vector is the final hidden state produced from the encoder part of the model. Decoder decodes the predicted output sequence by the neural network.

## Dataset Used

The data used to train the model is gunthercox. This data was used because there were different domains such as AI, sports, movies etc conversations in this dataset. The results are not great because the dataset is too small.

## Tools and Technologies Used

The complete code is written in python 3. The deep learning framework that is used is Keras because of its simplicity. Numpy is used to create matrices of data. The website was made with the help of Flask because of its simplicity. HTML and CSS are used for front-end.

### Downloading the dependencies from requirements file
```bash
pip install -r requirements.txt
or 
sudo pip install -r requirements.txt
```

### To run the website
```bash
python main.py
```
The website will run on server "127.0.0.1:5000".

### To retrain the model
```bash
python word_seq2seq_train.py

Note: The model is trained and all the weights and id2word etc files are stored in models folder.
```

#### Thank You
