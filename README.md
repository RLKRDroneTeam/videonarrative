# videonarrative
2021 한국어 질의응답 AI 경진대회: 비디오 네러티브 질의응답 태스크 baseline 환경 http://ai-competition.kaist.ac.kr/

* 실제 트레이닝 환경(requrements.txt는 무시)<br/>
pip_list.txt 참고

* 트레이닝/검증 데이터 적용 방법<br/>
본 폴더 기준으로 data\video-narr\  폴더를 만든 후, 
그 안에 video-narr_motion_feat.h5 (트레이닝 데이터)와 검증 데이터(압축 파일 해제)를 투입

* 트레이닝/검증 방법<br/>
train.py 실행 시 훈련 시작 및 results\ckpt 폴더에 model.pt(모델 파일) 자동 생성, validate.py 실행 시 생성된 모델로 검증작업 수행 후 test_preds.json 파일 생성
