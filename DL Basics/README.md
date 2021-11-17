# Deep Learning Basics

- ## Historical Review
  
  - 딥러닝에 대한 소개: CNN(Convolutional neural networks), RNN(Recurrent Neural Networks)와 같은 딥러닝 모델을 공부하기 전 중요한 요소인 Data, Model, Loss, Optimization algorithms에 대해 배웁니다.

  - 딥러닝의 역사: 2012년부터 2021년까지의 패러다임에 대해 배웁니다.
  
  - Further Reading
    
    - [A Brief Historical Review _ Denny Britz](https://dennybritz.com/blog/deep-learning-most-important-ideas/)

<br>

- ## Neural Networks & Multi-Layer Perceptron
  
  - 신경망(Neural Networks): 간단한 Linear neural network 를 예시로 Data, Model, Loss, Optimization algorithm 을 정의해보는 시간을 가집니다.
  
  - Deep Neural Networks: Deep Neural Network란 무엇이며 Multi-layer perceptron와 같이 깊은 네트워크는 어떻게 구성하는지에 대해 배웁니다.
  
  - Neural networks are function approximators that stack affine transfrmations followed by nonlinear transformations.
  
  - Universal Approximation Theorem
    
    - There is a single hidden layer feedforward network that approximates any measurable function to any desired degree of accuracy on some compact set K.
    
    - Caution: It only guarantees the existence of such networks.
  
  - Multi-Layer Perceptron 실습

    - https://github.com/sjchoi86/upstage-basic-deeplearning/blob/main/notebook/mlp.ipynb
  
  - Further Reading
    
    - [pytorch official docs](https://pytorch.org/docs/stable/nn.html#)

<br>

- ## Optimization Methods
  
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

    - SGD

    - Momentum

    - Nesterov accelerated gradient

    - Adagrad

    - Aadelta

    - RMSprop

    - Adam

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

- ## Convolutional Neural Networks
  
  - 

  - Convloutional Neural Network 실습

    - https://github.com/sjchoi86/upstage-basic-deeplearning/blob/main/notebook/cnn.ipynb
  
  - Further Reading
    
    - [cs231n - Lecture 7: Convolutional Neural Networks](https://www.youtube.com/watch?v=LxfUGhug-iQ)

<br>

- ## Modern CNN
  
  - 

<br>

- ## Computer Vision Applications
  
  - 

<br>

- ## Recurrent Neural Networks
  
  - 

<br>

- ## Transformer
  
  - 

<br>

- ## Generative Models
  
  - 
