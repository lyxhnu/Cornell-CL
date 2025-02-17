# A Generative Robotic Grasping Detection Method for Continual Learning with Perceptual Loss and Multi-Branch Deep Fusion
This is a method related to RGB-D multimodal fusion and continual learning for 2D grasping in general grasping scenarios, as described in the following paper:
A Generative Robotic Grasping Detection Method for Continual Learning with Perceptual Loss and Multi-Branch Deep Fusion，
by Qiaokang Liang,Yaoxin Lai, Songyun Deng, Xinhao Chen, Xiaoyu Yuan, and Li Zhou


#  Introduction
1.This project proposes a three-branch RGB-D multimodal fusion module and integrates it into GR-Convnet.
2.This project proposes a continual learning strategy for 2D robotic grasping.
3.The network we trained is integrated into the robotic grasping system, which is capable of autonomously grasping objects of various shapes that have never been seen before.
# Show
We have deployed the algorithm into the robotic grasping system, which is capable of autonomously grasping objects of various shapes.
![System Demonstration](https://github.com/lyxhnu/photos/raw/main/robot.jpg)
<p align="center">System Demonstration</p>

The following GIFs demonstrate the robot autonomously grasping spherical objects, objects with handles, rectangular objects, edge-graspable objects, and slender objects.
<table>
  <tr>
    <td><img src="https://github.com/lyxhnu/photos/raw/main/%E7%90%83%E5%BD%A21.gif" alt="Grasping spherical objects"><p align="center">Grasping spherical objects</p></td>
    <td><img src="https://github.com/lyxhnu/photos/raw/main/%E6%8A%8A%E6%89%8B1.gif" alt="Grasping objects with handles"><p align="center">Grasping objects with handles</p></td>
    <td><img src="https://github.com/lyxhnu/photos/raw/main/%E7%9F%A9%E5%BD%A21.gif" alt="Grasping rectangular objects"><p align="center">Grasping rectangular objects</p></td>
    <td><img src="https://github.com/lyxhnu/photos/raw/main/%E8%BE%B9%E7%BC%981.gif" alt="Grasping edge-graspable objects"><p align="center">Grasping edge-graspable objects</p></td>
    <td><img src="https://github.com/lyxhnu/photos/raw/main/%E9%95%BF%E6%9D%A11.gif" alt="Grasping slender objects"><p align="center">Grasping slender objects</p></td>
  </tr>
</table>
The following two GIFs demonstrate the scenario of the robot autonomously and continuously grasping objects.
<table>
  <tr>
    <td><img src="https://github.com/lyxhnu/Cornell-CL/blob/main/%E8%BF%9E%E7%BB%AD%E6%8A%93%E5%8F%961.gif" alt="Sequential Grasping 1"><p align="center">Sequential Grasping 1</p></td>
    <td><img src="https://github.com/lyxhnu/Cornell-CL/blob/main/%E8%BF%9E%E7%BB%AD2.gif" alt="Sequential Grasping 2"><p align="center">Sequential Grasping 2</p></td>
  </tr>
</table>


# Attention!
Since our paper is currently under peer review, we will release the related code after the paper is accepted.
# References
This project utilizes the [Cornell Grasp Dataset](http://pr.cs.cornell.edu/grasping/rect_data/data.php) for training and evaluation.
