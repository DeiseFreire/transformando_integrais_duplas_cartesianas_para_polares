# Transformando integrais duplas cartesianas para polares

📝 Descrever como transformar uma integral dupla em coordenadas cartesianas em uma integral dupla em coordenadas polares.

Para converter uma integral dupla em coordenadas cartesianas para uma integral dupla em coordenadas polares, seguimos estes passos:


**1. Identificar a região de integração:**

* **Região em coordenadas cartesianas:** A região R é geralmente definida por desigualdades com x e y, como por exemplo, $R = \{(x, y) | a \leq x \leq b, c \leq y \leq d\}$.
* **Região em coordenadas polares:** A região R em coordenadas polares precisa ser redefinida em termos de $r$ e $\theta$. Isso pode envolver converter as desigualdades cartesianas para polares ou usar outras formas de descrever a região, como arcos, setores ou regiões com limites polares.

**2. Substituir as variáveis:**

* Substitua x e y por suas definições em coordenadas polares: $x = r \cos(\theta)$ e $y = r \sin(\theta)$.
* Certifique-se de que a função a ser integrada também esteja expressa em termos de r e $\theta$.

**3. Ajustar o elemento diferencial:**

* O elemento diferencial em coordenadas cartesianas é $dA = dx \, dy$.
* Em coordenadas polares, o elemento diferencial se transforma em $dA = r \, dr \, d\theta$.

**4. Estabelecer os limites de integração:**

* Os limites de integração em coordenadas cartesianas geralmente definem os intervalos de x e y sobre os quais a integração é realizada.
* Em coordenadas polares, os limites precisam ser convertidos para os intervalos de $\theta$ e r que cobrem a região R definida anteriormente.
* O limite de $\theta$ geralmente varia de $\alpha$ a $\beta$, onde $\alpha$ e $\beta$ definem os ângulos que englobam a região R.
* O limite de r geralmente varia de 0 a $R(\theta)$, onde $R(\theta)$ define a distância máxima do ponto $(0,0)$ até a fronteira da região R em um ângulo específico $\theta$.

**5. Reescrever a integral:**

Após as substituições e ajustes, a integral dupla em coordenadas cartesianas se transforma em uma integral dupla em coordenadas polares:

$$\int_a^b \int_c^d f(x, y) \, dA = \int_{\alpha}^{\beta} \int_0^{R(\theta)} f(r \cos(\theta), r \sin(\theta)) \, r \, dr \, d\theta$$

**🚨​Observações importantes:🚨​**

* A conversão para coordenadas polares pode ser vantajosa quando a região R possui simetria rotacional ou quando a função f a ser integrada é mais fácil de expressar em termos de r e $\theta$.
* É crucial verificar se os limites de integração em coordenadas polares cobrem corretamente a região R original definida em coordenadas cartesianas.

**Recursos adicionais:**

* 📽️ Vídeos 🎞️
    * [Multivariable functions - Playlist](https://www.youtube.com/watch?v=TrcCbdWwCBc&list=PLSQl0a2vh4HC5feHa6Rc5c0wbRTx56nF7)
    * [Convert Double Integrals into Polar Coordinates](https://www.youtube.com/watch?v=FBlmzpFNxmQ)


