# News Summarization WebApp- News On Tips.


**News On Tips** is a Web Application created on the base of Natural Language Processing (Hugging Face)- I have used **Facebook's BART Large CNN model.** 

The model asks users to Input any type of News Article and also the range of the output they would want, and summarizes it into a short concise paragraph. The range of the output is from 30 words to 700 words.



Input           |  Output
:-------------------------:|:-------------------------:
![](https://github.com/parthkohli92/News-Summarizer/blob/main/images/news3.PNG)  |  ![](https://github.com/parthkohli92/News-Summarizer/blob/main/images/news2.PNG)




#### About BART model
BART model pre-trained on English language, and fine-tuned on CNN Daily Mail. It was introduced in the paper BART: Denoising Sequence-to-Sequence Pre-training for Natural Language Generation, Translation, and Comprehension by Lewis et al. and first released in (https://github.com/pytorch/fairseq/tree/master/examples/bart).

#### Technologies used:
Html, Css, Python-NLP, Flask, Deployment on Heroku.

## How do you run this project?

1. Clone or download this repository to your local machine.
2. Install all the libraries mentioned in the requirements.txt file with the command ```pip install -r requirements.txt ```
3. Open your terminal/command prompt from your project directory and run the file ``` app.py``` by executing the command ```python app.py```
4. Go to your browser and type ```http://127.0.0.1:5000/``` in the address bar.
5. And, there you go!

### The Basic UI of the website

<p align="center">
  <img width="1000" height="400" src="https://github.com/parthkohli92/News-Summarizer/blob/main/images/news1.PNG">
</p>


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

