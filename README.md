# Conflict EDT
A python version of an Evidential Decision Tree based on a conflict measure.

### Summary

When the data are labeled in an uncertain and imprecise way, Evidential Decision Tree models can be used for classification problems.
The model presented here uses conflict as a splitting criterion.

### Reference

When using this code please cite and refer to [Paper being published](https://github.com/ArthurHoa/conflict_edt)

### Example

For two observations respectively labeled *I think it's a dog* and *I'm sure it's a cat*, the model will try to group the observations in two different nodes. After the construction of the tree, a new observation will then be classified according to its attributes.
