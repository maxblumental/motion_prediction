# motion_prediction
Predict motion of AVs with ResNet

Input data: frames with an autonomous vehicle and surrounding traffic agents.
Output data: agents positions in the future.

Here we use 10 frames of history + 1 current frame to predict (X, Y) corrdinates of the agents for the next 50 frames.
