# EConTara_OrbSlam2_CheckerBoardDetector
  Repozytorium zawiera paczki do środowiska ROS Kinetic, pozwalające na uruchomienie kamery sterowizyjnej E-Con Tara. Dodatkowo zawiera pakiet zwracający informację o położeniu i orientacji planszy konfiguracyjnej w postaci x,y,z oraz kwaternionów. Rejestracja w przestrzeni trajektorii ruchu kamery odbywa się za pomocą pakietu ORB-SLAM2.
  
  
### Pakiety niezbędne do prawidłowego działania
  ```
  sudo apt-get install ros-kinetic-camera-info-manager
  sudo apt-get install libudev-dev
  sudo apt-get install libv4l-dev
  sudo apt-get install ros-kinetic-rqt-image-view
  ```
  
  Pangolin:
  https://github.com/stevenlovegrove/Pangolin
  
  Eigen3:
  https://github.com/OPM/eigen3
  
  
### Adresy repozytoriów, na podstawie których pracowano
  Deimos:
  https://github.com/i3drobotics/deimos-ros
  
  CheckerBoard Detector:
  https://github.com/jsk-ros-pkg/jsk_recognition
  
  ORB-SLAM2:
  https://github.com/raulmur/ORB_SLAM2
  
  
  
