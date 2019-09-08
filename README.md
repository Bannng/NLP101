# NLP 101: 딥러닝과 자연어 처리 학습을 위한 자료 저장소
본 문서는 딥러닝을 이용한 자연어 처리를 학습하고자 하는 분들을 대상으로 작성되었습니다.
추가되었으면 좋겠다 생각하시는 자료를 알려주시면 반영하도록 하겠습니다.

_본 문서는 아래와 같은 규칙을 따라 작성되었습니다._
- 기본적으로 동일한 내용을 다루는 자료는 중복해서 기록하지 않습니다. <br/>
*e.g.) Dive into Deep Learning과 Deep Learning book 중 더 좋은 자료라고 판단한 Deep Learning book만 기록합니다.*
- 난이도가 유사하다고 판단되는 자료는 하나만 기록합니다.
- 다만, 유사 난이도를 보유한 자료가 한글 자료일 경우, 영어에 어려움이 있으신 분들을 고려해 함께 기록합니다.
- 난이도의 차이가 있는 자료, 이를테면 선후행 학습이 수반되어야 하는 자료는 모두 기록합니다.
- 난이도 판단은 주관적으로 이루어졌습니다. 난이도 산정에 문제가 있다고 생각하시거나, 더 나은 산정 방안이 있다면 공유해주시길 바랍니다. **(Scale: 1-5)**
<br/>

