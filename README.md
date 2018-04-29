
:full_moon_with_face: ***Deep Learning Lab까지 계속 추가하는 중이고,이후에는 Reinforcement Learning도 작업 할 예정입니다.***

## TensorFlow Machine Learning Lab using IBM Watson Studio ##

 * 본 문서는 Tensorflow 를 활용한 machine learning 학습을 위한 Lab notebook을 제공합니다.
 * 원본 소스 화일들은 김성훈 교수님의 [DeepLearningZeroToAll](https://github.com/hunkim/DeepLearningZeroToAll) 에서 가져왔습니다.
 * .py 확장자를 가진 Python script 들을 [IBM Watson Studio](https://console.bluemix.net/catalog/services/watson-studio) notebook으로 전환했습니다.
 * 각 notebook에  한글 comment는 제가 스터디하면서 추가한 내용으로 저와 같은 초보자들의 이해를 돕기 위함입니다. 
 * 궁금한 사항이나 Watson Studio Project 공유를 원하시는 분은 메일 주세요. (parkhsu@kr.ibm.com)

----------
:paw_prints:*`lab-01-basics `* : TensorFlow 기초적인 개념을 설명합니다.

:bouquet:*`lab-02-1-linear_regression `* :	선형회귀를 매뉴얼로 구현합니다.   

:cherry_blossom:*`lab-02-1-linear_regression_plot `* : 선형회귀 모델링 결과를 plot 그래프로 그려봅니다.   

:tulip:*`lab-02-2-linear_regression_feed `* : input 값을 변수 처리했다가 실제 run 할때 받아들이는 테스트입니다.   

:four_leaf_clover:*`lab-03-1-minimizing_cost_show_graph `* : cost값이 어떻게 변화하는 지 그래프로 그려서 이해합니다.   

:rose:*`lab-03-2-minimizing_cost_gradient_update `* : 경사하강법 공식을 수작업으로 만들어 봅니다.   

:sunflower:*`lab-03-3-minimizing_cost_tf_optimizer `* : 최소 시작점이 되는 W 값을 변화시켜 경사하강의 개념을 이해합니다.   

:hibiscus:*`lab-03-3-minimizing_cost_tf_optimizer_IRIS `* : IRIS 데이터를 가지고 learning 을 수행합니다.   

:maple_leaf:*`lab-04-1-multi_variable_linear_regression `* : 다변량 값으로 선형회귀를 실습합니다.           	

:leaves:*`lab-04-2-multi_variable_matmul_linear_regression.py `* : 다변량 처리를 matrix 로 구성해서 소스를 간략히 합니다.       

:fallen_leaf:*`lab-04-3-file_input_linear_regression `* : 이제는 input data를 화일로 읽어들입니다. (Numpy 이용)       
   
:herb:*`lab-05-1-logistic_regression`* : 로그함수로 처리해서 0 or 1로 분류합니다.

:mushroom:*`lab-05-2-logistic_regression_diabete `* : 당뇨병 데이터를 가지고 yes/no 를 판별합니다.

:cactus:*`lab-06-1-softmax_classifier`* : 2개 이상의 그룹으로 분류하기 위한 함수를 배웁니다.

:palm_tree:*`lab-06-2-softmax_zoo_classifier`* : 7개의 class, 여기서는 7개 동물군을 예측하는 예제입니다.  

:evergreen_tree::*`lab-07-1-learning_rate_and_evaluation`* : LR의 의미를 배우기 위해서 여러값으로 변형해서 실행해봅니다.  

:deciduous_tree:*`lab-07-2-linear_regression_without_min_max`* : X 값이 너무 편차가 클때는 learning 이 잘 안됩니다.

:chestnut:*`lab-07-3-linear_regression_min_max`* : 이때는 표준화 작업을 거쳐서 데이터를 pre-processing이 필요합니다.

:seedling:*`lab-08-tensor_manipulation `* : tensor 에 대한 기초적인 핸들링 방법을 배웁니다.

----------

:blossom:*`lab-09-1-xor`* : Deep Learning 에 들어가지 앞서서 그 역사에 해당하는 xor 문제를 풀어봅니다.

:ear_of_rice:*`lab-09-2-xor-nn `* : Neural network 으로 xor 문제를 해결합니다.

:shell:*`lab-09-3-xor-nn-wide-deep`* : 4개 layer를 가진 NN으로 돌려서 더 좋은 결과를 얻습니다. 

:globe_with_meridians:*`lab-09-4-xor_tensorboard `* : tensorboard를 활용하여 tensorflow 가 어떻게 작동하는지 봅니다.


----------
* 아이콘 모음
:sun_with_face:
:full_moon_with_face:










