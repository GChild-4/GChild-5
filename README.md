# 🧚 GChild-5
- 노인과 양방향적 의사소통을 가능하게 함으로써, 노인 우울, 외로움을 해결하고 주기적으로 건강을 확인하는 반려로봇 제작 프로젝트

### Project Problem Statement
달콩이는 독거노인의 말벗이 되어줄 뿐만 아니라 다양한 기능을 구현하여 노인 우울 및 불안, 외로움을 해소시켜주는 반려 로봇이다. 본 디바이스를 활용하였을 때 노인을 심리 정서적으로 안정시킬 수 있으며, 위험에 대한 대비를 가능하도록 하고, 보호자가 노인에 대한 정보를 쉽게 접근할 수 있도록 한다. 
#### Functuonal Requirement
1. 대화
</br>달콩이는 노인과 양방향적 의사소통을 가능하게 하고, 독거 노인분들의 말동무가 되어서 우울감과 외로움을 해결하기 위해 일상적 대화를 수행하는 기능을 가지고 있다. 노인이 말을 걸면 스피커를 이용하여 음성을 인식하고 정해진 대화 매뉴얼에 따라 대답을 하면서 의사소통이 가능하도록 한다.

2. 시선관찰
</br>달콩이는 사람의 움직임을 인식하는 카메라를 사용하여 노인을 따라다니면서 집 안에서의 노인의 움직임을 관찰한다. 만약 노인의 움직임이 포착되지 않거나 외출을 하는 경우에는 어플리케이션을 통해 보호자에게 알림을 전송한다.

3. 의료비대면관찰
</br>COVID-19의 영향으로 사회 각 분야에 비대면 기술과 서비스가 확대되고 있는 것을 바탕으로 비대면 의료 서비스를 제공한다. 노인과 달콩이의 자연스러운 대화 도중 몸이 불편하거나 아프다는 내용을 데이터로 축적 시키고 일정 한계치를 초과할 경우 보호자에게 알림을 전송 시켜 도움을 요청한다.

4. 게임
</br>달콩이의 신체 일부를 눌렀을 때 달콩이와 끝말잇기, 초성 게임, 속담 맞추기 등 간단한 의사소통 게임을 진행 할 수 있다. 이를 통하여 기억력, 스피드, 정확도, 추론 능력 등 다양한 인지 능력을 자극 시킴으로써 노인들의 치매를 예방할 수 있도록 한다. 게임으로 일상생활에 필요한 학습능력이나 상황 이해력, 문제해결능력을 강화시키는데 도움을 준다. 디지털기기에 익숙하지 않은 어르신들의 눈높이에 맞추어 개발하여 근력이나 인지능력이 떨어지는 노인도 쉽게 참여할 수 있다.

5. 정서 안정
</br>달콩이의 왼팔, 오른 다리 등 신체 일부분을 누르면(터치 센서) 명상을 할 수 있도록 한다. 이때 명상은 단순히 음악을 틀어주는 것이 아닌 노인을 위한 호흡 법 및 신체에 오로지 집중할 수 있는 코멘트 등을 함께 가이드해준다. 명상을 통해 노인의 뇌에 긍정적 변화를 일으켜 정서를 안정시키고 스트레스를 완화한다.

6. 일정 관리
</br>노인 또는 보호자가 병원, 투약 일정 등을 반려 로봇에 사전에 입력할 경우 시간이 되면 알림을 울려 주요 일정을 잊지 않도록 한다. 이때 일정은 음성 인식 혹은 어플리케이션리케이션을 이용하여 등록할 수 있으며, 구체적인 시간까지 입력 받는다. 일정 변경 역시 같은 방식으로 가능하도록 한다.

#### Nonfunctuonal Requirement
  #### Quality requirement
  #### - Supportability
  어플리케이션 제작 시 사용자에 따라 이용을 분리하여 설계하여 새로운 사용자 추가가 용이하다.
  #### Constraints or Pseudo requirement
  #### - 제작 될 어플리케이션은 Java와 호환성이 좋으며 문법이 간결하고 컴파일이 빠르게 이루어진다는 점에서 Kotiln을 사용하여 작성한다.
  #### - 프로젝트에 제작 될 웹 프레임워크(서버)는 가벼우며 개발자 자유도가 높기 때문에 Flask를 이용한다.

### 🧸 팀구성원
- 조장 : 이채영
- 방희연, 서현주, 이승재, 조수빈

### 🧸 각 멤버 역할과 역량

|Participant|Roles|Skills|Training needs|
|:---:|-----------|---|---|
|이채영|Team leader, <br/>Backend Developer|Programming : Python, Java, C <br/>Github <br/>Django, Android Studio|UML, Flask|
|방희연|Android Developer, <br/>Configuration manager|Programming : Python, Java, C, HTML <br/>Database : sql|UML, Kotlin|
|이승재|Android Developer, <br/>Tester|Programming : Java, C, Python|UML, Kotlin|
|서현주|Embedded developer, <br/>Facilities management|Programming: Python, Java, C|UML|
|조수빈|Embedded developer, <br/>Document editor|Programming: Python, Java, C|UML|
