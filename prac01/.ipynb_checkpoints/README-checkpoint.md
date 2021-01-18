# 1. Сходимости случайных величин
[colab url](https://colab.research.google.com/github/mathmechterver/stat2021/blob/master/prac01/stat01.ipynb)

### Видеоматериалы 
[Сходимости случайных величин](https://stepik.org/lesson/48680/step/2?unit=26451)

### Теория (курс Черновой)
[Сходимости почти наверное и по вероятности](https://nsu.ru/mmf/tvims/chernova/tv/lec/node53.html#SECTION0001210)

### Сходимость почти наверное

$$\xi_n \overset{\textrm{п.н.}}{\to} \xi$$

Если

$$P(\{ \omega \in \Omega : \xi_n(\omega) \underset{n \to \infty}{\to} \xi(\omega) \}) = 1$$ 

или

$$P(\{ \omega \in \Omega : \xi_n(\omega) \underset{n \to \infty}{\not\to} \xi(\omega) \}) = 0$$ 

или эквивалентно

$$\forall \varepsilon > 0 : P(\{ \omega \in \Omega : \sup_{k \geq n} |\xi_k(\omega)-\xi(\omega)| > \varepsilon \}) \underset{n \to \infty}{\to} 0$$

### По вероятности
$$\xi_n \overset{\mathbb{P}}{\to} \xi$$ 

Если

$$\forall \varepsilon > 0 : P(\{\omega \in \Omega : |\xi_n(\omega)-\xi(\omega)| > \varepsilon \}) \underset{n \to \infty}{\to} 0$$

------------------

# На паре

1. Рассмотрим последовательность $\xi_1, \ldots, \xi_n$, в которой все величины имеют разные распределения: величина  принимает значения $0$ и $n^7$ с вероятностями $1 - \frac{1}{n}$ и $\frac{1}{n}$. Докажите, что $\xi_n \xrightarrow[n \to \infty]{\mathbb{P}} 0 $.

2. Пусть $\xi_n \overset{\textrm{п.н.}}{\to} 1$ и $\mu_n \overset{\textrm{п.н.}}{\to} 1$. 
Тогда $\xi_n + \mu_n \overset{\textrm{п.н.}}{\to} 2$

3. Пусть $\xi_n \overset{п.н.}{\to} \xi$ и $g(x)$ - непрерывная функция. Докажите, что $g(\xi_n) \overset{п.н.}{\to} g(\xi)$ 

4. Пусть $(\xi_n - \xi)^2 \overset{п.н.}{\to} 0$. Доказать, что $\xi_n \overset{п.н.}{\to} \xi$.


# Дома

**1.** (1) Пусть $\xi_n \overset{\textrm{п.н.}}{\to} 1$ и $\mu_n \overset{\textrm{п.н.}}{\to} 1$. 
Тогда $\xi_n\mu_n \overset{\textrm{п.н.}}{\to} 1$

**2.** (1) Пусть $\xi_n \overset{\mathbb{P}}{\to} 1$ и $\mu_n \overset{\mathbb{P}}{\to} 1$. 
Тогда $\frac{1}{\xi_n + \mu_n} \overset{\mathbb{P}}{\to} \frac{1}{2}$

**3.** (1) Пусть $\xi_n \overset{\mathbb{P}}{\to} \xi$ и $g(x)$ - непрерывная, дифференцируемая и монотонно возрастающая функция. Докажите, что $g(\xi_n) \overset{\mathbb{P}}{\to} g(\xi)$.


**4.** (1) Пусть $\xi_n \overset{\textrm{п.н.}}{\to} \xi$ и $\mu_n \overset{\textrm{п.н.}}{\to} \eta$. 
Тогда $\xi_n + \mu_n \overset{\textrm{п.н.}}{\to} \xi + \eta$

**5.** (1) Пусть $\xi_n$ - последовательность независимых и равномерно распределенных на [0,1] случайных величин. 

Найдите распределение случайной величины $m_n=\min (\xi_1,\ldots,\xi_n)$. Докажите, что $m_n$ стремится почти наверное к 0