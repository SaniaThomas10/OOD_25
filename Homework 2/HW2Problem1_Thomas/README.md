#Problem 1: Hurricane Prediction System
##Overview

This program implements a simplified hurricane prediction system using two design patterns:

##Template Method Pattern 
Defines the overall workflow for predicting hurricanes while allowing different models (Statistical vs. Machine Learning) to implement the individual steps differently.

##Command Pattern 
Encapsulates individual prediction steps (fetching data, running models, saving results) into executable command objects that can be queued and executed by an invoker.

Together, these patterns create a flexible, extensible structure where prediction workflows can vary without rewriting the main algorithm, and system operations can be modularized into reusable commands.
