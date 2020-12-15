# Rates and Kinetics Models of Catalytic Reaction

-----------

## 1. 순서

1. 우선 촉매 반응이 어떠한 kinetic model인지를 정해야한다.
2. kinetic model이 정해졌다면 그 때 촉매 반응속도식을 정하면 된다.

-----------

## 2. Kinetic Model : Langmuir Hinshelwood

### 1) 가정

1. 여러 종의 흡착물들이 있다면, 이들은 경쟁흡착을 한다.
2. 1 site에 1개의 흡착물만이 흡착을 한다. (Langmuir Isotherm)
3. 흡착된 species 끼리만 반응이 일어난다.
4. 흡착속도가 탈착속도보다 월등히 빠르다고 가정한다.

### 2) 반응속도

$$-\frac{1}{V}\frac{dN_A}{dt} = \frac{dC_A}{dt} = -r = k\theta_A\theta_B$$

<부피가 일정하다는 조건하에 생성된 반응속도식>

이 때, 반응속도식에 $P_A, P_B$ 가 들어있지 않은 것도 반응은 surface에서만 일어나기 때문이다.

### 3) Decomposition & Product not Adsorbed

$$A \to Product$$

$$-r_a = k_a(1-\theta_A)P_A . . . . ①$$
$$-r_d = k_d\theta_A . . . . ②$$
$$ \frac{r_a}{r_d}= K_{eq} . . . . ③$$
④ 식은 흡착속도와 탈착속도가 같은 지점. 즉 평형일 때를 말한다.
$$ k_a(1-\theta_A)P_A = k_d\theta_A . . . . ④$$
$$ \theta_A = \frac{k_aP_A}{k_d + k_aP_A} = \frac{K_{eq}P_A}{1+K_{eq}P_A}. . . . ⑤$$
$$ -r = -k\theta_A = -k\frac{K_{eq}P_A}{1+K_{eq}P_A}. . . . ⑤$$

### 4) Decomposition & Product can Adsorbed

$$A \to B+C$$

$$-r = k\theta_A(1-\sum\theta) . . . . ①$$

1. A,B,C 모두 흡착 가능하다.
2. 반응속도가 흡착된 coverage에 영향을 받는다.
3. reverse reaction은 존재하지 않는다.
4. _**여기서 $1-\sum\theta$가 들어가는 이유는 product $B+C$ 가 존재하기에 이 부분 coverage를 남겨놔야한다.**_ 

$$k_a(1-\sum\theta)P_A = k_d\theta_A \to K_A(1-\sum\theta)P_A = \theta_A. . . . ②$$
$$k_a'(1-\sum\theta)P_B = k_d'\theta_B \to K_ B(1-\sum\theta)P_A = \theta_B. . . . ②'$$
$$k_a''(1-\sum\theta)P_C = k_d''\theta_C \to K_C(1-\sum\theta)P_A = \theta_C. . . . ②''$$
$$ ② + ②' + ②'' = \sum\theta = K_A(1-\sum\theta)P_A + K_B(1-\sum\theta)P_B + K_C(1-\sum\theta)P_C$$
$$\sum\theta =  \frac{K_AP_A + K_BP_B + K_CP_C}{1 + K_AP_A + K_BP_B + K_CP_C}. . . . ③$$
$$ \theta_A = \frac{K_AP_A}{1 + K_AP_A + K_BP_B + K_CP_C} . . . . ④$$
$$ \theta_B = \frac{K_BP_B}{1 + K_AP_A + K_BP_B + K_CP_C} . . . . ④'$$
$$ -r = k\theta_A(1-\sum\theta) = -k\frac{K_AP_A}{(1 + K_AP_A + K_BP_B + K_CP_C)^2}. . . . ⑤$$

### 5) Bimolecular Reaction

$$A + B \to C$$

1. A,B,C 모두 흡착 가능하다.
2. 반응속도가 흡착된 coverage에 영향을 받는다.
3. reverse reaction은 존재하지 않는다.

