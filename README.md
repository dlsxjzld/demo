# 페르소나, 사용자 스토리를 통한 AI 프로토타이핑
### 배포 링크: https://quiz-meta-master.lovable.app
## **📌 여러분의 서비스는 누가 사용하나요?**

- 사용자는 어떤 문제를 겪고 있나요?
    - 내가 공부를 했을 때 이 지식을 진짜 알고 있는지 모른다.
    - 시험 공부를 할 때나, 배운 것에 대해 내가 진짜 알고 있는지 시험을 보기 전까지는 알기 어렵다.
- 그 문제를 해결하기 위해 어떤 해결책을 생각하고 있나요?
    - 학습한 내용을 입력하면 이를 바탕으로 퀴즈, 문제를 만든다.
        - 학습한 내용 입력 방법
            - 링크
            - pdf
            - 텍스트
    - 자주 틀린 문제를 따로 모아서 제공한다.
    - 시간이 오래 지나면 푸쉬알림을 통해 다시 학습해 보는 것 어떠냐고 여쭤보기.

## **📌 사용자로 시작하기**

- 여러 개발 프로세스의 요소를 가져와서 예시를 보여줌
- 예시 주제: 대학 축제를 더욱 편리하고 원활하게 즐길 수 있는 온라인 줄서기 및 통합 플랫폼 서비스
- 공부를 하는 모든 사람들에게 복습 및 메타인지를 제공하는 서비스

## **📌 사용자는 누구인가?**

- 서비스를 정했다면 타겟이 누구인지 알아야 하고
- 타겟의 니즈가 무엇인지 파악해야 한다
- 서비스를 이용할 사용자 역할을 예상한다

| 사용자 | 사용자 정의 |
| --- | --- |
| **학생(학생, 취준생, 이직생)** | 시험, 면접, 복습을 준비하는 사람 |

## **📌 사용자를 알아보자**

- 사용자는 무엇을 하고싶을까?

| 사용자 | 사용자 니즈 |
| --- | --- |
| **학생** | 본인이 공부한 내용을 입력하면 퀴즈를 풀어볼 수 있다. 
면접의 경우 말하면서 연습해야 한다면 음성을 인식하거나, 답변을 AI가 면접관으로써 평가하여 점수와 피드백을 제공한다. |

## **📌 페르소나를 정해보자**

- 제품 또는 서비스의 주요 사용자 그룹을 대표하는 가상의 인물
- 행동 패턴과 목표 그리고 동기가 잘 드러날 수 있는 요소를 활용
- 인터뷰, 설문조사, 데이터 분석 등을 활용하여 작성할 수 있음
- 구체적이고 생생한 인물로 묘사

| 사용자 | 페르소나 |
| --- | --- |
| **학생** | **이름**: 김민수 **나이**: 21세 **전공**: 경영학 **목표**: 시험을 준비해서 잘 보고 싶다. **니즈**: 공부한 내용에 대해 내가 잘 알고 있는지 확인 및 공부한 내용에 대한 퀴즈 및 틀린 문제 오답 노트 |
| 취준생/이직생 | **이름**: 이영희 **나이**: 27세 **역할**: 프론트엔드 취준생 **목표**: 면접에서 나올만한 질문들을 미리 준비하고 싶다. **니즈**: 면접 질문에 대한 답변 평가 및 피드백 |

## **📌 사용자 시나리오 제작하기**

- 특정 사용자가 목표를 달성하기 위해 시스템을 사용하는 과정을 이야기 형식으로 설명
- 페르소나 관점에서 작성하고 페르소나와 시스템 사이의 인터렉션을 묘사
- 사용자가 목표를 달성하기 위해 거치는 단계를 순차적으로 서술
- 가능한 한 구체적이고 현실적인 상황을 반영

## **📌 시나리오 예시**

### **학생 사용자 시나리오**

- **목표**: 시험을 준비해서 잘 보고 싶다.
- **시나리오**:
    - 다음 주에 전공 시험이 있다.
    - 공부한 내용을 문서화 했다.
    - 서비스의 메인 화면에서 복습하고 싶은 내용에 대해 퀴즈를 만듭니다.
    - 문서화 링크 혹은 pdf 파일, 혹은 텍스트를 첨부하면 퀴즈가 만들어집니다.
    - 만들어진 퀴즈에는 객관식과 주관식이 있고 퀴즈를 풀어봅니다.
    - 객관식의 경우 틀리면 오답 노트에 자동으로 저장됩니다. 주관식의 경우 문서화 내용을 바탕으로 답변을 AI가 평가해서 점수를 매기고 피드백을 제공합니다.
    
    - 다른 사람들이 제공하는 퀴즈를 북마크할 수 있습니다.
    - 가장 많이 북마크를 받거나 풀어본 퀴즈를 최상단에서 볼 수 있도록 필터링을 제공합니다.

