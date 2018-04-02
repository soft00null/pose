conda create -n mahesh_pose python=3.6 pip

conda activate mahesh_pose

pip install -r requirements.txt

pip install --ignore-installed --upgrade tensorflow-gpu


pip install opencv_python-3.4.1-cp36-cp36m-win_amd64.whl


python src\run_webcam.py --model=mobilenet_thin --resolution=432x368 --camera=0


