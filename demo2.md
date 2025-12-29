
#### 7. QUINTO MÓDULO

**7.1 Inferencia Estadística**

Como se ha podido apreciar en los módulos anteriores, “La estadística trata
con recolección de datos, su análisis e interpretación”.

En Inferencia clásica y Teoría de decisiones, las observaciones son postuladas
tomando valores en forma aleatoria, la ley ó distribución de la(s) variable(s)
aleatoria(s) observable(s), _P_ , se asume pertenece a una familia paramétrica conocida
en su forma general, pero no se conoce el(los) valor(es) de parámetro(s). Un objetivo
fundamental de la inferencia estadística, es determinar valor(es) factibles de
parámetro(s) a partir de los datos.

La utilidad de los datos, generados a partir de muestras probabilísticas, es
inferir características esenciales, de la distribución de la muestra a la población

Una de las áreas asociadas a la inferencia estadística, es la estimación de
parámetros, para introducirnos en el tema se requieren algunas definiciones.

**Definición 7.1** Parámetro. Es una característica numérica de la distribución de la
población, que describe, parcial o completamente, la función de masa de probabilidad
de la característica de interés, habitualmente se simboliza por la letra griega ‘θ’.

**Definición 7.2** Espacio Paramétrico. Es el conjunto de posibles valores que puede(n)
ser considerado(s) para el(los) parámetro(s). Se simboliza por la letra griega
mayúscula ‘Θ’.

La Figura 7.1, se muestra esquemáticamente el problema de estimación.

```
Figura 7.1 El problema de estimación.
```


Los posibles valores de la muestra aleatoria constituyen el espacio de
información, y utilizando algún resumen apropiado (Estadística), construimos un
estimador de(l) parámetro(s) asociado(s) a la familia de distribución supuesta.

Distinguimos dos métodos en la estimación de parámetros: el primero
conocido como estimación puntual, trata de especificar un valor numérico para el
(los) parámetro(s) que se desea estimar; el segundo, que entrega un conjunto de
posibles valores asociados al parámetro como se muestra en la Figura 7.1. Pasemos a
revisar algunas de las técnicas de estimación.

**7.2 Método de Momentos**

Es quizás el método más antiguo para la estimación puntual de parámetros,
consiste en igualar los momentos apropiados de la distribución de la población con
los correspondientes momentos muestrales. Este método conduce a que existan,
tantas ecuaciones como parámetros se deseen estimar de la población.

**Definición 7.3** Momentos muestrales. Sean X 1 , X 2 , ... , X _n_ , una muestra aleatoria con

una función de masa de probabilidad _f_ ( _x_ ; θ). Entonces el _r-ésimo_ momento muestral
en torno a cero se define por:

```
1
```
```
1
MX
```
```
n
r
ri
n i =
```
### = ∑

donde se puede observar, que para el caso de _r_ = 1, se obtiene la media muestral,
mientras que para los casos de _r_ = 2, 3, 4, se obtienen indicadores que ayudan al
cálculo de medidas de variabilidad y forma respectivamente.

**Definición 7.4** Momentos Poblacionales. Sean X 1 , X 2 , ... , X _n_ , una muestra aleatoria

con una función de masa de probabilidad _f_ ( _x_ ; θ). Entonces el _r-ésimo_ momento
poblacional en torno a cero se define por:

```
μ r = „[X r ]
```
donde se puede observar, que para el caso de _r_ = 1, se obtiene la esperanza
matemática, mientras que para los casos de _r_ = 2, 3, 4, se obstinen indicadores que
ayudan al cálculo de medidas de variabilidad y forma poblacionales.

**APLICACIÓN 7.1** Sea X 1 , X 2 ,..., X _n_ una muestra aleatoria de tamaño _n_ de una

población la cual se supone tiene función de cuantía de probabilidad dada por:

[X = _x_ ] = _ppx_ (1− )^1 − _x x_ = 0,1.



Entonces el estimador de momentos _p_ , de _p_ , consiste en igualar el primer

momento muestral al primer momento poblacional, es decir:

„[X] = 1 × _p_ +0 × (1 – _p_ ) = _p_ = μ 1 ⇒ μ 1 = M 1

⇒ _p_  = X.

**APLICACIÓN 7.2** Suponga que el tiempo de vida [ **en años** ] de un componente
eléctrico se encuentra representada por:

```

```
```


```
```
 < <∞ >
=
```
```
−
```
```
e.o.c.
```
```
x x
f(x
0
```
```
3 , 0
)
```
```
3 4
α α α
```
Suponga además que se obtienen de estos componentes una muestra aleatoria
de _n_ de ellos, digamos, X 1 ,..., X _n_. El estimador de momentos α~, de α, a partir de la

muestra, consiste en igualar el primer momento muestral al primer momento
poblacional, es decir:

„[X] = 3 33 _x x_

```
α
```
```
α
```
```
∞
− ∂
```
## ∫ =

```
3
2
```
```
α = μ 1 ⇒ μ 1 = M 1
```
⇒

```
3
2
```
```
α = X ⇒ α~ =
```
```
2
3
```
```
X
```
**APLICACIÓN 7.3** Sea X 1 ,..., X _n_ una muestra aleatoria de tamaño 100 de una

población la cual se supone tiene función de densidad de probabilidades:

```
1
0 , 0
()
0
```
```
x
exp x
fx
e.o.c.
```
```
θ
θθ
```
```
 
− >>
=  


```
Entonces determinar el estimador de momentos θ, de θ, consiste en igualar el
primer momento muestral al primer momento poblacional, es decir:

„[X] =

```
xx
exp dx
```
```
α
```
```
θθ
```
```
∞

−
```
# ∫ 

```
= θ = μ 1 ⇒ μ 1 = M 1
```
⇒ X
~
θ =



**7.3 Métodos de Máxima Verosimilitud**

Es uno de los métodos más empleados para obtener estimadores puntuales,
selecciona como estimador el valor(es) del parámetro(s) que tiene(n) la propiedad de
maximizar la probabilidad de lo observado en la muestra aleatoria.

El método de máxima verosimilitud consiste en encontrar el valor(es) del
parámetro(s) que maximiza la función de masa (densidad) de probabilidad conjunta
de la muestra, llamada verosimilitud.

