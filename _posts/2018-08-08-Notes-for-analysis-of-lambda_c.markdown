---
layout: note
---

*This article is notes for reactions listed below*

$$ \Lambda_c^+ \rightarrow \Sigma^0 \pi^+ \pi^0$$

$$ \Lambda_c^+ \rightarrow \Sigma^0 \pi^+ \eta $$

$$\Sigma^0 \rightarrow \gamma \Lambda$$

$$\eta \rightarrow \gamma \gamma$$

## Basical Information

$$\Sigma^0 \rightarrow \gamma \Lambda$$
* Fraction: $(100)\%$ From [PDG](http://pdglive.lbl.gov/Particle.action?init=0&node=S021&home=BXXX025)


$$\eta \rightarrow \gamma + \gamma$$
* Fraction: $(39.41 \pm 0.20)\%$ From [PDG](http://pdglive.lbl.gov/Particle.action?init=0&node=S014&home=MXXX005#decayclump_N)


$$\Lambda \rightarrow p + \pi^-$$
* Fraction: $(63.9 \pm 0.5)\%$ From [PDG](http://pdglive.lbl.gov/Particle.action?init=0&node=S018&home=BXXX020)


$$\pi^0 \rightarrow \gamma + \gamma$$
* Fraction: $(98.823 \pm 0.034)\%$ From [PDG](http://pdglive.lbl.gov/Particle.action?init=0&node=S009&home=MXXX005)

## Cut information
# Good track
vr < 1  Vz < 10  theta < 0.93

# Good track for lambda
Vz < 20 theta < 0.93


# Good shower


# Good Pi0
0.115 < (pShr1+pShr2).m() < 0.150
constrain: pi0_mass = 0.134976
pi0_chis <= 100


# Good Lambda
After primary vertex fit, use updated pProton ,pPion and chisq_1 to cut
1.111 < (pProton+pPion).m() < 1.121
chisq_1 < 100

After second vertex fit, use lchue = dl/de to cut
lchue > 2


# Good Sigma0
1.179 < (pLambda_from_second_vertex_fit + pShr).m() < 1.203
constrain: sigma0_mass = 1.19264
sigma0_chis <= 100

# Good Eta
0.535 < (pShr1+pShr2).m() < 0.565
constrain: Eta_mass = 0.54786
Eta_chis <= 100

## one constrain on particle 4-Vector
Due to $m=\sqrt{E^2-p^2}$, 

$$\frac{\delta m}{m}= \frac{E}{E^2-p^2}\delta E - \frac{p}{E^2-p^2}\delta p$$

Because $p << 1$,

$$ \frac{\delta m}{m} = \frac{\delta E}{E}$$

In conclusion, to improve $m_{BC}$ resolution, use 1c to narrow the range of $\Delta E$.


