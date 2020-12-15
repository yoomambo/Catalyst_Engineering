# Catalysis

### cf) 용어정리

- Conversion : 반응이 일어난 반응물의 양 / input 양
- Selectivity : 내가 원하는 생성물의 양 / output 양
- Yield : 내가 원하는 생성물의 양 / input 양

------------

## 1. 정의

> _**어떤 공정에서 조성이나 구조의 변화 없이 반응물을 활성화시켜서 다른 물질로 만드는데 도움을 주는 물질을 촉매라고 한다.**_

------------

## 2. Catalytic Activity

> 내가 원하는 반응의 진행 정도를 촉매 활성이라 한다. 

보통 performance 측정은 다양한 방법으로 진행된다.

------------

## 3. Catalyst selectivity & functionality

ex) $Cu : CH_3OH \to HCHO$, $Al_2O_3 : 2CH_3OH \to $

같은 메탄올 반응이지만 copper는 산화반응, 산촉매인 Alumina는 isomerization 반응을 한다. 이는 촉매가 selectivity와 functionality를 각각 가지고 있음을 증명하는 예이다.

------------

## 4. Characterization

### 4-1. Selective Chemisorption

1. 수소흡착법 : metal catalyst 에 주로 사용. TPD 방법을 쓴다.
2. CO 흡착법 : Pd는 수소를 과량으로 잡아둘 수 있기 때문에, Pd는 CO로 흡착시켜서 알아본다. TPD 방법을 쓴다.
3. 암모니아 or pyridine : 산촉매의 세기를 in-situ IR로 판단 가능하다.

### 4-2. Probe Reaction

1. alcohol
   1. Olefin : dehydration (탈수)
   2. Aldehyde : dehydrogenation (탈수소), 산화반응
2. Olefin
   1. isomerization 일어난다면 : 산촉매
   2. n-paraffin 생성된다면 : $Pt/Al_2O_3$, hydrogenation (수소첨가반응)

### 4-3. BiFunctionality

1. n-paraffin 을 dehydrogenation (탈수소), 산화반응 : $Pt/Al_2O_3$
2. olefin 을 isomerization : acid catalyst
3. olefin 을 hydrogenation (수소첨가), 환원반응 : $Pt/Al_2O_3$

두 개의 촉매가 동시에 진행한다.

------------

## 5. Negative Catalyst

### 5-1. 정의

> 어떤 반응속도를 느리게 만들어주는 촉매

- 보통 radical을 없앤다.
- MTBE : organic peroxide을 없앤다.

------------

## 6. Site

### 6-1. 정의

> 촉매에서 실제로 반응이 이루어지는 곳

### 6-2. 특징

- Coordinately Unsaturated Site : Dangling bond가 많은 곳
- corner or edge에 site가 많이 있다.

### 6-3. Characterization

1. coverage & 흡착열의 변화
2. coverage & 흡착 $E_a$ 의 변화
3. TPD
4. physical isobaric graph

### 6-4. Turnover Number

> 1 site 마다 반응하는 분자의 수

이걸 계산하려면 active site 의 갯수를 알아야한다. 이는 TPD를 쓰면 된다.

------------

## 7. Oxide Catalyst

1. 헤테로폴리산
2. perovskie : $ABO_3$
3. Hydroxyapatite ($Ca₅(PO₄)₃$)
   1. Redox Mechanism을 담당한다. 
   2. 산소와 직접 반응하면 발화하는 것들에게 최적화, Hydroxyaptite가 격자산소 형태로 공급하고 반응 후에는 공기중에 산소를 가져와서 채워넣는다.
   3. 구조가 안정적이다.
4. Zeolite : 큰 형태의 결정을 만들 수 있다. Si, Al 비율을 조절해서 proton 조절 가능

------------

## 8. Deactivation

- poisoning : metal의 active site 를 줄어들게 만드는 현상
- by product가 poisoning하는 경우도 있다.
- Pd는 CO가 치명적이다.
- S는 전기음성도가 커서 강력한 poisoning 물질이다.
- Effect
  - Physical : active site를 완전히 막거나 pore를 완전히 막아버린다.
  - Chemical : 전자를 가져온다.
- deactivation 속도를 아는 것도 중요하다. 이는 촉매의 교체 주기를 파악하는데 큰 도움이 된다.
- Metal Oxide의 Votalization : $Fe(MoO_4)_3$ 의 경우 $MoO_3$가 형성되어 승화

------------

## 9. Catalyst Thermodynamics

### 9-1. Equation

$$\triangle G = -RT\ln K = -RT\ln \frac{k_a}{k_d}$$

촉매에서의 반응이 평형을 이룰때의 자유에너지를 구하는 식이다. 여기서 $\triangle G = \triangle H - T \triangle S$ 식에서$\triangle H, \triangle S$ 을 알고있으면 바로 자유에너지를 구할 수 있다. 자유에너지로 adsorption에서의 반응속도상수와 desorption에서의 반응속도상수를 바로 구할 수 있다.

### 9-2. Shift of Equilibrium

1. Reactive Distillation : 반응과 증류를 같이하며 물이 생성물일 경우 평형이동시킨다.
2. Membrane Reactor : 수소 purification 작업을 할 때, Pd-Cu membrane이 수소만 빼내어서 평형이동 시켰다.

### 9-3. Rate Equation of catalyst

$$\ln K = -\frac{E_a}{RT}$$