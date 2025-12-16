# COSE362ML_24
## 본 프로젝트 코드는 Google Colab 환경을 전제로 작성되었습니다.
- demo.ipynb를 Google Colab 환경에서 실행
- 라이브러리 설치 후 세션 재시작(출력문의 RESTART SESSION 클릭)
- 세션 디렉토리에 All_pose_classifier_keras.h5 업로드
- 모든 셀 순차적으로 실행
- 최하단 셀 실행문에 영상과 자세 평가가 출력됩니다(안되는 경우 브라우저 권한 확인 후 셀 재실행)

demo.ipynb는 최종 모델 실행을 위한 간략화된 코드입니다.
./test.ipynb를 Google Colab에서 실행해 비교 모델들과 피쳐 조합을 실험해볼 수 있습니다. 모든 checkpoint 파일들은 ./checkpoints 폴더에서 확인할 수 있습니다.
데이터셋 생성 코드와 생성된 데이터셋은 ./data 폴더에서 확인할 수 있습니다. 해당 데이터셋을 활용해 ./model_codes 폴더의 코드들에서 비교 모델들의 학습 및 검증 평가가 가능합니다.