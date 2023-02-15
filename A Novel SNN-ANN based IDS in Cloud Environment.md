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
##### 클라우드는 연산력이나 저장 공간과 같은 컴퓨터 자원들을 pooling하는 아이디어의 구현이다.  
-> 서비스의 중단을 최소화하고 운영 중에 애플리케이션이 예상치 못한 resource spikes를 경험할 수 있는 사용 당 비용 방식으로 대규모 사용자 기반의 서비스를 제공하는 데 종종 사용된다.  
##### 이러한 컴퓨팅 장치는 모두 클라우드 환경의 개별적으로 필수적인 부분이다.  
-> 클라우스를 형성하는 장치가 손상된 장치를 인식하지 않는 한 유사한 패턴의 소프트웨어 구성을 따른다.  
-> 하나의 장치에 대한 손상은 전체 클라우드 서비스의 중단을 일으킬 수 있다.  
-> 해당 장치에서 수행되는 악의적인 활동을 중단시키기 위해서는 어떤 장치가 어떤 방식으로 손상되었는지 식별하는 것이 중요하다.  
##### IDS는 시스템에서 수행되는 모든 악의적인 활동을 지속적으로 모니터링한다.  
-> 호스트 기반 IDS (Host-based IDS)와 913 네트워크 기반 IDS (NIDS)로 분류된다.  
##### 본 논문에서 저자들은 NSL KDD dataset에서 침입이 발생할 때 정확하게 결정하고 침입 유형을 식별하는 IDS를 생성하기 위해 spiking neuron model과 함께 artificial neuron을 통합하는 model을 제시한다.  
-> 먼저 악성 연결과 비악성 연결을 정확하게 분류하여 ANN과 SNN의 장점을 결합한다.  
-> 그 다음 악성 연결에서 수행된 악성 활동의 유형을 확인한다.  
-> 이렇게 하면 클라우드에서 수행 중인 공격을 빠르게 확인할 수 있으므로 악의적인 연결을 검역할 수 있다.
***
### Related Works  
### Preliminary Study  
### Dataset  
### Proposed Model  

### Result and Analysis  
### Conclusion
