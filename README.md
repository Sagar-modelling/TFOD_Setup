# Setup for custom object detection model using the Tensorflow Object Detection API.

### Steps for Installation

Create a virtual environment.
Install Visual c++ Build Tools [here](https://visualstudio.microsoft.com/vs/community/).

Install appropriate CUDA and cuDNN verisons [here](https://www.tensorflow.org/install/source)


<b>Step 1.</b> Create a new virtual environment 
<pre>
conda create -n tfod python=3.7 -y
</pre> 
<br/>
<b>Step 2.</b> Activate your virtual environment
<pre>
conda activate tfod
</pre>
<br/>
<b>Step 3.</b> Install dependencies and add virtual environment to the Python Kernel
<pre>
python -m pip install --upgrade pip
pip install ipykernel
python -m ipykernel install --user --name=tfod