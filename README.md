# weree

![image](https://github.com/user-attachments/assets/f98b3c50-c5d7-455e-a948-c538d2818802)

A continuación, nos dicen que escribamos las ecuaciones diferenciales que representan el modelo de la siguiente figura para ello vemos que es un sistema mecánico el cual es un carro jalando un remolque que en el medio tiene un resorte y un amortiguador para ello comenzaremos realizando el diagrama de bloques correspondiente.

![image](https://github.com/user-attachments/assets/72a6c88e-6e6b-4e88-b288-41f81d9db858)

Una vez teniendo este diagrama de bloques pasaremos a hacer la sumatoria de fuerzas para el vehículo quedando de la siguiente manera.

$$ Fy_1 - Fk_b + FB_b = m_1 a_{m1} $$

Vemos en la sumatoria de fuerzas cómo actúan cada una de ellas a continuación pasaremos a reemplazar cada fuerza con su respectivo valor para poder así hallar la ecuación correspondiente quedando de la siguiente manera.

$$y_1(t) - K_b \left( y_1(t) - y_2(t) \right) - B_b \frac{d \left( y_1(t) - y_2(t) \right)}{dt} = m_1 \frac{d^2 y_1(t)}{dt^2}$$

Con esto tendríamos la ecuación para el primer diagrama de bloques el cual es el vehículo a continuación para terminar el análisis pasaremos a hacer lo mismo en este caso para el remolque teniendo en cuenta que su diagrama de bloques queda de la siguiente manera.

![image](https://github.com/user-attachments/assets/625bc383-15fa-4f86-b255-cf2456022583)

Listo una vez con esto pasaremos nuevamente a hacer la sumatoria de fuerzas teniendo la siguiente ecuación.

$$ F_{K_b} + F_{B_b} - F_{B_t} = m_2 a_{m_2} $$

Una vez con la sumatoria de fuerzas realizada pasaremos a reemplazar cada una de las fuerzas para así obtener la ecuación característica del sistema esta nos quedaría de la siguiente forma.

$$K_b \left( y_1(t) - y_2(t) \right) + B_b \frac{d \left( y_1(t) - y_2(t) \right)}{dt} - B_t \frac{dy_2(t)}{dt} = m_2 \frac{d^2 y_2(t)}{dt^2}$$
