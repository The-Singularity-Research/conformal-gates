# conformal-gates
convert a conformal map of a mesh on a Riemann surface to another mesh on a Riemann surface into quantum gates
---

This will take as input a mesh or cellularly embedded graph in a Riemann surface along with a conformal mapping 
of it to another cellularly embedded graph in a Riemann surface and will produce as output an intitial quantum
surface code and a set of gates adjusting the pairwise entanglement of qudits to produce the second surface code
asssociated to the image of the conformal map. 

The initial surface code will have controlled-U gates (applied pairwaise to qudits) rather than CNOT/CX gates for
entanglement in the most general sense. The second surface code will have a different set of controlled-U gates
determined by the conformal mapping. The entanglement between any pair of qudits will be adjusted to produce an
"entanglement distance" that reflects the new relative positions of the qudits in the new surface code. 

### [SageMath Riemann Mapping](https://doc.sagemath.org/html/en/reference/calculus/sage/calculus/riemann.html)
### [SageMath Complex Plots](Complex Plots)
### [SageMath Minimal Genus](https://doc.sagemath.org/html/en/reference/graphs/sage/graphs/genus.html)
