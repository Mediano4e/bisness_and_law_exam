# Формулы с практических занятий

## Производственная мощность

$$ М = \cfrac{П}{З_{ед}}  $$
- П — пропускная способность(общий объем работ, который может быть выполнен при имеющихся основных фондах)
- З<sub>ед</sub> — объёмная загрузка единицы продукции

## Среднегодовая мощность

$$ М_{сг} = M_{вх} + \cfrac{\sum М_{вв} \cdot n_1}{12} - \cfrac{\sum М_{выб} \cdot n_2}{12} $$
- М<sub>сг</sub> — среднегодовая мощность
- М<sub>вх</sub> — входная мощность
- М<sub>вв</sub> — введённая мощность
- М<sub>выб</sub> — выбывшая мощность

### Пример задачи

Определить среднегодовую мощность, учитывая, что входная мощность 1 050 000 000, среднегодовой прирост за счёт модернизации 100 000 000, за счёт нового производства 50 000 000, за счёт реконструкции 30 000 000, выбывшая мощность 260 000 000 в том числе выбывшие площади на 40 000 000 с 1 ноября, выбывшее оборудование 20 000 000 с 1 декабря, коэффициент использования среднегодовой можности 87%.


## Мощность конвеера

$$ М_к = \cfrac{F_{эф}}{r}  $$
- М<sub>к</sub> — мощность конвеера
- F<sub>эф</sub> — время чистой работы 
- r — такт конвеера

$$ F_{эф} = d \cdot t \cdot S \cdot (1 - \cfrac{a}{100}) $$
- d — количество рабочих дней
- t — время смены
- S — количество смен
- a — потери времени на ремент и обслуживание

### Пример задачи

Определить мощность конвеера по производству планшетов, такт которого 2.6 минуты, при этом в году 365 дней, 111 дней выходных и праздничных, 5 дней предпраздничных, режим работы двусменный, потери времени на обслуживание 6.2%.

## Процентная ставка
$$ r = \cfrac{j}{P_0 \cdot n} $$
- r — процентная ставка
- j — величина дохода владельца
- P<sub>0</sub> — первоначальный капитал
- n — срок ссуды в годах

### Наращенная сумма по простой процентной ставке 

$$ S = P_0 \cdot (1 + n \cdot r) $$

или, если не целый год

$$ S = P_0 \cdot (1 + \cfrac{t \cdot r}{k}) $$

- P<sub>0</sub> — первоначальный капитал
- r — процентная ставка
- n — срок ссуды в годах

### Наращенная сумма по сложной процентной ставке 
Сложные — проценты полученные на реинвестированные проценты

$$ S = P_0 \cdot (1 + r)^n $$

или, если не целый год

$$ S = P_0 \cdot (1 + \cfrac{r}{m})^{n \cdot m} $$

- P<sub>0</sub> — первоначальный капитал
- r — процентная ставка
- n — срок ссуды в годах

### Примеры задач

#### Задача 1

Фирма приобрела в банке вексель, по которому через год должна получить 66 000 (наминальная стоимость векселя). В момент приобретения стоимость векселя 30 000. Определить нарощенную сумму долга при возврате кредита полностью 18 января в размере 50 000, срок возврата кредита 3 марта, процентная ставка 80% годовых.

#### Задача 2

Определить нарощенную сумму по годовому депозиту при условии 50% ставка, каждый следующий квартал +8%, проценты начисляются на первоначальную сумму 500 000.

#### Задача 3

Определить время для увеличения капитала в 3 раза, используя простую и сложную ставки в 10%.

#### Задача 4

Депозит в размере 500 000 внесён в банк под 10% на 3 года. Определить нарощенную сумму со сложными процентами при ежеквартальном/ежемесячном начислении.

#### Задача 5

Рассчитать будущую стоимость 1000 у.е. для следующих ситуаций:
1. 5 лет, 8% ежегодное начисление
2. 5 лет, 8% полугодовое начисление
3. 5 лет, 8% ежеквартальное начисление

## Оценка предполагаемого времени работ

### Мат.ожидание
#### Это приближённое математическое ожидание времени выполнения задачи с учетом неопределённости и вариативности

$$ t = \frac{t_{min} + 4 t_{н.в.} + t_{max}}{6} $$


-  t<sub>min</sub>  - оптимистичная оценка времени (минимально возможное время выполнения задачи).

-  t<sub>max</sub> - пессимистичная оценка времени (максимально возможное время).

-  t<sub>н.в.</sub> - наиболее вероятное время выполнения задачи.

### Дисперсия
#### Cтепень неопределённости или риска в оценке сроков

$$ sigma^2 = \left(\frac{t_{max} - t_{min}}{6}\right)^2 $$


# Формулы из бизнес плана

## Базовая выручка

$$ BP = Ц_i \cdot N $$
- BP — базовая выручка
- Ц<sub>i</sub> — цена единицы товара
- N — количество товара

## Прибыль

$$ П = BP - C_i \cdot N $$
- П — прибыль
- BP — базовая выручка
- C<sub>i</sub> — себестоимость единицы товара
- N — количество товара

## Коэффициент рентабельности

$$ R_i = \cfrac{Ц_i - C_i}{C_i} = \cfrac{П_i}{C_i} $$
- R<sub>i</sub> — рентабельность продукции
- Ц<sub>i</sub> — цена единицы товара
- П<sub>i</sub> — прибыль с единицы товара
- C<sub>i</sub> — себестоимость единицы товара

## Рентабельность капитала

$$  K_t = \cfrac{1}{1+D} \cdot t $$
- K<sub>t</sub> — коэффициент рентабельности капитала
- D — норма дисконта (ставка рефинансирования нац. банка)
- t — год на который идёт расчёт