### **취준생 사용자 시나리오**

- **목표**: 면접을 준비해서 잘 보고 싶다.
- **시나리오**:
    - 다음 주에 면접이 있다.
    - 공부한 내용을 문서화 했다.
    - 서비스의 메인 화면에서 면접 대비하고 싶은 내용에 대해 퀴즈를 만듭니다.
    - 문서화 링크 혹은 pdf 파일, 혹은 텍스트를 첨부하면 퀴즈가 만들어집니다.
    - 만들어진 퀴즈는 주관식이고 퀴즈를 풀어봅니다.
    - 주관식의 경우 문서화 내용을 바탕으로 답변을 AI가 평가해서 점수를 매기고 피드백을 제공합니다.
    - 꼬리 질문을 제공합니다.
    - 꼬리 질문에 대한 답변도 AI가 평가해서 점수를 매기고 피드백을 제공합니다.
    

## **📌 시나리오에서 요구사항 도출**

- 요구사항은 명확하고 구체적이며, 실제 사용자 요구를 반영한 효율적인 시스템 설계의 기초

| 페르소나 | 시나리오 | 요구사항 |
| --- | --- | --- |
| 학생 | 시험 준비를 하는 김민수는 노트북에서 공부한 내용을 복습하는 서비스를 실행합니다. 서비스의 메인 화면에서 퀴즈 만들기를 선택합니다. 김민수는 만드는 퀴즈의 분야를 선택하고, 만들어뒀던 문서의 링크, 혹은 pdf 파일을 첨부하거나 텍스트를 복사해서 붙여넣습니다. 퀴즈가 만들어지면 객관식과 주관식이 존재합니다. 퀴즈를 풀 때 객관식 문제의 경우 틀리면 오답 노트에 자동으로 저장됩니다. 주관식 문제의 경우 문서화 내용을 바탕으로 답변을 AI가 평가해서 점수를 매기고 피드백을 제공합니다.  | 1. 퀴즈 만들 수 있도록 문서의 링크, pdf 파일 첨부, 텍스트 입력란 기능 필요.
2. 객관식 및 주관식 퀴즈 자동생성 기능.
3. 답변 평가 및 피드백 제공 기능.
4. 오답 노트에 자동으로 저장 기능.
5. 퀴즈 끝나면 전체적인 피드백 제공하는 기능. 또한 선택한 답안 및 답변한 내용 볼 수 있는 기능. |
| 취준생 | 면접 준비를 하는 이영희는 노트북에서 면접 대비를 위해 공부한 내용을 복습하는 서비스를 실행합니다. 서비스의 메인 화면에서 면접 퀴즈 만들기를 선택합니다. 이영희는 만드는 퀴즈의 분야를 선택하고, 만들어뒀던 문서의 링크, 혹은 pdf 파일을 첨부하거나 텍스트를 복사해서 붙여넣습니다. 퀴즈가 만들어지면 주관식과 꼬리질문이 존재합니다. 퀴즈를 풀 때 주관식 문제의 경우 문서화 내용을 바탕으로 답변을 AI가 평가해서 점수를 매기고 피드백을 제공합니다. 또한 꼬리질문을 자동으로 제공하고 답변을 AI가 평가해서 점수를 매기고 피드백을 제공합니다. | 1. 퀴즈 만들 수 있도록 문서의 링크, pdf 파일 첨부, 텍스트 입력란 기능 필요.
2. 주관식 퀴즈 및 꼬리질문 여러개 자동생성 기능.
3. 답변 평가 및 피드백 제공 기능.
4. 퀴즈 끝나면 전체적인 피드백 제공하는 기능. 또한 답변한 내용 볼 수 있는 기능. |

## **📌 사용자 스토리와 인수 조건**

- **요구사항**: 퀴즈 만들 수 있도록 문서의 링크, pdf 파일 첨부, 텍스트 입력란 기능
- **사용자 스토리**: 학생으로서, 저는 공부한 내용을 복습하고 싶습니다. 그래서 공부한 내용을 잘 알고 있는지 확인할 수 있는 퀴즈를 만드는 기능이 필요합니다.
- **인수 조건**:
    - Given: 학생이 로그인하고 메인화면에서 일반 퀴즈 만들기, 면접 대비 퀴즈 만들기 버튼 및 퀴즈 목록을 보고 있습니다.
    - When: 학생이 일반 퀴즈 만들기 버튼을 선택합니다.
    - Then: 서비스는 문서화 내용을 입력할 수 있는 텍스트, 혹은 문서화 내용이 담긴 링크 혹은 pdf 문서를 첨부할 수 있는 첨부란을 보여줍니다.
