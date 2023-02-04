## INPUT
```
ecutwfc                100
smearing_method        gaussian
smearing_sigma         0.001
```

## KPT

structures | bcc | fcc | dhcp
:-:|:-:|:-:|:-:
k mesh | $$16\times16\times16$$ | $$16\times16\times16$$ | $$16\times16\times4$$

## Results
### dhcp (stable)
Methods | PW | LCAO | [exp.](https://www.sciencedirect.com/science/article/abs/pii/0022508874901635)
:-:|:-:|:-:|:-:
a (\AA) | 3.761 | 3.760 | 3.772
c (\AA) | 12.075 | 12.127 | 12.144
B (GPa) | 24.7 | 27.4 | 28

### bcc
Methods | PW | LCAO 
:-:|:-:|:-:
a (\AA) | 4.226 | 4.224
B (GPa) | 24.0 | 25.3 

### fcc
Methods | PW | LCAO 
:-:|:-:|:-:
a (\AA) | 5.274 | 5.284
B (GPa) | 24.0 | 28.5