# GFSDCF

Code from: https://github.com/XU-TIANYANG/GFS-DCF/archive/master.zip



## Preparation

### The code depends on MatConvNet and PDollar Toolbox.

#### Please download [MatConvNet](https://codeload.github.com/vlfeat/matconvnet/zip/master) and unzip it in tracker_exter/matconvnet/.

#### Please download [PDollar Toolbox](https://codeload.github.com/pdollar/toolbox/zip/master) and unzip it in tracker_exter/pdollar_toolbox/.

### Make sure you have run install.m before the test.

### Please replace the followings, remember to change the absolute path.

- #### in tracker_GFSDCF.m

  ##### tracker_command =generate_matlab_command('gfsdcf(''GFSDCF'', ''run_GFSDCF'', true)', {'abs_path/GFSDCF'});

### Move tracker_GFSDCF.m to your workspace.

### Then, you can run the tracker within VOT toolkit following [VOT Chanllenge support](http://www.votchallenge.net/howto/).



## Trouble Shooting

1. ### If you met with an ERROR like this: "Tracker execution interrupted: Did not receive response.", you can try to replace GFSDCF/vot.m with the vot.m in vot-toolkit/tracker/examples/matlab/.

2. ### If you use the pretrained model or sequences downloaded by install.m, the files may can't be loaded. In that case, you'd better download the pre-trained model or sequences independently from the url given in install.m and prepare them following install.m by yourself.



## System Requirements

- ### Ubuntu(tested with 18.04LTS)

- ### MATLAB(tested with R2018b)

- ### The result is obtained using a single CPU