**Definición 7.5** Función de verosimilitud. Sean X 1 ,..., X _n_ , una muestra aleatoria con

una función de masa (densidad) de probabilidad _f_ ( _x_ ; θ), y sea _L_ (θ; X 1 , X 2 , ... , X _n_ )

la verosimilitud de la muestra como función de θ, la cuál se representa por:

_L_ (θ; **_x_** ) = _L_ (θ; X 1 , X 2 , ... , X _n_ ) = _f_ ( _x_ 1 ; θ) × _f_ ( _x_ 2 ; θ) × ... × _f_ ( _xn_ ; θ)

El método de máxima verosimilitud busca θˆ( _x_ 1 ,..., _xn_ ), función que depende

sólo de la muestra que maximiza _L_ (θ; **_x_** ). Para obtener estimadores máximo
verosímiles se utilizan las herramientas de cálculo matemático, además para
simplificar lo cálculos se utiliza el logaritmo de verosimilitud, llamada función de
_logverosimilitud_ , representada por:

_l_ (θ; **_x_** ) = _ln_ ( _L_ (θ; **_x_** )).

**APLICACIÓN 7.4** Sea X 1 ,..., X _n_ una muestra aleatoria de tamaño _n_ de una población

la cual se supone tiene función de densidad de probabilidades:

```
1
0 , 4
() 4 4
0
```
```
x
exp x
fx
e.o.c.
```
```
φ
φφ
```
```
 
− >>
=  −−


```
Utilizando herramientas de cálculo diferencial a la función _l_ (φ; **_x_** ), se obtiene

estimador máximo verosímil φˆ, de φ.

_l_ (φ, **_x_** ) = +
1 1

```
11
I()
4 4
```
```
n n
ii
i i
```
```
nln x ln x
φφ= =
```
```
 
−+
```
#### −−∑ ∏ \

###### ∂ l (φ, x )

```
∂ φ
```
```
= 0 ⇒
```
###### ()^4

```
n
φ
```
```
−
−
```
```
+
```
###### ()

```
2
1
```
```
1
4
```
```
n
i
i
```
```
x
φ − =
```
#### ∑ = 0 ⇒^ φˆ = X + 4



Para verificar que es un máximo local, la segunda derivada evaluada en φˆ es:

###### ∂^2 l (φ, x )

∂φ (^2) φ=X
(^) ⇒

###### ()

```
2
4
```
```
n
φ −
```
-

###### ()

```
3
1
```
```
2
4
```
```
n
i
i
```
```
x
φ − =
```
#### ∑^

###### ()

###### ()

```
1
3
```
```
42
```
```
4
```
```
n
i
i
```
```
nx φ
```
```
φ
```
```
=
```
```
−−
```
```
−
```
#### ∑

###### ; ()

```
3
φφ− 4 > 0 ∀> 4
```
(^) ()
1
42 = X2X= X
_n
i
i
nxnnn_ φ
=

#### −−∑ − − < 0. ⇒

φˆMV = X + 4

Luego _l_ (φˆMV, **_x_** ) es un máximo local, y bastara probar que es máximo global.

**APLICACIÓN 7.5** El número de clientes que llega a la fila de un cajero automático
entre las 14:00 y las 14:45 es modelado por la siguiente función de probabilidades:

```
[X = x ]
!
```
```
( 6)
( 6 )
```
```
x
```
```
e − x
=
```
```
− −
φ
φ
x = 0, 1, 2,... ; φ > 6
```
Considerando una muestra aleatoria de _n_ días, el estimador máximo verosímil

