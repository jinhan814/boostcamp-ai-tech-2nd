# Deep Learning Basics

- ## 1. Historical Review
  
  - 딥러닝에 대한 소개: CNN(Convolutional neural networks), RNN(Recurrent Neural Networks)와 같은 딥러닝 모델을 공부하기 전 중요한 요소인 Data, Model, Loss, Optimization algorithms에 대해 배웁니다.

  - 딥러닝의 역사: 2012년부터 2021년까지의 패러다임에 대해 배웁니다.
  
  - Further Reading
    
    - [A Brief Historical Review _ Denny Britz](https://dennybritz.com/blog/deep-learning-most-important-ideas/)

<br>

- ## 2. Neural Networks & Multi-Layer Perceptron
  
  - 신경망(Neural Networks): 간단한 Linear neural network 를 예시로 Data, Model, Loss, Optimization algorithm 을 정의해보는 시간을 가집니다.
  
  - Deep Neural Networks: Deep Neural Network란 무엇이며 Multi-layer perceptron와 같이 깊은 네트워크는 어떻게 구성하는지에 대해 배웁니다.
  
  - Neural networks are function approximators that stack affine transfrmations followed by nonlinear transformations.
  
  - Universal Approximation Theorem
    
    - There is a single hidden layer feedforward network that approximates any measurable function to any desired degree of accuracy on some compact set K.
    
    - Caution: It only guarantees the existence of such networks.
  
  - Multi-Layer Perceptron 실습

    - https://github.com/sjchoi86/upstage-basic-deeplearning/blob/main/notebook/mlp.ipynb
  
  - Further Reading
    
    - [pytorch docs _ nn](https://pytorch.org/docs/stable/nn.html#)

<br>

- ## 3. Optimization Methods
  
  - Keywords : Generalization, Overfitting, Cross-validation

  - 다양한 Gradient Descent 기법: 기존 SGD(Stochastic gradient descent)를 넘어서 최적화(학습)가 더 잘될 수 있도록 하는 다양한 기법들에 대해 배웁니다.

  - Convex optimization, Non-Convex optimization

    - [Convex optimization](https://wikidocs.net/17206)

  - K-Fold (Cross-validation)

  - Bootstrapping
    
    - Bagging (Bootstrap aggregating)

    - Boosting
  
  - Gradient Descent Methods
    
    - Stochastic, Mini-batch, Batch gradient descent
      
      - Batch-size Matters

      - [On Large-Batch Training for Deep Learning: Generalization Gap and Sharp Minima](https://arxiv.org/abs/1609.04836)

    - SGD, Momentum, Nesterov accelerated gradient, Adagrad, Adadelta, RMSprop, Adam

  - Regularization
    
    - Early stopping

    - Parameter norm penalty

    - Data Augmentation

      - rotate, flip, ...

    - Noise robustness

    - Label smoothing

      - Mixup, Cutout, Cutmix, ...
    
    - Dropout

    - Batch Normalization

      - [Batch Normalization: Accelerating Deep Network Training by Reducing Internal Covariate Shift](https://arxiv.org/abs/1502.03167)

  - Optimization 실습
    
    - https://github.com/sjchoi86/upstage-basic-deeplearning/blob/main/notebook/optm.ipynb
  
  - Further Reading
    
    - [RAdam Github](https://github.com/LiyuanLucasLiu/RAdam)
    
    - [AdamP Github](https://github.com/clovaai/AdamP)

<br>

- ## 4. Convolutional Neural Networks
  
  - CNN에 대한 공부를 하기 전에 Convolution의 정의, convolution 연산 방법과 기능에 대해 배웁니다.
  
  - Convolution, 입력을 축소하는 Pooling layer, 모든 노드를 연결하여 최종적인 결과를 만드는 Fully connected layer 로 구성되는 기본적인 CNN(Convolutional Neural Network) 구조에 대해 배웁니다.

  - Convloutional Neural Network 실습

    - https://github.com/sjchoi86/upstage-basic-deeplearning/blob/main/notebook/cnn.ipynb
  
  - Further Reading
    
    - [cs231n - Lecture 7: Convolutional Neural Networks](https://www.youtube.com/watch?v=LxfUGhug-iQ)

<br>

- ## 5. Modern CNN
  
  - ILSVRC 대회에서 수상을 했던 5개 Network 들의 주요 아이디어와 구조에 대해 배웁니다.

  - Network List

    - AlexNet

      - 최초로 Deep Learning을 이용하여 ILSVRC에서 수상

    - VGGNet

      - 3x3 Convolution을 이용하여 Receptive field는 유지하면서 더 깊은 네트워크를 구성

      - [Receptive field 참고 자료](https://cs231n.github.io/convolutional-networks/#conv)

    - GoogLeNet

      - Inception block을 제안

    - ResNet

      - Residual connection(Skip connection)이라는 구조를 제안

      - h(x) = f(x) + x의 구조

    - DenseNet

      - Resnet과 비슷한 아이디어지만 Addition이 아닌 Concatenation을 적용한 CNN

  - [pytorch docs _ models](https://pytorch.org/vision/stable/models.html)

<br>

- ## 6. Computer Vision Applications
  
  - 

<br>

- ## 7. Recurrent Neural Networks
  
  - 

<br>

- ## 8. Transformer
  
  - 

<br>

- ## 9. Generative Models
  
  - 
