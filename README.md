Introduction
Artificial Neural Networks (ANN) have paved a new path to the emerging AI industry since decades it has been introduced
. With no doubt in its massive performance and architectures proposed over the decades, traditional machine-learning 
algorithms are on the verge of extinction with deep neural networks, in many real-world AI cases.
But, every new invention in technology must come with a drawback, otherwise, scientists cannot strive and discover
something better to compensate for the previous drawbacks. Similarly, Neural Networks also came up with some loopholes
that called for the invention of recurrent neural networks.

Why Recurrent?
In Neural Networks, we stack up various layers, composed of nodes that contain hidden layers, which are for learning 
and a dense layer for generating output. But, the central loophole in neural networks is that it does not have memory.
Since no memory is associated, it becomes very difficult to work on sequential data like text corpora where we have 
sentences associated with each other, and even time-series where data is entirely sequential and dynamic.
Here, Recurrent Neural Networks comes to play. RNN addresses the memory issue by giving a feedback mechanism that 
looks back to the previous output and serves as a kind of memory. Since the previous outputs gained during training 
leaves a footprint, it is very easy for the model to predict the future tokens (outputs) with help of previous ones.

Why LSTM when we have RNN?
A sentence or phrase only holds meaning when every word in it is associated with its previous word and the next one. 
LSTM, short for Long Short Term Memory, as opposed to RNN, extends it by creating both short-term and long-term memory
components to efficiently study and learn sequential data. Hence, it’s great for Machine Translation, Speech 
Recognition, time-series analysis, etc.


![image](https://github.com/KawulJanSetouchi/documents/assets/145730569/a02fab7c-b50b-492d-b765-e7ba45501fdc)

![image](https://github.com/KawulJanSetouchi/documents/assets/145730569/07865cab-db6c-4832-af0b-3e02451a3a6a)