```
φˆ, de φ, esta dado por.
```
_l_ (φ, _x_

```
K
) = ln

```
```

```
```

```
```


```
```

```
```

```
```
 −
```
## ∏

```
=
```
```
n − −
```
```
i
```
```
x
```
```
x
```
_e_

```
1
```
```
( 6 )
```
```
!
```
```
( 6)
```
(^99)
= _ln_  − ∑

 − _n_ − _xi
e_^ (^9  6 ) ( 9 6) (^) 


!
1
_xi_

## = – n (φ – 6) + ∑

```
=
```
```
n
```
```
i
```
```
xi
1
```
```
ln (φ – 6) + ln 

```
```



```
```

!
```
```
1
xi
```
```
d l (φ, x )
d φ
= 0 ⇔ 9 ˆ=X+ 6
```
- _n_ +
    6

```
1
9 −
```
(^) ∑
=
_n
i
xi_
1
= 0 ⇔
Donde se pude verificar que _l_ (φˆMV, **_x_** ) es un máximo global.



**7.4 Propiedades de los Estimadores**

Para entender las propiedades asociadas a un estimador, considérese una
muestra aleatoria, X 1 , X 2 ,..., X _n_ , y T = _T_ (X 1 , X 2 ,..., X _n_ ) una función de la muestra,

entonces T es llamada Estadística.

**Estimadores Insesgados**

Cuando una estadística T, se utiliza con fines de estimación, recibe el nombre
de estimador, es deseable que los estimadores tengan algunas propiedades deseables,
algunas de las cuales pasamos a revisar.

**Definición 7.6** _Insesgamiento_. Sean T un estimador (estadística) de un parámetro θ, se
dice que T es un estimador insesgado (libre de sesgo), si „[T] = θ, para todos los
posibles valores de θ.

Básicamente lo que se desea es que el estimador, T, en promedio
(promediando sobre todas las posibles muestras), sea igual a θ, lo que se desea
estimar, bajo la hipótesis que la distribución de probabilidad de la población
propuesta es la correcta.

**APLICACIÓN 7.6** El número de clientes que llega a la fila de un cajero automático
entre las 14:00 y las 14:45 se encuentra representado por la siguiente función de
cuantía:

```
[X = x ]
!
```
```
( 6)
( 6 )
```
```
x
```
```
e − x
=
```
```
− −
φ
φ
x = 0, 1, 2, ... ; φ > 6
```
A partir de una muestra aleatoria de _n_ días, el estimador máximo verosímil,

calculado anteriormente es φˆ= X6+. ¿Es φˆ un estimador insesgado de φ?.

„[φˆ] = „[X+ 6 ] = „[X] + 6 =
_n_

```
1
```
## „[∑

```
=
```
```
n
```
```
i
```
```
Xi
1
```
```
] + 6
```
=
_n_

```
1
```
(^) ∑
=
_n
i_ 1
„[ _Xi_ ] + 6= 9 − 6 + 6 = φ
Luego se tiene que φˆ, es un estimador insesgado de φ.
**APLICACIÓN 7.7** Suponga que el tiempo de vida [ **en años** ] de un componente



eléctrico se encuentra modelada por:

```

```
```


```
```
 < <∞ >
=
```
```
−
```
```
e.o.c.
```
```
x x
f(x
0
```
```
3 , 0
)
```
```
3 4
α α α
```
A partir de una muestra aleatoria de _n_ componentes, el estimador de

momentos, es α~=
2
3

```
X.: ¿Es α~ un estimador insesgado de α?.
```
„[α~] =

```
2
3
```
```
„[X] =
```
```
2
3 n
```
## „[∑

```
=
```
```
n
```
```
i
```
```
Xi
1
```
```
] =
```
```
2
3 n
```
```
33
1
```
```
3
```
```
n
```
```
i
```
```
x dx
α
```
```
α
```
```
∞
−
=
```
#### ∑ ∫.

=

```
2
3 n
```
```
×
```
```
3
2
```
```
n
α = α.
```
Entonces se tiene que α~, es un estimador insesgado de α.

**APLICACIÓN 7.8** Sean _φ_ ˆ 1 y _φ_ ˆ 2 dos estimadores insesgados del parámetro

poblacional _φ_ , tal que V [ _φ_ ˆ 1 ] = 3V [ _φ_ ˆ 2 ]. Por razones técnicas se decide usar como

estimador a _φ_ ˆ 3 , donde:

_φφφ_ ˆˆˆ 31122 =+ α α , α 1 y α 2 ∈ ‘.

Para encontrar los valores de α 1 y α 2 que mantengan la propiedad de insesgamiento de _φ_ ˆ 3 ,
se tiene que:

„[ _φ_ ˆ 3 ] = „[α 11 _φφ_ ˆˆ +α2 2] = α 1 „[ _φ_ ˆ 1 ] + α 2 „[ _φ_ ˆ 2 ]

= α 1 _φ_ + α 2 _φ_

„[ _φ_ ˆ 3 ] = _φ_ ⇒ _φ_ ˆ 3 es Estimador Insesgado, luego:

α 1 +α 2 = 1

Otro criterio de evaluación de estimadores, es el _error cuadrático medio,_
midiendo la dispersión cuadrática media del estimador en torno lo que desea estimar.

**Definición 7.7** _Error Cuadrático Medio_. Sea T estimador de un parámetro θ, se
define el error cuadrático medio de T, como el valor esperado del cuadrado de la
diferencia entre T y θ, y se anota ECM (T).

ECM (T) = „[(T – θ)^2 ]



Desarrollando la expresión ECM (T) se obtiene:

ECM (T) = „[T^2 – 2Tθ + θ^2 ]

ECM (T) = „[T^2 ] – „[2Tθ] + „[θ^2 ]

ECM(T) = „[T^2 ] – 2θ„[T] + θ2.

ECM(T) = „[T^2 ] – 2θ„[T]+ θ^2 ] + („[T])^2 – („[T])^2

ECM(T) = („[T^2 ] – („[T])^2 ) + ((„[T])^2 – 2θ„[T]+ θ^2 )

ECM(T) = •[T] + („[T]-θ)^2

El _Error Cuadrático Medio_ de un estimador T, es la suma de dos cantidades
no negativas: una es la varianza del estimador (•[T]), mientras que la otra es el sesgo
al cuadrado ((„[T]-θ)^2 )^

(^) Un criterio para seleccionar un estimador, es que posea el error cuadrático
medio más pequeño entre los posibles estimadores de θ.
**Estimadores Eficientes
Definición 7.8** _Eficiencia relativa_. Sean T 1 y T 2 dos estimadores de θ. Se define la
eficiencia relativa entre T 1 y T 2 como:
_Ef_ (T 1 ;T 2 ) =^1
2
ECM(T )
ECM(T )
Si la eficiencia relativa es menor que uno, se concluye que el estimador T 1 es
más eficiente que el estimador T 2 , en caso contrario, se concluye que el estimador T 1
es más eficiente que el estimador T 2.
Resulta evidente que si un estimador es insesgado, el error cuadrático medio
es la varianza del estimador, y dentro de la clase de estimadores insesgados, el
problema de encontrar el mejor estimador, se reduce a encontrar el que tenga varianza
más pequeña.
**APLICACIÓN 7.10** Sean _φ_ ˆ 1 y _φ_ ˆ 2 , insesgados de _φ_ , tal que V [ _φ_ ˆ 1 ] = 3V[ _φ_ ˆ 2 ].
Entonces la eficiencia de los estimadores _φ_ ˆ 1 y _φ_ ˆ 2 es:
_Ef_ ( _φ_ ˆ 1 ; _φ_ ˆ 2 ) = 3 _φ_ ˆ 2 más eficiente



Si por razones técnicas se decide usar como estimador a _φ_ ˆ 3 , dado por:

_φφφ_ ˆˆˆ 31122 =+ α α , α 1 y α 2 ∈ ‘.

Para determinar los valores de α 1 y α 2 que mantengan la propiedad de

insesgamiento, y que la varianza de _φ_ ˆ 3 sea mínima. Se tiene que bajo el supuesto de

independencia entre _φ_ ˆ 1 y _φ_ ˆ 2 :

Ψ = •[ _φ_ ˆ 3 ] = •[α 11 _φφ_ ˆˆ +α2 2] = α 12 • [ _φ_ ˆ 1 ] + (1−α 1 )^2 • [ _φ_ ˆ 2 ] = α 12 r + (1−α 1 )^2
3

```
r
```
```
1
```
```
d
d
```
```
ψ
α
```
```
= 0 ⇒ α 1 =
```
```
1
4
```
```
⇒ α 2 =
```
```
3
4
```
Entonces ahora debería probarse que el estimador más eficiente de los tres
presentados es _φ_ ˆ 3 , como se prueba a continuación:

- [ _φ_ ˆ 3 ] =
    1
16

```
r +
9
16
```
```
r/3 =
1
4
```
```
r Ef ( φ ˆ 1 / φ ˆ 3 ) = 4 IE ( φ ˆ 2 / φ ˆ 3 ) =
4
3
```
**Consistencia en Media Cuadrática**

