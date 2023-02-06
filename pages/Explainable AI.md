- ### Papers
- ![Deep Inside Convolutional Networks - Visualising Image Classification Models and Saliency Maps.pdf](../assets/Deep_Inside_Convolutional_Networks_-_Visualising_Image_Classification_Models_and_Saliency_Maps_1675714177817_0.pdf)
  collapsed:: true
	- author : [[Karen Simonyan]]
	  type : [[paper]]
	  tags : [[Explainable AI]] [[Computer Vision]] [[Convolutional Neural Networks]] [[Visualization]] [[Saliency Map]] [[ImageNet]] [[Segmentation]] [[Deconv Nets]]
	- **Key Insights**:
	  collapsed:: true
		- To generate an image that maximizes the output of a class, simply freeze the hidden layers and let backpropagation adjust the input image.
		- To generate the saliency map, use backpropagation to generate the Jacobian matrix (derivatives) leading up the input image.  The Jacobian matrix is the saliency map for that particular image.
		- Using the Jacobian matrix, it is possible to perform automatic segmentation of objects within an image.
	-
- ![Visualizing and Understanding Convolutional Networks.pdf](../assets/Visualizing_and_Understanding_Convolutional_Networks_1675460396745_0.pdf)
  collapsed:: true
	- author : [[Matthew Zeiler]] 
	  type : [[paper]]
	  tags : [[Explainable AI]] [[Computer Vision]] [[Convolutional Neural Networks]] [[Visualization]] [[ImageNet]] [[Deconv Nets]]
	- **Key Insights:**
	  collapsed:: true
		- Using a deconv net it is possible to backpropagate back to the original image and identify what a hidden layer was focused on.
		- In this paper a decov net is a method that performs:
			- 1. max unpooling
			- 2. unRectified Linear Function
			- 3. unconvolution $F^{T}$
		- The backpropagated image as well as the original image are shown side by side to help the reader visualize what is going on.
-
- ### Websites
- [Building Blocks for Explainable AI](https://distill.pub/2018/building-blocks/)
  collapsed:: true
	- author : [[Chris Olah]]
	  type : [[website]] 
	  tags : [[Computer Vision]] [[Convolutional Neural Networks]] [[Visualization]]
- [Understanding RL Vision](https://distill.pub/2020/understanding-rl-vision/)
  collapsed:: true
	- author : [[Chris Olah]] 
	  type : [[website]] 
	  tags : [[Reinforcement Learning]] [[Computer Vision]] [[Convolutional Neural Networks]] [[Visualization]]