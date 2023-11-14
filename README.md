# Automatic-Speech-Recognition-using-CTC




This project explores Automatic Speech Recognition (ASR), teaching computers to understand spoken words and convert them into text. It's like magic: talking to a computer and having it understand every word you say!

The demonstration features a special kind of computer brain called a 2D Convolutional Neural Network (CNN), combined with a Recurrent Neural Network (RNN) and something called a Connectionist Temporal Classification (CTC) loss. This combination helps the computer build a model similar to the ones used in advanced speech recognition systems like DeepSpeech2.

To train this brainy model, we use a dataset called LJSpeech from the LibriVox project. This dataset contains short recordings of someone reading parts of different non-fiction books.

We test how good our model is at understanding by using a cool metric called Word Error Rate (WER). It's like grading our computer's homework. We count how many mistakes it makes in recognizing words compared to the original spoken words. The lower the mistakes, the better our computer is at understanding speech.

In this project, we've used the WER score as our main yardstick to see how well our model performs in understanding spoken language.