La consistencia mide la capacidad del estimador, de acercarse (en algún
sentido) cada vez más al verdadero valor de parámetro, a medida que el tamaño de
muestra crece.

**Definición 7.9** _Consistencia en media cuadrática_. Un estimador T, de un parámetro
desconocido θ, se dice consistente en media cuadrática, si se cumple:

ECM(T ) _n
n_

```
lim
→∞
```
```
= 0
```
**APLICACIÓN 7.11** El número de clientes que llega a la fila de un cajero automático
entre las 14:00 y las 14:45 se encuentra modelado por la siguiente función de cuantía:

```
[X = x ]
!
```
```
( 6)
( 6 )
```
```
x
```
```
e − x
=
```
```
−φ− φ
x = 0, 1, 2, ... ; φ > 6
```
¿Es el estimador, φˆ, consistente?.

Como se demostró anteriormente, φˆ es un estimador insesgado de _φ_ , basta



probar que:

ECM( )ˆ
_n_

```
lim φ
→∞
```
```
= []ˆ
n
```
```
lim φ
→∞
```
```
V = 0
```
- [X + 4] = •[X] =
    _n_

```
1
```
## • [∑

```
=
```
```
n
```
```
i
```
```
Xi
1
```
```
] =
n
```
```
1
```
```
1
```
```
[]
```
```
n
i
i
```
```
X
=
```
# ∑

```
V =
```
###### ()

```
2
4
n
```
```
φ−
```
###### ()

```
2
4
0
n
lim
n
```
```
φ
→∞
```
```
−
=


```
De donde φˆ, es un estimador consistente.

**APLICACIÓN 7.12** Suponga que los tiempos de vida [ **en años** ] de un componente
eléctrico de un particular de tipo de automóviles se encuentra modelada por:

```

```
```


```
```
 < <∞ >
=
```
```
−
```
```
e.o.c.
```
```
x x
f(x
0
```
```
3 , 0
)
α^34 α α
```
¿Es el estimador, α~, consistente?.

Comoα~ es un estimador insesgado de α, basta probar que:

ECM( )
_n_

