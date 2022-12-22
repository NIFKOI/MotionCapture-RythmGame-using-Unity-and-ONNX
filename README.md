# MotionCapture-RythmGame-using-Unity-and-ONNX

<h3> 사용된 모션캡쳐에 더 알고싶다면 여기로 </h3>
https://github.com/digital-standard/ThreeDPoseUnityBarracuda

<h3> 원리 </h3>
ONNX를 이용한 모션 캡쳐를 통해 동영상에서 좌표값을 받아 한 캐릭터에 대입하고, 카메라의 영상을 통해 사용자의 캐릭터가 움직인다.
그 후, 사용자의 캐릭터와 동영상의 움직임에 따른 캐릭터의 좌표값의 차이를 이용해 점수를 판정한다.

따라서 ONNX를 2개 사용하므로 GPU를 GTX 1060 이상을 권장합니다.
ONNX 파일은 Tensorflow를 사용하여 제작되었으며 표준 라이브러리를 사용합니다.

유니티 2021.3.4f1 버전을 기준으로 제작되었으므로 그 이상의 버전을 권장합니다.

<h4> 찾아낸 버그들 </h4> 
개발자 모드에서 카메라를 작동시킬경우 인게임에서 카메라를 가져오지 못하는 오류 <br>
게임이 종료되고 다시 곡 선택화면으로 돌아가지 못하고 게임이 강제종료되는 오류 <br>
캐릭터의 값이 일정하지 않아 판정이 적절하지 못한 오류 <br> 

<h6> 본 프로그램은 상업적 이용을 제외한 수정, 사용을 허용합니다. </h6>
2022 SHT
