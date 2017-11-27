# Translating from English to French with an LSTM cell

Translating text from one language to another is something that seems like an easy software problem to solve, but it is surprisingly difficult. Only recently has Google been able to create a model that translates anywhere near human efficiency. While there is no way to know exactly how Google is translating text so well, a good start is using an LSTM cell (or maybe a bi-directional RNN). 

This project takes a text corpus with a vocab size of a few hundred words and learns how to translate sentences from English to French with **97% validation accuracy**. While this vocab size is small, it proves that an LSTM cell is a viable method for translating text. In order to translate a larger vocab of words, we would need more data and GPU time, but I think you could achieve good results.

Here is an example of the model translating a sentence.

```
Input
  Word Ids:      [188, 46, 107, 197, 39, 113]
  English Words: ['my', 'favorite', 'fruit', 'is', 'orange', '.']

Prediction
  Word Ids:      [48, 38, 20, 267, 319, 132, 1]
  French Words: ['mon', 'fruit', 'préféré', 'est', "l'orange", '.', '<EOS>']
```

# Connect with me

If you'd like to collaborate on a project, learn more about me, or just say hi, feel free to contact me using any of the social channels listed below.

- [Personal Website](https://zackthoutt.com)
- [Email](mailto:zackarey.thoutt@colorado.edu)
- [LinkedIn](https://www.linkedin.com/in/zack-thoutt-57275655/)
- [Twitter](https://twitter.com/zthoutt)
- [Medium](https://medium.com/@zthoutt)
- [Quora](https://www.quora.com/profile/Zack-Thoutt)
- [HackerNews](https://news.ycombinator.com/submitted?id=zthoutt)
- [Reddit](https://www.reddit.com/user/zthoutt/)
- [Kaggle](https://www.kaggle.com/zynicide)
- [Instagram](https://www.instagram.com/zthoutt/)
- [500px](https://500px.com/zthoutt)
