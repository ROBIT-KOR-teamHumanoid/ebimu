# ebimu with ros2


- quaternion -> euler
- gui
- 값 이상할 시 EBTerminal로 e2box imu 설정 다시하기

SUBSYSTEM=="tty", ATTRS{idVendor}=="0403", ATTRS{idProduct}=="6014", MODE:="0666",SYMLINK+="ttyUSB-U2D2"
ACTION=="add", SUBSYSTEM=="tty", ATTRS{idVendor}=="10c4", ATTRS{idProduct}=="ea60",MODE:="0666", SYMLINK+="ttyUSB-EBIMU"
