# A Novel SNN-ANN based IDS in Cloud Environment
### Abstract  
##### 최근 cloud-based servers에서 제공되는 서비스의 수가 급증함에 따라 이러한 플랫폼의 보안에 대한 우려 제기  
-> 시스템 관리자가 클라우드 플랫폼의 악의적인 활동을 인식/경고할 수 있는 시스템을 구축하는 것이 중요하다.  
-> 위협을 잘 이해/완화하기 위해 cloud server에 대한 공격의 종류를 아는 것이 바람직하다.  
##### ANN의 사용은 IDS에서 발견되었다.  
-> 이러한 시스템을 neural system의 생물학적 모델에 더 가깝게 만들기 위해 저자는 높은 효율의 IDS를 만들기위해 SNN을 배치하였다.  
##### SNN은 단순화된 수학 모델인 artificial neuron model보다 biological neuron을 더 가깝게 모방하는 spiking neuron을 배치한다.  
-> 저자들은 NSL-KDD dataset을 사용하여 네트워크의 악의적인 연결을 식별하고 공격 유형으로 분류하는 데 높은 수준의 정확도를 달성하는 hybrid SNN-ANN model을 제안한다.  
***
### Introduction  
클라우드는 연산력이나 저장 공간과 같은 컴퓨터 자원들을 pooling하는 아이디어의 구현이다.  
-> 서비스의 중단을 최소화하고 운영 중에 애플리케이션이 예상치 못한 resource spikes를 경험할 수 있는 사용 당 비용 방식으로 대규모 사용자 기반의 서비스를 제공하는 데 종종 사용된다.  
-> 
