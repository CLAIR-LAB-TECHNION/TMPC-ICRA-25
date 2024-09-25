To perform complex tasks robots need to make decisions at three levels of abstraction. At the highest level, they need to compute a task plan that prescribes the sequence of high-level actions that need to be performed to accomplish the long-horizon objective. For example, a task plan may include a sequence of pick-and-place actions of items that need to be collected from a cluttered environment. Then, to accomplish each action, there is a need to plan the physical motions required to achieve the next desired state of the robot. For example, a
motion plan is needed to reach the robot configuration from which the next item can be picked up. Finally, to accomplish the prescribed motion plan, there is a need to continuously monitor the execution of the motion and adjust the control action. This low-level feedback control helps maintain the desired performance despite disturbances or changes in the system.
Until recently, challenges of task planning, motion planning, and control have been investigated by three different research communities. On the one hand, the AI planning community developed approaches for task planning that scale to large discrete domains. At the same time, research on robotics and motion planning has achieved great progress in finding optimal and continuous motions that respect constraints on kinematics and dynamics, as well as constraints imposed by obstacles in the environment. Finally, research in feedback control
has yielded various techniques for computing strategies to ensure the robot follows the planned trajectory accurately while minimizing energy consumption, travel time, and other criteria.

Over the last decade, much effort has been invested in bridging these research streams, with a special focus on the integration of task and motion planning and on applying machine learning and reinforcement learning to feedback control. We aim to support the integrated account of the different perspectives and to provide the foundations for generating novel ideas in this realm. Our tutorial will introduce the fundamental ideas of task planning, motion planning, and feedback control. We will then present leading approaches in each of these fields and novel frameworks that aim to address various challenges that arise when robotic agents need to accomplish complex tasks and combine long-term decision-making with low-level reasoning and a continuous interaction with the physical environment via various sensors.

To ensure a lasting impact and an assimilation of the learned ideas, the lectures will be accompanied by hands-on lab sessions based on a simulated robotic setting. The format of the labs will be Google Colab notebooks that can be run from a Chrome browser without requiring any installations. During the labs, participants will implement ideas discussed in the tutorial. To encourage the exchange of ideas, work will be done in groups, with participants from different backgrounds in each group. At the end of the day, we will facilitate a discussion on challenges that were encountered during the labs, potential solution approaches to these challenges, and promising avenues for future research.

By presenting the perspectives taken by each research community and by overviewing the state of the art in each field, our tutorial aims to enable diverse groups of researchers to develop a unified view of the task of developing novel approaches for the complex decision-making of robotic agents. This will support compelling applications in a variety of domains including household robotics, healthcare robotics, wildfire detection and prevention, and agriculture.

