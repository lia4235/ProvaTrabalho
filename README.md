# ProvaTrabalho
**4.3.4 Estimativa de máxima verossimilhança**
Para estimar os parâmetros do modelo,adaptamos um algoritmo proposto por Anderson (1973). A log-verossimilhança para o modelo espacial linear t-Student é dado por 

$L(\theta)=log(K_{n}(\eta))-½log (\Sigma)-½(\eta)(1+n\eta) log(1+c(\eta) \delta)$     (4.4)

com  $log(K_{n}(\eta))=\frac{n}{2}log(\frac {c(\eta)}{\pi})+log \Gamma (\frac{1-n\eta}{2\eta})-log \Gamma (\frac{1}{2\eta}), \delta = (\boldsymbol{Y} - \boldsymbol {X} \beta)^{T}\Sigma^-¹(\boldsymbol{Y}-\boldsymbol {X} \beta)$ e $c(\eta) = \eta/(1-2 \eta), 0<\eta<½$. Conforme observado por Zellner (1976), a função log-verossimilhança. Veja também De Bastini et al. (2015).
As funções escores para o modelo espacial linear
