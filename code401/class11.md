# Data Visualization
## matplotlib: is probably the single most used Python package for 2D-graphics. It provides both a very quick way to visualize data from Python and publication-quality figures in many formats
- IPython:is an enhanced interactive Python shell that has lots of interesting features including named inputs and outputs, access to shell commands
- pyplot: provides a convenient interface to the matplotlib object-oriented plotting library

### draw the cosine and sine functions on the same plot
```
import numpy as np

X = np.linspace(-np.pi, np.pi, 256, endpoint=True)
C, S = np.cos(X), np.sin(X)
```

## types of plots
-  figure: in matplotlib means the whole window in the user interface. Within this figure there can be subplots
-  subplot:the plots in a regular grid
-  axes: allows free placement within the figure

