### Syntactic sugar for calling an instance like a function

Use __call__ in Python classes to call class instances (objects) like functions. See a sample definition for [micrograd Neuron class ](https://github.com/karpathy/micrograd/blob/c911406e5ace8742e5841a7e0df113ecb5d54685/micrograd/nn.py#L20-L22)
and corresponding usage 
```
n = Neuron(2)
x = [1.0, 2.0]
n(x) #usage
```

