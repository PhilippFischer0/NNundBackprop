# Praktikum

## Fragen

-Wieso kann ich nicht direkt die Summe berechnen?

```python
losses = [(yout - ygt)**2 for ygt, yout in zip(ys, ypred)]
loss = sum(losses[i].data for i in range(len(losses)))
loss
```
