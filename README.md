# A multi-branch multimodal fusion and continual learning method for robotic grasping

This is a method related to RGB-D multimodal fusion and continual learning for 2D grasping in general grasping scenarios, as described in the following paper:
A Grasp Detection Method Based on Continual Learning Using Perceptual Loss and Multi-Branch Deep Fusion，
by Qiaokang Liang,Yaoxin Lai, Songyun Deng, Xinhao Chen, Xiaoyu Yuan, and Li Zhou


#  Introduction
1.This project proposes a three-branch RGB-D multimodal fusion module and integrates it into GR-Convnet.
2.This project proposes a continual learning strategy for 2D robotic grasping.
3.The network we trained is integrated into the robotic grasping system, which is capable of autonomously grasping objects of various shapes that have never been seen before.
# Show
We have deployed the algorithm into the robotic grasping system, which is capable of autonomously grasping objects of various shapes。
![System Demonstration](https://github.com/lyxhnu/photos/raw/main/robot.jpg)

The following GIFs demonstrate the robot grasping spherical objects, objects with handles, rectangular objects, edge-graspable objects, and slender objects.
![Grasping spherical objects](https://github.com/lyxhnu/photos/raw/main/%E7%90%83%E5%BD%A21.gif)

grasping spherical objects

![Grasping objects with handles](https://github.com/lyxhnu/photos/raw/main/%E6%8A%8A%E6%89%8B1.gif)

grasping objects with handles

![Grasping rectangular objects](https://github.com/lyxhnu/photos/raw/main/%E7%9F%A9%E5%BD%A21.gif)

grasping rectangular objects

![Grasping edge-graspable objects](https://github.com/lyxhnu/photos/raw/main/%E8%BE%B9%E7%BC%981.gif)

grasping edge-graspable objects

![Grasping slender objects](https://github.com/lyxhnu/photos/raw/main/%E9%95%BF%E6%9D%A11.gif)

grasping slender objects


The following two GIFs demonstrate the scenario of the robot continuously grasping multiple objects.
![Sequential Grasping 1](https://github.com/lyxhnu/Cornell-CL/blob/main/%E8%BF%9E%E7%BB%AD%E6%8A%93%E5%8F%961.gif)
![Sequential Grasping 2](https://github.com/lyxhnu/Cornell-CL/blob/main/%E8%BF%9E%E7%BB%AD2.gif)
# Attention!
Since our paper is currently under peer review, we will release the related code after the paper is accepted.
