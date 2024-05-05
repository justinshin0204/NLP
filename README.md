# Seq2Seq
이전에 봤던 RNN과 LSTM의 모델에는 몇가지 문제점이 존재했음
RNN 기반 모델은 1:1 realationship을 가정하고 학습 및 추론을 했는데 input sequence와 출력의 길이가 다를 때도 있을 수 있음
ex) vamos => Let's go
그리고 꼭 x<sub>1</sub> 이 y<sub>1</sub>에 대응되리라는 법도 없다.
![](https://velog.velcdn.com/images/justinshin/post/7ed2fee7-d8ef-4ece-a7fd-cdf94948ffe1/image.png)
이렇게 순서가 바뀌게 되는 경우들도 허다함
