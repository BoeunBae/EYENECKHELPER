# EYENECKHELPER

안구건조증, 거북목증후군을 예방하기 위한 시스템

-EYE HELPER (안구건조증 예방 시스템 모드_눈을 자주 깜박여 안구건조증을 예방할 수 있는 습관을 기를 수 있도록 눈 깜박임 횟수를 측정하는 기능)

1. 노트북 상단의 카메라를 이용하여 사용자의 얼굴 및 눈을 인식합니다.

2. 1분 동안 눈 깜박임의 횟수를 측정하여 10회 이상의 깜박임이 감지되면 이어서 1분 동안 눈 깜박임의 횟수를 측정합니다.

3. 1분 동안 눈 깜박임의 횟수가 10회 이하이면 눈이 건조하다는 경고창을 사용자의 화면에 띄어줍니다.

4. 경고창에서 사용자에게 사용여부를 묻고 사용자가 원하면 계속해서 1분 동안 깜박임의 횟수를 측정합니다. 사용자가 원하지 않을 땐 시스템이 종료됩니다.

-NECK HELPER (거북목증후군 예방 시스템 모드_노트북 받침대를 사용자가 원하는 높이에 맞게 자동으로 조절하여 거북목증후군을 예방하는 기능)

1. 노트북 상단의 카메라를 이용하여 사용자의 얼굴을 인식합니다.

2. 화면 나뉘어진 위치로 얼굴을 움직임으로써 노트북 받침대의 높낮이가 움직여 사용자가 가장 편하게 느끼는 높이로 설정할 수 있습니다.

3. 한 번 설정한 높이는 NECK HELPER 모드를 다시 사용할 때까지 움직이지 않습니다.

*eyeneckhelper.py파일은 테스트하는 동안 시간을 단축시키기 위해 1분이 아닌 10초동안 눈 깜박임을 측정하는 코드입니다.

# 개발환경

window 10 (x64)

OpenCV 2.4.10

Python 3.6(Spyder)

Arduino - Sketch


