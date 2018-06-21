
 # Resources and Libraries
- Libraries:
  You can install your own libraries in your home (~) directory.
  
- Resources:
  All resources can be found in the directory: */workspace/resouces* (or on Internet :D)
  Your are also given a permission to access the folder */workspace/your_user_name* (for example: */workspace/blob*). So keep your data, models and figures in this folder and **DO NOT STORE DATA ON YOUR HOME DIRECTORY**
  P/s: the server is for computing purpose only. So we **CAN NOT RESCUE** your **DATA** in **any circumstances**. So please, **DO NOT STORE VALUABLE DATA** on **this server**. 
  
- We also put some config files of vim, tmux in */workspace/resouces/utilities* 
  You can use your own config files or simply put those config files and related folder in */workspace/resouces/utilities* into your home directory and then add `.` before those files and folder (for example: put the file *vimrc* in */workspace/resouces/utilities* into your home folder and then change the file *vimrc* to *.vimrc* )
- We installed Open JDK as default Java. If you want to use Oracle Java, you can simply access */home/hien-v/programs/jdk-10.0.1* or add */home/hien-v/programs/jdk-10.0.1/bin* to your _PATH_ variable in *.bashrc*

# Deep learning and Python
- Python:  We only support python 3+ on this server. If you still want to use python 2+, let try on your own virtualenv.
  
- Install and Usage of Deep learning frameworks: We recommend you to follow those steps for the first time of using this server:
    * Create your own virtualenv by using a command:
        * *virtualenv -p python3 your_directory_or_project*
        
    * Then run your virtualenv by using a command:
        * *source your_directory_or_project_with_full_adress*
        * example: _source /home/blob/my_project/bin/activate_
    * Install Tensorflow: Go to the folder */workspace/resouces/tensorflow* and run **one** of the following commands:
      * *pip3 install --upgrade tensorflow-1.7.0-cp35-cp35m-linux_x86_64.whl* (for tensorflow 1.7)
      * *pip3 install --upgrade tensorflow-1.8.0-cp35-cp35m-linux_x86_64.whl* (for tensorflow 1.8)
    * Install Torch: Go to the folder */workspace/resouces/pytorch* and run the following commands:
      * *pip3 install torch-0.4.0-cp35-cp35m-linux_x86_64.whl*
      * *pip3 install torchvision*
 - For other frameworks: Feel free to install other frameworks such as Caffe, Keras, etc. on your own virtualenv. Ask [@thuannm](athuan255@gmail.com)  or [@hien-v](hienvuhuy@gmail.com) if you need help.
 
 
        
Enjoy and take your experiments on this server. :heart:
