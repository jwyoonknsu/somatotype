# somatotype
디지털 데이터를 활용한 체형분류 모델입니다. 샘플로 제공된 'somatotype_pred.csv' 파일에 데이터를 입력하면 내배엽, 중배엽, 외배엽이 자동 산출됩니다. 코드작성 버전은 다음과 같습니다. Python 3.11.2 TensorFlow 2.13.0 pandas 2.0.3

파일구성

somatotype.ipynb #체형분류 모델 활용
my_somatotype.keras #학습된 체형모델 가중치
somatotype_pred.csv #예제 csv파일로서 내배엽, 중배엽, 외배엽 값이 비어있음.
somato_cart.jpg #체형분류 차트 이미지 *위 파일들이 동일한 폴더에 두고 실행해야 합니다.
