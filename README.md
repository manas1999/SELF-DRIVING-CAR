# DRL APPROCH FOR AUTONOMOUS DRIVING
• Used a hybrid CNN-RNN architecture, trained with a variant of Q-learning to learn control policies with raw sensory data.
• The CNN is given a 32*32 image of the track from the player's perspective, LSTM is fed with car's speed, angle, distance from
the track, used standard L2 loss between networks predicted Q values and estimated Q values.
• Used CARLA as the simulation environment for the autonomous vehicle.
