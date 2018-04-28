# SDK-for-LPIRC-Track2
the sdk to install tensorflow and caffe2 in the Nvidia tx2. 
If you have already installed some software, e.g. python, please skip that step.

Install Tensorflow:
step 1. install pip, python2.7 and numpy: 

chmod +x step1_install_dependency.sh

sudo ./step1_install_dependency.sh


step2. install bazel

chmod +x step2_install_bazel.sh

sudo ./step2_install_bazel.sh

step3. install cuda

chmod +x step3_install_cuda.sh

sudo ./step3_install_cuda.sh

step4. install nivida version
Note that you should replace the version here with your own hardware version

sudo apt-get install -y nvidia-version-*

step4. install docker

chmod +x step4_install_docker.sh

sudo ./step4_install_docker.sh


step5. install tensorflow

chmod +x step5_install_tf.sh

sudo ./step5_install_tf.sh

Valid your installation:

python test.py
