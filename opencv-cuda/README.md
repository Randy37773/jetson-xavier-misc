
for higher python version on jetson-xavier (ubuntu 18)

python3.8:

 > apt install python3.8 python3.8-env
 > sudo update-alternatives --install /usr/bin/python3 python3 /usr/bin/python3.6 1
 > sudo update-alternatives --install /usr/bin/python3 python3 /usr/bin/python3.8 2
 > python3 --version
 
 ~~ NICHT python3.8 -m venv myenv # erst mal global testen ~~
 ~~ pip install cython pybind11 cppy matplotlib numpy ~~
 pip install -r requirements.txt
 / modify build_opencv.sh oruse build_opencv-python38.sh /
 ./build_opencv-python38.sh
 
