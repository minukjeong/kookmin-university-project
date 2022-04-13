opencv와 keras 그리고 resnet50을 사용하여 만든 마스크 감지 AI 프로그램 입니다.
마스크를 착용했을땐 mask로 인식되고 마스크 미착용시 nomask로 인식되며
nomask로 인식 될 시 "마스크를 써주세요" 라는 경고음과 함께 공공데이터 포털에 등록된 코로나 현황 자료를 이용하여 카카오톡 메세지로 확진자
사망자 등 정보를 제공하는 서비스 입니다.
카카오톡 메세지 발송 기능은 카카오톡 openapi 기능을 사용하였고 일주일마다 토큰이 리셋되어 새로 토큰을 발급받아야 하는 불편한 점이
있습니다.


본 프로젝트에 사용된 데이터
https://github.com/chandrikadeb7/Face-Mask-Detection/tree/master/dataset

withmask 와 withoutmask에 저장된 데이터들을 