$$-r = k\theta_A\theta_B . . . . ①$$
$$k_a(1-\sum\theta)P_A = k_d\theta_A \to K_A(1-\sum\theta)P_A = \theta_A. . . . ②$$
$$k_a'(1-\sum\theta)P_B = k_d'\theta_B \to K_B(1-\sum\theta)P_A = \theta_B. . . . ②'$$
$$k_a''(1-\sum\theta)P_C = k_d''\theta_C \to K_C(1-\sum\theta)P_A = \theta_C. . . . ②''$$
$$ ② + ②' + ②'' = \sum\theta = K_A(1-\sum\theta)P_A + K_B(1-\sum\theta)P_B + K_C(1-\sum\theta)P_C$$
$$\sum\theta =  \frac{K_AP_A + K_BP_B + K_CP_C}{1 + K_AP_A + K_BP_B + K_CP_C}. . . . ③$$
$$ \theta_A = \frac{K_AP_A}{1 + K_AP_A + K_BP_B + K_CP_C} . . . . ④$$
$$ \theta_B = \frac{K_BP_B}{1 + K_AP_A + K_BP_B + K_CP_C} . . . . ④'$$
$$ -r = -k\theta_A\theta_B = -k\frac{K_AP_AK_BP_B}{(1 + K_AP_A + K_BP_B + K_CP_C)^2}. . . . ⑤$$

### 6) Adsorption & Desorption with Dissociation

$$A_2 \rightleftharpoons 2A \to product$$

1. Dissoication이 일어나기 위해서는 서로 인접해있어야한다.
2. 반응속도는 $\theta_A$가 있는 만큼 조절된다.
3. Adsorption 할 때 남는 coverage가 2A로 두배가 빨라진다.
4. Desorption 할 때 coverage는 그대로.

$$-r = k\theta_{A} . . . . ①$$
$$k_a(1-\theta_A)^2P_A = k_d\theta_A^2 ②$$
$$\theta_A = \sqrt{KP_A}(1-\theta_A) . . . . ③$$
$$ \theta_A = \frac{\sqrt{KP_A}}{1 + \sqrt{KP_A}} . . . . ④$$
$$ -r = -k\theta_A = -k\frac{\sqrt{KP_A}}{1 + \sqrt{KP_A}} . . . . ⑤$$

-----------

## 2. Kinetic Model : Rideal Model

### 1. 가정

1. 기존 흡착물 $A$ 가 surface에 흡착되어있다.
2. 다른 흡착물 $B$ 가 기존 흡착물 $A$ 에 붙어서 반응한다.
3. 생성물 $C$ 가 탈착한다.

### 2. 반응속도

$$-r = k\theta_AP_B$$

기존에 흡착되어있던 $A$ 의 coverage + 새롭게 $A$ 와 반응하려는 $B$ 의 압력이 반응속도에 영향을 준다.

### 3. Example

$$2CO + O_2 \to 2CO_2$$

-----------

## 3. Activation Energy

### 3-1. 조건

1. $-r = k\frac{K_AP_A}{1+K_AP_A}$ 라고 가정!
2. $K_AP_A << 1$ 일 때, $-r = k_sK_AP_A$. $k_s$ 는 surface 에서의 반응속도상수
3. 실제 plot 한 $k_{exp} = k_sK_A$
4. $k_S = Ae^{\frac{-E_s}{RT}}$
5. $K_A = \frac{k_a}{k_d} = A'e^{\frac{-E}{RT}} = A'e^{\frac{(E_{des} - E_{ads})}{RT}}$
6. $\lambda = E_{des} - E_{ads}$ = heat of chemisorption (chemisorption 할 때 생기는 열)
7. $k_{exp} = k_sK_A = A''e^{\frac{-E_a}{RT}} = A''e\frac{\lambda - E_s}{RT} = $
8. _**plot에서 나타나는 activation energy는 $E_a = E_s - \lambda$, surface process에서의 activation energy와 chemisorption에서 생성된 열을 빼준 값이다.**_