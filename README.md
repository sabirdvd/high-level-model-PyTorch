# high-level-model-PyTorch

To visualize the architecture 

add to the file 

```python 
from torchviz import make_dot

make_dot(model output).render("attached", format="png")
```