```
lim α
→∞
```
```
 = []
n
```
```
lim α
→∞
```
```
V  = 0
```
- [
    2
    3

```
X] =
4
9
```
- [X] = 2
    4
9 _n_

## • [∑

```
=
```
```
n
```
```
i
```
```
Xi
1
```
```
] = 2
4
9 n
1
```
```
[]
```
```
n
i
i
```
```
X
=
```
# ∑

```
V
```
„[X^2 ] = 3 32 _x x_

```
α
```
```
α
```
```
∞
− ∂
```
## ∫ = 3α

(^2) „[X] = 3 33 _x x_
α
α
∞
− ∂

## ∫ =

```
3
2
```
```
α
```
- [X] = 3α^2 

```
9
4
```
```
− α =^2
```
```
3
4
```
```
α ⇒ • [α~] =
```
```
4
9 n
```
```
×^2
```
```
3
4
```
```
α =
```
```
2
```
```
3 n
```
```
α
```
```
2
0
n 3
lim
n
```
```
α
→∞
```
```

=

```
Luego α~, es un estimador consistente.



**7.5 Estimación por Intervalo**

La estimación puntual de un parámetro poblacional adolece del siguiente
defecto: La probabilidad de que el estimador coincida con el verdadero valor del
parámetro es muy pequeña y en el caso continuo nula. Los intervalos de _confianza_
resuelven este inconveniente, ofreciéndonos un rango para los posibles valores del
parámetro poblacional.

**Definición 7.10** Sea _X_ 1 , _X_ 2 ,..., _Xn_ una muestra aleatoria desde _f_ ( _x_ ; θ), donde _f_ ( _x_ ; θ) es

una función de masa (densidad) de probabilidades dependiendo de un parámetro
desconocido θ. Sean T 1 y T 2 dos estadísticos tales que T 1 ( _x_ ) < T 2 ( _x_ ), para casi todo _x_

###### y P(T 1 ≤θ≤T 2 ) = γ, donde γ no depende de θ. Se dice que [ T 1 , T 2 ] es un intervalo

de confianza para θ con 100γ% de confianza.

**Observaciones** :

- 1.- T 1 y T 2 reciben el nombre de cota inferior y superior de confianza.
- 2.- γ recibe el nombre de coeficiente de confianza.
- 3.- [] _T_ 1 , _T_ 2 es un intervalo aleatorio, ya que sus extremos son **_v.a_**.

**Definición 7.11** En las mismas condiciones de la definición 7.10. Sea T 1 un estadístico

que cumple con P (T 1 ≤θ) = γ. Se dice que T 1 es un limite inferior de confianza

para θ con 100γ% de confianza.

**Definición 7.12** En las mismas condiciones de la definición 7.10. Sea T 2 un estadístico
que cumple con y P (T 2 ≥θ) = γ. Se dice que T 2 es un limite superior de confianza

para θ con 100γ% de confianza.

Existen técnicas para construir intervalos (regiones) de confianza, y una de
ellas es la del pivote que pasamos a presentar.

**Cantidad Pivotal**

Sea _X_ 1 , _X_ 2 ,..., _Xn_ una _m.a_. ( _n_ ) desde _f_ ( _x_ ; θ) y _Q_ = _Q_ ( _X_ 1 ,..., _Xn_ ). Si la

distribución de _Q_ es independiente de θ, se dice que Q es una _Cantidad Pivotal_.

**Aplicación** : Sea _X_ 1 , _X_ 2 ,..., _Xn_ una _m.a_ .( _n_ ) desde familia Normal (YN(μ, σ^2 )con

```
media μ y varianza conocida σ^2 , luego
```
```
Q = X – μ Î Q ≈N (0,
n
```
```
2
σ ) Î Q es cantidad pivotal.
```


**Intervalo de Confianza para la Media Poblacional**

Sea _X_ 1 , _X_ 2 ,..., _Xn_ una _m.a_ .( _n_ ) desde familia Normal (YN(μ, σ^2 ), como X es

el mejor estimador de μ, entonces si se conoce σ^2 , se tiene que:

```
Z =
σ
```
```
(X - μ) n
≈N (0, 1) Î Z es pivote
```
Luego dado γ, se requiere determinar los valores más apropiados de _q_ 1 y _q_ 2

que cumplan con:

```
[ q 1 ≤
σ
```
```
(X - μ) n
≤ q 2 ] = γ
```
Como se puede observar de las gráficas existen muchos (infinitos) valores de
_q_ 1 y _q_ 2 que satisfacen lo anterior, sin embargo, se puede probar que si se desea

minimizar la longitud del intervalo de confianza, los valores de _q_ 1 y _q_ 2 deben ser

aquellos que produzcan igualdad de probabilidades en las colas, es decir:

```
q 2 = Z
2
```
```
1 + γ y q 1 = - q 2^
```
Luego si tomamos α= 1 −γ, se tiene:

[Z α (^) / 2 ≤
σ
(X - μ) _n_
≤ Z1 – α (^) / 2 ] = 1-α



[Zα (^) / 2
_n_
σ ≤
X - μ ≤ Z1 – α (^) / 2
_n_
σ
] = 1-α
[Zα (^) / 2
_n_
σ
– X≤ -μ ≤ Z1 – α (^) / 2
_n_
σ

- X] = 1-α

[X – Zα (^) / 2
_n_
σ ≥ μ ≥ X – Z
1 – α (^) / 2
_n_
σ ] = 1-α
[X – Z1 – α (^) / 2
_n_
σ
≤^ μ^ ≤^ X – Z α (^) / 2
_n_
σ ] = 1-α
Pero como Zα (^) / 2 = – Z1 – α (^) / 2
[X – Z1 – α (^) / 2
_n_
σ ≤ μ ≤ X + Z
1 – α (^) / 2
_n_
σ ] = 1-α
Con lo anterior se concluye que el intervalo del (1-α)% de confianza para la
media poblacional está dado por:
IC (μ):= [X ∓ Z1 – α (^) / 2
_n_
σ
]
Si se tiene una _m.a_ .( _n_ ) _X_ 1 , _X_ 2 , ... , _Xn_ tal que _Xi_ ≈N(μ, σ^2 ), con varianza
poblacional σ^2 desconocida, como sabemos _S_^2 es el mejor estimador de σ^2 , luego se
tiene que:
T =
_s_
(X - μ) _n_
≈ ℑ **_t-Student_** (n – 1) Î T es cantidad pivotal.



Análogo al caso anterior, dado γ (coeficiente de confianza), para determinar

los valores de _q_ 1 y _q_ 2 que minimicen la longitud del intervalo de confianza, se

escogen con igualdad de probabilidades en las colas, es decir:

_q_ 1 = _t_ α (^) /
2 ( _n_ – 1) = – _t_ 1 – α^ / 2 ( _n_ – 1)
[ _q_ 1 ≤^
_s_
(X - μ) _n_
(^) ≤ _q_ 2 ] = γ (^) _q_
2 = _t_ 1 – α^ / 2 ( _n_ – 1)
Se tiene que:
[ _t_ α (^) / 2 ( _n_ – 1)
_n
s_
≤ X - μ ≤ _t_ 1 – α (^) / 2 ( _n_ – 1)
_n
s_
] = 1-α
[ _t_ α (^) / 2 ( _n_ – 1)
_n
s_ – X
≤ – μ^ ≤^ _t_ 1 – α (^) / 2 ( _n_ – 1)
_n
s_ –X] = 1-α
[X – _t_ α (^) / 2 ( _n_ – 1)
_n
s_ ≥ μ ≥ X – _t_
1 – α (^) / 2 ( _n_ – 1)
_n
s_ ] = 1-α
[X – _t_ 1 – α (^) / 2 ( _n_ – 1)
_n
s_ ≤ μ ≤ X – _t_
α (^) / 2 ( _n_ – 1)
_n
s_ ] = 1-α
Î ( _t_ α (^) / 2 ( _n_ – 1) = – _t_ 1 – α (^) / 2 ( _n_ – 1))
[X – _t_ 1 – α (^) / 2 ( _n_ – 1)
_n_

##### s ≤ μ ≤ X + t

1 – α (^) / 2 ( _n_ – 1)
_n
s_ ] = 1-α
Luego el intervalo de confianza del (1-α)% para la media poblacional es:
IC (μ):= [X ∓ _t_ 1 – α (^) / 2 ( _n_ – 1)
_n
s_
]
Si el tamaño de la muestra es grande (mayor que 50), utilizando Teorema del
Limite Central, el intervalo de confianza toma de la siguiente forma:
IC (μ):= [X ∓ Z1 – α (^) / 2
_n
s_
]
Notemos que es importante distinguir cuando la varianza poblacional es
conocida o desconocida. Si a partir de la muestra aleatoria se determine una varianza,
ésta es la muestral, por lo tanto lo correcto es utilizar un intervalo de confianza
considerando la distribución **_t - Student_** , si el tamaño de la muestra es superior a 40,
entonces empleamos el T.L.C. para aproximar por **distribución Normal**.



**Intervalos de Confianza para una Proporción Poblacional**

Sea _X_ 1 , _X_ 2 ,..., _Xn_ una _m.a_. ( _n_ ) desde Familia Binomial (ℑ **B** (1, p)).El

estimador de **p** sobre la base de la muestra es Pˆ = X. La distribución de Pˆ = X ,
para muestras grandes (empleando el T.L.C), se puede aproximar por:

**Nota** : Es una aproximación útil pero no completamente satisfactoria, debe utilizarse
con algunas recomendaciones entregadas en clases.

Un inconveniente de ésta aproximación para la construcción de intervalos de
confianza, es que la varianza del estimador depende del parámetro a estimar, lo cual
no permite un despeje sencillo, por lo que se decide estimar la varianza con los datos,
con lo cuál se tiene una doble aproximación:

Con esta aproximación se obtiene la siguiente cantidad pivotal:

```
Z =
```
```
n
```
```
Pˆ (1 - Pˆ)
```
```
(Pˆ - p)
≈ N (0,1) Î Z es cantidad pivotal
```
Luego dado (1-α), los valores de _q_ 1 y _q_ 2 que minimizan la longitud del

intervalo son, como se observó anteriormente:

[Pˆ – Z1 – α (^) / 2
_n_
Pˆ (1 - Pˆ)
≤ p≤ Pˆ + Z1 – α (^) / 2
_n_
Pˆ (1 - Pˆ)
] = γ
Luego el intervalo de confianza, del γ% para la proporción poblacional es:
IC (p):= [Pˆ ∓ Z1 – α (^) / 2
_n_
Pˆ (1 - Pˆ)
]
Se puede apreciar que los intervalos de confianza anteriores están compuestos
por un estimador puntual, más ó menos cantidad, esta cantidad recibe el nombre de,
**_error de estimación_** , que resultara útil para la determinación de tamaños de muestra.



**Intervalos de Confianza para la Varianza Poblacional**

Como se habrá observado en intervalos de confianza para la media, existen
dos situaciones, dependiendo si la varianza poblacional conocida ó desconocida,
siendo obviamente este último el caso más común.

Sea _X_ 1 , _X_ 2 ,..., _Xn_ una _m.a_. ( _n_ ) desde una familia Normal (YN(μ, σ^2 ), existen

dos posibilidades para la estimación de la varianza , la primera cuando la media
poblacional es conocida (caso extraño) y el segundo cuando la media poblacional es
desconocida. Ambas cantidades pivotales se expresan respectivamente por:

```
2
```
```
2
```
```
σ
```
```
n Sn ≈ ℑ 2
χ ( n )
χ^2 ( n ) Chi-cuadrado con n grados de libertad ( g. l .)
```
```
2
```
```
2
( - 1) - 1
σ
```
```
n Sn ≈ ℑ 2
χ ( n – 1)
χ^2 ( n – 1) Chi-cuadrado con n – 1 g. l.
```
## donde: ∑

```
=
```
```
−
=
```
```
n
```
```
i
```
```
i
n
n
```
```
X
S
1
```
```
2
2 ( μ)
```
## ∑

```
=
```
```
−
=
```
```
n
```
```
i
```
```
i
n
n
```
```
X
S
1
```
```
2
2
```
- 1
    - 1

```
( X)
```
Como se puede apreciar de las gráficas, la distribución Chi-cuadrado no tiene
la propiedad de simetría, por lo que tomar igualdad de probabilidades en las colas no
conduce a intervalos de longitud mínima, sin embargo son una buena aproximación
cuando la muestra es grande.



Considerando la cantidad pivotal para el caso más realista, es decir, se
desconoce la media poblacional, se obtiene:

##### [χα^2 / 2 ( n – 1) ≤

```
2
```
```
2
( - 1) - 1
σ
```
##### n Sn ≤ 2

```
χ 1 - α/ 2 ( n – 1)] = 1 – α
```
```
[
2
1
```
```
2
/ 2
( - 1)
```
```
( 1 )
```
```
−
```
```
χα −
```
```
n Sn
```
```
n
```
##### ≤

```
2
```
```
1
σ
```
##### ≤

```
2
1
```
```
2
1 - / 2
( - 1)
```
```
( 1 )
```
```
−
```
```
χ α −
```
```
n Sn
```
```
n
] = 1 – α
```
```
[
( 1 )
```
```
( - 1)
2
1 - / 2
```
```
2
1
χ α −
```
```
−
n
```
```
n Sn
```
##### ≤

```
2
```
##### σ ≤

```
( 1 )
```
```
( - 1)
2
/ 2
```
```
2
1
χα −
```
```
−
n
```
```
n Sn
] = 1 – α
```
Luego el intervalo del (1-α)% de confianza para la varianza poblacional está
dado por:

```
IC(σ^2 ):= [
( 1 )
```
```
( - 1)
2
1 - / 2
```
```
2
1
χ α −
```
```
−
n
```
```
n Sn
;
( 1 )
```
```
( - 1)
2
/ 2
```
```
2
1
χα −
```
```
−
n
```
```
n Sn
]
```
**APLICACIÓN 7.13** ‘ _Entradas y Salidas de efectivo de un negocio_ ’. Las entradas ( **_x_** ) y
salidas ( **_y_** ) semanales de efectivo de un negocio [ **en UF** ] son variables aleatorias. Los
siguientes datos proporcionan los valores de **_x_** e **_y_** durante 28 semanas. Suponga que



**_x_** e **_y_** están normalmente distribuidas.

```
x y x y x y x y
42 25 23 36 82 72 86 68
65 37 63 70 28 39 68 72
76 83 40 51 61 27 53 60
92 36 70 39 75 38 87 65
37 73 82 36 83 27 63 80
47 23 90 82 60 78 47 62
27 97 68 30 93 20 52 36
```
Definir las variables asociadas al problema, es siempre el primer paso en el
desarrollo de todo problema.

X:=Entradas semanales en efectivo del negocio [ **UF** ] X ∼ N (μ _x_ , σ^2 _x_ )

Y:= Salidas semanales en efectivo del negocio [ **UF** ] Y ∼ N (μ _y_ , σ^2 _y_ )

_Datos_ : _x_ = 62,86 _sx =_ 20,75 _nx =_ 28

_y_ = 52,21 _sy =_ 22,45 _ny =_ 28

Determinar intervalos del 95% de confianza para los parámetros.

I95%C (μ _x_ )= [X ∓ _t_ 1 – α (^) / 2 ( _nx_ – 1)
_x
x
n
S_
] ⇔ I95%C(. _x_ ) : [54,81 ; 70,90]
**_Interpretación_** : Con un 95% de confianza las entradas medias reales del negocio se
encuentra entre los límites 54,81 [ **UF** ] y 70,90 [ **UF** ].
I95%C (μ _y_ ) = [Y ∓ _t_ 1 – α (^) / 2 ( _ny_ – 1)
_y
y
n
S_
] ⇔ I95%C (. _y_ ) = [43,51; 60,92]
**_Interpretación_** : Con un 95% de confianza las salidas medias reales del negocio se
encuentra entre los límites 43,51 [ **UF** ] y 60,92 [ **UF** ].
I95%C ( _σ_^2 _x_ ) = [
( 1 )
( - 1)
2
1 - / 2
2
χ α _x_ −
_x x
n
n S_
;
( 1 )
( - 1)
2
/ 2
2
χα _x_ −
_x x
n
n S_
] ⇔ I95%C ( _σ_^2 _x_ ) :[269,17 ; 797,90]
**_Interpretación_** : Con un 95% de confianza las varianzas de las entradas medias reales
del negocio se encuentra entre los limites 269,17[ **UF** ]^2 y 797,90 [ **UF** ]^2.
I95%C ( _σ_^2 _y_ ) = [
( 1 )
( - 1)
2
1 - / 2
2
χ α _y_ −
_y y
n
n S_
;
( 1 )
( - 1)
2
/ 2
2
χα _y_ −
_y y
n
n S_
] ⇔ I95%C ( _σ_^2 _y_ ) : [315,14 ; 934,16]
**_Interpretación_** : Con un 95% de confianza las varianzas de las entradas medias reales



del negocio se encuentra entre los limites 315,144 [ **UF** ]^2 y 934,16 [ **UF** ]^2.

Determine mediante un intervalo del 90% de confianza la verdadera
proporción de semanas donde se obtuvo pérdida.

```
X: = Nº de semanas donde se obtuvo pérdida. X ∼ B (28, p)
```
```
⇒ pˆ ∼ N (p,
28
```
```
pˆ(1−pˆ)
)
```
```
x y x y x y x y
42 25 23 36 Î 4 82 72 86 68
65 37 63 70 Î 5 28 39 Î 7 68 72 Î 9
76 83 Î 1 40 51 Î 6 61 27 53 60 Î 10
92 36 70 39 75 38 87 65
37 73 Î 2 82 36 83 27 63 80 Î 11
47 23 90 82 60 78 Î 8 47 62 Î 12
27 97 Î 3 68 30 93 20 52 36
```
```
⇒ pˆ=
28
```
```
12
```
I (^90) %C (p) = [Pˆ ∓ Z1 – α (^) / 2
_n_
Pˆ (1 - Pˆ)
] ⇔ I (^90) %C(p) = [27,47% ; 58,24%]
**_Interpretación_** : Con un 90% de confianza la verdadera proporción de semanas donde
el negocio tiene pérdida se encuentra entre los límites 27,47% y 58,24%.
Determine el nivel de confianza con el que se podría afirmar que la
proporción de semanas donde hubo pérdidas se encuentra entre los límites 27,86% y
57,86%.
Notemos que LS – LI = Pˆ + Z1 – α (^) / 2
_n_
Pˆ (1 - Pˆ)
– (Pˆ – Z1 – α (^) / 2
_n_
Pˆ (1 - Pˆ)
)
0.58 –0.28 = 2× Z1 – α (^) / 2
_n_
Pˆ (1 - Pˆ)
Z1 – α (^) / 2 = (0.58 – 0.28) ×^2
0. 57 0. 43
28
2
1
×
Z1 – α (^) / 2 = 1.603 ⇒ 1 –
2
α
= (0.9452 + 0.9458)
2
1
×
⇓
! = 0,1090 ⇒ # = 89,10%
**_Interpretación_** : Con un 89,10% de confianza la verdadera proporción de semanas



donde el negocio tiene pérdidas se encuentra entre los límites 27,86 % y 57,86%.

**APLICACIÓN 7.14** ‘ _El especialista de mercadeo_ ’. Un especialista en mercadeo de
cierta universidad, asegura que la proporción de hombres que utiliza una tarjeta de
crédito para hacer compras superiores a **US** $10 es inferior a la proporción de mujeres
que realiza este mismo tipo de pago. Como parte de un proyecto, el especialista,
encuesta en un centro comercial local a 50 hombres y 100 mujeres respecto a sus
hábitos de compra. De los hombres, 39 dijeron que habían utilizado este tipo de pago
en el último mes, mientras que 84 mujeres admitieron hacer este mismo tipo de pago.

```
X 1 = Nº de mujeres que utiliza la tarjeta de crédito en compras superiores a US $10.
X 2 = Nº de hombres que utiliza la tarjeta de crédito en compras superiores a US $10.
```
_Supuestos_ :

```
X 1 ∼ B (100, p 1 ) ⇒ pˆ 1 ∼ N (p 1 ,
100
```
```
pˆ 1 (1−pˆ 1 )
) ⇒ pˆ 1 = 0, 84
```
```
X 2 ∼ B (50, p 2 ) ⇒ pˆ 2 ∼ N (p 2 ,
50
```
```
pˆ 2 (1−pˆ 2 )
) ⇒ pˆ 2 = 0, 78
```
Intervalos del 90% de confianza para la proporción de mujeres, como para la
de hombres que utiliza el medio de pago en cuestión son:.

I (^90) %C (p) = [Pˆ _i_ ∓ Z1 – α (^) / 2 2
Pˆ (1 - Pˆ)
_n
i i_ ]=
**_Interpretación_** : Con un 90% de confianza se puede decir que la verdadera proporción
de mujeres que utiliza una tarjeta de crédito para hacer compras superiores a **US** $10 se
encuentra entre los limites 76,81% y 91,19%, mientras que la verdadera proporción
de hombres que utiliza una tarjeta de crédito para hacer compras superiores a **US** $
se encuentra entre los limites 66,52% y 89,48%.
Determine un intervalo del 95% de confianza para la verdadera proporción de
personas que no utiliza una tarjeta de crédito para hacer compras superiores a **US** $10.
X 3 :=Nº de personas que no usa la tarjeta de crédito en compras superiores a **US** $10.
X 3 ∼ B (150, p 3 ) ⇒ pˆ 3 ∼ N (p 3 ,
150
pˆ 3 (1−pˆ 3 )
) ⇒ pˆ 3 = 0,
I95%C (p) = [Pˆ ∓ Z1 – α (^) / 2 2
Pˆ (1 - Pˆ)
_n_
] ⇔ I95%C(p 3 ) : [12,84% ; 23,16%]
**_Interpretación_** : Con un 95% de confianza, se puede decir que la verdadera
proporción personas que no utiliza una tarjeta de crédito para hacer compras
superiores a **US** $10 se encuentra contenida entre los límites 12,84% y 23,16%.
I90%C (p 1 ) : [76,81% ; 91,19%]
I90%C (p 2 ) : [66,52% ; 89,48%]



Determine el tamaño de muestra necesario para que el error de estimación en
la verdadera proporción personas que no utiliza una tarjeta de crédito para hacer
compras superiores a **US** $10 no sea superior a 5% con un 95% de confianza.

Z1 – α (^) / 2 2
Pˆ (1 - Pˆ)
_n_
< 0.05 ⇒ Z0.975 2
0. 18 (1 - 0.18)
_n_
< 0.05
Error de Estimación
_n_ >

###### ()^2

```
2
0.975
0. 05
```
```
Z × 0. 18 ×( 1 − 0. 18 )
≈ 227
```
**_Interpretación_** : El tamaño de muestra necesario, para que con un 95% de confianza,
el error de estimación de la proporción personas que no utiliza una tarjeta de crédito
para hacer compras superiores a **US** $10 no sea mayor a 5%, es de al menos 227
personas.

Determine con un 96% de confianza, el tamaño de muestra necesario para que
la amplitud del intervalo para la proporción personas que no utiliza una tarjeta de
crédito en compras superiores a **US** $10 no sea mayor al 8%.

LS – LI = 2 × Z1 – α (^) / 2 2
Pˆ (1 - Pˆ)
_n_
< 0.08 ⇒ 2 × Z0.98 2
0. 18 (1 - 0.18)
_n_
< 0.08
_n_ >

###### ()^2

```
2
0.975
0. 08
```
```
4 ×Z × 0. 18 ×( 1 − 0. 18 )
≈ 390
```
**_Interpretación_** : El tamaño de muestra necesario, para que la amplitud del intervalo de
la proporción personas que no utiliza una tarjeta de crédito en compras superiores a
**US** $10 no sea mayor a 8%, es de un mínimo de 390 personas, con un 96% de
confianza.

**APLICACIÓN 7.15 ‘** _La decisión_ : AT&T ó _Sprint_ **’**. Un contador de una corporación en
los Estados Unidos, debe decidir si seleccionar a AT _&_ T ó Sprint para manejar su
servicio telefónico de llamadas a larga distancia de la empresa, El contador
seleccionó una muestra al azar de las llamadas realizadas en cada una de las
compañías reportando la siguiente información:

```
AT & T Sprint
Número de llamadas 145 102
Costo promedio US $ 4.07 US $ 3.89
Desviación estándar US $ 0.97 US $ 0.85
```


X = Costo de llamadas a larga distancia en la compañía AT&T.
Y =: Costo de llamadas a larga distancia en la compañía Sprint.

_Supuestos_ : X ∼ N (μ _x_ , σ^2 _x_ ) Y ∼ N (μ _y_ , σ^2 _y_ )

_Datos: x_ = 4,07 [ **US$** ] _sx_ = 0,97 [ **US$** ] _nx_ = 145

```
y = 3,89 [ US$ ] sy = 0,85 [ US$ ] ny = 102
```
Determine intervalos del 96% de confianza, para los parámetros de las
variables definidas.

```
I96%C (μ x ) =

```
```


```
```

```
```

```
```


```
```

−α
x
```
```
x
/
n
```
```
s
x ∓ Z 1 2 ⇔ I96%C(μ x ) = [3,90 ; 4,42]
```
**_Interpretación_** : Con un 96% de confianza, el verdadero costo medio de llamadas a
larga distancia en la compañía AT _&_ T se encuentra entre los limites
3,90 [ **US$** ] y 4,42 [ **US$** ].

```
I96%C (μ y ) :

```
```


```
```

```
```

```
```


```
```

−α
y
```
```
y
/
n
```
```
s
y ∓ Z 1 2 ⇔ I96%C(μ y ) = [3,72 ; 4,31]
```
**_Interpretación_** : Con un 96% de confianza, el verdadero costo medio de llamadas a
larga distancia con la compañía Sprint se encuentra entre los limites 3,72 [ **US$** ] y 4,31
[ **US$** ].

```
I96%C(σ^2 x ) :

```
```


```
```

```
```

```
```


```
```

```
```
−
−α^2
```
```
4
1 2
```
```
2
1
```
```
2
n
```
```
s
s Z
x
```
```
x
x ∓ /^ ⇔ I96%C(
```
```
2
σ x ) : [0,71 ; 1,17]
```
**_Interpretación_** : Con un 96% de confianza, la verdadera varianza del costo de
llamadas a larga distancia en la compañía AT _&_ T se encuentra entre los limites 0,71
[ **US$** ]^2 y 1,17 [ **US$** ]^2.

```
I96%C (σ^2 y ) =

```
```

```
```

```
```

```
```

```
```

```
```

```
```

−α −
2
```
```
4
1 2
```
```
2
1
```
```
2
n
```
```
s
s Z
y
```
```
y
y ∓ /^ ⇔ I96%C (
```
```
2
σ y ) = [0,51; 0,93]
```
**_Interpretación_** : Con un 96% de confianza, la verdadera varianza del costo de
llamadas a larga distancia en la compañía Sprint se encuentra entre los limites 0,51
[ **US$** ]^2 y 0,93 [ **US$** ]^2.

Determine un intervalo unilateral del 98% de confianza, que establezca una

```
GRANDES
```


cota superior para el verdadero costo medio de llamadas a larga distancias de AT _&_ T.

##### [μ ≤ k ] = 0.98 ⇔ [X − μ ≥ X– k ] = 0.98.

```
[
σ
```
```
(X − μ ) n
≥
σ
```
```
(X − k ) n
] = 0.98.
```
```
[
σ
```
```
(X − μ ) n
≤
σ
```
```
(X − k ) n
] = 0.02. Î
```
```
[
σ
```
```
(X − μ ) n
≤ Z!] = 0.02. Í
```
```
[X– Zα
n
```
```
σ
≤ μ ] = 0.02
```
```
[μ ≥ X+ Z1 – α
n
```
```
σ ] = 0.02 Î (Z
α = –Z1–α)
```
##### [μ ≤ X+ Z1 – α

```
n
```
```
σ ] = 0.98
```
```
I 98 %C (μ x ) =

```
```


```
```


```
```


```
```

−∞ + −α
x
```
```
x
n
```
```
S
; X Z 1 ⇒ I 98 %C (μ x ) = ] – ∞ ; 4,42]
```
**_Interpretación_** : Con un 98% de confianza se puede afirmar que, el costo medio de
llamadas a larga distancia con la compañía AT&T se encuentra bajo la cota de 4,42
[ **US$** ]^2. En términos prácticos el costo no puede ser negativo.

```
Z =
σ
```
(X - μ) _n_

```
Ð
```
```
σ
```
```
(X − k ) n
= Z!
```

