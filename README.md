## CPU only PVANet: Lightweight Deep Neural Networks for Real-time Object Detection


### Installation

* Clone the Faster R-CNN repository
###### Make sure to clone with --recursive
    `git clone --recursive https://github.com/sasadep/pva-faster-rcnn.git`
   
* clone CPU only configurations settings 

	```Shell
    git clone -b cpu_only https://github.com/sasadep/pva-faster-rcnn.git cpu_pva
    ```
* copy the changed configuration files to the original *pva-faster-rcnn* directory 
	
	```Shell
    cp -R cpu_pva/* pva-faster-rcnn/
    ```
* follow same Installation procedure from step 2 in [pva-faster-rcnn](https://github.com/sasadep/pva-faster-rcnn)
