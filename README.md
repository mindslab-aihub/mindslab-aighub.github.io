
# AI HUB github.io

#### 1. AI HUB 페이지 안내

    - 페이지 구성 및 무슨 페이지인지 ?


#### 2. DATA 안내

    - Train Data (약 25만건)
    - Validation Data (약 5만건 - codalab 오류로 데이터 줄여야함)


#### 3. 평가파일 안내

    - Evaluation (평가)에 사용되는 python 파일 제공
    - 제공된 파일 실행 방법 안내
    - 평가파일에 필요한 임시 테스트 파일 제공
---


# Codalab WorkSheet 작성
#### 1. Validation Set 평가(임시 테스트)

- LeaderBoard 등재 전 **AI HUB github.io** 에서 주어진 파일로 테스트


    - codalab 튜토리얼을 숙지하였다는 전제조건하에 작성
    - WorkSheet에 AI HUB github.io에서 제공되는 train.json(으)로 학습된 모델 등록
    - WorkSheet에 학습된 모델로 user_prediction.json 생성 후 등록
    - user_prediction.json 은 WorkSheet에 AI HUB github.io에서 제공되는 sample_prediction.json 형식과 같아야함
    - AI HUB WorkSheet 번들에 있는 macro를 통해 user_prediction.json 평가
    
#### 2. Test Set 평가 (LeaderBoard 등재)

- LeaderBoard 에 등재하기 위한 절차


    - codalab 튜토리얼을 숙지하였다는 전제조건하에 작성
    - LeaderBoard 등재에 일정시간 소요됨을 공지
    - AI HUB github.io에서 제공되는 train.json(으)로 학습된 모델과 prediction.json을 생성하는 실행 코드를 upload
    - 참고사항으로 https://worksheets.codalab.org/worksheets/0xa55e9737f8bf44bf8d90c3a28719081f/ 혹은 https://github.com/graykode/KorQuAD-beginner 제공 
    - WorkSheet에 올릴 양식이나 구조 설명
    - validation.json 으로 prediction.json 을 생성후 upload
    - prediction.json 생성하는 프로그램에 대해 번들 생성
    - LeaderBoard 에 등재될 이름 지정 후 해당 번들의 링크를 e-mail 로 전송
    - e-mail 은 임시로 지정
    - 시간이 걸린다는 것을 재공지                                                                                                                                                   
                                                                                                                                                
# mindslab-aihub.github.io
