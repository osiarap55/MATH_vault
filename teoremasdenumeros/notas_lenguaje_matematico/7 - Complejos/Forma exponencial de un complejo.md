---
tipo: teorema
tags: [definicion, teorema, complejos]
capitulo: "[[LM Cap 7 - Números complejos]]"
ref: "§7.4 · pp. 252-254; Ejemplos 7.7-7.9"
aliases: [Forma exponencial, Fórmula de Euler, Fórmulas de Euler, e^(iα), Identidad de Euler]
---
# Forma exponencial (fórmulas de Euler)

> [!tip] En palabras sencillas
> $\cos\alpha+i\sin\alpha$ se comporta **igual que una exponencial**: al multiplicar se suman los "exponentes" (ángulos). Por eso se escribe $e^{i\alpha}$.

> [!note] Notación
> $$e^{i\alpha}=\cos\alpha+i\sin\alpha\qquad z=re^{i\alpha}\ \ (\text{forma exponencial})$$
> Justificación: $\Phi(\alpha)=\cos\alpha+i\sin\alpha$ cumple $\Phi(\alpha+\alpha')=\Phi(\alpha)\Phi(\alpha')$ y $\Phi(n\alpha)=\Phi(\alpha)^n$, igual que $e^{x+x'}=e^xe^{x'}$ (es un [[Homomorfismo]] de $(\mathbb R,+)$ en $(\mathbb C^*,\cdot)$).

> [!example] Valores famosos
> $e^{i\pi}=-1$ (**identidad de Euler**: $e^{i\pi}+1=0$), $\ e^{i\pi/2}=i$, $\ e^{2\pi i}=1$.

> [!important] Reglas de cálculo
> - $re^{i\alpha}=r'e^{i\alpha'}\iff r=r'$ y $\alpha=\alpha'\ [\mathrm{mód}\ 2\pi]$
> - $\overline{re^{i\alpha}}=re^{-i\alpha}$, $\ -re^{i\alpha}=re^{i(\alpha+\pi)}$
> - $(re^{i\alpha})(r'e^{i\alpha'})=rr'e^{i(\alpha+\alpha')}$, $\ (re^{i\alpha})^n=r^ne^{in\alpha}$

> [!important] Fórmulas de Euler
> $$\cos\alpha=\frac{e^{i\alpha}+e^{-i\alpha}}2\qquad\sin\alpha=\frac{e^{i\alpha}-e^{-i\alpha}}{2i}$$
> **Uso (Ejemplo 7.8): "linealizar" potencias de senos y cosenos.**
> $\cos^3\alpha=\left(\frac{e^{i\alpha}+e^{-i\alpha}}2\right)^3=\frac18\big(e^{3i\alpha}+e^{-3i\alpha}+3(e^{i\alpha}+e^{-i\alpha})\big)=\frac14(\cos3\alpha+3\cos\alpha)$.

> [!warning] Ojo
> Para **sumar** complejos, las formas polar y exponencial no sirven: pasa a binómica. Ej.: $\sqrt2e^{i\pi/4}+2e^{i\pi/3}=(1+i)+(1+i\sqrt3)=2+i(1+\sqrt3)$.

## Conexiones
- **Necesitas antes:** [[Forma trigonométrica y polar]], [[Fórmula de De Moivre]]
- **Lleva a:** [[Raíces n-ésimas de un complejo]], [[Aplicaciones geométricas de los complejos]]
- **Relacionado:** [[Número e]]; en análisis complejo, $e^z$ se define con series ([[resumen_completo_ahlfors]])
