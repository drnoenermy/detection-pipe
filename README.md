# detection-pipe

This project is trying to represent a object detection task in terms of  graph.

Traditional object detection models have a fixed structure, e.g. one stage model or two stage model.

But it is very much fixed and making changes is hard.
We can use the idea of directed acyclic graph to construct detectors in a more general way.
In this way, we only need to define the dependency table in order to build a model no matter how complicated it is as long as it follows some rule.
