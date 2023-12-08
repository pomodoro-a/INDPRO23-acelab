# 한밭대학교 SW중심대학 산학연계프로젝트 - 거리 정도만을 이용하여 군집 노드의 상대 측위 인공지능 기술 개발

## 팀구성

### 지도교수
* 정의림 교수님

### 기업체
* 이창석 대표

### 참여학생
* 30221059 오정은
* 30221060 이민아
* 30221061 조아민
* 30221062 허유라
* 20221044 김내경
* 20221059 이상현

### Project Background
* 필요성
    * 실내 군집 이동체의 경로 최적화 및 충돌 회피를 위해 로봇들이 서로의 좌표를 정확하게 파악하는 것이 중요
* 기존 해결책의 문제점
    * 실내 군집 노드 (이동체)의 측위는 중요한 문제
    * GPS 신호의 수신이 어려운 건물 내부나 지하 공간에서는 GPS를 통한 측위에 어려움이 있음

### System Design
* System Requirements
   * 상대 측위 연구 및 성능 평가

### Case Study
* Description
     * 본 과제에서는 거리 정보만을 이용한 상대 측위 연구를 수행함
     * 상대 측위란 군집 이동체 간의 거리 정보를 의미
     * 
* Method
     * 노드 사이 거리를 이용한 Rule-based 알고리즘 개발
        * ![image](https://github.com/pomodoro-a/INDPRO23-acelab/assets/153184149/079a9487-a4c8-477f-bf02-ab7d1a7ce6ee)
        * 제한된 영역 내의 노드에서 설정한 개수만큼 좌표축을 나누어, 최적의 좌표를 추정
     *  노드 사이 거리를 이용한 인공지능 알고리즘 개발
        * ![image](https://github.com/pomodoro-a/INDPRO23-acelab/assets/153184149/f13bdce3-5ec7-48bb-a602-aa0b3f367a60)
        * 노드 간의 거리 정보를 입력하여 노드의 2차원 상대 좌표를 출력하는 인공지능 설계

* Experimental Results
   * 알고리즘에 따른 상대 측위 성능 결과
      * ![image](https://github.com/pomodoro-a/INDPRO23-acelab/assets/153184149/c7d79178-c9c3-4b1f-ae96-9e947a74ba57)
 
### Conclusion
* 노드 개수와 상관없이 Rule-based 알고리즘 대비 인공지능 알고리즘의 성능이 우수한 것을 확인하였음

### Project Outcome
* OOO
