# ProvaTrabalho
**4.3.4 Estimativa de máxima verossimilhança**
Para estimar os parâmetros do modelo,adaptamos um algoritmo proposto por Anderson (1973). A log-verossimilhança para o modelo espacial linear t-Student é dado por 

$L(\theta)=log(K_{n}(\eta))-½log (\Sigma)-½(\eta)(1+n\eta) log(1+c(\eta) \delta)$     (4.4)

com  $log(K_{n}(\eta))=\frac{n}{2}log(\frac {c(\eta)}{\pi})+log \Gamma (\frac{1-n\eta}{2\eta})-log \Gamma (\frac{1}{2\eta}), \delta = (\boldsymbol{Y} - \boldsymbol {X} \beta)^{T}\Sigma^-¹(\boldsymbol{Y}-\boldsymbol {X} \beta)$ e  $c(\eta) = \eta/(1-2 \eta), 0<\eta<½$. Conforme observado por Zellner (1976), a função log-verossimilhança. Veja também De Bastini et al. (2015).
As funções escores para o modelo espacial linear t-Student são fornecidos por $U_{\theta}(\theta) = (U^T_\beta,U^T_\phi)^T$,em que

$U_\beta=\partial L(\theta)/\partial\beta=w(\delta)\boldsymbol {X}^T \Sigma^-¹\epsilon$  and   $U_\phi =\partial L(\theta)/\partial\phi$,
com j-ésimo elemento de $U_\phi$  dado por  $U_\phi j =L(\theta)/\partial\phi_j=-½tr(\Sigma^-¹(\partial\Sigma/\partial \phi_j)) + ½w(\delta)_\epsilon^T \Sigma^-¹(\partial\Sigma/\partial\phi_j)\Sigma^-¹\epsilon$,  para $j=1,2, w(\delta)=(\frac {1+\eta n} {\eta})(\frac{c(/eta)}{1+c(\eta)\delta}$  e  $\psi(x)$  é a função Digama. Nesse artigo, $\Sigma=\phi_1\boldsymbol {I}_n + \phi_2 \boldsymbol {R}$,  então  $\partial\Sigma/\partial\phi_1= \boldsymbol {I}_n$  e $\partial\Sigma/\partial\phi_2=\boldsymbol {R}$.  Dado $\Sigma$, a função log-verossimilhança (4.4) é maximizada  em

$\hat{\beta}=(\boldsymbol {X}^T \Sigma ^-¹\boldsymbol {X})^-¹ \boldsymbol {X}^T \Sigma^-¹ \boldsymbol {Y}$, (4.5) 
e de  $U_\phi=0$  tem-se que,

$i)\phi_1 tr(\Sigma^-¹\Sigma^-¹)+\phi_2 tr(\Sigma^-¹\boldsymbol {R}\Sigma^-¹)=w(\delta)\epsilon^T \Sigma^-¹\Sigma-¹\epsilon$,

$ii)\phi_1 tr(\Sigma^-¹\boldsymbol {R}\Sigma^-¹)+\phi_2 tr(\Sigma^-¹\boldsymbol {R}\Sigma^-¹\boldsymbol{R}) = w(\delta)\epsilon ^T \Sigma^-¹ \boldsymbol{R} \Sigma^-¹\epsilon$.