## Mathematics
### Statistics and Probabilities
| source | level | description |
|---|:---:|---|
| [Statistics 110](https://www.edwith.org/harvardprobability/) | 1.5 | 문과생도 이해할 수 있을 정도로 쉽게 확률론에 대한 설명을 해주는 강의입니다. |
| [확률과 통계 (이상화)](http://www.kocw.net/home/search/kemView.do?kemId=1056974) | 2 | KOCW에서 높은 평점을 자랑하는 한양대학교 이상화 교수님의 확률과 통계 강의입니다. |
<br/>

### Linear Algebra
| source | level | description |
|---|:---:|---|
| [Linear Algebra (김영길)](https://www.youtube.com/watch?v=sDZB7ozFytk&list=PL9k2wIz8VsfOjzW_nU_yRPFBoyS5C7ttG&index=2&t=58s) | 2 | Gilbert Strang의 선형대수 책과 더불어 선형대수 입문서로 유명한 Friedberg의 Linear Algebra 교재를 김영길 교수님이 한국어로 강의하신 내용입니다. |
| [Linear Algebra (Gilbert Strang)](https://www.youtube.com/watch?v=ZK3O402wf1c&list=PLE7DDD91010BC51F8) | 2.5 | Gilbert Strang의 전설적인 선형대수 강의입니다. |
| [선형대수 (이상화)](http://www.kocw.net/home/search/kemView.do?kemId=977757) | 2.5 | KOCW에서 높은 평점을 자랑하는 한양대학교 이상화 교수님의 선형대수 강의입니다. |
| [Matrix methods in Data Analysis and Machine Learning (Gilbert Strang)](https://www.youtube.com/watch?v=Cx5Z-OslNWE&list=PLUl4u3cNGP63oMNUHXqIUcrkS2PivhN3k) | 3.5 | Gilbert Strang 교수의 선형대수 응용편입니다. 선형대수 강의를 선수 지식으로 하기 때문에 난이도가 어느 정도 있지만, 실제 선형대수가 머신러닝에 있어 어떻게 활용되는지 학습할 수 있는 좋은 강의입니다. |
<br/>

### Basic mathematics & Overview
| source | level | description |
|---|:---:|---|
| [Calculus (Gilbert Strang)](https://ocw.mit.edu/ans7870/resources/Strang/Edited/Calculus/Calculus.pdf) | 2 | Gilbert Strang 교수의 미적분학 교재입니다. 모든 챕터를 볼 필요는 없지만, Chapter 2-4, 11-13, 15-16 등은 학습하면 좋을 것 같다고 생각해 추가하였습니다. |
| [Mathematics for Machine Learning](https://mml-book.github.io/) | 3 | 머신러닝 학습에 수반되는 수학 지식을 모두 담은 책입니다. 개괄적 설명을 이어나가기에 이공계 학부 수준의 수학 지식은 선행되어야 이해하기 수월할 것이라 생각합니다. |
<br/>

## Deep Learning and Natural Language Processing
### Deep Learning
| source | level | description |
|---|:---:|---|
| [모두를 위한 딥러닝 (Sung Kim)](https://www.youtube.com/watch?v=BS6O0zOGX4E&list=PLlMkM4tgfjnLSOjrEJN31gZATbcj_MpUm) | 1.5 | Clova AI를 리드하고 계신 김성훈님의 딥러닝 강의입니다. 입문 수준으로 이만한 강의가 없다고 생각합니다. |
| [모두를 위한 딥러닝2](https://www.youtube.com/channel/UCC76Jmsg6SAjdvphzGSJMBQ) | 1.5 | 앞서 언급한 김성훈님 강좌의 후속작입니다. Tensorflow와 PyTorch 버전이 각각 존재하며, 최신 코드로 설명을 진행하기 때문에 가치가 있다고 생각합니다. |
| [Deep Learning Book (Ian Goodfellow)](https://www.deeplearningbook.org/) | 2.5 | GAN의 아버지, Ian Goodfellow 주도로 작성된 명서입니다. 영어에 어려움이 없으시다면, 해당 책을 꼭 읽어보시길 권합니다. |
<br/>

### Natural Language Processing 
| source | level | description |
|---|:---:|---|
| 밑바닥부터 시작하는 딥러닝2 | 2.5 | 유명한 밑바닥 시리즈의 자연어 처리 버전입니다. 신경망 이론을 선수 지식으로 필요로 하기에 난이도가 살짝 있지만, 한국어로 번역된 혹은 한국어로 작성된 자연어 책 중 수준급의 책입니다. |
| 딥러닝을 이용한 자연어 처리 (Kyunghyun Cho) | 2 | GRU로 유명한 조경현 교수님이 D2 캠퍼스에서 강의하신 자연어 처리 강의입니다. 딥러닝 지식에 대한 복습 이후, 자연어 처리를 개괄적으로 설명해주기 때문에 딥러닝 기본 지식이 선수 지식으로 필요합니다. |
| [Neural Network Methods for NLP (Yoav Goldberg)](https://www.morganclaypool.com/doi/abs/10.2200/S00762ED1V01Y201703HLT037) | 3.5 | Yoav Goldberg가 작성한 딥러닝을 이용한 자연어 처리 전문 서적입니다. 위트있는 설명으로 핵심을 잘 짚어주는 명서입니다. |
| [CS224N (Chris Manning)](https://www.youtube.com/watch?v=8rXD5-xhemo&list=PLoROMvodv4rOhcuXMZkNm7j3fVwBBY42z) | 3.5 | Stanford 대학의 자연어 처리 명강의입니다. 2019년 버전까지 나왔기 때문에 최신 트렌드까지 다룬다는 큰 장점이 있습니다. |
| [CS224U (Christopher Potts)](https://www.youtube.com/watch?v=tZ_Jrc_nRJY&list=PLoROMvodv4rObpMCir6rNNUlFAn56Js20) | 3.5 | 올해 신설된 것으로 보이는 자연어 이해 강의입니다. CS224N 이후 수강하면 좋을 것 같아보이며, PyTorch로 과제를 제공한다는 점이 매력적입니다. |
<br/>

## Libraries related to Natural Language Processing
| source | description |
|---|---|
| [NumPy Tutorial](http://cs231n.github.io/python-numpy-tutorial/) | 머신러닝 연산에 필수적으로 사용되는 NumPy를 Stanford CS231N 강좌에서 정리해주었습니다. |
| [PyTorch Tutorial](https://pytorch.org/tutorials/) | Facebook이 제공하는 PyTorch Tutorial로 현존하는 튜토리얼 중 최고의 퀄리티를 자랑합니다. |
| [spaCy Tutorial](https://course.spacy.io/) | 최근 자연어 처리 분야에서 각광을 받고 있는 spaCy의 핵심 개발자 Ines가 작성한 튜토리얼입니다. |
| [NLTK Tutorial](https://datascienceschool.net/view-notebook/118731eec74b4ad3bdd2f89bab077e1b/) | 김도형 박사님이 제공하는 NLTK 튜토리얼로 보기도 편하며, 내용도 알찹니다. |
| KoNLPy | |
<br/>

## AWE-SOME blogs
| blog | article you should read |
|---|:---:|
| [Christopher Olah's Blog](https://colah.github.io/) | [Understanding LSTM Networks](https://colah.github.io/posts/2015-08-Understanding-LSTMs/) |
| [Jay Alammar's Blog](http://jalammar.github.io/) | [Illustrated Word2vec](http://jalammar.github.io/illustrated-word2vec/) |
| [Sebastian Ruder's Blog](http://ruder.io/) | [Tracking Progress in Natural Language Processing](https://nlpprogress.com/) |
| [김현중님 블로그](https://lovit.github.io/) | [Unsupervised tokenizers in soynlp project](https://lovit.github.io/nlp/2018/04/09/three_tokenizers_soynlp/) |
<br/>

## Communities
- [Tensorflow Korea](https://www.facebook.com/groups/TensorFlowKR/)
- [PyTorch Korea](https://www.facebook.com/groups/PyTorchKR/)
- [Keras Korea](https://www.facebook.com/groups/KerasKorea/)
- [Reinforcement Learning Korea](https://www.facebook.com/groups/ReinforcementLearningKR/)
- [AI Robotics Korea](https://www.facebook.com/groups/airoboticskr/)
- [모두의 연구소](http://home.modulabs.co.kr/)
- [바벨피쉬](https://www.facebook.com/groups/babelPish/)
- [GDG Seoul](https://www.facebook.com/groups/gdgseoul/)
- [GDG Pangyo](https://www.facebook.com/groups/gdgpangyo/)
<br/>

## NLP Specialsts You should remember
*not enumarted by rank*

| name | description | known for |
|---|---:|:---:|
| Kyunghyun Cho | Professor @NYU | [Attention](https://arxiv.org/abs/1409.0473) |
| Yejin Choi | Professor @Washington Univ. | [Grover]() |
| Yoon Kim | Ph.D Student @Harvard Univ. | [CNN for NLP](https://www.aclweb.org/anthology/D14-1181) |
| Yoav Goldberg | Professor @Bar Ilan Univ. | [Neural Net Methods for NLP](https://www.morganclaypool.com/doi/abs/10.2200/S00762ED1V01Y201703HLT037) |
| Chris Manning | Professor @Stanford Univ. | [CS224N](https://www.youtube.com/watch?v=8rXD5-xhemo&list=PLoROMvodv4rOhcuXMZkNm7j3fVwBBY42z) |
| Richard Socher | Researcher @Salesforce | [Glove](https://www.aclweb.org/anthology/D14-1162) |
| Sebastian Ruder | Researcher @DeepMind | [NLP Progress](https://nlpprogress.com/) |
| Tomas Mikolov | Researcher @FAIR | [Word2vec](https://papers.nips.cc/paper/5021-distributed-representations-of-words-and-phrases-and-their-compositionality.pdf) |
| Quoc V. le | Researcher @Google Brain | [Doc2vec](https://cs.stanford.edu/~quocle/paragraph_vector.pdf) |
| Graham Neubig | Professor @CMU | [Neural Nets for NLP lec](https://www.youtube.com/watch?v=pmcXgNTuHnk&list=PL8PYTP1V4I8Ajj7sY6sdtmjgkt7eo2VMs) |
| Thomas Wolf | Lead Engineer @Hugging face | [pytorch-transformers](https://github.com/huggingface/pytorch-transformers)
| Kyubyong Park | Researcher @Kakao Brain | [Paper implementation & NLP with Korean language](https://github.com/Kyubyong) |
| Minjoon Seo | Researcher @Clova AI | [QA research](https://seominjoon.github.io/) |