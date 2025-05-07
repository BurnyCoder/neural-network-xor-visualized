# neural-network-xor-visualized
Interactive visualization of a simple neural network training on the XOR dataset

![image](https://github.com/user-attachments/assets/7c5fda76-06a2-417f-9db4-6c948730c953)

Open network.html

Network Structure:
Overall Layout: The network is organized into three vertical sections:
Input Layer (Left): Shows the neurons that receive the initial data (e.g., [0,0], [0,1]).
Hidden Layer (Middle): An intermediate layer of neurons that processes information from the input layer. The complexity of patterns the network can learn often depends on this layer.
Output Layer (Right): Shows the neuron(s) that produce the network's final prediction (e.g., trying to match 0 or 1 for XOR).
Neurons (Circles): Each circle represents a single neuron or processing unit.
Neuron Color: The color of a neuron indicates its activation level.
Darker/Cooler Color (e.g., dark blue/grayish): Represents a low activation (close to 0). The neuron is not firing strongly.
Brighter/Warmer Color (e.g., light blue evolving to yellowish): Represents a high activation (close to 1). The neuron is firing strongly.
Neuron Labels (e.g., I0, H1, O0): These are simple identifiers for each neuron (I for Input, H for Hidden, O for Output, followed by an index).

Connections (Weights):
Lines between Neurons: These lines represent the connections between neurons. Each connection has an associated weight.
Weight's Role: A weight determines the strength and influence of one neuron's output on another neuron in the next layer. During training, the network learns by adjusting these weights.
Connection Line Thickness:
Thicker Line: Indicates a stronger influence (higher absolute value of the weight). The signal passing through this connection will have a more significant impact on the receiving neuron.
Thinner Line: Indicates a weaker influence (lower absolute value of the weight).
Connection Line Color:
Green Line: Represents a positive weight. A positive weight means that if the sending neuron is highly activated, it will excite (try to increase the activation of) the receiving neuron.
Red Line: Represents a negative weight. A negative weight means that if the sending neuron is highly activated, it will inhibit (try to decrease the activation of) the receiving neuron.
Opacity/Intensity of Color: The more saturated or opaque the color (green or red), the larger the magnitude of the positive or negative weight, complementing the thickness cue.
