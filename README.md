# Markovianity-Jaynes-Cummings-Model

The [Jaynes-Cummings Hamiltonian](https://en.wikipedia.org/wiki/Jaynes%E2%80%93Cummings_model#Jaynes%E2%80%93Cumming_Hamiltonian_1) in the rotating wave approximation is given by 

![\color{grey}  H = \hbar \omega_c \hat{a}^\dagger \hat{a} + \frac{1}{2} \hbar \omega_a \hat{\sigma}_z + \frac{1}{2} \hbar \Omega \left( \hat{a}^{\dagger}\hat{\sigma}_- + \hat{a}\hat{\sigma}_+ \right)
](https://render.githubusercontent.com/render/math?math=%5Cdisplaystyle+%5Ccolor%7Bgrey%7D++H+%3D+%5Chbar+%5Comega_c+%5Chat%7Ba%7D%5E%5Cdagger+%5Chat%7Ba%7D+%2B+%5Cfrac%7B1%7D%7B2%7D+%5Chbar+%5Comega_a+%5Chat%7B%5Csigma%7D_z+%2B+%5Cfrac%7B1%7D%7B2%7D+%5Chbar+%5COmega+%5Cleft%28+%5Chat%7Ba%7D%5E%7B%5Cdagger%7D%5Chat%7B%5Csigma%7D_-+%2B+%5Chat%7Ba%7D%5Chat%7B%5Csigma%7D_%2B+%5Cright%29%0A)

A counter ![\color{grey}  \mathcal{N}
](https://render.githubusercontent.com/render/math?math=%5Cdisplaystyle+%5Ccolor%7Bgrey%7D++%5Cmathcal%7BN%7D%0A) is defined [here](https://arxiv.org/abs/0908.0238) to analyze the markovianity of the evolution, 

![\color{grey}  \mathcal{N} = \max_{\rho_{e,g}} \int_{\sigma_d>0} \sigma_{d} dt
](https://render.githubusercontent.com/render/math?math=%5Cdisplaystyle+%5Ccolor%7Bgrey%7D++%5Cmathcal%7BN%7D+%3D+%5Cmax_%7B%5Crho_%7Be%2Cg%7D%7D+%5Cint_%7B%5Csigma_d%3E0%7D+%5Csigma_%7Bd%7D+dt%0A)

where 

![\color{grey}  \sigma_d = \frac{1}{2} \frac{d}{dt} D(\rho_e,\rho_g)
](https://render.githubusercontent.com/render/math?math=%5Cdisplaystyle+%5Ccolor%7Bgrey%7D++%5Csigma_d+%3D+%5Cfrac%7B1%7D%7B2%7D+%5Cfrac%7Bd%7D%7Bdt%7D+D%28%5Crho_e%2C%5Crho_g%29%0A)

and

![\color{grey}  D(\rho_e,\rho_g) = \frac{1}{2} \text{Tr} |\rho_e-\rho_g| = \frac{1}{2} \text{Tr} \sqrt{\rho_e^{\dagger}\rho_g}](https://render.githubusercontent.com/render/math?math=%5Cdisplaystyle+%5Ccolor%7Bgrey%7D++D%28%5Crho_e%2C%5Crho_g%29+%3D+%5Cfrac%7B1%7D%7B2%7D+%5Ctext%7BTr%7D+%7C%5Crho_e-%5Crho_g%7C+%3D+%5Cfrac%7B1%7D%7B2%7D+%5Ctext%7BTr%7D+%5Csqrt%7B(%5Crho_e-%5Crho_g)%5E%7B%5Cdagger%7D(%5Crho_e-%5Crho_g)%7D)

