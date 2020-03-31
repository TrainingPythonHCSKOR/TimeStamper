# TimeStamper 

TFT 내의 신입사원 Script Training Project로서 진행한 TimeStamper 입니다. 

GUI를 통해 실행 및 중지 가능하며, Excel 파일로 기록됩니다. 

해당 프로젝트는 python training을 목적으로 하며, 이후 출입문 기록을 통한 workload 산출 script project로 확장 될 예정입니다.

## Project Manifest

TimeStamper.exe  : pyinstaller로 구성한 실행 파일입니다.

TimeStamperUi.py : pyqt designer로 구성한 .ui 파일을 .py 파일로 변환한 파일입니다. 

TimeStamper.py   : UI 슬롯 연결 및 기능 구현을 한 파일입니다.

resource_rc.py   : UI 내에 들어가는 icon을 위한 resource 파일입니다.

## Getting Started

Harman Logo의 'TimeStamper' .exe 프로그램을 실행합니다.

Detect mouse/keyboard 중 원하는 장치에 체크한 후 Start 버튼을 누르시면 실행합니다.

Start Time은 프로그램 동작 이후, 그 날 처음으로 키보드나 마우스 동작을 한 시간이 기록됩니다.

End Time은 프로그램 동작 이후, 그 날 마지막으로 키보드나 마우스 동작을 한 시간이 기록됩니다.

Working Time 은 Start Time과 End Time의 차이를 기록합니다.

최소화 버튼으로 트레이 아이콘으로 들어가며, 우클릭 시 종료 혹은 GUI 창을 띄웠을 때 X 버튼으로 종료 가능합니다.

## Authors

신민주 사원 ( Minju.Shin2@harman.com )

최민재 사원 ( Minjae.Choi@harman.com )

## BUGS

## ChangeLog

TimeStamper.exe 


