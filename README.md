# Details

As-Rigid-As-Possible Energy implementation (Sorkine and Alexa, 2007) and Maya plugin.
For testing/experimentation purposes.

## Usage

```python
from arap import ARAPEnergy

# V: vertices of the mesh (N, 3)
# F: faces of the mesh (M, 3) (indices)
# V_deformed: deformed vertices of the mesh (N, 3) 
loss_fn = ARAPEnergy(V, F)
loss = loss_fn(V_deformed)
```
