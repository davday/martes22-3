# martes22-3
Ejemplo número 3

import numpy as	np
import matplotlib.pyplot as plt

t = np.arange(0., 5., 0.2)

plt.plot(t, t, 'r--', t, 'bs', t, t**3,	'g^')
plt.show()
