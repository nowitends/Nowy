# Reguła Leibnitza

## Definicja

Reguła Leibnitza (znana również jako reguła iloczynu) mówi, że pochodna iloczynu dwóch funkcji jest równa:

$$\frac{d}{dx}[f(x) \cdot g(x)] = f'(x) \cdot g(x) + f(x) \cdot g'(x)$$

## Uogólnienie dla n-tego rzędu

Dla pochodnych wyższych rzędów reguła Leibnitza przyjmuje postać:

$$\frac{d^n}{dx^n}[f(x) \cdot g(x)] = \sum_{k=0}^{n} \binom{n}{k} f^{(k)}(x) \cdot g^{(n-k)}(x)$$

gdzie:
- $\binom{n}{k}$ - współczynnik dwumianowy
- $f^{(k)}(x)$ - k-ta pochodna funkcji $f$
- $g^{(n-k)}(x)$ - $(n-k)$-ta pochodna funkcji $g$

## Przykłady

### Przykład 1: Pierwsza pochodna

Niech $f(x) = x^2$ oraz $g(x) = \sin(x)$

$$\frac{d}{dx}[x^2 \sin(x)] = 2x \cdot \sin(x) + x^2 \cdot \cos(x)$$

### Przykład 2: Druga pochodna

Dla $f(x) = e^x$ oraz $g(x) = x^2$:

$$\frac{d^2}{dx^2}[e^x \cdot x^2] = e^x \cdot x^2 + 2 \cdot e^x \cdot 2x + e^x \cdot 2$$

$$= e^x(x^2 + 4x + 2)$$

## Zastosowania

Reguła Leibnitza ma szerokie zastosowanie w:
- Analizie matematycznej
- Równaniach różniczkowych
- Fizyce teoretycznej
- Mechanice kwantowej
