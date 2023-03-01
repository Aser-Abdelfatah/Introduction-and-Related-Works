# Introduction-and-Related-Works
This project aims to use an open-source self-driving car simulator to design a neural-network-based model for a self-driving car. Developing a self-driving car is a complex process that requires automating an array of human functions, such as perception of surroundings, following traffic laws, and decision-making. A typical self-driving car would incorporate many machine learning models with each model performing different functions; for instance, the self-driving car needs a computer-vision model to identify traffic lights and road signs as well as a reinforcement-learning model to make decisions, such as whether the car will take a turn. 
We decided to use an open-source car simulator to focus only on the machine learning portion of the self-driving car development without the need for sensors and hardware components. The car simulator allows us to source the data by using the training mode, which is a game-like mode wherein we are put in different situations, and we take decisions to move the car depending on the surrounding environment; the model provides us with a complete dataset of the car surroundings, the decisions we took, and the result of each decision in different contexts. Using this data, we will design a classification model for object detection and decision making. The classification model will use convolutional neural networks to classify traffic lights, pedestrians, signs, etc. and classify decisions to figure out the correct decision depending on the inputs. To test our model, we use the simulator in the test mode, which automatically runs our model on different test cases and provides us with an analysis of the results.
When developing self-driving cars, significant attention must be given to potential ethical issues they may face. A classic problem in the realm of self-driving cars is the trolley problem, where a self-driving car would have to choose between hitting and killing one pedestrian versus five. While the trolley problem is a challenging problem with many perspectives to address, self-driving cars may not have to address the problem directly and other potentially more important and tangible problems exist (Holstein et al.). In this paper, we seek to discuss various ethical (and pragmatic) issues self driving cars may face, different ethical frameworks to addressing them, and survey different authors’ solutions to these ethical problems. While we do not attempt to create a definitive solution to these issues, we want to open discussion about it. 

References: 

* Duong, M.T., Do, T.D., Le, M.H. (2018). Navigating Self-Driving Vehicles Using Convolutional Neural Network. 2018 4th International Conference on Green Technology and Sustainable Development (GTSD), 607-610, https://ieeexplore.ieee.org/abstract/document/8595533.

* Goodall, N. J. (2016). Can you program ethics into a self-driving car?. IEEE Spectrum, 53(6). 28-58, https://ieeexplore.ieee.org/abstract/document/7473149.

* Holstein, T., Dodig-Crnkovic, G., Pelliccione, P. (2018). Ethical and Social Aspects of Self-Driving cars. 	 
https://doi.org/10.48550/arXiv.1802.04103

* Kaur, P., Taghavi, S., Tian, Z., Shi, W. (2021). A Survey on Simulators for Testing Self-Driving Cars. https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9499331&tag=1

* Karnouskos, S. (2020). Self-Driving Car Acceptance and the Role of Ethics. IEEE Transactions on Engineering Management, 67(2). 252-265, https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8542947.

* Ni, J., Chen, Y., Chen, Y., Zhu, J., Ali, D., Weidong, C. (2020). A Survey on Theories and Applications for Self-Driving Cars Based on Deep Learning Methods. Applied Sciences, 10(8). https://doi.org/10.3390/app10082749

* Shalev-Shwartz, S., Shammah, S., & Shashua, A. (2017). On a formal model of safe and scalable self-driving cars. arXiv preprint arXiv:1708.06374.
