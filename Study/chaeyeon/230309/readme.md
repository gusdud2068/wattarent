# today what I do

#### 1. 특화 PJT 중간발표 준비

- ROS 개념 공부 및 대본 작성

ROS 통신

메세지 통신(Topic으로) --> Topic : 이름, 내용, type 존재

publish, subscribe 방식

노드간 통신, 마스터(roscore 실행) 존재해야 함, 시뮬레이터 연동시 rosbridge 실행

```
[ROS - 대본]
ROS는 로봇 소프트웨어를 구현하기 위한 SW 프레임워크로, 로봇을 개발하는데 있어 필수적인 라이브러리를 제공합니다.
ROS에서 가장 중요하게 생각하는 부분은 ROS 통신입니다. ROS 통신이 가능해야 자율주행에 있어 필수적인 센서 데이터 값을
송수신하여 원하는 기능을 개발할 수 있기 때문입니다. 
지금부터 ROS 통신에 대해 설명드리도록 하겠습니다. ROS 통신은 메세지를 통해 데이터를 전송하며, 
크게 다음과 같은 구조를 가지고 있습니다.(ROS arch)
여러 개의 노드들이 마스터에 등록되며 데이터를 송수신합니다. 여기서 말하는 노드는 ROS에서
실행되는 최소단위 프로세스로 차량, 신호등, 도로 등의 객체를 의미합니다. 이러한 노드들이 통신하기 위해서는
topic이 필요하며, 노드들간 약속된 topic 으로 메세지를 publish, subscribe하는 방식으로 데이터를 송수신합니다.
요약하면, ROS 통신은 마스터에 등록된 노드들간 메세지 형태로 데이터를 송수신하는 방식이라 말할 수 있습니다.
실제 시뮬레이터와 ROS간 통신에서는 그림과 같이 ROS bridge가 마스터 역할을 수행하며, Morai와 개발환경을 연결해줍니다.
```

#### 2. 특화 PJT 전문가 리뷰

- 프로젝트 기획, 사전질문 등을 바탕으로 발표 진행

- 피드백 (.word 파일 참고)
