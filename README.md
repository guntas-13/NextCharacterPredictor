# Next Character Predictor
## Find the app hosted at [Link](https://tensionflowcharpredict.streamlit.app/)
**Datasets: [Link](https://cs.stanford.edu/people/karpathy/char-rnn/)**

## **App Homepage**
![](https://github.com/guntas-13/NextCharacterPredictor/blob/main/1.png)
## **Generated Text for Gulliver's Travels**
![](https://github.com/guntas-13/NextCharacterPredictor/blob/main/2.png)
## **Generated Text for Wikipedia Corpus**
![](https://github.com/guntas-13/NextCharacterPredictor/blob/main/3.png)

### **Embedding the characters as a Vector $\in \mathbb{R}^N$**
![](https://github.com/guntas-13/NextCharacterPredictor/blob/main/Embed.svg)

### **Input layer of the model and creating the training examples**
![](https://github.com/guntas-13/NextCharacterPredictor/blob/main/MLPToken.svg)

To make inference from the model trained on ```tolstoy.txt``` run the script:
```bash
python3 predictT.py
```

To make inference from the model trained on ```wonderland.txt``` run the script:
```bash
python3 predictW.py
```

To run the StreamLit App, run the script:
```bash
streamlit run app.py
```
