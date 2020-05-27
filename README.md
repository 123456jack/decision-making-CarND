注意事项：

1. 代码运行时会关闭所有终端，所以不要在终端中运行程序（可以在PyCharm中运行），其他在运行的程序也要注意先关闭；
2. 程序环境依赖在`environment.yaml`中；
3. 在`/CarND-test/src/train/train.py`中编写你的强化学习程序，注意在其中的150、179等行修改你的文件存储位置；
4. 按照`/CarND-test/README.md`中的提示编译程序，理解`/CarND-test/src/main.cpp`的作用（可能需要作相应调整）；
5. 不同电脑，tensorflow-gpu、cuda、cudnn的版本配置可能不同，请自行安装；
6. 测试环境是否安装成功，可以运行`decision-making-CarND/term3_sim_linux/term3_sim.x86_64`和`decision-making-CarND/CarND-test/src/test/path_planning`。



环境配置步骤：

1. `git clone https://github.com/DRL-CASIA/decision-making-CarND.git` （有文件更新，建议重新克隆）
2. `cd decision-making-CarND/term3_sim_linux`
3. `sudo chmod u+x term3_sim.x86_64`
4. 确保cmake >= 3.5，make >= 4.1，gcc/g++ >= 5.4（一般都已安装，未安装参考decision-making-CarND/CarND-test/README.md）
5. 进入`decision-making-CarND/CarND-test`文件夹，运行install-ubuntu.sh安装依赖（`bash install-ubuntu.sh`）
6. 保持在decision-making-CarND/CarND-test文件夹，进行编译：
   `mkdir build && cd build`
   `cmake .. && make`
   此时运行`./path_planning`显示`connect error`为正常现象
7. 安装anaconda3或miniconda3
8. 修改environment.yaml中最后一行至你的conda安装位置，运行`conda env create -f environment.yaml`建立虚拟环境
9. 编写`decision-making-CarND/CarND-test/src/train/train.py`文件并运行，注意事项如上

