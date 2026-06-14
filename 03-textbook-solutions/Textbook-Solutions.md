---
title: "教材习题解答_逐题版"
date: 2026-05-29
tags:
  - discrete-math
  - textbook-exercises
  - per-exercise
cssclasses:
  - eduocr
---
> [!note] 相关
> 📖 详细解法：[[discrete-math/analysis/解法完全指南_v3.md]]
> 📋 作业解答：[[discrete-math/analysis/作业解答_41次完整版|作业解答]]



> [!note] 相关
> 📋 作业解答：[[discrete-math/analysis/作业解答_41次完整版.md|作业解答 41次]]
## 第一章 命题逻辑

#### 1-1

> 指出下列语句哪些是命题,哪些不是命题,如果是命题,指出它的真值:
> - a) 离散数学是计算机科学系的一门必修课。
> - b) 计算机有空吗?
> - c) 明天我去看电影。
> - d) 请勿随地吐痰!
> - e) 不存在最大质数。
> - f) 如果我掌握了英语、法语,那么学习其他欧洲语言就容易得多了。
> - g)  $9+5 \le 12$ .
> - h) x=3
> - i) 我们要努力学习。
> [1-1,1-2,(1)]

**解**：

a) 是命题,真值为 T。
b) 不是命题。
c) 是命题,真值要根据具体情况确定。
d) 不是命题。
e) 是命题,真值为T。
f) 是命题,真值为T。
g) 是命题,真值为 F。
h)不是命题。
i) 不是命题。

---
#### 1-2 举例说明原子命题和复合命题。 【1-1,1-2.(2)】 解 例如 原子命题:我今天去北京。

复合命题:如果天不下雨,那么今天将如期进行篮球赛。

---
#### 1-3

> 设 P 表示命题"天下雪", Q 表示命题"我将去镇上", R 表示命题"我有时间"。以符号形式写出下列命题:
> - a) 如果天不下雪和我有时间,那么我将去镇上。
> - b) 我将去镇上,仅当我有时间。
> - c) 天不下雪。
> d) 天下雪,那么我不去镇上。
> [1-1, 1-2, (3)]

**解**：

a)  $( P \land R) \rightarrow Q$ ; b)  $Q \rightarrow R$ ;

c)  $\neg P$ ;

d)  $P \rightarrow \neg Q$

---
#### 1-4

> 用汉语写出一个句子,对应下列每一命题:
> a)  $Q \leftrightarrow (R \land \neg P)$ ; b)  $R \land Q$ ;
> c)  $(Q \rightarrow R) \land (R \rightarrow Q)$
> [1-1,1-2,(4)]

**解**：

a) 设 Q: 我将去镇上。R: 我有时间。P: 天下雨。

Q  $\leftrightarrow$   $(R \land \neg P)$ : 我将去镇上当且仅当我有时间和天不下雨。

b) 设 R:我去镇上开会。Q:我去镇上买书。  $R \land Q$ :我去镇上开会并买书。

c) 设 Q:一个数是奇数。R:一个数不能被 2 除。  $(Q \rightarrow R) \land (R \rightarrow Q)$ :一个数是奇数,则它不能被 2 整除并 且一个数不能被2整除,则它是奇数。

---
#### 1-5

> 将下列命题符号化:
> - a) 王强身体很好,成绩也很好。
> - b) 小李一边看书,一边听音乐。
> - c) 气候很好或很热。
> - d) 如果 a 和 b 是偶数,则 a+b 是偶数。
> - e) 四边形 ABCD 是平行四边形,仅当其对边平行。
> [1-1,1-2,(5)]

**解**：

a) 设S:王强身体很好。R:王强成绩很好。则有:

$S \wedge R$

b) 设 *P*:小李看书。*Q*:小李听音乐。则有:

$P \wedge Q$

c) 设 P: 气候很好。R. 气候很热。则有: 
$P \lor R$

d) 设 Q:a 和 b 是偶数。R:a+b 是偶数。则有:

$Q \rightarrow R$

e) 设 Q:四边形 ABCD 是平行四边形。S:四边形 ABCD 的 对边平行。则有:

$Q \rightarrow S$

---
#### 1-6

> 将下列复合命题分成若干原子命题:
> - a) 天气炎热且正在下雨; b) 天气炎热但湿度较低;
> - c) 天正在下雨或湿度很高; d) 刘英与李进上山;
> - e) 老王或小李是革新者:
> - f) 如果你不看电影,那么我也不看电影:
> - g) 我既不看电视也不外出,我在睡觉:
> - h) 控制台打字机既可作输入设备,又可作输出设备。
> [1-1,1-2,(6)]

**解**：

a) 设 P:天气炎热。Q:正在下雨。则有:

$P \wedge Q$

b) 设 P:天气炎热。R:湿度较低。则有:

$P \wedge R$

c) 设 Q:天正下雨。S:湿度很高。则有:

Q \vee S

d) 设 E:刘英上山。G:李进上山。则有:

$E \vee G$

e) 设 W:老王是革新者。L:小李是革新者。则有:

$W \vee L$

f) 设 S: 你看电影。H: 我看电影。则有:

$\neg S \rightarrow \neg H$

g) 设 P:我不看电视,Q:我不外出。R:我不睡觉。则有:  $P \wedge Q \wedge \neg R$

h) 设 P:控制台打字机作输入设备。G:控制台打字机作输 出设备。则有:

$P \wedge G$

---
#### 1-7

> 判别下列公式哪些是合式公式,哪些不是合式公式:
> - a)  $(Q \rightarrow R \land S)$ ;
> - b)  $(P \rightleftarrows (R \rightarrow S))$ ;
> - c)  $(( \neg P \rightarrow Q) \rightarrow (Q \rightarrow P)));$  d)  $(RS \rightarrow T);$
> - e)  $((P \rightarrow (Q \rightarrow R)) \rightarrow ((P \rightarrow Q) \rightarrow (P \rightarrow R)))$ . [1-3.(1)]

**解**：

a) 不是合式公式。(若规定运算符次序后亦可作为合式 公式)

b) 是合式公式。c) 不是合式公式。(括弧不配对)
d) 不是合式公式。(RS之间缺联结词) e) 是合式公式。

---
#### 1-8

> 根据合式公式的定义,说明下列公式是合式公式:
> - a)  $(A \rightarrow (A \lor B))$ ;
> - b)  $(( A \land B) \land A);$
> - c)  $(( A \rightarrow B) \rightarrow (B \rightarrow A))$ :
> - d)  $((A \rightarrow B) \lor (B \rightarrow A))$
> $[1 \ 3, (2)]$

**解**：

a) A 是合式公式, $(A \lor B)$  是合式公式, $(A \to (A \lor B))$  是合式公式。这个过程可简记为:

$A; (A \lor B); (A \rightarrow (A \lor B))$

同理可记

b) A;  $\neg A$ ;  $(\neg A \land B)$ ;  $((\neg A \land B) \land A)$ .
c)  $A; \neg A; B; (\neg A \rightarrow B); (B \rightarrow A); ((\neg A \rightarrow B) \rightarrow (B \rightarrow A))$ .
d)  $A;B;(A \rightarrow B);(B \rightarrow A);((A \rightarrow B) \lor (B \rightarrow A))$ .

---
#### 1-9

> 对下列各式用指定的公式进行代换:
> - a)  $(((A \rightarrow B) \rightarrow B) \rightarrow A)$ ,用 $(A \rightarrow C)$ 代换 A,用 $((B \land C) \rightarrow A)$ 代换 B。
> - b) ((A→B) \ (B→A)),用B代换A,A代换B。【1-3.(3)】

**解**：

a)  $((((A \rightarrow C) \rightarrow ((B \land C) \rightarrow A)) \rightarrow ((B \land C) \rightarrow A)) \rightarrow ((A \rightarrow C))$ 。
b)  $((B \rightarrow A) \lor (A \rightarrow B))$

---
#### 1-10

> 下列几个式子中有哪几个是其他式子经过代换得到的。
> - a)  $(P \rightarrow (Q \rightarrow P))$ ;
> - b)  $((((P \rightarrow Q) \land (R \rightarrow S)) \land (P \lor R)) \rightarrow (Q \lor S))$ ;
> - c)  $(Q \rightarrow ((P \rightarrow P) \rightarrow Q));$  d)  $(P \rightarrow ((P \rightarrow (Q \rightarrow P)) \rightarrow P));$
> - e)  $(((R \rightarrow S) \land (Q \rightarrow P)) \land (R \lor Q)) \rightarrow (S \lor P))$ , [1-3. (4)]

**解**：

a) 是由 c)式进行代换得到,在 c)中用 Q 代换 P,  $(P \rightarrow P)$  代换 Q。

d) 是由 a)式进行代换得到,在 a)中用  $P \rightarrow (Q \rightarrow P)$ 代换 Q。
e) 是由 b)式进行代换得到,用 R 代换 P,S 代换 Q,Q 代换 R,P 代换 S.

---
#### 1-11

> 试把原子命题表示为 P,Q,R 等,然后用符号译出下列各句子:
> - a) 或者你没有写信,或者它在途中丢失了;
> - b) 如果张三和李四都不去,他就去;
> - c) 我们不能既划船又跑步;
> - d) 如果你来了,那末他唱不唱歌将看你是否伴奏而定。
> [1-3.(5)]

**解**：

a) 设 P:你没有给我写信。R:信在途中丢失了。则有:

$$P \overline{\vee} Q$$

b) 设 P:张三不去。Q:李四不去。R:他就去。则有:

$$(P \land Q) \rightarrow R$$

c) 设 P:我们能划船。Q:我们能跑步。则有:

$$\neg (P \land Q)$$

d) 设 P:你来了。Q:他唱歌。R:你伴奏。则有:

$$P \rightarrow (Q \leftrightarrow R)$$

---
#### 1-12

> 一个人起初说"占据空间的,有质量的而且不断变化的叫做物质";后来他改说"占据空间的有质量的叫做物质,而物质是不断变化的"。问他前后主张的差异在什么地方,试以命题形式进行分析。

**解**：

P:它占据空间。 R:它不断变化。

Q:它有质量。 S:它是物质。

这个人开头主张:  $(P \land Q \land R)$   $\rightleftarrows S$

后来改说:  $(P \land Q \rightleftarrows S) \land (S \rightarrow R)$

此人开头主张和后来主张不同点在于:后来认为如有  $P \land Q$  必同时有 R, 开头时没有这样的主张。

---
#### 1-13

> 用符号形式写出下列命题:
> - a) 假如上午不下雨,我去看电影;否则就在家里读书或看报。
> - b) 我今天进城,除非下雨。
> - c) 仅当你走,我将留下。
> [1-3.(7)]

**解**：

a) P:上午天下雨。Q:我去看电影。 R:我在家读书。S:我在家看报。

$$( P \rightarrow Q) \overline{\vee} ( P \rightarrow (R \vee S) )$$

b) P:我今天进城。Q:天下雨。

$$\neg Q \rightarrow P$$

c) P:你走了。Q:我留下。

$$Q \rightarrow P$$

---
#### 1-14

> 求下列各复合命题的真值表;
> - a)  $P \rightarrow (Q \lor R)$ ;
> - b)  $(P \lor R) \land (P \rightarrow Q)$ ;
> - c)  $(P \lor Q) \rightleftarrows (Q \lor R)$ ;
> - d)  $(P \lor \neg Q) \land R$ ;
> - e)  $(P \rightarrow (Q \rightarrow R)) \rightarrow ((P \rightarrow Q) \rightarrow (P \rightarrow R))$  [1-4, (1)]

**解**：

a) 见表 1-5。

表 1-5

| Р | Q                | R                | $Q \lor R$ | $P \rightarrow (Q \lor R)$ |
|---|------------------|------------------|------------|----------------------------|
| r | T                | T                | T          | T                          |
| T | T                | F                | T          | T                          |
| T | $\boldsymbol{F}$ | r                | r          | T                          |
| T | $\boldsymbol{F}$ | F                | F          | F                          |
| F | T                | T                | T          | T                          |
| F | T                | F                | T          | T                          |
| F | F                | $\boldsymbol{r}$ | T          | T                          |
| F | $\mathbf{F}$     | F                | F          | T                          |

b) 见表 1-6。

表 1-6

| P | Q | R | $P \lor R$ | P→Q | $(P \lor Q) \land (P \rightarrow Q)$ |
|---|---|---|------------|-----|--------------------------------------|
| Т | T | T | T          | T   | T                                    |
| Г | T | F | T          | T   | T                                    |
| T | F | T | T          | F   | $\boldsymbol{F}$                     |
| Г | F | F | T          | F   | F                                    |
| F | T | T | T          | T   | T                                    |
| F | T | F | F          | T   | $\boldsymbol{F}$                     |
| F | F | T | T          | r   | T                                    |
| 6 | F | F | F          | T   | F                                    |

c) 见表 1-7。

表 1-7

| ŗ,         | Q              | R              | $P \lor Q$       | Q V R | $(P \lor Q) \leftrightarrow (Q \lor R)$ |
|------------|----------------|----------------|------------------|-------|--------------------------------------------|
| r          | т              | T              | T                | T     | T                                          |
| r          | T              | <b>D</b> :     | $\boldsymbol{r}$ | T     | T                                          |
| T          | $\mathbf{b}^r$ | T              | T                | T     | T                                          |
| Y          | B'             | ₽ <sup>r</sup> | Tr               | F     | $\boldsymbol{F}$                           |
| b.         | T              | T              | T                | T     | $\boldsymbol{T}$                           |
| <b>6</b> ^ | T              | ₽              | T                | T     | T                                          |
| F          | $\mathbf{F}$   | T              | **F** '       | T     | F                                          |
| F          | $\mathbf{F}$   | F              | F                | F     | T                                          |

d) 见表 1-8。

表 1-8

| ₽ | Q | R | $\neg Q$ | $P \lor \neg Q$ | $(P \lor \neg Q) \land R$ |
|---|---|---|-------------|-----------------|---------------------------|
| T | T | T | F           | T               | Т                         |
| T | T | F | F           | T               | $\boldsymbol{F}$          |
| T | F | T | T           | T               | T                         |
| T | F | F | T           | T               | $\boldsymbol{F}$          |
| F | T | T | F           | F               | F                         |
| F | T | F | F           | F               | F                         |
| F | F | T | T           | T               | T                         |
| F | F | F | T           | T               | F                         |

e) 设 $S \Leftrightarrow (P \rightarrow (Q \rightarrow R)) \rightarrow ((P \rightarrow Q) \rightarrow (P \rightarrow R))$ , 见表 1-9。 表 1-9

| P | Q | **解**： | Q→R | $P \rightarrow (Q \rightarrow R)$ | P→Q | $P \rightarrow R$ | $(P \rightarrow Q) \rightarrow (P \rightarrow R)$ | s |
|---|---|--------------|-----|-----------------------------------|-----|-------------------|---------------------------------------------------|---|
| T | T | T            | T   | T                                 | T   | T                 | T                                                 | T |
| T | T | F            | F   | F                                 | T   | F                 | F                                                 | T |
| T | F | T            | T   | T                                 | F   | T                 | T                                                 | T |
| T | F | $\mathbf{F}$ | T   | T                                 | F   | F                 | T                                                 | T |
| F | T | T            | T   | T                                 | T   | T                 | T                                                 | T |
| F | T | F            | F   | T                                 | T   | T                 | T                                                 | T |
| F | F | T            | T   | T                                 | T   | T                 | T                                                 | T |

---
#### 1-15

> 试求下列命题的真值表并解释其结果。
> - a)  $(P \rightarrow Q) \land (Q \rightarrow P)$ ;
> - b)  $(P \land Q) \rightarrow P$ ;
> - c)  $Q \rightarrow (P \lor Q)$ ;
> - d)  $(P \rightarrow Q) \leftrightarrow (\neg P \lor Q)$ ;
> - e)  $( P \lor Q) \land ( ( P \land Q))$ .
> [1-4.(2)]
> T

**解**：

$F \supset F$

a) 从真值表 1-10 中可看出

$$(P \rightarrow Q) \land (Q \rightarrow P) \Leftrightarrow P \stackrel{\cdot}{\leftrightarrow} Q$$

表 1-10

| P                | Q | $P \rightarrow Q$ | $Q \rightarrow P$ | $(P \rightarrow Q) \land (Q \rightarrow P)$ |
|------------------|---|-------------------|-------------------|---------------------------------------------|
| T                | T | T                 | T                 | - **T**                                  |
| T                | F | $\boldsymbol{F}$  | T                 | F                                           |
| $\boldsymbol{F}$ | T | T                 | F                 | F                                           |
| F                | F | T                 | T                 | T                                           |

b) 从真值表 1-11 中可看出, $(P \land Q) \rightarrow P$  是一个永真式。
c) 从真值表 1-12 中可看出, $Q \rightarrow (P \lor Q)$  是一个永真式。
d) 从真值表 1-13 中可看出, $(P \rightarrow Q) \rightleftarrows (\neg P \lor Q)$  是永真式。
e) 从真值表 1-14 中可看出,



表 1-11

| P Q |   | $P \wedge Q$ | $(P \land Q) \rightarrow P$ |  |
|-----|---|--------------|-----------------------------|--|
| T   | T | T            | T                           |  |
| T   | F | F            | T                           |  |
| F   | T | F            | T                           |  |
| F   | F | F            | T                           |  |

表 1-12

| P Q |   | $P \lor Q$       | $Q \rightarrow (P \lor Q)$ |  |
|-----|---|------------------|----------------------------|--|
| T   | T | T                | T                          |  |
| T   | F | T                | T                          |  |
| F   | T | T                | T                          |  |
| F   | F | $\boldsymbol{F}$ | T                          |  |

表 1-13

| P                | Q | $\neg P$         | P→Q | $\neg P \lor Q$ | $(P\rightarrow Q) = (P \lor Q)$ |
|------------------|---|------------------|-----|--------------------|---------------------------------|
| T                | T | F                | T   | T                  | T                               |
| T                | F | F                | F   | F                  | T                               |
| $\boldsymbol{F}$ | T | T                | T   | T                  | T                               |
| F                | F | $\boldsymbol{T}$ | T   | $\boldsymbol{T}$   | T                               |

表 1-14

| P                | Q | $\neg P$ | ¬Q | $\neg P \lor Q$ | $\neg (P \land \neg Q)$ | $(\neg P \lor Q) \land (\neg (P \land \neg Q))$ |
|------------------|---|----------|----|--------------------|-------------------------|----------------------------------------------------------|
| T                | T | F        | F  | T                  | T                       | T                                                        |
| T                | F | F        | T  | F                  | F                       | F                                                        |
| $\boldsymbol{F}$ | T | T        | F  | T                  | T                       | T                                                        |
| F                | F | T        | T  | T                  | T                       | T                                                        |

---
#### 1-16

> 作出下列命题的真值表:并非"室内很冷或很乱",也不是"室外暖和且室内太脏"。 【1-4、(3)】
> **解** *P*:室内很冷。*Q*:室内很乱。 *R*:室外暖和。*S*:室内太脏。
> 本题可用符号表示为:
> $\neg (P \lor Q) \land \neg (R \land S)$
> 其真值表如表 1-15。
> 表 1-15
> | P                | Q                | **解**：     | S                | $\neg (P \lor Q)$ | $\neg (R \land S)$ | $\neg (P \lor Q) \land \neg (R \land S)$ |
> |------------------|------------------|------------------|------------------|----------------------|--------------------|------------------------------------------------|
> | T                | T                | T                | T                | F                    | F                  | F                                              |
> | T                | T                | T                | $\boldsymbol{F}$ | F                    | T                  | F                                              |
> | T                | T                | $\boldsymbol{F}$ | $\boldsymbol{T}$ | F                    | T                  | F                                              |
> | T                | T                | $\boldsymbol{F}$ | $\boldsymbol{F}$ | F                    | T                  | F                                              |
> | T                | $\boldsymbol{F}$ | T                | T                | F                    | F                  | F                                              |
> | T                | $\boldsymbol{F}$ | T                | $\boldsymbol{F}$ | F                    | T                  | F                                              |
> | T                | $\boldsymbol{F}$ | $\boldsymbol{F}$ | T                | F                    | T                  | F                                              |
> | T                | F                | F                | $\boldsymbol{F}$ | F                    | T                  | F                                              |
> | F                | T                | $\boldsymbol{T}$ | T                | F                    | F                  | $\boldsymbol{F}$                               |
> | F                | $\boldsymbol{T}$ | $\boldsymbol{T}$ | $\boldsymbol{F}$ | F                    | T                  | $\boldsymbol{F}$                               |
> | F                | $\boldsymbol{T}$ | $\boldsymbol{F}$ | T                | F                    | T                  | F                                              |
> | $\boldsymbol{F}$ | T                | $\boldsymbol{F}$ | $\boldsymbol{F}$ | F                    | T                  | F                                              |
> | F                | $\boldsymbol{F}$ | $\boldsymbol{T}$ | T                | T                    | F                  | $\boldsymbol{F}$                               |
> | $\boldsymbol{F}$ | $\boldsymbol{F}$ | $\boldsymbol{T}$ | $\boldsymbol{F}$ | T                    | T                  | T                                              |
> | $\boldsymbol{F}$ | F                | $\boldsymbol{F}$ | T                | T                    | T                  | $\boldsymbol{T}$                               |
> | F                | $\boldsymbol{F}$ | F                | F                | T                    | T                  | T                                              |

---

#### 1-17

> 试以真值表证明下列命题:
> - a) 合取运算之结合律;
> - b) 析取运算之结合律;
> - c) 合取(A)对析取(V)之分配律;
> - d) 德·摩根律。
> [1-4.(4)]

**解**：

a) 如表 1-16。

$P \wedge (Q \wedge R) \Leftrightarrow (P \wedge Q) \wedge R$

b) 如表 1-17。

$P \lor (Q \lor R) \Leftrightarrow (P \lor Q) \lor R$

表 1-16

| P | Q                | R | $Q \wedge R$     | $P \wedge (Q \wedge R)$ | $P \wedge Q$ | $(P \land Q) \land R$ |
|---|------------------|---|------------------|-------------------------|--------------|-----------------------|
| T | T                | T | T                | T                       | T            | T                     |
| T | T                | F | F                | F                       | Ť            | F                     |
| T | $\boldsymbol{F}$ | T | F                | F                       | F            | F                     |
| T | $\boldsymbol{F}$ | F | F                | F                       | F            | F                     |
| F | T                | T | T                | F                       | F            | F                     |
| F | T                | F | F                | F                       | F            | F                     |
| F | F                | T | F                | F                       | F            | F                     |
| F | $\boldsymbol{F}$ | F | $\boldsymbol{F}$ | F                       | F            | F                     |

表 1-17

| P | Q                | R | $Q \lor R$ | $P \lor (Q \lor R)$ | $P \lor Q$ | $(P \lor Q) \lor R$ |
|---|------------------|---|------------|---------------------|------------|---------------------|
| T | T                | T | T          | T                   | T          | T                   |
| T | T                | F | T          | T                   | T          | T                   |
| T | $\boldsymbol{F}$ | T | T          | T                   | T          | T                   |
| T | $\boldsymbol{F}$ | F | F          | T                   | T          | T                   |
| F | T                | T | T          | T                   | T          | T                   |
| F | T                | F | T          | T                   | T          | T                   |
| F | $\boldsymbol{F}$ | T | T          | T                   | F          | T                   |
| F | $\boldsymbol{F}$ | F | F          | F                   | F          | F                   |

c) 如表 1-18。

$P \land (Q \lor R) \Leftrightarrow (P \land Q) \lor (P \land R)$

表 1-18

| P | Q                | R | $Q \vee R$ | $P \wedge (Q \vee R)$ | $P \wedge R$ | $P \wedge Q$ | $(P \land Q) \lor (P \land R)$ |
|---|------------------|---|------------|-----------------------|--------------|--------------|--------------------------------|
| T | T                | T | T          | T                     | T            | T            | T                              |
| T | T                | F | T          | T                     | F            | T            | T                              |
| T | $\boldsymbol{F}$ | T | T          | T                     | T            | F            | T                              |
| T | $\boldsymbol{F}$ | F | F          | F                     | F            | F            | F                              |
| F | T                | T | T          | F                     | F            | F            | F                              |
| F | $\boldsymbol{T}$ | F | T          | F                     | F            | F            | F                              |
| F | $\boldsymbol{F}$ | T | T          | F                     | F            | F            | F                              |
| F | $\boldsymbol{F}$ | F | F          | F                     | F            | F            | F                              |

d) 如表 1-19。

| P | Q | $\neg P$         | $\neg Q$ | $\neg P \lor \neg Q$ | $\neg (P \land Q)$ | $\neg P \land \neg Q$ | $\neg (P \lor Q)$ |
|---|---|------------------|----------|----------------------------|-----------------------|-----------------------------|-------------------|
| T | T | F                | F        | F                          | F                     | F                           | F                 |
| T | F | F                | T        | T                          | T                     | F                           | F                 |
| F | T | T                | F        | T                          | T                     | $\boldsymbol{F}$            | F                 |
| F | F | $\boldsymbol{T}$ | T        | T                          | T                     | $\boldsymbol{T}$            | T                 |

---
#### 1-18

> 由表 1-20 求出公式 $E_1$, $E_2$, $E_3$, $E_4$, $E_5$, $E_6$。在表上有问号(?)的地方以 F 或 T 代入都可以,只要所求公式形式较简单。

表 1-20

| P | Q                | R | $E_1$            | $E_2$ | $E_3$ | $E_4$ | $E_5$      | $E_6$      |
|---|------------------|---|------------------|-------|-------|-------|------------|------------|
| T | T                | T | T                | F     | T     | T     | F          | ? **F** |
| T | T                | F | $\boldsymbol{F}$ | F     | T     | F     | F          | ? **F** |
| T | $\boldsymbol{F}$ | T | T                | F     | F     | T     | T          | ? **F** |
| T | $\boldsymbol{F}$ | F | F                | T     | F     | T     | ? **T** | ? F        |
| F | T                | T | T                | F     | F     | T     | T          | F          |
| F | T                | F | T                | F     | F     | F     | T          | F          |
| F | $\boldsymbol{F}$ | T | T                | F     | T     | T     | ? **T** | F          |
| F | F                | F | $\boldsymbol{F}$ | T     | F     | T     | ? T        | T          |

如表 1-20,对问号所填的情况,可得公式  $E_1 \sim E_6$ ,可表达为:

$E_1:(Q\rightarrow P)\rightarrow R$

$E_2: (P \land \neg Q \land \neg R) \lor (\neg P \land \neg Q \land \neg R)$

$E_3:(P\rightleftarrows Q)\land(Q\lor R)$

$E_4: ( P \lor Q \lor R) \land (P \lor Q \lor R)$

$E_5: ( P \lor Q \lor R) \land ( P \lor Q \lor R)$

$E_6: \neg (P \lor Q \lor R)$

---
#### 1-19

> 表 1-21 为含有两个变元的命题公式的各种情况的
> 真值表;对于每一列,试写出一个至多包含此两个变元的命题 公式。 【1-4.(6)】
> 表 1-21
> | P                | Q                | 1 | 2  | 3  | 4  | 5  | 6  | 7  |
> |------------------|------------------|---|----|----|----|----|----|----|----|
> | T                | T                | F | F  | F  | F  | F  | F  | F  | F  |
> | $\boldsymbol{T}$ | $\boldsymbol{F}$ | F | F  | F  | F  | T  | T  | T  | T  |
> | $\boldsymbol{F}$ | T                | F | F  | T  | T  | F  | F  | T  | T  |
> | F                | $\boldsymbol{F}$ | F | T  | F  | T  | F  | T  | F  | T  |
> | P                | Q                | 9 | 10 | 11 | 12 | 13 | 14 | 15 |
> | T                | T                | T | T  | T  | T  | T  | T  | T  | T  |
> | T                | F                | F | F  | F  | F  | T  | T  | T  | T  |
> | F                | T                | F | F  | T  | T  | F  | F  | T  | T  |
> | $\boldsymbol{F}$ | F                | F | T  | F  | T  | F  | T  | F  | T  |

**解**：

由上表可得有关公式为:

1. F; 2.  $\neg (P \lor Q)$ ; 3.  $\neg (Q \to P)$ ; 4.  $\neg P$ ; 5.  $\neg (P \to Q)$ ; 6.  $\neg Q$ ; 7.  $\neg(P \rightleftarrows Q)$ ; 8.  $\neg (P \land Q)$ ; 9.  $P \land Q$ ; 10.  $P \rightleftarrows Q$ ; 11. Q; 12.  $P \to Q$ ; 13. P; 14.  $Q \to P$ ; 15.  $P \lor Q$ ; 16.  $T$

---
#### 1-20

> 证明下列等价式:
> - a)  $A \rightarrow (B \rightarrow A) \Leftrightarrow \neg A \rightarrow (A \rightarrow \neg B);$
> - b)  $\neg (A \rightleftarrows B) \Leftrightarrow (A \lor B) \land \neg (A \land B)$ ;
> - c)  $\neg (A \rightarrow B) \Leftrightarrow A \land \neg B$ ;
> - d)  $\neg (A \leftrightarrow B) \Leftrightarrow (A \land \neg B) \lor (\neg A \land B);$
> - e)  $(((A \land B) \land C) \rightarrow D) \land (C \rightarrow (A \lor (B \land D))) \Leftrightarrow ((C \land (A \rightleftarrows B)) \rightarrow D);$
> - f)  $A \rightarrow (B \lor C) \Leftrightarrow (A \land \neg B) \rightarrow C$ ;
> - g)  $(A \rightarrow D) \land (B \rightarrow D) \Leftrightarrow (A \lor B) \rightarrow D$ ;
> - h)  $((A \land B) \rightarrow C) \land (B \rightarrow (D \lor C)) \Leftrightarrow (B \land (D \rightarrow A)) \rightarrow C$ .
> [1-4.(7)]

**证明**：

a)  $(A \rightarrow (B \rightarrow A))$  $\Leftrightarrow \neg A \lor (\neg B \lor A)$

$\Leftrightarrow A \lor ($

$\Leftrightarrow \neg A \rightarrow (A \rightarrow \neg B)$

b)  $\neg (A \leftrightarrow B) \Leftrightarrow \neg ((A \to B) \land (B \to A))$

$\Leftrightarrow \neg \left( \left( \neg A \lor B \right) \land \left( \neg B \lor A \right) \right)$

$\Leftrightarrow \neg \, ((\neg A \wedge \neg B) \vee (\neg A \wedge A)$

$\vee (B \wedge \neg B) \vee (B \wedge A))$

$\Leftrightarrow \neg (\neg (A \lor B) \lor (A \land B))$

$\Leftrightarrow (A \lor B) \land \neg (A \land B)$

c)  $\neg (A \rightarrow B) \Leftrightarrow \neg (\neg A \lor B) \Leftrightarrow A \land \neg B$
d)  $\neg (A \leftrightarrow B) \Leftrightarrow \neg ((A \rightarrow B) \land (B \rightarrow A))$

$\Leftrightarrow \neg ((\neg A \lor B) \land (\neg B \lor A))$

$\Leftrightarrow (A \land \neg B) \lor (B \land \neg A)$

e)  $(((A \land B \land C) \rightarrow D) \land (C \rightarrow (A \lor B \lor D)))$

$\Leftrightarrow (( (A B C)$

$\land ($

$\Leftrightarrow ( A \lor B \lor C \lor D)$

$\wedge ( C \lor A \lor B \lor D)$

$\Leftrightarrow ( C \lor D) \lor [( A \lor B) \land (A \lor B)]$

$\Leftrightarrow ( C \lor D) \lor [ (A \land B) \lor (B \land A) ]$

$\Leftrightarrow ( C \lor D) \lor$

$\Leftrightarrow \neg [C \land (\neg A \lor B) \land (\neg B \lor A)] \lor D$

$\Leftrightarrow \neg (C \land (A \rightarrow B) \land (B \rightarrow A) \lor D$

$\Leftrightarrow ((C \land (A \rightleftarrows B)) \rightarrow D)$

f)  $A \rightarrow (B \lor C) \Leftrightarrow \neg A \lor (B \lor C)$

$\Leftrightarrow \neg (A \land \neg B) \lor C \Leftrightarrow (A \land \neg B) \rightarrow C$

g)  $(A \rightarrow D) \land (B \rightarrow D) \Leftrightarrow ( A \lor D) \land ( B \lor D)$

$\Leftrightarrow \neg (A \land B) \lor$

$\Leftrightarrow (A \lor B) \rightarrow D$

h)  $((A \land B) \rightarrow C) \land (B \rightarrow (D \lor C))$

$\Leftrightarrow ($

$\Leftrightarrow ( \neg A \lor \neg B \lor C) \land ( \neg B \lor D \lor C)$

$\Leftrightarrow ( A \land D) \lor ( B \lor C)$

$\Leftrightarrow \neg B \lor (\neg A \land D) \lor C$

$\Leftrightarrow \neg \left( B \land \left( A \lor \neg D \right) \right) \lor C$

$\Leftrightarrow (B \land (A \lor \neg D)) \rightarrow C \Leftrightarrow (B \land (D \rightarrow A)) \rightarrow C$

---
#### 1-21 化简以下各式:

a)  $((A \rightarrow B) \rightleftarrows ($
b)  $A \lor ( A \lor (B \land B));$
c)  $(A \land B \land C) \lor ( A \land B \land C)$ .

[1-4, (8)]

**解**：  a)  $((A \rightarrow B) \leftrightarrow (\neg B \rightarrow \neg A)) \land C$

$\Leftrightarrow ((A \rightarrow B) \leftrightarrow (A \rightarrow B)) \land C \Leftrightarrow T \land C \Leftrightarrow C$

b)  $A \lor ( A \lor (B \land B)) \Leftrightarrow A \lor ( A \lor F)$

$\Leftrightarrow A \lor \neg A \Leftrightarrow T$

c)  $(A \land B \land C) \lor ($

$\Leftrightarrow (A \lor \neg A) \land (B \land C)$

$\Leftrightarrow \mathbf{T} \land (B \land C) \Leftrightarrow B \land C$

---
#### 1-22

> 如果  $A \lor C \Leftrightarrow B \lor C$ ,是否有  $A \Leftrightarrow B$ ? 如果  $A \land C \Leftrightarrow B \land C$ ,是否有  $A \Leftrightarrow B$ ? 如果  $A \Leftrightarrow B$ ? 如果  $A \Leftrightarrow B$ ? 【1-4.(9)】

**解**：

1) 设有某种指派,使公式 C 的真值为 T,但 A 的真值为 T,B 的真值为 F(或 A 为 F,B 为 T),则  $A \lor C$  和  $B \lor C$  的真值都 为 T,故  $A \lor C \Leftrightarrow B \lor C$  成立,但  $A \Leftrightarrow B$  不一定成立。

2)设有某种指派,使公式 C 的真值为 F,但 A 的真值为 T,B 的真值为 F(或 A 为 F,B 为 T),则  $A \land C$  和  $B \land C$  的真值均为 F。故  $A \land C \Leftrightarrow B \land C$  成立时, $A \Leftrightarrow B$  不一定成立。
3) 因为 $(A \rightarrow B) \Leftrightarrow ($

同理 $\neg A \Rightarrow \neg B \text{ 时}, B \Rightarrow A, \text{所以} \neg B \Leftrightarrow \neg A \text{ 时}, \text{必有 } A \Leftrightarrow B.$

---
#### 1-23

> 试证下列各式为重言式:
> - a)  $(P \land (P \rightarrow Q)) \rightarrow Q$ ;
> - b)  $\neg P \rightarrow (P \rightarrow Q)$ ;
> - c)  $((P \rightarrow Q) \land (Q \rightarrow R)) \rightarrow (P \rightarrow R);$
> - d)  $((a \land b) \lor (b \land c) \lor (c \land a)) \rightleftarrows ((a \lor b) \land (b \lor c) \land (c \lor a))$  [1-5. (1)]

**证明**：

a)
$$(P \land (P \rightarrow Q)) \rightarrow Q \Leftrightarrow (P \land (\neg P \lor Q)) \rightarrow Q$$
$\Leftrightarrow ((P \land \neg P) \lor (P \land Q)) \rightarrow Q$   $\Leftrightarrow (P \land Q) \rightarrow Q \Leftrightarrow \neg (P \land Q) \lor Q$   $\Leftrightarrow \neg P \lor \neg Q \lor Q \Leftrightarrow \neg P \lor T \Leftrightarrow T$

b)  $\neg P \rightarrow (P \rightarrow Q) \Leftrightarrow P \lor (\neg P \lor Q) \Leftrightarrow T \lor Q \Leftrightarrow T$
c) 因为  $(P \rightarrow Q) \land (Q \rightarrow R) \Rightarrow P \rightarrow R$  所以  $((P \rightarrow Q) \land (Q \rightarrow R)) \rightarrow (P \rightarrow R)$  为重言式。
d) 因为  $(a \land b) \lor (b \land c) \lor (c \land a)$   $\Leftrightarrow (b \land (a \lor c)) \lor (c \land a)$   $\Leftrightarrow (b \lor (c \land a)) \land ((a \lor c) \lor (c \land a))$  $\Leftrightarrow (b \lor c) \land (b \lor a) \land (a \lor c)$

所以  $((a \land b) \lor (b \land c) \lor (c \land a)) \rightleftarrows ((a \lor b) \land (b \lor c) \land (c \lor a))$  是重言式。

---
#### 1-24

> 不构造真值表证明下列蕴含式:
> - a)  $(P \rightarrow Q) \Rightarrow P \rightarrow (P \land Q)$ ;
> - b)  $(P \rightarrow Q) \rightarrow Q \Rightarrow P \lor Q$ ;
> - c)  $(Q \rightarrow (P \land \neg P)) \rightarrow (R \rightarrow (R \rightarrow (P \land \neg P)) \Rightarrow R \rightarrow Q$
> [1-5.(2)]

**证明**：

a) 解法 1 设  $P \rightarrow Q$  为 T,

(1) 若 P 为 T, 得 Q 为 T, 所以  $P \land Q$  为 T, 故  $P \rightarrow (P \land Q)$  为 T。
(2) 若 P 为 F , 得 Q 为 F , 所以 P ∧ Q 为 F , 故 P → (P ∧ Q) 为 T 。

法 2 设  $P \rightarrow (P \land Q) \rightarrow F$ ,则  $P \rightarrow T$ , $P \land Q \rightarrow F$ ,故必有  $P \rightarrow T$ , $Q \rightarrow F$ ,所以  $P \rightarrow Q \rightarrow F$ .

法 3  $(P \rightarrow Q) \Rightarrow (P \rightarrow (P \land Q))$

$\Leftrightarrow \neg (\neg P \lor Q) \lor (\neg P \lor (P \land Q))$  $\Leftrightarrow \neg (\neg P \lor Q) \lor ((\neg P \lor P) \land (\neg P \lor Q)) \Leftrightarrow T$

所以

$(P \rightarrow Q) \Rightarrow (P \rightarrow (P \land Q))$

b) 设  $P \lor Q$  为 F,则 P 为 F 且 Q 为 F,故  $P \rightarrow Q$  为 T,  $(P \rightarrow Q) \rightarrow Q$  为 F。所以 $(P \rightarrow Q) \rightarrow Q \Rightarrow P \lor Q$ 。
c) 设  $R \rightarrow Q$  为 F ,则 R 为 T ,Q 为 F 。因  $P \land \neg P$  为 F ,所以  $Q \rightarrow (P \land \neg P)$  为 T , $R \rightarrow (P \land \neg P)$  为 F ,于是得到: $R \rightarrow (R \rightarrow (P \land \neg P))$  为 F 。则

$$(Q \rightarrow (P \land \neg P)) \rightarrow (R \rightarrow (R \rightarrow (P \land \neg P)))$$

为F。即

$(Q \rightarrow (P \land \neg P)) \rightarrow (R \rightarrow (R \rightarrow (P \land \neg P)) \Rightarrow R \rightarrow Q$  成立。

---
#### 1-25

> 设 P 表示命题"8 是偶数"。Q 表示命题"糖是甜的",试以句子写出:
> - a)  $P \rightarrow Q$ ;
> - b) 写出 a)的逆换式;
> - c) 写出 a)的反换式;
> - d) 写出 a)的逆反式。
> [1-5, (3)]

**解**：

a) P→Q表示命题:如果8是偶数,则糖是甜的。

b) Q→P表示命题:如果糖是甜的,则8是偶数。
c)  $\neg P \rightarrow \neg Q$  表示命题:如果 8 不是偶数,则糖不是甜的。
d)  $\neg Q \rightarrow \neg P$  表示命题:如果糖不是甜的,则 8 不是偶数。

---
#### 1-26

> 叙述下列命题的逆换式和逆反式,并以符号写出:
> - a) 如果天下雨,我不去。
> - b) 仅当你走,我将留下。
> - c) 如果我不能获得更多帮助,我不能完成这个任务。
> [1-5.(4)]

**解**：

a) 设 P:天下雨。Q:我不去。有式  $P \rightarrow Q$ 。则其: 逆换式  $Q \rightarrow P$  表示命题:如果我不去,则天下雨。 逆反式  $\Box Q \rightarrow \Box P$  表示命题:如果我去,则天不下雨。 b) 在本题中,原命题:仅当你走我将留下,理解为:我留下的 必要条件是你走。或者就是你不走则我不留下。

设 S:你走了。R:我将留下。有式 R→S。

逆換式 S→R 表示命题:如果你走了则我将留下。

逆反式¬S→¬R表示命题:如果你不走,则我不留下。

c) 设 E:我不能获得更多帮助。H:我不能完成这个任务。

$$E \rightarrow H$$

逆换式  $H \rightarrow E$  表示命题: 我不能完成这个任务,则我不能获得更多帮助。

逆反式 $\Pi H \rightarrow \Pi E$  表示命题:我完成这个任务,则我能获得更多帮助。

---
#### 1-27 试证明 *P* ⇄ *Q*, *Q* 逻辑蕴含 *P*。 【1-5. (5)】

本题要求证明 $(P \rightleftarrows Q) \land Q \Rightarrow P$ 。设 $(P \rightleftarrows Q) \land Q \Rightarrow T$ ,则  $P \rightleftarrows Q \Rightarrow T$ ,故由  $\rightleftarrows$  的定义,必有  $P \Rightarrow T$ 。所以

$$(P \rightleftarrows Q) \land Q \Rightarrow P$$

---
#### 1-28

> 检验下述论证的有效性:
> 如果我学习,那么我数学不会不及格。
> 如果我不热衷于玩扑克,那么我将学习。
> 但我数学课不及格,因此我热衷于玩扑克。 【1-5.(6)】

**解**：

设 P: 我学习。Q: 我的数学课考试不及格。R: 我热衷于 玩扑克。本题符号化为:

$$P \rightarrow \neg Q, \neg R \rightarrow P, Q \Rightarrow R$$

验证:设 $(P \rightarrow \neg Q) \land (\neg R \rightarrow P) \land Q \rightarrow T$ ,则因  $Q \rightarrow T$ , P  $\rightarrow \neg Q \rightarrow T$ ,可得  $P \rightarrow F$ ,由  $\neg R \rightarrow P \rightarrow T$ ,得到  $\neg R \rightarrow F$ ,即  $R \rightarrow T$ ,故本题论证有效。

---
#### 1-29

> 用符号写出下列各式,并且验证论证的有效性:
> 如果6是偶数,则7被2除不尽。
> 或5不是素数,或7被2除尽。
> 但5是素数。
> 所以6是奇数。
> [1-5, (7)]

**解**：

*解** 设 P:6 是偶数。Q:7 被 2 除尽。R:5 是素数。故本题符号化为:

$(P \rightarrow \neg Q) \land (\neg R \lor Q) \land R \Rightarrow \neg P$

验证:设 $(P \rightarrow \neg Q) \land (\neg R \lor Q) \land R 为 T,则有 R 为 T,且 \neg R$   $\lor Q 为 T,故 Q 为 T,再因 P \rightarrow \neg Q 为 T,得到 <math>\neg P 为 T$ 。

注意:本题结论 6 是奇数(即 6 不是偶数)与实际意义虽然不符,但其前提中或 5 不是素数,或 7 被 2 除尽,也不符实际意义。故本题仅是逻辑推证有效。

---
#### 1-30

> 逻辑推证以下各式:
> - a)  $P \Rightarrow (\neg P \rightarrow Q)$ ;
> - b)  $\neg A \land B \land C \Rightarrow C$ ;
> - c)  $C \Rightarrow A \lor B \lor \neg B$ ;
> - d)  $\neg (A \land B) \Rightarrow \neg A \lor \neg B$ ;
> - e)  $\neg A \rightarrow (B \lor C), D \lor E, (D \lor E) \rightarrow \neg A \Rightarrow B \lor C;$
> - f)  $(A \land B) \rightarrow C$ ,  $\neg D$ ,  $\neg C \lor D \Rightarrow \neg A \lor \neg B$ . 【1-5.(8)】 证明 a) 假定  $P \rightarrow T$ , 则  $\neg P \rightarrow Q \rightarrow T$ .
> - b) 假定
> - c) 因为  $A \lor B \lor \neg B$  为永真,故  $C \Rightarrow A \lor B \lor \neg B$  成立。
> - d) 假定了 $(A \land B)$ 为 T,则  $A \land B$ 为 F。
> 若 A 为 F , B 为 T , 则
> - e) 假定
> - f) 假定 $\Box A \lor \Box B \to F$ ,则 $\Box (A \land B) \to F$ 。因为在条件式  $(A \land B) \to C \to A \land B \to T$ ,故:
> - (1) 若 C 为 T,则  $\Box$  C 为 F,若 D 为 T,则  $\Box$  D 为 F,故有 (( $A \land B$ ) $\rightarrow C$ )  $\land$  ( $\Box$  D)  $\land$  ( $\Box$   $C \lor D$ )为 F。
> - (2) 若 D 为  $\mathbb{F}$ ,则  $\Box$  C  $\lor$  D 为  $\mathbb{F}$ ,故((A  $\land$  B)→C)  $\land$  ( $\Box$  D)  $\land$  ( $\Box$  C  $\lor$  D) 为  $\mathbb{F}$ .
> - (3) 若 C 为 F,则( $A \land B$ )→C 为 F,因此(( $A \land B$ )→C)  $\land$  ( $\neg D$ )  $\land$  ( $\neg C \lor D$ ) 为 F。
> 综上各种情况( $A \land B$ )→C,  $\neg D$ ,  $\neg C \lor D$ ⇒  $\neg A \lor \neg B$  成立。 1-31 求与下列命题等价的逆反式:
> a) 如果他有勇气,他将得胜。
> b) 仅当他不累,他将得胜。
> [1-5.(9)]

**解**：

a) 设 P:他有勇气。R:他将得胜。 $P \rightarrow R$ 。逆反式

b) 设 E:他不累。R:他将得胜。 $R \rightarrow E$ 。逆反式  $\Box E \rightarrow \Box R$  表示命题:他累了则他不能得胜。

---
#### 1-32

> 已知  $A \neq B$  的充分条件, $B \neq C$  的必要条件, $C \neq D$  的必要条件, $D \neq B$  的必要条件,D:
> - a) A 是 D 的什么条件?
> - b) B是D的什么条件?

**解**：

已知  $A \Rightarrow B, C \Rightarrow B, D \Rightarrow C, B \Rightarrow D$ ,故有

a)  $A \Rightarrow B, B \Rightarrow D$ ,故  $A \Rightarrow D$ ,即  $A \neq D$ 的充分条件。
b) B是D的充分条件。

---
#### 1-33

> 把下列各式用只含 V 和 门的等价式表达, 并要尽可能简单:
> - a)  $(P \land Q) \land \neg P$ ;
> - b)  $(P \rightarrow (Q \lor \neg R)) \land \neg P \land Q;$
> - c)  $\neg P \land \neg Q \land (\neg R \rightarrow P)$ .
> [1-6.(1)]

**解**：

a)  $(P \land Q) \land \neg P \Leftrightarrow (\neg P \land P) \land Q \Leftrightarrow \neg (T \lor Q)$

b)  $(P \rightarrow (Q \lor \neg R)) \land \neg P \land Q$

$\Leftrightarrow ($

$\vee ( \neg R \wedge \neg P \wedge Q)$

$\Leftrightarrow (\neg P \land Q) \lor (\neg P \land Q) \lor (\neg P \land \neg R \land Q)$

$\Leftrightarrow \neg P \land Q \Leftrightarrow \neg (P \lor \neg Q)$

c)  $\neg P \land \neg Q \land (\neg R \rightarrow P) \Leftrightarrow \neg P \land \neg Q \land (R \lor P)$   $\Leftrightarrow (\neg P \land \neg Q \land R) \lor (\neg P \land \neg Q \land P)$  $\Leftrightarrow (\neg P \land \neg Q \land R) \lor F \Leftrightarrow (\neg P \lor Q \lor \neg R)$

---
#### 1-34

> 对下列各式仅用"或非"(↓)表达:
> - a)  $\neg P$ ;
> - b)  $P \lor Q$ ;
> c)  $P \wedge Q$
> [1-6, (2)]

**解**：

a)  $\neg P \Leftrightarrow P \lor P$

b)  $P \lor Q \Leftrightarrow \neg (P \lor Q) \Leftrightarrow (P \lor Q) \lor (P \lor Q)$
c)  $P \land Q \Leftrightarrow \neg P \lor \neg Q \Leftrightarrow (P \lor P) \lor (Q \lor Q)$

---
#### 1-35

> 把  $P \to ($
> **1-36** 把  $P \uparrow Q$  表示为只含有" $\downarrow$ "的等价公式,把  $P \downarrow Q$  表示为只含有" $\uparrow$ "的等价公式。 【1-6.(4)】

**解**：

$P \uparrow Q \Leftrightarrow \neg (P \land Q) \Leftrightarrow \neg P \lor \neg Q$

$\Leftrightarrow (P \downarrow P) \lor (Q \downarrow Q)$

$\Leftrightarrow ((P \downarrow P) \downarrow (Q \downarrow Q)) \downarrow ((P \downarrow P) \downarrow (Q \downarrow Q))$

$P \downarrow Q \Leftrightarrow \neg (P \lor Q) \Leftrightarrow \neg P \land \neg Q$

$\Leftrightarrow (P \uparrow P) \land (Q \uparrow Q)$

$\Leftrightarrow ((P \uparrow P) \uparrow (Q \uparrow Q)) \uparrow ((P \uparrow P) \uparrow (Q \uparrow Q))$

---
#### 1-37

**证明**：

a)  $\neg (B \land C) \Leftrightarrow \neg B \lor \neg C$ ;
b)  $\neg (B \downarrow C) \Leftrightarrow \neg B \uparrow \neg C$
[1-6.(5)]
a)  $\neg (B \uparrow C) \Leftrightarrow B \land C \Leftrightarrow \neg (\neg B \lor \neg C)$
$\Leftrightarrow \neg B \downarrow \neg C$
b)  $\neg (B \downarrow C) \Leftrightarrow B \lor C \Leftrightarrow \neg (\neg B \land \neg C)$  $\Leftrightarrow \neg B \uparrow \neg C$  1-38 联结词"↑"和"↓"服从结合律吗? 【1-6.(6)】 解 联结词"↑"和"↓"不满足结合律。举例如下:
a) 给出一组指派:P 为 F,Q 为 T,R 为 T,则( $P \land Q$ )  $\uparrow R$  为 F, $\Pi$   $P \land (Q \land R)$  为 T,故
$$(P \uparrow Q) \uparrow R \Leftrightarrow P \uparrow (Q \uparrow R)$$
b) 给出一组指派:P 为 T,Q 为 F,R 为 F,则( $P \lor Q$ )  $\lor R$  为 T, $P \lor (Q \lor R)$  为 F,即
$$(P \downarrow Q) \downarrow R \Leftrightarrow P \downarrow (Q \downarrow R)$$
---
#### 1-39

> 证明⟨⇒, ¬⟩ ${∇}, ¬⟩$ 不是最小联结词组。
> [1-6, (7)]

**证明**：

由例题 1-3,已证 $\{ \rightleftarrows , \sqcap \}$  不是最小联结词组,又因为  $P \overline{\lor} Q \Leftrightarrow \overline{\lor} (P \rightleftarrows Q)$ ,故任何命题公式中的联结词,如仅用 $\{ \neg , \overline{\lor} \}$  表达,则必可用 $\{ \rightleftarrows , \sqcap \}$  表达,其逆亦真。故 $\{ \neg , \overline{\lor} \}$  也必不是最小联结词组。

---
#### 1-40 证明 $\{ \lor \}$ , $\{ \land \}$ 和 $\{ \rightarrow \}$ 不是最小联结词组。【1-6.(8)】 证明 若 $\{ \lor \}$ 或 $\{ \land \}$ 是最小联结词组,则

$$\neg P {\Leftrightarrow} (P \vee \cdots)$$

$\neg P \Leftrightarrow (P \land \cdots)$

对所有命题变元指派 T,则等价式左边为 F,右边为 T,与等价表达式矛盾。

若{→}是最小联结词组,则

$$\neg P \Leftrightarrow P \rightarrow (P \rightarrow (P \rightarrow \cdots) \cdots)$$

对所有命题变元指派 T,则等价式左边为 F,右边为 T,矛盾。

---
#### 1-41

> 证明 $\{ \neg, \rightarrow \}, \{ \neg, \stackrel{c}{\rightarrow} \}$  是最小联结词组。 【1-6.(9)】

**证明**：

因为 $\{ \neg, \lor \}$  是最小联结词组,且  $P \lor Q \Leftrightarrow \neg P \rightarrow Q$ ,故  $\{ \neg, \rightarrow \}$  是功能完备的联结词组,又 $\{ \neg \}$  和 $\{ \rightarrow \}$  都不是功能完备的,所以 $\{ \neg, \rightarrow \}$  为最小联结词组。

又因为  $P \rightarrow Q \Leftrightarrow \neg (P \xrightarrow{c} Q)$ ,故 $\{\neg, \xrightarrow{c}\}$ 也是功能完备的联结

词组。但{<del>`</del>}不是功能完备的。因为若不然,则

$$P \Leftrightarrow P \xrightarrow{c} (P \xrightarrow{c} \cdots (P \xrightarrow{c} \cdots) \cdots)$$

对 P 指派 F , 左边的  $\bigcap P$  为 T , 右边为 F , 矛盾。

所以{┐,→}}是最小联结词组。

---
#### 1-42

> 求公式  $P \land (P \rightarrow Q)$ 的析取范式和合取范式。
> [1-7.(1)]

**解**：

$P \land (P \rightarrow Q) \Leftrightarrow P \land (\neg P \lor Q)$

$\Leftrightarrow (P \land \neg P) \lor (P \land Q)$

$P \land (P \rightarrow Q) \Leftrightarrow P \land (\neg P \lor Q)$

$\Leftrightarrow (P \lor (Q \land \neg Q)) \land (\neg P \lor Q)$

$\Leftrightarrow (P \lor Q) \land (P \lor \neg Q) \land (\neg P \lor Q)$

---
#### 1-43

> 把下列各式化为析取范式(每项两个变元)。
> - a)  $( \neg P \land Q) \rightarrow R;$
> - b)  $P \rightarrow ((Q \land R) \rightarrow S)$ ;
> - c)  $\neg (P \lor \neg Q) \land (S \rightarrow T)$ ;
> - d)  $(P \rightarrow Q) \rightarrow R$ ;
> - e)  $\neg (P \land Q) \land (P \lor Q)$ .
> [1-7.(2)]
> $\mathbf{m} \quad \text{a)} \quad ($
> $\Leftrightarrow P \lor \neg Q \lor R \Leftrightarrow (P \land Q) \lor (P \land \neg Q)$  $\lor (\neg Q \land R) \lor (\neg Q \land \neg R)$  $\lor (R \land P) \lor (R \land \neg P)$
> b)  $P \rightarrow ((Q \land R \rightarrow S) \Leftrightarrow \neg P \lor (\neg (Q \land R) \lor S)$
> $\Leftrightarrow \neg P \lor \neg Q \lor \neg R \lor S$
> $\Leftrightarrow (\, \neg P \land Q) \lor (\, \neg P \land \, \neg Q) \lor (\, \neg Q \land R)$
> $\vee ($
> $\vee ( \neg R \wedge \neg S) \vee (S \wedge \neg P) \vee (S \wedge P)$
> - c)  $\neg (P \lor \neg Q) \land (S \rightarrow T) \Leftrightarrow (\neg P \land Q) \land (\neg S \lor T)$  $\Leftrightarrow (\neg P \land Q \land \neg S) \lor (\neg P \land Q \land T)$
> - d)  $(P \rightarrow Q) \rightarrow R \Leftrightarrow \neg (\neg P \lor Q) \lor R$
> $\Leftrightarrow (P \land \neg Q) \lor R \Leftrightarrow (P \lor R) \land (\neg Q \lor R)$
> e)  $\neg (P \land Q) \land (P \lor Q) \Leftrightarrow (\neg P \lor \neg Q) \land (P \lor Q)$
> $\Leftrightarrow (\neg P \land P) \lor (\neg Q \land P)$
> V ( P Q) \vee ( Q Q)
> $\Leftrightarrow ( Q P) V P Q)$
---
#### 1-44

> 把下列各式化为合取范式:
> - a)  $P \lor ( P \land Q \land R )$ ;
> - b)  $\neg (P \rightarrow Q) \lor (P \lor Q)$ ;
> - c)  $\neg (P \rightarrow Q)$ ;
> - d)  $(P \rightarrow Q) \rightarrow R$ ;
> - e)  $( \neg P \land Q) \lor (P \land \neg Q)$ .
> [1-7.(3)]

**解**：

a)  $P \lor ( P \land Q \land R )$

$\Leftrightarrow (P \lor \neg P) \land (P \lor Q) \land (P \lor R)$

$\Leftrightarrow$   $(P \lor Q) \land (P \lor R)$

b)  $\neg (P \rightarrow Q) \lor (P \lor Q)$

$\Leftrightarrow \neg (\neg P \lor Q) \lor (P \lor Q)$

$\Leftrightarrow$   $(P \land \neg Q) \lor (P \lor Q)$

$\Leftrightarrow (P \lor Q \lor P) \land (\neg Q \lor P \lor Q)$

c)  $\neg (P \rightarrow Q) \Leftrightarrow \neg (\neg P \lor Q) \Leftrightarrow P \land \neg Q$

$\Leftrightarrow (P \lor Q) \land (P \lor \neg Q) \land (\neg Q \lor \neg P)$

d)  $(P \rightarrow Q) \rightarrow R \Leftrightarrow \neg (\neg P \lor Q) \lor R$

$\Leftrightarrow (P \land \neg Q) \lor R \Leftrightarrow (P \lor R) \land (\neg Q \lor R)$

e)  $( P \land Q) \lor (P \land Q)$

$\Leftrightarrow ( P \lor P) \land ( P \lor Q)$

$\wedge (Q \vee P) \wedge (Q \vee \neg Q)$

$\Leftrightarrow ($

---
#### 1-45

> 求下列各式的主析取范式及主合取范式,并指出下列 各式哪些是重言式:
> - a)  $( P \lor Q) \rightarrow (P \rightleftarrows Q);$
> - b)  $Q \land (P \lor \neg Q)$ ;
> - c)  $P \lor ( P \rightarrow (Q \lor ( Q \rightarrow R)));$
> - d)  $(P \rightarrow (Q \land R)) \land (\neg P \rightarrow (\neg Q \land \neg R));$
> - e)  $P \rightarrow (P \land (Q \rightarrow P));$
> - f)  $(Q \rightarrow P) \wedge (\neg P \wedge Q)_{\sigma}$
> [1-7.(4)]

**解**：

a)  $( P \lor Q) \rightarrow (P \rightleftarrows Q)$

$\Leftrightarrow \neg (\neg P \lor \neg Q) \lor (P \rightleftarrows \neg Q)$

$\Leftrightarrow (P \land Q) \lor (P \land \neg Q) \lor (\neg P \land Q)$

$\Leftrightarrow \sum_{1,2,3} \Leftrightarrow P \lor Q = \prod_0$

b)  $Q \land (P \lor \neg Q) \Leftrightarrow (P \land Q) \lor (Q \land \neg Q)$

$\Leftrightarrow P \land Q = \sum_3$

$\Leftrightarrow \prod_{0,1,2} = (P \lor Q) \land (P \lor \neg Q) \land (\neg P \lor Q)$

c)  $P \lor ( \neg P \rightarrow (Q \lor ( \neg Q \rightarrow R)))$

$\Leftrightarrow P \lor (P \lor (Q \lor (Q \lor R))$

$\Leftrightarrow P \lor Q \lor R = \prod_{\sigma}$

$\Leftrightarrow \sum_{1,2,3,4,5,6,7} = ( P \land Q \land R)$

$\vee \left( \neg P \land Q \land \neg R \right) \vee \left( \neg P \land Q \land R \right)$

$\vee (P \wedge \neg Q \wedge R) \vee (P \wedge \neg Q \wedge R)$

$\vee (P \wedge Q \wedge \neg R) \vee (P \wedge Q \wedge R)$

d)  $(P \rightarrow (Q \land R)) \land (\neg P \rightarrow (\neg Q \land \neg R))$

$\Leftrightarrow ( P (Q R))$

$\Leftrightarrow (\neg P \lor Q) \land (\neg P \lor R)$

$\wedge (P \vee \neg Q) \wedge (P \vee \neg R)$

$\Leftrightarrow ( P \lor Q \lor R)$

$\wedge ( P \lor R \lor Q) \wedge ( P \lor R \lor Q)$

$\wedge (P \vee \neg Q \vee R) \wedge (P \vee \neg Q \vee \neg R)$

$\bigwedge (P \vee \neg R \vee Q) \land (P \vee \neg R \vee \neg Q)$

$\Leftrightarrow (\neg P \lor Q \lor R) \land (\neg P \lor Q \lor \neg R)$

$\wedge ( P \vee Q \vee R) \wedge (P \vee Q \vee R)$

$\wedge (P \vee \neg Q \vee R) \wedge (P \vee Q \vee \neg R)$

$=\prod_{1,2,3,4,5,6}$

$\Leftrightarrow \sum_{0,7} = (P \land Q \land R) \lor (\neg P \land \neg Q \land \neg R)$

e)  $P \rightarrow (P \land (Q \rightarrow P)) \Leftrightarrow \neg P \lor (P \land (\neg Q \lor P))$

$\Leftrightarrow (\neg P \lor P) \land (\neg P \lor Q \lor P)$

$\Leftrightarrow T \land (T \lor \neg Q) \Leftrightarrow T$

$\Leftrightarrow \sum_{0,1,2,3} = (P \land Q) \lor (\neg P \lor Q)$

$\vee (\neg P \land Q) \lor (\neg P \land \neg Q)$

f)  $(Q \rightarrow P) \land ( \neg P \land Q) \Leftrightarrow ( \neg Q \lor P) \land ( \neg P \land Q)$

$\Leftrightarrow (\neg P \land Q \land P) \lor (\neg Q \land \neg P \land Q)$

$\Leftrightarrow (F \land Q) \lor (F \land \neg P) \Leftrightarrow F$

$\Leftrightarrow (P \lor Q) \land (P \lor \neg Q) \land (\neg P \lor Q)$

$\land ($

---
#### 1-46

> 用将合式公式化为范式的方法证明下列各题中两式 是等价的。
> - a)  $(A \rightarrow B) \land (A \rightarrow C), A \rightarrow (B \land C);$
> - b)  $(A \rightarrow B) \rightarrow (A \land B), ( A \rightarrow B) \land (B \rightarrow A);$
> - c)  $A \land B \land ( A \lor B), A \land B \land (A \lor B);$
> - d)  $A \lor (A \rightarrow (A \land B)), \neg A \lor \neg B \lor (A \land B)$ . [1-7. (5)]

**证明**：

a)  $(A \rightarrow B) \land (A \rightarrow C) \Leftrightarrow ($

$A \rightarrow (B \land C) \Leftrightarrow \neg A \lor (B \land C)$

$\Leftrightarrow ( A \lor B) \land ( A \lor C)$

b)  $(A \rightarrow B) \rightarrow (A \land B) \Leftrightarrow \neg (\neg A \lor B) \lor (A \land B)$

$\Leftrightarrow (A \land \neg B) \lor (A \land B)$

$\Leftrightarrow A \land ( B \lor B)$

$\Leftrightarrow A \land T \Leftrightarrow A$

$( A \rightarrow B) \land (B \rightarrow A) \Leftrightarrow (A \lor B) \land ( B \lor A)$

$\Leftrightarrow A \land (B \lor \neg B) \Leftrightarrow A$

c)  $A \land B \land ( A \lor B ) \Leftrightarrow (A \land B) \land (A \land B)$

$\Leftrightarrow F$

d)  $A \lor (A \rightarrow (A \land B)) \Leftrightarrow A \lor (\neg A \lor (A \land B))$

$\Leftrightarrow T \lor (A \land B) \Leftrightarrow T$

$\neg A \lor \neg B \lor (A \lor B) \Leftrightarrow \neg (A \land B) \lor (A \land B) \Leftrightarrow T$

---
#### 1-47

> 如果 A(P,Q,R)由  $R \uparrow (Q \land \neg (R \lor P))$ 给出,求它的对偶  $A^*(P,Q,R)$ ,并求出与  $A \neg A \land A^*$ 等价且仅包含联结词"  $\land$ "," $\lor$ " 
> $\boldsymbol{R} \quad A \Leftrightarrow R \uparrow (Q \land \neg (R \lor P)), \ \mathcal{M} \quad A^* \Leftrightarrow R \lor (Q \lor \neg (R \uparrow P)).$
> $R \uparrow (Q \land \neg (R \lor P)) \Leftrightarrow R \uparrow (Q \land (R \lor P))$
> $\Leftrightarrow \neg (R \land (Q \land (R \lor P))$
> $\Leftrightarrow ($
> $\Leftrightarrow \neg (R \land Q) \lor \neg (R \lor P)$
> $R \downarrow (Q \lor \neg (R \uparrow P)) \Leftrightarrow R \downarrow (Q \lor (R \land P))$
> $\Leftrightarrow \neg (R \lor (Q \lor \neg (R \land P)))$
> $\Leftrightarrow \neg R \land \neg Q \land \neg (R \land P)$
> $\Leftrightarrow \neg (R \lor Q) \land \neg (R \land P)$
---
#### 1-48

> 已知定理,如果  $A \lor B \Leftrightarrow A \lor C$ ,  $\neg A \lor B \Leftrightarrow \neg A \lor C$ ,则  $B \Leftrightarrow C$  写出它的对偶定理,并验证。

**解**：

对偶定理为:如果  $A \land B \mapsto A \land C$ ,  $\neg A \land B \mapsto \neg A \land C$ ,则  $B \mapsto C$ 。其证明如下:

$B \Leftrightarrow B \land (A \lor \neg A) \Leftrightarrow (B \land A) \lor (B \land \neg A)$  $\Leftrightarrow (A \land B) \lor (\neg A \land B) \Leftrightarrow (A \land C) \lor (\neg A \land C)$  $\Leftrightarrow (A \lor \neg A) \land C \Leftrightarrow \mathbf{T} \land C \Leftrightarrow C$

---
#### 1-49

> A,B,C,D 四个人中要派两个人出差,按下述三个条件有几种派法?如何派?
(1) 若 A 去,则 C和 D 中要去一人。
(2) B和C不能都去。
(3) C去则 D 要留下。

[1-7, (7)]

设A:A 去出差。B:B 去出差。

C:C去出差。D:D去出差。

按题意应有: $A \rightarrow C \overline{\lor} D$ ,  $\bigcap (B \land C)$ ,  $C \rightarrow \bigcap D$  必须同时成立。 因为

$C \overline{\vee} D \Leftrightarrow (C \wedge \neg D) \vee (D \wedge \neg C)$

故  $(A \rightarrow C \overline{\vee} D) \wedge \neg (B \wedge C) \wedge (C \rightarrow \neg D)$

$\Leftrightarrow ( A$

$\Leftrightarrow (\, \neg A \, \lor \, (\, \neg C \, \land \, D) \, \lor \, (\, \neg D \, \land \, C))$

$\wedge (( B \land C) \lor ( B \land D )$

$\forall ( \neg C \land \neg D) \lor \neg C)$

$\Leftrightarrow \underline{( \, \neg A \wedge \, \neg B \wedge \, \neg C) \, \vee ( \, \neg A \wedge \, \neg B \wedge \, \neg D)}$

$\vee ($

$\vee ( B \wedge C \wedge D) \vee \underline{( A \wedge D \wedge B \wedge D)}$

$\vee \, ( \, \neg C \land D \land \, \neg C \land \, \neg D) \lor ( \, \neg C \land D \land \, \neg C)$

$\bigvee ( \neg D \land C \land \neg B \land \neg C)$

$\vee ($

$\vee (\neg D \land C \land \neg C \land \neg D)$

$\forall ( \neg D \land C \land \neg C)$

在上述的析取范式中,有些项不符题意,如( $\Box A \land \Box C \land \Box D$ ) 表示三人都不出差,这不可能,另外如( $\Box C \land D \land \Box C \land \Box D$ )等都属矛盾,应在式中删除,故原式应为:

(

注意:上式( $\neg C \land D$ )这项表示可派  $D \land A$ ,或  $D \land B$ ,故与其他三项合并,总共为三种派法。

---
#### 1-50

> 三人估计比赛结果,甲说"A第一,B第二"。乙说"C第二,D第四",丙说"A第二,D第四"。结果三人估计得都不全对,但都对了一个,问A,B,C,D的名次。 【1-7. (8)】

**解**：

设 P:A 是第一。Q:B 是第二。R:C 是第二。S:D 是第四。E:A 是第二。根据题意为:

$(P \overline{\vee} Q) \wedge (R \overline{\vee} S) \wedge (E \overline{\vee} S)$ 原式 $\leftrightarrow ((P \wedge \neg Q) \vee (\neg P \wedge Q)) \wedge ((R \wedge \neg S))$  $\vee (\neg R \wedge S)) \wedge ((E \wedge \neg S) \vee (\neg E \wedge S))$  $\leftrightarrow ((\neg P \wedge Q \wedge R \wedge \neg S)$   $V (P \land \neg Q \land \neg R \land S)$   $V (\neg P \land Q \land R \land \neg S)$

$\vee \left( \neg P \land Q \land \neg R \land S \right) \right) \land \left( (E \land \neg S) \right)$

$\forall (\neg E \land S))$

因为 $(P \land \neg Q \land \neg R \land S)$ 与 $(\neg P \land \neg Q \land R \land \neg S)$ 不符题意,故可 在式中删去,原式即为:

$((P \land \neg Q \land R \land \neg S) \lor (\neg P \land Q \land \neg R \land S))$

$\wedge ((E \wedge \neg S) \vee (\neg E \wedge S))$

$\Leftrightarrow (P \land \neg Q \land R \land \neg S \land E \land \neg S)$

$\forall (P \land \neg Q \land R \land \neg S \land \neg E \land S)$

$\forall ( \neg P \land Q \land \neg R \land S \land E \land \neg S)$

$\vee (\neg P \land Q \land \neg R \land S \land \neg E \land S)$

$\Leftrightarrow (P \land \neg Q \land R \land \neg S \land E)$

$\vee (\neg P \land Q \land \neg R \land S \land \neg E)$

因 R 与 E 矛盾,故  $\Box P \land Q \land \Box R \land S \land \Box E$  为真。即 A 不是第一, B 为第二,C 不是第二,D 为第四,A 不是第二,于是得到:

C为第一,B为第二,A为第三,D为第四。

---
#### 1-51

> 甲、乙、丙、丁四人参加考试后,有人问他们,谁的成绩最好,甲说"不是我",乙说"是丁",丙说"是乙",丁说"不是我"。四人的回答只有一人符合实际,问是谁的成绩最好,只有一人成绩最好的是谁。

**解**：

设A:甲的成绩最好,B:乙的成绩最好,

C:丙的成绩最好,D:丁的成绩最好。

因为四人的回答只有一人符合实际,故

$( A \land D \land B \land D) \lor (A \land D \land B \land D)$

$\forall (A \land \neg D \land B \land D)$

$\forall (A \land \neg D \land \neg B \land \neg D) \Leftrightarrow \mathbf{T}$

即  $(A \land \neg B \land D) \lor (A \land \neg B \land \neg D) \Leftrightarrow T$

但  $(A \land \neg B \land D) \lor (A \land \neg B \land \neg D)$

$\Leftrightarrow (A \land \neg B \land D \land C) \lor (A \land \neg B \land D \land \neg C)$

$\bigvee (A \land \neg B \land \neg D \land C)$ $\bigvee (A \land \neg B \land \neg D \land \neg C)$

故有(1)甲、丙、丁三人并列成绩最好。

(2)甲、丁并列成绩最好。
(3)甲、丙并列成绩最好。
(4)甲的成绩最好。

所以只有一人成绩最好,就是甲。

---
#### 1-52

> 张三说李四在说谎,李四说王五在说谎,王五说张 三、李四都在说谎,问张三、李四、王五三人,到底谁说真话,谁 说假话。

**解**：

设A:张三说真话;B:李四说真话;C:王五说真话。

依题意有  $A \Leftrightarrow \neg B, B \Leftrightarrow \neg C, C \Leftrightarrow \neg A \land \neg B$  为真。但  $A \Leftrightarrow \neg B$  成立,即( $A \to \neg B$ )  $\land (\neg B \to A)$  为  $T_c$

同理, $B \Leftrightarrow \neg C$ 成立, $\mathbb{D}(B \to \neg C) \land (\neg C \to B)$ 为 T。

$C \Leftrightarrow \neg A \land \neg B$  成立,即 $(C \to (\neg A \land \neg B)) \land ((\neg A \land \neg B)) \to C)$ 为  $T_0$

故原题为  $((A \land \neg B) \lor \neg (A \land B)) \land ((B \land \neg C) \lor (\neg B \land C)) \land ((\neg A \land \neg B \land C)) \lor (\neg A \land \neg B \land \neg C))$ 为 T。即  $((\neg A \land B \land \neg C) \lor (A \lor B) \land C)) \land ((\neg A \land \neg B \land C) \lor (A \land \neg C) \lor (B \land \neg C))$ 为 T。得  $\neg A \land B \land \neg C$ 为 T。

即,张三说假话,王五说假话,而李四说真话。

---
#### 1-53

> 将下列推理符号化,并判断推理是否正确。
> - (1) 若 a,b 两数之积是负的,则 a,b 中恰有一个负数。a,b 两数之积是非负的,所以 a,b 中没有负数。
> - (2) 若一个数为整数,则它为无理数;若一个数为有理数,则它为实数;有一个数为整数,所以它为实数。
> - (3) 若一个数是实数,则它是复数;若一个数是质数,则它也是复数;一个数既不是实数,又不是虚数,所以它不是复数。
> - (4) 一个数是复数,仅当它是实数或是虚数;一个数既不是实数又不是虚数,所以它不是复数。

**解**：

(1) 设 P:a,b 两数之积是负的。Q:a 是负数。R:b 是负数。故本题的推证为

$$P \rightarrow (Q \overline{\vee} R), \neg P \rightarrow \neg Q \wedge \neg R$$

设
$$S \Leftrightarrow ((P \to (Q \overline{\vee} R)) \land \neg P) \to (\neg Q \land \neg R)$$

则
$$S \Leftrightarrow (($$

当P为F,Q为T,R为F时,S为F,故S不是重言式,故本题推理不正确。

(2) 设 P:一个数为整数;Q:一个数为有理数;R:一个数为 实数。故本题的推证为

$$((P \rightarrow Q) \land (Q \rightarrow R) \land P) \Rightarrow R$$

$$\diamondsuit \qquad S \Leftrightarrow ((P \to Q) \land (Q \to R) \land P) \to R$$

则
$$S \Leftrightarrow (( P \lor Q) \land ( Q \lor R) \land P) \rightarrow R$$

$$\Leftrightarrow (P \land \neg Q) \lor (Q \land \neg R) \lor \neg P \lor R$$

$$\Leftrightarrow ( Q \lor P) \lor (Q \lor R)$$

$$\Leftrightarrow \neg Q \lor Q \lor \neg P \lor R$$

$$\Leftrightarrow T \lor \neg P \lor R \Leftrightarrow T$$

因为 S 为重言式,故本题的推理成立。

(3) 设 R:一个数是实数;H:一个数是虚数;G:一个数是复数。故本题的推证为

$$(R \rightarrow G) \land (H \rightarrow G) \land (\neg R \land \neg H) \Rightarrow \neg G$$

$$\diamondsuit \qquad S \Leftrightarrow ((R \rightarrow G) \land (H \rightarrow G) \land (\neg R \land \neg H)) \rightarrow \neg G$$

$$\Leftrightarrow (( \, \neg R \, \forall \, G) \, \wedge ( \, \neg \, H \, \forall \, G)$$

$$\wedge ( \neg R \wedge \neg H)) \rightarrow \neg G$$

$$\Leftrightarrow (R \land \neg G) \lor (H \land \neg G) \lor (R \lor H) \lor \neg G$$

$$\Leftrightarrow (R \land \neg G) \lor \neg G \lor (H \land \neg G) \lor H \lor R$$

$$\Leftrightarrow \neg G \lor H \lor R$$

当G为T,H为F,R为F时, $S \Leftrightarrow F$ ,所以S不是重言式,即本题推理不能成立。

(4) 设 R:一个数是实数; H:一个数为虚数; G:一个数是 复数。

故本题的推证为

$(G \rightleftarrows (R \lor H)) \land ($

$\diamondsuit \qquad \qquad S \Leftrightarrow ((G \rightleftarrows (R \lor H)) \land (\neg R \land \neg H)) \rightarrow \neg G$

则  $S \Leftrightarrow ((G \rightarrow R \lor H)) \land ((R \lor H) \rightarrow G)$

$\wedge ( \neg R \wedge \neg H)) \rightarrow \neg G$

$\Leftrightarrow ((G \lor \neg R \lor H) \land (\neg (R \lor H) \lor G)$

$\wedge ( \neg R \wedge \neg H)) \rightarrow \neg G$

$\Leftrightarrow (($

$\Leftrightarrow (G \land \neg R \land \neg H) \lor (R \lor H) \lor \neg G$

$\Leftrightarrow (G \land \neg R \land \neg H) \lor \neg (G \land \neg R \land \neg H) \Leftrightarrow \mathbf{T}$

因为 S 为重言式, 故本题推理成立。

---
#### 1-54

> 用符号形式写出下题的推理过程,并指出推理是香 正确:
> - (1) 菱形的对角线相互垂直且二等分,若一个四边形的对角 线互相垂直且二等分,则此四边形是菱形。
> - (2) 如果这里有球赛,则通行是困难的;如果他们按指定的时间到达,则通行是不困难的;他们按指定的时间到达了,所以这里没有球赛。
> - (3) 如果甲得冠军,则乙或丙将得亚军;如果乙得亚军,则甲不能得冠军;如果丁得亚军,丙不能得亚军。事实是甲已得冠军,可知丁不能得亚军。

**解**：

(1) 设A:四边形是菱形。

B:四边形的对角线互相垂直且二等分。

本题的推理为

$A \rightarrow B, B \Rightarrow A$

其真值表如表 1-22。由真值表可看到 S 不是永真式,故本题的推理不成立。

(2) 设A:这里有球赛;B:通行是困难的;C:他们按指定时间

表 1-22

| A B                               | $A \rightarrow B$ | $(A \rightarrow B) \land B$ | S                |
|-----------------------------------|-------------------|-----------------------------|------------------|
| T T                               | T                 | T                           | T                |
| T $F$                             | F                 | F                           | $\boldsymbol{r}$ |
| $\boldsymbol{F}$ $\boldsymbol{T}$ | T                 | T                           | $\boldsymbol{F}$ |
| F F                               | T                 | F                           | T                |

到达。

本题的推理为

$$(A \rightarrow B), (C \rightarrow \neg B), C \Rightarrow \neg A$$

因为 C 为 T,  $C \rightarrow \Box B$  为 T, 故有  $\Box B$  为 T, 即 B 为 F, 但  $A \rightarrow B$  为 E 为 E 为 E 为 E 为 E E E E E E E E E E

由上论证,说明 $(A \rightarrow B) \land (C \rightarrow \neg B) \land C \Rightarrow \neg A$  成立。

(3) 设 A:甲得冠军。B:乙得亚军。C:丙得亚军。D:丁得亚军。

本题的推理为

$$(A \rightarrow B \lor C), (B \rightarrow \neg A)$$

$$(D \rightarrow \neg C), A \Rightarrow A \rightarrow \neg D$$

因为 A 为 T,  $A \rightarrow B \lor C$  为 T, 故有  $B \lor C$  为 T; 又  $B \rightarrow \neg A$  为 T, 故必有  $B \lor C \rightarrow \neg A \lor C$  为 T, 所以得到  $\neg A \lor C$  为 T, 即  $A \rightarrow C$  为 T。由  $D \rightarrow \neg C$  为 T,得  $C \rightarrow \neg D$  为 T。所以由  $A \rightarrow C$  为 T, $C \rightarrow \neg D$  为 T,得  $A \rightarrow \neg D$  为 T。故本题推理成立。

---
#### 1-55

> 用推理规则证明以下各式:
> - a)  $\neg (P \land \neg Q), \neg Q \lor R, \neg R \Rightarrow \neg P;$
> - b)  $J \rightarrow (M \lor N), (H \lor G) \rightarrow J, H \lor G \Rightarrow M \lor N;$
> - c)  $B \land C$ ,  $(B \rightleftarrows C) \rightarrow (H \lor G) \Rightarrow G \lor H$ ;
> - d)  $P \rightarrow Q$ ,  $( Q \lor R) \land R$ ,  $( P \land S) \Rightarrow S$ .
> [1-8, (1)]

**证明**：

a) (1) \(\bar{1}\)R

P

(2)  $\neg Q \lor R$

$\boldsymbol{P}$

(3)  $\neg Q$

(1)(2)T,I

| a) $\neg A \lor B, C \rightarrow \neg B \Rightarrow A \rightarrow \neg C;$ c) (1) $\neg (A \rightarrow F)$ P(附加前提) b) $A \rightarrow (B \rightarrow C), (C \land D) \rightarrow E, \neg F \rightarrow (D \land \neg E) \Rightarrow A \rightarrow (B \rightarrow F);$ (2) A (1) $T, I$ | (4) ¬(P ∧ ¬Q) (5) ¬P ∨ Q (6) ¬P b) (1) (H ∨ G) → J (2) (H ∨ G) (3) J (4) J→(M ∨ N) (5) M ∨ N c) (1) B ∧ C (2) B (3) C (4) B ∨ ¬C (5) C ∨ ¬B (6) C → B (7) B → C (8) B ⇄ C (9) (B ⇄ C) → (H ∨ G) (10) H ∨ G d) (1) (¬Q ∨ R) ∧ ¬R (2) ¬Q ∨ R (3) ¬R (4) ¬Q (5) P → Q (6) ¬P (7) ¬(¬P ∧ ¬S) (8) P ∨ ¬S (9) ¬S (9) ¬S 1-56 仅用规则 P 和 T 推证以下 | (8)(9)T,I P (1)T,I (1)T,I (2)(3)T,I P (4)(5)T,I P (7)T,E (6)(8)T,I |                      | c) $A \lor B \rightarrow C \land D, D \lor E \rightarrow F \Rightarrow A$<br>d) $\Box B \lor D, (E \rightarrow \Box F) \rightarrow \Box D \Rightarrow$<br>\ne) $(A \rightarrow B) \land (C \rightarrow D), (B \rightarrow E)$<br>$C \Rightarrow \Box A$ 。<br>证明 a) (1) $\Box (A \rightarrow \Box C)$<br>(2) $A$<br>(3) $C$<br>(4) $\Box A \lor B$<br>(5) $B$<br>(6) $C \rightarrow \Box B$<br>(7) $\Box B$<br>(8) $B \land \Box B$<br>b) (1) $\Box (A \rightarrow (B \rightarrow F))$<br>(2) $A$<br>(3) $\Box (B \rightarrow F)$<br>(4) $B$<br>(5) $\Box F$<br>(6) $A \rightarrow (B \rightarrow C)$<br>(7) $B \rightarrow C$<br>(8) $C$<br>(9) $\Box F \rightarrow (D \land \Box E)$<br>(10) $D \land \Box E$<br>(11) $D$<br>(12) $C \land D$<br>(13) $(C \land D) \rightarrow E$<br>(14) $E$<br>(15) $\Box E$<br>(16) $E \land \Box E$ | B→E;<br>∧(D→F), ¬(E∧F), A→<br>【1-8.(2)】<br>P(附加前提)<br>(1)T, I<br>(1)T, I<br>P<br>(2)(4)T, I<br>P<br>(3)(6)T, I<br>矛盾。(5), (7)<br>P(附加前提)<br>(1)T, I<br>(1)T, I<br>(3)T, I<br>(3)T, I<br>P<br>(2)(6)T, I<br>(4)(7)T, I<br>P<br>(5)(9)T, I<br>(10)T, I<br>(8)(11)T, I<br>P<br>(12)(13)T, I<br>(10)T, I<br>矛盾。(14), (15) |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------|----------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| b) $A \rightarrow (B \rightarrow C), (C \land D) \rightarrow E, \neg F \rightarrow (D \land \neg E) \Rightarrow A \rightarrow (B \rightarrow F);$ (1) $T, I$                                                                                                                          |                                                                                                                                                                                                                                                                                                                                        | YA:                                                                |                      | c) $(1) \  \   \   \   \   \   \   \   \   \ $                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | P(附加前提)                                                                                                                                                                                                                                                                                                               |
|                                                                                                                                                                                                                                                                                       | b) $A \rightarrow (B \rightarrow C), (C \land D) \rightarrow E, \neg F \rightarrow$                                                                                                                                                                                                                                                    | $(D \land \neg E) \Rightarrow A \rightarrow (B \rightarrow A)$     | <b>→</b> <i>F</i> ); | (2) A                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | (1)T,I                                                                                                                                                                                                                                                                                                                |

| $(8) E \rightarrow \neg F \qquad (7)T,E \qquad (13) B \rightarrow F \qquad CP$ $(9) A \rightarrow \neg F \qquad (5)(8)T,I \qquad (14) A \rightarrow (B \rightarrow F) \qquad CP$ $(10) C \rightarrow D \qquad (1)T,I \qquad c) (1) A \qquad P(附加前提)$ |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| (10) $C \rightarrow D$ (1) $T, I$ c) (1) $A$ $P(附加頁是)$ (11) $D \rightarrow F$ (3) $T, I$ (2) $A \lor B$ (1) $T, I$                                                                                                                                   |

|      | $(3) A \lor B \rightarrow C \land D$                                                     | P                                         |                                                    |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
|------|------------------------------------------------------------------------------------------|-------------------------------------------|----------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|      | $(4) C \wedge D$                                                                         | (2)(3)T,I                                 | (3) S                                              | (1)(2)T,I                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
|      | (5) D                                                                                    | (4)T,I                                    | $(4) S \rightarrow \neg Q$                         | P                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
|      | (6) D \ E                                                                                | (5)T,I                                    | (5) <b>\( \bar{Q}</b>                              | (3)(4)T,I                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
|      | $(7) D \lor E \rightarrow F$                                                             | P                                         | $(6) \   \neg R \rightleftarrows Q$                | P                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
|      | (8) F                                                                                    | (6)(7)T,I                                 | (7) (                                              |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
|      | (9) <i>A</i> → <i>F</i>                                                                  | CP                                        | $(8)  \neg R \rightarrow Q$                        | (7)T,I                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| 1 –  | 58 证明下列各式                                                                                | <u>~</u>                                  | (9) R                                              | (5)(8)T,I                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
|      | $R \rightarrow \neg Q, R \lor S, S \rightarrow \neg Q, P \rightarrow Q \Rightarrow \neg$ | р.                                        | (10) $R \land \neg R$                              | 矛盾。(2),(9)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
|      |                                                                                          |                                           | c) (1) R                                           | P                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
|      | $S \rightarrow \neg Q, S \lor R, \neg R, \neg R \rightleftarrows Q \Rightarrow \neg R$   |                                           | $(2) (Q \rightarrow P) \lor \neg R$                | P                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| c)   |                                                                                          | 1.0 × × × × × × × × × × × × × × × × × × × | $(3) Q \rightarrow P$                              | (1)(2)T,I                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| \max |                                                                                          | [1-8.(4)]                                 | $(4) \   \bigcap (P \to Q) \to \bigcap (R \lor Q)$ | (S) P                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| 1411 | 明 a) 解法 1                                                                                | _                                         | $(5) (R \lor S) \rightarrow (P \rightarrow Q)$     | (4)T,E                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
|      | $(1) R \rightarrow \neg Q$                                                               | P                                         | (6) R V S                                          | (1)T,I                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
|      | $(2) R \lor S$                                                                           | P                                         | (7) <i>P</i> → <i>Q</i>                            | (5)(6)T,I                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
|      | $(3) S \rightarrow \neg Q$                                                               | P                                         | $(8) (P \rightarrow Q) \land (Q \rightarrow P)$    | (3)(7)T,I                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
|      | $(4) \   \bigcap Q$                                                                      | (1)(2)(3)T,I                              | $(9) P \leftrightarrow Q$                       | (8)T,E                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
|      | $(5) P \rightarrow Q$                                                                    | P                                         | 1-59 对下面的每一组前据                                     | 是,写出可能导出的结论,以及所                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
|      | (6) <b>¬</b> <i>P</i>                                                                    | (4)(6)T,I                                 | 用的推理规则:                                            |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| 解法 2 | (1) P                                                                                    | P(附加前提)                                   | a) 如果我跑步,那么我很疲                                     | 劳 <b>。</b>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
|      | $(2) P \rightarrow Q$                                                                    | P                                         | 我没有疲劳。                                             |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
|      | (3) Q                                                                                    | (1)(2)T,I                                 | b) 如果他犯了错误,那么他神色慌张。                                |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
|      | $(4) S \rightarrow \neg Q$                                                               | P                                         | 他神色慌张。                                             |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
|      | (5) \Bar{S}                                                                              | (3)(4)T,I                                 | c) 如果我的程序通过,那么                                     | 我很快乐。                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
|      | (6) RVS                                                                                  | P                                         | 如果我快乐,那么阳光很                                        | 好。                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
|      | (7) R                                                                                    | (5)(6)T,I                                 | 现在是晚上十一点,天很!                                       | 暖。 【1-8.(5)】                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
|      | $(8) R \rightarrow \neg Q$                                                               | P                                         | 解 a) 设 P:我跑步。Q:                                    |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
|      | (9) \( \bar{Q} \)                                                                        |                                           | 前提为:P→Q,¬Q                                         | and the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of the same of th |
| Ы    | $(1) S \vee R$                                                                           | (7)(8),T,I(矛盾)                            | $(1) P \rightarrow Q$                              | P                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| 67   | $(2) \   \neg R$                                                                         | P                                         | $(2) \   \neg Q$                                   | P                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
|      | (2)  K                                                                                   | P                                         | (=)   ec                                           | <del></del>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |

(3) ¬P

(1)(2)T,I

结论为: $\Box P$ ,我没有跑步。

b) 设 S:他犯了错误。R:他神色慌张。

前提为: $S \rightarrow R, R$

因为 $(S \rightarrow R) \land R \Leftrightarrow ($

c)设 P:我的程序通过。Q:我很快乐。

R:阳光很好。

S:天很暖和。

(把晚上十一点理解为阳光不好)

前提为: $P \rightarrow Q$ ,  $Q \rightarrow R$ ,  $\neg R \land S$

(1)  $P \rightarrow Q$

P

(2) **Q→R**

(3) *P*→*R*

(1)(2)T,I

(4)  $\neg R \land S$

P

(5)  $\neg R$

(4)T,I

(6)  $\neg P$

(3)(5)T,I

结论为: $\Box P$ ,我的程序没有通过。

---
#### 1-60 下式推证是否有效?

甲、乙、丙、丁四人参加拳击比赛。如果甲获胜,则乙失败;如果丙获胜,则乙也获胜;如果甲不获胜,则丁不失败。所以如果丙获胜,则丁不失败。

设A:甲获胜。B:乙获胜。

C: 丙获胜。D: 丁获胜。

前提为: $A \rightarrow \Box B, C \rightarrow B, \Box A \rightarrow D$

结论为:

$C \rightarrow D$

(1)  $A \rightarrow \neg B$

$\boldsymbol{P}$

(2)  $B \rightarrow \neg A$

(1)T,E

(3)  $\neg A \rightarrow D$

(4)  $B \rightarrow D$

(2)(3)T,I

(5)  $C \rightarrow B$

$\boldsymbol{P}$

(6)  $C \rightarrow D$

(5)(4)T,I

故本题的推证有效。

---
#### 1-61 证明

(

要证本题为正确推理形式,即证:

((

令  $B \Leftrightarrow B_1 \lor B_2 \lor \cdots \lor B_n$ ,则  $\sqcap B \Leftrightarrow \sqcap B_1 \land \sqcap B_2 \land \cdots \land \sqcap B_n$ ,故原式为

$$(($$

---
#### 1-62

**证明**：

$(A_1 \rightarrow B) \land (A_2 \rightarrow B) \land \cdots \land (A_n \rightarrow B) \land (A_1 \lor A_2 \lor \cdots \lor A_n) \Rightarrow B$ 是一个正确的推理形式。
要证本题是一个正确推理形式,即证:
$(A_1 \rightarrow B) \land (A_2 \rightarrow B) \land \cdots \land (A_n \rightarrow B) \land (A_1 \lor A_2 \lor \cdots \lor A_n) \rightarrow B$ 是一个永真表达式。用归纳法:
当 n=1 时,
$$((A_1 \rightarrow B) \land A_1) \rightarrow B \Leftrightarrow ($$
设当 n=k-1 时推理表达式为 T,即设
$$(A_1 \rightarrow B) \land (A_2 \rightarrow B) \land \cdots \land (A_{k-1} \rightarrow B)$$
$$\land (A_1 \lor A_2 \lor \cdots \lor A_{k-1}) \rightarrow B$$
为  $T$  令  $C \Leftrightarrow A_1 \lor A_2 \lor \cdots \lor A_{k-1}$
$D \Leftrightarrow (A_1 \rightarrow B) \land (A_2 \rightarrow B) \land \cdots \land (A_{k-1} \rightarrow B)$
即设  $C \land D \rightarrow B$  为 T。则当 n = k 时有
$(D \land (A_k \rightarrow B) \land (C \lor A_k)) \rightarrow B$  $\Leftrightarrow (D \land ($  $\Leftrightarrow \neg D \lor (A_k \land \neg B) \lor (\neg C \land \neg A_k) \lor B$  $\Leftrightarrow \neg D \lor A_{k} \lor B \lor (\neg C \land \neg A_{k})$  $\Leftrightarrow$  $\Leftrightarrow \neg (D \land C) \lor B \lor A_{h}$  $\Leftrightarrow$   $(C \land D \rightarrow B) \lor A_{1} \Leftrightarrow T \lor A_{2} \Leftrightarrow T$
所以原题是一个正确推理形式。
---
#### 1-63

> 银行的金库装有自动报警装置,仅当总经理室的一个 人工控制开关合上时,它才能动作。如果这个人工开关合上,那么 当金库的门被撬时或者当工作人员尚未切断监视器电源且通向金 库的通道有人时,就要发出警报。试设计这个控制线路。
> [1-9, (1)]

**解**：

设 P:人工开关合上。Q:金库的门被撬。 R:工作人员尚未切断监视器电源。 S:通向金库的通道有人。

F:自动报警装置报警。

则有

$F \Leftrightarrow P \land (Q \lor (R \land S))$

其控制线路如图 1-2 所示。

![](_page_33_Picture_10.jpeg)

---
#### 1-64

> 设计一个控制船洗室照明的电路,使得分别装在卧室 和盥洗室的两只开关都能控制照明。 [1-9, (2)]

**解**：

设盥洗室和卧室的控制开关分别为  $K_1$  和  $K_2$ , S 表示盥洗室照明状态, 灯亮为 "1",灯暗为"0"。且  $K_1$  和  $K_2$  两种状态也以

图 1-3

"0"和"1"表示,则

$S \Leftrightarrow (K_1 \land \neg K_2) \lor (\neg K_1 \land K_2) \Leftrightarrow K_1 \overline{\lor} K_2$ 所以控制电路如图 1-3 所示。

---
#### 1-65

> 设计一个二进制半加器的电路,它的功能如表 1-23 所示,其中x和y是被加数,S是和,C是进位。 [1-9, (3)]
> 表 1-23
> | x | ý | S | С |  |
> |---|---|---|---|--|
> | 0 | 0 | 0 | 0 |  |
> | 0 | 1 | 1 | 0 |  |
> | 1 | 0 | 1 | 0 |  |
> | 1 | 1 | Ö | 1 |  |

**解**：

半加器是由 x 与 y 相加,求出和 S 以及进位 C 的一种逻 辑线路,这一线路有两个输入x,y和两个输出S 与 C。由上表所 列情况可知:

$$S \Leftrightarrow x \overline{\vee} y$$
,  $C \Leftrightarrow x \wedge y$

故逻辑线路如图 1-4 所示。

![](_page_33_Picture_23.jpeg)

图 1-4

---
#### 1-66

> 设计红绿灯自动控制线路,要求传感器中计数器内容 Z,当  $Z \ge 5$  时亮绿灯,当  $Z \le 2$ ,亮红灯,当 2 < Z < 5 时亮黄灯。
> [1-9, (4)]

**解**：

设  $P:Z \ge 5$  且  $P \Rightarrow L_1$  (亮绿灯)  $Q: Z \leq 2$  且  $Q \Rightarrow L_2$  (亮红灯)

$S: 2 < Z < 5, S \Rightarrow L_3$ (亮黄灯)

因为

$S \Leftrightarrow \neg P \land \neg Q \Leftrightarrow \neg (P \lor Q)$

![](_page_34_Picture_3.jpeg)

故控制电路如图 1-5 所示。

---
#### 1-67

> 设三人表决器装有 A, B, C 三个按钮, 其中 A 为主按钮, 仅当 A 及其他 两个按钮至少有一个按下时, 表决器灯亮, 试设计此表决器 线路。

**解**：

由题意可列出真值表 1-24。由表有:

$F \Leftrightarrow (A \land \neg B \land C) \lor (A \land B \land \neg C) \lor (A \land B \land C)$

$\Leftrightarrow (A \land \neg B \land C) \lor ((A \land B) \land (\neg C \lor C))$

$\Leftrightarrow (A \land \neg B \land C) \lor (A \land B)$

$\Leftrightarrow A \land (B \lor C)$

故表决器线路如图 1-6 所示。

表 1-24

| A | В | С | F |
|---|---|---|---|
| 0 | 0 | 0 |
| 0 | 0 | 1 |
| 0 | 1 | 0 |
| 0 | 1 | 1 |
| 1 | 0 | 0 |
| 1 | 0 | 1 |
| 1 | 1 | 0 |
| 1 | 1 | 1 |
|   |   |   |   |

![](_page_34_Picture_14.jpeg)

---
#### 1-68

> 设计一种保密锁的控制电路,锁上共有三个键钮 A,B,C。当三键同时按下,或只有 A,B 两键按下,或只有 A,B 其
> 表 1-25
> | A | В      | C      | G |
> |---|--------|--------|---|
> | 1 | 1      | 1      |
> | 1 | 1      | 0      |
> | 1 | 0      | 0      |
> | 0 | 1      | 0      |
> | 1 | 0      | 1      |
> | 0 | 1      | 1      |
> | 0 | 0      | 1      |
> | 0 | 0      | 0      | o |
> | 0 | 0<br>0 | 1<br>0 |
> 中之一按下时,锁被打开,请写出此控制电路的公式并画出线路图。

**解**：

根据题目要求,列出开锁条件的真值表如表 1-25 所示。 由真值表可写出逻辑表达式为:

$G \Leftrightarrow (A \land B \land C) \lor (A \land B \land \neg C)$

$\forall (A \land \neg B \land \neg C) \lor (\neg A \land B \land \neg C)$

$\Leftrightarrow (A \land B) \lor (A \land \neg B \land \neg C) \lor (\neg A \land B \land \neg C)$

$\Leftrightarrow (A \land (B \lor ( B \land C))) \lor ( A \land B \land C)$

$\Leftrightarrow (A \land (B \lor \neg C)) \lor (\neg A \land B \land \neg C)$

$\Leftrightarrow (A \land B) \lor (A \land \neg C) \lor (\neg A \land B \land \neg C)$

$\Leftrightarrow$   $(A \land B) \lor ((A \lor ($

$\Leftrightarrow$   $(A \land B) \lor ((A \lor B) \land \neg C)$

![](_page_34_Picture_28.jpeg)

图 1-7

#### $\Leftrightarrow$ $(A \land B) \lor (A \land \neg C) \lor (B \land \neg C)$

故保密锁的控制电路如图 1-7 所示。

---
#### 1-69

> 在上题中,附加一个报警装置的控制电路,当出现不符上述开锁信号时,使电铃发响报警。

**解**：

设报警器的输出信号为 S,在上题所列出的真值表中,使 G 为 0 的变元指派,应是使 S 真值为 1 的变元指派,但还要除去 A,B,C 均为 0 的情况。故可列出真值表 1-26。

表 1-26

| A | В | С   | S |
|---|---|-----|---|
| 1 | 0 | 1   |
| 0 | 1 | i i |
| 0 | 0 | 1   |
由真值表列出报警器的逻辑表达式:

$S \mathop{\Leftrightarrow} (A \land \neg B \land C) \lor (\neg A \land B \land C)$

$\forall ( \neg A \land \neg B \land C)$

$\Leftrightarrow (($

$\Leftrightarrow C \land ( B \lor ( A \land B) )$

$\Leftrightarrow C \land ( B \lor A)$

$\Leftrightarrow ($

故其电路如图 1-8 所示。

## 第二章 谓词逻辑

#### 2-1

> 用谓词表达式写出下列命题:
> - a) 小张不是工人;
> - b) 他是田径或球类运动员;
> - c) 小莉是非常聪明和美丽的:
> - d) 若 m 是奇数,则 2m 不是奇数;
> - e) 每一个有理数是实数;
> - f) 某些实数是有理数:
> - g) 并非每个实数都是有理数;
> - h) 直线 A 与直线 B 平行当且仅当直线 A 与 B 不相交。
> [2-1,2-2,(1)]

**解**：

a) 设W(x):x是工人。c:小张。则有

$\neg W(c)$

b) 设 S(x): x 是田径运动员。B(x): x 是球类运动员。h: 他。则有

$S(h) \vee B(h)$

c) 设 C(x):x 是聪明的。B(x):x 是美丽的。l:小莉。则有  $C(l) \land B(l)$
d) 设 O(x):x 是奇数。则有

$O(m) \rightarrow \neg O(2m)$

e) 设 R(x):x 是实数。Q(x):x 是有理数。则有

$(\forall x)(Q(x)\rightarrow R(x))$

f) 设 R(x):x 是实数。Q(x):x 是有理数。则有

$(\exists x)(R(x) \land Q(x))$

g) 设 R(x):x 是实数。Q(x):x 是有理数。则有

$\neg (\forall x)(R(x)\rightarrow Q(x))$

h) 设 P(x,y):直线 x 平行于直线 y。G(x,y):直线 x 相交于直线 y。则有

$P(A,B) \rightleftarrows \Box G(A,B)$

---
#### 2-2

> 找出以下十二个句子所对应的谓词表达式:
> - a) 所有教练员是运动员(J(x),L(x));
> - b) 某些运动员是大学生(S(x));
> - c) 某些教练是年老的,但是健壮的(O(x),V(x));
> - d) 金教练既不老但也不是健壮的(j);
> - e) 不是所有运动员都是教练;
> - f) 某些大学生运动员是国家队选手(C(x));
> - g) 没有一个国家队选手不是健壮的;
> - h) 所有老的国家队选手都是运动员;
> - i) 没有一位女同志既是国家队选手又是家庭妇女(W(x), H(x));
> - i) 有些女同志既是教练员又是国家队选手;
> - k) 所有运动员都钦佩某些教练(A(x,y));
> - 1) 有些大学生不钦佩运动员。
> [2-1,2-2,(2)]

**解**：

a) 设J(x);x是教练员。L(x);x是运动员。得

$(\forall x)(J(x)\rightarrow L(x))$

b) 设 S(x):x 是大学生。L(x):x 是运动员。则有  $(\exists x)(L(x) \land S(x))$
c) 设 J(x):x 是教练员。O(x):x 是年老的。V(x):x 是健壮的。则有

$(\exists x)(J(x) \land O(x) \land V(x))$

d) 设 O(x):x 是年老的。V(x):x 是健壮的。j:金教练。则有

$\neg O(j) \land \neg V(j)$

e) 设L(x):x是运动员。J(x):x是教练员。则有

$\neg (\forall x)(L(x) \rightarrow J(x))$

本题亦可理解为:某些运动员不是教练。故  $(\exists x)(L(x) \land \neg J(x))$ 。

f) 设 S(x):x 是大学生。L(x):x 是运动员。C(x):x 是国家队选手。故有

$(\exists x)(S(x) \land L(x) \land C(x))$

g) 设 C(x):x 是国家队选手。V(x):x 是健壮的。故有  $(\forall x)(C(x)\rightarrow V(x))$ 或  $(\exists x)(C(x)) \land \neg V(x)$
h) 设 O(x):x 是老的。L(x):x 是运动员。C(x):x 是国家队选手。则有

$(\forall x)(O(x) \land C(x) \rightarrow L(x))$

i) 设 W(x):x 是女同志。H(x):x 是家庭妇女。C(x):x 是国家队选手。得

$(\exists x)(W(x) \land C(x) \land H(x))$

j) 设W(x):x是女同志。C(x):x是国家队选手。J(x):x是教练员。则有

$(\exists x)(W(x) \land J(x) \land C(x))$

k) 设 L(x):x 是运动员。J(y):y 是教练。A(x,y):x 钦佩y。故有

$(\forall x)(L(x)\rightarrow(\exists y)(J(y)\land A(x,y))$

l) 设 S(x):x 是大学生。L(x):x 是运动员。A(x,y):x 钦 佩 y。故有

$(\exists x)(S(x) \land \forall y(L(y) \rightarrow \neg A(x,y)))$

---
#### 2-3 令 P(x)为"x 是质数",E(x)为"x 是偶数",O(x)为"x 是奇数",D(x,y)为"x 除尽 y"。把下列各式译成汉语。
a) P(5);
b)  $E(2) \wedge P(2)$ ;
c)  $(\forall x)(D(2,x)\rightarrow E(x));$
d)  $(\exists x)(E(x) \land D(x,6));$
e)  $(\forall x)(\neg E(x) \rightarrow \neg D(2,x));$
f)  $(\forall x)(E(x)\rightarrow(\forall y)(D(x,y)\rightarrow E(x)));$
g)  $(\forall x)(P(x)\rightarrow(\exists y)(E(y)\land D(x,y)));$
h)  $(\forall x)(O(x) \rightarrow (\forall y)(P(y) \rightarrow \Box D(x,y))$ 。 【2-3.(1)】 解 a) 5 是质数。
b) 2是偶数且2是质数。
c) 对所有 x,若 x 被 2 除尽,则 x 是偶数。
d) 存在 x,x 是偶数,且 x 除尽 6(即某些偶数能除尽 6)。
e) 对所有 x,若 x 不是偶数,则 x 不能被 2 除尽。
f) 对所有x,若x是偶数,则对所有y,若x除尽y,则y是偶数。
g) 对所有 x,如果 x 是质数,则存在 y,y 是偶数且 x 除尽 y (即所有质数能除尽某些偶数)。
h) 对所有x,若x是奇数,则对所有y,y是质数,则x不能除尽y(即任何奇数不能除尽任何质数)。

---
#### 2-4

> 设 P(x), L(x), R(x,y,z)和 E(x,y)分别表示"x 是一个点", "x 是一条直线", "z 通过 x 和 y", "x=y", 符号化下面句子: 对每两个点,有且仅有一条直线通过该两点。 【2-3. (2)】解
> $(\forall x)(\forall y)((P(x) \land P(y) \land \neg E(x,y))$   $\rightarrow (\exists !z)(L(z) \land R(x,y,z)))$
---
#### 2-5

> 利用谓词公式翻译下列命题:
> - a) 如果有限个数的乘积为零,那么至少有一个因子等于零。
> - b) 对于每一个实数 x,存在一个更大的实数 y。
> - c) 存在实数 x, y 和 z, 使得 x 与 y 之和大于 x 与 z 之积。
> [2-3, (3)]

**解**：

a) 设 N(x): x 是有限个数的乘积。z(y): y 为 0。 P(x): x 的乘积为零。F(y): y 是乘积中的一个因子。则有  $(\forall x)((N(x) \land P(x) \rightarrow (\exists y)(F(y) \land z(y)))$

b) 设 R(x):x 是实数。Q(x,y):y 大于x。则有  $(\forall x)(R(x)\rightarrow (\exists y)(Q(x,y)\land R(y)))$
c) R(x):x 是实数。G(x,y):x 大于 y。则有 ( $(\exists x$ )( $(\exists y$ )( $(\exists z$ )( $R(x) \land R(y) \land R(z) \land G(x+y,x \cdot z$ )

---
#### 2-6

> 用谓词公式写出下式:
> 若 x < y,且 z < 0,则  $x \cdot z > y \cdot z$ 。

**解**：

设G(x,y);x大于y。则有

$(\forall x)(\forall y)(\forall z)(G(y,x) \land G(0,z) \rightarrow G(x \cdot z, y \cdot z))$

---
#### 2-7

> 自然数共有三条公理:
> - a) 每个数都有唯一的一个数是它的后继数;
> - b) 没有一个数,使数1是它的后继;
> - c) 每个不等于 1 的数, 都有唯一的一个数是它的直接先行者。
> 用两个谓词表达上述三条公理。
> [2-3, (5)]

**解**：

设 N(x): x 是一个数。S(x,y): y 是 x 的后继数(即 x 是 y 的直接先行者,如 2 的直接先行者是 1)。则

a)  $(\forall x)(N(x)\rightarrow(\exists !y)(N(y) \land S(x,y)));$
b)  $\neg (\exists x)(N(x) \land S(x,1))$ :
c)  $(\forall x)(N(x) \land \neg S(x,2) \rightarrow (\exists !y)(N(y) \land S(y,x)))$ .

---
#### 2-8

> 用谓词公式刻划下述命题:
> 那位戴眼镜的用功的大学生在看这本大而厚的巨著。
> [2-3, (6)]

**解**：

设S(x):x 是大学生。E(x):x 是戴眼镜的。

F(x):x 是用功的。R(x,y):x 在看 y。

G(y):y 是大的。K(y):y 是厚的。J(y):y 是巨著。

a:这本。b:那位。则有

$E(b) \wedge F(b) \wedge S(b) \wedge R(b,a) \wedge G(a) \wedge K(a) \wedge J(a)$

---
#### 2-9

> 取个体域为实数集 R,函数 f 在 a 点连续的定义是: f 在点 a 连续当且仅当对每个  $\epsilon>0$ ,存在一个  $\delta>0$ ,使得对所有 x,若  $|x-a|<\delta$ ,则  $|f(x)-f(a)|<\epsilon$ 。把上述定义用符号化形式 表达。

**解**：

设 P(x,y):x 在 y 连续。Q(x,y):x>y。则有 P(f,a) $\rightleftarrows$ (( $\forall \varepsilon$ )( $(\exists \delta$ )( $\forall x$ )( $Q(\varepsilon,0)$   $\rightarrow$ ( $Q(\delta,0) \land Q(\delta,|x-a|$ )  $\rightarrow$  $Q(\varepsilon,|f(x)-f(a)|))))$

---
#### 2-10

> 用谓词表达式符号化下列命题:
> - (1) 有一数比任何数都大;
> - (2) 并非一切劳动都能用机器代替;
> - (3) 存在着一个并且仅存在一个偶数。

**解**：

(1) 设 N(x):x 是数。G(x,y):x 大于 y。则有 ( $(\exists x$ )( $N(x) \land (\forall y)(N(y) \rightarrow G(x,y))$ )
(2) 设 L(x): x 为劳动。M(x): x 为机器。R(x,y): x 被 y 代替。则有

$\neg (\forall x)(L(x)\rightarrow(\exists y)(M(y)\land R(x,y)))$

(3) 设 P(x):x 是偶数。则有

$(\exists x)P(x) \land (\exists !x)P(x)$

---
#### 2-11

> 对下面每个公式指出约束变元和自由变元:
> - a)  $(\forall x)P(x) \rightarrow P(y)$ ;
> - b)  $(\forall x)(P(x) \land Q(x)) \land (\exists x)S(x)$ :
> - c)  $(\exists x)(\forall y)(P(x) \land Q(y) \rightarrow (\forall x)R(x));$
> - d)  $(\exists x)(\exists y)(P(x,y) \land Q(z))$ ,
> [2-4.(1)]

**解**：

a) x 是约束变元, y 是自由变元。
b) x 是约束变元,在  $P(x) \land Q(x)$ 中的 x 受全称量词( $\forall$ )约束,在 S(x)中的 x 受存在量词( $\exists$ )的约束。
c) x,y 都是约束变元,P(x)中的 x 受( $\exists$ )的约束,R(x)中的 x 受( $\forall$ )的约束。
d) x,y是约束变元,z是自由变元。

---
#### 2-12

> 如果论域是集合 $\{a,b,c\}$ ,试消去下面公式中的量词。
> - a)  $(\forall x)P(x)$ ;
> - b)  $(\forall x)R(x) \land (\forall x)S(x)$ :
> - c)  $(\forall x)(P(x)\rightarrow Q(x));$
> - d)  $(\forall x) \neg P(x) \lor (\forall x) P(x)$ ;
> - e)  $(\forall x)R(x) \land (\exists x)S(x)$ .
> [2-4.(2)]
> - $\mathbf{H}$  a)  $(\forall x)P(x) \Leftrightarrow P(a) \land P(b) \land P(c)$
> - b)  $(\forall x)R(x) \land (\forall x)S(x) \Leftrightarrow$  $R(a) \land R(b) \land R(c) \land S(a) \land S(b) \land S(c)$
> - c)  $(P(a) \rightarrow Q(a)) \land (P(b) \rightarrow Q(b)) \land (P(c) \rightarrow Q(c))$
> - d)  $( P(a) \land P(b) \land P(c) ) \lor (P(a) \land P(b) \land P(c) )$
> - e)  $(R(a) \land R(b) \land R(c)) \land (S(a) \lor S(b) \lor S(c))$
> - **2-13** 设个体域为{0,1},将下列命题转换成不含量词的形式:
> - a)  $(\forall x)F(0,x)$ ;
> - b)  $(\forall x)(\forall y)F(x,y)$ ;
> - c)  $(\exists !x)(\forall y)F(x,y);$
> - d)  $(\exists x)((\forall y)F(x,y) \lor G(x));$
> - e)  $(\exists x)F(x)\rightarrow (\forall y)G(y)$ ;
> - f)  $(\forall x)((\exists y)F(x,y)\rightarrow G(x))$ .
> - **M** a)  $(\forall x)F(0,x) \Leftrightarrow F(0,0) \land F(0,1)$
> - b)  $(\forall x)(\forall y)F(x,y)\Leftrightarrow (\forall x)(F(x,0) \land F(x,1))$  $\Leftrightarrow (F(0,0) \land F(0,1)) \land (F(1,0) \land F(1,1))$
> - c)  $(\exists !x)(\forall y)F(x,y)\Leftrightarrow (\exists !x)(F(x,0) \land F(x,1))$   $\Leftrightarrow (F(0,0) \land F(0,1) \land \neg (F(1,0) \land F(1,1)))$  $\lor (F(1,0) \land F(1,1) \land \neg (F(0,0) \land F(0,1)))$
> - d)  $(\exists x)((\forall y)F(x,y) \lor G(x))$
> $\Leftrightarrow (\exists x)((F(x,0) \land F(x,1)) \lor G(x))$
> $\Leftrightarrow ((F(0,0) \land F(0,1)) \lor G(0))$
> $\forall ((F(1,0) \land F(1,1)) \lor G(1))$
> e)  $(\exists x)F(x) \rightarrow (\forall y)G(y)$
> $\Leftrightarrow F(0) \lor F(1) \rightarrow G(0) \land G(1)$
> f)  $(\forall x)((\exists y)F(x,y)\rightarrow G(x))$
> $\Leftrightarrow (\forall x)(F(x,0) \lor F(x,1) \rightarrow G(x))$
> $\Leftrightarrow$   $(F(0,0) \lor F(0,1) \rightarrow G(0))$
> $\bigwedge (F(1,0) \bigvee F(1,1) \rightarrow G(1))$
---
#### 2-14

> 寻求下列各式的真值:
> - a)  $(\forall x)(P(x) \lor Q(x))$ ,其中 P(x);x=1,Q(x);x=2 且论 域是 $\{1,2\}$ ;
> - b)  $(\forall x)(P \rightarrow Q(x)) \lor R(a)$ ,其中  $P:2 > 1, Q(x):x \le 3$ , R(x):x > 5, a:5 且论域 $\{-2,3,6\}$ 。 【2-4.(3)】

**解**：

a)  $(\forall x)(P(x) \lor Q(x)) \Leftrightarrow (P(1) \lor Q(1)) \land (P(2) \lor Q(2))$ 但 P(1)为 T,Q(1)为 F,P(2)为 F,Q(2)为 T,所以  $(\forall x)(P(x) \lor Q(x)) \Leftrightarrow (T \lor F) \land (F \lor T) \Leftrightarrow T$

b)  $(\forall x)(P \rightarrow Q(x)) \lor R(a) \Leftrightarrow ((P \rightarrow Q(-2)) \land (P \rightarrow Q(3)))$  $\land (P \rightarrow Q(6))) \lor R(a)$

因为P为T,Q(-2)为T,Q(3)为T,Q(6)为F,R(5)为F,

$(\forall x)(P \rightarrow Q(x)) \lor R(a) \Leftrightarrow (T \rightarrow T) \land (T \rightarrow T)$

$\land (T \rightarrow F)) \lor F \Leftrightarrow F$

---
#### 2-15

> 证明公式( $\forall x$ ) $P(x) \land (\exists y) \neg P(y)$ 是永假式。

**证明**：

假定公式( $\forall x$ )P(x)  $\land$  ( $(\exists y$ )  $\neg P(y)$  不是永假式,那 么至少存在某个赋值 T,在此赋值情况下( $\forall x$ )P(x) 与( $(\exists y$ )  $\neg P(y)$ 同时为 T。因为( $\forall x$ )P(x)为 T,故在论域 D 中对任意元 x,P(x)都为 T。( $(\exists y$ )  $\neg P(y)$   $\neg T$ 0,则在论域 D0 中,至少有某个元素 C0,使得  $\neg P(C)$   $\neg T$ 0,因而在这赋值情况下,有 D(C)  $\neg T$ 0,可得 D(C)0,为 D(C)1,不同

因此 $(\forall x)P(x) \land (\exists y) \neg P(y)$ 必是永假式。

---
#### 2-16

> 对下列谓词公式中的约束变元进行换名:
> - a)  $(\forall x)(\exists y)(P(x,z)\rightarrow Q(y)) \leftrightarrow S(x,y);$
> - b)  $(\forall x)(P(x) \rightarrow (R(x) \lor Q(x)) \land (\exists x)R(x) \rightarrow (\exists z)$  $S(x,z)$  [2-4. (4)]

**解**：

a)  $(\forall u)(\exists v)(P(u,z)\rightarrow Q(v)) \stackrel{\sim}{\leftrightarrow} S(x,y);$

b)  $(\forall u)(P(u) \rightarrow (R(u) \lor Q(u)) \land (\exists v)R(v) \rightarrow (\exists z)S(x,z)$ .

---
#### 2-17

> 对下列谓词公式中的自由变元进行代人:
> - a)  $((\exists y)A(x,y)\rightarrow (\forall x)B(x,z)) \land (\exists x)(\forall z)C(x,y,z);$
> - b)  $((\forall y)P(x,y) \land (\exists z)Q(x,z)) \lor (\forall x)R(x,y)$ .
> [2-4.(5)]
> $\mathbf{m} \quad \text{a)} \quad ((\exists y) A(u, y) \rightarrow (\forall x) B(x, v)) \land (\exists x) (\forall z) C(x, t, z)$
> - b)  $((\forall y)P(u,y) \land (\exists z)Q(v,z)) \lor (\forall x)R(x,t)$
---
#### 2-18

> 考虑以下赋值:论域 D={1,2}
> 指定常数a和b
> | a | b |
> |---|---|
> | 1 |
> ### 指定函数 f
> | f(1) | f(2) |
> |------|------|
> | 2    |
> ### 指定谓词 P
> | $\boldsymbol{T}$ | T       | F      | F      |
> |------------------|---------|--------|--------|
> | P(1,1)           | P(1, 2) | P(2,1) | P(2,2) |
> ### 求以下各式的真值:
> - a)  $P(a,f(a)) \wedge P(b,f(b));$
> - b)  $(\forall x)(\exists y)P(y,x)$ ;
> - c)  $(\forall x)(\forall y)(P(x,y) \rightarrow P(f(x),f(y)))$  [2-5.(1)]
> - 解 a)  $P(a, f(a)) \wedge P(b, f(b))$
> $\Leftrightarrow P(1, f(1)) \land P(2, f(2))$
> $\Leftrightarrow P(1,2) \land P(2,1) \Leftrightarrow T \land F \Leftrightarrow F$
> b)  $(\forall x)(\exists y)P(y,x)\Leftrightarrow (\forall x)(P(1,x) \lor P(2,x))$
> $\Leftrightarrow$   $(P(1,1) \lor P(2,1)) \land (P(1,2) \lor P(2,2))$
> $\Leftrightarrow$   $(T \lor T) \land (F \lor F) \Leftrightarrow F$
> - c)  $(\forall x)(\forall y)(P(x,y)\rightarrow P(f(x),f(y)))$
> - $\Leftrightarrow (\forall x)((P(x,1)\rightarrow P(f(x),f(1)))$
> $\bigwedge (P(x,2) \rightarrow P(f(x)f(2)))$
> $\Leftrightarrow$   $(P(1,1)\rightarrow P(f(1),f(1)))$
> $\wedge (P(1,2) \rightarrow P(f(1),f(2)))$
> $\bigwedge (P(2,1) \rightarrow P(f(2),f(1)))$
> $\wedge (P(2,2) \rightarrow P(f(2),f(2)))$
> $\Leftrightarrow$   $(P(1,1)\rightarrow P(2,2))$
> $\wedge (P(1,2) \rightarrow P(2,1))$
> $\land (P(2,1) \rightarrow P(1,2))$
> $\wedge (P(2,2) \rightarrow P(1,1))$
> $\Leftrightarrow (T \rightarrow F) \land (T \rightarrow F) \land (F \rightarrow T) \land (F \rightarrow T)$
> $\Leftrightarrow F \land F \land T \land T \Leftrightarrow F$
> ### 2-19 对以下各公式赋值后求真值:
> - a)  $(\forall x)(P(x)\rightarrow Q(f(x),a));$
> - b)  $(\exists x)(P(f(x)) \land Q(x, f(a));$
> - c)  $(\exists x)(P(x) \land Q(x,a));$
> - d)  $(\forall x)(\exists y)(P(x) \land Q(x,y))$ .
> ### 其中,论域 $D=\{1,2\},a=1$ 。
> [2-5, (2)]
> | f(1) | f(2) |
> |------|------|
> | 2    |
> | P(1) | P(2) |
> |------|------|
> | F    | T    |
> | Q(1,1) | Q(1,2) | Q(2,1) | Q(2,2) |
> |--------|--------|--------|--------|

**解**：

a)
$$(\forall x)(P(x)\rightarrow Q(f(x),a))$$

$$\Leftrightarrow (P(1) \rightarrow Q(f(1),1)) \land (P(2) \rightarrow Q(f(2),1))$$

$$\Leftrightarrow (\mathbf{F} \rightarrow \mathbf{Q}(2,1)) \land (\mathbf{T} \rightarrow \mathbf{Q}(1,1))$$

$$\Leftrightarrow$$
$(F \rightarrow F) \land (T \rightarrow T) \Leftrightarrow$  $T$

b)  $(\exists x)(P(f(x)) \land Q(x, f(a))$

$$\Leftrightarrow (P(f(1)) \land Q(1, f(1))) \lor (P(f(2))$$

$$\land Q(2, f(1)) \Leftrightarrow (T \land T) \lor (F \land F) \Leftrightarrow T$$

c)  $(\exists x)(P(x) \land Q(x,a))$

$\Leftrightarrow (P(1) \land Q(1,a)) \lor (P(2) \land Q(2,a))$

$\Leftrightarrow (P(1) \land Q(1,1)) \lor (P(2) \land Q(2,1))$

$\Leftrightarrow (F \land T) \lor (T \land F) \Leftrightarrow F$

d)  $(\forall x)(\exists y)(P(x) \land Q(x,y))$

$\Leftrightarrow (\forall x)(P(x) \land (\exists y)Q(x,y))$

$\Leftrightarrow (\forall x)(P(x) \land (Q(x,1) \lor Q(x,2)))$

$\Leftrightarrow ((P(1) \land (Q(1,1) \lor Q(1,2)))$

$\bigwedge (P(2) \bigwedge (Q(2,1) \vee Q(2,2)))$

$\Leftrightarrow (F \land (T \lor T)) \land (T \land (F \lor F)) \Leftrightarrow F$

---
#### 2-20 举例说明下列各蕴含式:

a)  $\neg ((\exists x)P(x) \land Q(a)) \Rightarrow (\exists x)P(x) \rightarrow \neg Q(a);$
b)  $(\forall x)( \neg P(x) \rightarrow Q(x)), (\forall x) \neg Q(x) \Rightarrow P(a);$

c)  $(\forall x)(P(x) \rightarrow Q(x)), (\forall x)(Q(x) \rightarrow R(x))$  $\Rightarrow (\forall x)(P(x) \rightarrow R(x));$
d)  $(\forall x)(P(x) \lor Q(x)), (\forall x) \neg P(x) \Rightarrow (\exists x)Q(x);$
e)  $(\forall x)(P(x) \lor Q(x)), (\forall x) \neg P(x) \Rightarrow (\forall x)Q(x)$ .

[2-5.(3)]

a) 因为

#### 故原式为

$(\exists x) P(x) \lor \neg Q(a) \Rightarrow (\exists x) P(x) \rightarrow \neg Q(a)$

设 P(x):x 是大学生。Q(x):x 是运动员。

前提 或者不存在 x,x 是大学生,或者 a 不是运动员。

结论 如果存在x是大学生,则必有a不是运动员。

b) 设 P(x):x 是研究生。Q(x):x 是大学生。a:论域中的某人。

前提 对论域中所有 x,如果 x 不是研究生,则 x 是大学生。 对论域中所有 x,x 不是大学生。

结论 对论域中的所有 x 都是研究生。故对论域中的某个 a ,必有结论 a 是研究生,即 P(a) 成立。

c) 设 P(x): x 是研究生。Q(x): x 曾读过大学。R(x): x 曾读过中学。

前提 对所有 x,如果 x 是研究生,则 x 曾读过大学。 对所有 x,如果 x 曾读过大学,则 x 曾读过中学。

结论 对所有x,如果x是研究生,则x曾读过中学。

d) 设 P(x):x 是研究生。Q(x):x 是运动员。

前提 对所有 x,或者 x 是研究生,或者 x 是运动员。 对所有 x,x 不是研究生。

结论 必存在 x,x 是运动员。

e) 设 P(x):x 是研究生。Q(x):x 是运动员。

前提 对所有 x,或者 x 是研究生,或者 x 是运动员。 对所有 x,x 不是研究生。

```
结论 对所有x,x是运动员。

---
#### 2-21

> 求证
> (\exists x)(A(x) \rightarrow B(x)) \Leftrightarrow (\forall x)A(x) \rightarrow (\exists x)B(x)
> [2-5, (4)]

**证明**：

(\exists x)(A(x) \rightarrow B(x)) \Leftrightarrow (\exists x)(\neg A(x) \lor B(x))
\Leftrightarrow (\exists x) \neg A(x) \lor (\exists x) B(x)
\Leftrightarrow \neg (\forall x) A(x) \lor (\exists x) B(x)
\Leftrightarrow (\forall x)A(x) \rightarrow (\exists x)B(x)

---
#### 2-22

> 设论域 D = \{a,b,c\},求证
> (\forall x)A(x) \lor (\forall x)B(x) \Rightarrow (\forall x)(A(x) \lor B(x))
> [2-5.(5)]

**证明**：

因为论域 D=\{a,b,c\},所以
(\forall x)A(x) \lor (\forall x)B(x)
\Leftrightarrow (A(a) \land A(b) \land A(c)) \lor (B(a) \land B(b) \land B(c))
\Leftrightarrow (A(a) \lor B(a)) \land (A(a) \lor B(b))
\bigwedge (A(a) \vee B(c)) \bigwedge (A(b) \vee B(a))
\bigwedge (A(b) \vee B(b)) \bigwedge (A(b) \vee B(c))
\bigwedge (A(c) \vee B(a)) \bigwedge (A(c) \vee B(b))
\Lambda(A(c) \vee B(c))
\Rightarrow (A(a) \lor B(a)) \land (A(b) \lor B(b)) \land (A(c) \lor B(c))
\Leftrightarrow (\forall x)(A(x) \lor B(x))
所以
(\forall x)A(x) \lor (\forall x)B(x) \Rightarrow (\forall x)((A(x) \lor B(x)))

---
#### 2-23

> 判断下列推证是否正确:
> (\forall x)(A(x)\rightarrow B(x))
> \Leftrightarrow (\forall x)(\neg A(x) \lor B(x))
> \Leftrightarrow (\forall x) \neg (A(x) \land \neg B(x))
> \Leftrightarrow \neg (\exists x)(A(x) \land \neg B(x))
> \Leftrightarrow \neg ((\exists x)A(x) \land (\exists x) \neg B(x))
> ```
> $\Leftrightarrow \neg (\exists x) A(x) \lor (\forall x) B(x)$
> ```
> \Leftrightarrow (\exists x)A(x)\rightarrow (\forall x)B(x)
> [2-5, (6)]

**解**：

推证不正确,因为
\exists x)(A(x) \land \neg B(x)) \Leftrightarrow \neg ((\exists x)A(x) \land (\exists x) \neg B(x))

---
#### 2-24

> 求证(\forall x)(\forall y)(P(x) \rightarrow Q(y))\Leftrightarrow(\exists x)P(x)
> \rightarrow (\forall y)Q(y)
> [2-5, (7)]

**证明**：

左式\leftrightarrow(\forall x)(\forall y)(\neg P(x) \lor Q(y))
\Leftrightarrow (\forall x) \neg P(x) \lor (\forall y) Q(y)
\Leftrightarrow \neg (\exists x) P(x) \lor (\forall y) Q(y)
\Leftrightarrow (\exists x) P(x) \rightarrow (\forall y) Q(y)

---
#### 2-25

> 把以下各式化为前束范式:
> a) (\forall x)(P(x)\rightarrow(\exists y)Q(x,y));
> b) (\exists x)(\neg((\exists y)P(x,y))\rightarrow((\exists z)Q(z)\rightarrow R(x)));
> c) (\forall x)(\forall y)(((\exists z)P(x,y,z) \land (\exists u)Q(x,u)) \rightarrow (\exists v)
> Q(y,v)).
> [2-6, (1)]

**解**：

a) (\forall x)(P(x)\rightarrow(\exists y)Q(x,y))
\Leftrightarrow (\forall x)(\neg P(x) \lor (\exists y)Q(x,y))
\Leftrightarrow (\forall x)(\exists y)(\neg P(x) \lor Q(x,y))
b) (\exists x)( \neg (\exists y)P(x,y)) \rightarrow ((\exists z)Q(z) \rightarrow R(x)))
\Leftrightarrow (\exists x)((\exists y)P(x,y) \lor ((\exists z)Q(z) \rightarrow R(x)))
\Leftrightarrow (\exists x)((\exists y)P(x,y) \lor (\exists z)Q(z) \lor R(x)))
\Leftrightarrow (\exists x)((\exists y)P(x,y) \lor ((\forall z) \neg Q(z) \lor R(x)))
\Leftrightarrow (\exists x)(\exists y)(\forall z)(P(x,y) \lor \neg Q(z) \lor R(x))
c) (\forall x)(\forall y)(((\exists z)P(x,y,z) \land (\exists u)Q(x,u))
\rightarrow (\exists v)Q(y,v))
\Leftrightarrow (\forall x)(\forall y)(\neg (\exists z)P(x,y,z))
\bigwedge (\exists u) Q(x,u)) \lor (\exists v) Q(y,v))
\Leftrightarrow (\forall x)(\forall y)((\forall z) \neg P(x,y,z)
\bigvee (\forall u) \neg Q(x,u) \bigvee (\exists v) Q(y,v)
\Leftrightarrow (\forall x)(\forall y)(\forall z)(\forall u)(\exists v)(\neg P(x,y,z))
\bigvee \neg Q(x,u) \bigvee Q(y,v)
```

```

---
#### 2-26

> 求等价于下面公式的前束合取范式与前束析取范式:
> a) ((\exists x)P(x) \lor (\exists x)Q(x)) \rightarrow (\exists x)(P(x) \lor Q(x));
> b) (\forall x)(P(x)\rightarrow(\forall y)((\forall z)Q(x,y)\rightarrow \neg(\forall z)R(y,x)));
> c) (\forall x)P(x) \rightarrow (\exists x)((\forall z)Q(x,z) \lor (\forall z)R(x,y,z));
> d) (\forall x)(P(x)\rightarrow Q(x,y))\rightarrow ((\exists y)P(y)\land (\exists z)Q(y,z)),
> [2-6.(2)]
> \mathbb{R} a) ((\exists x)P(x) \lor (\exists x)Q(x)) \rightarrow (\exists x)(P(x) \lor Q(x))
> \Leftrightarrow \neg (\exists x)(P(x) \lor Q(x)) \rightarrow (\exists x)(P(x) \lor Q(x)) \Leftrightarrow \mathbf{T}
> 因是特殊式永真,不写为前束范式形式。
> b) (\forall x)(P(x) \rightarrow (\forall y)((\forall z)Q(x,y) \rightarrow \neg (\forall z)R(y,x)))
> \Leftrightarrow (\forall x)(\neg P(x) \lor (\forall y)(Q(x,y) \rightarrow \neg R(y,x)))
> \Leftrightarrow (\forall x)(\forall y)(\neg P(x) \lor \neg Q(x,y) \lor \neg R(y,x))
> 前束合取范式
> \Leftrightarrow (\forall x)(\forall y)((P(x) \land Q(x,y) \land R(y,x))
> \bigvee (P(x) \land Q(x,y) \land \neg R(y,x))
> \forall (P(x) \land \neg Q(x,y) \land R(y,x))
> \forall ( \neg P(x) \land Q(x,y) \land R(y,x))
> \bigvee (   P(x)
> \forall (P(x) \land \neg Q(x,y) \land \neg R(y,x))
> \forall ( \neg P(x) \land Q(x,y) \land \neg R(y,x)))
> 前束析取范式
> c) (\forall x)P(x) \rightarrow (\exists x)((\forall z)Q(x,z) \lor (\forall z)R(x,y,z))
> \Leftrightarrow \neg (\forall x) P(x) \lor (\exists x) ((\forall z) Q(x,z))
> \forall (\forall z)R(x,y,z))
> \Leftrightarrow (\exists x) \neg P(x) \lor (\exists x) ((\forall z) Q(x,z))
> \forall (\forall u)R(x,y,u))
> \Leftrightarrow (\exists x)( \neg P(x) \lor (\forall z)Q(x,z)
> \bigvee (\forall u) R(x,y,u)
> \Leftrightarrow (\exists x)(\forall z)(\forall u)(\neg P(x) \lor Q(x,z))
> \forall R(x,y,u)
> ```
> ```
> \Leftrightarrow (\exists x)(\forall z)(\forall u)(P(x) \land Q(x,z) \land R(x,y,u))
> \forall (P(x) \land Q(x,z) \land \neg R(x,y,u))
> \forall (P(x) \land \neg Q(x,z) \land R(x,y,u))
> \forall (P(x) \land \neg Q(x,z) \land \neg R(x,y,u))
> \bigvee (   P(x) \land Q(x,z) \land   R(x,y,u) )
> \forall ( \neg P(x) \land \neg Q(x,z) \land R(x,y,u))
> \forall . ( \neg P(x) \land \neg Q(x,z) \land \neg R(x,y,u))
> 前束析取范式
> d) (\forall x)(P(x)\rightarrow Q(x,y))\rightarrow ((\exists y)P(y) \land (\exists z)Q(y,z))
> \Leftrightarrow \neg (\forall x)(\neg P(x) \lor Q(x,y))
> \forall ((\exists y)P(y) \land (\exists z)Q(y,z))
> \Leftrightarrow (\exists x)(P(x) \land \neg Q(x,y))
> \bigvee ((\exists u) P(u) \land (\exists z) Q(y,z))
> \Leftrightarrow (\exists x)(\exists u)(\exists z)((P(x) \land \neg Q(x,y))
> \bigvee (P(u) \land Q(y,z))
> 前束析取范式
> \Leftrightarrow (\exists x)(\exists u)(\exists z)((P(x) \lor P(u))
> \bigwedge (P(x) \vee Q(y,z))
> \bigwedge (   Q(x, y)
> \bigwedge \left(   Q(x,y)
> 前東合取范式
---
#### 2-27

> 证明以下各式:
> a) (\forall x)(\neg A(x) \rightarrow B(x)), (\forall x) \neg B(x) \Rightarrow (\exists x)A(x);
> b) (\exists x)A(x) \rightarrow (\forall x)B(x) \Rightarrow (\forall x)(A(x) \rightarrow B(x));
> c) (\forall x)(A(x)\rightarrow B(x)), (\forall x)(C(x)\rightarrow \neg B(x))
> \Rightarrow (\forall x)(C(x) \rightarrow \neg A(x));
> d) (\forall x)(A(x) \lor B(x)), (\forall x)(B(x) \rightarrow \neg C(x), (\forall x)C(x))
> [2-7, (1)]
> \Rightarrow (\forall x)A(x).
> P

**证明**：

a) (1) (\forall x)( \neg A(x) \rightarrow B(x))
(1)US
(2) \neg A(u) \rightarrow B(u)
```

前束合取范式

| (3) $(\forall x) \neg B(x)$                      | P                  |
|-----------------------------------------------------|--------------------|
| $(4)  \neg B(u)$                                 | (3)US <sup>-</sup> |
| $(5) \ A(u) \lor B(u)$                              | (2)T,E             |
| (6) A(u)                                            | (4)(5)T,I          |
| $(7) (\exists x) A(x)$                              | EG                 |
| b) (1) $\neg (\forall x)(A(x) \rightarrow B(x))$    | P(附加前提)            |
| $(2) (\exists x) \neg (A(x) \rightarrow B(x))$      | (1)T,I             |
| $(3)  \neg (A(c) \rightarrow B(c))$                 | (2)ES              |
| $(4) \ A(c)$                                        | (3)T,I             |
| (5) $\neg B(c)$                                  | (3)T,I             |
| $(6) (\exists x) A(x)$                              | (4)EG              |
| $(7) (\exists x) A(x) \rightarrow (\forall x) B(x)$ | P                  |
| $(8) (\forall x)B(x)$                               | (6)(7)T,I          |
| (9) B(c)                                            | (8)US              |
| (10) $B(c) \land \neg B(c)$                         | 矛盾(5)(9)           |
| c) (1) $(\forall x)(A(x) \rightarrow B(x))$         | P                  |
| $(2) \ A(u) \rightarrow B(u)$                       | (1)ES              |
| $(3) (\forall x)(C(x) \rightarrow \neg B(x))$       | P                  |
| $(4) C(u) \rightarrow \neg B(u)$                    | (3) <i>ES</i>      |
| $(5)  \neg B(u) \rightarrow \neg A(u)$        | (2)T,E             |
| $(6) C(u) \to \neg A(u)$                            | (4)(5)T,I          |
| $(7) (\forall x)(C(x) \to \neg A(x))$               | (6) <i>UG</i>      |
| d) (1) $(\forall x)(B(x) \rightarrow \neg C(x))$    | P                  |
| $(2) B(u) \to \neg C(u)$                            | (1) <i>US</i>      |
| $(3) (\forall x)C(x)$                               | P                  |
| (4) C(u)                                            | (3) <i>US</i>      |
| $(5)  \neg B(u)$                                 | (2)(4)T,I          |
| (6) $(\forall x)(A(x) \lor B(x))$                   | P                  |
| $(7) \ A(u) \lor B(u)$                              | (6)US              |
| (8) A(u)                                            | (5)(7)T,I          |

| $(9) (\forall x)A(x)$                                                    | (8) <i>UG</i>                      |
|--------------------------------------------------------------------------|------------------------------------|
| 2-28 用 CP 规则证明:                                                          |                                    |
| a) $(\forall x)(P(x)\rightarrow Q(x))\Rightarrow (\forall x)P(x)$        | $\rightarrow (\forall x)Q(x);$     |
| b) $(\forall x)(P(x) \lor Q(x)) \Rightarrow (\forall x)P(x)$             | $(\exists x)Q(x)$ .                |
|                                                                          | [2-7.(2)]                          |
| 证明                                                                       |                                    |
| a) (1) $(\forall x)P(x)$                                                 | P(附加前提)                            |
| (2) P(u)                                                                 | (1) <i>U</i> S                     |
| $(3) (\forall x)(P(x) \rightarrow Q(x))$                                 | P                                  |
| $(4) P(u) \rightarrow Q(u)$                                              | (3) <i>US</i>                      |
| (5) Q(u)                                                                 | (2)(4)T,I                          |
| (6) $(\forall x)Q(x)$                                                    | (5) <i>UG</i>                      |
| $(7) \ (\forall x) P(x) \rightarrow (\forall x) Q(x)$                    | CP                                 |
| b) 因为                                                                    |                                    |
| $(\forall x)P(x) \lor (\exists x)Q(x) \Leftrightarrow \neg (\forall x)P$ | $(x) \rightarrow (\exists x) Q(x)$ |
| 故本题就是推证:                                                                 |                                    |
| $(\forall x)(P(x) \lor Q(x)) \Rightarrow \neg (\forall x)P(x)$           | $(x) \rightarrow (\exists x) Q(x)$ |
| $(1)  \neg (\forall x) P(x)$                                             | P(附加前提)                            |
| $(2) (\exists x) \neg P(x)$                                           | (1)T,E                             |
| (3) $\neg P(c)$                                                       | (2)ES                              |
|                                                                          |                                    |

| $(1)  \neg (\forall x) P(x)$                                 | P(附加前提           |
|--------------------------------------------------------------|------------------|
| $(2) (\exists x) \neg F(x)$                               | (1)T,E           |
| (3) $\neg P(c)$                                              | (2)ES            |
| $(4) (\forall x)(P(x) \lor Q(x))$                            | $\boldsymbol{P}$ |
| $(5) P(c) \vee Q(c)$                                         | (4) <i>US</i>    |
| (6) Q(c)                                                     | (3)(5)T,I        |
| $(7) (\exists x) Q(x)$                                       | (6)EG            |
| $(8)  \neg (\forall x) P(x) \rightarrow (\exists x) Q(x)$ | CP               |

---
#### 2-29

> 符号化下列命题,并推证其结论:
> - a) 所有有理数是实数,某些有理数是整数,因此某些实数是整数。
> - b) 任何人如果他喜欢步行,他就不喜欢乘汽车,每一个人或者喜欢乘汽车,或者喜欢骑自行车。有的人不爱骑自行车,因而有
> • 91 •
> 的人不爱步行。
> c)每个大学生,不是文科学生,就是理工科学生,有的大学生是优等生,小张不是理工科学生,但他是优等生,因而如果小张是大学生,他就是文科生。

**解**：

a) 设 R(x):x 是实数。Q(x):x 是有理数。I(x):x 是整数。 本题符号化为:

$$(\forall x)(Q(x) \rightarrow R(x)) \land (\exists x)(Q(x) \land I(x))$$

$$\Rightarrow (\exists x)(R(x) \land I(x))$$

(1)  $(\exists x)(Q(x) \land I(x))$

$\boldsymbol{P}$

(2)  $Q(c) \wedge I(c)$

(1)ES

(3)  $(\forall x)(Q(x) \rightarrow R(x))$

$\boldsymbol{P}$

(4)  $Q(c) \rightarrow R(c)$

(3)US

(5) Q(c)

(2)T,I

(6) R(c)

(4)(5)T,I

(7) I(c)

(2)T,I

(8)  $R(c) \wedge I(c)$

(6)(7)T,I

(9)  $(\exists x)(R(x) \land I(x))$

(8)EG

b) 设 P(x):x 喜欢步行。Q(x):x 喜欢乘汽车。R(x):x 喜欢骑自行车。

本题符号化为:

$(\forall x)(P(x) \rightarrow \neg Q(x)), (\forall x)(Q(x) \lor R(x)),$

$(\exists x) \neg R(x) \Rightarrow (\exists x) \neg R(x)$

(1)  $(\exists x) \neg R(x)$

P

(2)  $\neg R(c)$

(1)ES

(3)  $(\forall x)(Q(x) \lor R(x))$

P

(4)  $Q(c) \vee R(c)$

(3)US

(5) Q(c)

(2)(4)T,I

(6)  $(\forall x)(P(x) \rightarrow \neg Q(x))$

P

(7)  $P(c) \rightarrow \neg Q(c)$

(6)US

(8)  $\neg P(c)$

(5)(7)T,I

(9)  $(\exists x) \neg P(x)$

(8) EG

c) 设 G(x):x 是大学生。L(x):x 是文科学生。P(x):x 是理工科学生。S(x):x 是优秀生。c:小张。

本题符号化为:

$$(\forall x)(G(x) \to L(x) \lor P(x)), (\exists x)(G(x) \land S(x)),$$

$$\neg P(x) S(x) \to G(x) \to I(x)$$

$(2) (\forall x)(G(x) \rightarrow L(x) \lor P(x))$

$(3) \ G(c) \rightarrow L(c) \lor P(c)$

(2)US

$(4)\ L(c) \lor P(c)$

(1)(3)T,I

(5)  $\neg P(c)$

P

(6) L(c)

(4)(5)T.I

(7)  $G(c) \rightarrow L(c)$

CP

注意:本题在推证过程中未用到前提( $(\exists x$ )( $G(x) \land S(x)$ )以及 S(c)。主要是 S(x):x 是优等生,这个条件与其他前提的联系对证明结论没有影响,因 S(x)与其他前提不矛盾,故本题推证仍是有效的。

---
#### 2-30 用推理规则证明下式:

前提  $(\exists x)(F(x) \land S(x)) \rightarrow (\forall y)(M(y) \rightarrow W(y))$  $(\exists y)(M(y) \land \neg W(y))$

结论  $(\forall x)(F(x) \rightarrow \neg S(x))$

$(1) (\exists y) (M(y) \land \neg W(y))$

$\boldsymbol{P}$

(2)  $M(c) \wedge \neg W(c)$

(1)ES

$(3)$

(2)T,E (3)EG

(5)  $\neg (\forall y)(M(y) \rightarrow W(y))$

(4)T,E

(6)  $(\exists x)(F(x) \land S(x))$

$\rightarrow (\forall y)(M(y) \rightarrow W(y)) \qquad P$

--

## 第三章 集合与关系

#### 3-1

> 写出下列集合的表达式:
> - a) 所有一元一次方程的解组成的集合;
> - b)  $x^6-1$  在实数域中的因式集;
> - c) 在直角坐标系中单位圆内(不包括单位圆周)的点集;
> - d) 极坐标系中,单位圆外(不包括单位圆周)的点集;
> - e) 能被5整除的整数集。
> [3-1.(1)]

**解**：

a)  $S = \{x \mid ax + b = 0, a \neq 0\}$

b)  $D = \{x+1, x-1, x^2+x+1, x^2-x+1, x^2-1, x^3+2x^2+2x+1, x^3+1, x^3-1, x^3-2x^2+2x+1, x^4+x^2+1, x^5-x^4+x^3-x^2+x-1, x^5+x^4+x^3+x^2+x+1, x^4-x^3+x-1, x^4+x^3-x-1, x^6-1\}$
c)  $P = \{\langle x, y \rangle | x^2 + y^2 < 1\}$
d)  $P = \{\langle \rho, \theta \rangle | \rho^2 > 1\}$
e)  $I_5 = \{5x | x \in I\}$

---
#### 3-2

> 某电视台,拟制定一项为时半小时的节目,其中包含戏剧、音乐与广告,每项节目都定为五分钟的倍数,试求:
> - a) 各种时间分配情况的集合;
> - b) 戏剧所分配的时间较音乐多的集合;
> - c) 广告所分配的时间与音乐或戏剧所分配的时间相等的 集合;
> - d) 音乐所分配的时间恰为五分钟的集合。 【3-1.(2)】

**解**：

a) 各种时间分配情况的集合:

$T = \{\langle 5, 5, 20 \rangle, \langle 5, 10, 15 \rangle, \langle 5, 15, 10 \rangle, \langle 5, 20, 5 \rangle, \langle 10, 5, 15 \rangle, \langle 10, 10, 10 \rangle, \langle 10, 15, 5 \rangle, \langle 15, 5, 10 \rangle, \langle 15, 10, 5 \rangle, \langle 20, 5, 5 \rangle\}$

b) 戏剧所分配的时间较音乐多的集合:

$D = \{\langle 10, 5, 15 \rangle, \langle 15, 5, 10 \rangle, \langle 15, 10, 5 \rangle, \langle 20, 5, 5 \rangle\}$

c) 广告分配的时间与音乐或戏剧所分配的时间相等的集合:

$S = \{\langle 5, 20, 5 \rangle, \langle 10, 10, 10 \rangle, \langle 20, 5, 5 \rangle\}$

d) 音乐所分配的时间恰为五分钟的集合:  $M = \{\langle 5, 5, 20 \rangle, \langle 10, 5, 15 \rangle, \langle 15, 5, 10 \rangle, \langle 20, 5, 5 \rangle\}$

---
#### 3-3

> 给定集合 A,B 和 C 的例子,使得
> $A \in B, B \in C, \neg A \notin C$
> [3-1.(3)]

**解**：

设  $A = \{1\}, B = \{1, \{1\}\}, C = \{2, \{1, \{1\}\}\},$ 就有  $A \in B, B \in C,$ 和  $A \notin C$

---
#### 3-4

> 给定集合 A 描述为  $A = \{2,4,8,\cdots\}$ ,你能认为  $16 \in A$  吗?

**解**：

如果  $A = \{x \mid x \in 2^n, n \in E$  是正整数 $\}$ ,则  $16 \in A$ ;如果  $A = \{x \mid x = 2 + n(n-1), n \in E$  正整数 $\}$ ,则  $16 \notin A$ 。

---
#### 3-5

> 设  $R = \{1,3,\Pi,4.1,9,10\}, S = \{\{1\},3,9,10\}, T = \{1,3,\Pi\}, U = \{\{1,3,\Pi\},1\}.$  以下各式中哪些为真? 哪些不成立,为什么不成立?
> a)  $S \subseteq R$ :
> g)  $T \subseteq R$ ;
> b)  $1 \in R$ :
> h)  $\{1\} \in S$ ;
> c)  $1 \in S$ ;
> i) Ø⊆S;
> d) 1⊆U:
> j) *T*⊆*U*;
> e)  $\{1\}\subseteq T$ ;
> k)  $T \in U$ ;
> f) {1}⊆S;
> - 1) T#R.

**解**：

b) 真; e) 真; g) 真;
h) 真; i) 真; k) 真; l) 真。
a) 假,因为{1}∈S但{1}∉R:
c) 假,因为 $\{1\} \in S$ ,不是 $1 \in S$ ;
d) 假,1 不是一个集合;
f) 假,1∉S;
j) 假,3∉U且 II ∉U。

---
#### 3-6

> 对任意集合 A, B, C 确定下列命题是否为真, 并证明之。
> - a) 如果  $A \in B$  及  $B \subseteq C$ ,则  $A \in C$ ;
> - b) 如果  $A \in B$  及  $B \subseteq C$ ,则  $A \subseteq C$ ;
> - c) 如果  $A \subseteq B$  及  $B \in C$ ,则  $A \in C$ :
> - d) 如果  $A \subseteq B$  及  $B \in C$ ,则  $A \subseteq C$ ;
> - e) 如果  $A \in B$  及  $B \nsubseteq C$ ,则  $A \notin C$ ;
> - f) 如果  $A \subseteq B$  及  $B \in C$ ,则  $A \notin C$ 。
> [3-1,(4)]

**解**：

a) 真。因为  $B \subseteq C$ ,故  $A \in B \Rightarrow A \in C$ 。

b) 假。例如  $A = \{a\}, B = \{b, \{a\}\}, C = \{d, b, \{a\}\}, \mathbf{M} \in B$ ,  $B \subseteq C$ , 但  $A \nsubseteq C$ 。
c) 假。例如  $A = \{a\}$ ,  $B = \{a,b\}$ ,  $C = \{a,\{a,b\}\}$ , 则  $A \subseteq B$ ,  $B \in C$ , 但  $A \notin C$ .
d) 假。例如  $A = \{1,2\}, B = \{1,2,\{3\}\}, C = \{\{1,2,\{3\}\}\},$ 4 $\}$ ,则  $A \subseteq B, B \in C$  但  $A \nsubseteq C$ 。
e) 假。例如  $A = \{a\}, B = \{\{a\}, b\}, C = \{\{a\}, d\},$ 则  $A \in B$ ,  $B \nsubseteq C$ , 但  $A \in C$ 。
f) 假。例如  $A=\{a\}, B=\{a,b\}, C=\{\{a,b\}, \{a\}\}, 则 A\subseteq B, B\in C, \exists, A\in C, a\in A$

是可能的。因为  $A \subseteq B$ ,要求 A 中的元素都在 B 中,但 B 中除去 A 的元素外,还可能有其他元素。故如 B 中有元素为集合 A 时,则本命题就可能成立的。

例如: $A = \{a\}$ , $B = \{a, \{a\}\}$ ,则就有  $A \subseteq B \land A \in B$ 。

---
#### 3-8

> 确定下列集合的幂集:
> - a)  $\{a,\{a\}\}$ ; b)  $\{\{1,\{2,3\}\}\}$ ; c)  $\{\emptyset,a,\{b\}\}$ ;
> - d)  $\mathcal{P}(\emptyset)$ ; e)  $\mathcal{P}(\mathcal{P}(\emptyset))$ .
> [3-1.(6)]

**解**：

a) 设 $A = \{a, \{a\}\}, 则$

$$\mathcal{P}(A) = \{\emptyset, \{a\}, \{\{a\}\}, \{a, \{a\}\}\}\}$$

b)  $\&B = \{\{1,\{2,3\}\}\}, \emptyset$

$$\mathcal{P}(B) = \{\emptyset, \{\{1, \{2,3\}\}\}\}\aleph$$

c) 设  $E = \{\emptyset, a, \{b\}\}, 则$   $\mathscr{P}(E) = \{\emptyset, \{a\}, \{\{b\}\}, \{\emptyset\}, \{\emptyset, a\}, \{\emptyset, \{b\}\}\}, \{\emptyset, a, \{b\}\}\}$
d) 因为 $\mathcal{P}(\emptyset) = \{\emptyset\}, 则$

$$\mathcal{P}(\mathcal{P}(\emptyset)) = \{\emptyset, \{\emptyset\}\}$$

e)  $\mathcal{P}(\mathcal{P}(\mathcal{P}(\emptyset))) = \{\emptyset, \{\emptyset\}, \{\{\emptyset\}\}, \{\emptyset, \{\emptyset\}\}\}\}$

---
#### 3-9 证明 若  $B \subseteq C$ ,则 $\mathcal{P}(B) \subseteq \mathcal{P}(C)$ 。

$\forall X \in \mathcal{P}(B)$ ,则  $X \subseteq B$ 。因为  $B \subseteq C$ ,故  $X \subseteq C$ ,即  $X \in \mathcal{P}(C)$ ,于是  $\mathcal{P}(B) \subseteq \mathcal{P}(C)$ 。

---
#### 3-10

> 证明 对任意集合 A 和 B,  $\mathscr{P}(A) \cap \mathscr{P}(B) = \mathscr{P}(A \cap B)$ 。

**证明**：

设任意  $x \in [\mathscr{P}(A) \cap \mathscr{P}(B)]$ , 则  $x \in \mathscr{P}(A)$ 且  $x \in \mathscr{P}(B)$ , 即有

$$x \subseteq A \perp x \subseteq B \Rightarrow x \subseteq A \cap B \Rightarrow x \in \mathcal{P}(A \cap B)$$

所以

$[\mathscr{P}(A)\cap\mathscr{P}(B)]\subseteq\mathscr{P}(A\cap B)$

反之,对任意  $x \in \mathcal{P}(A \cap B) \Rightarrow x \subseteq A \cap B$ 。故对所有  $a \in x$ ,有  $a \in A \cap B$ ,即  $a \in x$  则  $a \in A$  且  $a \in B$ ,所以  $a \in x$ ,则  $a \in A$ ,且  $a \in x$  则  $a \in B$ ,即  $x \subseteq A$  且  $x \subseteq B$ ,得到  $x \in \mathcal{P}(A)$  且  $x \in \mathcal{P}(B)$ ,故 $x \in \mathcal{P}(A) \cap \mathcal{P}(B)$  ]。所以

$$\mathscr{P}(A \cap B) \subseteq [\mathscr{P}(A) \cap \mathscr{P}(B)]$$

综上可得

$$\mathcal{P}(A) \cap \mathcal{P}(B) = \mathcal{P}(A \cap B)$$

---
#### 3-11 证明  $\mathcal{P}(A) \cup \mathcal{P}(B) \subseteq \mathcal{P}(A \cup B)$ ,在什么条件下等式成立。

设任意  $x \in (\mathcal{P}(A) \cup \mathcal{P}(B))$ ,则  $x \in \mathcal{P}(A)$ 或  $x \in \mathcal{P}(B)$ 。

a) 若  $x \in \mathcal{P}(A)$ ,则  $x \subseteq A$ ,对任意

$a \in x \Rightarrow a \in A \Rightarrow a \in A \cup B$

b) 若  $x \in \mathcal{P}(B)$ ,则  $x \subseteq B$ ,对任意

$a \in x \Rightarrow a \in B \Rightarrow a \in A \cup B$

由 a),b)得  $x\subseteq A\cup B$ ,即  $x\in \mathcal{P}(A\cup B)$ ,所以

$\mathcal{P}(A) \cup \mathcal{P}(B) \subseteq \mathcal{P}(A \cup B)$

当  $A \subseteq B$  时, $\mathcal{P}(A) \subseteq \mathcal{P}(B)$ ,故  $A \subseteq B$  时有  $A \cup B = B$ ,且  $\mathcal{P}(A) \cup \mathcal{P}(B) = \mathcal{P}(B)$

即题设的等式成立。

$B\subseteq A$  时情况同。

---
#### 3-12

> $\mathcal{P}(A-B)$ 是否等于 $\mathcal{P}(A)-\mathcal{P}(B)$ ,试予证明。

**证明**：

$\mathcal{P}(A-B)$ 不一定等于 $\mathcal{P}(A)-\mathcal{P}(B)$ 。例如:设 $A\cap B\neq\emptyset$ ,且 $A\cap B\neq A$ ,若 $x\in A\cap B$ ,则 $x\in A$ 且 $x\in B$ 。又设 $y\in A-B$ ,则 $y\in A\wedge y\notin B$ 。由 $\{x,y\}\in\mathcal{P}(A)$ ,有

$$\{x,y\}\subseteq A$$

同样 $\{x,y\} \notin \mathcal{P}(B)$ ,有

$\{x,y\} \subseteq B$

于是  $\mathcal{P}(A-B)\neq\mathcal{P}(A)-\mathcal{P}(B)$

---
#### 3-13

> 证明对每个集合 S, $\{\emptyset,\{\emptyset\}\}$ ∈  $\mathcal{P}\mathcal{P}\mathcal{P}(S)$ 成立。

**证明**：

对所有集合  $S,\emptyset\subseteq S,$ 所以 $\emptyset\in\mathcal{P}(S),\{\emptyset\}\subseteq\mathcal{P}(S),\{\emptyset\}\in\mathcal{P}(S),$   $\{\emptyset\}\in\mathcal{P}(S)$ 。因为 $\emptyset\subseteq\mathcal{P}(S)$ ,故 $\emptyset\in\mathcal{P}(S)$ ,所以 $\{\emptyset,\{\emptyset\}\}\subseteq\mathcal{P}(S)$ ,即 $\{\emptyset,\{\emptyset\}\}\in\mathcal{P}\mathcal{P}(S)$ 。

---
#### 3-14

> 假定 $\mathcal{P}(A) = \mathcal{P}(B)$ ,证明A = B。

**证明**：

对任意  $a \in A$  有 $\{a\} \subseteq A$ ,所以 $\{a\} \in \mathcal{P}(A)$ 。因为  $\mathcal{P}(A) = \mathcal{P}(B)$ ,故 $\{a\} \in \mathcal{P}(B)$ 即 $\{a\} \subseteq B$ ,得到  $a \in B$ 。所以  $A \subseteq B$ 。

同理可证  $B \subseteq A$ 。

因此 A=B。

---
#### 3-15

> 假定  $x \in B, y \in B$ ,证明 $\{\{x\}, \{x,y\}\} \in \mathcal{P}(\mathcal{P}(B))$ 。

**证明**：

由  $x \in B, y \in B, \{x\} \in \mathcal{P}(B), \{x,y\} \in \mathcal{P}(B), \{x\}, \{x,y\}\} \subseteq \mathcal{P}(B), \{x\}, \{x,y\}\} \in \mathcal{P}(\mathcal{P}(B))$ 。

---
#### 3-16

> 设 $A = \{\emptyset\}, B = \mathcal{P}(\mathcal{P}(A))$ :
> - a) 是否 $\emptyset \in B$ ? 是否 $\emptyset \subseteq B$ ?
> - b) 是否{∅}∈B? 是否{∅}⊆B?
> c) 是否{{∅}}⊆B? 是否{{∅}}⊆B?
> [3-1.(7)]

**解**：

设  $A = \{\emptyset\}$ ,  $\mathcal{P}(A) = \{\emptyset, \{\emptyset\}\}, B = \mathcal{P}(\mathcal{P}(A)) = \{\emptyset, \{\emptyset\}, \{\emptyset\}\}, \{\emptyset, \{\emptyset\}\}\}, $

a)  $\emptyset \in B, \emptyset \subseteq B$  成立;
b)  $\{\emptyset\} \in B$ ,且 $\{\emptyset\} \subseteq B$ 成立;
c)  $\{\{\emptyset\}\}\in B, \{\{\emptyset\}\}\subseteq B$ 成立。

---
#### 3-17

**证明**：

若 a,b,c 是任意客体,则
$$\{\{a\},\{a,b\}\}=\{\{c\},\{c,d\}\}$$
当且仅当 a=c,且 b=d。
[3-1.(8)]
充分性 若 a=c,b=d,则 $\{a\}=\{c\}$ 且 $\{a,b\}=\{c,d\}$ , 故 $\{\{a\},\{a,b\}\}=\{\{c\},\{c,d\}\}$ 。
必要性 若 $\{\{a\},\{a,b\}\}=\{\{c\},\{c,d\}\}$ ,由集合相等的条件,必有
- a)  $\{a\} = \{c\} \underline{1} \{a,b\} = \{c,d\}$ ,则有 a=c  $\underline{1} \{a,b\} = \{c,d\}$ ,故有 a=c  $\underline{1} b=d$ ;
- b)  $\{a\} = \{c,d\} \perp \{c\} = \{a,b\}$ ,则有 c = d = a,且 c = a = b,即 c = a = b = d。
---
#### 3-18

> 设某集合有 101 个元素,试问:
> - a) 可构成多少个子集?
> - b) 其中有多少个子集元素为奇数?
> - c) 是否有 102 个元素的子集?
> [3-1.(9)]

**解**：

a) 可构成 2<sup>101</sup>个子集;

b) 有 2<sup>101</sup>/2 个子集元素为奇数;
c) 不能有 102 个元素的子集。

---
#### 3-19 设  $S = \{a_1, a_2, \dots, a_8\}, B_i$  是 S 的子集,由  $B_{17}$ 和  $B_{31}$ 表达的子集是什么? 应如何规定子集 $\{a_2, a_6, a_7\}$ 和 $\{a_1, a_8\}$ 。

[3-1.(10)]

$$B_{17} = B_{00010001} = \{a_4, a_8\}$$

$B_{31} = B_{00011111} = \{a_4, a_5, a_6, a_7, a_8\}$

$$\{a_2, a_6, a_7\} = B_{0100011} = B_{35}$$

$\{a_1, a_8\} = B_{10000001} = B_{129}$

---
#### 3-20

> 设 $A = \{x \mid x < 5, x \in N\}, B = \{x \mid x < 7, x$ 是正偶数}, 求 $A \cup B, A \cap B$ 。
> $$\begin{array}{ll}
> \mathbf{A} & A \cup B = \{0,1,2,3,4,6\} \\
> A \cap B = \{2,4\}
> \end{array}$$
---
#### 3-21

> 设 $A = \{x \mid x \text{ book 中的字母}\}, B = \{x \mid x \text{ E black 中的字母}\}, 求 A \cup B, A \cap B$ 。 【3-2.(2)】
> $\mathbf{H} \quad A \cup B = \{b,1,a,c,o,k\}, A \cap B = \{b,k\}$
---
#### 3-22

> 给定下列自然数子集:
> $$A = \{1,2,7,8\};$$
> $B = \{i | i^2 < 50\};$
> $C = \{i \mid i$  可被 3 整除, $0 \le i \le 30\}$ ;
> $D=\{i | i=2^K, K \in I_+, 1 \leq K \leq 6\}$
> 求下列集合:
> - a)  $A \cup (B \cup (C \cup D))$ :
> - b)  $A \cap (B \cap (C \cap D))$ ;
> - c)  $B-(A \cup C)$ :
> - d)  $(\sim A \cap B) \cup D$ .
> [3-2,(3)]

**解**：

因为

$$A = \{1,2,7,8\}$$

$B = \{0,1,2,3,4,5,6,7\}$

$C = \{0,3,6,9,12,15,18,21,24,27,30\}$

$D = \{2,4,8,16,32,64\}$

则

a)  $A \cup (B \cup (C \cup D)) = A \cup B \cup C \cup D$ =  $\{0,1,2,3,4,5,6,7,8,9,12,15,16,18,21,24,27,30,32,64\}$

b)  $A \cap (B \cap (C \cap D)) = A \cap B \cap C \cap D = \emptyset$
c)  $A \cup C = \{0,1,2,3,6,7,8,9,12,15,18,21,24,27,30\}$

所以

$$B - (A \cup C) = \{4,5\}$$

d) 由于  $(\sim A \cap B) = B - A = \{0, 3, 4, 5, 6\}$

故

$$(\sim A \cap B) \cup D = \{0,2,3,4,5,6,8,16,32,64\}$$

---
#### 3-23

> 设  $A = \{2,4,5,6,8\}, B = \{1,4,5,9\}, C = \{x \mid x \in I_+ \}$  $2 \le x \le 5$ , 为  $S = \{0.1, 2.3, 4.5, 6.7, 8.9\}$ 的子集,求
> a)  $\sim (A \cap B)$ :
> - b) C-B:
> - c)  $(C \cap B) \cup \sim A$ : d)  $\sim (B-A) \cap (A-B)$ :
> - e)  $\sim (\sim C \cup B)$ .

**解**：

a) 因  $A \cap B = \{4,5\}$ ,故

$$\sim (A \cap B) = S - (A \cap B) = \{0,1,2,3,6,7,8,9\}$$

h)

$C B = \{2,3\}$
c)  $\Box B = \{4\}, \sim A = \{0,1,3,7,9\},$ 故  $(C \cap B) \cup \sim A = \{0,1,3,4,7,9\}$
d)  $\boxtimes \sim (B-A) = \{0,2,3,4,5,6,7,8\}, A-B = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\}, \text{ in } A = \{2,6,8\},$  $\sim (B-A) \cap (A-B) = \{2,6,8\}$
e) 故  $\sim (\sim C \cup B) = \{2,3\}$

---
#### 3-24

**证明**：

对任意集合 A,B,C 有
$(A \cap B) \cup C = A \cap (B \cup C)$  iff  $C \subseteq A$  [3-2.(4)]
必要性 对任意  $x \in C$ ,必有  $x \in (A \cap B) \cup C$ ,因为
$A \cap (B \cup C) = (A \cap B) \cup C$
故  $x \in C \Rightarrow x \in A \cap (B \cup C) \Rightarrow x \in A \land x \in (B \cup C)$ 即  $C\subseteq A$ 。
充分性 若  $C \subseteq A$ ,则  $A \cup C = A$ ,但  $(A \cap B) \cup C = (A \cup C) \cap (B \cup C) = A \cap (B \cup C)$
---
#### 3-25

**证明**：

对任意集合 A,B,C 有
- a)  $(A-B)-C=A-(B \cup C)$ ;
- b) (A-B)-C=(A-C)-B:
c) (A-B)-C=(A-C)-(B-C)
[3-2,(5)]
a) 对任意
$$x \in (A-B)-C \Leftrightarrow x \in (A-B) \land x \notin C$$
$\Leftrightarrow x \in A \land x \notin B \land x \notin C$
$\Leftrightarrow x \in A \land x \notin (B \cup C)$
$\Leftrightarrow x \in A - (B \cup C)$
所以
$$(A-B)-C=A-(B \cup C)$$
b)
$$(A-B)-C = (A-B) \cap \sim C = (A \cap \sim B) \cap \sim C$$
=  $(A \cap \sim C) \cap \sim B = (A-C) \cap \sim B$
=  $(A-C)-B$
c)
$$(A-B)-C = (A \cap \sim C) \cap \sim B = A \cap \sim (C \cup B)$$
$= A - (C \cup B) = A - ((C \cup B) \cap (C \cup \sim C))$
$= A - (C \cup (B \cap \sim C)) = A - (C \cup (B - C))$
$= (A-C) - (B-C)$
---
#### 3-26

> 确定以下各式:
> - a)  $\emptyset \cap \{\emptyset\}$ ; b)  $\{\emptyset\} \cap \{\emptyset\}$ ; c)  $\{\emptyset, \{\emptyset\}\} \emptyset$ ;
> - d)  $\{\emptyset, \{\emptyset\}\} \{\emptyset\}; e\}$   $\{\emptyset, \{\emptyset\}\} \{\{\emptyset\}\}\}$
> [3-2,(6)]

**解**：

a)  $\emptyset$ ; b)  $\{\emptyset\}$ ; c)  $\{\emptyset,\{\emptyset\}\}$ ; d)  $\{\{\emptyset\}\}$ ; e)  $\{\emptyset\}$ .

---
#### 3-27

> 假定 A 和 B 是 E 的子集,证明以下各式中每个关系 式彼此等价:
> - a)  $A \subseteq B, \sim A \supseteq \sim B, A \cup B = B, A \cap B = A$ :
> - b)  $A \cap B = \emptyset, A \subseteq \sim B, B \subseteq \sim A$ :
> - c)  $A \cup B = E, \sim A \subseteq B, \sim B \subseteq A;$
> - d)  $A=B,A \oplus B=\emptyset$ .
> [3-2,(7)]

**证明**：

a) 因为

$$A \subseteq B \Leftrightarrow (\forall x)(x \in A \rightarrow x \in B)$$

仴  $(x \in A \rightarrow x \in B) \Leftrightarrow (x \notin B \rightarrow x \notin A)$

$\Leftrightarrow (x \in \sim B \rightarrow x \in \sim A)$

$A \subseteq B \Leftrightarrow (\forall x)(x \in A \rightarrow x \in B)$

$$\Leftrightarrow (\forall x)(x \in \sim B \rightarrow x \in \sim A)$$
$$\Leftrightarrow \sim B \subseteq \sim A$$

由定理 3-2.3 可得

$A \subseteq B \Leftrightarrow A \cup B = B$

恒  $(A \cup B = B) \Rightarrow (A \cap (A \cup B) = A \cap B) \Leftrightarrow A \cap B = A$  $(A \cap B = A) \Rightarrow ((A \cap B) \cup B = A \cup B) \Rightarrow A \cup B = B$

故

$A \cup B = B \Leftrightarrow A \cap B = A$

b)  $(A \cap B = \emptyset) \Leftrightarrow (\forall x)(x \in A \rightarrow x \notin B)$  $\Leftrightarrow (\forall x)(x \in A \rightarrow x \in \sim B) \Leftrightarrow (A \subseteq \sim B)$  $\Leftrightarrow (B \subseteq \sim A)$

c)  $(A \cup B = E) \Leftrightarrow (\forall x) (x \notin A \rightarrow x \in B)$   $\Leftrightarrow (\forall x) (x \in \sim A \rightarrow x \in B) \Leftrightarrow \sim A \subseteq B$   $(A \cup B = E) \Leftrightarrow (\forall x) (x \notin B \rightarrow x \in A)$  $\Leftrightarrow (\forall x) (x \in \sim B \rightarrow x \in A) \Leftrightarrow \sim B \subseteq A$

d) 若A=B,有

$A \oplus B = (A \cap \sim B) \cup (B \cap \sim A)$  $= (A \cap \sim A) \cup (B \cap \sim B) = \emptyset \cup \emptyset = \emptyset$

反之,若 $A \oplus B = \emptyset$ ,有

$A \oplus A = \emptyset$

所以  $A \oplus B = A \oplus A$ ,可推得 A = B(见习题 3-28c))。

---
#### 3-28 a) 已知  $A \cup B = A \cup C$ , 是否必须 B = C?

b) 已知  $A \cap B = A \cap C$ , 是否必须 B = C?
c) 已知  $A \oplus B = A \oplus C$ ,是否必须 B = C?

[3-2.(8)]

a) 不一定。例如  $A = \{a\}$ ,  $B = \{a,c\}$ ,  $C = \{c\}$ ,则有  $A \cup B = A \cup C$ ,但  $B \neq C$ 。

b) 不一定。例如  $A=\{a\}$ ,  $B=\{a,b\}$ ,  $C=\{a,c\}$ , 则有  $A\cap B=A\cap C$ , 但  $B\neq C$ 。
c) B=C。因为若  $A \oplus B=A \oplus C$ ,对任意  $x \in B$ ,
(1) 若

$x \in A \Rightarrow x \in A \cap B \Rightarrow x \notin A \oplus B \Leftrightarrow x \notin A \oplus C$

由  $x \in A \land x \notin A \oplus C \Rightarrow x \in A \cap C \Rightarrow x \in C$ ,所以  $B \subseteq C$ 。

(2)

$x \notin A \Rightarrow x \notin A \cap B$

因为

$x \in B \Rightarrow x \in A \cup B$

由

$x \notin A \cap B \land x \in A \cup B \Rightarrow x \in A \oplus B \Rightarrow x \in A \oplus C$

仴

$x \notin A \land x \in A \oplus C \Rightarrow x \in C$

即  $B\subseteq C$ 。

用同样的方法,可证  $C \subseteq B$ 。

因此  $A \oplus B = A \oplus C$  时,必有 B = C。

---
#### 3-29

> 设 A,B,C 是集合,在什么条件下,下列命题是真的?
> - a)  $(A-B) \cup (A-C) = A;$
> - b)  $(A-B) \cup (A-C) = \emptyset$ ;
> - c)  $(A-B) \cap (A-C) = \emptyset$ ;
> d)  $(A-B) \oplus (A-C) = \emptyset$
> [3-2.(9)]

**解**：

a) 因为

$$(A-B) \cup (A-C) = (A \cap \sim B) \cup (A \cap \sim C)$$
$$= A \cap \sim (B \cap C) = A - (B \cap C)$$

故当 $A \cap (B \cap C) = \emptyset$ 时, $A - (B \cap C) = A$ 成立。

b) 要使(A-B)  $\bigcup (A-C)=\emptyset$ ,则需使

$(A \cap \sim B) \cup (A \cap \sim C) = \emptyset$

即要使

$A-(B\cap C)=\emptyset$

故当  $A \subseteq B \cap C$  时,

$$(A-B) \cup (A-C) = \emptyset$$

c)
$$(A-B) \cap (A-C) = (A \cap \sim B) \cap (A \cap \sim C)$$

= $A \cap \sim (B \cup C)$
= $A - (B \cup C)$

所以当  $A\subseteq B\cup C$  时,  $A-(B\cup C)=\emptyset$ 成立。即  $A\subseteq B\cup C$  时,

$$(A-B) \cap (A-C) = \emptyset$$

d) 因为  $A \oplus A = \emptyset$ ,故当 A - B = A - C 时,  $(A - B) \oplus (A - C) = \emptyset$

---
#### 3-30

> 借助于文氏图考察以下命题的正确性:
> - a) 若 A, B 和 C 是 E 的子集, 使得  $A \cap B \subseteq \sim C$ , 且  $A \cup C \subseteq B$ , 则  $A \cap C = \emptyset$ 。
> - b) 若 A, B 和 C 是 E 的子集, 使得  $A \subseteq \sim (B \cup C)$  且  $B \subseteq \sim (A \cup C)$ , 则  $B = \emptyset$ 。
> [!tip] 3-2.(10)
> 

**解**：

文氏图如图 3-3(a)和(b)所示。由图可知命题 a),b)是 正确的。

![](_page_18_Picture_4.jpeg)

![](_page_18_Picture_5.jpeg)

图 3-3

---
#### 3-31 证明

a)  $A \cap (B \oplus C) = (A \cap B) \oplus (A \cap C)$ ;
b)  $A \cup (B \oplus C) = (A \cup B) \oplus (A \cup C)$ 不一定成立。【3-2.(11)】

a)  $(A \cap B) \oplus (A \cap C)$
$= ((A \cap B) \cap \sim (A \cap C)) \cup ((A \cap C) \cap \sim (A \cap B))$
$= ((A \cap B) \cap (\sim A \cup \sim C)) \cup ((A \cap C) \cap (\sim A \cup \sim B))$
$= (A \cap B \cap \sim A) \cup (A \cap B \cap \sim C) \cup (A \cap C \cap \sim A)$  $\cup (A \cap C \cap \sim B)$
$=(A \cap B \cap \sim C) \cup (A \cap C \cap \sim B)$
$=A \cap ((B \cap \sim C) \cup (C \cap \sim B))$
$=A \cap ((B-C) \cup (C-B)) = A \cap (B \oplus C)$
b)  $\c A = \{2,3\}, B = \{1,4,7\}, C = \{3,5\}, \c B \oplus C = \{1,3,4,5,7\}$

所以
$$A \cup (B \oplus C) = \{1,2,3,4,5,7\}$$
但  $A \cup B = \{1,2,3,4,7\}$  私  $C = \{2,3,5\}$  故  $A \cup C = \{2,3,5\}$  故  $A \cup (B \oplus C) = (A \cup B) \oplus (A \cup C)$

不一定成立。

---
#### 3-32 给定正整数集合 $I_+$ 的下列子集:

$$A = \{n \mid n < 12\},$$
$B = \{n \mid n \le 8\},$   $C = \{n \mid n = 2k, k \in I_{+}\},$   $D = \{n \mid n = 3k, k \in I_{+}\},$   $F = \{n \mid n = 2k - 1, k \in I_{+}\},$

试用 A,B,C,D 和 F,表达下列集合;

a)  $\{2,4,6,8\}$ ;
b) {3,6,9};
c) {10};
d)  $\{n | n$  是偶数, $n > 10\};$
e)  $\{n \mid n$  是偶数且  $n \le 10$ ,或 n 是奇数,且  $n \ge 9\}$ 。

a)
$$\{2,4,6,8\} = B - F$$

b)  $\{3,6,9\} = A \cap D$
c)  $\{10\} = (A-B)-F$
d)  $\{n \mid n$  是偶数, $n > 10\} = C A$
e)  $\{n \mid n$  是偶数且  $n \le 10$ ,或 n 是奇数且  $n \ge 9\}$ =  $(A \cap C) \cup (F - B)$

---
#### 3-33 设所有整数集合 I,已知 I 的子集:

$$A = \{x \mid x = 3y, y \in I, y \geqslant 4\}$$

$$B = \{x \mid x = 2y, y \in I\}$$

$$C = \{x \mid x \in I, |x| \leq 10\}$$

# 试用A,B,C和集合的运算,表达下列集合:

a) 所有奇整数的集合;
b)  $\{-10, -8, -6, -4, -2, 0, 2, 4, 6, 8, 10\}$ :
c)  $\{x | x = 6y, y \in I, y \ge 2\};$

d)  $\{-9, -7, -5, -3, -1, 1, 3, 5, 7, 9\}$ :

e)  $\{x | x = 2y + 1, y \in I, y \ge 5\}$

$\bigcup \{x | x = 2y - 1, y \in I, y \le -5\}$

a)  $\sim B$ ; b)  $B \cap C$ ;

c)  $A \cap B$ ;

d)  $\sim B \cap C$ ; e)  $\sim B \cap \sim C$ (或 $\sim B - C$ ).

---
#### 3-35

> 3-35** 证明 对任意集合 A,  $\bigcup \mathcal{P}(A) = A$ .

**证明**：

设任意  $x \in \bigcup \mathcal{P}(A)$ ,则存在  $S \in \mathcal{P}(A)$ ,使得  $x \in S$ 。 又因  $S \subseteq A$ ,故  $x \in A$ ,于是以  $\mathcal{P}(A) \subseteq A$ 。反之,设任意  $x \in A$ , $x \in A$  $\{x\}\subseteq A$ ,故 $\{x\}\in\mathcal{P}(A)$ 。因此  $x\in\bigcup\mathcal{P}(A)$ ,得到

$A \subseteq \bigcup \mathcal{P}(A)$

于是

$\bigcup \mathcal{P}(A) = A$

---
#### 3-36

**证明**：

若 S∈B,则 $\mathcal{P}(S)$ ∈ $\mathcal{P}\mathcal{P}(\bigcup B)$ 。
对所有  $X \in \mathcal{P}(S)$ ,有  $X \subseteq S$ ,对任意  $x \in X$ ,可得  $x \in X$ S。因为  $S \in B$ ,有  $x \in \bigcup B$ ,即  $X \subseteq \bigcup B$ ,故  $X \in \mathcal{P}(\bigcup B)$ 。所以  $\mathcal{P}(S) \subseteq \mathcal{P}(\bigcup B)$ ,即
$\mathcal{P}(S) \in \mathcal{PP}(\bigcup B)$
---
#### 3-37

**证明**：

$\bigcup (A \cup B) = (\bigcup A) \bigcup (\bigcup B)$ 。
对任意  $x \in \bigcup (A \cup B)$ ,则必存在  $a \in A \cup B$ ,且  $x \in a$ , 故  $a \in A$  或  $a \in B$ ,且  $x \in a$ ,所以  $x \in \bigcup A$  或  $x \in \bigcup B$ ,即
$x \in (\bigcup A) \cup (\bigcup B)$
于是
$\bigcup (A \bigcup B) \subseteq (\bigcup A) \bigcup (\bigcup B)$
反之,设任意
$x \in (UA)U(UB)$
$\Rightarrow x \in \bigcup A$  或  $x \in \bigcup B$
$\Rightarrow (\exists a \in A, x \in a) \not \equiv (\exists b \in B, x \in b)$
$\Rightarrow (\exists a \in A \cup B, x \in a) \not \equiv (\exists b \in A \cup B, x \in b)$
$\Rightarrow x \in \bigcup (A \cup B)$
$(\cap A) \cup (\cup B) \subseteq \cup (A \cup B)$ 所以
$\bigcup (A \bigcup B) = (\bigcup A) \bigcup (\bigcup B)$ 于是
---
#### 3-38

**证明**：

若 B 是非空集,则
$A \cup (\cap B) = \bigcap \{A \cup X \mid X \in B\}$
对任意  $x \in A \cup (\cap B)$ , 若  $x \in A$ , 则  $x \in A \cup X$ (对  $\forall X \in A \cup X$ ) B),所以 $x \in \bigcap \{A \cup X \mid X \in B\}$ 。
若 x ∉ A,则 x ∈  $\cap B$ ,所以对所有 X ∈ B,x ∈ X,故有对所有  $X \in B, x \in A \cup X,$ 即  $x \in \bigcap \{A \cup X \mid X \in B\}$ ,所以
$A \cup (\cap B) \subseteq \cap \{A \cup X \mid X \in B\}$
$\forall x \in \bigcap \{A \cup X \mid X \in B\} \Rightarrow x \in A \cup X (\forall X \in B)$
若  $x \in A$ ,有  $x \in A \cap \bigcup B$
若  $x \notin A \Rightarrow x \in X(\forall X \in B)$
则  $x \in \bigcap B \Rightarrow x \in A \cup \bigcap B$
故  $\bigcap \{A \cup X \mid X \in B\} \subseteq A \cup \bigcap B$
于是  $A \cup (\cap B) = \bigcap \{A \cup X \mid X \in B\}$
---
#### 3-39

**证明**：

若 A 是非空集,则
$\mathcal{P}(\cap A) = \bigcap \{\mathcal{P}(X) | X \in A\}$
对所有  $x \in \mathcal{P}(\cap A)$ ,则  $x \subseteq \cap A$ ,即对任意  $a \in x$  必有  $a \in \bigcap A$ 。所有  $X \in A$ ,有  $a \in X$ 。于是  $x \subseteq X$ ,得到  $x \in \mathcal{P}(X)$ ,对 所有  $X \in A$ ,故  $x \in \bigcap \{ \mathscr{P}(X) | X \in A \}$ ,于是证得
$\mathcal{P}(\cap A) \subseteq \cap \{\mathcal{P}(X) | X \in A\}$
反之,设任意  $x \in \bigcap \{ \mathcal{P}(X) \mid X \in A \}$ ,则对所有  $X \in A, x \in A$  $\mathcal{P}(X)$ 即  $x\subseteq X$ 。 所以所有  $X\in A, a\in x$ ,则对所有  $X\in A, a\in X$ , 因此  $a \in \bigcap A$ ,有
$x \subseteq \bigcap A \Rightarrow x \in \mathcal{P}(\bigcap A)$
$\bigcap \{ \mathscr{P}(X) | X \in A \} \subseteq \mathscr{P}(\bigcap A)$ 所以
$\bigcap \{ \mathscr{P}(X) \mid X \in A \} = \mathscr{P}(\bigcap A)$ 于是
---
#### 3-40

**证明**：

$\cup$  { $\mathcal{P}(X) \mid X \in A$ }⊆ $\mathcal{P}(\cup A)$ ,在什么情况下, 等式成立。
对任意  $x \in \bigcup \{ \mathcal{P}(X) | X \in A \}$ , 必存在  $\mathcal{P}(X_i)$ ,  $X_i \in A$ A, 使得  $x \in \mathcal{P}(X_i)$  成立, 故有  $x \subseteq X_i$ 。为此, 对任意  $a \in x$ , 必有  $a \in X_i$ 。因  $X_i \in A$ ,故  $a \in \bigcup A$ ,于是  $x \subseteq \bigcup A$ ,即  $x \in \mathcal{P}(\bigcup A)$ ,有
$\bigcup \{ \mathcal{P}(X) | X \in A \} \subseteq \mathcal{P}(\bigcup A)$
当集合 A 中只有一个元素时上面式子中的等式成立。
---
#### 3-41

> 给定集合 A 和 B 的一个例子, 使得  $A \cap B \neq \emptyset$ , 目  $(\cap A) \cap (\cap B) \neq \cap (A \cap B)$

**解**：

设
$$A = \{\{1,2,3\},\{2,3,4\},\{2,3,4,6\}\}\}$$

$B = \{\{2,3,4\},\{2,3,4,6\},\{2,3,4,8\}\}\}$
则  $\bigcap A = \{2,3\}, \bigcap B = \{2,3,4\}$
$A \bigcap B = \{\{2,3,4\},\{2,3,4,6\}\}\}$
$(\bigcap A) \bigcap (\bigcap B) = \{2,3\}, \bigcap (A \bigcap B) = \{2,3,4\}$
所以  $(\bigcap A) \bigcap (\bigcap B) \neq \bigcap (A \cap B)$

所以

理的推广。

---
#### 3-42

> 设 C 为全集 E 的非空子集簇,证明以下德· 摩根定
> a)
> $$\overline{\bigcup_{S \in C}} S = \bigcap_{S \in C} \overline{S}$$
> ; b)  $\overline{\bigcap_{S \in C}} S = \bigcup_{S \in C} \overline{S}$  ( $\overline{S} = \sim S$ )。

**证明**：

a)  $\bigcap_{S \in C} \overline{S} = \{x \mid (\forall S)(S \in C \rightarrow x \in \overline{S})\}$
$= \{x \mid (\forall S)(\neg (S \in C) \lor (x \in \overline{S}))\}$
$= \{x \mid \neg (\neg S)((S \in C) \land (x \in S))\}$
$= \{x \mid (\neg S)(S \in C \land x \in S)\} = \overline{\bigcup_{S \in C}} S$

b)
$$\bigcup_{S \in C} \overline{S} = \{x \mid (\neg S)(S \in C \land x \in \overline{S})\}$$
$$= \{x \mid (\neg S)(\neg (S \notin C \lor x \in S))\}$$
$$= \{x \mid \neg \forall S(S \in C \rightarrow x \in S)\}$$
$$= \{\overline{x} \mid \forall S(S \in C \rightarrow x \in S)\} = \overline{\bigcap_{S \in S}}$$

---
#### 3-43

> 设对自然数定义为:
> $0 = \emptyset, 1 = 0 \cup \{0\}, 2 = 1 \cup \{1\}, 3 = 2 \cup \{2\}, 4 = 3 \cup \{3\}, \dots$ 设  $X = \{\{2,5\}, 4, \{4\}\}, 求 \cap (\bigcup X - 4)$ 。
> 由题设定义,
> $$1=\emptyset \cup \{\emptyset\} = \{\emptyset\} = \{0\}$$
> $$2=\{0\} \cup \{1\} = \{0,1\}$$
> $$3=\{0,1\} \cup \{\{0,1\}\} = \{0,1,2\}$$
> $$4=\{0,1,2\} \cup \{3\} = \{0,1,2,3\}$$
> 所以
> $$X=\{\{2,5\},\{0,1,2,3\},\{4\}\}$$
> $$\cup X=\{0,1,2,3,4,5\}$$
> $$\cup X-4=\{0,1,2,3,4,5\}-\{0,1,2,3\} = \{4,5\}$$
> $$=\{(0,1,2,3\},\{0,1,2,3,4\}\}$$
> 因此
> $$\cap (\cup X-4) = \{0,1,2,3\} = 4$$
> $$3-44$$
> $A_0 = \{a \mid a < 1\}, A_i = \{a \mid a \le 1 - \frac{1}{i}\} \quad (i = 1, 2, \dots)$
> $$\bigcup_{i=1}^{\infty} A_i = A_0$$

**证明**：

(1) 先证  $\bigcup_{i=1}^{\infty} A_i \subseteq A_0$ 。

设  $x \in \bigcup_{i=1}^{\infty} A_i$ ,则必存在某个自然数 k,使  $x \in A_k$  即  $x \le 1 - \frac{1}{k}$ ,则  $x \le 1$ ,故  $x \in A_0$ 。

(2) 再证  $\bigcup_{i=1}^{\infty} A_i \supseteq A_0$ 。

设  $x \in A_0$ ,即 x < 1,对 x 必有 $-\varepsilon > 0$ ,使  $x = 1 - \varepsilon$ .

$$\diamondsuit k = \left[\frac{1}{\varepsilon}\right] + 1$$
,则  $x \le 1 - \frac{1}{k}$ ,即  $x \in A_k$ ,所以  $x \in \bigcup_{i=1}^{\infty} A_i$ ,故有

$$A_0 \subseteq \bigcup_{i=1}^{\infty} A_i$$

由以上情况,即得到

$$\bigcup_{i=1}^{\infty} A_i = A_0$$

---
#### 3-48

> 设 $B_i$ 是实数集,它被定义为.
> $$B_0 = \{b \mid b \leq 1\}, B_i = \{b \mid b < 1 + \frac{1}{i}\} \quad (i = 1, 2, \cdots)$$

**证明**：

$$\bigcap_{i=1}^{\infty} B_i = B_0$$

(1) 先证  $B_0 \subseteq \bigcap_{i=1}^{\infty} B_i$ .

设  $x \in B_0$ ,即  $x \le 1$ ,对任一个 i,均有  $x < 1 + \frac{1}{i}$ ,设对任何 i,  $x \in B_i$ ,所以  $x \in \bigcap_{i=1}^{\infty} B_i$  。

(2) 再证  $\bigcap_{i=1}^{\infty} B_i \subseteq B_0$ .

设  $x \in \bigcap_{i=1}^{\infty} B_i$ ,则  $x \in B_i$   $(i=1, 2, \cdots)$ 。对任何 i,  $x < 1 + \frac{1}{i}$  都成立,则必有  $x \le 1$ 。若不然,即 x > 1,则必有某个  $\epsilon > 0$ ,使  $x = 1 + \epsilon$ 。

$$\diamondsuit$$
$k = \left[\frac{1}{\varepsilon}\right] + 1$ ,则  $x \ge 1 + \frac{1}{k}$ ,故  $x \notin B_k$ ,但  $x \in B_i$   $(i = 1, i = 1)$

$2,\cdots$ )矛盾,因此  $x \leq 1$  即  $x \in B_0$ ,所以  $\bigcap_{i=1}^{\infty} B_i \subseteq B_0$ 。由上述证明可得

$$\bigcap_{i=1}^{\infty} B_i = B_0$$

---
#### 3-49

> 设某校足球队有球衣 38 件,篮球队有球衣 15 件,棒球队有球衣 20 件,三队队员的总数为 58 人,其中有三人同时参加三队,试求同时参加二队的队员共有几人? 【3-3.(1)】

**解**：

设 $A_1$  表示参加足球队的队员集合;

A<sub>2</sub> 表示参加篮球队的队员集合;

A<sub>3</sub> 表示参加棒球队的队员集合。

根据题意有

$$|A_1| = 38, |A_2| = 15, |A_3| = 20$$

$$|A_1 \cup A_2 \cup A_3| = 58, |A_1 \cap A_2 \cap A_3| = 3$$

由容斥原理

$$|A_1 \cup A_2 \cup A_3| = |A_1| + |A_2| + |A_3| - |A_1 \cap A_2|$$

$|A_1 \cap A_3| - |A_2 \cap A_3|$
+  $|A_1 \cap A_2 \cap A_3|$

$58=38+15+16-|A_1 \cap A_2|-|A_1 \cap A_3|-|A_2 \cap A_3|+3$  所以,  $|A_1 \cap A_2|+|A_1 \cap A_3|+|A_2 \cap A_3|=18$  参加二个队的队员共 18 人。

---
#### 3-50

> 设由某项调查,发现学生阅读杂志的情况如下:
> 百分之六十阅读甲类杂志;
> 百分之五十阅读乙类杂志;
> 百分之五十阅读丙类杂志;
> 百分之三十阅读甲类杂志与乙类杂志;
> 百分之三十阅读乙类杂志与丙类杂志;
> 百分之三十阅读甲类杂志与丙类杂志;
> 百分之十阅读三类杂志。
> 问 a) 试求确实阅读两类杂志的学生的百分比。
> b) 试求不读任何杂志的学生的百分比。
> [3-3.(2)]

**解**：

设 $A_1$  表示阅读甲类杂志学生的集合;

A。表示阅读乙类杂志学生的集合;

A<sub>3</sub> 表示阅读丙类杂志学生的集合。

则按题意有:
$$|A_1|=60\%$$
,  $|A_2|=50\%$ ,  $|A_3|=50\%$
$|A_1 \cap A_2|=30\%$ ,  $|A_2 \cap A_3|=30\%$
$|A_1 \cap A_3|=30\%$ ,  $|A_1 \cap A_2 \cap A_3|=10\%$

a)
$$|A_1 \cap A_2| + |A_2 \cap A_3| + |A_1 \cap A_3| - 3|A_1 \cap A_2 \cap A_3|$$

= 30\% + 30\% + 30\% - 3 \cdot 10\% = 60\%

b)
$$|A_1 \cup A_2 \cup A_3| = |A_1| + |A_2| + |A_3| - |A_1 \cap A_2|$$

$-|A_1 \cap A_3| - |A_2 \cap A_3|$
$+|A_1 \cap A_2 \cap A_3|$
$=60\% + 50\% + 50\% - 30\% - 30\%$
$-30\% + 10\% = 80\%$

所以  $|\sim A_1 \cap \sim A_2 \cap \sim A_3 |=1-|A_1 \cup A_2 \cup A_3|=20\%$

---
#### 3-51

> 75 个儿童到公园游乐场,他们在那里可以骑旋转木
> ![](_page_22_Picture_8.jpeg)
> 图 3-4
> 马,坐滑行铁道,乘宇宙飞船,已知 其中 20 人这三种东西都乘坐过, 其中 55 人至少乘坐过其中两种。 若每样乘坐一次的费用是 0.50 元,公园游乐场总共收入 70 元,试 确定有多少儿童没有乘坐过其中 任何一种。

**解**：

设

$A_1 = \{$  骑过旋转木马的儿童 $\}$ ;  $A_2 = \{$  坐过滑行铁道的儿童 $\}$ ;  $A_3 = \{$  乘过宇宙飞船的儿童 $\}$ 。

集合  $A_1 \cup A_2 \cup A_3$  的图示如图 3-4 所示。

因为
$$|A_1| = |B| + |H| + |K| + |J|$$

$|A_2| = |C| + |I| + |K| + |J|$

$$|A_3| = |D| + |H| + |I| + |J|$$

去公园游乐场儿童总数为 N=75。

$$|A_{1} \cap A_{2} \cap A_{3}| = |J| = 20$$

$$|K| + |H| + |I| + |J| = 55$$

$$0.5 \times (|A_{1}| + |A_{2}| + |A_{3}|) = 70$$

$$|C| + |D| + 2 \times (|K| + |H| + |I|) + 3 \times |J|$$

即
$$|B|+|C|+|D|+2\times(|K|+|H|+|I|)+3\times|J|$$

=70/0.5

得到

$$|B| + |C| + |D| = 10$$

$$N(0) = N - |A_1 \bigcup A_2 \bigcup A_3| = 75 - (10 + 55) = 10$$

所以没有乘过其中任何一种的儿童共10人。

---
#### 3-52

> a)在一个班级的 50 个学生中,有 26 人在第一次考试中得到 A,21 人在第二次考试中得到 A,假如有 17 人两次考试都没有得到 A,问有多少学生两次考试中都得到 A。
> - b) 若全班有50个学生,在这些学生中,如果第一次考试中得到A的人数,等于第二次考试中得到A的人数,如果仅在一次考试中得到A的学生总数是40,并且如果有4个学生两次考试都没有得到A,问有多少学生仅在第一次考试中取得A? 问有多少学生仅在第二次考试中取得A? 又问有多少学生在两次考试中都得到A。

**解**：

a) 设第一次考试得到 A 的人为具有性质  $P_1$ ,其集合为  $A_1$ ,第二次考试得到 A 的人为具有性质  $P_2$ ,其集合为  $A_2$ ,则按题 意有:

$$|A_1 \bigcup A_2| = 50 - 17 = 33$$

由容斥原理

$|A_1 \cap A_2| = |A_1| + |A_2| - |A_1 \cup A_2| = 26 + 21 - 33 = 14$ 故两次考试都得到 A 的人数为 14 人。

b)
$$|A_1| = |A_2|$$

因为
$$|A_1 \cup A_2| = |A_1 \cap \sim A_2| + |A_2 \cap \sim A_1| + |A_1 \cap A_2|$$

但  $|A_1 \cup A_2| = 50 - 4 = 46$
$|A_1 \cap \sim A_2| + |A_2 \cap \sim A_1| = 40$

故

$$|A_1 \cap A_2| = 46 - 40 = 6$$

即在两次考试中均有 6 人得到 A。

$|A_1 \bigcup A_2| = |A_1| + |A_2| - |A_1 \cap A_2|$

得到

$$46=2|A_1|-6$$

即

$$|A_1| = |A_2| = 26$$

故在第一次(或第二次)考试中有 26 人得到 A,而仅在一次考试中得到 A 的人数为 26-6=20(人)。

---
#### 3-53

> 对 200 名大学一年级的学生进行调查的结果是:其中 67 人学数学,47 人学物理,95 人学生物,26 人既学数学又学物理,27 人既学物理又学生物,50 人这三门课都不学。
> - a) 求出对三门课都学的学生人数:
> - b) 在文氏图中以正确的学生人数填入其中 8 个区域。
> [3-3.(5)]

**解**：

a) 设学生学习数学为具有性质  $P_1$ ,其集合为  $A_1$ ;学生学物理为具有性质  $P_2$ ,其集合为  $A_2$ ;学生学生物为具有性质  $P_3$ , 其集合为  $A_3$ 。

![](_page_23_Figure_14.jpeg)

图 3-5

由题设  $|A_1|=67$ ,  $|A_2|=47$ ,  $|A_3|=95$   $|A_1 \cap A_3|=26$ ,  $|A_1 \cap A_2|=28$ ,  $|A_1 \cap A_2|=27$   $|\sim A_1 \cap \sim A_2 \cap \sim A_3|=50$ , N=200  $|\sim A_1 \cap \sim A_2 \cap \sim A_3|=N-|A_1|-|A_2|-|A_3|+|A_1 \cap A_2|$   $+|A_1 \cap A_3|+|A_2 \cap A_3|$   $-|A_1 \cap A_2 \cap A_3|$   $50=200-67-47-95+28+26+27-|A_1 \cap A_2 \cap A_3|$ 所以  $|A_1 \cap A_2 \cap A_3|=22(\Lambda)$

b) 见图 3-5。

---
#### 3-54 试求在1到10000之间不能被4,5或6整除的整数的个数。

设 $A_i$ 是1到10000之间能为i除尽的整数的集合,则有:

$$|A_{4}| = \left[\frac{10000}{4}\right] = 2500$$

$$|A_{5}| = \left[\frac{10000}{5}\right] = 2000$$

$$|A_{6}| = \left[\frac{10000}{6}\right] = 1666$$

$$|A_{4} \cap A_{5}| = \left[\frac{10000}{20}\right] = 500$$

$$|A_{4} \cap A_{6}| = \left[\frac{10000}{12}\right] = 833$$

$$|A_{5} \cap A_{6}| = \left[\frac{10000}{30}\right] = 333$$

$$|A_{4} \cap A_{5} \cap A_{6}| = \left[\frac{10000}{60}\right] = 166$$

根据容斥原理

$$N(0) = N - |A_4| - |A_5| - |A_6| + |A_4 \cap A_5|$$

+  $|A_4 \cap A_6| + |A_5 \cap A_6| - |A_4 \cap A_5 \cap A_6|$
所以  $N(0) = 10000 - (2500 + 2000 + 1666)$
+  $(500 + 833 + 333) - 166 = 5334$

这里  $N(0) = |\overline{A}_4 \cap \overline{A}_5 \cap \overline{A}_6|$ 。所以满足题意的整数个数为: 5334。

$$3-55$$
设有集合 $\{1,2,3,\dots,n\}$ ,其无重复的一个排列  $(a_1,a_2,\dots,a_n)$

满足条件  $a_i \neq i (i=1,2,\dots,n)$ ,则称该排列为一个错列。求证集 合 $\{1,2,3,\dots,n\}$ 的错列个数  $D_n$  为

$$D_n = \left(1 - \frac{1}{1!} + \frac{1}{2!} - \frac{1}{3!} + \dots + (-1)^n \frac{1}{n!}\right) (n!)$$

令 S 是 $\{1,2,\dots,n\}$ 的所有无重复排列的集合,则 |S|=n!

设有一个排列如果 j 在第 j 个位置上,称该排列具有性质  $P_j$ ,设  $A_j$  是具有性质  $P_j$  的排列的集合,故  $A_j \subseteq S$ 。对于 $\{1,2,\cdots,n\}$ 中的任意一个错乱排列,当且仅当这个排列为不具有性质  $P_1$ , $P_2$ ,…, $P_n$  中任意一个性质。所以全部错乱排列组成的集合应该 是

$$\overline{A}_1 \cap \overline{A}_2 \cap \cdots \cap \overline{A}_n$$

在集合  $A_1$  中,所有排列应具有形式  $1, i_2, i_3, \dots, i_n$ ,其中  $: i_2, i_3, \dots, i_n$  是集合  $\{2, 3, \dots, n\}$  的一个无重复排列。因而有  $|A_1| = (n-1)!$  。同理当  $1 \le j \le n$  时,我们都有

$$|A_j| = (n-1)!$$

在集合  $A_1 \cap A_2$  中的排列应具有形式  $1, 2, i_3, i_4, \dots, i_n$ , 其中  $i_3$ ,  $i_4, \dots, i_n$  是 $\{3, 4, \dots, n\}$ 的一个无重复的排列。所以有

$$|A_1 \cap A_2| = (n-2)!$$

同理  $1 \leq i < j \leq n$  时有:

$$|A_i \cap A_j| = (n-2)!$$

一般地,对
$$1 \leqslant i_1 < i_2 < \cdots < i_k \leqslant n$$
,有
$$|A_{i_k} \cap A_{i_k} \cap \cdots \cap A_{i_k}| = (n-k)!$$

集合 $\{1,2,3,\cdots,n\}$ 的 k -组合数是 $\binom{n}{k}$ ,故由容斥原理

$$|\overline{A}_{1} \cap \overline{A}_{2} \cap \cdots \cap \overline{A}_{n}| = |S| - \sum |A_{i}| + \sum |A_{i} \cap A_{j}|$$
$$- \sum |A_{i} \cap A_{j} \cap A_{k}| + \cdots$$
$$+ (-1)^{m} |A_{1} \cap A_{2} \cap \cdots \cap A_{n}|$$

所以

$$D_{n} = n! - \binom{n}{1}(n-1)! + \binom{n}{2}(n-2)!$$

$$+ (-1)^{k} \binom{n}{k}(n-k)! + \cdots (-1)^{n} \binom{n}{n} 0!$$

$$= n! - \frac{n!}{1!} + \frac{n!}{2!} + \cdots + (-1)^{n} \frac{n!}{n!}$$

$$= \left(1 - \frac{1}{1!} + \frac{1}{2!} + \cdots + (-1)^{n} \frac{1}{n!}\right) \cdot n!$$

---
#### 3-56

> 设 $A=\{0,1\},B=\{1,2\},$ 确定下列集合:
> - a)  $A \times \{1\} \times B$ ;
> - b)  $A^2 \times B$ :
> c)
> $$(B \times A)^2$$
> [3-4.(1)]

**解**：

a)
$$A \times \{1\} \times B = \{\langle 0,1,1 \rangle, \langle 0,1,2 \rangle, \langle 1,1,1 \rangle, \langle 1,1,2 \rangle\}$$

b)
$$A^2 \times B = \{\langle 0,0,1 \rangle, \langle 0,1,1 \rangle, \langle 0,0,2 \rangle, \langle 0,1,2 \rangle, \langle 1,0,1 \rangle, \langle 1,0,2 \rangle, \langle 1,1,1 \rangle, \langle 1,1,2 \rangle\}$$

c)
$$(B \times A)^2 = \{ \langle \langle 1,0 \rangle, \langle 1,0 \rangle \rangle, \langle \langle 1,0 \rangle, \langle 1,1 \rangle \rangle, \\ \langle \langle 1,0 \rangle, \langle 2,0 \rangle \rangle, \langle \langle 1,0 \rangle, \langle 2,1 \rangle \rangle, \\ \langle \langle 1,1 \rangle, \langle 1,0 \rangle \rangle, \langle \langle 1,1 \rangle, \langle 1,1 \rangle \rangle, \\ \langle \langle 1,1 \rangle, \langle 2,0 \rangle \rangle, \langle \langle 1,1 \rangle, \langle 2,1 \rangle \rangle, \\ \langle \langle 2,0 \rangle, \langle 1,0 \rangle \rangle, \langle \langle 2,0 \rangle, \langle 1,1 \rangle \rangle, \\ \langle \langle 2,0 \rangle, \langle 2,0 \rangle, \langle \langle 2,0 \rangle, \langle 2,1 \rangle \rangle, \\ \langle \langle 2,1 \rangle, \langle 1,0 \rangle \rangle, \langle \langle 2,1 \rangle, \langle 1,1 \rangle \rangle,$$

$$\langle\langle 2,1\rangle,\langle 2,0\rangle\rangle,\langle\langle 2,1\rangle,\langle 2,1\rangle\rangle\}$$

---
#### 3-57

> 设 $A=\{a,b\}$ ,请构成集合 $\mathcal{P}(A)\times A$ 。 【3-4.(2)】
> $$\mathscr{P}(A) = \{ \varnothing, \{a\}, \{b\}, \{a,b\} \}$$
> • 143 •
> ```
> A-B=\{e\}, C-D=\{c,f\}, \emptyset
> \mathcal{P}(A) \times A = \{\langle \varnothing, a \rangle, \langle \varnothing, b \rangle, \langle \{a\}, a \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}, b \rangle, \langle \{a\}
> (A-B)\times(C-D)=\{\langle e,c\rangle,\langle e,f\rangle\}
> \langle \{b\},a\rangle, \langle \{b\},b\rangle, \langle \{a,b\},a\rangle, \langle \{a,b\},b\rangle \}
> A \times C = \{\langle a,c \rangle, \langle a,f \rangle, \langle e,c \rangle, \langle e,f \rangle\}
---
#### 3-58

> 设 A,B,C 是任意三个集合,则下式成立:
> 仴
> B \times D = \{\langle a, d \rangle, \langle b, d \rangle\}
> (A \cap B) \times (C \cap D) = (A \times C) \cap (B \times D)
> (A \times C) - (B \times D) = \{\langle a, c \rangle, \langle a, f \rangle, \langle e, c \rangle, \langle e, f \rangle\}

**证明**：

因为
A \cap B \subseteq A, C \cap D \subseteq C
即
(A-B)\times(C-D)\neq(A\times C)-(B\times D)
(A \cap B) \times (C \cap D) \subseteq A \times C
故
c) 不成立。设A = \{a\}, B = \{b\}, C = \{c\}, D = \{d\}, A \cap B = \{c\}, D = \{d\} [OCR损坏,见原书] 同理可证
\{a,b\},C \oplus D = \{c,d\}, \emptyset = \{c,d\}
(A \cap B) \times (C \cap D) \subseteq B \times D
(A \oplus B) \times (C \oplus D) = \{\langle a,c \rangle, \langle a,d \rangle, \langle b,c \rangle, \langle b,d \rangle\}
所以
(A \cap B) \times (C \cap D) \subseteq (A \times C) \cap (B \times D)
A \times C = \{\langle a,c \rangle\}, B \times D = \{\langle b,d \rangle\}
反之,若\langle x, y \rangle \in (A \times C) \cap (B \times D),则
(A \times C) \oplus (B \times D) = \{\langle a,c \rangle, \langle b,d \rangle\}
\langle x, y \rangle \in A \times C \land \langle x, y \rangle \in B \times D
(A \oplus B) \times (C \oplus D) \neq (A \times C) \oplus (B \times D)
即
得到
d) 成立。因为
x \in A \land y \in C \land x \in B \land y \in D \Rightarrow x \in A \cap B \land y \in C \cap D
(A-B)\times C=\{\langle x,y\rangle \mid x\in \langle A-B\rangle \land y\in C\}
\Rightarrow \langle x, y \rangle \in (A \cap B) \times (C \cap D)
所以
(A \times C) \cap (B \times D) \subseteq (A \cap B) \times (C \cap D)
所以
\langle x,y\rangle \in (A-B)\times C \Leftrightarrow x\in (A-B) \land y\in C
综上所述有
\Leftrightarrow (x \in A \land x \notin B) \land y \in C
(A \cap B) \times (C \cap D) = (A \times C) \cap (B \times D)
\Leftrightarrow (x \in A \land y \in C \land x \notin B) \lor (x \in A)

---
#### 3-59

> 下列各式中哪些成立,哪些不成立,为什么?
> \land y \in C \land y \notin C
> a) (A \cup B) \times (C \cup D) = (A \times C) \cup (B \times D);
> \Leftrightarrow (x \in A \land y \in C) \land (x \notin B \lor y \notin C)
> b) (A-B)\times(C-D)=(A\times C)-(B\times D);
> \Leftrightarrow (x \in A \land y \in C) \land \neg (x \in B \land y \in C)
> c) (A \oplus B) \times (C \oplus D) = (A \times C) \oplus (B \times D);
> \Leftrightarrow \langle x,y \rangle \in A \times C \land \langle x,y \rangle \notin B \times C
> d) (A-B)\times C=(A\times C)-(B\times C);
> \Leftrightarrow \langle x,y\rangle \in [(A\times C)-(B\times C)]
> e) (A \oplus B) \times C = (A \times C) \oplus (B \times C).
> [3-4.(3)]
> (A-B)\times C=(A\times C)-(B\times C)

**证明**：

a) 不成立。设 A = \{a\}, B = \{b\}, C = \{c\}, D = \{d\}, f
e) 成立。因为
A \cup B = \{a,b\}, C \cup D = \{c,d\}
(A \oplus B) \times C = \lceil (A - B) \cup (B - A) \rceil \times C
(A \cup B) \times (C \cup D) = \{\langle a, c \rangle, \langle a, d \rangle, \langle b, c \rangle, \langle b, d \rangle\}
= \lceil (A-B) \times C \rceil \cup \lceil (B-A) \times C \rceil
A \times C = \{\langle a,c \rangle\}, B \times D = \{\langle b,d \rangle\}
但
= \lceil (A \times C) - (B \times C) \rceil
故
(A \times C) \cup (B \times D) = \{\langle a, c \rangle, \langle b, d \rangle\}
\bigcup \lceil (B \times C) - (A \times C) \rceil
(A \cup B) \times (C \cup D) \neq (A \times C) \cup (B \times D)
即
=(A\times C)\oplus (B\times C)
b) 不成立。设 A = \{a, e\}, B = \{a, b\}, C = \{c, f\}, D = \{d\},
```

---
#### 3-60

**证明**：

若  $X \times X = Y \times Y$ ,则 X = Y。
[3-4.(4)]
设任意  $x \in X$ ,则 $\langle x, x \rangle \in X \times X$ ,即 $\langle x, x \rangle \in Y \times Y$ , Y, 所以  $X \subseteq Y$ 。
同理可证  $Y \subseteq X$ 。
综上所述,X=Y得证。
---
#### 3-61

**证明**：

若  $X \times Y = X \times Z$ ,且  $X \neq \emptyset$ ,则 Y = Z.
[3-4.(5)]
若 $Y=\emptyset$ ,则 $X\times Y=\emptyset$ ,故 $X\times Z=\emptyset$ ,即 $Z=\emptyset$ ,所以Y=Z。
若  $Y \neq \emptyset$ ,设任意  $y \in Y$ ,因为  $X \neq \emptyset$ ,令  $a \in X$ ,则〈a,y〉∈  $X \times Y$ ,即〈a,y〉∈  $X \times Z$ ,故  $y \in Z$ ,所以  $Y \subseteq Z$ 。同理可证  $Z \subseteq Y$ 。 综上所述,即 Y = Z 得证。
---
#### 3-62

**证明**：

$A \times B = B \times A \Leftrightarrow (A = \emptyset) \lor (B = \emptyset) \lor (A = B)$
必要性 若 $A \times B = B \times A$ ,则
- 1) 当 $A \times B = B \times A = \emptyset$ 时, $(A = \emptyset) \lor (B = \emptyset)$ ;
- 2)当  $A \times B = B \times A \neq \emptyset$ 时,任取 $\langle x, y \rangle \in A \times B$ ,必有 $\langle x, y \rangle \in B \times A$ ,故  $x \in A \land x \in B$ ,且  $y \in B \land y \in A$ 。由 $\langle x, y \rangle$ 的任意性,所以  $A \subseteq B \land B \subseteq A$ ,得到 A = B。
所以
$A \times B = B \times A \Rightarrow (A = \emptyset) \lor (B = \emptyset) \lor (A = B)$
充分性 若 $(A=\emptyset) \lor (B=\emptyset) \lor (A=B)$ ,则
- 1)  $\neg A \neq B \text{ th}, A = \emptyset, B \neq \emptyset, f A \times B = B \times A.$   $A \neq \emptyset, B \neq \emptyset, f A \times B = B \times A.$
- 2) 当A=B时, $A\times B=B\times A$ 。
所以
$(A=\varnothing) \lor (B=\varnothing) \lor (A=B) \Rightarrow A \times B = B \times A$
---
#### 3-63

> 若 $A \cap B \neq \emptyset$ ,求证:
> $(A \cap B) \times (A \cap B) = (A \times A) \cap (B \times B)$  $= (A \times B) \cap (B \times A)$

**证明**：

对任意

$\langle x,y\rangle \in (A \cap B) \times (A \cap B)$

$\Leftrightarrow (x \in A \cap B) \land (y \in A \cap B)$

$\Leftrightarrow x \in A \land x \in B \land y \in A \land y \in B$

$\Leftrightarrow (\langle x,y\rangle \in A \times A) \land (\langle x,y\rangle \in B \times B)$

$\Leftrightarrow \langle x, y \rangle \in (A \times A) \cap (B \times B)$

所以

$(A \cap B) \times (A \cap B) = (A \times A) \cap (B \times B)$

又对任意

$\langle x,y\rangle\in (A\cap B)\times (A\cap B)$

$\Leftrightarrow (x \in A \cap B) \land (y \in A \cap B)$

$\Leftrightarrow x \in A \land x \in B \land y \in A \land y \in B$

$\Leftrightarrow (x \in A \land y \in B) \land (x \in B \land y \in A)$

$\Leftrightarrow (\langle x, y \rangle \in A \times B) \land (\langle x, y \rangle \in B \times A)$

$\Leftrightarrow \langle x, y \rangle \in (A \times B) \cap (B \times A)$

所以

$(A \cap B) \times (A \cap B) = (A \times B) \cap (B \times A)$

---
#### 3-64

> 若 $A \cap B \neq \emptyset$ ,求证:
> - 1)  $(A \cup B) \times (A \cap B)((A \times A) \cup (B \times B);$
> - 2)  $(A \cap B) \times (A \cup B) \subseteq ((A \times A) \cup (B \times B))$ .

**证明**：

1)  $\langle x, y \rangle \in (A \cup B) \times (A \cap B)$

$\Rightarrow (x \in A \cup B) \land (y \in A \cap B)$

$\Rightarrow (x \in A \lor x \in B) \land (y \in A \land y \in B)$

$\Rightarrow (x \in A \land y \in A \land y \in B) \lor (x \in B \land y \in A \land y \in B)$

$\Rightarrow (x \in A \land y \in A) \lor (x \in B \land y \in B)$

$\Rightarrow (\langle x, y \rangle \in A \times A) \lor (\langle x, y \rangle \in B \times B)$

$\Rightarrow \langle x, y \rangle \in (A \times A) \cup (B \times B)$

所以

$(A \cup B) \times (A \cap B) \subseteq (A \times A) \cup (B \times B)$

2)  $\langle x,y\rangle \in (A \cap B) \times (A \cup B)$
$\Rightarrow (x \in A \cap B) \land (y \in A \cup B)$
$\Rightarrow (x \in A \cap B) \land (y \in A \lor y \in B)$
$\Rightarrow ((x \in A \cap B) \land y \in A) \lor ((x \in A \cap B) \land y \in B)$
$\Rightarrow (x \in A \land y \in A) \lor (x \in B \land y \in B)$
$\Rightarrow (\langle x, y \rangle \in A \times A) \land (\langle x, y \rangle \in B \times B)$
$\Rightarrow \langle x, y \rangle \in (A \times A) \cup (B \times B)$

所以

$(A \cap B) \times (A \cup B) \subseteq (A \times A) \cup (B \times B)$

#### 3-65 列出所有从  $X = \{a,b,c\}$ 到  $Y = \{s\}$ 的关系。【3-5.(1)】

$$Z_1 = \{\langle a, s \rangle \},$$
$Z_2 = \{\langle b, s \rangle \}$   $Z_3 = \{\langle c, s \rangle \},$   $Z_4 = \{\langle a, s \rangle, \langle b, s \rangle \}$   $Z_5 = \{\langle a, s \rangle, \langle c, s \rangle \},$   $Z_6 = \{\langle b, s \rangle, \langle c, s \rangle \}$

---
#### 3-66

> 在一个有n个元素的集合上,可以有多少种不同的 关系。

**解**：

因为在 X 中的任何二元关系都是  $X \times Y$  的子集,而  $X \times X = X^2$  中共有  $n^2$  个元素,取 0 个到  $n^2$  个元素,共可组成  $2^{n^2}$  个子集,即  $|\mathcal{P}(X \times X)| = 2^{n^2}$ 。

故在 n 个元素集合上,共有  $2^{n^2}$  个不同的关系。

---
#### 3-67

> 设  $A = \{6:00,6:30,7:00,\cdots,9:30,10:00\}$ 表示在晚上每隔半小时的九个时刻的集合,设  $B = \{3,12,15,17\}$ 表示本地四个电视频道的集合,设  $R_1$  和  $R_2$  是从 A 到 B 的两个二元关系,对于二元关系  $R_1$ ,  $R_2$ ,  $R_1 \cup R_2$ ,  $R_1 \cap R_2$ ,  $R_1 \oplus R_2$  和  $R_1 - R_2$  可分别得出怎样的解释。

**解**：

$A \times B$  表示在晚上九个时刻和四个电视频道所组成的电视节目表。

$R_1$  和  $R_2$  分别是  $A \times B$  的两个子集,例如  $R_1$  表示音乐节目播出的时间表, $R_2$  是戏曲节目的播出时间表,则  $R_1 \cup R_2$  表示音

乐或戏曲节目的播出时间表, $R_1 \cap R_2$  表示音乐和戏曲一起播出的时间表, $R_1 \oplus R_2$  表示音乐节目表以及戏曲节目表,但不是音乐和戏曲一起的节目表, $R_1 - R_2$  表示不是戏曲时间的音乐节目时间表。

---
#### 3-68

> 设 L 表示关系"小于或等于",D 表示"整除"关系,L 和 D 均定义于 $\{1,2,3,6\}$ ,分别写出 L 和 D 的所有元素并求出  $L\cap D$ 。

**解**：

$$L = \{\langle 1,2 \rangle, \langle 1,3 \rangle, \langle 1,6 \rangle, \langle 2,3 \rangle, \langle 2,6 \rangle, \langle 3,6 \rangle, \langle 1,1 \rangle, \langle 2,2 \rangle, \langle 3,3 \rangle, \langle 6,6 \rangle\}$$

$$D = \{\langle 1,2 \rangle, \langle 1,3 \rangle, \langle 1,6 \rangle, \langle 2,6 \rangle, \langle 3,6 \rangle, \langle 1,1 \rangle, \langle 2,2 \rangle, \langle 3,3 \rangle, \langle 6,6 \rangle\}$$

$$L \cap D = \{\langle 1,1 \rangle, \langle 2,2 \rangle, \langle 3,3 \rangle, \langle 6,6 \rangle, \langle 1,2 \rangle, \langle 1,3 \rangle, \langle 1,6 \rangle, \langle 2,6 \rangle, \langle 3,6 \rangle\}$$

---
#### 3-69

> 对下列每一式,给出 A 上的二元关系,试给出关系图:
> - a)  $\{\langle x,y \rangle | 0 \le x \land y \le 3\}$ ,这里  $A = \{0,1,2,3,4\}$ ;
> - b)  $\{\langle x,y\rangle | 2 \leqslant x,y \leqslant 7 \text{ 且 } x$
> - c)  $\{\langle x,y \rangle | 0 \leq x-y \leq 3\}$ ,这里  $A = \{0,1,2,3,4\}$ ;
> - d)  $\{\langle x,y\rangle | x \, \text{和 } y \, \text{是互质的} \}$ ,这里  $A = \{2,3,4,5,6\}$ 。
> [3-5.(5)]

**解**：

a)
$$R = \{\langle 0,0 \rangle, \langle 0,1 \rangle, \langle 0,2 \rangle, \langle 0,3 \rangle, \langle 1,0 \rangle, \langle 1,1 \rangle, \langle 1,2 \rangle, \langle 1,3 \rangle, \langle 2,0 \rangle, \langle 2,1 \rangle, \langle 2,2 \rangle, \langle 2,3 \rangle, \langle 3,0 \rangle, \langle 3,1 \rangle, \langle 3,2 \rangle, \langle 3,3 \rangle, \langle 4,0 \rangle, \langle 4,1 \rangle, \langle 4,2 \rangle, \langle 4,3 \rangle\}$$

b)
$$R = \{\langle 2,0 \rangle, \langle 2,2 \rangle, \langle 2,4 \rangle, \langle 2,6 \rangle, \langle 3,0 \rangle, \langle 3,3 \rangle, \langle 3,6 \rangle, \langle 4,0 \rangle, \langle 4,4 \rangle, \langle 5,0 \rangle, \langle 5,5 \rangle, \langle 6,0 \rangle, \langle 6,6 \rangle, \langle 7,0 \rangle, \langle 7,7 \rangle\}$$

c)
$$R = \{\langle 0, 0 \rangle, \langle 1, 0 \rangle, \langle 2, 0 \rangle, \langle 1, 1 \rangle, \langle 2, 1 \rangle, \langle 2, 2 \rangle, \langle 3, 1 \rangle, \langle 3, 2 \rangle, \langle 4, 2 \rangle, \langle 3, 3 \rangle, \langle 4, 3 \rangle, \langle 4, 4 \rangle\}$$

d)  $R = \{\langle 2,3 \rangle, \langle 3,2 \rangle, \langle 2,5 \rangle, \langle 5,2 \rangle, \langle 3,5 \rangle, \langle 3,4 \rangle, \langle 4,3 \rangle\}$

![](_page_28_Figure_0.jpeg)

![](_page_28_Figure_1.jpeg)

![](_page_28_Figure_2.jpeg)

![](_page_28_Figure_3.jpeg)

图 3-6

(4,5),(5,4),(5,3),(5,6),(6,5)

其图如图 3-6 所示。

---
#### 3-70

> 对  $P=\{0,1,2,3,4,5,6\}$ 上的二元关系, $R=\{\langle x,y\rangle | x < y \lor x$  是质数}写出关系矩阵。

**解**：

$$R = \{\langle 0,1 \rangle, \langle 0,2 \rangle, \langle 0,3 \rangle, \langle 0,4 \rangle, \langle 0,5 \rangle, \langle 0,6 \rangle, \langle 1,2 \rangle, \langle 1,3 \rangle, \langle 1,4 \rangle, \langle 1,5 \rangle, \langle 1,6 \rangle, \langle 2,3 \rangle, \langle 2,4 \rangle, \langle 2,5 \rangle, \langle 2,6 \rangle, \langle 3,4 \rangle, \langle 3,5 \rangle, \langle 3,6 \rangle, \langle 4,5 \rangle, \langle 4,6 \rangle, \langle 5,6 \rangle, \langle 2,0 \rangle, \langle 2,1 \rangle, \langle 2,2 \rangle, \langle 3,0 \rangle,$$

其关系矩阵为:

$$M_{P} = \begin{vmatrix} 0 & 1 & 1 & 1 & 1 & 1 & 1 \\ 0 & 0 & 1 & 1 & 1 & 1 & 1 \\ 1 & 1 & 1 & 1 & 1$$

---
#### 3-71

> 设  $P = \{\langle 1,2 \rangle, \langle 2,4 \rangle, \langle 3,3 \rangle\}$ 和  $Q = \{\langle 1,3 \rangle, \langle 2,4 \rangle, \langle 4,2 \rangle\}$ ,找出  $P \cup Q$ ,  $P \cap Q$ , domP, domQ, ranP, ranQ, dom $(P \cap Q)$ , ran $(P \cap Q)$ . [3-5.(7)]

**解**：

$$P \cup Q = \{\langle 1, 2 \rangle, \langle 1, 3 \rangle, \langle 2, 4 \rangle, \langle 3, 3 \rangle, \langle 4, 2 \rangle\}$$

$P \cap Q = \{\langle 2, 4 \rangle\}$
$\text{dom}P = \{1, 2, 3\}, \quad \text{dom}Q = \{1, 2, 4\}$
$\text{ran}P = \{2, 3, 4\}, \quad \text{ran}Q = \{2, 3, 4\}$
$\text{dom}(P \cap Q) = \{2\}, \quad \text{ran}(P \cap Q) = \{4\}$

---
#### 3-72

**证明**：

集合 A 是一个关系,当且仅当:
$$A \subseteq \text{dom} A \times \text{ran} A$$
[3-5.(8)]
设 $\langle x,y \rangle \in A$ ,则  $x \in \text{dom}A$ ,  $y \in \text{ran}A$ ,所以
$\langle x, y \rangle \in \text{dom} A \times \text{ran} A$
即
$A \subseteq \text{dom} A \times \text{ran} A$
反之,设  $A \subseteq \text{dom}A \times \text{ran}A$ ,因为  $\text{dom}A \times \text{ran}A$  为序偶的集合,故 A 也必是序偶的集合,即 A 是一个关系。
---
#### 3-73

> 分析集合  $A=\{1,2,3\}$ 上的下述五个关系:
> - (1)  $R = \{\langle 1,1 \rangle, \langle 1,2 \rangle, \langle 1,3 \rangle, \langle 3,3 \rangle\};$
> - (2)  $S = \{\langle 1,1 \rangle, \langle 1,2 \rangle, \langle 2,1 \rangle, \langle 2,2 \rangle, \langle 3,3 \rangle\};$
> - (3)  $T = \{\langle 1, 1 \rangle, \langle 1, 2 \rangle, \langle 2, 2 \rangle, \langle 2, 3 \rangle\};$
> - (4) Ø=空关系;
> (5) A×A=全域关系。
> 判断 A 中的上述关系是否为 a) 自反的, b) 对称的, c) 可传递的, d) 反对称的。 【3-6.(1)】

**解**：

(1) R是可传递的。

(2) S是自反、对称和可传递的。
(3) T 关于 a),b),c),d)都不成立。
(4) 空关系可定义为自反、对称和可传递的。
(5) 全域关系是自反、对称和可传递的。

---
#### 3-74

> 给定  $A = \{1, 2, 3, 4\}$ , 考虑 A 上的关系 R, 若  $R = \{\langle 1, 3 \rangle, \langle 1, 4 \rangle, \langle 2, 3 \rangle, \langle 2, 4 \rangle, \langle 3, 4 \rangle\}$ 。
> - a)  $A \times A$  的坐标图上标出R,并绘出它的关系图;
> - b) R 是 (i) 自反的, (ii) 对称的, (iii) 可传递的, (iv) 反对称的吗? 【3-6.(2)】

**解**：

a) 见图 3-7。

b) R 是可传递和反对称的,但不是自反和对称的。

![](_page_29_Figure_12.jpeg)

---
#### 3-75

> 举出  $A = \{1,2,3\}$  上关系 R 的例子,使其具有下述性质:
> - a) 既是对称的,又是反对称的;
> - b) R 既不是对称的,又不是反对称的;
> - c) R 是可传递的。
> [3-6.(3)]

**解**：

a)  $R = \{\langle 1, 1 \rangle, \langle 2, 2 \rangle, \langle 3, 3 \rangle\}$

b)  $R = \{\langle 1, 2 \rangle, \langle 2, 1 \rangle, \langle 2, 3 \rangle\}$

c)  $R = \{\langle 1, 2 \rangle, \langle 2, 1 \rangle, \langle 1, 1 \rangle, \langle 2, 2 \rangle, \langle 3, 3 \rangle\}$

---
#### 3-76

> 举出一个集合,在上面定义出一个**关系**,**分别适合于** 自反性、对称性和传递性中的两个且仅**适合两个**。

**解**：

设 $A = \{a,b,c\}, 定义$ :

1)  $R_1 = \{\langle a, a \rangle\}$ ,则  $R_1$  为对称和传递的,但  $R_1$  不是自反的, 因为 $\langle b, b \rangle \notin R_1$ , $\langle c, c \rangle \notin R_1$ 。
2)  $R_2 = \{\langle a, a \rangle, \langle b, b \rangle, \langle c, c \rangle, \langle a, b \rangle\}$ ,则  $R_2$  为自反和传递的,但无对称性,因为 $\langle a, b \rangle \in R$  但 $\langle b, a \rangle \notin R$ 。
3)  $R_3 = \{\langle a, a \rangle, \langle b, b \rangle, \langle c, c \rangle, \langle a, b \rangle, \langle b, a \rangle, \langle a, c \rangle, \langle c, a \rangle\}$ , 则  $R_3$  具有自反性和对称性,但无传递性。例如 $\langle b, a \rangle \in R \land \langle a, c \rangle \in R$ , 但 $\langle b, c \rangle \notin R$ 。

---
#### 3-77

> 如果关系 R 和 S 是自反的、对称的和可传递的,证明  $R \cap S$  也是自反、对称和可传递的。

**证明**：

设 R 和 S 是 X 上的自反关系。

1) 对任意  $x \in X$ ,有 $\langle x, x \rangle \in R$  和 $\langle x, x \rangle \in S$ ,所以 $\langle x, x \rangle \in R \cap S$ ,即  $R \cap S$  在 X 上是自反的。
2) 对任意 $\langle x,y \rangle \in R \cap S$ ,有 $\langle x,y \rangle \in R \wedge \langle x,y \rangle \in S$ 。因为 R 和 S 是对称的,故必有 $\langle y,x \rangle \in R \wedge \langle y,x \rangle \in S$ ,即 $\langle y,x \rangle \in R \cap S$ , 所以  $R \cap S$  在 X 上是对称的。
3)对任意 $\langle x,y\rangle \in R \cap S \wedge \langle y,z\rangle \in R \cap S$ ,则有  $\langle x,y\rangle \in R \wedge \langle x,y\rangle \in S \wedge \langle y,z\rangle \in R \wedge \langle y,z\rangle \in S$  因为 R 和 S 是传递的,故得 $\langle x,z\rangle \in R$ , $\langle x,z\rangle \in S$ ,即 $\langle x,z\rangle \in R \cap S$ , 所以  $R \cap S$  在 X 上是传递的。

---
#### 3-78

> 给定  $S = \{1,2,3,4\}$ 和 S 上关系:
> $$R = \{\langle 1, 2 \rangle, \langle 4, 3 \rangle, \langle 2, 2 \rangle, \langle 2, 1 \rangle, \langle 3, 1 \rangle\}$$
> 说明 R 是不可传递的,找出关系  $R_1 \supseteq R$ ,使得  $R_1$  是可传递的,还 能找出另一个  $R_2 \supseteq R$ ,也是可传递的吗? 【3-6.(5)】

**解**：

1) 因为 $\langle 4,3 \rangle \in R$ , $\langle 3,1 \rangle \in R$ ,但 $\langle 4,1 \rangle \notin R$ ,故 R 不是可传递的。
2) f  $R_1 = \{\langle 1, 2 \rangle, \langle 4, 3 \rangle, \langle 2, 2 \rangle, \langle 2, 1 \rangle, \langle 3, 1 \rangle,$

$$\langle 4,1\rangle,\langle 1,1\rangle,\langle 3,2\rangle,\langle 4,2\rangle \rangle$$

则  $R_1$  是可传递的,且  $R_1 \supseteq R_2$

3)
$$f(R_2 = R_1 \cup \{\langle 3, 3 \rangle\} = \{\langle 1, 2 \rangle, \langle 4, 3 \rangle, \langle 2, 2 \rangle, \langle 2, 1 \rangle, \langle 3, 1 \rangle, \langle 4, 1 \rangle, \langle 1, 1 \rangle, \langle 3, 2 \rangle, \langle 4, 2 \rangle, \langle 3, 3 \rangle\}$$

故  $R$  ⊇  $R$  且  $R$  是可传递的。

---
#### 3-79

> 设R 是集合X 上的一个自反关系,求证:R 是对称和 传说的,当且仅当 $\langle a,b\rangle$ 和 $\langle a,c\rangle$ 在 R 之中,并有: $\langle b,c\rangle\in R$ 。
> [3-6,(6)]

**证明**：

设R是集合X上的一个自反关系,如果R是X上对 称和传递的,则当任意 a,b,c ∈ X,若有

$\langle a,b\rangle\in R \land \langle a,c\rangle\in R$

则

$\langle b,a\rangle \in R \land \langle a,c\rangle \in R$

故得

$$\langle b,c\rangle\in R$$

反之,若 $\langle a,b\rangle\in R$ , $\langle a,c\rangle\in R$ ,必有 $\langle b,c\rangle\in R$ ,则对任意  $a,b\in$ X,若 $\langle a,b\rangle \in R(\mathbb{B}\langle a,a\rangle \in R)$ ,得到 $\langle b,a\rangle \in R$ ,故 R 是对称的。

若

$\langle a,b\rangle \in R \land \langle b,c\rangle \in R$

$$\langle b,a\rangle\in R \land \langle b,c\rangle\in R$$

所以 $\langle a,c\rangle \in R$ ,即 R 是可传递的。

---
#### 3-80

> 设  $R_1$  和  $R_2$  为 A 到 B 上的二元关系,则
> - a)  $\emptyset' = \emptyset$ ; b)  $R_1 \subseteq R_2 \Rightarrow R_1 \subseteq R_2$

**证明**：

a)  $\emptyset' = \{\langle x, y \rangle \mid \langle y, x \rangle \in \emptyset \}$ , 因 $\langle y, x \rangle \in \emptyset$ 为假, 所以

$$\emptyset^c = \emptyset$$

b) 设 R<sub>1</sub>⊆R<sub>2</sub>,则

$\langle y, x \rangle \in R_1 \Leftrightarrow \langle x, y \rangle \in R_1 \Rightarrow \langle x, y \rangle \in R_2 \Rightarrow \langle y, x \rangle \in R_2$ 所以  $R_{i} \subseteq R_{i}$

---
#### 3-81

> 设  $R_1$  和  $R_2$  是 A 上任意关系,说明以下命题的真假 并予以证明:
> - a) 若  $R_1$  和  $R_2$  是自反的,则  $R_1 \circ R_2$  也是自反的:
> - b) 若  $R_1$  和  $R_2$  是反自反的,则  $R_1 \circ R_2$  也是反自反的.
> - c) 若  $R_1$  和  $R_2$  是对称的,则  $R_1 \circ R_2$  也是对称的:
> - d) 若  $R_1$  和  $R_2$  是传递的,则  $R_1 \circ R_2$  也是传递的。【3-7.(1)】 证明 a) 真。对任意  $a \in A$ , 设  $R_1$  和  $R_2$  是自反的,则
> 所以, $\langle a,a\rangle \in R_1 \circ R_2$ ,即  $R_1 \circ R_2$  也是自反的。
> b) 假。例如:设 $A = \{a,b\}$ ,有
> $$R_1 = \{\langle a, b \rangle\} \quad = R_2 = \{\langle b, a \rangle\}$$
> $\langle a,a\rangle \in R_1, \langle a,a\rangle \in R_2$
> $R_1$  和  $R_2$  都是反自反。但  $R_1 \circ R_2 = \{\langle a, a \rangle\}$ ,所以  $R_1 \circ R_2$  在 A 上 不是反自反的。
> c) 假。例如:设 $A = \{a,b,c\}$ ,有
> $$R_1 = \{\langle a, b \rangle, \langle b, a \rangle, \langle c, c \rangle\}, \quad R_2 = \{\langle b, c \rangle, \langle c, b \rangle\}$$
> $R_1$  与  $R_2$  是对称的,但
> $$R_1 \circ R_2 = \{\langle a,c \rangle, \langle c,b \rangle\}$$
> 所以, $R_1 \circ R_2$  不是对称的。
> d) 假。例如:设 $A = \{a,b,c\}$ ,有
> $$R_1 = \{\langle a, b \rangle, \langle b, c \rangle, \langle a, c \rangle\}, R_2 = \{\langle b, c \rangle, \langle c, a \rangle, \langle b, a \rangle\}$$
> 则  $R_1$ ,  $R_2$  都是传递的。 但
> $$R_1 \circ R_2 = \{\langle a,c \rangle, \langle a,a \rangle, \langle b,a \rangle\}$$
> 所以, $R_1 \circ R_2$  不是传递的。
---
#### 3-82

**证明**：

若 S 为集合 X 上的二元关系:
- a) S 是传递的,当且仅当( $S \circ S$ )⊆S;
- b) S 是自反的,当且仅当  $I_x \subseteq S$ :
- c) 证明定理 3-7.3(b)(即 S 是反对称的,当月仅当  $S \cap S \subset$  $I_X$ ). [3-7,(2)]
a) 设 S 为传递的,  $\Xi(x,z) \in S \circ S$ , 则存在某个  $v \in X$ , 使得 $\langle x,y\rangle \in S$ ,且 $\langle y,z\rangle \in S$ 。
若 S 是传递的, $\langle x,z\rangle$ ∈S,所以 S•S⊆S。
反之,设 $S \circ S \subseteq S$ ,假定 $\langle x,y \rangle \in S$ 且 $\langle y,z \rangle \in S$ ,则 $\langle x,z \rangle \in$  $S \cdot S$ 。因为  $S \cdot S \subseteq S$ ,故 $\langle x, z \rangle \in S$ ,得到 S 是传递的。
b) 设 S 是自反的,令 $\langle x,y\rangle \in I_X$ ,则 x=y。但 $\langle x,x\rangle \in S$ ,因
此 $\langle x,y\rangle = \langle x,x\rangle \in S$ ,得  $I_x \subseteq S$ 。
反之,令  $I_X\subseteq S$ ,设任意  $x\in X$ , $\langle x,x\rangle\in I_X$ ,故 $\langle x,x\rangle\in S$ ,因此 S 是自反的。
c) 设 S 是反对称的。假定 $\langle x,y \rangle \in S \cap S^c$ ,则  $\langle x,y \rangle \in S \wedge \langle x,y \rangle \in S \wedge \langle x,y \rangle \in S$
因为 R 是反对称的,故 x=y,所以 $\langle x,y\rangle = \langle x,x\rangle \in I_X$ ,即  $S \cap S^c \subseteq I_X$ 。
反之,若 $S \cap S^c \subseteq I_X$ ,设 $\langle x,y \rangle \in S$ 且 $\langle y,x \rangle \in S$ ,则  $\langle x,y \rangle \in S \land \langle x,y \rangle \in S \Leftrightarrow \langle x,y \rangle \in S \cap S^c \Rightarrow \langle x,y \rangle \in I_X$  故 x = y,即S是反对称的。
---
#### 3-83

> 设 S 是 X 上的二元关系,证明:
> - a) S 是反自反的,当且仅当  $I_x \cap S = \emptyset$ ;
> - b) S 是对称的,当且仅当 S=S'。

**证明**：

a) 设 S 是反自反的⇔( $\forall x$ )( $x \in X \rightarrow \langle x, x \rangle \notin S$ ),但 对所有  $x \in X$ , $\langle x, x \rangle \in I_X$ ,故对所有  $x \in X$ , $\langle x, x \rangle \notin S \land \langle x, x \rangle \in I_X$ ,即  $S \cap I_X = \emptyset$ 。

b) 设 S 是对称的,则有:

$(\forall x)(\forall y)(x \in X \land y \in X \land \langle x, y \rangle \in S \rightarrow \langle y, x \rangle \in S)$  $\Leftrightarrow (\forall x)(\forall y)(x \in X \land y \in X \land \langle x, y \rangle \in S \rightarrow \langle x, y \rangle \in S^{\circ})$  $\Leftrightarrow S \subseteq S^{\circ}$

同理可证,S 是对称的 $\Leftrightarrow S \subseteq S$ 。

综上所述,S 是对称的,当且仅当 S=S.

---
#### 3-84

> 设S为X上的关系,证明:若S是自反的和传递的,则 $S \circ S = S$ ,其逆为真吗? 【3-7.(3)】

**证明**：

若 S 是 X 上传递关系,由习题 3-82(a)可知  $S \circ S \subseteq S$ ,令 $\langle x,y \rangle \in S$ ,根据自反性,必有 $\langle x,x \rangle \in S$ ,因此有 $\langle x,y \rangle \in S \circ S$ ,即  $S \subseteq S \circ S$ 。得到

$$S=S \circ S$$

这个定理的逆不真。例如  $X = \{1,2,3\}$ ,  $S = \{\langle 1,2 \rangle, \langle 2,2 \rangle, \langle 1,1 \rangle\}$ ,  $S \circ S = S$ , 但 S 不是自反的。

---
#### 3-85

> 设 S 为 X 到 Y 的关系,T 为 Y 到 Z 的关系,对于  $A \subseteq X$ ,定义  $S(A) = \langle y | \langle x, y \rangle \in S \land x \in A \rangle$ 。证明:
> - a)  $S(A) \subseteq Y$ :
> - b)  $(S \circ T)(A) = T(S(A))$ ;
> - c)  $S(A \cup B) = S(A) \cup S(B)$ :
> - d)  $S(A \cap B) \subseteq S(A) \cap S(B)$ .
> [3-7.(4)]

**证明**：

a) 设

$$y \in S(A) \Rightarrow (\exists x) (x \in A \land \langle x, y \rangle \in S)$$
$$\Rightarrow (\exists x) (x \in X \land \langle x, y \rangle \in S) \Rightarrow y \in Y$$

所以

$S(A)\subseteq Y$

b) 设

$z \in (S \circ T)(A) \Leftrightarrow x \in A \land y \in Y \land z \in Z \land \langle x, y \rangle \in S \land \langle y, z \rangle \in T$  $\Leftrightarrow z \in T(S(A))$

所以

$(S \circ T)(A) = T(S(A))$

c) 设

$y \in S(A \cup B) \Leftrightarrow (\langle x, y \rangle \in S) \land (x \in A \cup B)$

$\Leftrightarrow (\langle x,y\rangle \in S \land x \in A) \lor (\langle x,y\rangle \in S \land x \in B)$

$\Leftrightarrow y \in S(A) \lor y \in S(B) \Leftrightarrow y \in S(A) \bigcup S(B)$

所以

$S(A \cup B) = S(A) \cup S(B)$

d) 设

$y \in S(A \cap B) \Leftrightarrow (\langle x, y \rangle \in S) \land (x \in A \cap B)$

$\Leftrightarrow (\langle x, y \rangle \in S) \land (x \in A) \land (x \in B)$

$\Leftrightarrow (\langle x,y\rangle \in S \land x \in A) \land (\langle x,y\rangle \in S \land x \in B)$

$\Leftrightarrow y \in S(A) \land y \in S(B)$

$\Leftrightarrow y \in (S(A) \cap S(B))$

所以

$S(A \cap B) \subseteq S(A) \cap S(B)$

---
#### 3-86

> R 是 A 上的一个二元关系,如果 R 是自反的,则  $R^c$  一定是自反的吗?如果 R 是对称的,则  $R^c$  一定是对称吗?如果 R 是传递的,  $R^c$  一定是传递吗?

**证明**：

a) 若 R 是自反的,则对所有  $x \in A$ ,有 $\langle x, x \rangle \in R$ ,故

$\langle x,x\rangle \in R^c$ ,即  $R^c$  是自反的。

b) 若 R 是对称的,则  $R=R^c$ ,所以  $R^c$  也是对称的。
c) 若 R 是传递的,则对所有 x, y,  $z \in A$ ,若 $\langle x, y \rangle \in R^c \land \langle y, z \rangle \in R^c$ ,必有

$\langle y,x\rangle\!\in\!R\,\wedge\,\langle z,y\rangle\!\in\!R\!\Rightarrow\!\langle z,y\rangle\!\in\!R\!\Rightarrow\!\langle x,z\rangle\!\in\!R^c$  故  $R^c$  是传递的。

---
#### 3-87 设 R 为集合 X 上的二元关系,R 在 X 上是反传递⇔  $(\forall x)(\forall y)(\forall z)(x \in X \land y \in X \land z \in X \land xRy \land yRz \rightarrow (xRz))$ ,试证 R 是反传递的,当且仅当 $(R \circ R) \cap R = \emptyset$ 。

[3-7.(6)]

设 R 是反传递的,设有 $\langle x,z\rangle \in R \circ R$ ,则必有某个  $y \in X$ ,使得 $\langle x,y\rangle \in R \land \langle y,z\rangle \in R$ 。因为 R 是反传递的,故必有 $\langle x,z\rangle \notin R$ ,所以

$$(R \circ R) \cap R = \emptyset$$

反之,设 $(R \circ R) \cap R = \emptyset$ ,令 $\langle x, y \rangle \in R \land \langle y, z \rangle \in R$ ,则 $\langle x, z \rangle$   $\in R \circ R$ 。由 $(R \circ R) \cap R = \emptyset$ ,所以 $\langle x, z \rangle \notin S$ ,即R为反传递的。

---
#### 3-88

> 如果 R 是反对称关系,则在  $R \cap R^c$  的关系矩阵中有多少非零值。

**解**：如果 R 是反对称关系,则在  $R \cap R^c$  的关系矩阵中只有对角线上有非零值。如果 R 又是反自反的,则对角线上也无非零值。

---
#### 3-89

> 设 R,S,T 为集合 X 上的关系,试证:
> $$R \circ (S \cup T) = R \circ S \cup R \circ T \qquad [3-7.(8)]$$

**证明**：

设 $a,c \in X, \langle a,c \rangle \in R^{\circ}(S \cup T)$ ,当且仅当存在某个 $b \in X$ ,使得 $\langle a,b \rangle \in R \land \langle b,c \rangle \in S \cup T$ ,即是

$(\exists b)(\langle a,b\rangle \in R \land \langle b,c\rangle \in S \cup T)$

$\Leftrightarrow (\exists b)(\langle a,b\rangle \in R \land (\langle b,c\rangle \in S \lor \langle b,c\rangle \in T))$

$\Leftrightarrow (\exists b)((\langle a,b\rangle \in R \land \langle b,c\rangle \in S)$

$\forall (\langle a,b\rangle \in R \land \langle b,c\rangle \in T))$

$\Leftrightarrow \langle a,c \rangle \in R \circ S \lor \langle a,c \rangle \in S \circ T \Leftrightarrow \langle a,c \rangle \in (R \circ S \cup S \circ T)$

所以

$R \circ (S \cup T) = R \circ S \cup R \circ T$

---
#### 3-90

> 设  $R_1$  为 A 到 B 的关系,  $R_2$  和  $R_3$  是 B 到 C 的关系, 则有:
> - a)  $R_1 \circ (R_2 \bigcup R_3) = R_1 \circ R_2 \bigcup R_1 \circ R_3$ :
> - b)  $R_1 \circ (R_2 \cap R_3) \subseteq R_1 \circ R_2 \cap R_1 \circ R_3$ :
> - c) 在式 b)中,能用"="代表"⊆"吗?

**证明**：

a) 设 $\langle a,c \rangle \in R_1 \circ (R_2 \cup R_3)$ ,则必存在某个  $b \in B$ ,使得  $\langle a,b \rangle \in R_1 \land \langle b,c \rangle \in R_2 \cup R_3$

但是

$(\exists b)[\langle a,b\rangle \in R_1 \land \langle b,c\rangle \in R_2 \bigcup R_3]$

$\Leftrightarrow (\exists b)(\langle a,b\rangle \in R_1 \land (\langle b,c\rangle \in R_2 \lor \langle b,c\rangle \in R_3))$

$\Leftrightarrow (\exists b)(\langle a,b\rangle \in R_1 \land \langle b,c\rangle \in R_2)$

$\forall (\langle a,b\rangle \in R_1 \land \langle b,c\rangle \in R_3))$

$\Leftrightarrow (\langle a,c\rangle \in R_1 \circ R_2) \lor (\langle a,c\rangle \in R_1 \circ R_3)$

$\Leftrightarrow \langle a,c \rangle \in R_1 \circ R_2 \bigcup R_1 \circ R_3$

所以  $R_1 \circ (R_2 \cup R_3) = R_1 \circ R_2 \cup R_1 \circ R_3$

b) 设 $\langle a,c \rangle \in R_1 \circ (R_2 \cap R_3)$ ,则必存在  $b \in B$ ,使得  $\langle a,b \rangle \in R_1, \langle b,c \rangle \in R_2 \cap R_3$

因为

$(\exists b)(\langle a,b\rangle \in R_1 \land \langle b,c\rangle \in R_2 \cap R_3)$

$\Leftrightarrow (\exists b)(\langle a,b\rangle \in R_1 \land (\langle b,c\rangle \in R_2 \land \langle b,c\rangle \in R_3))$

$\Leftrightarrow (\exists b)((\langle a,b\rangle \in R_1 \land \langle b,c\rangle \in R_2)$

$\wedge (\langle a,b\rangle \in R_1 \wedge \langle b,c\rangle \in R_3))$

$\Leftrightarrow (\exists b)(\langle a,b\rangle \in R_1 \land \langle b,c\rangle \in R_2)$

$\wedge (\exists b) (\langle a,b \rangle \in R_1 \wedge \langle b,c \rangle \in R_3))$

$\Leftrightarrow \langle a,c \rangle \in R_1 \circ R_2 \land \langle a,c \rangle \in R_1 \circ R_3$

$\Leftrightarrow \langle a,c \rangle \in R_1 \circ R_2 \cap R_1 \circ R_3$

所以  $R_1 \circ (R_2 \cap R_3) \subseteq R_1 \circ R_2 \cap R_1 \circ R_3$

c) 在式 b)中,不能用"="代表"⊆"。

例如:设  $A=\{a\}, B=\{1,2,3\}, C=\{c\}$

$$R_1 = \{\langle a, 1 \rangle, \langle a, 3 \rangle\}, R_2 = \{\langle 2, c \rangle, \langle 3, c \rangle\}, R_3 = \{\langle 1, c \rangle\}$$

$$R_1 \circ (R_2 \cap R_3) = \emptyset, R_1 \circ R_2 \cap R_1 \circ R_3 = \{\langle a, c \rangle\}$$

所以

$$R_1 \circ (R_2 \cap R_3) \neq R_1 \circ R_2 \cap R_1 \circ R_3$$

---
#### 3-91

> 设 A 为具有 n 个元素的有限集, R 是 A 上的关系,则 必存在 s 和 t,使得  $R^s = R^t$ ,且  $0 \le s < t \le 2^{n^2}$ 。

**证明**：

因为 A 上的每个关系 R 都是  $A \times A$  的子集, 而  $A \times A$ 共有  $n^2$  个元素,故有  $2^{n^2}$ 个子集,即在 A 上有  $2^{n^2}$ 个不同的关系。 但是  $R^0$ ,  $R^1$ ,  $R^2$ , ...,  $R^{2n^2}$ , 有  $2^{n^2}+1$  项, 故在 A 上必有两项  $R^i=$ R',且  $0 \leqslant s \leqslant t \leqslant 2^{n^2}$  成立。

---
#### 3-92

> 根据图 3-8 中的有向图,写出邻接矩阵和关系 R,并 求出R的自反闭包和对称闭包。 [3-8.(1)]

**解**：

邻接矩阵为:

$$M_R = \begin{vmatrix} 1 & 1 & 0 \\ 0 & 0 & 1 \\ 0 & 1 & 0 \end{vmatrix}$$

$$R = \{\langle a, a \rangle, \langle a, b \rangle, \langle b, c \rangle, \langle c, b \rangle\}$$

$$r(R) = R \cup I_X$$

$$= \{\langle a,a\rangle,\langle b,b\rangle,\langle c,c\rangle,\langle a,b\rangle,\langle b,c\rangle,\langle c,b\rangle\}$$

$$s(R) = R \cup R^c = \{\langle a, a \rangle, \langle a, b \rangle, \langle b, a \rangle, \langle b, c \rangle, \langle c, b \rangle\}$$

![](_page_33_Picture_12.jpeg)

图 3-8

![](_page_33_Picture_14.jpeg)

图 3-9

---
#### 3-93 设集合  $A = \{a,b,c,d\}$  上关系

$$R = \{\langle a,b \rangle, \langle b,a \rangle, \langle b,c \rangle, \langle c,d \rangle\}$$

a) 用矩阵运算和作图方法求出 R 的自反、对称、传递闭合;
b) 用 Warshall 算法,求出 R 的传递闭包。 [3-8.(2)]解 a) 矩阵为:

$$M_R = \begin{vmatrix} 0 & 1 & 0 & 0 \\ 1 & 0 & 1 & 0 \\ 0 & 0 & 0 & 1 \\ 0 & 0 & 0 & 0 \end{vmatrix}$$

R的关系图如图 3-9 所示。

$$M_R + M_{I_A} = \begin{vmatrix} 0 & 1 & 0 & 0 \\ 1 & 0 & 1 & 0 \\ 0 & 0 & 0 & 1 \\ 0 & 0 & 0 & 0 \end{vmatrix} + \begin{vmatrix} 1 & 0 & 0 & 0 \\ 0 & 1 & 0 & 0 \\ 0 & 0 & 1 & 0 \\ 0 & 0 & 0 & 1 \end{vmatrix}$$

$$= \begin{vmatrix} 1 & 1 & 0 & 0 \\ 1 & 1 & 1 & 0 \end{vmatrix}$$

$$r(R) = R \bigcup I_A = \{\langle a, a \rangle, \langle a, b \rangle, \langle b, a \rangle, \langle b, b \rangle,$$

$$\langle b, c \rangle, \langle c, c \rangle, \langle c, d \rangle, \langle d, d \rangle \}$$
(

$$M_R + M_{R^c} = \begin{bmatrix} 0 & 1 & 0 & 0 \ 1 & 0 & 1 & 0 \ 0 & 0 & 0 & 1 \ 0 & 0 & 0 & 0 \end{pmatrix} + \begin{bmatrix} 0 & 1 & 0 & 0 \ 1 & 0 & 0 & 0 \ 0 & 1 & 0 & 0 \ 0 & 0 & 1 & 0 \end{bmatrix} \ = \begin{bmatrix} 0 & 1 & 0 & 0 \ 1 & 0 & 1 & 0 \ 0 & 1 & 0 & 1 \ 0 & 0 & 1 & 0 \end{bmatrix}$$

$$s(R) = R \cup R^2 = \{\langle a, b \rangle, \langle b, a \rangle, \langle b, c \rangle, \langle c, b \rangle,$$

![](_page_33_Picture_27.jpeg)

![](_page_33_Picture_28.jpeg)

![](_page_33_Figure_30.jpeg)

图 3-10

$$M_{R^2} = M_R \circ M_R = \begin{vmatrix} 0 & 1 & 0 & 0 \\ 1 & 0 & 1 & 0 \\ 0 & 0 & 0 & 1 \\ 0 & 0 & 0 & 0 \end{vmatrix} \circ \begin{vmatrix} 0 & 1 & 0 & 0 \\ 1 & 0 & 1 & 0 \\ 0 & 0 & 0 & 1 \\ 0 & 0 & 0 & 0 \end{vmatrix}$$

$$= \begin{vmatrix} 1 & 0 & 1 & 0 \\ 0 & 1 & 0 & 1 \\ 0 & 0 & 0 & 0 \\ 0 & 0 & 0 & 0 \end{vmatrix}$$

$$M_{R^3} = M_{R^2} \circ M_R = \begin{vmatrix} 1 & 0 & 1 & 0 \\ 0 & 1 & 0 & 1 \\ 0 & 0 & 0 & 0 \\ 0 & 0 & 0 & 0 \end{vmatrix} \circ \begin{vmatrix} 0 & 1 & 0 & 0 \\ 1 & 0 & 1 & 0 \\ 0 & 0 & 0 & 1 \\ 0 & 0 & 0 & 0 \end{vmatrix}$$

$$= \begin{vmatrix} 0 & 1 & 0 & 1 \\ 1 & 0 & 1 & 0 \\ 0 & 0 & 0 & 0 \\ 0 & 0 & 0 & 0 \end{vmatrix} \circ \begin{vmatrix} 0 & 1 & 0 & 0 \\ 1 & 0 & 1 & 0 \\ 0 & 0 & 0 & 0 \end{vmatrix}$$

$$M_{R^4} = M_{R^3} \circ M_R = \begin{vmatrix} 0 & 1 & 0 & 1 \\ 1 & 0 & 1 & 0 \\ 0 & 0 & 0 & 0 \\ 0 & 0 & 0 & 0 \end{vmatrix} \circ \begin{vmatrix} 0 & 1 & 0 & 0 \\ 1 & 0 & 1 & 0 \\ 0 & 0 & 0 & 1 \\ 0 & 0 & 0 & 0 \end{vmatrix}$$

$$= \begin{vmatrix} 1 & 0 & 1 & 0 \\ 0 & 1 & 0 & 1 \\ 0 & 0 & 0 & 0 \\ 0 & 0 & 0 & 0 \end{vmatrix}$$

$$M_R + M_{R^2} + M_{R^3} + M_{R^4} = \begin{vmatrix} 1 & 1 & 1 & 1 \\ 1 & 1 & 1 & 1 \\ 0 & 0 & 0 & 1 \\ 0 & 0 & 0 & 0 \end{vmatrix}$$

b)
$$A:=M_{R}=\begin{vmatrix}0&1&0&0\\1&0&1&0\\0&0&0&1\\0&0&0&0\end{vmatrix}$$
$i=1,A[2,1]=1,$ 将第一行加到第二行得
$$A:=\begin{vmatrix}0&1&0&0\\1&1&1&0\\0&0&0&1\\0&0&0&0\end{vmatrix}$$
$i=2,A[1,2]=A[2,2]=1,$ 将第二行加到第一行及第二行上 得到
$$A:=\begin{vmatrix}1&1&1&0\\1&1&1&0\\0&0&0&1\\0&0&0&0\end{vmatrix}$$
$i=3,A[1,3]=A[2,3]=1,$  将第三行加到第一行及第二行 得到
$$A:=\begin{vmatrix}1&1&1&1\\1&1&1&1\\0&0&0&1\end{vmatrix}$$

i=3,A[1,3]=A[2,3]=1,将第三行加到第一行及第二行 得到

$$A := \begin{vmatrix} 1 & 1 & 1 & 1 \\ 1 & 1 & 1 & 1 \\ 0 & 0 & 0 & 1 \\ 0 & 0 & 0 & 0 \end{vmatrix}$$

i=4, $A \lceil 1,4 \rceil = A \lceil 2,4 \rceil = A \lceil 3,4 \rceil = 1$ ,将第四行加到第一、第 二及第三行得到

$$A := \begin{vmatrix} 1 & 1 & 1 & 1 \\ 1 & 1 & 1 & 1 \\ 0 & 0 & 0 & 1 \\ 0 & 0 & 0 & 0 \end{vmatrix}$$

$t(R) = \{\langle a, a \rangle, \langle a, b \rangle, \langle a, c \rangle, \langle a, d \rangle, \langle b, a \rangle,$  $\langle b,b\rangle,\langle b,c\rangle,\langle b,d\rangle,\langle c,d\rangle$ (见图 3-10(c))

---
#### 3-94

> 归纳出用矩阵和作图方法求出自反(对称、传递)闭包
> · 163 ·
> 所以
> 的一般方法。

**解**：

设有  $X = \{x_1, x_2, \dots, x_n\}$ 上关系 R,其关系矩阵为  $M_R$ ,关系图为  $G_R$ 。如果求 R 的自反闭包 r(R),在  $M_R$  中,只需将其对角线上的元素都改为 1,即在  $M_R$  中使  $a_{ii} = 1$ , $1 \le i \le n$ 。在关系图  $G_R$  上只需对每个结点画上自回路。

对于求 R 的对称闭包 s(R),在关系矩阵  $M_R$  中,若有  $a_{ij}=1$ ,则可添加  $a_{ji}=1$ ,在关系图  $G_R$  上,只要对任意两个结点间有连线,可使该两结点添加为双向线。

对于求 R 的传递闭包,矩阵  $M_R$  可利用 Warshall 算法,求得 传递闭包的矩阵,其算法为:

(1) 置新矩阵 A := M;
(2) 置 i:=1:
(3) 对所有 j,如果 A[j,i]=1,则对  $k=1,2,\dots,n$ ,有 A[j,k]:=A[j,k]+A[i,k]
(4) i加1:
(5) 如果 i≤n 则转到步骤(3),否则停止。

对于关系图  $G_R$ ,可自某一结点开始,逐点检查,若有三个结点  $x_i, x_j, x_k$  满足 $\langle x_i, x_j \rangle \in R$ , $\langle x_j, x_k \rangle \in R$  则可连结  $x_i$  与  $x_j$ 。这样 对所有邻接边都逐对检查,直至结束。

---
#### 3-95

> 设 R 是有限集 X 上的一个二元关系,定义:
> $$R^+ = R \cup R^2 \cup \cdots \cup R^n \cup \cdots$$

**证明**：

a) 对于任意 X 上的二元关系 R,则 R<sup>+</sup> 是传递的;

b) 若有 X 上其他传递关系 P,使得  $P \supseteq R$ ,则必有  $R^+ \subseteq P$ ;
c) R<sup>+</sup> 就是内容提要 8 中所说的传递闭包。 【3-8.(4)】

a) 设 x, y,  $z \in X$ , 对任意 $\langle x, y \rangle \in R^+$ ,  $\langle y, z \rangle \in R^+$ 必存在正整数 s 和 t, 使 $\langle x, y \rangle \in R^s \land \langle y, z \rangle \in R^t$ , 即有 $\langle x, z \rangle \in R^s \land R^t = R^{s+t}$ , 但  $R^{s+t} \subseteq R^+$ , 所以 $\langle x, z \rangle \in R^+$ , 故  $R^+$  为传递的。

b) 对任意 $\langle x,y \rangle \in R^+$ ,必有某个正整数 s,使得 $\langle x,y \rangle \in R^t$ ,即存在  $l_1$ , $l_2$ ,…, $l_{s-1}$ ,且有 $\langle x,l_1 \rangle \in R$ , $\langle l_1,l_2 \rangle \in R$ ,…, $\langle l_{s-1},y \rangle \in R$ 。因为  $R \subseteq P$ ,故有 $\langle x,l_1 \rangle \in P$ , $\langle l_1,l_2 \rangle \in P$ ,…, $\langle l_{s-1},y \rangle \in P$ ,由

P的传递性,得到 $\langle x,y \rangle \in P$ ,所以  $R^+ \subseteq P$ 。

c)按假设  $R^+ \supseteq R$ ,由 a),b)证明了  $R^+$  是包含 R 的最小传递 关系,故它就是内容提要 8 中的传递闭包。

---
#### 3-96

> 设 R 为有限集 X 上的传递关系,证明: $(R^c)^+ = R^c$ 。

**证明**：

题设中的 $(R^c)^+ = t(R^c)$ ,设任意  $a,b,c \in X$ ,如果 $\langle a,b \rangle \in R^c \land \langle b,c \rangle \in R^c$ ,则 $\langle b,a \rangle \in R$ , $\langle c,b \rangle \in R$ 。因为 R 是传递的,故 $\langle c,a \rangle \in R$ ,所以 $\langle a,c \rangle \in R^c$ ,即  $R^c$  是 X 上传递关系,由定理3-8.1c),得到  $R^c = t(R^c)$ 。

---
#### 3-97

> 试证 a) 若 R 是自反的,则 s(R)和 t(R)是自反的:
> - b) 若 R 是对称的,则 r(R)和 t(R)是对称的;
> - c) 若 R 是传递的,则 r(R) 是传递的。

**证明**：

a) 设 R 是 X 上的自反关系,因此  $I_X \subseteq R$ ,由 s(R)定义, $s(R) \supseteq R$ ,故  $s(R) \supseteq I_X$ 。对所有  $x \in X$ ,有 $\langle x, x \rangle \in I_X$ ,得到 $\langle x, x \rangle \in s(R)$ ,即 s(R)是 X 上的自反关系。

同理,对任意  $x \in X$ , $\langle x, x \rangle \in R$ 。因为  $t(R) = R \cup R^2 \cup \dots$ ,故 必有 $\langle x, x \rangle \in t(R)$ ,即 t(R)是 X上自反关系。

b) 设 R 是 X 上对称关系,对任意  $x,y \in X$ ,若有 $\langle x,y \rangle \in r(R)$ ,则 $\langle x,y \rangle \in R \vee \langle x,y \rangle \in I_X$ ,即

$$\langle x,y\rangle \in R \ \forall \ x=y \Rightarrow \langle y,x\rangle \in R \ \forall \ x=y$$

故r(R)在X上是对称的。

又,如果 $\langle x,y\rangle \in t(R) = R \cup R^2 \cup R^3 \cup \cdots$ ,则必存在某个 s,使得 $\langle x,y\rangle \in R^s$ ,故有序列  $l_1, l_2, \cdots, l_{s-1}$ 使得

$$\langle x, l_1 \rangle \in R, \langle l_1, l_2 \rangle \in R \cdots \langle l_{s-1}, y \rangle \in R$$

因为 R 是对称的,故有

$$\langle y, l_{s-1} \rangle \in R \cdots \langle l_2, l_1 \rangle \in R, \langle l_1, x \rangle \in R$$

得到 $\langle y,x\rangle \in R'$ ,即 $\langle y,x\rangle \in t(R)$ ,所以 t(R)在 X 上是对称的。

c) 因为由定理 3-8.1,R 传递当且仅当 t(R) = R。故要证 r(R)为传递,只需证得 tr(R) = r(R)。

$$tr(R) = t(R \bigcup I_x) = \bigcup_{i=1}^{\infty} (R \bigcup I_x)^i$$

由归纳法可证

$$(R \bigcup I_x)^i = \bigcup_{i=0}^i R^i$$

故

$$tr(R) = \bigcup_{i=1}^{\infty} \bigcup_{j=0}^{i} R^{j} = \bigcup_{i=0}^{\infty} R^{i} = I_{x} \bigcup \bigcup_{i=1}^{\infty} R^{i} = I_{x} \bigcup t(R)$$
$$= I_{x} \bigcup R = r(R)$$

E

$$tr(R) = r(R)$$

---
#### 3-98

> 设  $R_1$  和  $R_2$  是集合 A 上的关系,且  $R_1 \supseteq R_2$ ,求证:
> - a)  $r(R_1) \supseteq r(R_2)$ ;
> - b)  $s(R_1) \supseteq s(R_2)$ ;
> - c)  $t(R_1) \supseteq t(R_2)$ .
> [3-8.(5)]

**证明**：

a) 因为  $R_1 \supseteq R_2$ ,故  $R_1 \cup I_A \supseteq R_2 \cup I_A$ ,即

$$r(R_1) \supseteq r(R_2)$$

b) 因为  $s(R_1)$ 对称,且  $s(R_1) \supseteq R_1$ ,但  $R_1 \supseteq R_2$ ,故  $s(R_1) \supseteq R_2$ ,由  $s(R_2)$ 的定义, $s(R_2)$ 是包含  $R_2$ 的最小对称关系,故  $s(R_1) \supseteq s(R_2)$

c) 因为
$$t(R_1)$$
传递,且  $t(R_1) \supseteq R_1$ ,但  $R_1 \supseteq R_2$ ,故  $t(R_1) \supseteq R_2$

因  $t(R_2)$  是包含  $R_2$  的最小传递关系,所以

$$t(R_1)\supseteq t(R_2)$$

---
#### 3-99

> 证明定理 3-8.6 的 c)。
> [3-8.(6)]

**证明**：

设X是集合,R是X上的二元关系,则

$$ts(R) \supseteq st(R)$$

因为  $R_1 \supseteq R_2$  时, $s(R_1) \supseteq s(R_2)$ ,且  $t(R_1) \supseteq t(R_2)$ ,根据对称闭包 定义, $s(R) \supseteq R$ ,故

$$ts(R)\supseteq t(R)$$
,  $sts(R)\supseteq st(R)$

由 s(R)对称,以及习题 3-97b)可知 ts(R)是对称的,再由定理 3-8.1 得到

$$sts(R) = ts(R)$$

所以

$$ts(R) \supseteq st(R)$$

---
#### 3-100

> 设  $R_1$  和  $R_2$  是 A 上的关系,证明:
> - a)  $r(R_1 \cup R_2) = r(R_1) \cup r(R_2)$ ;
> - b)  $s(R_1 \cup R_2) = s(R_1) \cup s(R_2)$ ;
> - c)  $t(R_1 \bigcup R_2) \supseteq t(R_1) \bigcup t(R_2)$ .
> [3-8.(7)]

**证明**：

a)
$$r(R_1 \cup R_2) = R_1 \cup R_2 \cup I_X = R_1 \cup I_X \cup R_2 \cup I_X$$

=  $r(R_1) \cup r(R_2)$

b)
$$s(R_1 \cup R_2) = (R_1 \cup R_2) \cup (R_1 \cup R_2)^c$$

$= R_1 \cup R_2 \cup R_1^c \cup R_2^c$
$= (R_1 \cup R_1^c) \cup (R_2 \cup R_2^c)$
$= s(R_1) \cup s(R_2)$

c) 因为  $R_1 \cup R_2 \supseteq R_1$ , 由习题 3-98,则

$$t(R_1 \bigcup R_2) \supseteq t(R_1)$$

同理

$$t(R_1 \bigcup R_2) \supseteq t(R_2)$$

所以  $t(R_1 \cup R_2) \supseteq t(R_1) \cup t(R_2)$

---
#### 3-101

> 设 R 是集合 A 上的一个任意关系,证明下列各式。
> - a)  $(R^+)^+ = R^+$ ;
> - b)  $R \circ R^* = R^+ = R^* \circ R$ ;
> - c)  $(R^*)^* = R^* (R^* = tr(R))_{\alpha}$
> [3-8,(8)]

**证明**：

a)  $(R^+)^+ = t(t(R))$ ,因为 t(R)是传递的,根据定理 3-8.1, t(t(R)) = t(R),即 $(R^+)^+ = R^+$ 。

b)
$$R \circ R^* = R \circ (tr(R)) = R \circ (rt(R)) = R \circ (t(R) \cup I_A)$$

$= R \circ t(R) \cup R \circ I_A = R \circ \bigcup_{i=1}^{\infty} R^i \cup R$
$= \bigcup_{i=2}^{\infty} R^i \cup R = \bigcup_{i=1}^{\infty} R^i = t(R) = R^+$

同理可证

$$R^+ = R^* \circ R$$

c) 因为 r(R)是自反的,由习题 3-97a),tr(R)是自反的,根据定理 3-8.1, rtr(R) = tr(R),即  $r(R^*) = R^*$ ,但  $R^*$ 传递的,故  $t(R^*) = R^*$ ,即  $tr(R^*) = R^*$ 。所以, $(R^*)^* = R^*$ 。

---
#### 3-102

> 考虑图 3-11 所示四颗骰子,称其为 A,B,C,D。任取其中两颗骰子 x 和 y 投掷,若 x 的点数大于 y 的点数,则称为 "x 胜于 y"。
> ![](_page_37_Figure_1.jpeg)
> 图 3-11
> a) 对每一对骰子 x 和 y, 计算"x 胜于 y"的概率,用二维数组表示这些结果,使得数组的填入值正好是概率。
> 设 R 是集合 $\{A,B,C,D\}$ 上的二元关系,R 定义如下:  $xRy \mapsto x$  打败 y 的概率大于 1/2。
> - b) 给出 R 的关系图和关系表达式。
> - c) 找出 R 的传递闭包。
> - d) 关系 R 是可传递吗?
> - e) 假定有人提出下面的游戏办法:让你先从{A,B,C,D}中任选一颗骰子,在你选定后,他从剩下的三颗骰子中选一颗骰子,然后投掷这两颗骰子,点数大的人得胜,输者要向赢者付钱,问这个游戏办法,你是否能接受?为什么?

**解**：

a) 设任取两颗骰子如 A, B, 投掷后将 A 的点数 x 和 B 的点数 y 作成点数序偶 $\langle x,y \rangle$ , 若在 $\langle x,y \rangle$ 中有 x > y 则称此点数序偶为胜数序偶。因为投掷 A, B 两颗骰子, 共有 36 个点数序偶,其中 24 个为胜数序偶,故 A 胜于 B 的概率为 24/36=2/3。类似这样的方法,可得每对骰子的"胜于"概率(表 3-1)。在表中位于第 i 行和第 j 列的值,是第 i 颗骰子胜于第 j 颗骰子的概率。
b) 从表 3-1 中看出,概率大于 1/2 共有 5 项:  $B = \{\langle A, B \rangle, \langle B, C \rangle, \langle C, A \rangle, \langle C, D \rangle, \langle D, A \rangle\}$  关系图如图 3-12 所示。

表 3-1

|                  | A                                                                                           | В             | $\boldsymbol{c}$ | D                                 |
|------------------|---------------------------------------------------------------------------------------------|---------------|------------------|-----------------------------------|
| Α                | 2 9                                                                                         | 2 3           | 4 9              | 1
| В                | 1 2                                                                                         | 0             | $\frac{2}{3}$    | $\frac{1}{2}$                     |
| $\boldsymbol{C}$ | $\begin{array}{ c c }\hline 1\\\hline 3\\\hline 5\\\hline 9\\\hline 2\\\hline 3\end{array}$ | 1/3           | 9                | $\frac{\frac{1}{2}}{\frac{2}{3}}$ |
| D                | $\frac{2}{3}$                                                                               | $\frac{1}{2}$ | $\frac{1}{3}$    | $\frac{1}{4}$                     |

![](_page_37_Picture_13.jpeg)

c) 由 Warshall 算法得  $R^+$  为  $S = \{A, B, C, D\}$ 上的全域关系,即  $R^+ = S \times S$ 。
d) R 不是传递的。因为 $\langle B,C\rangle \in R$ , $\langle C,A\rangle \in R$ ,但 $\langle B,A\rangle \notin R$ ,故 R 不是传递的。
e) 所提游戏办法不能接受。因为从 a) 所列表 3-1 中,可以看出在任意 *i* 行,都能找到一个 *j*,使该项的概率为 2/3,故不论你洗那颗骰子,你的对手必可选出一颗骰子,使胜你的概率为 2/3。

---
#### 3-103

> 设R 为集合A 上的反对称关系,则t(R) 一定是反对称吗?

**证明**：

设R为A上反对称关系,则t(R)在A上不一定是反对称的。例如,设

$$A = \{a,b,c,d\}$$

$$R = \{\langle a,b\rangle,\langle b,c\rangle,\langle c,d\rangle,\langle d,a\rangle\}$$

则R的传递闭包

$$t(R) = \{ \langle a,b \rangle, \langle b,c \rangle, \langle c,d \rangle, \langle d,a \rangle, \langle a,c \rangle, \langle c,a \rangle, \\ \langle a,d \rangle, \langle d,c \rangle, \langle b,d \rangle, \langle d,b \rangle, \langle c,b \rangle, \langle b,a \rangle, \\ \langle a,a \rangle, \langle b,b \rangle, \langle c,c \rangle, \langle d,d \rangle \}$$

在本例中,R是反对称的,但是 t(R)是对称的。

---
#### 3-104

> 4个元素的集合共有多少不同的划分。 【3-9.(1)】

**解**：

整数 4 可划分为:4,1+3,1+1+2,2+2,1+1+1+1。

$$1+C_4^1+C_4^2+\frac{1}{2}C_4^2+1=15$$
(种)

---
#### 3-105

> 设 $\{A_1,A_2,\cdots,A_k\}$ 是集合 A 的一个划分,我们定义
> A 上的一个二元关系 R,使 $\langle a,b\rangle \in R$  当且仅当 a 和 b 在这个划分 [3-9.(2)]的同一块中。证明 R 是自反的、对称的和传递的。

**证明**：

设对任意  $a \in A$ ,则必存在 A,使  $a \in A$ ,因 a 与 a 必可 看作在同一块中,故有 $\langle a,a\rangle \in R$ ,即 R 是自反的。

设 $a,b \in A$ ,若有 $\langle a,b \rangle \in R$ ,则a = b必在同一块,故b = a亦 在同一块、 $\langle b,a\rangle$  ∈ R,即 R 是对称的。

设 $a,b,c \in A$ ,若有 $\langle a,b \rangle \in R \land \langle b,c \rangle \in R$ ,则必 $(\exists i$ ,使得 $a \in$  $A_i \land b \in A_i$ ,且必  $(\exists j$ ,使  $b \in A_i \land c \in A_i$ ,这样 i = j。因为若  $i \neq j$ , 则  $b \in A_i \cap A_j$ ,故  $A_i \cap A_i \neq \emptyset$ 。这与  $A_i$ ,  $A_i$  是 A 的划分块矛盾。 由此得 a,b,c 均属同一分块  $A_i$ , 因此 $\langle a,c \rangle \in R$ , 即 R 是传递的。

---
#### 3-106

> 设  $\Pi_1$  和  $\Pi_2$  是非空集合 A 的划分,说明下列各式,哪 些是A的划分,哪些可能是A的划分,哪些不是A的划分,并给 予证明。
> - a)  $\Pi_1 \cup \Pi_2$ ;
> - b)  $\Pi_1 \cap \Pi_2$ ;
> - c)  $\Pi_1 \Pi_2$ [3-9.(3)]

**证明**：

a) 当  $\Pi_1 = \Pi_2$  时  $\Pi_1 \cup \Pi_2 = \Pi_1$  ,故  $\Pi_1 \cup \Pi_2$  是 A 的划 分。设 $\Pi_1 = \{A_1, A_2, \dots, A_k\}, \Pi_2 = \{B_1, B_2, \dots, B_k\}$ 。

当  $\Pi_1 \neq \Pi_2$  时,必存在  $B_i \in \Pi_2$ ,但  $B_i \notin \Pi_1$ 。为此, $B_i \in \Pi_1$  ∪  $\Pi_2$ 。如果  $\Pi_1 \cup \Pi_2$  是 A 的划分,则根据划分的定义, $B_i \cap A_1 = \emptyset$ ,  $B_i \cap A_i = \emptyset, \dots, B_i \cap A_i = \emptyset$ 。设对任意  $x \in B_i$ ,则  $x \in A$ ,但因  $x \in B_1$ ,故  $x \notin A_1$ ,  $x \notin A_2$ ,  $x \notin A_3$ , ...,  $x \notin A_k$ 。这与

$$\bigcup_{i=1}^k A_i = A$$

矛盾。所以当 $\Pi_1 \neq \Pi_2$ 时, $\Pi_1 \cup \Pi_2$ 不是A的划分。

b) 当  $\Pi_1 = \Pi_2$  时  $\Pi_1 \cap \Pi_2 = \Pi_1$  是 A 的划分。

当  $\Pi_1 \neq \Pi_2$  时,设  $\Pi_1 = \{A_1, A_2, \dots, A_r\}$ ,  $\Pi_2 = \{B_1, B_2, \dots, A_r\}$  $B_i$ },则必存在  $B_i \in \Pi_2$ ,但  $B_i \notin \Pi_1$ ,故  $B_i \notin \Pi_1 \cap \Pi_2$ ,为此可得  $\Pi_1 \cap \Pi_2 \subset \Pi_2$ ,  $\Pi_2 \not\in A$  的划分, 故其真子集  $\Pi_1 \cap \Pi_2$  必不是 A 的 划分。

c) 若  $\Pi_1 \cap \Pi_2 = \emptyset$ ,则  $\Pi_1 - \Pi_2 = \Pi_1$  是 A 的划分。

若  $\Pi_1 \cap \Pi_2 \neq \emptyset$ ,必有  $A_i \in \Pi_1 \land A_i \in \Pi_2$ ,故必有  $A_i \notin \Pi_1 - \Pi_2$ . 因此  $\Pi_1 - \Pi_2 \subset \Pi_1$ 。  $\Pi_1$  是 A 的划分,所以其真子集  $\Pi_1 - \Pi_2$ ,必不 A 的划分。

---
#### 3-107

> 设 R 是集合 A 上的一个自反、对称和传递的关系,  ${\it X}\{A_1,A_2,\cdots,A_k\}$ 是 A 的子集的集合,当  $i\neq i$  时, $A_i \subseteq A_i$ ,使得 a 和 b 在同一个子集中,当且仅当 $\langle a,b\rangle \in R$ 。求证: $\{A_1,A_2,\cdots,A_k\}$ 是 A 的一个划分。 [3-9.(4)]

**证明**：

设 $A_i(i=1,2,\cdots,k)$ 为A的子集,即 $A_i \subseteq A$ ,所以

$$\bigcup_{i=1}^k A_i \subseteq A$$

设有任意  $a \in A$ ,因为  $R \neq A$  上等价关系,得 $\langle a,a \rangle \in R$ ,故 a与a在同一子集A,中,即

$$a \in A_i \Rightarrow a \in \bigcup_{i=1}^k A_i$$

$a \in A_i \Rightarrow a \in \bigcup_{i=1}^k A_i$ 所以有  $A \subseteq \bigcup_{i=1}^k A_i$  ,得到

$$A = \bigcup_{i=1}^k A_i$$

其次可以证明, 当  $i \neq j$  时,  $A_i \cap A_i = \emptyset$ 。因为  $i \neq j$  时,  $A_i \nsubseteq$  $A_i$ ,故 $A_i$ , $A_i$ 非空。

设有  $a \in A_i$ ,对任意  $b \in A_i$   $(i \neq i)$ ,则必有 $\langle a,b \rangle \notin R_i$ 。因为如 果 $(a,b) \in R$ ,则 a,b 属于同一子集,故有  $b \in A_i$ ,于是有  $A_i \subseteq A_i$ , 与题设  $A_i \subset A_i$  矛盾。因此若有  $A_i \cap A_i \neq \emptyset$ ,则有  $C \in A_i \cap A_i$ ,对  $a \in A_i \land b \in A_i \Rightarrow \langle a,c \rangle \in R \land \langle c,b \rangle \in R$

因 R 县等价关系,得到 $\langle a,b\rangle$  ∈ R,与 $\langle a,b\rangle$  ∉ R 矛盾。所以 A,  $\cap$  $A_i = \emptyset$ ,于是证得: $\{A_1, A_2, \dots, A_n\}$ 是 A 的划分。

---
#### 3-108

> 设 $\{A_1,A_2,\dots,A_n\}$ 是集合 A 的划分,若  $A_i \cap B \neq \emptyset$ ,  $1 \le i \le n$ , 试证明 $\{A_1 \cap B, A_2 \cap B, \dots, A_n \cap B\}$  是集合  $A \cap B$  的 划分。 [3-9,(5)]

**证明**：

因为 $\{A_1,A_2,\cdots,A_n\}$ 是集合 A 的划分,故

$$A = \bigcup_{i=1}^{B} A_i, A_i \cap A_j = \emptyset (i \neq j)$$

$$A \cap B = (\bigcup_{i=1}^{n} A_i) \cap B = \bigcup_{i=1}^{n} (A_i \cap B)$$

当  $i\neq j$  时,

$$(A_i \cap B) \cap (A_i \cap B) = \emptyset$$

当 i=j 时,

$$A_i \cap B = A_i \cap B$$

所以, $\{A_1 \cap B, A_2 \cap B, \dots, A_n \cap B\}$ 是  $A \cap B$  的划分。

---
#### 3-109

> 设 R 和 R'是集合 A 上的等价关系,用例子说明 R U R'不一定是等价关系。

**证明**：

设
$$A = \{1,2,3\}, S = R \cup R'$$
$R = \{\langle 1,1\rangle, \langle 2,2\rangle, \langle 3,3\rangle, \langle 3,1\rangle, \langle 1,3\rangle\}$   $R' = \{\langle 1,1\rangle, \langle 2,2\rangle, \langle 3,3\rangle, \langle 3,2\rangle, \langle 2,3\rangle\}$

则

$$R \cup R' = \{\langle 1,1 \rangle, \langle 2,2 \rangle, \langle 3,3 \rangle, \langle 3,1 \rangle, \langle 1,3 \rangle, \langle 3,2 \rangle, \langle 2,3 \rangle\}$$

因为如 $\langle 2,3 \rangle \in S \land \langle 3,1 \rangle \in S$ ,但 $\langle 2,1 \rangle \notin S$ ,故  $R \cup R'$ 不是传递的,即  $R \cup R'$ 不是 A 上的等价关系。

---
#### 3-110

> 试问:由 4 个元素组成的有限集上所有等价关系的个数为多少? 【3-10.(2)】

**解**：

因为集合 X 上的等价关系与 X 的划分是——对应的,所以 4 个元素的有限集上等价关系的数目,与 4 个元素集合进行划分的数目是相同的,由习题 3-104 可知共有 15 个不同的等价关系。

---
#### 3-111

> 给定集合  $S=\{1,2,3,4,5\}$ ,找出 S 上的等价关系 R,此关系 R 能产生划分 $\{\{1,2\},\{3\},\{4,5\}\}$ ,并画出关系图
> [3-10.(3)]

**解**：

我们可用如下方法产生一个等价关系:

$$R_1 = \{1,2\} \times \{1,2\} = \{\langle 1,1\rangle, \langle 1,2\rangle, \langle 2,1\rangle, \langle 2,2\rangle\}$$

$$R_{2} = \{3\} \times \{3\} = \{\langle 3,3 \rangle\}$$

$$R_{3} = \{4,5\} \times \{4,5\}$$

$$= \{\langle 4,4 \rangle, \langle 4,5 \rangle, \langle 5,4 \rangle, \langle 5,5 \rangle\}$$

$$R = R_{1} \cup R_{2} \cup R_{3}$$

$$= \{\langle 1,1 \rangle, \langle 2,2 \rangle, \langle 3,3 \rangle, \langle 4,4 \rangle,$$

$$\langle 5,5 \rangle, \langle 1,2 \rangle, \langle 2,1 \rangle, \langle 4,5 \rangle,$$

![](_page_39_Figure_21.jpeg)

图 3-13

〈5,4〉} 关系图如图 3-13。

---
#### 3-112

> 设 R 是一个二元关系, $S=\{\langle a,b\rangle \mid$ 对于某一 c,有  $\langle a,c\rangle \in R \land \langle c,b\rangle \in R \rangle$ ,证明若 R 是一个等价关系,则 S 也是一个等价关系。

**证明**：

设 R 是 A 上的等价关系:

(1) 对任一 $x \in A$ ,因为R在A上自反,所以 $\langle x, x \rangle \in R$ 。由S定义, $\langle x, x \rangle \in S$ ,所以S是自反的。
(2) 对任意 x,  $y \in A$ , 若 $\langle x, y \rangle \in S$ , 则存在某个 c, 使得  $\langle x, c \rangle \in R \land \langle c, y \rangle \in R$ ,因为 R 对称,故有 $\langle y, c \rangle \in R \land \langle c, x \rangle \in R$ ,由 S 的定义,可知 $\langle y, x \rangle \in S$ ,所以 S 是对称的。
(3) 对任意  $x,y,z \in A$ ,若 $\langle x,y \rangle \in S$ ,及 $\langle y,z \rangle \in S$ ,则必存在某个  $c_1$ ,使 $\langle x,c_1 \rangle \in R$ , $\langle c_1,y \rangle \in R$ ,由 R 传递性,可知 $\langle x,y \rangle \in R$ 。同理存在  $c_2$ ,使 $\langle y,c_2 \rangle \in R \land \langle c_2,z \rangle \in R$ ,由 R 传递,可知 $\langle y,z \rangle \in R$ 。再由 S 定义,得 $\langle x,z \rangle \in S$ ,故 S 是传递的。

综上可知,S是A上的等价关系。

---
#### 3-113

> 设 R 是集合 A 上的一个自反关系,证明 :R 是等价 关系当且仅当若 $\langle a,b\rangle\in R$   $\land$   $\langle a,c\rangle\in R$  时,则 $\langle b,c\rangle\in R$  。

**证明**：

必要性 设 R 是 A 上等价关系,由对称性及传递条件,得  $\langle a,b\rangle \in R \land \langle a,c\rangle \in R \Rightarrow \langle b,a\rangle \in R \land \langle c,a\rangle \in R$   $\Rightarrow \langle b,c\rangle \in R$

充分性 设有

$\langle a,b\rangle \in R \land \langle a,c\rangle \in R \Rightarrow \langle b,c\rangle \in R$

且 R 是自反关系,则对任意  $a \in A$ ,必有 $\langle a,a \rangle \in R$ ,若  $\langle a,b \rangle \in R \land \langle a,a \rangle \in R \Rightarrow \langle b,a \rangle \in R$

故R是对称的。

对任意
$$a,b,c \in A$$
,若 $\langle a,b \rangle \in R \land \langle b,c \rangle \in R$ ,则必有
$$\langle b,a \rangle \in R \land \langle c,b \rangle \in R \Rightarrow \langle b,c \rangle \in R \land \langle b,a \rangle \in R$$

$$\Rightarrow \langle c,a \rangle \in R \Rightarrow \langle a,c \rangle \in R$$

故 R 是传递的,于是证明了 R 是一个等价关系。

---
#### 3-114

> 设 R 是集合 X 上的二元关系,对任意  $x_i, x_j, x_k \in X$ , 每当 $\langle x_i, x_j \rangle \in R \land \langle x_j, x_k \rangle \in R$  时,必有 $\langle x_k, x_i \rangle \in R$ ,则称 R 是循环的。试证:R 是等价关系,当且仅当 R 是自反和循环的。

**证明**：

设 R 是 X 上的等价关系,则对任意  $x_i, x_j, x_k \in X$ ,每 当 $\langle x_i, x_j \rangle \in R \land \langle x_j, x_k \rangle \in R$  时,必有 $\langle x_i, x_k \rangle \in R$ 。 因为 R 是对称的,故必有 $\langle x_k, x_i \rangle \in R$ 。

所以 R 是循环和自反的。

反之,设 R 是 X 上的自反和循环关系,对任意 $\langle x_i, x_j \rangle \in R$ ,由  $\langle x_i, x_i \rangle \in R$ ,得 $\langle x_i, x_i \rangle \in R$ ,所以 R 是对称的;再由

$\langle x_i, x_j \rangle \in R \land \langle x_j, x_k \rangle \in R \Rightarrow \langle x_k, x_i \rangle \in R \Rightarrow \langle x_i, x_k \rangle \in R$  故 R 是传递的。

于是 R 是 X 上的等价关系。

---
#### 3-115

> 假设给定了正整数的序偶集合 A,在 A 上定义二元 关系 R 如下: $\langle\langle x,y\rangle,\langle u,v\rangle\rangle\in R$ ,当且仅当 xv=yu,证明 R 是一个等价关系。 【3-10.(5)】

**证明**：

设A上定义的二元关系R为:

$$\langle\langle x,y\rangle,\langle u,v\rangle\rangle\in R\Leftrightarrow \frac{x}{y}=\frac{u}{v}$$

(1) 对任意
$$\langle x, y \rangle \in A$$
,因为 $\frac{x}{y} = \frac{x}{y}$ ,所以  $\langle \langle x, y \rangle, \langle x, y \rangle \rangle \in R$

即R是自反的。

(2) 设 $\langle x,y\rangle\in A,\langle u,v\rangle\in A$ ,若

$$\langle\langle x, y \rangle, \langle u, v \rangle\rangle \in R \Rightarrow \frac{x}{y} = \frac{u}{v} \Rightarrow \frac{u}{v} = \frac{x}{y}$$

$$\Rightarrow \langle\langle u, v \rangle, \langle x, y \rangle\rangle \in R$$

即 R 是对称的。

(3) 设任意 $\langle x, y \rangle \in A, \langle u, v \rangle \in A, \langle w, s \rangle \in A,$ 对  $\langle \langle x, y \rangle, \langle u, v \rangle \rangle \in R \land \langle \langle u, v \rangle, \langle w, s \rangle \rangle \in R$   $\Rightarrow \left(\frac{x}{y} = \frac{u}{v}\right) \land \left(\frac{u}{v} = \frac{w}{s}\right) \Rightarrow \frac{x}{y} = \frac{w}{s}$   $\Rightarrow \langle \langle x, y \rangle, \langle w, s \rangle \rangle \in R$

故R是传递的。

由

于是R是A上的等价关系。

---
#### 3-116

> 设 R 是集合 A 上对称和传递关系,证明如果对于 A 中每个元素 a,在 A 中同时也存在一个 b,使 $\langle a,b\rangle$ 在 R 之中,则 R 是一个等价关系。

**证明**：

对任意  $a\in A$ ,必存在一个  $b\in A$ ,使得 $\langle a,b\rangle\in R$ ,由 $b\in A$ ,必存在一个  $c\in A$ ,使得 $\langle b,c\rangle\in R$ 。因为 R 是传递和对称的,故

$$\langle a,b\rangle \in R \land \langle b,c\rangle \in R \Rightarrow \langle a,c\rangle \in R \Rightarrow \langle c,a\rangle \in R$$
$$\langle a,c\rangle \in R \land \langle c,a\rangle \in R \Rightarrow \langle a,a\rangle \in R$$

所以 R 在 A 上是自反的,即 R 是 A 上等价关系。

---
#### 3-117

> 设 R 是集合 A 上的一个传递和自反关系;T 是 A 上的一个关系,使得 $\langle a,b\rangle\in T$  当且仅当 $\langle a,b\rangle\in R$   $\land$   $\langle b,a\rangle\in R$ ,证明 T 是一个等价关系。

**证明**：

a) 对任意  $a \in A$ ,因 R 为 A 上自反关系,故有: $\langle a,a \rangle$   $\in R$ ,由 T 的充要条件,得到 $\langle a,a \rangle \in T$ 。

b) 对任意  $a,b \in A$ ,若

$$\langle a,b\rangle \in T \Leftrightarrow \langle a,b\rangle \in R \land \langle b,a\rangle \in R$$
$$\Leftrightarrow \langle b,a\rangle \in R \land \langle a,b\rangle \in R \Leftrightarrow \langle b,a\rangle \in T$$

所以T是对称的。

c) 对任意  $a,b,c \in A$ ,若有

$\langle a,b\rangle \in T \land \langle b,c\rangle \in T$

$\Rightarrow \langle a,b \rangle \in R \land \langle b,a \rangle \in R \land \langle b,c \rangle \in R \land \langle c,b \rangle \in R$

$\Rightarrow \langle a,b \rangle \in R \land \langle b,c \rangle \in R \land \langle c,b \rangle \in R \land \langle b,a \rangle \in R$

$\Rightarrow \langle a,c \rangle \in R \land \langle c,a \rangle \in R \Rightarrow \langle a,c \rangle \in T$

所以 T 是一个传递关系。

于是 T 是 A 上的等价关系。

---
#### 3-118

> 设  $R_1$  和  $R_2$  是非空集合 A 上的等价关系,试确定下述各式,哪些是 A 上的等价关系,对不是的式子,提供反例证明。
> - a)  $(A \times A) R_1$ ; b)  $R_1 R_2$ ;
> - c)  $R_1^2$ ; d)  $r(R_1-R_2)$  (即  $R_1-R_2$  的自反闭包)。
> [3-10.(7)]

**解**：

a)  $(A \times A) - R_1$  不是 A 上等价关系。例如:

$$A = \{a,b\}, \quad R_1 = \{\langle a,a\rangle, \langle b,b\rangle\}$$

$$A \times A = \{\langle a,a\rangle, \langle a,b\rangle, \langle b,a\rangle, \langle b,b\rangle\}$$

$$(A \times A) - R_1 = \{\langle a,b\rangle, \langle b,a\rangle\}$$

所以 $(A \times A) - R_1$  不是 A 上等价关系。

$$A = \{a,b,c\}$$

$$R_{1} = \{\langle a,b \rangle, \langle b,a \rangle, \langle b,c \rangle, \langle c,b \rangle, \langle a,c \rangle, \langle c,a \rangle, \langle a,a \rangle, \langle b,b \rangle, \langle c,c \rangle\}$$

$$R_{2} = \{\langle a,a \rangle, \langle b,b \rangle, \langle c,c \rangle, \langle b,c \rangle, \langle c,b \rangle\}$$

$$R_{1} - R_{2} = \{\langle a,b \rangle, \langle b,a \rangle, \langle a,c \rangle, \langle c,a \rangle\}$$

所以  $R_1$  和  $R_2$  是 A 上等价关系,但  $R_1-R_2$  不是 A 上等价关系。

c) 若  $R_1$  是 A 上等价关系,则

$$\langle a,a\rangle\in R_1\Rightarrow\langle a,a\rangle\in R_1\circ R_1$$

所以  $R_1^2$  是 A 上自反的。

若 $\langle a,b\rangle\in R_1^2$ 则存在 c,使得 $\langle a,c\rangle\in R_1$   $\wedge$   $\langle c,b\rangle\in R_1$ 。因  $R_1$  对称,故有

$$\langle b,c\rangle \in R_1 \land \langle c,a\rangle \in R_1 \Rightarrow \langle b,a\rangle \in R_1^2$$

即R<sup>2</sup>是对称的。

若 $\langle a,b\rangle \in R_1^2 \land \langle b,c\rangle \in R_1^2$ ,则有

$\langle b,a\rangle \in R_1^2 \land \langle c,b\rangle \in R_1^2$

故存在 e1,使得:

$$\langle b, e_1 \rangle \in R_1 \land \langle e_1, a \rangle \in R_1$$

同理存在 e2,使得:

$$\langle c, e_2 \rangle \in R_1 \land \langle e_2, b \rangle \in R_1$$

于是由  $R_1$  的传递性,可得到

$$\langle b,a\rangle \in R_1 \land \langle c,b\rangle \in R_1 \Leftrightarrow \langle c,b\rangle \in R_1 \land \langle b,a\rangle \in R_1$$

$$\Rightarrow \langle c,a\rangle \in R_1^2$$

即R<sup>2</sup>是传递的。

故 $R^2$  是 A 上的等价关系。

d) 如 b)所设, R1 和 R2 是 A 上等价关系, 但

$$r(R_1-R_2) = (R_1-R_2) \bigcup I_A$$

$$= \{\langle a,b\rangle, \langle b,a\rangle, \langle a,c\rangle, \langle c,a\rangle, \langle a,a\rangle, \langle b,b\rangle, \langle c,c\rangle\}$$

不是A上的等价关系。

---
#### 3-119

> 设  $C^*$  是实数部分非零的全体复数组成的集合, $C^*$  上关系 R 定义为: $(a+bi)R(c+di) \Leftrightarrow ac > 0$ ,证明 R 是等价关系,并给出关系 R 的等价类的几何说明。

**证明**：

(1) 对任意非零实数 a,有

$$a^2 > 0 \Leftrightarrow (a+bi)R(a+bi)$$

故R在C\*上是自反的

$$ca = ac > 0 \Leftrightarrow (c+di)R(a+bi)$$

所以R在C\*上是对称的。

(3) 设(a+bi)R(c+di)且(c+di)R(u+vi),则有

$$ac>0 \land cu>0$$

若 c>0,则

$$a>0 \land u>0 \Rightarrow au>0$$

若 c<0,则

$$a < 0 \land u < 0 \Rightarrow au > 0$$

所以(a+bi)R(u+vi),即 R 在  $C^*$  上是传递的。

关系 R 的等价类,就是在复数平面上第一、第四象限上的点,或第二、第三象限上的点,因为在这两种情况下,任意两个点 (a,b),(c,d),其横坐标乘积  $a \cdot c > 0$ 。

---
#### 3-120 设  $\delta$  是集合 X 上的等价关系的集合。试证:  $\bigcap$   $\delta$  是 一个 X 上的等价关系。

设  $S \in \delta \neq \emptyset$ ,则  $\bigcap \delta \subseteq S \subseteq X \times X$ 。对任意  $x \in X$ ,必对所有  $S \in \delta(S$  是等价关系),使得 $\langle x, x \rangle \in S$ ,故 $\langle x, x \rangle \in \bigcap \delta$ ,即  $\bigcap \delta$  是自反的。

对任意  $x,y \in X$ ,若 $\langle x,y \rangle \in \bigcap \delta$ ,则对所有  $S \in \delta$  有 $\langle x,y \rangle \in S$ ,因 S 是对称的,故对所有  $S \in \delta$  有 $\langle y,x \rangle \in S$ ,即 $\langle y,x \rangle \in \bigcap \delta$ ,所以  $\bigcap \delta$  是对称的。

对任意  $x,y,z \in X$ ,若 $\langle x,y \rangle \in \bigcap \delta$ , $\langle y,z \rangle \in \bigcap \delta$ ,则对所有 $S \in \delta$ ,有 $\langle x,y \rangle \in S \land \langle y,z \rangle \in S$ ,但 S 是传递的,故对所有  $S \in \delta$ ,有 $\langle x,z \rangle \in S$ ,即 $\langle x,z \rangle \in \bigcap \delta$ ,故 $\bigcap \delta$  是传递的。

于是 $\bigcap$  是 X 上的等价关系。

---
#### 3-121

> 设 R 是 A 上二元关系,令 R' = tsr(R),则
> - a) R'是 A 上的等价关系;
> - b) 若有等价关系 R'',使得  $R'' \supseteq R$ ,则  $R'' \supseteq R'$ ,即 R' 是包含 R 的最小等价关系。

**证明**：

a) 由定理 3-8.1 知 r(R) 是自反的,由习题 3-97 知 sr(R) 是自反和对称的,因此 tsr(R) 是自反和对称的,但 tsr(R) 是传递的,故 tsr(R) 是一个等价关系。

b) 设 R''是任意包含 R 的等价关系,则 R''是自反的,由闭包定义: $R'' \supseteq r(R)$ ,R''是对称的,故  $R'' \supseteq sr(R)$ ;R''是传递的,故  $R'' \supseteq tsr(R)$ 。

---
#### 3-122

> 试在复数集 C 中给出一个关系,使它是 C 的一个等价关系,并以此等价关系,构造 C 的划分。

**解**：

对所有  $\alpha$ , $\beta$   $\in$  C,设  $\alpha$  = a + bi, $\beta$  = c + di,定义关系 R:  $\alpha R\beta \Leftrightarrow \alpha^2 + b^2 = c^2 + d^2$

对任意  $\alpha \in C$ , 因为  $a^2 + b^2 = a^2 + b^2$ , 所以  $\alpha R\alpha$ , 即 R 是自 反的。

对任意  $\alpha,\beta \in C$ ,若  $\alpha R\beta$ ,则

$$a^2+b^2=c^2+b^2$$

即  $c^2+b^2=a^2+b^2$ ,故有  $\beta R\alpha$ ,即 R 是对称的。

对任意
$$\alpha, \beta, \gamma \in C, \alpha = a + bi, \beta = c + di, \gamma = e + fi,$$
则
$$\alpha R \beta \wedge \beta R \gamma \Rightarrow (a^2 + b^2 = c^2 + d^2) \wedge (c^2 + d^2 = e^2 + f^2)$$

$$\Rightarrow a^2 + b^2 = e^2 + f^2 \Rightarrow \alpha R \gamma$$

所以R是传递的。

于是 R 为等价关系。

关系 R 所决定的划分,是复平面上以原点为中心的圆的集合,即每个半径 r 对应一个等价类,该等价类为对应圆上点的集合。

---
#### 3-123

> 设  $\Pi$  为集合 A 的一个划分,R 是 A 上的等价关系,则  $\Pi$  诱导出 R,当且仅当 R 诱导出  $\Pi$ 。

**证明**：

必要性 假定  $\Pi$  诱导出 R ,且 R 诱导出一个划分  $\Pi'$  ,设任意  $a \in A$  ,令 B 和 B' 分别为  $\Pi$  和  $\Pi'$  的块,使得  $a \in B$  和  $a \in B'$  ,则对任意 b ,有

$$b \in B \Leftrightarrow aRb \Leftrightarrow [a]_R = [b]_R$$

因为 $[a]_R \in \Pi \land [a]_R \in \Pi'$ ,故 $[b]_R \in \Pi'$ ,且由

$$b \in B \Leftrightarrow [a]_R = [b]_R \Leftrightarrow b \in B'$$

因此 B=B'。由于  $\Pi$  和  $\Pi'$  取尽 A 的所有元素,因此  $\Pi=\Pi'$ 。

充分性 假定 R 诱导出  $\Pi$ ,且  $\Pi$  诱导出一个等价关系 R',则 对任意  $a,b \in A$ ,有

$$aRb \Leftrightarrow [a]_R = [b]_R \Leftrightarrow a \in [a]_R \land b \in [a]_R$$
$$\Leftrightarrow (\neg B)[B \in \Pi \land a \in B \land b \in B] \Leftrightarrow aR'b$$

因此 R=R'。

---
#### 3-124

> 设  $\Pi$  和  $\Pi'$  是非空集合 A 上的划分,并设 R 和 R' 分别由  $\Pi$  和  $\Pi'$  诱导的等价关系,那么  $\Pi'$  细分  $\Pi$  的充要条件是  $R' \subseteq R$ 。 【3-10.(9)】

**证明**：

若  $\Pi'$ 细分  $\Pi$ 。有假设 aR'b,则在  $\Pi'$ 中有某个块 S',使得  $a,b \in S'$ ,因  $\Pi'$ 细分  $\Pi$ ,故在  $\Pi$  中,必有某个块 S,使  $S' \subseteq S$ ,即  $a,b \in S$ ,于是有 aRb,即  $R' \subseteq R$ 。

反之,若
$$R' \subseteq R$$
,令  $S' 为  $\Pi'$ 的一个分块,且  $a \in S'$ ,则  $S' = \lceil a \rceil_{R'} = \{x \mid xR'a\}$$

但是对每一个 x,若 xR'a,因  $R'\subseteq R$ ,故 xRa,因此,

$$\{x \mid xR'a\} \subseteq \{x \mid xRa\}$$

即 $[a]_R \subseteq [a]_R$ 。设  $S = [a]_R$ ,则  $S \neq \Pi$  的一个分块,且  $S' \subseteq S$ 。 这就证明了  $\Pi'$ 细分  $\Pi$ 。

---
#### 3-125

> 设  $R_i$  表示 I 上模 i 等价关系, $R_k$  表示 I 上模 k 等价关系,证明: $I/R_k$  细分  $I/R_i$ ,当且仅当 k 是 i 的整数倍。
> [3-10.(10)]

**证明**：

由题设

$$R_{j} = \{\langle x, y \rangle \mid x \equiv y \pmod{j}\}$$

$$R_{k} = \{\langle x, y \rangle \mid x \equiv y \pmod{k}\}$$

故

$$\langle x,y \rangle \in R_j \Leftrightarrow x-y=c_j$$
(对某个  $c \in I$ )
$\langle x,y \rangle \in R_k \Leftrightarrow x-y=dk$  (对某个  $d \in I$ )

a) 假设  $I/R_k$  细分  $I/R_j$ ,则  $R_k \subseteq R_j$ ,因此

$$\langle k, 0 \rangle \in R_k \Rightarrow \langle k, 0 \rangle \in R_j$$

故

$$k-0=1 \cdot k=c \cdot i$$
(对某个  $c \in I$ )

于是 k 是 i 的整数倍。

b) 若对某个  $r \in I$ ,有 k = ri,则

$$\langle x,y \rangle \in R_k \Leftrightarrow (x-y) = ck($$
对某个  $c \in I$ )
$\Rightarrow (x-y) = crj($ 对某个  $c,r \in I$ )
$\Rightarrow \langle x,y \rangle \in R_i$

因此  $R_k \subseteq R_i$ ,于是  $I/R_k$  细分  $I/R_i$ 。

---
#### 3-126

> 设  $R_1$  和  $R_2$  是非空集合 A 的划分  $\Pi_1$  和  $\Pi_2$  所诱导出的等价关系。那末  $R=R_1\cap R_2$  诱导出  $\Pi_1$  和  $\Pi_2$  的积划分为  $\Pi_2$

**证明**：

因为  $R=R_1 \cap R_2$ ,故  $R_1 \supseteq R \wedge R_2 \supseteq R$ 。根据习题3-124  $\Pi$  细分  $\Pi_1$  和  $\Pi_2$ 。

如果有另一划分  $\Pi'$ ,细分  $\Pi_1$  和  $\Pi_2$ ,且  $\Pi'$ 诱导出 R',则根据习

$$R_1 \supseteq R' \land R_2 \supseteq R' \Rightarrow R_1 \cap R_2 \supseteq R'$$

即有  $R \supseteq R'$ ,故  $\Pi'$ 细分  $\Pi$ 。

上述结果根据划分积的定义,可知  $\Pi = \Pi_1 \cdot \Pi_2$ 。

---
#### 3-127

> 设  $R_1$  和  $R_2$  是非空集合 A 上的划分  $\Pi_1$  和  $\Pi_2$  所诱导出的等价关系,定义  $R_1 \cup R_2$  的传递闭包为
> $$R = (R_1 \bigcup R_2)^+ = t(R_1 \bigcup R_2)$$
> 试证: $R \neq A$  上的等价关系,且划分  $A/R \neq \Pi_1$  和  $\Pi_2$  的和。

**证明**：

因为  $R_1$  和  $R_2$  是 A 上的等价关系,故很容易证明  $R_1 \cup R_2$  是自反和对称的,故  $R_1 \cup R_2 = r(R_1 \cup R_2)$  且有

$$s(R_1 \cup R_2) = R_1 \cup R_2$$
,  $g = rs(R_1 \cup R_2) = R_1 \cup R_2$

所以

$$R=t(R_1 \cup R_2)=trs(R_1 \cup R_2)$$

由习题 3-121 知,R 是包含  $R_1$  和  $R_2$  的最小等价关系。其诱导的 划分为 A/R。因为  $R \supseteq R_1$ , $R \supseteq R_2$ ,故  $II_1$  和  $II_2$  细分 A/R。

设有  $\Pi'$ 被  $\Pi_1$  和  $\Pi_2$  细分,则  $\Pi'$ 诱导的等价关系 R'必满足:

$$R' \supseteq R_1 \land R' \supseteq R_2 \Rightarrow R' \supseteq R_1 \bigcup R_2$$

仴

$$R=t(R_1 \cup R_2)=trs(R_1 \cup R_2)$$

其是包含  $R_1$  和  $R_2$  的最小等价关系,故  $R' \supseteq t(R_1 \cup R_2)$ ,即 A/R 细分  $\Pi'$ 。

由上述证明,可知 A/R 是  $\Pi_1$  和  $\Pi_2$  的和。

---
#### 3-128

> 设  $R_j$  表示 I 上的模 j 等价, $R_k$  表示 I 上的模 k 等价,描述
> - a) 划分  $I/R_i + I/R_k$ ;
> - b) 划分 I/R; · I/Rk。

**解**：

a) 设 d 为 j 和 k 的最大公约数, $R_d$  为 I 上的模 d 等价,则  $I/R_d = I/R_i + I/R_k$ ;

b) 设m 为j 和k 的最小公倍数, $R_m$  表示 I 上的模m 等价,则  $I/R_m = I/R_i \cdot I/R_k$ 。

---
#### 3-129

> 设  $\Pi_1$  和  $\Pi_2$  是非空集合 A 的划分,则  $\Pi_1$  和  $\Pi_2$  的积 是唯一的。

**证明**：

假设  $\Pi=\Pi_1 \cdot \Pi_2$ , $\Pi'=\Pi_1 \cdot \Pi_2$ ,根据划分积的定义,应有  $\Pi$  细分  $\Pi'$ ,且  $\Pi'$  细分  $\Pi$ ,若  $\Pi$  和  $\Pi'$  分别诱导等价关系为 R 和 R',则应有

$$R \subseteq R' \land R' \subseteq R \Rightarrow R = R'$$

由习题 3-123 可知 Ⅱ=Ⅱ′。

所以  $\Pi_1$  和  $\Pi_2$  的积必是唯一的。

---
#### 3-130

> 设R是X上二元关系,试证明: $\alpha=I_X$   $\cup R$   $\cup R^c$  是X 上相容关系。 【3-11.(1)】

**证明**：

设  $\alpha = I_X \cup R \cup R^c$ ,则  $\alpha = I_X \cup s(R) = rs(R)$ 。因为 s(R)在 X上对称,故有:

$$\langle x, y \rangle \in I_X \cup s(R) \Leftrightarrow \langle x, y \rangle \in I_X \vee \langle x, y \rangle \in s(R)$$
$$\Leftrightarrow \langle y, x \rangle \in I_X \vee \langle y, x \rangle \in s(R)$$
$$\Leftrightarrow \langle y, x \rangle \in I_X \cup s(R)$$

所以  $I_X \cup s(R) = rs(R)$ 在 X 上是对称的。

因为 rs(R) 是自反的,所以  $\alpha = rs(R)$  是 X 上的相容关系。

---
#### 3-131

> 给定集合  $X = \{x_1, x_2, \dots, x_6\}, R$  是 X 上的相容关系,且  $M_R$  简化矩阵为:
> $$\begin{array}{c|ccccccccccccccccccccccccccccccccccc$$
> ![](_page_44_Picture_12.jpeg)
> 试求出 X 的完全覆盖,并画出相容关系图。
> [3-11.(2)]

**解**：

根据给定的相容关系矩阵,可画出相容关系图如图 3-14 所示,由图可得 X 的完全覆盖:

$$\Pi = \{\{x_1, x_2, x_3\}, \{x_1, x_3, x_6\}, \{x_3, x_5, x_6\}, \{x_3, x_4, x_5\}\}$$

---
#### 3-132

> 给定 X 上相容关系 R,证明:  $\bigcup_{i=1}^{\infty} R^i$  为 X 上的等价 关系。

**证明**：

设R是X上的一个相容关系,故R是自反和对称的。

式
$$\bigcup_{i=1}^{\infty} R^{i} = t(R)$$

由习题 3-97 知 t(R)是自反和对称的,且 t(R)根据定义是传递的。 所以当 R 是相容关系时,t(R)是 X 上的等价关系。

---
#### 3-133

> 设  $C=\{A_1,A_2,\cdots,A_n\}$  为集合 A 的覆盖,试由此覆 盖确定 A 上的一个相容关系。并说明在什么条件下,此相容关系 为等价关系。 【3-11.(4)】

**解**：

此覆盖确定 A 上的相容关系:

$$R = A_1 \times A_1 \cup A_2 \times A_2 \cup \cdots \cup A_n \times A_n$$

因为
$$A = \bigcup_{i=1}^{n} A_i$$
,对任一  $x \in A$ ,必有某个  $j > 0$ ,使  $x \in A_j$ ,故  $\langle x, x \rangle \in A_i \times A_i \Rightarrow \langle x, x \rangle \in R$

所以 R 在 A 上是自反的。

对任意  $x,y \in A$ ,若有 $\langle x,y \rangle \in R$ ,必有某个 k > 0,使得  $\langle x,y \rangle \in A_k \times A_k \Rightarrow \langle y,x \rangle \in A_k \times A_k \Rightarrow \langle y,x \rangle \in R$  所以 R 在 A 上是对称的。

这说明 R 是 A 上的一个相容关系。

一般地说,R 在 A 上不一定是传递的。因为若有 $\langle x,y \rangle \in A_i$   $\times A_i$ , $\langle y,z \rangle \in A_j \times A_j$ ,这里  $i \neq j$  而  $y \in A_i \cap A_j$ , $x \in A_i$ , $z \in A_j$ ,故  $\langle x,z \rangle$ 不一定在 R 中,只有当此覆盖是 A 的划分时,此相容关系 R 为在 X 上的等价关系。

---
#### 3-134

> 设  $A=\{1,2,3,4,5,6\}$ 上有关系  $\beta=\{\langle 1,2\rangle,\langle 1,3\rangle,\langle 2,3\rangle,\langle 2,4\rangle,\langle 3,4\rangle,\langle 2,5\rangle,\langle 4,5\rangle,\langle 3,6\rangle,\langle 4,6\rangle\}$ ,试说明:至少有 A 的两个不同覆盖可产生
> $$\alpha = I_X \cup \beta \cup \beta^c \qquad [3-11.(5)]$$

**解**：

$$\alpha = \{\langle 1,2 \rangle, \langle 2,1 \rangle, \langle 1,3 \rangle, \langle 3,1 \rangle, \langle 2,3 \rangle, \langle 3,2 \rangle, \langle 2,4 \rangle, \langle 4,2 \rangle, \langle 3,4 \rangle, \langle 4,3 \rangle, \langle 2,5 \rangle, \langle 5,2 \rangle, \langle 4,5 \rangle, \langle 5,4 \rangle, \langle 3,6 \rangle, \langle 6,3 \rangle, \langle 4,6 \rangle, \langle 6,4 \rangle, \langle 1,1 \rangle, \langle 2,2 \rangle, \langle 3,3 \rangle, \langle 4,4 \rangle, \langle 5,5 \rangle, \langle 6,6 \rangle \}$$

$$S_1 = \{\{1,2,3\},\{2,4,5\},\{3,4,6\}\}\}$$

$$S_2 = \{\{1,2,3\},\{2,4\},\{2,5\},\{4,5\},\{3,4,6\}\}\}$$

$S_1$  和  $S_2$  都可产生相容关系  $\alpha$ 。

---
#### 3-135

> 设  $\alpha$  和  $\beta$  是 A 上相容关系,试说明:
> - a) 复合关系  $\alpha \circ \beta$  是 A 上相容关系吗?
> - b) αUβ是A上相容关系吗?
> - c)  $\alpha \cap \beta$  是 A 上相容关系吗?
> [3-11.(6)]

**解**：

a) 设
$$\alpha = \{\langle a, a \rangle, \langle b, b \rangle, \langle c, c \rangle, \langle a, b \rangle, \langle b, a \rangle\}$$

$\beta = \{\langle a, a \rangle, \langle b, b \rangle, \langle c, c \rangle, \langle a, c \rangle, \langle c, a \rangle\}$
$\alpha \circ \beta = \{\langle a, a \rangle, \langle a, c \rangle, \langle b, b \rangle, \langle c, c \rangle, \langle c, a \rangle, \langle a, b \rangle, \langle b, a \rangle, \langle b, c \rangle\}$ 。

所以  $\alpha,\beta$  是相容关系,但  $\alpha^{\circ}\beta$  不是相容关系。

b) 对任意  $\alpha \in A$ ,因为 $\langle a,a \rangle \in \alpha$ , $\langle a,a \rangle \in \beta$ ,故 $\langle a,a \rangle \in \alpha \cup \beta$ , 即  $\alpha \cup \beta \in A$  上自反的。

对任意  $a,b \in A$ ,如果有 $\langle a,b \rangle \in \alpha \cup \beta$ ,则 $\langle a,b \rangle \in \alpha$  或 $\langle a,b \rangle \in \beta$ ,因  $\alpha,\beta$ 在 A 上对称,故

$$\langle b,a\rangle \in \alpha$$
ø  $\langle b,a\rangle \in \beta \Rightarrow \langle b,a\rangle \in \alpha \cup \beta$

所以  $\alpha \cup \beta$  在 A 上对称,于是  $\alpha \cup \beta$  是 A 上相容关系。

c) 对任意  $\alpha \in A$ ,因 $\langle a,a \rangle \in \alpha \land \langle a,a \rangle \in \beta$ ,故 $\langle a,a \rangle \in \alpha \cap \beta$ ,即  $\alpha \cap \beta \in A$  上自反关系。

对任意
$$a,b \in A$$
,若 $\langle a,b \rangle \in \alpha \cap \beta$ ,则有
$$\langle a,b \rangle \in \alpha \wedge \langle a,b \rangle \in \beta \Rightarrow \langle b,a \rangle \in \alpha \wedge \langle b,a \rangle \in \beta$$

$$\Rightarrow \langle b,a \rangle \in \alpha \cap \beta$$

即  $\alpha \cap \beta$  在 A 上对称。

所以 $\alpha \cap \beta$ 是A上相容关系。

---
#### 3-136

> 设集合为{3,5,15},{1,2,3,6,12},{3,9,27,54}。
> ![](_page_45_Figure_20.jpeg)
> 其上面的偏序关系为整除,画出这些集合的偏序关系图,并指出哪 些是全序关系。

**解**：

关系图如图 3-15 所示。

集合{3,9,27,54}上的整除关系是全序关系。

---
#### 3-137

> 设 R 是 A 上二元关系,如果 R 是传递和反自反的,则称 R 是拟序关系。证明:
> - a) 如果 R 是 A 上拟序关系,则  $r(R) = R \cup I_A$  是偏序关系。
> - b) 如果 R 是一偏序关系,则  $R-I_A$  是一拟序关系。
> [3-12,(2)]

**证明**：

a) 对任意  $a \in A$ ,因为 $\langle a,a \rangle \in I_A$ ,所以

$$\langle a,a\rangle\in(R\bigcup I_A)=r(R)$$

故r(R)是A上自反的。

对任意  $a,b \in A$ ,若有 $\langle a,b \rangle \in r(R)$ ,则

$\langle a,b\rangle\in R \vee \langle a,b\rangle\in I_A$

当a=b时, $\langle a,b\rangle \in I_A$ 。

当  $a \neq b$  时,  $\langle a,b \rangle \in R$ 。如果另有 $\langle b,a \rangle \in R$ ,则因 R 是传递的,故必有 $\langle a,a \rangle \in R$ ,这与 R 是反自反相矛盾。所以当  $a \neq b$  时,

$$\langle a,b\rangle\in R\Rightarrow\langle b,a\rangle\notin R$$

故(b,a) ∉ r(R),即 r(R) 是反对称的。

另外,对任意  $a,b,c \in A$ ,若 $\langle a,b \rangle \in r(R) \land \langle b,c \rangle \in r(R)$ ,则有  $\langle a,b\rangle \in R \cup I_A \land \langle b,c\rangle \in R \cup I_A$ , to

$\langle a,b\rangle \in R \vee \langle a,b\rangle \in I_A$

目

$\langle b,c\rangle \in R \vee \langle b,c\rangle \in I_A$

因为 R 是反自反的,故  $a \neq b \land b \neq c$ ,即

$\langle a,b\rangle \notin I_A, \langle b,c\rangle \notin I_A$

故

$\langle a,b\rangle \in r(R) \land \langle b,c\rangle \in r(R) \Rightarrow \langle a,b\rangle \in R \land \langle b,c\rangle \in R$  $\Rightarrow \langle a,c \rangle \in R \Rightarrow \langle a,c \rangle \in r(R)$

即 r(R) 为传递的,于是 r(R) 为 A 上的偏序关系。

b) 设 R 为偏序关系,对任意  $a \in A$ ,如果 $\langle a,a \rangle \in R - I_A$ ,则必 有 $\langle a,a\rangle$  ∈  $R \land \langle a,a\rangle \notin I_A$  矛盾。故对任意  $a \in A$ ,必有 $\langle a,a\rangle \notin$  $R-I_A$ ,所以  $R-I_A$  是反自反的。

设 $a,b,c \in A$ ,若 $\langle a,b \rangle \in R-I_A$ , $\langle b,c \rangle \in R-I_A$ ,则  $\langle a,b\rangle \in R \land \langle a,b\rangle \notin I_A \land \langle b,c\rangle \in R \land \langle b,c\rangle \notin I_A$

为此,必须  $a \neq b \neq c$ 。所以 $\langle a,b \rangle \in R - I$ 。和 $\langle b,c \rangle \in R - I$ 。可推出  $\langle a,b\rangle \in R \land \langle b,c\rangle \in R \Rightarrow \langle a,c\rangle \in R$

$(a,c) \notin I_A$ ,所以 $(a,c) \in R - I_A$ ,即  $R - I_A$  是传递的。

于是 $R-I_{\Delta}$  为拟序关系。

---
#### 3-138

> 设 R 是 X 上的二元关系:
> - a) 证明 R 是拟序,当且仅当  $R \cap R' = \emptyset$ 和  $R = R^+$ :
> - b) 证明 R 是偏序,当且仅当  $R \cap R' = I_x$  和 R = R'.

**证明**：

a) 若 R 是 X 上的一个拟序关系,则 R 是反自反和传 递的。由定理 3-8.1 得  $R=t(R)=R^+$ 。

对任意 $\langle x,y\rangle \in R$ ,如果 $\langle x,y\rangle \in R$ ,则 $\langle y,x\rangle \in R$ ,由 R 的传 递性得到 $\langle x,x\rangle \in R$ ,这与 R 的反自反性矛盾,故对任意 $\langle x,v\rangle \in R$  $R, 则\langle x, y \rangle \notin R'$ 。所以

$$R \cap R^c = \emptyset$$

反之,若 $R \cap R^c = \emptyset$ ,且 $R = R^+$ ,则R必是反自反的。因为对

任意  $x \in X$ ,如果有 $\langle x, x \rangle \in R$ ,则必有 $\langle x, x \rangle \in R$ ,这与  $R \cap R' =$ Ø矛盾,故对任意  $x \in X$ ,必定是 $\langle x, x \rangle \notin R$ ,又因为  $R = R^+$ ,故由 定理 3-8.1 得 R 是传递的,即 R 是拟序。

b) 如果 R 是 X 上的一个偏序关系,则 R 是自反、传递和反 对称的,由定理 3-8.1 得 R=r(R)和 R=t(R),所以 R=tr(R),即  $R=R^*$

又 R 是自反的,故对任意  $x \in X$ ,有 $\langle x,x \rangle \in R$ ,且有 $\langle x,x \rangle \in$ R',故 $\langle x,x\rangle \in R \cap R'$ 。对任意  $x,y \in X$ ,若  $x \neq y$ :

① 如果 $\langle x, y \rangle \in R$ ,因 R 反对称,必有 $\langle y, x \rangle \notin R$ ,即  $\langle x, y \rangle \in R \Rightarrow \langle x, y \rangle \notin R^c$

所以 $\langle x,y\rangle \in R$  时, $\langle x,y\rangle \notin R \cap R^c$ 。

② 如果 $\langle x, y \rangle \notin R$ ,则 $\langle x, y \rangle \notin R \cap R^c$ .

综上所述

$R \cap R^c = I_x$

反之,如果  $R \cap R^c = I_X$ ,且  $R = R^+$ ,则对任意  $x \in X$ ,因为  $\langle x,x\rangle \in I_X$ ,  $\mathbb{D}\langle x,x\rangle \in R \cap R^c$ ,  $\mathbb{T} = \{x,x\} \in R \land \langle x,x\rangle \in R^c$ ,  $\mathbb{T} \in R^c$ 是自反的。

对任意  $x, y \in X$ ,如果  $x \neq y$ 。设 $\langle x, y \rangle \in R$  时有 $\langle y, x \rangle \in R$ ,则  $\langle x,y\rangle \in R^{\epsilon}$ ,这样 $\langle x,y\rangle \in R \cap R^{\epsilon}$ ,故 $\langle x,y\rangle \in I_{x}$ 矛盾。所以

$$\langle x,y\rangle\in R\Rightarrow\langle y,x\rangle\notin R$$

故 R 是反对称的。因为 R=tr(R),由传递闭包定义,可知 R 是传 递的。

所以R是X上的偏序关系。

---
#### 3-139

> 设 R 是集合 S 上的关系, S'是 S 的子集, 定义 S'上 关系 R'如下,
> $$R'=R\cap (S'\times S')$$
> 确定下述每一断言是真还是假。
> - a) 如果 R 在 S 上是传递的,那么 R'在 S'上是传递的。
> - b) 如果  $R \neq S$  上的偏序关系,那么  $R' \neq S'$  上的偏序关系。
> - c) 如果 R 是 S 上的拟序关系,那么 R'是 S'上的拟序关系。
> - d) 如果 R 是 S 上的线序关系,那么 R'是 S'上的线序关系。
> - e) 如果 R 是 S 上的良序关系,那么 R' 是 S' 上的良序关系。 【3-12.(3)】

**解**：

对任意  $a,b,c \in S'$ ,因  $S' \subseteq S$ ,故  $a,b,c \in S$ 。
a) 若有 $\langle a,b\rangle \in R', \langle b,c\rangle \in R', 因 R' = R \cap (S' \times S')$ ,得到  $\langle a,b\rangle \in R \cap (S' \times S') \Rightarrow \langle a,b\rangle \in R \wedge \langle a,b\rangle \in S' \times S'$   $\Rightarrow \langle a,b\rangle \in R \wedge a \in S' \wedge b \in S'$

同理

$\langle b,c \rangle \in R \cap (S' \times S') \Rightarrow \langle b,c \rangle \in R \land b \in S' \land c \in S'$ 因  $R \in S$ 上传递,故

$$\langle a,b\rangle \in R' \land \langle b,c\rangle \in R' \Rightarrow \langle a,c\rangle \in R \land a \in S' \land c \in S'$$
$$\Rightarrow \langle a,c\rangle \in R \cap (S' \times S')$$
$$\Rightarrow \langle a,c\rangle \in R'$$

所以 R'在 S'上是传递的。

b) 对任意  $a \in S'$ ,因  $S' \subseteq S$ ,故  $a \in S$ ,由 $\langle a,a \rangle \in R$  且 $\langle a,a \rangle \in R$  ( $S' \times S'$ )得到 $\langle a,a \rangle \in R'$ 即 R'在 S 上是自反的。若有  $a,b \in S'$ 且  $a \neq b$ ,则对任意

$$\langle a,b\rangle \in R' \Rightarrow \langle a,b\rangle \in R \land \langle a,b\rangle \in S' \times S'$$

因 R 是反对称的,故必有

$$\langle b,a\rangle \notin R \Rightarrow \langle b,a\rangle \notin R'$$

所以 R'在 S'上是反对称的。由 a)中证得 R'在 S'上是传递的。 于是 R'是 S'上的偏序关系。

c) 对任意  $a \in S' \subseteq S$ ,因为 $\langle a,a \rangle \notin R$ ,所以 $\langle a,a \rangle \notin R \cap (S' \times S')$ ,得到 $\langle a,a \rangle \notin R'$ ,即 R'在 S'上是反自反的。由 a)知 R'在 S'上是传递的,故 R'是 S'上的拟序关系。
d) 设任意  $a,b \in S'$ ,如果  $R \neq S$  上线序关系,故必有  $\langle a,b \rangle \in R \lor \langle b,a \rangle \in R$

即 $\langle a,b\rangle \in R \cap (S' \times S'), \langle b,a\rangle \in R \cap (S' \times S')$ 亦即 $\langle a,b\rangle \in R'$ 或 $\langle b,a\rangle \in R'$ ,所以 R'为 S'上线序关系。

e)设 $\langle S,R \rangle$ 为良序集,若 $\langle S',R' \rangle$ 不是良序集,则必有  $S' \subseteq S'$ 且  $S'' \neq \emptyset$ ,使得 $\langle S'',R' \rangle$ 中不存在最小元,即对任意  $a \in S'$

必有 $b \in S''$ ,使得 $\langle a, b \rangle \in S' \times S''$ ,即 $\langle a, b \rangle \in S' \times S'$ ,但 $\langle a, b \rangle \notin R'$ 。

因为  $R'=R\cap (S'\times S')$ ,故 $\langle a,b\rangle \notin R$ ,但  $S'\subseteq S'\subseteq S$ ,这说明在 S 中存在非空子集 S'',对所有  $a\in S''$ 都存在  $b\in S''$ ,使 $\langle a,b\rangle \notin R$ ,这与 $\langle S,R\rangle$ 是良序集矛盾。于是证得 $\langle S',R'\rangle$ 是良序集。

---
#### 3-140

> 找出在集合{0,1,2,3}上包含序偶〈0,3〉和〈2,1〉的 线序关系。
> $$\mathbf{R} = \{\langle 0,0\rangle, \langle 2,2\rangle, \langle 1,1\rangle, \langle 3,3\rangle, \langle 0,2\rangle, \\ \langle 0,1\rangle, \langle 0,3\rangle, \langle 2,1\rangle, \langle 2,3\rangle, \langle 1,3\rangle\}$$
> 其哈斯图见图 3-16 所示。
> ![](_page_47_Figure_21.jpeg)
---
#### 3-141

> 构造下列集合的例子:
> - a) 非空线性集,其中某些子集没有最小元素;
> - b) 非空偏序集,它不是线序集,其中某些子集没有最大元:
> - c) 一个偏序集有一个子集,它存在一个最大下界,但没有最小元素;
> - d) 一偏序集有一子集,它存在一个上界,但没有最小上界。 【3-12.(5)】

**解**：

a)非负实数集上的小于等于关系,构成 $\langle R_+, \prec\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!$
b) 如图 3-17 所示哈斯图中,子集{a, b, c, d, e}, 没有最大元。

c) 如图 3-17 所示,子集 $\{d, e, f, g\}$ ,有一最大下界,但没有最小元素。
d) 图中 $\{a,b,c,d,e\}$ 有一上界  $f(\mathbf{d},g)$ ,但没有最小上界。

![](_page_48_Picture_2.jpeg)

---
#### 3-142

> 设集合  $P = \{x_1, x_2, x_3, x_4, x_5\}$ 上的偏序关系如图 3-18 所示,找出 P的最大元素,最小元素,极小元素,极大元素。找出子集 $\{x_2, x_3, x_4\}$ , $\{x_3, x_4, x_5\}$ 和 $\{x_1, x_2, x_3\}$ 的上界,下界,上确界,下确界。
> 图 3-18

**解**：

P 的最大元素为 $x_1$ ,无最小元

素。极大元素为  $x_1$ ,极小元素为  $x_4$ , $x_5$ 。其余如下表:

| 子 集                 | 上 界                | 下 界                   | 上确界   | 下确界   |
|---------------------|--------------------|-----------------------|-------|-------|
| $\{x_2, x_3, x_4\}$ | $\boldsymbol{x}_1$ | *x* <sub>4</sub> | $x_1$ | $x_4$ |
| $\{x_3, x_4, x_5\}$ | $x_1, x_3$         | 无                     | $x_3$ | 无     |
| $\{x_1, x_2, x_3\}$ | $x_1$              | $x_4$                 | $x_1$ | $x_4$ |

---
#### 3-143

> 图 3-19 给出了集合{1,2,3,4}上的四个偏序关系图,画出它们的哈斯图,并说明哪一个是全序关系,哪一个是良序关系。 【3-12.(7)】

**解**：

设 $A = \{1,2,3,4\}$ ,四个偏序关系为 $R_1,R_2,R_3,R_4$ ,其哈斯图如图 3-20 所示。

a)
$$R_1 = \{\langle 1,1 \rangle, \langle 2,2 \rangle, \langle 3,3 \rangle, \langle 4,4 \rangle, \langle 1,2 \rangle, \langle 1,3 \rangle, \langle 4,1 \rangle, \langle 4,3 \rangle, \langle 4,2 \rangle\}$$

$COV(A) = \{\langle 1,2 \rangle, \langle 1,3 \rangle, \langle 4,1 \rangle\}$

b)
$$R_2 = \{\langle 1,1 \rangle, \langle 2,2 \rangle, \langle 3,3 \rangle, \langle 4,4 \rangle, \langle 1,3 \rangle, \langle 1,4 \rangle, \langle 2,3 \rangle, \langle 2,4 \rangle\}$$

$$COV(A) = \{\langle 1,3 \rangle, \langle 1,4 \rangle, \langle 2,3 \rangle, \langle 2,4 \rangle\}$$

c)
$$R_3 = \{\langle 1, 1 \rangle, \langle 2, 2 \rangle, \langle 3, 3 \rangle, \langle 4, 4 \rangle, \langle 3, 1 \rangle, \langle 3, 4 \rangle, \langle 3, 2 \rangle, \langle 1, 2 \rangle, \langle 4, 2 \rangle, \langle 4, 1 \rangle\}$$

$COV(A) = \{\langle 1, 2 \rangle, \langle 3, 4 \rangle, \langle 4, 1 \rangle, \langle 3, 1 \rangle\}$

![](_page_48_Figure_14.jpeg)

图 3-19

![](_page_48_Figure_16.jpeg)

$R_3$  是全序关系,也是良序关系。

d)
$$R_4 = \{\langle 1, 1 \rangle, \langle 2, 2 \rangle, \langle 3, 3 \rangle, \langle 4, 4 \rangle, \langle 3, 1 \rangle, \langle 4, 3 \rangle, \langle 4, 1 \rangle, \langle 4, 2 \rangle\}$$

$COV(A) = \{\langle 3, 1 \rangle, \langle 4, 3 \rangle, \langle 4, 2 \rangle\}$

---
#### 3-144

> 画出集合  $S=\{1,2,3,4,5,6\}$  在偏序关系"整除"下的哈斯图,并讨论:
> - a) 写出{1,2,3,4,5,6}的极大元,极小元,最大元,最小元。
> - b) 分别写出 $\{2,3,6\}$ 及 $\{2,3,5\}$ 的上界,下界,上确界,下确界。

**解**：

设≼为整除关系:

"
$$=$$
{ $\langle 1,2 \rangle$ , $\langle 1,3 \rangle$ , $\langle 1,4 \rangle$ , $\langle 1,5 \rangle$ , $\langle 1,6 \rangle$ ,
$\langle 2,4 \rangle$ , $\langle 2,6 \rangle$ , $\langle 3,6 \rangle$ , $\langle 1,1 \rangle$ , $\langle 2,2 \rangle$ ,
$\langle 3,3 \rangle$ , $\langle 4,4 \rangle$ , $\langle 5,5 \rangle$ , $\langle 6,6 \rangle$ }

在偏序集 $\langle S, \preccurlyeq \rangle$ 中,

$$COV(S) = \{\langle 1,2 \rangle, \langle 1,3 \rangle, \langle 1,5 \rangle, \langle 2,4 \rangle, \langle 2,6 \rangle, \langle 3,6 \rangle\}$$

![](_page_49_Figure_7.jpeg)

其哈斯图如图 3-21 所示。

a) {1,2,3,4,5,6},在"整除"

关系中

极大元:6,5,4

极小元:1

最大元:没有

最小元:1

b) {2,3,6}的上界为6,上确界为6。
{2,3,6}的下界为1,下确界为1。
{2,3,5}的上界没有,上确界没有。
{2,3,5}的下界为1,下确界为1。

---
#### 3-145

> 设 X 上二元关系 R,若 R 满足反自反、反对称和传递性质,则称 R 为 X 上的严格序关系。证明:若 S 为 X 上偏序关系,则 S  $I_X$  是 X 上的严格序关系;若 S 为 X 上的一个严格序,则 S  $\bigcup$   $I_X$  是一个 X 上的偏序关系。

**证明**：

a) 设  $S \supset X$  上的偏序关系,则  $S \subseteq X \times X$ ,故  $S I_X \subseteq X \times X$ ,对任意  $x \in X$ ,则 $\langle x, x \rangle \in I_X$ ,因此 $\langle x, x \rangle \notin S I_X$ ,故  $S I_X$  是反自反的。

又若  $\langle x,y\rangle \in S-I_X \land \langle y,x\rangle \in S-I_X$

$\langle x,y\rangle \in S \land \langle y,x\rangle \in S \Rightarrow x = y$

即  $S-I_X$  是反对称的。

设  $\langle x,y\rangle \in S-I_X \land \langle y,z\rangle \in S-I_X$

则 $\langle x,y\rangle \in S \land \langle y,z\rangle \in S$ ,因 S 是传递的,故 $\langle x,z\rangle \in S$ 。

当  $x\neq z$  时,  $\langle x,z\rangle \in S-I_x$

当 x=z 时,  $\langle x,y\rangle \in S \land \langle y,z\rangle \in S \Rightarrow x=y$

若设 $\langle x,y\rangle \in S-I_X$ ,则 $\langle x,y\rangle \notin I_X \Rightarrow x\neq y$ 矛盾。

所以  $S-I_x$  是传递的。

b) 若 S 为 X 上的一个严格序,则对任意  $x \in X$ , $\langle x, x \rangle \notin S$ , 但 $\langle x, x \rangle \in I_X$ ,故 $\langle x, x \rangle \in S \cup I_X$ ,即  $S \cup I_X$  是自反的。

对任意  $x, y \in X$ ,若 $\langle x, y \rangle \in S \cup I_X \land \langle y, x \rangle \in S \cup I_X$ ,则

$(\langle x,y\rangle \in S \vee \langle x,y\rangle \in I_X) \wedge (\langle y,x\rangle \in S \vee \langle y,x\rangle \in I_X)$

$\Rightarrow (\langle x, y \rangle \in S \land \langle y, x \rangle \in S)$

$\forall (\langle x,y\rangle \in S \land \langle y,x\rangle \in I_X)$

$\forall (\langle x,y\rangle \in I_X \land \langle y,x\rangle \in S)$

$\forall (\langle x,y\rangle \in I_X \land \langle y,x\rangle \in I_X)$

$\Rightarrow x = y$

故  $S \cup I_X$  是反对称的。

对任意 $\langle x,y\rangle \in S \cup I_X$ ,且 $\langle y,z\rangle \in S \cup I_X$ ,则

$(\langle x,y\rangle \in S \lor \langle x,y\rangle \in I_X) \land (\langle y,z\rangle \in S \lor \langle y,z\rangle \in I_X)$

$\Rightarrow (\langle x, y \rangle \in S \land \langle y, z \rangle \in S) \lor (\langle x, y \rangle \in S)$

$\wedge \langle y,z \rangle \in I_X) \vee (\langle x,y \rangle \in I_X \wedge \langle y,z \rangle \in S)$

$\forall (\langle x,y\rangle \in I_X \land \langle y,z\rangle \in I_X)$

$\Rightarrow \langle x,z\rangle \in S \lor (x=y=z) \Rightarrow \langle x,z\rangle \in S \cup I_X$

所以  $S \cup I_X$  是传递的。

于是  $S \cup I_X$  是 X 上的偏序关系。

---
#### 3-146

> 设 S 为 X 上的偏序关系,T 为 Y 上的偏序关系,若  $\langle\langle x_1,y_1\rangle,\langle x_2,y_2\rangle\rangle\in P$  当且仅当 $\langle x_1,x_2\rangle\in S$  且 $\langle y_1,y_2\rangle\in T$ ,证 明:P 是  $X\times Y$  上的一个偏序关系。

**证明**：

因为  $P\subseteq (X\times Y)\times (X\times Y)$ :

--

## 第四章 函数

#### 4-2

> 4-2** 令  $f:A \rightarrow B$ ,这里  $C \subseteq A$ ,证明
> $$f(A) - f(C) \subseteq f(A - C) \qquad [4-1,(2)]$$

**证明**：

设 y 为任意元素,若  $y \in f(A) - f(C)$ ,则对某个  $x \in A$ , f(x) = y。但是对每个  $z \in C$ ,  $y \neq f(z)$ ,因此有  $x \in A - C$ 。因为 y = f(x),故有  $y \in f(A - C)$ ,由 y 的任意性,得到

$$f(A)-f(C)\subseteq f(A-C)$$

---
#### 4-3

> 设  $S = \{a,b,c\}$ ,  $T = \{p,q\}$ , 作  $f: S \rightarrow T$ , 问有多少函数 f, 其中有多少满射。

**解**：

因为|S|=3, |T|=2,  $f:S \to T$ , 故共有函数为  $2^3=8$  (个),其中满射为  $2 \times C_3^2=6$ (个)。

---
#### 4-4

> 以下哪些是函数,哪些是入射函数,哪些是满射函数, 对任意一个双射,写出它的逆函数:
> - a)  $f: Z \to N, f(x) = x^2 + 1;$
> - b)  $g: N \rightarrow Q, g(x) = 1/x;$
> - c)  $h: Z \times N \rightarrow Q, h(Z,n) = Z/(n+1)$ ;
> - d)  $f:\{1,2,3\}\rightarrow\{p,q,r\}$ ,  $\Diamond$   $\exists$   $f=\{\langle 1,q\rangle,\langle 2,r\rangle,\langle 3,p\rangle\}$ ;
> - e)  $g: N \rightarrow N, g$  定义为  $g(x) = 2^x$ ;
> - f)  $h: R^2 \rightarrow R^2$ , h 定义为  $h(x,y) = \langle y+1, x+1 \rangle$ 。

**解**：

a) 函数;

b) 不是函数,在x=0 无定义;
c)函数,满射;
d) 函数,双射,  $f^{-1}:\{p,q,r\} \rightarrow \{1,2,3\}$ ,这里  $f^{-1}=\{\langle q,1\rangle,\langle r,2\rangle,\langle p,3\rangle\}$
e) 函数,入射;
f) 函数,双射, $h^{-1}$ ; $R^2 \rightarrow R^2$ , $h^{-1}(x,y) = \langle y-1, x-1 \rangle$ 。

---
#### 4-5

> 假设 f 和 g 是函数,dom f = dom g,且对公共域上所有 x, f(x) = g(x),证明 f = g。

**证明**：

假定 dom f = dom g = A,则

$$f = \{\langle x, y \rangle | x \in A, xfy\}$$

$$= \{\langle x, y \rangle | x \in A, y = f(x)\}$$

$$= \{\langle x, y \rangle | x \in A, y = g(x)\}$$

$$= \{\langle x, y \rangle | x \in A, xgy\} = g$$

---
#### 4-6

> 假设 f 和 g 是函数,证明:
> $$f \subseteq g \Leftrightarrow \operatorname{dom} f \subseteq \operatorname{dom} g$$
> 且对所有  $x \in \text{dom } f, f(x) = g(x)$ 。

**证明**：

因为  $f = \{\langle x, f(x) \rangle | x \in \text{dom } f\}$

$$g = \{\langle x, g(x) \rangle | x \in \text{dom } g\}$$

$f \subseteq g \Leftrightarrow$ 对任意 $\langle x, f(x) \rangle \in f, x \in \text{dom } f \ \forall \langle x, f(x) \rangle \in g$ ,

$$x \in \operatorname{dom} f \Leftrightarrow (\langle x, f(x) \rangle \in f \rightarrow \langle x, f(x) \rangle \in g)$$

$(\exists \qquad (x \in \operatorname{dom} f \to x \in \operatorname{dom} g) \Leftrightarrow \operatorname{dom} f \subseteq \operatorname{dom} g$

且对所有  $x \in \text{dom } f, f(x) = g(x)$ 。

---
#### 4-9

> 4-9** 假定 *X* 和 *Y* 是有穷集合,找出 *X* 到 *Y* 存在入射的必要条件是什么? 【4-1.(5)】

**解**：

设X和Y是有穷集合,X到Y存在入射的必要条件是:

i)  $|X| \leq |Y|$ ;
ii)  $f(x_1) = f(x_2) \Rightarrow x_1 = x_2$ .

---
#### 4-10

> 设 A 和 B 是有穷集合,有多少不同人射函数和多少不同的双射函数。

**解**：

设 A 和 B 是有穷集合,且 |A|=m,|B|=n,要使映射 f:  $A \rightarrow B$  为人射,必须有  $|A| \leq |B|$ ,即  $m \leq n$ 。 在 B 中任意选出  $m \uparrow$  元素的任一全排列,都能形成  $A \rightarrow B$  的一个不同的人射,故  $f: A \rightarrow B$  的不同人射共有:

$$C_n^m \cdot m! = n(n-1)(n-2)\cdots(n-m+1)(\uparrow)$$

又要使映射  $f:A \rightarrow B$  为双射,必需有:|A| = |B|

设  $A = \{a_1, a_2, \dots, a_m\}$  ,  $B = \{b_1, b_2, \dots, b_m\}$  , 则对  $a_1$  对应的元素共有 m 种取法, $a_2$  的对应元素在  $a_1$  取定后共有 m-1 种取法, $a_3$  的对应元素在  $a_1$  和  $a_2$  取定后共有 m-2 种取法,依此类推, $a_m$  对应元素有 m-(m-1) 种取法。故  $f: A \rightarrow B$  的不同双射共有

$$m(m-1)(m-2)\cdots(m-m+1)=m!(\uparrow)$$

---
#### 4-11

> 设 f:N→N,定义 91 函数为:
> $$f(x) = x - 10$$
> , 若  $x > 100$
> $f(x) = f(f(x+11))$ , 若  $x \le 100$

**证明**：

a) f(99)=91;

b)  $f(x) = 91, (0 \le x \le 100)$ .

a)
$$f(99) = f(f(99+11)) = f(f(110))$$

=  $f(110-10) = f(100) = f(f(100+11))$
=  $f(f(111)) = f(111-10) = f(101)$
=  $101-10=91$

b) 证明可分两部分:
1) 首先证明 f(x) = 91,对所有  $90 \le x \le 100$ 。

$$f(90) = f(f(101)) = f(91) = f(f(102))$$

=  $f(92) = f(f(103))$
=  $f(93) = f(99)$ ,

2) 再证 f(x) = 91,对 x < 90。

设 x < 90,且设 k 为使得  $90 \le x + 11k \le 100$  的最小整数,则

$$f(x) = f(f(x+11)) = f(f(f(x+2 \cdot 11)))$$

=  $\cdots = f^{(k+1)}(x+11 \cdot k)$

这里  $90 \le x+11 \cdot k \le 100$ ,且  $k \ge 1$ 。

由 1)可知  $f(x+11 \cdot k)=91$ ,因此  $f(x)=f^*(f(x+11 \cdot k))=f^*(91)$ ;因为由 1)得 f(91)=91,因此对所有  $k \ge 0$ ,  $f^*(91)=91$ , 所以  $f(x)=f^*(91)=91$ ,对所有 x < 90 成立。

---
#### 4-12

> 试证明:
> - a)  $f(A \cup B) = f(A) \cup f(B)$ ;
> - b)  $f(A \cap B) \subseteq f(A) \cap f(B)$ .
> [4-1.(7)]

**证明**：

a) 设  $y \in f(A \cup B)$ ,则存在  $x \in A \cup B$ ,使 f(x) = y,即  $x \in A \lor x \in B$  时有 y = f(x)。故  $f(x) \in f(A) \lor f(x) \in f(B)$ ,因此  $y \in f(A) \cup f(B)$ ,于是  $f(A \cup B) \subseteq f(A) \cup f(B)$ 。

反之,设  $y \in f(A) \cup f(B)$ ,则有  $y \in f(A)$ 但  $y \notin f(B)$ ,或  $y \in f(B)$ ,但  $y \notin f(A)$ ,或  $y \in f(B)$ 。由此有  $x \in A$  使

f(x) = y,或有  $x \in B$  使 f(x) = y,或有  $x \in A$  且  $x \in B$  使 f(x) = y。

综上可得:存在  $x \in A \cup B$ ,使 f(x) = y。故  $y \in f(A \cup B)$ 。所以  $f(A \cup B) = f(A) \cup f(B)$ 。

b) 设  $y \in f(A \cap B)$ ,则存在  $x \in A \cap B$ ,使 f(x) = y。即存在  $x \in A \land x \in B$ ,使 f(x) = y。故

$$y \in f(A) \land y \in f(B) \Rightarrow y \in (f(A) \cap f(B))$$

所以

$$f(A \cap B) \subseteq f(A) \cap f(B)$$

---
#### 4-13 假定  $f: X \to Y$ , 定义 $\overline{f}: \mathcal{P}(X) \to \mathcal{P}(Y)$  使得 $\overline{f}(A) = \{y | \langle x, y \rangle \in f$ , 对某些  $x \in A\}$ 。对所有  $A, B \in \mathcal{P}(X)$ ,问

a)  $\overline{f}(A) \overline{f}(\dot{B}) \subseteq \overline{f}(A-B)$ 成立吗?
b)  $\overline{f}(A-B)\subseteq \overline{f}(A)-\overline{f}(B)$ 成立吗?

a) 成立。设  $y \in (\overline{f}(A) - \overline{f}(B))$ ,则必有:

$$y \in \overline{f}(A) \land y \notin \overline{f}(B)$$

即对某个  $x_1 \in A$ ,  $y = f(x_1)$ , 但对任意  $x \in B$ ,  $y \notin f(x)$ 。 故对某个  $x_1 \in A - B$ ,  $y = f(x_1)$ , 即

$$y \in \overline{f}(A-B)$$

于是

$$\overline{f}(A) - \overline{f}(B) \subseteq \overline{f}(A - B)$$

b) 不成立。设有一个函数 f 不是人射,  $f: X \to Y \Leftrightarrow y = f(x_1) = f(x_2)$ , 且  $x_1 \neq x_2$ , 设  $A = \{x_1, x_2\}$ ,  $B = \{x_2\}$ , 则

$$x_1 \in A-B, y=f(x_1)$$

故

$$y \in \overline{f}(A-B)$$

但  $x_1 \in A, y = f(x_1), x_2 \in B, y = f(x_2)$ ,即有

$$y \in \overline{f}(A) \land y \in \overline{f}(B) \Rightarrow y \in \overline{f}(A) \cap \overline{f}(B)$$

$$\Rightarrow y \notin \overline{f}(A) - \overline{f}(B)$$

于是 $\overline{f}(A-B)\subseteq \overline{f}(A)-\overline{f}(B)$ ,不成立。

---
#### 4-14

> 假定  $f:A \to B$ , 并定义一个函数  $G:B \to \mathcal{P}(A)$ , 对于  $b \in B$ ,  $G(b) = \{x \in A \mid f(x) = b\}$ , 证明: 如果  $f \in A$  到 B 的满映射,则 G 是入射的,其逆成立吗?

**证明**：

如果  $f \in A$  到 B 的满映射,则对每个  $b \in B$ ,至少存在 一个  $x \in A$ ,使得 f(x) = b,故 G 的定义域为 B。

若有  $b_1, b_2 \in B$ ,且  $b_1 \neq b_2$ ,

$$G(b_1) = \{x \in A \mid f(x) = b_1\}$$

$$G(b_2) = \{ y \in A \mid f(y) = b_2 \}$$

因为  $b_1 \neq b_2$ ,  $f(x) \neq f(y)$ , 而 f 是函数, 故  $x \neq y$ , 所以

$$G(b_1)\neq G(b_2)$$

故G是入射。但其逆不真。

例如  $A = \{a,b,c\}, B = \{x,y,z\},$ 则

$$f:A \rightarrow B, f(a) = x, f(b) = x, f(c) = y$$

$$G: B \to \mathcal{P}(A), G(x) = \{a,b\}, G(y) = \{c\}, G(z) = \emptyset$$

G是入射,但f不是满射。

---
#### 4-15

> 若  $A\subseteq B$ ,则  $A^c\subseteq B^c$ 。

**证明**：

$\diamondsuit f \in A^c$ ,则  $f \subseteq C \times A \subseteq C \times B$ 。

对所有  $x \in C$ ,都有一个  $y \in A$ (即  $y \in B$ ),使得 $\langle x, y \rangle \in f$ ,因为 f 是函数,故

$$\langle x, y_1 \rangle \in f \land \langle x, y_2 \rangle \in f \Rightarrow y_1 = y_2$$

故 f 也是从 C 到 B 的一个函数,即  $f \in B^c$ 。

所以  $A^c \subseteq B^c$ 。

---
#### 4-16

> 设  $X \neq \emptyset$ ,定义 fSg, iff ran f = ran g,  $f, g \in X^x$ ,证明 S 是在  $X^x$  上的等价关系,且存在双射
> $$\Phi: X^{X}/S \rightarrow \mathcal{P}(X) - \{\emptyset\}$$

**证明**：

(1) 对任意  $f \in X^X$ , ran f = ran f, 故 fSf 的 S 是自反的, 对任意  $f, g \in X^X$

$$\langle f, g \rangle \in S \Leftrightarrow \operatorname{ran} f = \operatorname{ran} g$$

$$\Leftrightarrow$$
ran  $g =$ ran  $f \Leftrightarrow \langle g, f \rangle \in S$

即 S 是对称的。对任意  $f,g,h \in X^{X}$

$$\langle f,g \rangle \in S \land \langle g,h \rangle \in S \Leftrightarrow (\operatorname{ran} f = \operatorname{ran} g) \land (\operatorname{ran} g = \operatorname{ran} h)$$

$\Rightarrow \operatorname{ran} f = \operatorname{ran} h \Leftrightarrow \langle f,h \rangle \in S$

故S是传递的。

(2) 定义
$$\Phi: X^X/S \to \mathcal{P}(X) - \{\emptyset\}$$
, 使得  $\Phi([f]_s) = \operatorname{ran} f$ 。 因  $\Phi([f]_s) = \Phi([g]_s) \Leftrightarrow \operatorname{ran} f = \operatorname{ran} g \Leftrightarrow \langle f, g \rangle \in S \Rightarrow [f]_s = \Phi([f]_s)$

$[g]_s$ ,故  $\Phi$  是入射的。

又如设  $A \in \mathcal{P}(X) - \{\emptyset\}$ ,则  $A \subseteq X$ ,且  $A \neq \emptyset$ 。令  $a \in A$ ,定义  $f: X \rightarrow A$  如下:

$$f(x) = \begin{cases} x, x \in A \\ a, x \notin A \end{cases}$$

则  $\Phi([f]_s) = \operatorname{ran} f = A$ ,因此  $\Phi$  是满射。

故存在双射  $\Phi: X^X/S \rightarrow \mathcal{P}(X) - \{\emptyset\}$ 。

---
#### 4-17 设 R 为实数集,令  $X=R^{[0,1]}$ ,若  $f,g\in X$ ,定义 $\langle f,g\rangle\in S$ ,iff 对所有  $x\in[0,1]$ , $f(x)-g(x)\geqslant 0$ ,证明:S 是一个偏序,S 是全序吗?

a) 先证 S 是一个偏序关系。

1) 因为对所有  $x \in [0,1]$ ,对任意  $f \in X$ ,有 f(x) f(x) = 0, 故 $\langle f, f \rangle \in S$ ,即  $S \in X$  上是自反的。
2) 对所有  $x \in [0,1]$ , 若有  $f,g \in X$ , 使 $\langle f,g \rangle \in S$ , 且 $\langle g,f \rangle \in S$ ,则对所有  $x \in [0,1]$ 有

$$f(x)-g(x)\geqslant 0$$
$(\exists g(x)-f(x)\geqslant 0$
$f(x)=g(x)$

故得

即S在X上反对称。

3) 对所有  $x \in [0,1]$ ,有 f,g, $h \in X$ ,使得 $\langle f,g \rangle \in S$ , $\langle g,h \rangle \in S$ ,即对所有  $x \in [0,1]$ 有

$$f(x)-g(x)\geqslant 0, g(x)-h(x)\geqslant 0$$

则

$$f(x)-g(x)+g(x)-h(x)\geqslant 0$$

所以对所有  $x \in [0,1]$ 有  $f(x) - h(x) \ge 0$ 。故 $\langle f, h \rangle \in S$ ,即 S在 X 上传递。

综上可得 S 是 X 上的偏序关系。

b) 再证 S 不是 X 上的全序关系。举一反例:

设
$$f(x) = x, g(x) = -x+1, 则$$

$$f(0)-g(0)=-1,g(1)-f(1)=-1$$

故 f 和 g 是不可比的,即 S 在 X 上不是全序关系。

---
#### 4-19

> 4-19** A 到 B 的映射决定 A 的一个划分  $\pi$ , A 的一个划分也 决定 A 到  $\pi$  的一个映射。

**证明**：

设  $f:A\rightarrow B$  是一个映射, 先取  $a\in A$ , 令

$$[a] = \{x \in A \mid f(x) = f(a)\}$$

次取  $b \in A$ ,但  $b \notin [a]$ ,令

$$[b] = \{ y \in A \mid f(b) = f(y) \}$$

再取  $c \in A$ ,但  $c \notin [a]$ , $c \notin [b]$ ,令

$$[c] = \{Z \in A \mid f(Z) = f(c)\}$$

依次类推,可对A的元素分类,设

$$\pi = \{[a], [b], [c], \dots, \}$$

则 1) 所有  $a \in A$ ,  $a \in [a]$ , 故 $[a] \neq \emptyset$ ;
2) 对任意 $[a] \in \pi$  和 $[b] \in \pi$ ,则 $[a] \cap [b] = \emptyset$ ,因为若 $[a] \cap$

$[b] \neq \emptyset$ ,则必有  $u \in A$ ,使得  $u \in [a] \land u \in [b]$ ,与上述对 A 的元素 分类矛盾。

3) [a] $\bigcup$ [b] $\bigcup$ [c] $\bigcup$ …=A,故  $\pi$  是 A 的一个划分。反之,设  $\pi$ ={ $A_1$ , $A_2$ ,…, $A_n$ }是 A 的一个划分,即:

$$A = A_1 \cup A_2 \cup \cdots \cup A_n \cup \cdots$$

对所有  $x \in A$ ,必有且仅有一个 i,使得  $x \in A_i$ ,作  $\varphi: A \to \pi$ ,使满足  $\varphi(x) = A_i$ ,即对任意  $x \in A$ ,都唯一确定  $\pi$  中一个元素  $A_i$ ,故可得  $\varphi$  是满射,即存在 A 到  $\pi$  的一个映射。

在习题  $4-20\sim4-22$  中,设 f 为集合 X 到集合 Y 上的映射,即  $f:X\rightarrow Y$ ,设 A,B 为 X 的子集,则有:

---
#### 4-20

> 试证 $(f * A) \cup (f * B) = f * (A \cup B)$ 。

**证明**：

若  $y \in (f * A) \cup (f * B)$ ,则  $y \in f * A$ ,或  $y \in f * B$ ; 如果  $y \in f * A$  为真,则存在一个  $x \in A$ ,使得 y = f(x)。因为  $x \in A$ ,故有  $x \in A \cup B$  且  $y = f(x) \in f * (A \cup B)$ 。对  $y \in f * B$  为真时,情况与上述类似,故

$$(f*A) \bigcup (f*B) \subseteq f*(A \bigcup B)$$

反之,若  $y \in f * (A \cup B)$ ,则存在一个  $x \in A \cup B$ ,使得 y = f(x),由定义  $x \in A$  或  $x \in B$ ,即是  $y \in f * A$ ,或  $y \in f * B$ ,为此可得

$$f*(A \bigcup B) \subseteq (f*A) \bigcup (f*B)$$

于是  $f*(A \cup B) = (f*A) \cup (f*B)$

---
#### 4-21

**证明**：

$f * (A \cap B) \subseteq (f * A) \cap (f * B)$ , 举一个例子说明本题中包含关系一般不能用等号替代。
设  $y \in f * (A \cap B)$ ,则存在一个  $x \in A \cap B$ ,使得有 y = f(x),由定义  $x \in A$  和  $x \in B$ ,则  $f(x) \in f * A$  和  $f(x) \in f * B$ ,所以
$$f(x) \in (f * A) \cap (f * B)$$
这样  $y \in (f * A) \cap (f * B)$
例:令  $f:R \to R$  是由  $f(x) = x^2$  所定义的一个映射,设  $A = R - R_+$ , $B = R_+$ , $A \cap B = \emptyset$ ,所以  $f * (A \cap B) = \emptyset$ ,但  $f * A = R_+ \cup \{0\}$ ,  $f * B = R_+$ ,这样 $(f * A) \cap (f * B) = R_+$ 。
---
#### 4-22

> 证明(f\*A)-(f\*B)⊆f\*(A-B),举一个例子说
> 明本题中包含关系一般不能用等号替代。

**证明**：

若  $y \in (f*A) - (f*B)$ ,则  $y \in f*A$ ,且  $y \notin f*B$ ,故 必存在一个  $x \in A$ ,使得 f(x) = y,显然  $x \notin B$ ,因为若  $x \in B$ ,则 f(x) $\in f*B$ ,与题设矛盾。于是  $x \in A - B$ ,且  $f(x) \in f*(A - B)$ ,所以

$$(f * A) - (f * B) \subseteq f * (A - B)$$

例如  $f:R \rightarrow R$ , 定义  $f(x) = x^2$ , 设 A = R,  $B = R_+$ ,  $f * A = R_+ \cup \{0\}$ ,  $f * B = R_+$ , 则

$$(f * A) - (f * B) = (0), f * (A - B) = R_{+} \cup \{0\}$$

---
#### 4-23

**证明**：

$A \subseteq B \Rightarrow f * A \subseteq f * B$ 。
因为 $A\subseteq B \Leftrightarrow A \cup B = B$ ,但
$$(A \cup B = B) \Rightarrow f * (A \cup B) = f * B$$
而由习题 4-20 可知:
$$f * (A \cup B) = (f * A) \cup (f * B)$$
$$(f * A) \cup (f * B) = (f * B)$$
所以得到
$$(f * A) \subseteq (f * B)$$
---
#### 4-24

> 设  $a \neq b$ ,  $X = \{a, b, \{a, b\}\}$ ,  $Y = \{a, b\}$ , 定义映射  $f: X \rightarrow Y$ 为 f(a) = f(b) = a,  $f(\{a, b\}) = b$ , 求  $f * \{a, b\}$ , 并说明结果可给我们什么启发?

**解**：

$f * \{a,b\} = \{a\}$ ,这个结果说明在 f(X)与 f \* X 之间是不同的,因为如本例中:  $f(\{a,b\}) = b$ ,但  $f * \{a,b\} = \{a\}$ 两者结果并不相同。

---
#### 4-25

> 设  $X = \{1, 2, 3, 4\}$ ,确定出这样的函数  $f: X \to X$ ,使 得  $f \neq I_X$ ,并且是人射的,求出  $f \circ f = f^2$ ,  $f^3 = f \circ f^2$ ,  $f^{-1}$  和  $f \circ f^{-1}$ ;是否能够找到另外一个人射函数  $g: X \to X$ ,使得  $g \neq I_X$ ,但 是  $g \circ g = I_X$ 。

**解**：

任意一个 $\{1,2,3,4\}$ 的排列,均满足要求,如:

$$f = \{\langle 1, 2 \rangle, \langle 2, 3 \rangle, \langle 3, 1 \rangle, \langle 4, 4 \rangle\}$$

$$f^{2} = \{\langle 1, 3 \rangle, \langle 2, 1 \rangle, \langle 3, 2 \rangle, \langle 4, 4 \rangle\}$$

$$f^{3} = \{\langle 1, 1 \rangle, \langle 2, 2 \rangle, \langle 3, 3 \rangle, \langle 4, 4 \rangle\}$$

$$f^{-1} = \{\langle 2, 1 \rangle, \langle 3, 2 \rangle, \langle 1, 3 \rangle, \langle 4, 4 \rangle\}$$

$f \circ f^{-1} = \{\langle 1, 1 \rangle, \langle 2, 2 \rangle, \langle 3, 3 \rangle, \langle 4, 4 \rangle\} = I_X$  $q = \{\langle 1, 2 \rangle, \langle 2, 1 \rangle, \langle 3, 4 \rangle, \langle 4, 3 \rangle\}$  $g \circ g = \{\langle 1, 1 \rangle, \langle 2, 2 \rangle, \langle 3, 3 \rangle, \langle 4, 4 \rangle\} = I_X$

---
#### 4-26

> 设 F 为函数簇  $X^{x}$ , 若  $f \in F$ , 证明 f 是传递关系, 当且 仅当  $f^2 = f$ 。

**证明**：

由习题 3-82 a)知 f 是传递的,当且仅当有  $f \circ f \subseteq f$ , 故本题只需证明当 f 是传递关系时,  $f \circ f \subseteq f \Leftrightarrow f^2 = f$  即可。

1) 因为  $f \circ f = f \Rightarrow f \circ f \subseteq f$  成立。所以 f 是传递的。
2) 如果  $f \circ f \subseteq f$ ,对任意 $\langle x, y \rangle \in f$ ,有  $y \in X$ ,由 f 是函数,必 有  $z \in X$ ,使 $\langle y,z \rangle \in f$ ,故 $\langle x,z \rangle \in f \circ f$ 。因为 f 是传递关系,故  $\langle x,y\rangle \in f \land \langle y,z\rangle \in f$ ,必有 $\langle x,z\rangle \in f$ 。但因 f 是函数 $\langle x,y\rangle \in f$  $f \land \langle x,z \rangle \in f \Rightarrow y = z$ ,故对任意 $\langle x,y \rangle \in f \Rightarrow \langle x,y \rangle \in f \circ f$ ,得  $f \subseteq$  $f \circ f$ ,于是有  $f = f \circ f$ ,即  $f \circ f \subseteq f \Leftrightarrow f = f \circ f$ 。

---
#### 4-27 设  $f: A \to B$ , 且  $B' \subseteq B$ , 则  $f^{-1}(B')$ 表示 A 的一个子 集,称作在 f 作用下,B'的逆映射: $f^{-1}(B') = \{x \mid f(x) \in B'\}$ 令  $A' \subseteq A$ ,证明.
a)  $f(f^{-1}(B'))\subseteq B'$ :
b) 如果 f 是满射的,那末  $f(f^{-1}(B')) = B'$ ;
c)  $f^{-1}(f(A')) \supseteq A'$ ;
d) 如果 f 是入射,那末  $f^{-1}(f(A')) = A'$ 。 [4-2,(2)]

a) 设  $y \in f(f^{-1}(B'))$ ,则必存在  $x \in f^{-1}(B')$  使得 f(x) = y,故  $f(x) \in B'$ ,即  $y \in B'$ ,所以  $f(f^{-1}(B')) \subseteq B'$ 。

b) 由 a)知  $f(f^{-1}(B'))\subseteq B'$ 。反之,若对任意  $y\in B'$ ,因为 f是满射,故必有  $x \in f^{-1}(B')$ ,使得 f(x) = y。因为  $x \in f^{-1}(B')$ , 故  $y \in f(f^{-1}(B')), B' \subseteq f(f^{-1}(B'))$ ,于是有  $f(f^{-1}(B')) = B'$ 。
c) 对任意  $x \in A'$ ,  $f(x) \in f(A')$ , 因为  $A' \subseteq A$ , 故  $f(A') \subseteq B$ . 设 f(A') = B',由  $f(x) \in B'$  得  $x \in f^{-1}(f(A'))$ ,所以  $f^{-1}(f(A'))$  $\supseteq A'$
d) 设  $x \in f^{-1}(f(A'))$ ,则  $f(x) \in f(A')$ ,在 A'中必存在 x', 使得 f(x) = f(x')。因为 f 是入射,故必有 x = x'。即  $x \in A'$ ,所

$\operatorname{pl} A' \supseteq f^{-1}(f(A'))$ ,于是  $f^{-1}(f(A')) = A'$ .

---
#### 4-28

> 设  $f \circ g$  是复合函数:
> - a) 如果  $f \circ g$  是满射的,那末 f 是满射的;
> - b) 如果  $f \circ g$  是入射的,那末 g 是入射的;
> - c) 如果  $f \circ g$  是双射的,那末 f 是满射的,g 是入射的。
> [4-2.(3)]

**证明**：

设  $g: X \rightarrow Y, f: Y \rightarrow Z, 有$

a) 设任意  $z \in Z$ , 因为  $f \circ q$  是满射, 故必有  $x \in X$ , 使得  $f \circ g(x) = z$ 。因为  $f \circ g(x) = f(g(x))$ ,这里  $g(x) = y \in Y$  由 f 是 函数,故每个  $y \in Y$ ,必有  $z \in Z$ ,使 z = f(y)。但每个 z 在 f 作用 下都是Y中元素的一个映象,由z的任意性,可知f是满射的。
b) 设  $f \circ g$  是入射的。如果 g 不是入射,则必存在  $x_1 \neq x_2$  时 有  $g(x_1) = g(x_2) = y \in Y$ 。由  $f \circ g(x_1) = f(g(x_1)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)) = f(g(x_2)$  $f \circ g(x_2)$ 得出  $f \circ g$  不是入射,与题设矛盾。
c) 因为  $f \circ g$  是双射函数,故  $f \circ g$  是满射和人射的,由 a)和 b)可知 f 是满射的,g 是入射的。

---
#### 4-30

> 4-30** 设函数  $f: R \to R$ ,若  $x \le y \Rightarrow f(x) \le f(y)$ ,则称函数 f是单调递增的。设 f 和 g 是在 R 上单调递增,证明
> 另外如
> - 1) 若(f+g)(x) = f(x) + g(x),则 f+g 是单调递增;
> - 2) 复合函数 f · g 是单调递增;
> - 3) f和g的乘积不一定是单调递增。

**证明**：

1) 因为 f 和 g 是单调递增, 若  $x \leq y$ , 则有

$$f(x) \leqslant f(y), g(x) \leqslant g(y)$$

$(f+g)(x) = f(x) + g(x) \le f(y) + g(y) = (f+g)(y)$  所以 f+g 是单调递增。

2) 若  $x \le y$ ,  $f(x) \le f(y)$ 且  $g(x) \le g(y)$ , 则有  $f \circ g(x) = f(g(x)) \le f(g(y)) = f \circ g(y)$

所以  $f \cdot g$  是单调递增。

3) 令 f(x) = g(x) = x,则 f 和 g 是单调递增,但其积函数  $f * g(x) = f(x) * g(x) = x^2$

在R上不是单调递增。

---
#### 4-31

> 设  $f: A \rightarrow B$  是一个满射,则可由 f 确定 A 上的一个等价关系 R,且存在唯一的双射  $f_{\Delta}: \pi \rightarrow B$ ,使得  $f = f_{\Delta} \circ \varphi$ ,其中  $\pi$  是由 f 所决定的 A 上的一个划分, $\varphi$  是 A 到  $\pi$  的满射。

**证明**：

由习题 4-19 知, f 决定 A 的一个划分  $\pi$ , 使得有  $\pi = \{ \lceil a \rceil, \lceil b \rceil, \lceil c \rceil, \cdots \}$

对任意[a] $\in \pi$ ,有

$$[a] = \{x | x \in A \quad \exists \quad f(x) = f(a)\}$$

\_由定理 3-10.3 可知 A 的任意一个划分  $\pi$ ,必可诱导确定一个等价 关系 R,使得有

$$aRb \Leftrightarrow [a] = [b] \Leftrightarrow f(a) = f(b)$$

为此可说 f 确定了 A 上的一个等价关系。任取  $[a] \in \pi$ ,令  $f_{\Delta}$ :  $\pi \rightarrow B$ ,使满足:

$$f_{\Delta}([a]) = f(a)$$

现证  $f_{\Delta}$  是双射。

1)  $f_{\Delta}$  是映射。因为若有[a]=[b],则 aRb,由我们定义, $aRb \Rightarrow f(a)=f(b)$ ,故  $f_{\Delta}([a])=f_{\Delta}([b])$ ,即  $f_{\Delta}$  是 $\pi$  到 B 的一个映射。

2)  $f_{\Delta}$  是满射。对任意  $b \in B$ ,因 f 是满射,故必存在  $a \in A$ ,使 f(a) = b,但  $f(a) = f_{\Delta}([a]) = b$ ,即对任意  $b \in B$  必有  $[a] \in \pi$ ,使  $f_{\Delta}([a]) = b$ 。所以  $f_{\Delta}$  是满射。
3)  $f_{\Delta}$  是入射:设有[x],  $[y] \in \pi$ , 且 $[x] \neq [y]$ , 则有 $\langle x, y \rangle \notin R$ , 故  $f(x) \neq f(y)$ , 为此  $f_{\Delta}([x]) \neq f_{\Delta}([y])$ 即  $f_{\Delta}$  是入射的。

由 1),2),3)可知 f<sub>△</sub> 是双射。

4) 再证存在  $f = f_{\Delta} \circ \varphi$ 。设  $\varphi: A \to \pi$  是一个满射,且满足对任  $\hat{a} \in A$ ,有  $\varphi(a) = [a]$ 。任取  $a \in A$ ,

$$(f_{\Delta} \circ \varphi)(a) = f_{\Delta}(\varphi(a)) = f_{\Delta}([a]) = f(a)$$

所以  $f_{\Delta} \circ \varphi = f$ 。

5) 最后证  $f_{\Delta}$  是唯一的。设另有  $g_{\Delta}$ ,使得  $g_{\Delta} \circ \varphi = f$ ,且  $g_{\Delta}([a]) = f(a)$ ,设有:  $f_{\Delta} \neq g_{\Delta}$ ,则至少存在一个  $a \in A$ ,使得

$$f_{\Delta}([a])\neq g_{\Delta}([a])$$

$(f_{\Delta} \circ \varphi)(a) = f_{\Delta}(\varphi(a)) = f_{\Delta}([a]) = f(a)$

$$(g_{\Delta} \circ \varphi)(a) = g_{\Delta}(\varphi(a)) = g_{\Delta}([a]) = f(a)$$

与假设矛盾,所以

$$f_{\Delta} = g_{\Delta}$$

---
#### 4-32

> 设  $f: X \rightarrow Y, g: Y \rightarrow X$ , 设  $g \circ f$  为 X 上恒等函数,证明 f 是人射和 g 是满射。

**证明**：

1) 因为  $g \circ f(x_1) = x_1, g \circ f(x_2) = x_2$ ,故必存在 c,使  $\langle x_1, c \rangle \in f, \langle c, x_1 \rangle \in g$ ,同样也存在 d,使 $\langle x_2, d \rangle \in f, \langle d, x_2 \rangle \in g$ 。

若  $x_1 \neq x_2$ ,但  $f(x_1) = f(x_2)$ ,则 c = d,但 g 是函数,若 c = d,则 g(c) = g(d),则  $x_1 = x_2$  矛盾。故 f 为入射。

2) 若 g 不是满射,则必有某个  $x \in X$ ,对所有  $y \in Y$ ,  $g(y) \neq x$ 。但  $g \circ f(x) = x$ ,故必有某个  $c \in Y$ ,使得 $\langle x, c \rangle \in f \land \langle c, y \rangle \in g$ 。即存在  $c \in Y$ ,使得 g(c) = x,矛盾。

所以 g 是满射。

---
#### 4-34

> 4-34** 设  $h \in X^{x}$ ,证明若  $f \circ h = g \circ h$ ,则对所有  $f, g \in X^{x}$ , f = g 当且仅当 h 是一个满射。

**证明**：

1) 假定  $h \in X^x$ ,若  $f \circ h = g \circ h$ ,且 f = g,如果 h 不是一个满射,则必存在  $x_1 \in X$ ,使得对所有  $x \in X$ , $h(x) \neq x_1$ ,因为  $h \in X^x$ ,所以  $X \neq \{x_1\}$ ,故必有  $x_2 \in X$ 且  $x_2 \neq x_1$ ,定义两个函数  $f,g \in X^x$  如下:

$$f: X \to X$$
,使得  $\begin{cases} f(x) = x_2, \, \text{当 } x \in X \text{ 且 } x \neq x_1 \\ f(x_1) = x_1 \end{cases}$

$g: X \to X$ , 使得对所有  $x \in X$  有  $g(x) = x_2$

这样 f(h(x)) = g(h(x)),但  $f \neq g$  与题矛盾,故 h 必是一个满射。

2) 假定  $f \circ h = g \circ h$ ,且 h 是一个满射,若  $f \neq g$ ,则必存一个  $x_1 \in X$ ,使得  $f(x_1) \neq g(x_1)$ ,因此对所有  $x \in X$ ,必有  $h(x) \neq x_1$ ,因为否则  $f(h(x)) \neq g(h(x))$ ,即:

$$f \circ h(x) \neq g \circ h(x)$$

与题设  $f \circ h = g \circ h$  矛盾。但若对所有  $x \in X$ ,  $h(x) \neq x_1$ , 则 h 不是满射,于是 f = g。

---
#### 4-35

> 设  $f: X \to X$ ,证明:
> - 1) 若  $f \subseteq I_X$ ,则  $f = I_X$ ;
> - 2) 若  $I_X \subseteq f$ ,则  $f = I_X$ 。

**证明**：

1)设  $x \in X$ ,因 f 是函数,故必有某个  $y \in X$ ,使得  $\langle x,y \rangle \in f$ ,但  $f \subseteq I_X$ ,故  $\langle x,y \rangle \in I_X$ ,即 x = y,于是对任意  $x \in X$ ,必有  $\langle x,x \rangle \in f$ ,所以  $\langle x,x \rangle \in I_X \Rightarrow \langle x,x \rangle \in f$ ,即  $x \subseteq f$ ,得  $I_X = f$ 。

2)设  $I_X \subseteq f$ ,对任意 $\langle x, y \rangle \in f$ ,则  $x \in X$ ,故 $\langle x, x \rangle \in I_X$ 。因为  $I_X \subseteq f$ ,得 $\langle x, y \rangle \in f \land \langle x, x \rangle \in f$ ,但 f 是函数,故 x = y,所以  $\langle x, y \rangle \in f \Rightarrow \langle x, y \rangle \in I_X$ ,即  $f \subseteq I_X$ 。于是  $f = I_X$ 。

---
#### 4-36

> 设  $f: X \rightarrow X$ , n 为正整数, 使得  $f^n = I_X(f^{n+1} = f \circ f^n = f^n \circ f$ ), 证明 f 是一个双射。

**证明**：

设 n=1 时, $f=I_X$ ,故 f 是双射,当 n>1 时, $f^n=I_X$ 。 若 f 不是入射,则必有  $x_1$ , $x_2 \in X$ ,使  $x_1 \neq x_2$  时有  $f(x_1) = f(x_2)$ ,即  $x_1 \neq x_2$  时有  $f^{n-1} \circ f(x_1) = f^{n-1} \circ f(x_2)$ ,故当  $x_1 \neq x_2$  时,有  $f^n(x_1) = f^n(x_2)$ ,即  $f^n$  不是入射的,但与假设  $f^n = I_X$  矛盾。故 f 必是入射。

其次若再假定 f 不是满射,则必有  $y \in X$ ,使得对所有  $x \in X$ ,  $f(x) \neq y$ ,为此可推出对所有  $z \in X$ , $f \circ (f^{n-1}(z)) \neq y$ ,这样  $f^n$  不 是满射,但  $f^n = I_X$  是满射的,与假定矛盾。

所以f必是一个双射。

---
#### 4-37

> 试证若  $f:A \rightarrow B$ ,  $g:B \rightarrow A$ , 且  $g \circ f = I_A$ ,  $f \circ g = I_B$ ,则  $g = f^{-1}$ ,且  $f = g^{-1}$ 。
> [!tip] 4-2.(4)
> 

**证明**：

因为  $g \circ f = I_A$ ,故有  $g \circ f(a_1) = g(f(a_1)) = a_1, g \circ f(a_2)$ =  $g(f(a_2)) = a_2$ ,若  $a_1 \neq a_2$ ,  $g(f(a_1)) \neq g(f(a_2))$ ,所以  $f(a_1) \neq f(a_2)$ ,即 f 是入射的。

又,对任意  $a \in A$  有  $g \circ f(a) = g(f(a)) = a$ ,即存在:  $f(a) = b \in B$ ,使得 g(b) = a,因此 g 是满射的。同理可证,若  $f \circ g = I_B$ ,则 g 是入射和 f 是满射的,故由本题条件得 f 和 g 都是双射的。

现在设有 $\langle a,b\rangle \in f$ ,因为 $\langle a,a\rangle \in I_A$ ,而  $g \circ f = I_A$ ,故必有某个  $c \in B$ ,使得 $\langle a,c\rangle \in f$  且 $\langle c,a\rangle \in g$ ,由

$$\langle a,b\rangle \in f \land (a,c) \in f \Rightarrow b=c$$

因此

$$\langle b,a\rangle\in g$$

反之,若 $\langle b,a\rangle \in g$ ,由 $\langle b,b\rangle \in I_B$ ,故必有某个  $d\in A$ ,有 $\langle b,d\rangle \in g \land \langle d,b\rangle \in f$ ,由

$$\langle b,a\rangle \in g \land \langle b,d\rangle \in g \Rightarrow a=d$$

因此 $\langle a,b\rangle \in f$ 。

上述证明得到 $\langle a,b\rangle\in f$  当且仅当 $\langle b,a\rangle\in g$ ,所以  $g=f^{-1}$ 且  $f=g^{-1}$ 。

---
#### 4-38

**证明**：

若 $(g \circ f)^{-1}$ 是一个函数,则 f 和 g 是入射不一定成立。 【4-2.(5)】
设
$$f=\{\langle a_1,b_2\rangle,\langle a_2,b_3\rangle,\langle a_3,b_4\rangle\}$$
$$g = \{\langle b_1, c_1 \rangle, \langle b_2, c_1 \rangle, \langle b_3, c_2 \rangle, \langle b_4, c_3 \rangle\}$$
则
$$g \circ f = \{\langle a_1, c_1 \rangle, \langle a_2, c_2 \rangle, \langle a_3, c_3 \rangle\}$$
和  $(g \circ f)^{-1} = \{\langle c_1, a_1 \rangle, \langle c_2, a_2 \rangle, \langle c_3, a_3 \rangle\}$
是函数,但g不是入射。
- **4-39** 设  $\varphi$  是 A 到 B 的映射,  $S \subseteq A$ ,  $T \subseteq B$ , 证明:
- 1)  $\varphi(\varphi^{-1} * T) = T \cap \varphi(A)$ ;
- 2)  $\varphi(S \cap \varphi^{-1} * T) = \varphi(S) \cap T$ .
1) 对任意  $b \in \varphi(\varphi^{-1} * T)$ ,必存在  $a \in \varphi^{-1} * T$ ,使得  $\varphi(a) = b$  且  $\varphi(a) \in T$ ,即  $b \in T$ 。因为  $\varphi: A \to B$ ,故有  $\varphi^{-1} * T \subseteq A$ ,而  $b = \varphi(a) \in \varphi(A)$ ,所以  $b \in T \cap \varphi(A)$ 。由此
$$\varphi(\varphi^{-1} * T) \subseteq T \cap \varphi(A)$$
反之,对任意  $b \in T \cap \varphi(A)$ ,而  $b \in T \perp b \in \varphi(A)$ ,故必存在  $a \in A$ ,使得  $\varphi(a) = b \perp a \in \varphi^{-1} * T$ ,有  $b \in \varphi(\varphi^{-1} * T)$ ,所以
$$T \cap \varphi(A) \subseteq \varphi(\varphi^{-1} * T)$$
因此
$$T \cap \varphi(A) = \varphi(\varphi^{-1} * T)$$
2) 对任意  $b \in \varphi(S \cap \varphi^{-1} * T)$ ,则存在  $a \in S \cap \varphi^{-1} * T$ ,使得  $\varphi(a) = b$ ,即  $a \in S$ ,且  $a \in \varphi^{-1} * T$ 。因此  $\varphi(a) \in \varphi(S)$ 且  $\varphi(a) \in T$ ,即  $b \in \varphi(S)$ 且  $b \in T$ ,得到  $b \in T \cap \varphi(S)$ 。所以
$$\varphi(S \cap \varphi^{-1} * T) \subseteq T \cap \varphi(S)$$
反之,对任意  $b \in T \cap \varphi(S)$ ,有  $b \in T$ ,且  $b \in \varphi(S)$ ,故存在  $a \in S$ ,使  $\varphi(a) = b$ ,且  $a \in \varphi^{-1} * T$ ,即  $a \in S \cap \varphi^{-1} * T$ , $\varphi(a) \in \varphi(S \cap \varphi^{-1} * T)$ ,故  $b \in \varphi(S \cap \varphi^{-1} * T)$ 。所以
$$T \cap \varphi(S) \subseteq \varphi(S \cap \varphi^{-1} * T)$$
---
#### 4-40

> 设 f 为集合 X 映入到集合 Y 的映射,A 和 B 为 Y 的 子集,证明:
> $$(f^{-1} * A) \cap (f^{-1} * B) = f^{-1} * (A \cap B)$$

**证明**：

1) 若  $x \in (f^{-1} * A) \cap (f^{-1} * B)$ ,则  $x \in f^{-1} * A$  且  $x \in f^{-1} * B$ ,即  $f(x) \in A$  且  $f(x) \in B$ ,所以  $f(x) \in A \cap B$ ,即  $x \in f^{-1}(A \cap B)$ 。

2) 若  $x \in f^{-1} * (A \cap B)$ ,则  $f(x) \in A \cap B$ ,即  $f(x) \in A$  且  $f(x) \in B$ ,所以  $x \in f^{-1} * A$  且  $x \in f^{-1} * B$ ,所以  $x \in (f^{-1} * A) \cap (f^{-1} * B)$ 。

由此证得
$$(f^{-1} * A) \cap (f^{-1} * B) = f^{-1} * (A \cap B)$$

---
#### 4-41

> 证明任意一个非空集的反映射是非空的,当且仅当 f 是满射的。

**证明**：

1) 设  $f: X \rightarrow Y$  为满射, $A \subseteq Y \coprod A \neq \emptyset$ ,则必存在 y,使得  $y \in A$ ,因为 f 是满射,故必有一个 x 使得 f(x) = y,而这个 x 是属于  $f^{-1} * A$ 。这说明,若 f 是满射,则任意非空子集的反映射 是非空的。

2) 假定 f 不是一个满射,则  $f * X \neq Y$ ,故  $Y - f * X \neq \emptyset$ ,集 合 Y - f \* X 是非空的,但它的反映射为空,这证明了若 f 不是满射,则存在一个非空集,它的反映射为空。

---
#### 4-42

> 设  $f: X \rightarrow Y, A \subseteq Y$ ,证明
> $$f * (f^{-1} * A) = A \cap (f * X)$$

**证明**：

因为  $f^{-1} * A \subseteq X$ ,故由习题 4-23, $f * (f^{-1} * A) \subseteq f * X$ ,故  $y \in f * (f^{-1} * A) \Rightarrow y \in f * X$  但  $y \in f * (f^{-1} * A)$  也表示存在一个  $x \in f^{-1} * A$ ,使得 y = f(x) 且  $y \in A$ ,所以

$$f * (f^{-1} * A) \subseteq A \cap (f * X)$$

反之,若  $y \in A \cap (f * X)$ ,则  $y \in A$  且  $y \in f * X$ ,故得到  $y \in A$ ,

且存在一个  $x \in X$ ,使 y = f(x)。而一方面有:  $x \in f^{-1} * A$ ,故  $y \in f * (f^{-1} * A)$ ,即

$$A \cap (f * X) \subseteq f * (f^{-1} * A)$$

由此证得  $f*(f^{-1}*A)=A\cap (f*X)$

---
#### 4-43 证明 若  $f: X \rightarrow Y, A \subseteq X, B \subseteq Y, 则:$

a)  $f * (A \cap f^{-1} * B) = (f * A) \cap B$ ;
b)  $A \cap f^{-1} * B \subseteq f^{-1} * [(f * A) \cap B]_{\bullet}$

a) 先证  $f * (A \cap f^{-1} * B) \subseteq (f * A) \cap B$ 。

因为
$$f * (A \cap f^{-1} * B) \subseteq (f * A) \cap f * (f^{-1} * B)$$

=  $(f * A) \cap (B \cap f * X)$

$$=(f*A)\cap (f*X)\cap B=(f*A)\cap B$$

再证 $(f*A) \cap B \subseteq f*(A \cap f^{-1}*B)$ 。

设  $y \in (f * A) \cap B$ ,则  $y \in f * A$ ,且  $y \in B$ ,所以存在一个  $x \in A$ ,使得 f(x) = y,因为  $f(x) \in B$ ,我们有  $x \in f^{-1} * B$ ,所以有  $x \in (A \cap f^{-1} * B)$ ,于是  $y \in f * (A \cap f^{-1} * B)$ 。

综上得  $f*(A \cap f^{-1}*B) = (f*A) \cap B$

b) 设 $x \in A$ ,则 $f(x) \in f * A$ ,所以 $x \in f^{-1} * (f * A)$ ,所以我们有 $A \subseteq f^{-1} * (f * A)$ ,故

$$A \cap f^{-1} * B \subseteq f^{-1} * (f * A) \cap f^{-1} * B$$

由习题 4-40 知

$$f^{-1} * (f * A) \cap f^{-1} * B = f^{-1} * [(f * A) \cap B]$$

于是得  $A \cap f^{-1} * B \subseteq f^{-1} * [(f * A) \cap B]$

---
#### 4-44

> 设函数  $g:S \rightarrow T, f:T \rightarrow S$ ,证明:
> - a)  $f: T \rightarrow S$ , 有一个左逆, 当且仅当 f 是入射的;
> - b)  $f: T \rightarrow S$ , 有一个右逆, 当且仅当 f 是满射的;
> - c) 若 g 是 f 的左逆和右逆,则 f 是一个双射,且  $g=f^{-1}$ 。
> [4-2.(6)]

**证明**：

a) 若 f 存在一个左逆 g,则  $g \circ f(t) = t$ ,故  $g \circ f$  是人射,由习题 4-28b)得到 f 是入射的。

反之,若f是入射, $f: T \rightarrow S$ ,选择任一元素  $c \in T$ ,定义 g 如

下: $g:S\to T$ ,使得

$$\begin{cases} g(s) = t, & \text{ if } s \in f(T), \text{ if } f(t) = s \\ g(s) = c, & \text{ if } s \notin f(T) \end{cases}$$

对每个变元  $s \in S$ , g(s) 只有一个值, 且若 f(t) = s,则  $g \circ f(t) = g(s) = t$ ,故  $g \in f$  的左逆,即若  $f \in f$  是入射的,则必能构造函数 g,使  $g \to f$  的左逆。

b) 若 f 存在一个右逆,则  $f \circ g(s) = S$ ,对每个  $s \in S$ ,因为 g 是函数,必有 g(s) = t,且 f(t) = s,故 f 是满射的。

反之,若 f 是满射,即对每个  $s \in S$ ,则至少存在一个  $t \in T$  使 f(t) = S,现构造 g 如下:对每个  $s \in S$  有

(1) 若仅有一个  $t \in T$ ,使 f(t) = S,则取 g(s) = t;
(2) 若有  $t_1$ ,  $t_2$ , ...,  $t_k \in T$ , 使  $f(t_1) = f(t_2) = \dots = f(t_k) = S$ 。 则取某一  $t_i$ , 使  $g(s) = t_i$ , 这样对每个  $s \in S$ , g 只有一个值,且  $f \circ g(s) = S$ , 故  $g \neq f$  的右逆。
c) 由 a),b)可证得 g 是 f 的左逆和右逆,则 f 是满射和入射,故 f 是双射,由逆函数定义证得  $g=f^{-1}$ 。

---
#### 4-46

> 4-46** 设  $f: X \rightarrow Y$ ,对所有  $A, B \in \mathcal{P}(Y)$ ,  $\overline{f}$  的定义如上题,  $\overline{f}$   $(A-B) = \overline{f}(A) - \overline{f}(B)$ 成立吗?

**证明**：

成立。因为对任意  $x \in f^c(A-B)$ ,当且仅当存在一个  $y \in (A-B)$ ,使得 $\langle x, y \rangle \in f$ 。当且仅当

$$y \in A \land y \notin B \land y = f(x)$$

即

$$x \in \overline{f}^c(A) \land x \notin \overline{f}^c(B)$$

即

$$x \in (\overline{f}^c(A) - \overline{f}^c(B))$$

所以有

$$\overline{f}^{c}(A-B) = \overline{f}^{c}(A) - \overline{f}^{c}(B)$$

---
#### 4-47

> 设  $f: X \to Y$ ,对每个  $i \in I$ ,令  $A_i \in \mathcal{P}(X)$ ,证明:
> - 1)  $\overline{f}(\bigcap_{i\in I}A_i)\subseteq\bigcap_{i\in I}\overline{f}(A_i)$ 成立;
> - 2) 对 $\bigcap_{i\in I}\overline{f}(A_i)\subseteq\overline{f}(\bigcap_{i=I}A_i)$ ,给出一个反例说明不成立。

**证明**：

1) 若  $y \in \overline{f}(\bigcap_{i \in I} A_i)$ ,则必存在一个 x,使得 y = f(x) 对所有  $i \in I$ , $x \in A_i$ ,这就推出,对所有  $i \in I$ , $x \in \overline{f}(A_i)$ ,因此  $x \in I$

所以
$$\overline{f}(\bigcap_{i\in I}A_i)\subseteq\bigcap_{i\in I}\overline{f}(A_i)$$
成立。

2)设
$$I=2, A_0 = \{0,1\}, A_1 = \{0,2\}, 有$$

$$f = \{(0,0), (1,1), (2,1)\}$$
则  $\overline{f}(A_0) = \{0,1\}, \overline{f}(A_1) = \{0,1\}$
故  $\bigcap_{i \in I} \overline{f}(A_i) = \{0,1\}, \overline{f}(\bigcap_{i \in I} A_i) = \{0\}$

所以 $\bigcap_{i\in I} \overline{f}(A_i) \subseteq \overline{f}(\bigcap_{i\in I} A_i)$ 不成立。

---
#### 4-48

> 证明,对于所有的 $x \in E$ 有:
> - a)  $\psi_A(x) \leqslant \psi_B(x)$ ,当且仅当  $A \subseteq B$ ;
> - b)  $\psi_{A\cap B}(x) = \min(\psi_A(x), \psi_B(x));$
> - c)  $\psi_{A\cup B}(x) = \max(\psi_A(x), \psi_B(x));$
> - d)  $\psi_{A-B}(x) = \psi_A(x) \psi_{A \cap B}(x)$ .
> [4-3.(1)]

**证明**：

a) 设  $\psi_A(x) \leq \psi_B(x)$ ,对所有  $x \in A$ , $\psi_A(x) = 1$ 。因为  $\psi_A(x) \leq \psi_B(x)$ ,故  $\psi_B(x) = 1$ ,得  $x \in B$ ,所以  $A \subseteq B$ 。

反之,若  $A\subseteq B$ ,对任意 x 有下列情况:

1)  $x \in A, \emptyset x \in B, \psi_A(x) = \psi_B(x) = 1;$
2)  $x \notin A$ ,  $\emptyset$   $\begin{cases} x \in B, \psi_A(x) = 0, \psi_B(x) = 1 \\ x \notin B, \psi_A(x) = 0, \psi_B(x) = 0. \end{cases}$

总之, $\psi_A(x) \leqslant \psi_B(x)$ 。

b) 对所有  $x \in E$ ,
1)  $x \in A \cap B \Rightarrow x \in A \land x \in B$  $\Rightarrow \psi_A(x) = 1 \land \psi_B(x) = 1$

所以  $\psi_{A\cap B}(x) = \min(\psi_A(x), \psi_B(x)) = 1$

2)  $x \notin A \cap B \Rightarrow x \notin A \lor x \notin B$

$$\Rightarrow \psi_A(x) = 0 \lor \psi_B(x) = 0$$

所以

$$\psi_{A\cap B}(x) = \min(\psi_A(x), \psi_B(x)) = 0$$

$\psi_{A\cap B}(x) = \min(\psi_A(x), \psi_B(x))$

c) 对所有  $x \in E$ ,
1)  $x \in A \cup B \Rightarrow x \in A \lor x \in B$  $\Rightarrow \phi_A(x) = 1 \lor \phi_B(x) = 1$

所以
$$\psi_{AUB}(x) = \max(\psi_A(x), \psi_B(x)) = 1$$

$$x \notin A \cup B \Rightarrow x \notin A \land x \notin B$$

$$\Rightarrow \psi_{A}(x) = 0 \land \psi_{B}(x) = 0$$
所以  $\psi_{A \cup B}(x) = \max(\psi_{A}(x))$

$$\psi_{B}(x) = 0$$
总之、
$$\psi_{A \cup B}(x) = \max(\psi_{A}(x), \psi_{B}(x))$$
d)  $\psi_{A-B}(x) = \psi_{A \cap A}(x)$

$$= \psi_{A}(x) \cdot \psi_{A}(x)$$

$$= \psi_{A}(x) \cdot \psi_{A}(x)$$

$$= \psi_{A}(x) \cdot \psi_{A}(x)$$

$= \varphi_A(x) - \varphi_{A \cap B}(x)$  **4-49** 设  $E = [0,1], A = \left[\frac{1}{2},1\right],$  画出  $\varphi_A(x)$  的图。

[4-3,(2)]

$=\psi_A(x)-\psi_A(x)*\psi_B(x)$

$$\phi_{A}(x) = \begin{cases} 1, x \in \left[\frac{1}{2}, 1\right] \\ 0, x \in \left[0, \frac{1}{2}\right] \end{cases}$$

其图如图 4-1 所示。

图 4-1

---
#### 4-50 设  $S=(A\cap B)\cup(\sim A\cap C)\cup(B\cap C)$ ,这里 A,B,C 是全集 E 的子集,对于  $\varphi_A(x)$ , $\varphi_B(x)$  和  $\varphi_C(x)$  的值的所有可能组合,试求出  $\varphi_S(x)$ 的值,并构成集的成员表。

| 屛 | $\psi_A(x)$ | $\psi_B(x)$ | $\psi_{\mathcal{C}}(x)$ | $\psi_{A\cap B}(x)$ | $\psi_{A\cap C}(x)$ | $\psi_{B\cap C}(x)$ | S |
|---|-------------|-------------|-------------------------|---------------------|---------------------|---------------------|---|
|   | 0           | 0           | 0                       | 0                   | 0                   | 0                   |
|   | 0           | 0           | 1                       | 0                   | 1                   | 0                   |
|   | 0           | 1           | 0                       | 0                   | 0                   | 0                   |
|   | 0           | 1           | 1                       | 0                   | 1                   | 1                   |
|   | 1           | 0           | 0                       | 0                   | 0                   | 0                   |
|   | 1           | 0           | 1                       | 0                   | 0                   | 0                   |
|   | 1           | 1           | 0                       | 1                   | 0                   | 0                   |
|   | 1           | 1           | 1                       | 1                   | 0                   | 1 1                 |

---
#### 4-51

> 设A,B是E上的两个模糊子集,它们的并集 $A \cup B$
> 和交集  $A \cap B$  都仍然是模糊子集,它们的隶属函数分别定义为:
> $$C' = A \cup B \Leftrightarrow \mu_{C'} = \max(\mu_A, \mu_B)$$
> $$C' = A \cap B \Leftrightarrow \mu_{C'} = \min(\mu_A, \mu_B)$$
> 证明模糊集 U 和 \ \ 运算满足幂等律,交换律,结合律,吸收律,分配

**证明**：

1) A为 E 上的任意模糊子集:

$$\underset{A \cup A = A}{\overset{A}{\cup}} = \underset{C}{\overset{C}{\otimes}} \mu_{\overset{C}{C}} = \max(\mu_{\overset{A}{\mathcal{L}}}, \mu_{\overset{A}{\mathcal{L}}}) = \mu_{\overset{A}{\mathcal{L}}}$$

所以

$$\underbrace{A \cap A}_{A} = \underbrace{C}_{B} \Leftrightarrow \mu_{\underline{C}'} = \min(\mu_{\underline{A}}, \mu_{\underline{A}}) = \mu_{\underline{A}}$$

$$\underbrace{A \cap A}_{A} = \underbrace{A}_{B}$$

所以

2) 设
$$C = A \cup B \Leftrightarrow \mu_{C'} = \max(\mu_{A}, \mu_{B})$$

$= \max(\mu_{B}, \mu_{A}) \Leftrightarrow B \cup A = C$

所以

$$A \cup B = B \cup A$$

同理,设  $C' = A \cap B \Leftrightarrow \mu_{C'} = \min(\mu_{A}, \mu_{B}) = \min(\mu_{B}, \mu_{A})$  $\Leftrightarrow B \cap A = C$

所以

$$A \cap B = B \cap A$$

3) 设  $C' = A \cap (A \cup B) \Leftrightarrow \mu_{C'} = \min(\mu_A, \max(\mu_A, \mu_B)) = \mu_A,$ 所以  $A \cap (A \cup B) = A$

同理,设

$$\underline{C}' = \underline{A} \cup (\underline{A} \cap \underline{B}) \Leftrightarrow \mu_{\underline{C}'} = \max(\mu_{\underline{A}}, \min(\mu_{\underline{A}}, \mu_{\underline{B}})) = \mu_{\underline{A}}$$

所以

$$A \cup (A \cap B) = A$$

4) 设
$$C' = A \cap (B \cap C) \Leftrightarrow \mu_{C'} = \min(\mu_A, \min(\mu_B, \mu_C))$$

=  $\min(\min(\mu_A, \mu_B), \mu_C) \Leftrightarrow C' = (A \cap B) \cap C$

所以

$$A \cap (B \cap C) = (A \cap B) \cap C$$

同理  $C' = A \cup (B \cup C) \Leftrightarrow \mu_{C'} = \max(\mu_A, \max(\mu_B, \mu_C))$ =  $\max(\max(\mu_A, \mu_B), \mu_C) \Leftrightarrow C' = (A \cup B) \cup C$

所以  $A \cup (B \cup C) = (A \cup B) \cup C$

5) 设
$$\underline{C}' = \underline{A} \cup (\underline{B} \cap \underline{C}) \Leftrightarrow \mu_{\underline{C}'} = \max(\mu_{\underline{A}}, \min(\mu_{\underline{B}}, \mu_{\underline{C}}))$$

$= \min(\max(\mu_{\underline{A}}, \mu_{\underline{B}}), \max(\mu_{\underline{A}}, \mu_{\underline{C}}))$

$$\Leftrightarrow \underline{C}' = (\underline{A} \cup \underline{B}) \cap (\underline{A} \cup \underline{C})$$

所以

$$A \cup (B \cap C) = (A \cup B) \cap (A \cup C)$$

同理,设  $C' = A \cap (B \cup C) \Leftrightarrow_{\mu_{C'}} = \min(\mu_{A}, \max(\mu_{B}, \mu_{C}))$  $= \max(\min(u_{A}, \mu_{B}), \min(\mu_{A}, \mu_{C}))$

$$\Leftrightarrow \underline{C}' = (\underline{A} \cap \underline{B}) \cup (\underline{A} \cap \underline{C})$$

所以

$$A \cap (B \cup C) = (A \cap B) \cup (A \cap C)$$

---
#### 4-52 设  $\psi_A: X \to \{0,1\}$ 为 X 的子集 A 所定义的 X 的特征函数,证明  $\Phi: \mathcal{P}(X) \to \{0,1\}^X$  是双射。这里  $\Phi(A) = \psi_A, A \subseteq X$ 。

$\Phi$  是  $\mathcal{P}(X)$  到  $\{0,1\}^X$  的一个函数,假定  $\Phi(A) = \Phi(B)$ ,则  $\psi_A = \psi_B$ 。 对所有  $x \in X$ ,  $\psi_A(x) = \psi_B(x)$ ,因为  $y \in A \Leftrightarrow \psi_A(y) = 1 \Leftrightarrow \psi_B(y) = 1 \Leftrightarrow y \in B$ ,即 A = B,所以  $\Phi$  是入射。

对任意  $f \in \{0,1\}^X$ ,定义  $A = \{x \mid x \in X \land f(x) = 1\}$ ,则  $A \in \mathcal{P}(X)$ 且  $\Phi(A) = f$ ,所以  $\Phi$  是满射。

---
#### 4-54

> 4-54** U4 是什么, ∩4 又是什么?

**解**：

$$4=\{\emptyset, \{\emptyset\}, \{\emptyset, \{\emptyset\}\}, \{\emptyset, \{\emptyset\}\}, \{\emptyset, \{\emptyset\}\}\}\}\}$$

$0$   $0$   $0$   $0$   $0$   $0$   $0$   $0$   $0$   $0$

---
#### 4-55

> 设  $A = \{1\}$ , 计算  $A^+$ ,  $U(A^+)$ ,  $U(\{2\}^+)$ 。

**解**：

$$A^+ = A \cup \{A\} = \{1\} \cup \{\{1\}\} = \{1, \{1\}\}\}$$

$\cup (A^+) = \cup \{1, \{1\}\} = \cup \{\{\emptyset\}, \{\{\emptyset\}\}\}\}$
$= \{\emptyset, \{\emptyset\}\} = 2$
$\cup (\{2\}^+) = \cup (\{2\} \cup \{\{2\}\}) = \cup \{2, \{2\}\}\}$

$$= \bigcup \{ \{\emptyset, \{\emptyset\}\}, \{\{\emptyset, \{\emptyset\}\}\}\} \}$$

$$= \{\emptyset, \{\emptyset\}, \{\emptyset, \{\emptyset\}\}\} \}$$

$$= \{0, 1, 2\} = 3$$

---
#### 4-56

**证明**：

若 a 是可递集,则 a+是可递集。

$$a^+ = a \cup \{a\}$$
$\bigcup (a^+) = \bigcup (a \bigcup \{a\}) = (\bigcup a) \bigcup (\bigcup \{a\}) = (\bigcup a) \bigcup a$ 因为 a 是可递集,故 $\bigcup a \subseteq a$ ,由子集定理得:
$$(\bigcup a)\bigcup a=a$$
所以 $a^+=a$ 是可递集。
---
#### 4-57

> 试证:A 是可递集,当且仅当 $\mathcal{P}(A)$ 是可递集。

**证明**：

1) 若 A 是可递集,则  $A \subseteq \mathcal{P}(A)$ 。由习题 3-9,得  $\mathcal{P}(A) \subseteq \mathcal{P}(\mathcal{P}(A))$

故 $\mathcal{P}(A)$ 是可递集。

2) 若 $\mathcal{P}(A)$ 是可递集,则 $\cup$   $\mathcal{P}(A)$  $\subseteq$   $\mathcal{P}(A)$ ,但是 $\cup$   $\mathcal{P}(A)$ = A,故有 A $\subseteq$   $\mathcal{P}(A)$ ,由可递集等价定义,所以 A 是可递集。

---
#### 4-58

**证明**：

若 A 是可递集,则 U A 也是可递集。
因为 A 是可递集,故有  $UA \subseteq A$ 。对任意  $y \in UA$ ,必有  $y \in A$ ,所以  $y \subseteq A$ ,得  $y \subseteq UA$ 。因此  $y \in UA \Rightarrow y \subseteq UA$ ,即 UA 是可递集。
---
#### 4-59

> 假定 A 的每个成员是可递集,证明:
> - a) UA 是可递集;
> - b) ∩ A 是可递集(设 A 是非空集)。

**证明**：

a) 对任意  $x \in \bigcup A \Rightarrow \exists a \in A, x \in A, a \subseteq \bigcup A, 因为 a$  是可递集,所以

$x\in a\Rightarrow x\subseteq a\subseteq \bigcup A$  即  $x\in \bigcup A\Rightarrow x\subseteq \bigcup A$  所以 $\bigcup A$  是可递集。

b) 对所有  $x \in \bigcap A \Rightarrow x \in a$ ,  $\forall a \in A$ , 因 a 是可递集, 故  $x \in a$ ,  $\forall a \in A \Rightarrow x \subseteq a$ ,  $\forall a \in A$ , 故对所有  $u \in x$  则  $u \in a$ , 且  $\forall a \in A$ , 即对任意  $u \in x$ ,  $u \in \bigcap A$ , 所以  $x \subseteq \bigcap A$ 。故由此证得

$$x \in \bigcap A \Rightarrow x \subseteq \bigcap A$$

于是∩A 是可递集。

---
#### 4-60 设 S 为集合 $\langle 1, 0 \rangle$ 。

a) 试找出可递集  $T_1$ ,使  $S \subseteq T_1$ ;
b) 试找出可递集  $T_2$ ,使  $S \in T_2$ 。

因为
$$\langle 1,0 \rangle = \{\{1\},\{1,0\}\} = \{\{\emptyset\},\{\emptyset,\{\emptyset\}\}\}\}$$

$$T_1 = \{\{\{\emptyset\}\}, \{\emptyset, \{\emptyset\}\}, \{\emptyset\}, \emptyset\} = \{\{1\}, 2, 1, 0\}\}$$

$$T_2 = \{\{\{\{\emptyset\}\}, \{\emptyset, \{\emptyset\}\}\}, \{\{\emptyset\}\}, \{\{\emptyset\}\}, \{\emptyset\}\}, \{\emptyset\}, \emptyset\}\}$$
$$= \{\{\{1\}, 2\}, \{1\}, 2, 1, 0\}$$

---
#### 4-61

> 对下列每组集合 A 和 B,构造一个从 A 到 B 的双射函数,以说明 A 和 B 具有相同的势。
> a)
> $$A=(0,1), B=(0,2);$$
> - b)  $A=N,B=N\times N$ ;
> - c)  $A=I\times I, B=N;$
> - d)  $A=R, B=(0,\infty);$
> e)
> $$A = [0,1), B = \left(\frac{1}{4}, \frac{1}{2}\right].$$
> [4-4.(1)]

**解**：

a) 作双射  $f:A \rightarrow B$ ,使得 f(x) = 2x,  $x \in A$ 。

b)
$$\emptyset$$
$A = \{0,1,2,3,4,5,\cdots\}$

其对应 B 可按序偶次序记为:

$$B = \{\langle 0, 0 \rangle, \langle 0, 1 \rangle, \langle 1, 0 \rangle, \langle 0, 2 \rangle, \langle 1, 1 \rangle, \langle 2, 0 \rangle, \langle 0, 3 \rangle, \langle 1, 2 \rangle, \langle 2, 1 \rangle, \langle 3, 0 \rangle, \cdots \}$$

c) 设
$$f: N \to I, P(n) = -\frac{1}{2}n,$$
当  $n$  为偶数,  $P(n) = \frac{1}{2}(n+1)$

1), 当 n 为奇数, 故 f 为双射, 令  $g: N \times N \rightarrow I \times I$ , g 为双射。

d) 设
$$f:A \rightarrow B$$
,  $f(x) = \tan \frac{\arctan x + \frac{\pi}{2}}{2}$ ,  $x \in A$ .

e) 设
$$f:A \rightarrow B, f(x) = -\frac{1}{4}x + \frac{1}{2}, x \in [0,1)$$
。

---
#### 4-62

> 证明(0,1)与[0,1)等势,[0,1)与[0,1]等势。
> [4-4.(2)]

**证明**：

a) 设
$$A = \left\{ \frac{1}{2}, \frac{1}{3}, \frac{1}{4}, \dots, \frac{1}{n}, \dots \right\}$$
,作 $f: (0,1) \rightarrow [0,1)$

如下:

$$\begin{cases} f\left(\frac{1}{2}\right) = 0 \\ f\left(\frac{1}{n}\right) = \frac{1}{n-1}, x \in A \land n > 2 \\ f(x) = x, x \in (0,1) - A \end{cases}$$

b) 设
$$A = \left\{0, \frac{1}{2}, \frac{1}{3}, \frac{1}{4}, \cdots\right\}$$
,作  $f:[0,1) \to [0,1]$ 如下:
$$\begin{cases} f(0) = 0 \\ f\left(\frac{1}{n}\right) = \frac{1}{n-1}, n > 1, \frac{1}{n} \in A \\ f(x) = x, x \in [0,1) - A \end{cases}$$

---
#### 4-63

> 若  $X_1 \sim X_2$  和  $Y_1 \sim Y_2$ ,且  $X_1 \cap Y_1 = X_2 \cap Y_2 = \emptyset$ ,试证: $X_1 \cup Y_1 \sim X_2 \cup Y_2$ 。
> [!tip] 4-4.(3)
> 

**证明**：

$X_1 \sim X_2$ ,  $Y_1 \sim Y_2$ , 均存在双射  $f: X_1 \rightarrow X_2$ ,  $g: Y_1 \rightarrow Y_2$ , 设  $f \cup g = h$ , 作  $h: X_1 \cup Y_1 \rightarrow X_2 \cup Y_2$ , 现在证明 h 是双射。

对任意  $x \in X_1 \cup Y_1$ ,必有  $x \in X_1$  或  $x \in Y_1$ ,但  $X_1 \cap Y_1 = \emptyset$ ,故  $x \in X_1$  或  $x \in Y_1$ ,而且仅有一式成立,若  $x \in X_1$ ,则因 f 为双射,必有唯一  $y \in x_2$ ,使 f(x) = y;若  $x \in Y_1$ ,则因 g 为双射,必有唯一  $y \in Y_2$ ,使 g(x) = y。由  $X_2 \cap Y_2 = \emptyset$ ,故  $f(x) \neq g(x)$ 。所以在 h 中,对任意  $x \in X_1 \cup Y_1$ ,仅有唯一的  $y \in X_2 \cup Y_2$  且  $x_1 \neq x_2$  时  $y_1 \neq y_2$ ,因此 h 是入射的。

其次,对任意  $y \in X_2 \cup Y_2$ ,则  $y \in X_2$  或  $y \in Y_2$ ,因  $X_2 \cap Y_2 = \emptyset$ ,故  $y \in X_2$ ,或  $y \in Y_2$  而且仅有一式成立。若  $y \in X_2$ ,因为 f 是满射的,故必有  $x \in X_1$ ,使 f(x) = y。若  $y \in Y_2$ ,因为 g 是满射,故必有  $x \in Y_1$ ,使 g(x) = y,由  $X_1 \cap Y_1 = \emptyset$ ,故对任一  $y \in X_2 \cup Y_2$ ,必有唯一  $x \in X_1 \cup Y_1$ ,使 h(x) = y,故 h 是满射的。

综上 h 为双射,故  $X_1 \cup Y_1 \sim X_2 \cup Y_2$ 。

---
#### 4-64 证明[0,1],(0,1),(0,2), $(-\infty,+\infty)$ 等势。

a) 作  $f:[0,1] \rightarrow (0,1)$  双射如下:

定义
$$A = \left\{0, 1, \frac{1}{2}, \frac{1}{3}, \dots, \frac{1}{n}, \dots\right\}$$

$$\begin{cases} f(0) = \frac{1}{2} \\ f\left(\frac{1}{n}\right) = \frac{1}{n+2} & \text{if } n \ge 1, \frac{1}{n} \in A \\ f(x) = x & x \in [0,1] - A \end{cases}$$

b) 作  $g:(0,1)\to(0,2)$  双射如下:

$$g(x) = 2x$$

c) 作  $h:(-\infty,+\infty)\to(0,1)$  双射如下:

$$h(Z) = \frac{1}{\pi} \arctan Z + \frac{1}{2}$$

---
#### 4-66

> 4-66** 证明:若 $A \sim B$ ,则 $A^c \sim B^c$ 。

**证明**：

*证明** 因为  $A \sim B$ ,故存在  $\varphi: A \rightarrow B$ ,使得  $\varphi$  为双射。对任意  $f \in A^c$ ,定义  $\psi: A^c \rightarrow B^c$  为  $\psi(f) = \varphi \circ f$ ,因为  $\varphi$  为人射的,设有  $g \in A^c$ ,则( $\varphi \circ f = \varphi \circ g$ )  $\Rightarrow f = g$ ,这是因为若( $\varphi \circ f = \varphi \circ g$ )  $\Rightarrow f \neq g$ ,则必有某个  $x_1 \in C$ ,使得:  $f(x_1) \neq g(x_1)$ ,故  $\varphi(f(x_1)) = \varphi(g(x_1))$ 有  $f(x_1) \neq g(x_1)$ ,即  $\varphi$  不是人射,与  $\varphi$  是双射的条件矛盾。

因为  $\psi(f) = \varphi \circ f$ ,  $\psi(g) = \varphi \circ g$ , 故  $\psi(f) = \psi(g) \Rightarrow f = g$ , 所以  $\psi$  是入射的。

其次,设 $h \in B^c$ , $\phi(\varphi^{-1} \circ h) = \varphi \circ \varphi^{-1} \circ h = h$ ,这里: $\varphi^{-1} \circ h \in A^c$ , 所以对任意 $h \in B^c$  必有 $\varphi^{-1} \circ A \in A^c$ ,使满足 $\phi(\varphi^{-1} \circ h) = h$  成立,即 $\phi$ 是满射。

综上 $\phi$ 是双射,故  $A^{\circ}\sim B^{\circ}$  成立。

---
#### 4-67

> 设 A 为任意一个集合, $n \in N$ ,定义 S 为从 $\{0,1,2,\cdots,n-1\}$ 到 A 的所有映射的集合,定义 T 为 A 的元素的所有 n 元组的集合,即  $T = \{\langle a_0, a_1, a_2, \cdots, a_{n-1} \rangle | a_i \in A \}$ ,证明从 S 到 T 存在一个双射。

**证明**：

设  $S=A^{\{0,1,2,\cdots,n-1\}}$

$$T=A^n=\{\langle a_0,a_1,a_2,\cdots,a_{n-1}\rangle \mid a_i\in A\}$$

定义映射  $g:S \rightarrow T$  如下:对任意  $f \in S$ ,有  $g(f) = \langle f(0), f(1), \dots, f(n-1) \rangle$

现在证明 g 是双射的。

a) 假定  $f_1, f_2 \in S$ ,且  $f_1 \neq f_2$ ,则对某个 k,0 $\leq k \leq n$ ,  $f_1(k) \neq f_2(k)$ ,故  $g(f_1) \neq g(f_2)$ ,因此 g 是入射。
b) 设有 n 元组 $\langle a_0, a_1, \dots, a_{n-1} \rangle \in A^n$ ,令函数 f 为

$$f:\{0,1,2,\cdots,n-1\}\rightarrow A, \forall 0 \leq i \leq n, f(i)=a_i$$

则在 g 的作用下,函数 f 的像是 $\langle a_0, a_1, \dots, a_{n-1} \rangle$ 。因此对任意一个 $\langle a_0, a_1, \dots, a_{n-1} \rangle \in T$ ,必存在一个  $f \in S$  使得

$$g(f) = \langle f(0), f(1), f(n-1) \rangle = \langle a_0, a_1, \dots, a_{n-1} \rangle$$

因此 g 是满射的,所以 g 是双射。

---
#### 4-68

> 设 S 表示  $A = \{a_1, a_2, \dots, a_n\}$  到  $\{0,1\}$  的一切映射构成的集合,即
> $$S = \{0,1\}^A = \{f | f: A \rightarrow \{0,1\}\}$$
> $$\mathcal{P}(A) \sim S$$
> 求证

**证明**：

任取  $B\subseteq A$ ,则  $B\in \mathcal{P}(A)$ 。作映射  $f_B:A\longrightarrow \{0,1\}$ ,使

$$f_B(x) = \begin{cases} 0, \not \le x \notin B \\ 1, \not \le x \in B \end{cases}$$

故  $f_B \in S$ 。

设  $\varphi$ :  $\mathcal{P}(A) \rightarrow S$ , 使  $\varphi(B) = f_B$ 。 现在证明  $\varphi$  是双射的。因为

(1) 设  $B_1 \in \mathcal{P}(A)$ ,  $B_2 \in \mathcal{P}(A)$ , 若  $B_1 \neq B$ , 则

$$f_{B_1} \neq f_{B_2}$$

因此, $\varphi$ 是入射的。

(2) 任取  $f_i \in S$ ,令  $B_i = \{x \mid x \in A \perp f_i(x) = 1\}$ ,则  $B \subseteq A$ ,且  $\varphi(B_i) = f_i$

故φ是满射的。

综上所述, $\varphi$ 为双射。故有

$$\mathcal{P}(A) \sim S$$

(注 由本题证明可知,  $\mathcal{P}(A)$ 也可记为  $2^{A}$ 。)

---
#### 4-69

> 下列集合 A 的势是什么?
> - a)  $A = \{\langle p, q \rangle | p, q$  都是整数 $\};$
> - b)  $A = \{\langle p, q \rangle | p, q$  都是有理数 $\}$ ;
> - c) A 是由所有半径为 1,圆心在 x 轴上的圆周所组成的集合:
> - d) A 是由实数轴上所有两两不相交的有限开区间组成的集合。 【4-5.(1)】

**解**：

a) 令  $f:A\rightarrow B$ ,使得  $f(\langle p,q\rangle)=p/q$ , f 为双射,所以  $A\sim B$ ,因为  $B=\{p/q\}$ ,  $K[B]=\aleph_0$ ,故 A 的势为  $\aleph_0$ 。

b) 与 a)相同,证得 K[A]= N₀。
c) 因为圆心在 x 轴上的圆周,半径均为 1,故这些圆周的集合,对应于 $(-\infty,\infty)$ 这个集合,所以其势为 $leph$
d) 实数轴上所有两两不相交的有限开区间组成的集合,其势为 №。。

---
#### 4-70 如果 A 是不可数无穷集,B 是 A 的可数子集,则(A B) $\sim A$ 。 【4-5.(2)】

设 P=A-B,则 P 不是有限集。因为  $P \cup B=A$ ,若 P 是有限集,B 必是可数集,于是 A 为可数集,与题设矛盾。故知 P

是无限集。由定理 4-5.2 知 P 必含可数子集 D,设 M=P-D,即  $P=M\cup D$ 。

由  $A=P\cup B=M\cup D\cup B$ ,因为 D,B 为可数集, $(D\cup B)\sim B$ ,  $M\sim M$ ,且  $M\cap (D\cup B)=\varnothing$ , $(M\cap B)=\varnothing$ ,由习题 4-63 得到  $M\cup D\cup B\sim M\cup D$

即  $A \sim P$ ,故

$$(A-B)\sim A$$

---
#### 4-71

> 如果 A 是任意无限集,M 是一个可数集,则
> $$(A \cup M) \sim A$$
> [4-5.(3)]

**证明**：

设 A 是任意无限集, M 是可数集:

1) 若 A 是可数无限集,则  $A \cup M$  是可数集,故

$$(A \cup M) \sim A$$

2) 若 A 是不可数无限集,因为 M—(A  $\cap$  M)  $\subseteq$  M  $\subseteq$  A  $\cup$  M ,由 定理 4-5.4,M—A  $\cap$  M 是可数集,但 A  $\cup$  M 为不可数无限集,由习 题 4-70 得

$$(A \cup M) - (M - A \cap M) \sim (A \cup M)$$

但

$$(A \cup M) - (M - A \cap M) = A$$

所以 $(A \cup M) \sim A$ 。

---
#### 4-73

> 4-73** 有限集 *A* 和可数集 *B* 的笛卡尔积集 *A*×*B* 是可数集吗?请予证明。 【4-5.(5)】

**证明**：

设有限集为 A,则  $A \cup N$  是可数集,由习题 4-72 可知  $(A \cup N) \times B$  是可数集。但  $A \times B \subseteq (A \cup N) \times B$ ,且  $A \times B$  是无限集,由定理 4-5.4 知可数集的任何无限子集是可数的,故  $A \times B$  为可数集。

设 Q 为有理数集,R 为实数集,S 为无理数集。因为 Q 是可数集,S 为无限集,由习题 4-71 可知( $S \cup Q$ )  $\sim S$ ,但  $S \cup Q = R$ ,所以  $S \sim R$ 。

于是 K[S]=K[R]= %。

---
#### 4-75

> 令  $K[A] = \aleph$, K[B] = \aleph$, K[D] = \aleph$_0$ ,这里 A, B, D 为互不相交集合,证明以下各式:
> a)  $K[A \cup B] = \aleph$ ;
> b)
> $$K \lceil A \mid JB \rceil = \aleph_0$$
> [4-5.(7)]

**证明**：

a) 设
$$g_1: \left[0, \frac{1}{2}\right] \to \left[0, 1\right],$$

$$\begin{cases} g_1(x) = \frac{1}{(n-2)}, \text{$$

又设
$$g_2:\left[\frac{1}{2},1\right)\rightarrow [0,1],$$

$$g_2(x) = 2x - 1$$

$g_1$  和  $g_2$  是双射的,用这些函数构造[0,1]到  $A \cup B$  的双射如下:  $h_1[0,1] \rightarrow A \cup B$

$$h(x) = f_A \circ g_1(x)$$
,若  $x \in \left[0, \frac{1}{2}\right)$

$$h(x) = f_B \circ g_2(x)$$
,若 $x \in \left[\frac{1}{2}, 1\right]$

因为  $A \cap B$  是不相交的,故 h 是从[0,1]到  $A \cup B$  的双射,所以  $K[A \cup B] = \aleph$$

b) 因为  $K[D] = \aleph$_0$ , 故 D 为可数集, K[A] = \aleph$, A 为无限 $\aleph$, 由习题 4-71 得 $(A \cup D) \sim A$ 。故  $K[A \cup D] = K[A] = \aleph$_0$ 。

---
#### 4-76

> 用定理 4-6.2 证明[0,1],(0,1],[0,1),(0,1)**是等** 势的。 【4-6.(1)】

**证明**：

1) 作
$$f:[0,1] \to (0,1]$$
人射为  $f(x) = \frac{x}{2} + \frac{1}{2}$

作  $g:(0,1] \rightarrow [0,1]$  人射为 g(x) = x

# [0,1]~(0, 1]

2) 作
$$f:(0,1] \to [0,1)$$
人射为  $f(x) = \frac{1}{2} - \frac{x}{2}$

作
$$g:[0,1)\to(0,1]$$
人射为  $g(x)=1-x$

$(0,1]\sim[0,1)$

3) 作
$$f:(0,1) \rightarrow [0,1)$$
人射为  $f(x)=x$

作
$$g:[0,1)\to(0,1)$$
人射为  $g(x)=\frac{x}{2}+\frac{1}{4}$

故 [0,1)~(0,1)

4) 作  $f:(0,1) \to [0,1]$ 人射为 f(x) = x

作
$$g:[0,1] \to (0,1)$$
为  $g(x) = \frac{x}{3} + \frac{1}{4}$

$\phi$  (0,1)~[0,1]

由上证明可得

$$[0,1] \sim (0,1] \sim [0,1) \sim (0,1)$$

---
#### 4-77

**证明**：

若从 A 到 B 存在一个满射,则
$$K[B] \leqslant K[A]$$
[4-6.(2)]
设  $f:A \rightarrow B$  为满射函数。构造函数:
$$f_{\Delta} = \{\langle y, x \rangle \mid \langle x, y \rangle \in f \cdot$$
且若 A 中存在  $x_i$ , 使  $f(x_i) = y(i=1,2,\dots,n)$ ,则任取一个  $x_i^A$  使  $f_{\Delta}(y) = x_i^A$ ,所以  $f_{\Delta}: B \rightarrow A$  是入射函数,故
#### $K[B] \leq K \lceil A)$
#### 4-78 设 N 为自然数集,证明  $K[\mathcal{P}(N)]$ = **N**。 【4-6.(3)】
1) 先证 K[𝒯(N)]≪w。
构造  $g: \mathcal{P}(N) \rightarrow [0,1]$ 如下:
对每个  $S \in \mathcal{P}(N)$ ,即  $S \subseteq N$  定义  $g(S) = x_0 x_1 x_2 \cdots$ ,这里函数 g(S)用二进制表示,且规定
$$x_{2j} = 0, (j = 0, 1, 2, \cdots)$$
$x_{2j+1} = 1, \forall j \in S$
$x_{2j+1} = 0, j \notin S$
即是:
$$g(\varphi) = 0, g(N) = .01010101\cdots$$
$g(\{1,3,5\}) = .0001000100010000\cdots$
由 g 的构造知 g 是入射函数。所以  $K[\mathcal{P}(N)] \leqslant \aleph$ 。
2) 再证 $\mathbb{N} \leq K[\mathcal{P}(N)]$ 。
构造  $f:[0,1] \to \mathcal{P}(N)$ ,设  $x=.x_0x_1x_2$  …为  $x \in [0,1]$ 的二进制数表示,定义  $f(x)=\{i \mid x_i=1\}$ 。即是
$$f(0) = \emptyset$$
$f(1) = f(.1111 \cdots) = N$
$f(.10101010000 \cdots) = \{0, 2, 4\}$
所以 f 是[0,1]到  $\mathcal{P}(N)$ 的人射,故  $\mathbf{X} \leq K[\mathcal{P}(N)]$ ,由定理 4-6.2 可知  $K[\mathcal{P}(N)] = \mathbf{X}$ 。
[4-6.(4)]
根据定义  $N^N = \{f | f: N \rightarrow N\}$ 。
1) 先证 K[N<sup>N</sup>]≤N。
构造一个入射函数  $g: N^{N} \rightarrow (0,1)$ 如下:
设  $f \in N^N$  即  $f: N \to N$ ,对每个  $i \in N$  使 f(i) 的二进制表达式为  $x_i$ ,现构造  $g: N^N \to (0,1)$  定义  $g(f) = (.x_0 2x_1 2x_2 2x_3 2\cdots)$ ,其中 2 为分隔符。
例如
$$f: N \to N$$
定义为  $f(x) = 2x$  则  $f(0) = (0)_2, f(1) = (10)_2, f(2) = (100)_2$
$$f(3) = (110)_2, f(4) = (1000)_2 \cdots$$
$g(f) = .02102100211021000 \cdots$
若  $h: N \rightarrow N, h(x) = 3x,$
Mil
$$h(0) = (0)_2, h(1) = (11)_2$$
$h(2) = (110)_2, h(3) = (1001)_2$
$h(4) = (1100)_2 \cdots$
$g(h) = .021121102100121100 \cdots$
由 g 的构造可知  $g: N^N \to (0,1)$  ,是人射函数,因 K[(0,1)] = \aleph$,所以  $K[N^N] \le \aleph$$ 。
再证¥≤K[N<sup>N</sup>]。
构造人射函数  $S:(0,1) \rightarrow N^N$  如下:设  $x \in (0,1) x = .x_0 x_1 x_2 \cdots$  是 x 的十进制小数表示,(如  $0.2 = 0.1999 \cdots$ )定义  $S(x) = f \in N^N$ ,使  $f(0) = x_0$ , $f(1) = x_1$ , $f(2) = x_2 \cdots$ 。
由 S 的构造可知  $S_{\cdot}(0,1) \rightarrow N^{N}$  是入射函数。故必有:
$K \leq K[N^N]$
于是
$$K[N^N] = \aleph$$
---
#### 4-80

> 设 A,B,D 都是集合,且  $A \cap B = \emptyset$ , $A \cap D = B \cap D = \emptyset$ ,K[A] = a,K[B] = b,K[D] = d。若定义  $a + b = K[A \cup B]$ ; $a \cdot b = K[A \times B]$ ,求证:
> - a)  $\aleph + \aleph_0 = \aleph$ ;
> - b) 如果  $a \leq b$ ,则  $a+d \leq b+d$ ;
> - c) 如果  $a \leq b$ ,则  $a \cdot d \leq b \cdot d$ 。
> [4-6.(5)]

**证明**：

a) 令  $A = \{x \mid x \in R, \exists x \geqslant 1\}$

$$B = \left\{ \frac{1}{n+2} \, \middle| \, n \in N \right\}$$

则  $K[A] = \aleph$ ,  $K[B] = \aleph_0$ ,  $A \cap B = \emptyset$ ,  $A \cup B \subset R$ , 故可作入射函数  $f:(A \cup B) \rightarrow R$ , 所以  $K[A \cup B] \leq \aleph$ 。因为  $A \subseteq A \cup B$ , 故

$$K[A] \leq K[A \cup B]$$

即

$\mathbf{K} \leq K[A \cup B]$

所以

$$K[A \cup B] = \aleph$$

b) 因为 K[A]=a, K[b]=b,若  $a \leq b$ ,则必存在一个人射函数  $f:A \rightarrow B$ 。

再定义
$$g$$
如下:  $g:A \cup D \rightarrow B \cup D$ ,使
$$\begin{cases} g(x) = f(x), \text{ } \exists x \in A \\ g(x) = x, \text{ } \exists x \in D \end{cases}$$

则 g 是从  $A \cup D$  到  $B \cup D$  的一个入射,因此

$$K[A \cup D] \leq K[B \cup D]$$

由于 $A \cap D = B \cap D = \emptyset$ ,故得

$$a+d \leq b+d$$

c) 因为  $a \leq b$ ,故存在人射函数  $f: A \rightarrow B$ 。

再定义
$$g$$
为  $g:A\times D\to B\times D$ ,使得

$$g(\langle x,y\rangle) = \langle f(x),y\rangle$$

因为  $g(\langle x_1, y_1 \rangle) = g(\langle x_2, y_2 \rangle)$

有  $\langle f(x_1), y_1 \rangle = \langle f(x_2), y_2 \rangle$

故
$$f(x_1) = f(x_2) \land y_1 = y_2$$

由 f 是人射,得  $f(x_1) = f(x_2) \Rightarrow x_1 = x_2$ 。故有 $\langle x_1, y_1 \rangle = \langle x_2, y_2 \rangle$ ,于是 g 为人射函数,即:

$$K[A \times D] \leqslant K[B \times D]$$

于是 ad≤bd。

---
#### 4-82

> 4-82** 设 S 为基数的集合,证明:在 S 上的序关系≤是一个 线序,在 S 上的序关系<是一个拟序。

**证明**：

a) 首先证明在 S上的序关系是一个偏序。

1)设在 S 上有一个基数 a ,令 A 为一个集合,使有 : K[A] = a ,因为  $I_A$  是 A 到 A 的一个双射,所以 A 到 A 必有一个入射,故  $K[A] \leq K[A]$ ,即  $a \leq a$ ,故 S 上  $\leq$  是自反的。
2) 设  $a,b \in S$ , 假定  $a \le b$  和  $b \le a$ , 由定理 4-6.2 可得 a = b, 故 $\le$ 在 S上是反对称的。
3) 令 a,b,c 为 S 的元素,假定  $a \le b,b \le c$ ,且设 K[A]=a, K[B]=b,K[C]=c,由  $a \le b$  故有  $f:A \to B$  为入射;由  $b \le c$ ,故有  $g:B \to C$  为入射。设  $h=g\circ f$ ,由定理 4-2.2 得到 h 是入射,这 里  $h:A \to C$ ,故  $a \le c$  即  $\le$  在 S 上是传递的。

由此可知 $\leq$ 是 S上的偏序关系。由定理 4-6.1 可知,对基数 a < b < S,必有 a < b < b < a,a = b 三者之一成立,故必有  $a \leq b$ ,或  $b \leq a$ ,所以 $\leq$ 为 S上的线序。

b) 对任意  $a \in S$ , a < a 都不成立,故<是在 S 上反对称的。 又如设  $a,b,c \in S$ ,且 K[A]=a,K[B]=b,K[C]=c,如果 a < b, b < c,则

$f:A \rightarrow B$  是一个人射,但不是双射;  $q:B \rightarrow C$  是一个人射,但不是双射。

由定理 4-2.2,  $g \circ f : A \to C$  是一个人射且  $g \circ f$  不是双射, 故 K[A] < K[C], 即 a < c, 故 < 在 S 上是传递的。所以 < 是 S 上的 拟序。

---
#### 4-83

> 设 A,B,D 为集合,令  $K[A]=a,K[B]=b,K[D]=d,K[A\cup B]=a+b,K[A\times B]=a\cdot b,K[A^B]=a^b$ ,证明:
> a)
> $$a^{b+d} = a^b \cdot a^d$$
> ;
> b)
> $$(a \cdot b)^d = a^d \cdot b^d$$
> ;
> c)
> $$(a^b)^d = a^{b \cdot d}$$
> .

**证明**：

a) 设  $g: B \rightarrow A$  和  $h: D \rightarrow A$ ,因为  $B \cap D = \emptyset$ ,故有映射  $f: B \cup D \rightarrow A$ 。

构造函数  $F: A^{B} \times A^{D} \rightarrow A^{B \cup D}$  使得  $\varphi(\langle g, h \rangle) = f$ , 这里:

$$\begin{cases} f(x) = g(x), x \in B \\ f(x) = h(x), x \in D \end{cases}$$

函数  $\varphi$  是入射,因此  $K[A^B \times A^D] \leqslant K[A^{B \cup D}]$ 。

再定义 $\phi: A^{B \cup D} \rightarrow A^B \times A^D$ ,使 $\phi(f) = \langle g, h \rangle$ ,这里

$$\begin{cases} f(x) = g(x), x \in B \\ f(x) = h(x), x \in D \end{cases}$$

因为  $\phi = \varphi^{-1}$ ,所以  $\phi$  也是入射。则有

$$K[A^{B\cup D}] \leq K[A^B \times A^D]$$

于是  $K[A^{B\cup D}] = K[A^B \times A^D]$ ,即  $a^{b+d} = a^b \cdot a^d$ 。

b) 定义 $\Phi: A^{D} \times B^{D} \rightarrow (A \times B)^{D}$ ,使得:

$$(\Phi(f,g))(x) = \langle f(x), g(x) \rangle$$
(对所有  $x \in D$ )

设 $\Phi(f_1,g_1)=\Phi(f_2,g_2)$ ,则对所有 $x\in D$ ,有

$$(\Phi\langle f_1,g_1\rangle)(x)=(\Phi\langle f_2,g_2\rangle)(x)$$

即

$$\langle f_1(x), g_1(x) \rangle = \langle f_2(x), g_2(x) \rangle$$

亦即对所有  $x \in D$  有  $f_1(x) = f_2(x)$ ,  $g_1(x) = g_2(x)$ 。故有:  $f_1 = f_2$ ,  $g_1 = g_2$ 。即 $\langle f_1, g_1 \rangle = \langle f_2, g_2 \rangle$ , 所以  $\Phi$  是入射。

其次,对任意  $h \in (A \times B)^D$ ,  $h(x) \in A \times B$ ; 设  $h(x) = \langle h_1(x), h_2(x) \rangle$ ,则  $h_1 \in A^D$ ,  $h_2 \in B^D$ , 故  $\langle h_1, h_2 \rangle \in A^D \times B^D$ 。设  $\Phi(\langle h_1, h_2 \rangle) = h$ ,则对所有  $x \in D$ 有

$$\Phi(\langle h_1,h_2\rangle)(x) = \langle h_1(x),h_2(x)\rangle = h(x)$$

故

综上可知 Φ 是双射,因此

$$K[A^{D} \times B^{D}] = K[(A \times B)^{D}]$$
$$a^{d} \cdot b^{d} = (a \cdot b)^{d}$$

c) 设
$$f \in A^{B \times C}$$
,定义  $\varphi: A^{B \times C} \rightarrow (A^B)^C$  如下:

$$\varphi(f) = \{\langle c, g \rangle | \langle c, g \rangle \in C \times A^B, \exists g(b) = f(\langle b, c \rangle)\}$$

设
$$\varphi(f_1) = \varphi(f_2)$$
,则

$$\{\langle c,g\rangle | \langle c,g\rangle \in C \times A^B, g(b) = f_1(\langle b,c\rangle)\}$$

=
$$\{\langle c,g\rangle | \langle c,g\rangle \in C \times A^B, g(b) = f_2(\langle b,c\rangle)\}$$

对所有  $b \in B$  和  $c \in C$ ,有

$$f_1(\langle b,c\rangle) = f_2(\langle b,c\rangle)$$

所以  $f_1 = f_2$ ,故  $\varphi$  为一入射函数。

其次,对任意  $h \in (A^B)^D$ ,则  $h(d):B \rightarrow A, h(d)(b) \in A, 令 f:$

$$B \rightarrow A$$
,使得  $f(\langle b, d \rangle) = h(d)(b)$ ,则

$$\varphi(f) = \{ \langle d, g \rangle \mid \langle d, g \rangle \in C \times A^B \coprod g(b) = f(\langle b, d \rangle) \}$$

$$= \{ \langle d, g \rangle \mid \langle d, g \rangle \in C \times A^B \coprod g(b) = h(d)(b) \}$$

$$= \{ \langle d, g \rangle \mid \langle d, g \rangle \in C \times A^B \coprod g = h(d) \} = h$$

故  $\varphi(f)$  是满射。即

$$K[A^{B\times D}]=K[(A^B)^D]$$

所以

## 第五章 代数结构

#### 5-1

> 设集合  $A = \{1, 2, 3, \dots, 10\}$ ,问下面定义的二元运算 \*
> - a)  $x * y = \max(x, y)$ ;
> - b)  $x * y = \min(x, y)$ ;
> - c) x \* y = GCD(x, y);
> - d) x \* y = LCM(x, y);
> - e) x \* y = 质数 p 的个数,使得  $x \le p \le y$ 。 【5-1.(1)】

**解**：

a) 封闭。

b) 封闭。
c) 封闭。
d) 不封闭,例 LCM(3,7)=21。
e) 不封闭,例6\*6=0。

---
#### 5-2

> 在表 5-1 所列出的集合和运算中,请根据运算的是否封闭,在相应的位置上填写"是"或"否"(其中 N 是自然数集合)。
> [5-1,(2)]

**解**：

见表 5-1。

表 5-1

| 是否封闭 集 合                                | + | _ | • | x-y | max | min | x |  |  |  |
|-----------------------------------------|---|---|---|-----|-----|-----|---|--|--|--|
| I                                       | 是 | 是 | 是 | 是   | 是   | 是   | 是 |  |  |  |
| N                                       | 是 | 否 | 是 | 是   | 是   | 是   | 是 |  |  |  |
| $\{x \mid 0 \leqslant x \leqslant 10\}$ | 否 | 否 | 否 | 是   | 是   | 是   | 是 |  |  |  |
| $\{x \mid -10 \le x \le 10\}$           | 否 | 否 | 否 | 否   | 是   | 是   | 是 |  |  |  |
| $\{2x \mid x \in I\}$                   | 是 | 是 | 是 | 是   | 是   | 是   | 是 |  |  |  |

---
#### 5-3

> 试列举你所熟悉的一些代数系统。
> [5-1.(3)]

**解**：

复数集合及其复数加法和复数乘法构成的代数系统 $\langle C, +, \cdot \rangle$ ;在整数集合的模 4 剩余类集合  $Z_4$  上定义二元运算+4 和  $\times$ 4 如表 5-2。那么, $\langle Z_4, +_4, \times_4 \rangle$  是一个代数系统;在日常生活中,也可举出实例,譬如,由若干个球队组成一个集合,在这个集合中,定义两个球队之间的二元运算是在这两个球队之间进行一场

表 5-2

|     |     |     |     |                   | <br>                     |     |     |     |     |  |
|-----|-----|-----|-----|-------------------|--------------------------|-----|-----|-----|-----|--|
| +4  | [0] | [1] | [2] | [3]               | ×4                       |     |     |     |     |  |
| [0] | [0] | [1] | [2] | [3]<br>[0]<br>[1] | [0]<br>[1]<br>[2]<br>[3] | [0] | [0] | [0] | [0] |  |
| [1] | [1] | [2] | [3] | [0]               | [1]                      | [0] | [1] | [2] | [3] |  |
| [2] | [2] | [3] | [0] | [1]               | [2]                      | [0] | [2] | [0] | [2] |  |
| [3] | [3] | [0] | [1] | [2]               | [3]                      | [0] | [3] | [2] | [1] |  |

球赛,那么,这也是一个代数系统,所要注意的是,这个二元运算是 不封闭的。等等。

---
#### 5-4

> 对于实数集合 R,表 5-3 所列的二元运算是否具有左边一列中的那些性质,请在相应位置上填写"是"或"否"。
> [5-2.(1)]

**解**：

见表 5-3。

表 5-3

|      | + | _ |   | max | min | x-y |
|------|---|---|---|-----|-----|-----|
| 可结合性 | 是 | 否 | 是 | 是   | 是   | 否   |
| 可交换性 | 是 | 否 | 是 | 是   | 是   | 是   |
| 存在幺元 | 是 | 否 | 是 | 否   | 否   | 是   |
| 存在零元 | 否 | 否 | 是 | 否   | 否   | 否   |

---
#### 5-5

> 设代数系统 $\langle A, * \rangle$ ,其中  $A = \{a,b,c\}$ ,\*是 A上的一个二元运算。对于由以下几个表所确定的运算,试分别讨论它们的交换性、等幂性以及在 A 中关于\*是否有幺元。如果有幺元,那么 A 中的每个元素是否有逆元。
> [5-2,(2)]

**解**：

a)可交换,不等幂,a 为幺元,a 以自身为逆元,b 与 c 互为逆元。

b) 可交换,不等幂,a 为幺元,a 和 b 均以自身为逆元,c 没有逆元。
c) 不可交换,等幂,没有幺元。
d) 可交换,不等幂,a 为幺元,a 以自身为逆元,b 和 c 都没有逆元。

[5-2,(3)]

由左零元定义可知  $\theta_l * \theta_r = \theta_l$ ,由右零元定义可知  $\theta_l * \theta_r = \theta_r$ ,所以, $\theta_l = \theta_r = \theta$ 。若有另一个零元  $\theta'$ ,则  $\theta' = \theta' * \theta = \theta$ ,因此,零元是唯一的。

---
#### 5-7

> 举日常生活的例子,分别说明幺元、零元和逆元。
> [5-2.(4)]

**解**：

对一组学生,用两两扳腕子比赛法来测定谁比谁臂力大,则臂力最小者为幺元,臂力最大者为零元。在钟表中,若将分针从零开始走了t分再走s分所指位置作为结果,则0就是幺元,若 $t+s\equiv 0 \pmod{60}$ ,则t与s互为逆元。

---
#### 5-8

> 定义  $I_+$ 上的两个二元运算为:
> $$a * b = a^b$$
> $$a\triangle b=a \cdot b$$
> ,  $a,b \in I_+$
> 试证明 \* 对△是不可分配的。
> [5-2.(5)]

**证明**：

因为

$$a * (b \triangle c) = a * (b \cdot c) = a^{b \cdot c}$$

$$(a * b) \triangle (a * c) = (a^b) \triangle (a^c) = a^b \cdot a^c = a^{b+c}$$

而  $b \cdot c$  不一定等于 b+c,所以,\*对于  $\triangle$  是不可分配的。

---
#### 5-9

> 对于正整数  $k, N_k = \{0, 1, 2, \dots, k-1\}$ ,设  $*_k$ 是  $N_k$ 上的一个二元运算,使得  $a *_k b = 用 k$  除  $a \cdot b$  所得的余数,这里  $a, b \in N_k$ 。
> - a) 当 k=4 时,试造出  $*_k$ 的运算表;
> - b) 对于任意正整数 k,证明 $\langle N_k, \star_k \rangle$ 是一个半群。【5-3.(1)】

**解**：

a) 当 k=4 时,  $*_4$  的运算表为:

b) 对于任意的  $a,b \in N_k$ ,  $a *_k b = a \cdot b - nk = r$ ,  $0 \le r < k - 1$ , 所以  $*_k$  在  $N_k$  上封闭。

对于任意的  $a,b,c \in N_{s}$ ,有

$$(a *_k b) *_k c = (a \cdot b - n_1 k) \cdot c - n_2 k = r_1, 0 \le r_1 < k - 1$$

$$= a \cdot b \cdot c - k(n_1 c + n_2)$$

$$a *_k (b *_k c) = a \cdot (b \cdot c - n_3 k) - n_4 k = r_2, 0 \le r_2 \le k - 1$$

=  $a \cdot b \cdot c - k(n_3 a + n_4)$

这说明  $r_1$ ,  $r_2$  都是  $a \cdot b \cdot c$  用 k 除所得的余数,它们应该相等。所以, $(a *_k b) *_k c = a *_k (b *_k c)$ ,即  $*_k$ 满足结合律。

因此, $\langle N_k, *_k \rangle$ 是半群。

---
#### 5-10

> 设 $\langle S, * \rangle$ 是一个半群, $a \in S$ ,在 S 上定义一个二元运
> $$x \square y = x * a * y$$
> 证明二元运算□是可结合的。
> [5-3.(2)]

**证明**：

因为

$$(x \square y) \square z = (x*a*y) \square z = (x*a*y)*a*z = x*a*y*a*z$$
$$x \square (y \square z) = x \square (y*a*z) = x*a*(y*a*z) = x*a*y*a*z$$

所以  $(x \square y) \square z = x \square (y \square z)$

---
#### 5-11

> 设 $\langle R,*\rangle$ 是一个代数系统,\* 是 R 上的一个二元运 算,使得对于 R 中的任意元素 a,b 都有
> $$a * b = a + b + a \cdot b$$

**证明**：

0 是幺元,且 $\langle R, * \rangle$ 是独异点。

[5-3,(3)]

对于任意的  $a \in R$ , 0 \* a = 0 + a + 0 • a = 0, a \* 0 = a + 0 + a • 0 = a, 所以 0 \* a = a \* 0 = a, 故 0 是幺元。

对于任意的  $a,b \in R$ ,由于十和·在 R 上封闭,所以,a \* b =

$a+b+a \cdot b \in R$ ,即\*在R上封闭。

对于任意的  $a,b,c \in R$ ,有

$$(a * b) * c = (a+b+a \cdot b) * c$$

$$= a+b+a \cdot b+c+(a+b+a \cdot b) \cdot c$$

$$= a+b+c+a \cdot b+a \cdot c+b \cdot c+a \cdot b \cdot c$$

$$a * (b * c) = a * (b+c+b \cdot c)$$

$$= a+b+c+b \cdot c+a \cdot (b+c+b \cdot c)$$

$$= a+b+c+a \cdot b+a \cdot c+b \cdot c+a \cdot b \cdot c$$

所以,(a\*b)\*c=a\*(b\*c),故\*是可结合的。

因此, $\langle R, * \rangle$ 是独异点。

---
#### 5-12

> 设  $X \neq \emptyset$ , 令  $S = t(X) = \sum_{n=0}^{\infty} X^n$ ,在 S 上定义二元运算 $\triangle$ ,对任意  $\alpha = \langle x_1, x_2, \dots, x_p \rangle \in X^p$ , $\beta = \langle y_1, y_2, \dots, y_q \rangle \in X^q$ ,有
> $$\alpha \triangle \beta = \langle x_1, x_2, \cdots, x_p, y_1, y_2, \cdots, y_q \rangle \in X^{p+q}$$

**证明**：

$\langle S, \triangle \rangle$ 是一个独异点。

对于任意的  $\alpha = \langle x_1, x_2, \dots, x_p \rangle, \beta = \langle y_1, y_2, \dots, y_q \rangle,$   $\gamma = \langle z_1, z_2, \dots, z_r \rangle \in S$ ,有

$\alpha \triangle \beta = \langle x_1, x_2, \cdots, x_p, y_1, y_2, \cdots, y_q \rangle \in X^{p+q} \subset S$ ,即 $\triangle$ 在S上封闭。

$$(\alpha \triangle \beta) \triangle \gamma = \langle x_1, x_2, \cdots, x_p, y_1, y_2, \cdots, y_q \rangle \triangle \gamma$$

$$= \langle x_1, x_2, \cdots, x_p, y_1, y_2, \cdots, y_q, z_1, z_2, \cdots, z_r \rangle$$

$$\alpha \triangle (\beta \triangle \gamma) = \alpha \triangle \langle y_1, y_2, \cdots, y_q, z_1, z_2, \cdots, z_r \rangle$$

$$= \langle x_1, x_2, \cdots, x_p, y_1, y_2, \cdots, y_q, z_1, z_2, \cdots, z_r \rangle$$

所以, $(\alpha \triangle \beta) \triangle \gamma = \alpha \triangle (\beta \triangle \gamma)$ ,即 $\triangle$ 在 S 上可结合。

$$\partial \theta = \langle \rangle \in \emptyset \subset S$$
,有

$$\theta \triangle \alpha = \alpha \triangle \theta = \alpha = \langle x_1, x_2, \dots, x_p \rangle \in X^p \subset S$$

所以, $\theta$  是 S 中的幺元。

因此, $\langle S, \triangle \rangle$ 是一个独异点。

---
#### 5-13 证明任意半群都可通过添加一个幺元而扩展为一个

独异点。

设 $\langle S, * \rangle$ 是任一半群。作 $\overline{S} = S \cup \{e\}$ ,在 $\overline{S}$ 上将 \* 扩展定义为 a\*e=e\*a=a, $a\in S$ ;e\*e=e。接着证明 $\langle \overline{S}, * \rangle$ 是独异点,\* 在 $\overline{S}$ 上是封闭的;对于任意的  $x,y,z\in \overline{S}$ ,因为 $\langle S, * \rangle$ 是半群,所以当  $x,y,z\in S$  时,有 x\*(y\*z)=(x\*y)\*z,而当 x,y,z中至少有一个 e 时,也必有 x\*(y\*z)=(x\*y)\*z,所以,\* 在 $\overline{S}$ 上满足结合律;e 又是 $\overline{S}$ 中的幺元,因此, $\langle \overline{S}, * \rangle$ 是一个独异点。

---
#### 5-14

> 设 $\langle G, * \rangle$ 是一个独异点,且|G|  $\geq$  2,则在 G 中不存在 有左逆元的左零元。

**证明**：

独异点中的幺元e显然不可能等于任一个左零元。

设有一个左零元  $\theta_l$ ,它的左逆元为  $\theta_l^{-1}$ ,则  $\theta_l^{-1} * \theta_l = e$ 。因为  $\theta_l * \theta_l = \theta_l$ ,所以  $\theta_l^{-1} * \theta_l * \theta_l = \theta_l^{-1} * \theta_l$ ,即  $e * \theta_l = e$ ,导致矛盾。因此,在 G 中不可能存在有左逆元的左零元。

---
#### 5-15

> 设 $\langle A, * \rangle$ 是一个半群,而且对于 A 中的元素 a 和 b, 如果  $a \neq b$  必有  $a * b \neq b * a$ ,试证明:
> - a) 对于 A 中每个元素 a,有 a \* a = a:
> - b) 对于 A 中任何元素 a 和 b, 有 a \* b \* a = a;
> - c) 对于 A 中任何元素 a,b 和 c,有 a\*b\*c=a\*c。 【5-3.(5)】 证明 由题意可知,若 a\*b=b\*a,则必有 a=b。
> - a) 由(a\*a)\*a=a\*(a\*a),所以a\*a=a。
> - b) 由 a \* (a \* b \* a) = (a \* a) \* b \* a = a \* b \* (a \* a) = (a \* b \* a) \* a, 所以 <math>a \* b \* a = a。
> - c)  $\neg (a * c) * (a * b * c) = (a * c * a) * (b * c) = a * (b * c) = (a * b) * (c * a * c) = (a * b * c) * (a * c), \text{ fill } a * b * c = a * c.$
---
#### 5-16

> 如果 $\langle S, * \rangle$ 是半群,且\*是可交换的,称 $\langle S, * \rangle$ 为可交换半群。证明:如果 S 中有元素 a,b,使得 a\*a=a 和 b\*b=b,则(a\*b)\*(a\*b)=a\*b。 【5-3.(6)】

**证明**：

$$(a * b) * (a * b) = a * (b * a) * b = a * (a * b) * b$$

=  $(a * a) * (b * b) = a * b$

---
#### 5-17

> 设  $X=R-\{0,1\}$ ,在 X 上定义 6 个函数如下:
> 对于任意  $x \in X$ ,
> $$f_1(x) = x; f_2(x) = x^{-1}; f_3(x) = 1 - x$$
> $f_4(x) = (1-x)^{-1}$ ;  $f_5(x) = (x-1)x^{-1}$ ;  $f_6(x) = x(x-1)^{-1}$  试证明 $\langle F, \circ \rangle$ 是一个群。其中  $F = \{f_1, f_2, f_3, f_4, f_5, f_6\}$ ,  $\circ$  是函数的复合运算。 【5-4.(1)】

**证明**：

由函数的复合运算。的定义  $f \circ g(x) = f(g(x))$ ,可写出。在 F上的运算表如表 5-3。

表 5-3

| ۰     | $f_1$ | $f_2$                               | $f_3$ | $f_4$ | $f_5$ | $f_6$ |
|-------|-------|-------------------------------------|-------|-------|-------|-------|
| $f_1$ | $f_1$ | $f_2$ $f_1$ $f_5$ $f_6$ $f_3$ $f_4$ | $f_3$ | $f_4$ | $f_5$ | $f_6$ |
| $f_2$ | $f_2$ | $f_1$                               | $f_4$ | $f_3$ | $f_6$ | $f_5$ |
| $f_3$ | $f_3$ | $f_5$                               | $f_1$ | $f_6$ | $f_2$ | $f_4$ |
| $f_4$ | $f_4$ | $f_6$                               | $f_2$ | $f_5$ | $f_1$ | $f_3$ |
| $f_5$ | $f_5$ | $f_3$                               | $f_6$ | $f_1$ | $f_4$ | $f_2$ |
| $f_6$ | $f_6$ | $f_4$                               | $f_5$ | $f_2$ | $f_3$ | $f_1$ |
|       |       |                                     |       |       |       |       |

可见,运算。在 F 上是封闭和可结合的。  $f_1$  是幺元;  $f_2$ ,  $f_3$ ,  $f_6$  均以自身为逆元;  $f_4$  与  $f_5$  互为逆元。因此, $\langle F, \circ \rangle$ 是一个群。

---
#### 5-18

> 设 $\langle A, * \rangle$ 是半群, e 是左幺元且对每一个  $x \in A$ , 存在  $\hat{x} \in A$ , 使得  $\hat{x} * x = e$ .
> - a) 证明:对于任意的  $a,b,c \in A$ ,如果 a \* b = a \* c,则 b = c;
> - b) 通过证明 e 是 A 中的幺元,证明 $\langle A, * \rangle$  是群。【5-4.(2)】

**证明**：

a) 由 a \* b = a \* c 即得  $\hat{a} * (a * b) = \hat{a} * (a * c)$ ,因为  $\langle A, * \rangle$  是半群,便有  $(\hat{a} * a) * b = (\hat{a} * a) * c, e * b = e * c,$ 又因  $\ell$  是左幺元,所以  $\ell$   $\ell$   $\ell$   $\ell$   $\ell$   $\ell$   $\ell$   $\ell$   $\ell$   $\ell$

b) 对于任意的  $x \in A$ ,  $\hat{x} * (x * e) = (\hat{x} * x) * e = e * e = e = \hat{x} * x$ , 所以, x \* e = x, 这说明 e 也是右幺元, 故 e 是幺元。于是, 对于任意的  $x \in A$ , 有 $(x * \hat{x}) * x = x * (\hat{x} * x) = x * e = x = e * x$ , 所以,  $x * \hat{x} = e$ , 故有  $\hat{x} * x = x * \hat{x} = e$ , 这说明对于任意的 x 均有逆元 $\hat{x}$ , 因此,  $\langle A, * \rangle$  是群。

---
#### 5-19

> 设 $\langle G, * \rangle$ 是群,对任 $-a \in G$ ,令  $H = \{y \mid y * a = a * y \}$
> $_{v} \in G$ },试证明 $\langle H, * \rangle$ 是 $\langle G, * \rangle$ 的子群。
> [5-4.(3)]

**证明**：

显然  $H \subseteq G$ 。运算 \* 在 H 中显然满足结合性。

对于任意的  $x,y \in H$ ,以及任意的  $a \in G$ ,因为

(x \* y) \* a = x \* y \* a = x \* a \* y = a \* x \* y = a \* (x \* y)

所以, $x * y \in H$ ,这说明 \* 关于 H 是封闭的。

因为 e \* a = a \* e, 所以  $e \in H$ .

对于任意的  $x \in H$ ,由于 x \* a = a \* x,所以

$$x^{-1} * (x * a) * x^{-1} = x^{-1} * (a * x) * x^{-1}$$

即得

$$a * x^{-1} = x^{-1} * a$$

这就表明  $x^{-1} \in H$ 。

综上所述, $\langle H, * \rangle$ 是 $\langle G, * \rangle$ 的子群。

---
#### 5-20

> 设 $\langle H, \cdot \rangle$ 和 $\langle K, \cdot \rangle$ 都是群 $\langle G, \cdot \rangle$ 的子群,令
> $$HK = \{h \cdot k | h \in H, k \in K\}$$

**证明**：

$\langle HK, \bullet \rangle$ 是 $\langle G, \bullet \rangle$ 的子群的充要条件是 HK=KH。

[5-4.(4)]

先证充分性。

对于任意的  $h_1 \cdot k_1$ ,  $h_2 \cdot k_2 \in HK$ , 因为 $\langle H, \cdot \rangle$ 和 $\langle K, \cdot \rangle$ 都 是群, 所以 $(h_2 \cdot k_2)^{-1} = k_2^{-1} \cdot h_2^{-1} \in KH$ ; 又因 HK = KH, 所以必有  $h_3 \in H$ ,  $k_3 \in K$ , 使得  $k_2^{-1} \cdot h_2^{-1} = h_3 \cdot k_3$ 。由于

$$(h_1 \cdot k_1) \cdot (h_2 \cdot k_2)^{-1} = (h_1 \cdot k_1) \cdot (h_3 \cdot k_3)$$

$$= h_1 \cdot (k_1 \cdot h_3) \cdot k_3 = h_1 \cdot (h_4 \cdot k_4) \cdot k_3$$

$$= (h_1 \cdot h_4) \cdot (k_4 \cdot k_3) = h_5 \cdot k_5 \in HK$$

因此,由定理 5-4.8 可知 $\langle HK, \bullet \rangle$ 是 $\langle G, \bullet \rangle$ 的子群。

再证必要性。

对于任意的  $k \cdot h \in KH$ ,  $(k \cdot h)^{-1} = h^{-1} \cdot k^{-1} \in HK$ , 因  $\langle HK, \cdot \rangle$  是群, 所以  $((k \cdot h)^{-1})^{-1} \in HK$ , 即  $k \cdot h \in HK$ , 因此,  $KH \subset HK$ .

对于任意的  $h \cdot k \in HK$ ,  $(h \cdot k)^{-1} \in HK$ , 即存在  $h_1 \in H$ ,  $k_1 \in K$ , 使得 $(h \cdot k)^{-1} = h_1 \cdot k_1$ , 所以

$$h \cdot k = (h_1 \cdot k_1)^{-1} = k_1^{-1} \cdot h_1^{-1} \in KH$$

因此, $HK \subseteq KH$ 。

由上便证得 HK=KH。

---
#### 5-21

> 设 $\langle A, * \rangle$ 是群,且 $|A|=2n,n\in N$ 。证明:在A中至少存在  $a\neq e$ ,使得 a\*a=e,其中 e是幺元。 【5-4.(5)]

**证明**：

对于任意的  $x \in A$ ,均有它的逆元  $x^{-1} \in A$ ,使得

$$x * x^{-1} = x^{-1} * x = e$$

由于互为逆元的两个不相等的元素是成对出现的,而且群中有唯一的幺元 e,因此,至少有一个元素是以自身为逆元的。即必存在  $a \in A$ , $a \neq e$ ,使得 a \* a = e。

---
#### 5-22

> 设 $\langle G, \bullet \rangle$ 是一个群, $H \subseteq G, H \neq \emptyset$ 且 H 中的元素都是有限阶的,运算在 H 中封闭,则 $\langle H, \bullet \rangle$ 为 $\langle G, \bullet \rangle$ 的子群。

**证明**：

封闭性已知,结合律自然成立。

对于任意的  $h \in H$ ,必存在正整数 n,使得 h'' = e,因为  $h'' \in H$ , 所以  $e \in H$ ,这说明 G 中的幺元 e 属于 H 。

对于任意的  $h \in H, h \neq e$ ,必存在正整数 n > 1,使得  $h^n = e$ ,故有  $h \cdot h^{n-1} = h^{n-1} \cdot h = e$ ,所以  $h^{-1} = h^{n-1} \in H$ 。

因此, $\langle H, \bullet \rangle$ 为 $\langle G, \bullet \rangle$ 的子群。

---
#### 5-23

> 设 $\langle G,*\rangle$ 是一个独异点,并且对于 G 中的每一个元
> [5-5.(1)]
> **证明** 对于任意的  $x \in G$ ,有 x \* x = e,所以  $x^{-1} = x$ 。 对于任意的  $a,b \in G$ ,
> $$a * b = (a * b)^{-1} = b^{-1} * a^{-1} = b * a$$
> 因此, $\langle G, * \rangle$ 是阿贝尔群。
> **5-24** 证明任何阶数分别为 1,2,3,4 的群都是阿贝尔群。 并举一个 6 阶群,它不是阿贝尔群。 【5-5.(2)】

**证明**：

对于阶数为 1 的群,该群中仅有唯一的一个幺元 e, e\*e=e,显然是阿贝尔群。以下幺元都用 e 表示。

对于阶数为 2 的群,该群中除幺元外,仅有一个与 e 不同的元素 a,且 a\*a=e,显然还有 e\*a=a\*e=a,因此,〈 $\{a,e\}$ ,\*〉是阿贝尔群。

对于阶数为 3 的群 $\langle \{a,b,e\},*\rangle$ 。若 a\*b=a,则有  $a^{-1}*a*b=a^{-1}*a$ ,导致 b=e 的矛盾;同理,若 a\*b=b,则将导致 a=e 的矛盾。所以,必有 a\*b=e。又因

$$b * a = b * a * b * b^{-1} = b * e * b^{-1} = e$$

因此、〈 $\{a,b,e\}$ , \*〉是阿贝尔群。

对于阶数为 4 的群〈 $\{a,b,c,e\}$ ,\*〉,(i)若 a,b,c 中有两个元素互为逆元,不妨设它们为 a, b, 则 a\*b=b\*a=e。于是,必有  $c*c=e,a*c\neq e$ ,所以 a\*c=b,同样地可证 c\*a=b,故 a\*c=c\*a。同理可证 b\*c=c\*b。(ii)若 a,b,c 中的每一个元素都以 自身为逆元,则必有 a\*b=b\*a=c,b\*c=c\*b=a,c\*a=a\*c=b。因此,不论是哪一种情况,都表明〈 $\{a,b,c,e\}$ ,\*〉是阿贝尔群。

定义在集合  $S=\{a,b,c\}$ 上的所有双射函数为:

$$f_0: f_0(a) = a, f_0(b) = b, f_0(c) = c$$

$f_1: f_1(a) = a, f_1(b) = c, f_1(c) = b$
$f_2: f_2(a) = b, f_2(b) = a, f_2(c) = c$
$f_3: f_3(a) = b, f_3(b) = c, f_3(c) = a$
$f_4: f_4(a) = c, f_4(b) = a, f_4(c) = b$
$f_5: f_5(a) = c, f_5(b) = b, f_5(c) = a$

于是集合  $F = \{f_0, f_1, f_2, f_3, f_4, f_5\}$ 关于函数的复合运算。构成群,群的阶数为 6。其运算表如表 5-4 所示。显然,它不是阿贝尔群。

表 5-4

|       | $f_0$ | $f_1$ | $f_2$                                                                                     | $f_3$   | $f_4$ | $f_5$ |
|-------|-------|-------|-------------------------------------------------------------------------------------------|---------|-------|-------|
| $f_0$ | $f_0$ | $f_1$ | f <sub>2</sub> f <sub>4</sub> f <sub>0</sub> f <sub>5</sub> f <sub>1</sub> f <sub>3</sub> | $f_3$   | $f_4$ | $f_5$ |
| $f_1$ | $f_1$ | $f_0$ | $f_4$                                                                                     | $f_{5}$ | $f_2$ | $f_3$ |
| $f_2$ | $f_2$ | $f_3$ | $f_0$                                                                                     | $f_1$   | $f_5$ | $f_4$ |
| $f_3$ | $f_3$ | $f_2$ | $f_5$                                                                                     | $f_4$   | $f_0$ | $f_1$ |
| $f_4$ | $f_4$ | $f_5$ | $f_1$                                                                                     | $f_0$   | $f_3$ | $f_2$ |
| $f_5$ | $f_5$ | $f_4$ | $f_3$                                                                                     | $f_2$   | $f_1$ | $f_0$ |

---
#### 5-25

> 设 $\langle G, * \rangle$ 是一个群,证明:如果对任意的  $a,b \in G$  都 有  $a^3 * b^3 = (a * b)^3$ ,  $a^4 * b^4 = (a * b)^4$  和  $a^5 * b^5 = (a * b)^5$ ,则
> $\langle G, * \rangle$ 是一个阿贝尔群。
> [5-5.(3)]

**证明**：

对于 $\langle G, * \rangle$ 中的任意元素 a 和 b。

因为  $a^3 * b^3 = (a * b)^3$ ,所以  $a^{-1} * (a^3 * b^3) * b^{-1} = a^{-1} * (a * b)^3 * b^{-1}$ ,即得  $a^2 * b^2 = (b * a)^2$ 。同理,由  $a^4 * b^4 = (a * b)^4$  可得  $a^3 * b^3 = (b * a)^3$ ;由  $a^5 * b^5 = (a * b)^5$  可得  $a^4 * b^4 = (b * a)^4$ 。

由此可得, $(a^3 * b^3) * (b * a) = (b * a)^4 = a^4 * b^4$ ,即  $b^4 * a = a * b^4$ 。同样地可得, $(a^2 * b^2) * (b * a) = (b * a)^3 = a^3 * b^3$ ,即  $b^3 + a = a * b^3$ 。

由于 $(a * b) * b^3 = a * b^4 = b^4 * a = b * (b^3 * a) = b * (a * b^3) = (b * a) * b^3$ ,故得,a \* b = b \* a。

因此, $\langle G, * \rangle$ 是阿贝尔群。

---
#### 5-26

> 设  $G=\{[1],[2],[3],[4],[5],[6]\}$ ,G 上的二元运 算 $\times$ ,如表 5-5 所示。问 $\langle G,\times_{7}\rangle$ 是循环群吗?若是,试找出它的 生成元。 【5-5.(4)】
> 表 5-5
> | [1] | [2]                             | [3]                                                 | [4]                                                 | [5]                                                                                         | [6]                                                                                                                                                                                                         |
> |-----|---------------------------------|-----------------------------------------------------|-----------------------------------------------------|---------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
> | [1] | [2]                             | [3]                                                 | [4]                                                 | [5]                                                                                         | [6]                                                                                                                                                                                                         |
> | [2] | [4]                             | [6]                                                 | [1]                                                 | [3]                                                                                         | [5]                                                                                                                                                                                                         |
> | [3] | [6]                             | [2]                                                 | [5]                                                 | [1]                                                                                         | [4]                                                                                                                                                                                                         |
> | [4] | [1]                             | [5]                                                 | [2]                                                 | [6]                                                                                         | [3]                                                                                                                                                                                                         |
> | [5] | [3]                             | [1]                                                 | [6]                                                 | [4]                                                                                         | [2]                                                                                                                                                                                                         |
> | [6] | [5]                             | [4]                                                 | [3]                                                 | [2]                                                                                         | [1]                                                                                                                                                                                                         |
> |     | [1]<br>[2]<br>[3]<br>[4]<br>[5] | [1] [2]<br>[2] [4]<br>[3] [6]<br>[4] [1]<br>[5] [3] | [1] [2] [3] [2] [4] [6] [2] [4] [1] [5] [5] [3] [1] | [1] [2] [3] [4]<br>[2] [4] [6] [1]<br>[3] [6] [2] [5]<br>[4] [1] [5] [2]<br>[5] [3] [1] [6] | [1]     [2]     [3]     [4]     [5]       [2]     [4]     [6]     [1]     [3]       [3]     [6]     [2]     [5]     [1]       [4]     [1]     [5]     [2]     [6]       [5]     [3]     [1]     [6]     [4] |

**解**：$\langle G, \times_7 \rangle$ 是循环群。其生成元是[3]和[5]。

---
#### 5-27

> 证明:循环群的任何子群必定也是循环群。 [5-5.(5)]

**证明**：

设 $\langle G, * \rangle$ 是循环群,其生成元是 a。设 $\langle S, * \rangle$ 是 $\langle G, * \rangle$ 的子群,且  $S \neq \{e\}$ 。那么,存在最小正整数 m,使得  $a^m \in S$ 。对于任意的  $a^l \in S$ ,必有 l = tm + r, $0 \leq r < m$ ,t > 0,故  $a^r = a^{l-tm} = a^l * (a^m)^{-t} \in S$ 。因为 m 是  $a^m \in S$  的最小正整数,所以,只能有 r = 0,即得  $a^l = (a^m)^t$ 。这说明,S 中的任意元素都是  $a^m$  的乘幂。因此, $\langle S, * \rangle$ 是以  $a^m$  为生成元的循环群。

---
#### 5-28

> 设 $\langle G, * \rangle$ 是 n 阶循环群,其生成元为 a。设  $b=a^k$ ,其 中 k 为正整数。求证:
> - a) 元素 b 的阶为 $\frac{n}{d}$ ,这里 d 是 n 与 k 的最大公约数;
> - b) 元素 b 为 G 的生成元的充要条件为 n 与 k 互质。

**证明**：

a) 因为  $d \in n$  与 k 的最大公约数,故可设

$$n=d \cdot n_1, k=d \cdot k_1$$

所以有

$$e = a^{nk_1} = a^{kn_1} = b^{n_1}$$

若 b 的阶不为  $n_1$  ,则 b 的阶 m 必小于  $n_1$  ,且有  $n_1 = l \cdot m$  ,l > 1 。就有  $b^m = e$  , $a^{km} = e$  , $a^{d \cdot k_1 \frac{n}{l}} = e$  , $a^{n \cdot \frac{k_l}{l}} = e$  ,这样就导致  $k_1$  有因子 l 的矛盾。因此, $n_1 = \frac{n}{d}$  为 b 的阶。

b) 若 b 为 G 的生成元,则 b 的阶为 n。由 a 可知 b 的阶为  $\frac{n}{d}$ ,故只能有 d=1。这说明 n 与 k 的最大公约数为 1,即 n 与 k 互质。

反之,若n与k互质,则存在整数s,t,使得sk+tn=1,故对于G中的任一个元素 $a^p$ ,均有

$$a^{p} = a^{p(sk+m)} = a^{psk} * a^{pm} = a^{kps} = b^{ps}$$

因此,b是G的生成元。

---
#### 5-29

> 设 $\langle G, \bullet \rangle$ 为有限交换群,n为G中元素的最大阶数,则G中任一元素的阶必能整除n。

**证明**：

设 a 为 G 中的一个 n 阶元, $b \in G$ ,b 的阶为 m。现用反证法,设  $m \ln n$ ,即存在质数 p,使得

$$m=p^s \cdot m_1, \quad n=p^t \cdot n_1$$

$ GCD(p,m_1)=1,GCD(p,n_1)=1,s>t$ .

在 G 中取元素  $a^{p^t}$  ,  $b^{m_1}$  ,则  $a^{p^t}$  的阶为  $n_1$  ,  $b^{m_1}$  的阶为  $p^t$  。由于  $GCD(p^t,n_1)=1$  ,所以,由例题 5-4 可知, $a^{p^t}$  •  $b^m$  的阶为  $p^t$  •  $n_1>p^t$  •  $n_1=n$  ,这就与 n 为 G 中元素的最大阶数相矛盾。因此,m|n 。 5-30 设有 $\{a,b,c,d,e\}$ 的置换如下:

$$\alpha = \begin{pmatrix} a & b & c & d & e \\ b & c & a & d & e \end{pmatrix}; \quad \beta = \begin{pmatrix} a & b & c & d & e \\ a & b & c & e & d \end{pmatrix}$$

$$\gamma = \begin{pmatrix} a & b & c & d & e \\ e & d & c & b & a \end{pmatrix}; \quad \delta = \begin{pmatrix} a & b & c & d & e \\ c & b & a & e & d \end{pmatrix}$$

试求  $\alpha \circ \beta, \beta \circ \alpha, \alpha \circ \alpha, \gamma \circ \beta, \delta^{-1}, \alpha \circ \beta \circ \gamma$ , 并解方程  $\alpha \circ x = \beta, y \circ \gamma = \delta$ .

[5-6.(1)]

$$\mathbf{MF} \quad \alpha \circ \beta = \begin{pmatrix} a & b & c & d & e \\ b & c & a & e & d \end{pmatrix}; \beta \circ \alpha = \begin{pmatrix} a & b & c & d & e \\ b & c & a & e & d \end{pmatrix} \\
\alpha \circ \alpha = \begin{pmatrix} a & b & c & d & e \\ c & a & b & d & e \end{pmatrix}; \gamma \circ \beta = \begin{pmatrix} a & b & c & d & e \\ e & d & c & a & b \end{pmatrix} \\
\delta^{-1} = \begin{pmatrix} a & b & c & d & e \\ c & b & a & e & d \end{pmatrix} \\
\alpha \circ \beta \circ \gamma = \begin{pmatrix} a & b & c & d & e \\ d & e & a & c & b \end{pmatrix} \\
x = \alpha^{-1} \circ \beta = \begin{pmatrix} a & b & c & d & e \\ c & a & b & e & d \end{pmatrix} \\
y = \delta \circ \gamma^{-1} = \begin{pmatrix} a & b & c & d & e \\ c & b & a & e & d \end{pmatrix} \circ \begin{pmatrix} a & b & c & d & e \\ e & d & c & b & a \end{pmatrix} \\
= \begin{pmatrix} a & b & c & d & e \\ d & e & a & b & c \end{pmatrix}$$

---
#### 5-31

> 设 p 是质数,证明从 a 种颜色不同的珠子中选取 p 粒 串成手镯,只有同色手镯保持旋转不变。
> ![](_page_42_Picture_5.jpeg)
> [5-6,(2)]

**证明**：

由 p 粒珠子串成的手镯,其珠子的颜色分别记为  $c_1$ ,  $c_2$ , …,  $c_p$ , 如图 5-7 所示。

顺时针方向旋转一粒珠子的位置后,若图 5-7 要不变,则必有  $c_2 = c_1$ , $c_3 = c_2$ ,…, $c_p = c_{p-1}$ , $c_1 = c_p$ ,即必有  $c_1 = c_2 = c_3 = \dots = c_p$ ,所以,只有用同色珠子串成的手镯才能保持旋转一粒珠子位置后不变。

由于 p 是质数,故不可能有 k,1 < k < p,使得 p 是 k 的倍数,因此,不可能实现  $c_1 = c_k = c_{2k} = \cdots = -$ 种颜色,而  $c_2 = c_{k+1} = c_{2k+1} = \cdots =$ 另一种颜色,…,即不可能用不同颜色的珠子串成的手镯,而使该 p 粒珠子串成的手镯保持旋转 k 粒珠子位置后不变。因此,只有同色手镯才能保持旋转不变。

---
#### 5-32

> 哪些对称群是阿贝尔群? 【5-6.(3)】

**解**：

$\langle S_1, \circ \rangle$ 和 $\langle S_2, \circ \rangle$ 是阿贝尔群。

$$\langle S_3, \circ \rangle$$
中有置换 $\begin{pmatrix} a & b & c \\ b & a & c \end{pmatrix}$ 和 $\begin{pmatrix} a & b & c \\ b & c & a \end{pmatrix}$ ,而
$$\begin{pmatrix} a & b & c \\ b & a & c \end{pmatrix} \circ \begin{pmatrix} a & b & c \\ b & c & a \end{pmatrix} = \begin{pmatrix} a & b & c \\ a & c & b \end{pmatrix}$$
$$\begin{pmatrix} a & b & c \\ b & c & a \end{pmatrix} \circ \begin{pmatrix} a & b & c \\ b & a & c \end{pmatrix} = \begin{pmatrix} a & b & c \\ c & b & a \end{pmatrix}$$

所以, $\langle S_a, \cdot \rangle$ 不是阿贝尔群。

对于任意的  $n,n \ge 4, \langle S_n, \cdot \rangle$  中总有置换

$$\begin{pmatrix} a_1 & a_2 & a_3 & a_4 & \cdots & a_n \\ a_2 & a_1 & a_3 & a_4 & \cdots & a_n \end{pmatrix} \neq \begin{pmatrix} a_1 & a_2 & a_3 & a_4 & \cdots & a_n \\ a_2 & a_3 & a_1 & a_4 & \cdots & a_n \end{pmatrix}$$

而这两个置换之间的运算是不可交换的。因此, $\langle S_n, \circ \rangle$ , $n \ge 4$ ,都不是阿贝尔群。

---
#### 5-33

> 用 4 种不同颜色中的一种或几种来涂一根六节的棍棒,问有多少种不同的涂法? 【5-6.(4)】

**解**：

设棍棒上第i节涂上 $c_i$ 色,如图 5-8 所示。

每一节上可以有 4 种涂色法,因此,棍棒的 所有涂色法共有  $4^6$  种。 然而,只要是  $c_1$  色与  $c_6$

$$\begin{array}{c|ccccccccccccccccccccccccccccccccccc$$

色相同, $c_2$  色与  $c_5$  色相同, $c_3$  色与  $c_4$  色相同,那么该棍棒倒向后的涂色情况是不会改变的。为此,我们构造置换群 $(\{\pi_0,\pi_1\},\bullet)$ ,其中  $\pi_0$  是幺置换,它将每一种涂色棍棒的情况  $c_1c_2c_3c_4c_5c_6$  仍映照成  $c_1c_2c_3c_4c_5c_6$  的情况,所以,在  $\pi_0$  作用下的不变元个数为  $4^6$ ;

而 π, 是这样的一个置换,它将每一种涂色棍棒的情况 c<sub>1</sub>c<sub>2</sub>c<sub>3</sub>c<sub>4</sub>c<sub>5</sub>c<sub>6</sub> 映照成  $c_s c_s c_s c_s c_s$  的情况,所以,在  $\pi_s$  作用下的不变元必定是  $c_1 = c_5$ ,  $c_2 = c_5$ ,  $c_3 = c_4$  的情况,故在  $\pi_1$  作用下的不变元个数为  $4^3$ . 因此,由伯恩赛德定理可知,该棍棒不同涂色法的总数应是

$$\frac{1}{2}(4^6+4^3)=2080$$
种

---
#### 5-34

> a) 2×2 的棋盘,用白色或黑色涂在每一个方格内,在 考虑旋转等价的条件下,试确定每个方格涂上颜色的不同棋盘的 数目。
> [5-6,(5)]

**解**：

a) 设 2×2 的棋盘如图 5-9 所示。

$\odot c_i$  表示棋盘中第 i 格所涂的颜色。现构造置换群为 $\langle \{\pi_0\}$  $\pi_1, \pi_2, \pi_3$ },  $\bullet$ 〉, 其中  $\pi_i$  (0 $\leq i \leq 3$ ) 是将棋盘映照到按顺时针方向旋 转  $i \times 90^{\circ}$  所得到的棋盘,那么,在  $\pi_i$  作用下,不变元的个数分别 如下:

π。·不转。不变元个数是 24。

$\pi_1$ : 顺时针转 90°, 只有当  $c_1 = c_2 = c_3 = c_4$  时为不变元, 所以, 不变元的个数是 2。

$\pi_0$ : 顺时针转 180°, 只有当  $c_1 = c_3$ ,  $c_2 = c_4$  时为不变元, 所以, 不变元的个数是 2<sup>2</sup>。

$\pi_0$ . 顺时针转 270°, 只有当  $c_1 = c_4 = c_3 = c_2$  时为不变元, 所以, 不变元的个数是 2。

![](_page_43_Figure_11.jpeg)

![](_page_43_Figure_12.jpeg)

因此,由伯恩赛德定理可知,不相同的 2×2 棋盘数是

$$\frac{1}{4}(2^4+2+4+2)=6$$

b) 设 4×4 的棋盘如图 5-10 所示。

类似于 a),构告置换群 $(\{\pi_0,\pi_1,\pi_2,\pi_2\},\circ)$ ,那么,在  $\pi_i$  作用下。 不变元的个数分别如下:

π₀:不转。不变元的个数是 216。

$\pi_1$ : 顺时针转 90°。不变元要求  $c_1 = c_2 = c_3 = c_{10}$ ;  $c_2 = c_5 = c_6 = c_{10}$  $c_{11}$ ;  $c_3 = c_6 = c_9 = c_{12}$ ;  $c_- = c_- = c_- = c_m$ 。故不变元的个数应等于四 组涂两色的个数,即为24。

$π_2$ : 顺时针转 180°。不变元要求  $c_1 = c_7$ ;  $c_2 = c_8$ ;  $c_3 = c_9$ ;  $c_4 =$  $c_{10}$ ;  $c_5 = c_{11}$ ;  $c_6 = c_{12}$ ;  $c_- = c_=$ ;  $c_- = c_{10}$ 。故不变元的个数应等于八 组涂两色的个数,即为28。

$π_3$ : 顺时针转 270°。不变元要求  $c_1 = c_{10} = c_7 = c_4$ ;  $c_2 = c_{11} = c_8$  $=c_5$ ;  $c_3=c_{12}=c_9=c_6$ ;  $c_-=c_m=c_-=c_-$ 。故不变元的个数应等于 四组涂两色的个数,即为24。

因此,由伯恩赛德定理可知,不相同的 4×4 棋盘数是

$$\frac{1}{4}(2^{16}+2^4+2^8+2^4)=16456$$

---
#### 5-35

> 对于正方形的四个顶点用黑、白两种颜色进行着色, 我们说两种着色法是等价的,如果一种着色法可以由一个正方形 的对称性变化到另一种着色法。其中,正方形的对称性如表 5-6
> 表 5-6 称 刚体运动 顶点的置换 之 前 之 后 恒等图  $h_1$ 顺时针  $h_2$ 旋转 90°
> ![](_page_44_Picture_0.jpeg)
> 所示的八种。
> 我们举一个通过反射相互等价的着色法例子如图 5-11 所示。 问有多少种不等价的着色法?
> ![](_page_44_Picture_3.jpeg)
> 图 5-11

**解**：

记正方形的顶点集合为  $X = \{K, L, M, N\}$ ,则由正方形的对称性所给出的顶点的置换为

$$h_1 = e, h_2 = (KLMN), h_3 = (KM)(LN)$$

$h_4 = (KNML), h_5 = (KL)(MN), h_6 = (KN)(LM)$
$h_7 = (KM)(L)(N), h_8 = (K)(LN)(M)$

令  $H = \{h_1, h_2, h_3, h_4, h_5, h_6, h_7, h_8\}$ ,则 $\langle H, \circ \rangle$ 是一个置换群。

设 $\mathcal{F}$ 是从顶点集合 X 到颜色集合  $Y = \{W, B\}$  的函数所组成的集合。

对于每个  $h \in H$ ,可以诱导出  $\mathcal{I}$ 的一个置换 h'如下:

对于任 $-f \in \mathcal{F}, h'(f) = f \circ h$ 。例如

$h_4: K \rightarrow N, N \rightarrow M, M \rightarrow L, L \rightarrow K$

$f: K \rightarrow W, L \rightarrow B, M \rightarrow B, N \rightarrow B$

则  $h'(f) = h \cdot h_4 : K \rightarrow B, L \rightarrow W, M \rightarrow B, N \rightarrow B_0$

所有这样的 h' 所组成的集合是  $\mathcal{F}$ 上的一个置换群 G。为了应用伯恩赛德定理,我们要计算  $\psi(h')$ , $h' \in G$ 。因为 e 是 H 中的幺元,所以 e' 是 G 中的幺元。可见

$$\psi(e') = 2^4 = 16$$

$\psi((KLMN)')$ 等于  $\mathcal{F}$ 中这样一些 f 的个数,这些 f 通过置换  $K \rightarrow L, L \rightarrow M, M \rightarrow N, N \rightarrow K$  是不变的,即

f(K) = f(L), f(L) = f(M), f(M) = f(N), f(N) = f(K)就是说  $f(x) = 常数, x \in X$ 。这样的 f 只有两种可能,即

$$f(x) = \mathbb{R}(B), x \in X$$

或

$$f(x) = \dot{\vdash}(W), x \in X$$

因此

$$\psi((KLMN)')=2$$

类似地, $\phi((KM)(LN)')$ 等于 $\mathcal{F}$ 中这样一些f的个数,这些f通过置换  $K \to M$ , $M \to K$ , $L \to N$ , $N \to L$  是不变的,即 f(K) = f(M),f(L) = f(N),而前者有两种选择,后者也有两种选择,所以, $\phi((KM)(LN)') = 2 \cdot 2 = 4$ 。

基于同样的理由可得:

$\psi((KNML)')=2$

$$\psi((KL)(MN)') = \psi((KN)(LM)') = 4$$

$$\psi((KM)(L)(N)') = \psi((K)(LN)(M)') = 2 \cdot 2 \cdot 2 = 8$$

将伯恩赛德定理应用于 G, 即得不等价的着色法共有

$$\frac{1}{8}$$
(16+2+4+2+4+4+8+8)=6 种

---
#### 5-36

> 设 $G = \{ \varphi | \varphi : x \rightarrow ax + b,$ 其中 $a,b \in R$ 且 $a \neq 0, x \in R \}$ , 二元运算。是映射的复合。
> - a) 证明 $\langle G, \circ \rangle$ 是一个群。
> - b) 若 S 和 T 分别是由 G 中 a=1 和 b=0 的所有映射构成的集合,证明 $\langle S, \circ \rangle$ 和 $\langle T, \circ \rangle$ 都是子群。
> - c) 写出 S 和 T 在 G 中所有的左陪集。 【5-7.(1)】

**证明**：

a) ① 对于任意的  $\varphi_1, \varphi_2 \in G$ , 设  $\varphi_1(x) = a_1 x + b_1, a_1 \neq 0$ ,  $\varphi_2(x) = a_2 x + b_2, a_2 \neq 0$ , 由于

$$\varphi_{1} \circ \varphi_{2}(x) = \varphi_{1}(\varphi_{2}(x)) = \varphi_{1}(a_{2}x+b_{2}) = a_{1}(a_{2}x+b_{2})+b_{1}$$

$$= (a_{1}a_{2})x+(a_{1}b_{2}+b_{1})$$

$$a_{1}a_{2} \in \mathbb{R}, \quad a_{1}b_{2}+b_{1} \in \mathbb{R} \ \underline{\mathbb{H}} \ a_{1}a_{2} \neq 0$$

所以, $\varphi_1,\varphi_2 \in G$ 。

② 对于任意的  $\varphi_1, \varphi_2, \varphi_3 \in G$ ,有

$$(\varphi_1, \varphi_2), \varphi_3(x) = (\varphi_1, \varphi_2)(\varphi_3(x)) = \varphi_1(\varphi_2(\varphi_3(x)))$$

而
$$\varphi_1 \circ (\varphi_2 \circ \varphi_3)(x) = \varphi_1(\varphi_2 \circ \varphi_3(x)) = \varphi_1(\varphi_2(\varphi_3(x)))$$

所以  $(\varphi_1 \circ \varphi_2) \circ \varphi_3 = \varphi_1 \circ (\varphi_2 \circ \varphi_3)$

③ 幺元为  $\varphi_{\epsilon}$ ,使  $\varphi_{\epsilon}(x)=x$ 。这是因为,对于任意的  $\varphi\in G$ ,设  $\varphi(x)=ax+b$ ,则

$$\varphi_{\epsilon} \circ \varphi(x) = \varphi_{\epsilon}(ax+b) = ax+b, \varphi \varphi_{\epsilon}(x) = \varphi(x) = ax+b$$
所以, $\varphi_{\epsilon} \circ \varphi = \varphi \varphi_{\epsilon} \circ \varphi_{\epsilon}$

④ 对于任意的  $\varphi \in G$ ,设  $\varphi(x) = ax + b$ , $a \neq 0$ ,于是存在  $\varphi^{-1} \in G$ ,使得  $\varphi^{-1}(x) = \frac{1}{a}x - \frac{b}{a}$ ,且有

$$\varphi \circ \varphi^{-1}(x) = \varphi(\varphi^{-1}(x)) = \varphi\left(\frac{1}{a}x - \frac{b}{a}\right) = a\left(\frac{1}{a}x - \frac{b}{a}\right) + b = x$$
$$\varphi^{-1} \circ \varphi(x) = \varphi^{-1}(ax + b) = \frac{1}{a}(ax + b) - \frac{b}{a} = x$$

所以, $\varphi^{-1}$ 。 $\varphi = \varphi$ 。 $\varphi^{-1} = \varphi_e$ 。

因此, $\langle G, \circ \rangle$ 是一个群。

b) 对于任意的  $\varphi_1, \varphi_2 \in S$ ,可设为:

$$\varphi_1(x) = x + b_1, \quad \varphi_2(x) = x + b_2$$

于是, $\varphi_2^{-1}(x) = x - b_2$ , $\varphi_1 \circ \varphi_2^{-1}(x) = \varphi_1(x - b_2) = x - b_2 + b_1 = x + (b_2 - b_2)$ 所以, $\varphi_1 \circ \varphi_2^{-1} \in S$ 。因此, $\langle S, \circ \rangle$ 是 $\langle G, \circ \rangle$ 的子群。

对于任意的  $\varphi_1, \varphi_2 \in T$ ,可设为  $\varphi_1(x) = a_1 x, \varphi_2(x) = a_2 x$ ,  $a_1 \neq 0, a_2 \neq 0$ ,于是, $\varphi_2^{-1}(x) = \frac{1}{a_2} x$ ,则有

$$\varphi_1 \circ \varphi_2^{-1}(x) = \varphi_1(\varphi_2^{-1}(x)) = \varphi_1\left(\frac{1}{a_2}x\right) = a_1 \frac{1}{a_2}x = \frac{a_1}{a_2}x, \frac{a_1}{a_2} \neq 0$$

所以, $\varphi_1,\varphi_2^{-1} \in T$ 。因此, $\langle T, \bullet \rangle$ 也是 $\langle G, \bullet \rangle$ 的子群。

c) S的左陪集应为: $\varphi$ 。S, $\varphi \in G$ 。

对于任意的  $\varphi \in G$ ,设  $\varphi(x) = ax + b, a \neq 0$ ,那么

$$\varphi \circ S = \{\varphi \circ \varphi' \mid \varphi' \in S\} = \{\varphi \circ \varphi' \mid \varphi' : x \rightarrow x + b', b' \in R, x \in R\}$$

$$= \{\widetilde{\varphi} \mid \widetilde{\varphi} : x \rightarrow a(x + b') + b = ax + (ab' + b), b' \in R, x \in R\}$$

$$= \{\widetilde{\varphi} \mid \widetilde{\varphi} : x \rightarrow ax + c, c \in R, x \in R\}$$

所以,S在G中的所有左陪集为

$\{\widetilde{\varphi} \mid \widetilde{\varphi}: x \rightarrow ax + c, c \in R, x \in R\}, a \in R$

T的左陪集应为: $\varphi$ 。T, $\varphi \in G$ 。

对于任意的  $\varphi \in G$ ,设  $\varphi(x) = ax + b, a \neq 0$ ,那么

$$\varphi \circ T = \{ \varphi \circ \varphi' \mid \varphi' \in T \} = \{ \varphi \circ \varphi' \mid \varphi' : x \rightarrow a'x, a' \in R, x \in R \}$$
$$= \{ \widetilde{\varphi} \mid \widetilde{\varphi} : x \rightarrow a(a'x) + b, a' \in R, x \in R \}$$

$$= \{ \widetilde{\varphi} \mid \widetilde{\varphi} : x \rightarrow cx + b, c \in R, x \in R \}$$

所以,T在G中的所有左陪集为

$$\{ \widetilde{\varphi} \mid \widetilde{\varphi} : x \rightarrow cx + b, c \in R, x \in R \}, b \in R$$

---
#### 5-37

> 设〈 $Z_6$ ,  $+_6$ 〉是一个群,这里  $+_6$  是模 6 加法, $Z_6$  = {[0],[1],[2],[3],[4],[5]},试写出〈 $Z_6$ ,  $+_6$ 〉中每个子群及其相应的左陪集。 【5-7.(2)】

**解**：

*解** 子群有:〈{[0]},+<sub>6</sub>〉,〈{[0],[3]},+<sub>6</sub>〉,〈{[0],[2], [4]},+<sub>6</sub>〉和〈Z<sub>6</sub>,+<sub>6</sub>〉。

{[0]}的左陪集为:

{[0],[3]}的左陪集为:

$\{[0],[2],[4]\}$ 的左陪集为:

Z。的左陪集就是 Z。本身。

---
#### 5-38

> 设 $\langle G, * \rangle$ 是任一群,定义  $R \subseteq G \times G$  为
> $$R = \{(\sigma, \varphi) \mid$$
> 存在  $\theta \in G$  使得  $\varphi = \theta * \sigma * \theta^{-1} \}$
> 验证R是G上的等价关系。
> [5-7,(3)]

**证明**：

设 e 是 $\langle G, * \rangle$ 中的幺元,则对于任意的  $a \in G$ ,有  $a = e * a * e^{-1}$ ,所以, $\langle a, a \rangle \in R$ ;若 $\langle a, b \rangle \in R$ ,由定义,存在  $\theta \in G$ ,使得  $b = \theta * a * \theta^{-1}$ ,所以, $a = \theta^{-1} * b * \theta = \theta^{-1} * b * (\theta^{-1})^{-1}$ ,这表明  $\langle b, a \rangle \in R$ ;若 $\langle a, b \rangle$ , $\langle b, c \rangle \in R$ ,则存在  $\theta$ , $\rho$ ,使得  $b = \theta * a * \theta^{-1}$ , $c = \rho * b * \rho^{-1}$ ,故有

$c = \rho * b * \rho^{-1} = \rho * \theta * a * \theta^{-1} * \rho^{-1} = (\rho * \theta) * a * (\rho * \theta)^{-1}$ 所以, $\langle a, c \rangle \in R$ 。 因此,R是G上的等价关系。

---
#### 5-39

> 设  $S_n$  是一个对称群,G 是保持某一个元素不变的置换群,求出 G 在  $S_n$  中的所有左陪集。

**解**：

设 G 是使第 i 个元素不变的置换群。因为  $|S_n|=n!$ , |G|=(n-1)!,所以由拉格朗日定理可知 G 在  $S_n$  中的左陪集共 f n 个,即为 G 以及

$$\pi_k \cdot G = \left\{ \begin{pmatrix} 1 & 2 & \cdots & i & \cdots & n \\ k_1 & k_2 & \cdots & k & \cdots & k_n \end{pmatrix} \right.$$

$$\begin{vmatrix} k_1, k_2, \cdots, k_{i-1}, k_{i+1}, \cdots, k_n & \text{是 } 1, 2, \cdots, k-1, k+1, \cdots, n \\ \text{的任一署换排列}(k=1, 2, \cdots, i-1, i+1, \cdots, n) \end{vmatrix}$$

---
#### 5-40

> 设 $\langle H, * \rangle$ 是群 $\langle G, * \rangle$ 的子群,如果
> $$A = \{x \mid x \in G, x * H * x^{-1} = H\}$$

**证明**：

$\langle A, * \rangle$ 是 $\langle G, * \rangle$ 的一个子群。

[5-7.(5)]

由定义可知  $A \subseteq G$ 。对于任意的  $a,b \in A$ ,有  $a * H * a^{-1} = H$ , $b * H * b^{-1} = H$ 。由  $b * H * b^{-1} = H$ ,可得  $b^{-1} * H * b = H$ 。因为

$$(a * b^{-1}) * H * (a * b^{-1})^{-1} = a * (b^{-1} * H * (b^{-1})^{-1}) * a^{-1}$$

=  $a * H * a^{-1} = H$

所以, $a * b^{-1} \in A$ ,因此, $\langle A, * \rangle$ 是 $\langle G, * \rangle$ 的一个子群。

---
#### 5-41

**证明**：

在由群 $\langle G, * \rangle$ 的一个子群 $\langle S, * \rangle$ 所确定的陪集中,只有一个陪集是子群。 【5-7.(6)】
设G中的幺元为e。因为eS=S,所以S是一个陪集。
若另有一个陪集 aS 也是 G 的子群,那么  $e \in aS$ ,故必有  $s_1 \in S$ ,使得  $a * s_1 = e$ ,即有  $a = s_1^{-1}$ 。对于任意的  $a * s \in aS$ ,有  $a * s = s_1^{-1} * s \in S$ ,所以, $aS \subseteq S$ ;反之,对于任意的  $s \in S$ ,有  $s = a * a^{-1} * s = a * (a^{-1} * s) = a * ((s_1^{-1})^{-1} * s) = a * (s_1 * s) \in aS$ ,所以, $S \subseteq aS$ ,因此,aS = S。这就表明,S 的左陪集只有一个是子群,即S 本身。
---
#### 5-42

> 设 aH 和 bH 是 H 在 G 中的两个左陪集,证明:要末  $aH \cap bH = \emptyset$ ,要末 aH = bH。 【5-7.(7)】

**证明**：

对于aH和bH,只有以下两种情况:

(i)  $aH \cap bH \neq \emptyset$ ,则至少存在  $h_1$  和  $h_2$ ,使  $ah_1 = bh_2$ ,即有  $a=bh_2h_1^{-1}$ 。

对于任意的  $ah \in aH$ ,有  $ah = bh_2h_1^{-1}h = bh_3 \in bH$ ,故有  $aH \subseteq bH$ 。同理可证  $bH \subseteq aH$ 。所以,aH = bH。

(ii)  $aH \cap bH = \emptyset$ .

---
#### 5-43

> 设 p 是质数,证明:p<sup>m</sup> 阶群中一定包含着一个 p 阶子群。 【5-7.(8)】

**证明**：

设 $p^m$  阶群为 $\langle G, \bullet \rangle$ 。

对于任意的  $a \in G$ ,  $a \neq e$ , 若 a 的阶为 n, 即  $a^n = e$ , 则  $n \mid p^m$ , 所以,  $n = p^t (t \ge 1$ , 且 t 为正整数)。

若 t=1,则 a 的阶为 p,于是,由 a 所生成的循环群就是G的一个 p 阶子群。

若 t>1,则令  $b=a^{p^{t-1}}$ ,则有

$$b^{p} = (a^{p^{t-1}})^{p} = a^{p^{t}} = a^{n} = e$$

于是,由b所生成的循环群就是G的一个p阶子群。

---
#### 5-44

> 设 $\langle S, * \rangle$ 和 $\langle T, * \rangle$ 分别是群 $\langle G, * \rangle$ 的 s 阶和 t 阶子群,并且  $S \cap T$  和  $S \cup T$  的阶分别为  $\mu$  和  $\nu$ ,证明  $st \geqslant \mu\nu$ 。 【5-2.(9)】

**证明**：

由包含排斥原理

$$|S \cup T| = |S| + |T| - |S \cap T|$$

即得  $\nu=s+t-\mu$ 。因为  $|S\cap T|\leqslant |S|$  ,  $|S\cap T|\leqslant |T|$  , 即有  $\mu\leqslant s$  ,  $\mu\leqslant t$  。因此,

$$\mu v = \mu(s+t-\mu) = \mu(s-\mu) - t(s-\mu) + st$$
$$= st - (t-\mu)(s-\mu) \leqslant st$$

---
#### 5-45

> 设 $\langle G, * \rangle$ 是一个有限群,|G| = mk, $\langle \widetilde{G}, * \rangle$ 是 $\langle G, * \rangle$ 的子群,且 $|\widetilde{G}| = m$ ,证明:对于任意  $a \in G$ ,必存在正整数  $n, 1 \le n \le k$ ,使得  $a^n \in \widetilde{G}$ 。

**证明**：

考察集合 $\{\widetilde{G}, a*\widetilde{G}, a^2*\widetilde{G}, \cdots, a^k*\widetilde{G}\}$ 。由拉格朗日定理可知,在G中有且仅有k个 $\widetilde{G}$ 的相异陪集,而上述集合中却有k+1个 $\widetilde{G}$ 的陪集,故必有两个陪集是相同的,即必存在正整

数  $n_1, n_2, 1 \le n_1 < n_2 \le k$ ,使得  $a^{n_1} * \widetilde{G} = a^{n_2} * \widetilde{G}$ 。 因为  $a^{n_2} = a^{n_2} * e \in a^{n_2} * \widetilde{G}$ ,所以必存在  $b \in \widetilde{G}$ ,满足  $a^{n_1} * b = a^{n_2}$ ,故有  $b = a^{n_2-n_1}$ ,令 $n = n_2 - n_1$ ,就有  $1 \le n \le k$ ,且有  $a^n \in \widetilde{G}$ 。

---
#### 5-46

> 设 $\langle G, \bullet \rangle$ 是一个群,对于  $a,b \in G$ ,若  $a \cdot b = b \cdot a$ , a 和 b 的阶分别为 r 和 s,且循环子群(a) 和(b) 的交只包含 G 的幺元 e,即(a)  $\cap$  (b) =  $\{e\}$ ,则  $a \cdot b$  的阶等于 r 和 s 的最小公倍数。

**证明**：

设  $d \ge r$  和 s 的最小公倍数。不妨设  $r = \alpha c$ ,  $s = \beta c$  ( $\alpha \le \beta \le \beta \le \beta$ )。故有  $d = \alpha \beta c$ 。于是 $(a \cdot b)^d = a^d \cdot b^d = e$ 。设  $a \cdot b$  的 阶为 k, 就有  $k \mid d$ 。

设  $k=mr+r_1$ ,  $0 \le r_1 < r_1 k=ns+s_1$ ,  $0 \le s_1 < s$ , 就可以有  $(a \cdot b)^k=e=a^k \cdot b^k=a^{r_1} \cdot b^{s_1}$ 。这表明  $b^{s_1}$ 是  $a^{r_1}$  的逆元,故  $b^{s_1} \in (a)$ 。若  $r_1 \ne 0$ ,则  $a^{r_1} \ne e$ ,于是必有  $b^{s_1} \ne e$ ,这就导致  $b^{s_1} \ne e$  且  $b^{s_1} \in (a) \cap (b)$ 的矛盾,所以只能有  $r_1 = 0$ 。同理可证  $s_1 = 0$ 。就得到 k=mr 和 k=ns,即有  $ac \mid k$  和  $\beta c \mid k$ ,因为  $\alpha$  与  $\beta$  互质,所以必有  $a\beta c \mid k$ ,即  $d \mid k$ 。因此,k=d。

---
#### 5-47

**证明**：

如果 f 是由 $\langle A, \bigstar \rangle$ 到 $\langle B, * \rangle$ 的同态映射,g 是由 $\langle B, * \rangle$ 到 $\langle C, \triangle \rangle$ 的同态映射,那么, $g \circ f$  是由 $\langle A, \bigstar \rangle$ 到 $\langle C, \triangle \rangle$ 的同态映射。 【5-8.(1)】
因为对于任意的  $a,b \in A$ ,有  $f(a \bigstar b) = f(a) * f(b)$ , 而对于任意的  $c,d \in B$ ,有  $g(c*d) = g(c) \triangle g(d)$ ,所以,对于任意的  $a,b \in A$ ,有
$$g \circ f(a \bigstar b) = g(f(a \bigstar b)) = g(f(a) * f(b))$$
$$= g(f(a)) \triangle g(f(b)) = g \circ f(a) \triangle g \circ f(b)$$
因此, $g \circ f$  是由 $\langle A, \bigstar \rangle$ 到 $\langle C, \triangle \rangle$ 的同态映射。
---
#### 5-48

> 设(G, \*)是一个群,而  $a \in G$ ,如果 f 是从 G 到 G 的 映射,使得对于每一个  $x \in G$ ,都有
> $$f(x) = a * x * a^{-1}$$
> 试证明 f 是一个从G 到G 上的自同构。
> [5-8,(2)]

**证明**：

对于任意的  $x,y \in G$ , 若  $x \neq y$ ,则

$$f(x) = a * x * a^{-1} \neq a * y * a^{-1} = f(y)$$

所以,f是G到G的入射。

对于任意的  $y \in G$ ,由封闭性得  $a^{-1} * y * a \in G$ ,不妨设  $a^{-1} * y * a = x$ ,这就说明,对于任意的  $y \in G$  必存在  $x \in G$ ,使得  $x = a^{-1} * y * a$ 。所以, $y = a * x * a^{-1} = f(x)$ 。可见, $f \notin G$  **到** G 的满射。

另外,对于任意的  $x,y \in G$ ,有

$f(x*y) = a*(x*y)*a^{-1} = (a*x*a^{-1})*(a*y*a^{-1}) = f(x)*f(y)$ 因此, f 是从 G 到 G 的一个自同构。

---
#### 5-49 试证由表 5-7 所给出的两个群〈G,★〉和〈S,\*〉是同构的。

表 5-7

| *                     | $p_1$      | $p_2$      | <b>p</b> 3            | <b>p</b> 4 | • *   | $q_1$ | $q_2$              | $q_3$ | $q_4$ |
|-----------------------|------------|------------|-----------------------|------------|-------|-------|--------------------|-------|-------|
| $p_1$                 | $p_1$      | <b>p</b> 2 | <b>p</b> <sub>3</sub> | <b>p</b> 4 | $q_1$ | $q_3$ | $q_4$              | $q_1$ | $q_2$ |
| $p_2$                 | $p_2$      | $p_1$      | ₽4                    | $p_3$      | $q_2$ | $q_4$ | $q_3$              | $q_2$ | $q_1$ |
| <i>p</i> <sub>3</sub> | <b>p</b> 3 | $p_4$      | $p_1$                 | $p_2$      | $q_3$ | $q_1$ | $q_2$              | $q_3$ | $q_4$ |
| <b>D</b> 4            | $p_4$      | $p_3$      | $p_2$                 | $p_1$      | $q_4$ | $q_2$ | $\boldsymbol{q}_1$ | $q_4$ | $q_3$ |

作G到S的映射f为:

$f(p_1)=q_3$ ,  $f(p_2)=q_2$ ,  $f(p_3)=q_1$ ,  $f(p_4)=q_4$ 由表 5-7 可知, f 是一个双射。

容易验证:

$$f(p_1 \bigstar p_1) = f(p_1) = q_3 = q_3 * q_3 = f(p_1) * f(p_1)$$

$$f(p_1 \bigstar p_2) = f(p_2) = q_2 = q_3 * q_2 = f(p_1) * f(p_2)$$

$$f(p_3 \bigstar p_2) = f(p_4) = q_4 = q_1 * q_2 = f(p_3) * f(p_2)$$

$$f(p_4 \bigstar p_2) = f(p_3) = q_1 = q_4 * q_2 = f(p_4) * f(p_2)$$

等等。其余可类似地验证。所以 $\langle G, \bigstar \rangle$ 和 $\langle S, * \rangle$ 同构。

---
#### 5-50

> 设  $f_1$ ,  $f_2$  都是从代数系统〈A, ★〉到代数系统〈B, \*〉的 同态。设 g 是从 A 到 B 的一个映射使得对任意 a ∈ A, 都有
> $$g(a) = f_1(a) * f_2(a)$$

**证明**：

如果 $\langle B, * \rangle$ 是一个可交换半群,那么 g 是一个由 $\langle A, \bigstar \rangle$ 到  $\langle B, * \rangle$ 的同态。

因为对于任意的  $a,b \in A$ ,都有

$$g(a \bigstar b) = f_1(a \bigstar b) * f_2(a \bigstar b) = f_1(a) * f_1(b) * f_2(a) * f_2(b)$$

=  $f_1(a) * f_2(a) * f_1(b) * f_2(b) = g(a) * g(b)$

所以,g 是 $\langle A, \bigstar \rangle$ 到 $\langle B, * \rangle$ 的同态。

---
#### 5-51

> $\langle R, + \rangle$ 是实数集上的加法群,设
> $$f: x \rightarrow e^{2\pi i x}, x \in \mathbb{R}$$
> f是同态否?如果是,请写出同态像和同态核。
> [5-8.(5)]

**解**：

对于任意的  $a,b \in R$ ,有

$$f(a+b) = e^{2\pi i(a+b)} = e^{2\pi ia} \cdot e^{2\pi ib} = f(a) \cdot f(b)$$

所以,f 是〈R,+〉到〈C,•〉的同态。这里,〈C,•〉是复数集上的乘 法群。

因为  $e^{2\pi ix} = \cos 2\pi x + i \sin 2\pi x$ , 所以, f 的同态像为 $\langle \{\cos 2\pi x + i \sin 2\pi x | x \in R \}$ ,  $\cdot$   $\rangle$ , 它是一个群,其幺元为 1,即  $\cos 2\pi x = 1$ ,  $\sin 2\pi x = 0$  的情况。由此可见,发生这种情况应该是

$$2\pi x = 2k\pi$$
$(k=0,\pm 1,\pm 2,\cdots)$

因此,f的同态核为整数集 I。

---
#### 5-52

**证明**：

循环群的同态像必定是循环群。 【5-8.(6)】
设循环群 $\langle A, \bullet \rangle$ 的生成元为 a 同态映射为 f,同态像 为 $\langle f(A), * \rangle$ 。于是,对于任意的  $a^n, a^m \in A$ ,都有
$$f(a^n \cdot a^m) = f(a^n) * f(a^m)$$
对于 n=1 时,有 f(a)=f(a)
对于 n=2 时,有  $f(a^2)=f(a \cdot a)=f(a) * f(a)=f(a)^2$
若 n=k-1 时,有  $f(a^{k-1})=f(a)^{k-1}$ ,那么,对 n=k 时有
$f(a^k) = f(a^{k-1} \cdot a) = f(a^{k-1}) * f(a) = f(a)^{k-1} * f(a) = f(a)^k$  这表明, f(A) 中的每一个元素都可表示为  $f(a)^n$ , 所以,  $\langle f(A), * \rangle$  是以生成元为 f(a)的循环群。
5-53
$$\langle R - \{0\}, \times \rangle = \langle R, + \rangle$$
同构吗? 【5-8.(7)】
设 f 是 $\langle R, + \rangle$ 与 $\langle R - \{0\}, \times \rangle$ 的同构映射,于是 对于任意的  $b \in R - \{0\}$ 必存在  $a \in R$ ,使得 f(a) = b,有  $b = f(a) = f(0) + a = f(0) \times f(a) = f(0) \times b$   $b=f(a)=f(a+0)=f(a)\times f(0)=b\times f(0)$
所以,f(0)是 $\langle R-\{0\},\times\rangle$ 中的幺元。即应有 f(0)=1。
对于 $-1 \in R - \{0\}$ 必存在  $c \in R$ ,使得 f(c) = -1,有
$$f(c+c) = f(c) \times f(c) = -1 \times (-1) = 1$$
所以就有 c+c=0,即有 c=0 的结果,由此导致 f(0)=-1 的矛盾。
因此, $\langle R-\{0\},\times\rangle$ 与 $\langle R,+\rangle$ 不可能同构。
---
#### 5-54

**证明**：

一个集合上任意两个同余关系的交也是一个同余 关系。 【5-8.(8)】
设 $\langle A, * \rangle$ 上的任意两个同余关系为  $R_1$  和  $R_2$ ,即:
对于任意的 $\langle a_1, b_1 \rangle$ ,  $\langle a_2, b_2 \rangle \in R_1$ , 有 $\langle a_1 * a_2, b_1 * b_2 \rangle \in R_1$ ;对于任意的 $\langle c_1, d_1 \rangle$ ,  $\langle c_2, d_2 \rangle \in R_2$ , 有 $\langle c_1 * c_2, d_1 * d_2 \rangle \in R_2$ 。
于是,对于任意的 $\langle a,b\rangle$ , $\langle c,d\rangle \in R_1 \cap R_2$ ,则
$\langle a * c, b * d \rangle \in R_1 \ \exists \langle a * c, b * d \rangle \in R_2$
所以、 $\langle a*c,b*d\rangle \in R_1 \cap R_2$ 。
因此,一个集合上任意两个同余关系的交仍是一个同余关系。

---
#### 5-55 证明:定理 5-8.4 中在 B上所定义的二元运算\*是唯一确定的。 【5-8.(9)】
对于任意的  $A_i$ ,  $A_j \in B$ , 任取  $a_1 \in A_i$ ,  $a_2 \in A_j$ , 若  $a_1 \not \uparrow a_2 \in A_k$ ,则定义  $A_i * A_j = A_k$ 。
若另取  $a_1' \in A_i$ ,  $a_2' \in A_j$ ,则有 $\langle a_1, a_1' \rangle \in R$  和 $\langle a_2, a_2' \rangle \in R$ ,又因 R 是 A 上的同余关系,所以必有 $\langle a_1 \bigstar a_2, a_1' \bigstar a_2' \rangle \in R$ 。由此可知,若  $a_1 \bigstar a_2 \in A_k$ ,则必有  $a_1' \bigstar a_2' \in A_k$ 。这就表明,不论怎样选取 $a_1 \in A_i$ ,  $a_2 \in A_j$ ,总有  $a_1 \bigstar a_2 \in A_k$ 。
因此,上述在 B 上定义的二元运算 \* 是唯一确定的。
---
#### 5-56

> 考察代数系统 $\langle I,+\rangle$ ,以下定义在 I 上的二元关系  $R^{L}$  同余关系吗?
> - a)  $\langle x,y \rangle \in R$  当且仅当 $(x < 0 \land y < 0) \lor (x \ge 0 \land y \ge 0)$ ;
> - b)  $\langle x,y \rangle \in R$  当且仅当|x-y| < 10:
> - c)  $\langle x,y\rangle \in R$  当且仅当 $(x=y=0) \lor (x\neq 0 \land y\neq 0)$ ;
> d)  $\langle x,y\rangle \in R$  当且仅当  $x \geqslant v$ 。
> (5-8.(10))

**解**：

a) 对于任意的  $x \in I$ ,  $(x < 0) \lor (x \ge 0) = (x < 0 \land x < 0) \lor (x \ge 0 \land x \ge 0)$ , 所以 $(x,x) \in R$ ;

若 $\langle x,y\rangle\in R,\langle y,z\rangle\in R,则$

$(x<0 \land y<0) \lor (x>0 \land y>0)$ , $(y<0 \land z<0) \lor (y>0 \land z>0)$ 可见,若 $x<0 \land y<0$ ,则必有 $y<0 \land z<0$ ,由此可得 $x<0 \land z<0$ 。 或者,若 $x>0 \land y>0$ ,则必有 $y>0 \land z>0$ ,由此可得 $x>0 \land z>0$ 。 所以 $(x,z) \in R$ 。

因此,R是I上的等价关系。

但是,存在着 $\langle -2, -2 \rangle \in R$ , $\langle 1, 4 \rangle \in R$ .而

$$\langle -2+1, -2+4 \rangle = \langle -1, 2 \rangle \notin R$$

所以,R不是同余关系。

b)  $\langle 2,5 \rangle \in R(因为|2-5|=3<10)$

$(5,13) \in R(因为|5-13|=8<10)$

但是|2-13|=11>10,所以 $\langle 2,13\rangle$  ∉ R,传递性不成立,R 连等价关系也不是,R 当然不是同余关系。

c) 虽然 $\langle -4,6 \rangle \in R$  且 $\langle 6,-6 \rangle \in R$ ,但 $\langle -4+6,6-6 \rangle = \langle 2,0 \rangle$   $\notin R$ ,所以 R 不是同余关系。
d) 显然 $\langle 2,1\rangle \in R$ ,但 $\langle 1,2\rangle \notin R$ ,对称性不成立,R 不是等价关系,当然也就不是同余关系。

---
#### 5-57

> 设 f 和 g 都是群 $\langle G_1, \bigstar \rangle$ 到群 $\langle G_2, * \rangle$ 的同态,证明。  $\langle C, \bigstar \rangle$ 是 $\langle G_1, \bigstar \rangle$ 的一个子群,其中
> $$C = \{x | x \in G_1 \coprod f(x) = g(x)\}$$
> [5-8.(11)]

**证明**：

由定义可知  $C \subseteq G_1$ 。

对于任意的  $a,b \in C$ ,有 f(a) = g(a), f(b) = g(b).

因为 f 和 g 都是同态映射,所以必有

$$f(b^{-1}) = f(b)^{-1}, g(b^{-1}) = g(b)^{-1}$$

现因 f(b)=g(b),故有  $f(b)^{-1}=g(b)^{-1}$ ,即有  $f(b^{-1})=g(b^{-1})$ 。由

--

## 第六章 格和布尔代数

#### 6-1

> 由图 6-5 所示的偏序集,哪一个是格? 为什么?
> [6-1.(1)]
> ![](_page_14_Picture_3.jpeg)

**解**：

a) 不是格,因为1,2没有最大下界。

b) 是格。
c)是格。
d) 不是格,因为1,2没有最大下界。

---
#### 6-2

> 由下列集合 L 构成的偏序集 $\langle L, \prec \rangle$ ,其中 $\prec$ 定义为:对于  $n_1, n_2 \in L, n_1 \prec n_2$  当且仅当  $n_1$  是  $n_2$  的因子。问其中哪几个偏序集是格。
> - a)  $L = \{1,2,3,4,6,12\}$ ;
> - b)  $L = \{1, 2, 3, 4, 6, 8, 12, 14\}$ ;
> - c)  $L = \{1,2,3,4,5,6,7,8,9,10,11,12\}$ . [6-1.(2)]

**解**：

a) 是格。

b) 不是格,因为 12,14 没有最小上界。
c) 不是格,因为 9,10 没有最小上界。

---
#### 6-3

> 验证以整除关系"|"为偏序关系的正整格 $\langle I_+, | \rangle$ 所诱导的代数系统

**证明**：

对于格 $\langle I_+, | \rangle$ 来说,其诱导的代数系统 $\langle I_+, \vee, \wedge \rangle$ 中的二元运算  $\vee$  和  $\wedge$  分别为:对于任意的  $a,b \in I_+$  有  $a \vee b = LCM(a,b), a \wedge b = GCD(a,b)$

所以,容易看出,对于任意的  $a,b,c \in I_+$ ,有

$$a \lor b = LCM(a,b) = LCM(b,a) = b \lor a$$

$$a \wedge b = GCD(a,b) = GCD(b,a) = b \wedge a$$

$$(a \lor b) \lor c = LCM(a,b) \lor c = LCM(a,b,c)$$

$$=a \lor LCM(b,c) = a \lor (b \lor c)$$

$$(a \land b) \land c = GCD(a,b) \land c = GCD(a,b,c)$$

$$=a \wedge GCD(b,c) = a \wedge (b \wedge c)$$

$$a \lor a = LCM(a,a) = a, a \land a = GCD(a,a) = a$$

设 GCD(a,b)=m,则必有整数 k,使得 a=mk,于是,

$$a \lor (a \land b) = a \lor (GCD(a,b)) = a \lor m$$

=  $LCM(a,m) = LCM(mk,m)$

$$=mk=a$$

另外,设 LCM(a,b)=n,则必有整数 l,使得 n=la,于是

$$a \wedge (a \vee b) = a \wedge LCM(a,b) = a \wedge n$$

=  $GCD(a,n) = GCD(la,a) = a$

---
#### 6-4

> 设 $\langle A, \preceq \rangle$ 是一个格,任取 a,b 且  $a \prec b$ ,构造集合  $B = \langle x | x \in A$  且  $a \preceq x \preceq b \rangle$ ,则 $\langle B, \preceq \rangle$ 也是一个格。 【6-1.(4)】

**证明**：

因为 $\langle A, \preccurlyeq \rangle$ 是一个格,而  $B \subseteq A$ ,所以 $\langle B, \preccurlyeq \rangle$ 是一个偏序集。对于任意的  $c,d \in B \subseteq A$ ,  $c \lor d$  和  $c \land d$  是唯一存在的。

由于 $a \leq c \leq b$ , $a \leq d \leq b$ ,所以由 $a \leq c$  和 $a \leq d$  可得

$$a = a \lor a \leq c \lor d$$

由 $c \leq b$  和 $d \leq b$  可得

$$c \lor d \leq b \lor b = b$$

这就表明  $a \leq c \lor d \leq b$ ,即可知  $c \lor d \in B \subseteq A$ 。

同理可证  $c \land d \in B$ 。

因此,⟨B,≼⟩也是一个格。

---
#### 6-6

> 6-6** 设 A, B 是两个集合, f 是 A 到 B 的映射,证明:  $\langle S$ ,  $\subseteq \rangle$  是 $\langle \mathscr{P}(B), \subseteq \rangle$ 的一个子格,其中
> $$S = \{y | y = f(x), x \in \mathcal{P}(A)\}$$
> [6-1.(5)]

**证明**：

首先,因为 f 是 A 到 B 的映射,所以对于任意的  $a \in A$ ,都有唯一的  $b \in B$ ,使得 f(a) = b。于是,对于任意的  $A_1,A_2 \in \mathcal{P}(A)$ ,有  $f(A_1)$ 和  $f(A_2)$ 且明显地有

$$f(A_1 \cup A_2) = f(A_1) \cup f(A_2)$$

$$f(A_1 \cap A_2) = f(A_1) \cap f(A_2)$$

其次,因为 $\langle \mathcal{P}(B), \subseteq \rangle$ 是一个格,且由 S 的定义可知  $S \subseteq \mathcal{P}(B)$ ,所以 $\langle S, \subseteq \rangle$ 是一个偏序集。

最后,对于任意的  $s_1, s_2 \in S$ ,必有  $A_1, A_2 \in \mathcal{P}(A)$ ,使得  $f(A_1) = s_1, f(A_2) = s_2$

故有  $s_1 \cup s_2 = f(A_1) \cup f(A_2) = f(A_1 \cup A_2)$  即得  $s_1 \cup s_2 \in S$   $s_1 \cap s_2 = f(A_1) \cap f(A_2) = f(A_1 \cap A_2)$  即得  $s_1 \cap s_2 \in S$  因此, $\langle S, \subseteq \rangle$  是 $\langle \mathcal{P}(B), \subseteq \rangle$ 的子格。

---
#### 6-7

> 设〈A, ∀, ∧〉是一个代数系统,其中∀, ∧都是二元 运算且分别满足幂等性,试举例说明吸收性不一定成立。
> [6-1.(6)]

**解**：

设 $\langle A, \lor, \land \rangle$ 是一个代数系统,其中  $A = \{a,b\}$ ,且  $\lor$  和  $\land$  的运算表分别如表 6-1(a)和表 6-1(b)所示。显然,  $\lor$  和  $\land$  都满足幂等性,但是却有

$$(a \lor b) \land a = b \land a = b$$

即吸收性不成立。

表 6-1

$$\begin{array}{c|ccccc}$$

---
#### 6-8

> 设 a 和 b 是格⟨A,≼⟩中的两个元素,证明:
> - a)  $a \land b = b$  当且仅当  $a \lor b = a$ ;
> - b)  $a \land b \prec b$  和  $a \land b \prec a$  当且仅当  $a \dashv b$  是不可比较的。
> [6-1.(7)]

**证明**：

a) 因为在格中吸收律总是满足的,所以:

若  $a \land b = b$ , 则  $a \lor b = a \lor (a \land b) = a$ , 反之, 若  $a \lor b = a$ , 则  $a \land b = (a \lor b) \land b = b$ 。

b) 若  $a \land b \prec b$  且  $a \land b \prec a$ ,即表明  $a \land b \neq b$  且  $a \land b \neq a$ 。现用反证法:如果  $a \vdash b$  可比较,则

要末  $a \leq b$  而导致  $a \wedge b = a$  的矛盾,要末  $b \leq a$  而导致  $a \wedge b = b$  的矛盾。

因此,a与b是不可比较的。

反之,若a与b是不可比较的,即a大b且b大a,这就表明

$a \land b \neq a$  且  $a \land b \neq b$ 。然而,在格中  $a \land b \leq a$  和  $a \land b \leq b$  总是成立的,因此,就有  $a \land b \prec a$  和  $a \land b \prec b$ 。

---
#### 6-9

> 设 $\langle A, \prec \rangle$ 是一个格,k是 A 中的一个固定元素,试证以下的两个从 A 到 A 的映射  $\varphi_1$  和  $\varphi_2$  都是保序映射,其中  $\varphi_1$  和  $\varphi_2$  分别定义如下:
> 对于任意的  $a \in A$
> $\varphi_1(a) = a \wedge k$
> $\varphi_2(a) = a \vee k$

**证明**：

对于 $a,b \in A$ ,若 $a \leq b$ ,则由格的保序性可得

$a \wedge k \leq b \wedge k$

$a \lor k \leq b \lor k$

这就表明  $\varphi_1(a) \preceq \varphi_1(b)$  和  $\varphi_2(a) \preceq \varphi_2(b)$ 。因此,  $\varphi_1$  和  $\varphi_2$  都是 A 到 A 的保序映射。

---
#### 6-10 证明:在格中若 a ≤ b ≤ c,则

$a \lor b = b \land c$

$(a \land b) \lor (b \land c) = b = (a \lor b) \land (a \lor c)$  [6-1.(8)]

由  $a \leq b$  得  $a \vee b = b$ ,而由  $b \leq c$  得  $b \wedge c = b$ ,所以

$a \lor b = b \land c$

因为 $(a \land b) \lor (b \land c) = (a \land b) \lor b = b$ ,而由  $a \lor b = b$  和  $a \lor c = c$  可得 $(a \lor b) \land (a \lor c) = b \land c = b$ ,所以

$(a \land b) \lor (b \land c) = b = (a \lor b) \land (a \lor c)$

---
#### 6-11

**证明**：

在格中成立:
$(a \land b) \lor (c \land d) \preceq (a \lor c) \land (b \lor d)$
和  $(a \land b) \lor (b \land c) \lor (c \land a) \preceq (a \lor b) \land (b \lor c) \land (c \lor a)$
[6-1,(9)]
因为  $a \land b \preceq a$ ,  $c \land d \preceq c$ , 所以 $(a \land b) \lor (c \land d) \preceq a \lor c$ 又因  $a \land b \preceq b$  和  $c \land d \preceq d$  而得 $(a \land b) \lor (c \land d) \preceq b \lor d$ ,因此,
$(a \land b) \lor (c \land d) \preceq (a \lor c) \land (b \lor d)$
另外,因为 $a \land b \leq a , b \land c \leq b , c \land a \leq a ,$ 所以  $(a \land b) \lor (b \land c) \leq a \lor b$
$((a \land b) \lor (b \land c)) \lor (c \land a) \preccurlyeq (a \lor b) \lor a$
$(a \land b) \lor (b \land c) \lor (c \land a) \leq a \lor b$
同理可得
即得
$(a \land b) \lor (b \land c) \lor (c \land a) \leq b \lor c$
$1 \qquad (a \land b) \lor (b \land c) \lor (c \land a) \leq c \lor a$
所以  $(a \land b) \lor (b \land c) \lor (c \land a) \preceq (a \lor b) \land (b \lor c) \land (c \lor a)$
---
#### 6-12

> 设 $\varphi$  是幂集 $\mathscr{P}(S)$ 的一个格自同态,证明:在 $\varphi$ 作用下映照为同一元素的全体元素所构成的集合对于集合的并和交都是封闭的。

**证明**：

对于 $a \in \mathcal{P}(S)$ ,令

$$R(a) = \{b \mid \varphi(b) = a, b \in \mathcal{P}(S)\}$$

于是,对于任意的  $x,y \in R(a)$ ,有

$$\varphi(x) = \varphi(y) = a$$

得  $x \bigcup y \in R(a)$

得  $x \cap y \in R(a)$

即集合的并和交在 R(a)中都是封闭的。

---
#### 6-13

> 用对偶原理证明定理 6-1.2 中的后一个结论,即在格中若  $a \leq b$  和  $c \leq d$ ,则  $a \wedge c \leq b \wedge d$ 。 【6-1.(10)】

**证明**：

利用定理 6-1.2 中的前一个结论:若  $a \leq b$  和  $c \leq d$ ,则  $a \vee c \leq b \vee d$ 。对此结论应用对偶原理应有,若  $b \leq a$  和  $d \leq c$ ,则

$$b \wedge d \preceq a \wedge c$$

现将 a = b 互换,c = d 互换,即得若  $a \leq b$  和  $c \leq d$ ,则  $a \wedge c \leq b \wedge d$

---
#### 6-14

> 设 $\langle A, \preceq \rangle$ 是一个格,证明: $\langle A, \preceq_R \rangle$ 也是一个格。
> [6-1,(11)]

**证明**：

首先,对于任意的  $a,b,c \in A, a \leq a$  当且仅当  $a \leq_{\mathbb{R}} a$ ,  $\leq_{\mathbb{R}}$  满足自反性;

性,所以有 a=b,因此, $\leq_R$  也满足反对称性;

若  $a \leq_{\mathbb{R}} b \perp b \leq_{\mathbb{R}} c$ ,则有  $b \leq a \perp b$ ,因为 $\leq$ 满足传递性, 所以有  $c \leq a$ ,即可得  $a \leq_{\mathbb{R}} c$ ,因此, $\leq_{\mathbb{R}} c$  也满足传递性。

由上可知、 $\langle A, \prec \rangle$ 是一个偏序集。

其次,对于任意的  $a,b \in A$ ,因为 $\langle A, \prec \rangle$ 是一个格,所以,不妨可设 a,b 的最小上界和最大下界分别为 c,d,则有

由  $a \leq c$  和  $b \leq c$  可导致  $c \leq_{R} a$  和  $c \leq_{R} b$ ,因此,若  $c \neq_{a} b$ , 于 $\leq$ 的最小上界,则 c 必是 a,b 关于 $\leq_{R}$  的最大下界;

由  $d \leq a$  和  $d \leq b$  可导致  $a \leq_{\mathbb{R}} d$  和  $b \leq_{\mathbb{R}} d$ ,因此,若  $d \neq_a,b$  关于 $\leq$ 的最大下界,则 d 必是 a ,b 关于 $\leq_{\mathbb{R}}$  的最小上界。

因此, $\langle A, \leq_R \rangle$ 也是一个格。

---
#### 6-15

> 试举两个含有 6 个元素的格,其中一个是分配格,另一个不是分配格。 【6-2.(1)】

**解**：

分配格如图 6-\neg(a) 所示, 不是分配格如图 6-\neg(b) 所示。

![](_page_17_Picture_9.jpeg)

---
#### 6-16

> 在图 6-8 中给出的几个格,哪个是分配格?【6-2.(2)】

**解**：

(a)和(c)中都有与 同构的子格,所以它们都不是

分配格。(b)是分配格。

![](_page_17_Picture_13.jpeg)

---
#### 6-17

**证明**：

格(I, max, min)是分配格。
[6-2.(3)]
对于任意的  $a,b,c \in I$ ,
$\max(a,\min(b,c))$
$$= \begin{cases} \max(a,b) = \begin{vmatrix} a, b \leq c, b \leq a \\ b, b \leq c, a \leq b \end{vmatrix} \\ \max(a,c) = \begin{vmatrix} a, c \leq b, c \leq a \\ c, c \leq b, a \leq c \end{vmatrix} \end{cases}$$
而
$$\min(\max(a,b), \max(a,c))$$
$$= \begin{cases} \min(a,c) = a, \ b \leq a, a \leq c \\ \min(a,a) = a, \ b \leq a, c \leq a \end{cases}$$
$$= \begin{cases} \min(b,c) = \begin{cases} b, \ a \leq b, a \leq c, b \leq c \\ c, \ a \leq b, a \leq c, c \leq b \end{cases}$$
$$\min(b,a) = a, \ a \leq b, c \leq a \end{cases}$$
所以  $\max(a, \min(b,c)) = \min(\max(a,b), \max(a,c))$
用对偶原理可知
$\min(a, \max(b,c)) = \max(\min(a,b), \min(a,c))$
---
#### 6-18

> 试证:分配格的每个子格必定是分配格。

**证明**：

根据书上给出的一个结论:一个格是分配格的充要条件是该格中没有任何子格与图 6-9 中两个五元素格中的任一个同构。

![](_page_18_Picture_0.jpeg)

![](_page_18_Picture_1.jpeg)

图 6-9

如果分配格的某个子格不是分配格,那么,该子格中必有子格与图 6-9 中两个五元素格中的一个同构,这就导致原分配格中含有与图 6-9 中两个五元素格中的一个同构的矛盾。

因此,分配格的每个子格必定是分配格。

---
#### 6-19

**证明**：

在分配格中,可把分配式更一般地写成:
$$a \wedge (b_1 \vee b_2 \vee \cdots \vee b_n) = (a \wedge b_1) \vee (a \wedge b_2) \vee \cdots \vee (a \wedge b_n)$$
$$a \lor (b_1 \land b_2 \land \cdots \land b_n) = (a \lor b_1) \land (a \lor b_2) \land \cdots \land (a \lor b_n)$$
[6-2.(4)]
用数学归纳法。
归纳基:已知
$$a \wedge (b_1 \vee b_2) = (a \wedge b_1) \vee (a \wedge b_2)$$
$a \vee (b_1 \wedge b_2) = (a \vee b_1) \wedge (a \vee b_2)$
归纳假设:设对 n-1 成立,即有
$$a \wedge (b_1 \vee b_2 \vee \cdots \vee b_{n-1}) = (a \wedge b_1) \vee (a \wedge b_2) \vee \cdots \vee (a \wedge b_{n-1})$$
$$a \lor (b_1 \land b_2 \land \cdots \land b_{n-1}) = (a \lor b_1) \land (a \lor b_2) \land \cdots \land (a \lor b_{n-1})$$
归纳步骤:对n就应有
$$a \wedge (b_1 \vee b_2 \vee \cdots \vee b_{n-1} \vee b_n)$$
$$= [a \wedge (b_1 \vee b_2 \vee \cdots \vee b_{n-1})] \vee (a \wedge b_n)$$
$$=(a \wedge b_1) \vee (a \wedge b_2) \vee \cdots \vee (a \wedge b_{n-1}) \vee (a \wedge b_n)$$
$$a \lor (b_1 \land b_2 \land \cdots \land b_{n-1} \land b_n)$$
$$= [a \lor (b_1 \land b_2 \land \cdots \land b_{n-1})] \land (a \lor b_n)$$
$$= (a \lor b_1) \land (a \lor b_2) \land \cdots \land (a \lor b_{n-1}) \land (a \lor b_n)$$
因此,对于任意 n,分配式总是成立的。
---
#### 6-20

> 设〈A,≼〉是一个分配格,a,b∈A且a ≺b,证明
> $$f(x) = (x \lor a) \land b$$
> 是-个从A到B的同态映射。其中
> $$B = \{x \mid x \in A \perp a \leq x \leq b\}$$
> [6-2.(5)]

**证明**：

首先证明,对任意  $x \in A$ ,必有  $f(x) \in B$ 。

因为 $a \leq x \vee a$ 且 $a \prec b$ ,所以

$$a=a \land b \leq (x \lor a) \land b \leq b$$

$\mathbb{P}_a \preceq f(x) \preceq b$ 。这就表明  $f(x) \in B$ 。因此, f 是从 A 到 B 的一个映射。

其次证明,f是同态映射。

对于任意的  $x,y \in A$ ,

$$f(x \lor y) = ((x \lor y) \lor a) \land b = (x \lor y \lor a) \land b$$
$$= (x \land b) \lor (y \land b) \lor (a \land b)$$

$$f(x) \lor f(y) = ((x \lor a) \land b) \lor ((y \lor a) \land b)$$
$$= (x \land b) \lor (a \land b) \lor (y \land b) \lor (a \land b)$$

$$=(x \land b) \lor (y \land b) \lor (a \land b)$$

所以,

$$f(x \lor y) = f(x) \lor f(y)$$

同理可证

$$f(x \land y) = f(x) \land f(y)$$

因此, f是一个从A到B的同态映射。

---
#### 6-21

> 试举例说明模格不一定是分配格。
> [6-2.(6)]

**解**：

给定格如图 6-10 所示。

对于任意的  $x, y, z \in \{0, 1, a, b, c\}$ , 若有  $y \leq x$ ,则只有 y=0 或者 x=1。

若 y=0,则

$$x \wedge (y \vee z) = x \wedge z$$

$$y \lor (x \land z) = x \land z$$

若 x=1,则

$$x \land (y \lor z) = y \lor z$$

$$y \lor (x \land z) = y \lor z$$

![](_page_18_Figure_51.jpeg)

图 6-10

所以,总有 $x \land (y \lor z) = y \lor (x \land z)$ 。因此,由图 6-10 给出的格是一个模格。然而,它不是分配格。

\* 6-22 证明: 一个格 $\langle A, \preccurlyeq \rangle$ 是分配格当且仅当对任意的 a, b,  $c \in A$ , 有

$$(a \land b) \lor (b \land c) \lor (c \land a) = (a \lor b) \land (b \lor c) \land (c \lor a)$$

[6-2.(7)]

对于任意的  $a,b,c \in A$ , 令

$$a' = (a \lor b) \land (a \lor c)$$

$b'=b \vee c$

c'=a

就有

$(a' \wedge b') \vee (b' \wedge c') \vee (c' \wedge a')$

$= ((a \lor b) \land (a \lor c) \land (b \lor c)) \lor ((b \lor c) \land a)$  $\lor (a \land (a \lor b) \land (a \lor c))$
$= ((a \lor b) \land (a \lor c) \land (b \lor c)) \lor ((b \lor c) \land a) \lor a$
$= ((a \land b) \lor (a \land c) \lor (b \land c)) \lor a$
$=a \lor (b \land c)$

$(a' \lor b') \land (b' \lor c') \land (c' \lor a')$

$= (((a \lor b) \land (a \lor c)) \lor (b \lor c))$

$\wedge ((b \lor c) \lor a) \wedge (a \lor ((a \lor b) \wedge (a \lor c)))$

$= (((a \lor b) \land (a \lor c)) \lor (b \lor c))$

$\bigwedge (a \lor b \lor c) \bigwedge ((a \lor b) \bigwedge (a \lor c))$

$= (((a \lor b) \land (a \lor c)) \lor (b \lor c)) \land ((a \lor b) \land (a \lor c))$
$=(a \lor b) \land (a \lor c)$

所以

$a \lor (b \land c) = (a \lor b) \land (a \lor c)$

同理可证  $a \wedge (b \vee c) = (a \wedge b) \vee (a \wedge c)$

因此,格 $\langle A, \preccurlyeq \rangle$ 是分配格。

反之,若格〈A,≼〉是分配格,则有

$(a \land b) \lor (b \land c) \lor (c \land a) = (b \land (a \lor c)) \lor (c \land a)$

$= (b \lor (c \land a)) \land ((a \lor c) \lor (c \land a))$

$= (a \lor b) \land (b \lor c) \land (c \lor a)$

---
#### 6-23

**证明**：

一个格 $\langle A, \preccurlyeq \rangle$ 是分配格当且仅当对任意的 a,  $b,c \in A$ , 有
$(a \lor b) \land c \preceq a \lor (b \land c)$
${\rm K}(A,\ll)$ 是分配格,由
$a \wedge c \leq a$   $\uparrow$   $a \wedge c \leq a$   $\uparrow$   $a \wedge c \leq a$
可得  $(a \land c) \lor (b \land c) \preceq a \lor (b \land c)$
所以  $(a \lor b) \land c \preceq a \lor (b \land c)$
反之,若对任意的 a, b,  $c \in A$ , 有 $(a \lor b) \land c \preceq a \lor (b \land c)$ ,则 可得
$(a \lor b) \land c = ((b \lor a) \land c) \land c$
$\leq (b \vee (a \wedge c)) \wedge c$
(由已知条件)
$=((a \land c) \lor b) \land c$
$\leq (a \land c) \lor (b \land c)$
(由已知条件)
又由  $a \land c \leq (a \lor b) \land c$  和  $b \land c \leq (a \lor b) \land c$
可得
$(a \land c) \lor (b \land c) \preccurlyeq (a \lor b) \land c$
于是就有
$(a \lor b) \land c = (a \land c) \lor (b \land c)$
由定理 6-2.1 可知
$$(a \land b) \lor c = (a \lor c) \land (b \lor c)$$
因此,格 $\langle A, \preceq \rangle$ 是分配格。
---
#### 6-24

> 举出两个含有 6 个元素的格,其中一个是模格,另一个不是模格。 【6-2.(8)】
> ![](_page_19_Picture_51.jpeg)
> ![](_page_19_Picture_52.jpeg)
> 图 6-11

**解**：

给出两个6元素的格,如图6-11所示。

由定理 6-2.4 可知,图 6-11(a)中的格是模格,而图 6-11(b)中的格不是模格。

---
#### 6-25

**证明**：

一个格是模格当且仅当对于任意的 a,b,c,有
$$a \lor (b \land (a \lor c)) = (a \lor b) \land (a \lor c)$$
[6-2.(9)]
设 $\langle A, \prec \rangle$ 是一个格,且对于任意的  $a,b,c \in A$ ,上式成立,则当  $a \prec c$  时,就有  $a \lor c = c$ ,故得
$$a \lor (b \land c) = (a \lor b) \land c$$
所以、 $\langle A, \preccurlyeq \rangle$ 是模格。
反之,若 $\langle A, \preceq \rangle$ 是模格,则对任意的  $a, b, c \in A$ ,当  $a \preceq c$  时,有
$$a \lor (b \land c) = (a \lor b) \land c$$
因为  $a \leq a \lor c$ ,所以
$$a \lor (b \land (a \lor c)) = (a \lor b) \land (a \lor c)$$
---
#### 6-26

> 设 $\langle A, \preccurlyeq \rangle$ 是模格, $x,y,a \in A$ ,且 x,y 分别盖住 a,证明  $x \lor y$  盖住 x 和 y。 【6-2.(10)】

**证明**：

由题意可知: $a \leq x$ , $a \leq y$ ,且没有  $z \in A$ ,使得

![](_page_20_Picture_13.jpeg)

$a \leq z \leq x$ ,  $a \leq z \leq y$

所以, $x \land y = a$ 。

又因  $x \leq x \vee y, y \leq x \vee y$ 。如果另有  $z \in A$ ,使得

$y \leq z \leq x \vee y$

那么,就应有图 6-12 的情况出现。

现考察 y V (z A x),有以下三种可能:

图 6-12 (i) 若  $z \land x = x$ ,则  $x \preceq z$ 。又因  $y \preceq z$ ,故 有  $x \lor y \preceq z$ ,所以只能有  $x \lor y = z$ ;

(ii)  $z \land x = z, 则 z \preceq x, 这是不可能的;$
(iii) 若 $z \land x = a$ ,则 $y \lor (z \land x) = y \lor a = y$ 。另有 $z \land (y \lor x)$ =z。因为 $y \preccurlyeq z$ ,故由模格的定义可得

$$y \lor (z \land x) = z \land (y \lor x)$$

所以

y=z

由此可见 x V y 盖住 y。

同理可证 x V y 盖住 x。

\*6-27 设 $\langle S, \leq \rangle$ 是模格, $a, b \in S$ ,作  $X = \langle x | x \in S$ ,且 $a \land b \leq x \leq a \rangle$ , $Y = \langle y | y \in S$ ,且 $b \leq y \leq a \lor b$ ,则下面的互逆映射

$$x \rightarrow x \lor b \quad (x \in X)$$

$y \rightarrow y \land a \quad (y \in Y)$

是X和Y之间的同构。

[6-2.(11)]

记

$$f: x \rightarrow x \lor b \quad (x \in X)$$

$$g: y \rightarrow y \land a \quad (y \in Y)$$

由于 $a \land b \leq x \leq a$ , 所以 $(a \land b) \lor b \leq x \lor b \leq a \lor b$ , 即 $b \leq x \lor b \leq a \lor b$ , 故  $f \not\in X$  到 Y 的映射;类似地可知, $g \not\in Y$  到 X 的映射。

对于任意的  $x \in X$ ,有

$$g(f(x)) = g(x \lor b) = a \land (x \lor b)$$

$= x \lor (a \land b)$  (因为  $x \le a$ ,并用模格条件)
$= x$  (因为  $a \land b \le x$ )

这就表明 g 是 f 的左逆。类似地,由于对任意的  $y \in Y$

$$f(g(y)) = f(y \land a) = (y \land a) \lor b = y \land (a \lor b) = y$$

所以g也是f的右逆。因此,f和g都是双射。

另外,设 $a \land b \leq x_1 \leq x_2 \leq a$ ,则有  $(x_1 \lor b) \lor (x_2 \lor b) = (x_1 \lor x_2) \lor b = x_2 \lor b$  由此可知  $x_1 \lor b \leq x_2 \lor b$ , 所以, f 是保序 映射。

类似地,容易验证 g 也是保序映射。

由上所述, f 和 g 分别是 X 到 Y 和 Y 到 X 的双射保序映射, 于是, 根据定理 6-1.9 即 可知, f 与 g 都是 X 和 Y 之间的同构映射。

---
#### 6-28

> 试根据图 6-13 所示的有界格,回 答以下问题。
> ![](_page_20_Figure_45.jpeg)
> 图 6-13
> - a) a 和 f 的补元素分别是哪些元素?
> - b) 该有界格是分配格吗?
> - c) 该有界格是有补格吗?
> [6-3.(1)]

**解**：

a) a和f都没有补元。

b) 因为  $c \land (e \lor f) = c \land a = c$ ,而

$$(c \land e) \lor (c \land f) = e \lor a = a$$

所以, $c \land (e \lor f) \neq (c \land e) \lor (c \land f)$ 。因此,它不是分配格。

c) 显然地, d 就没有补元。因此, 它不是有补格。

---
#### 6-29

**证明**：

在有界格中 0 是 1 的唯一补元, 1 是 0 的唯一补元。 【6-3.(2)】
因为  $0 \lor 1 = 1,0 \land 1 = 0$ ,所以 0 和 1 互为补元。若 1 的另一补元为  $0_1$ ,则
$$0_1 \land 1=0, 0_1 \lor 1=1$$
但  $0 \le 0_1 \le 1$ ,所以  $0_1 \land 1 = 0_1$ ,由此可得  $0_1 = 0$ 。因此,0 是 1 的 唯一补元。
同理可证,1是0的唯一补元。
---
#### 6-30

> 试举例说明,有补格不一定是分配格,分配格不一定是有补格。

**解**：

给出两个格,如图 6-14 所示。其中,(a)是分配格,但不 是有补格;(b)是有补格,但不是分配格。

![](_page_21_Figure_16.jpeg)

---
#### 6-31

**证明**：

具有两个或更多个元素的格中不存在以自身为补元的元素。 【6-3.(3)】
凡涉及到补元,该格必为有界格。对于任何一个有界 格来说,自然有
$$1 \lor 1=1,1 \land 1=1$$
$0 \lor 0=0,0 \land 0=0$
所以,0 和 1 都不可能以自身为补元。这就表明,具有两个元素的格中不可能存在以自身为补元的元素。
对于具有多于两个元素的有界格来说,我们考察该格中的任一元素  $a,a\neq 0$  且  $a\neq 1$ 。
故具有多于两个元素的格中也不存在以自身为补元的元素。
---
#### 6-32

> 在有界分配格中,证明具有补元的那些元素组成一个 子格。 【6-3.(4)】

**证明**：

在有界分配格中,至少有一个子格{0,1}。

设在有界分配格中具有补元的元素所组成的集合记为 C。对于任意的  $a,b \in C$ ,它们的补元分别记为  $\overline{a},\overline{b}$ 。

先考察 a V b, 因为

$$(a \lor b) \lor (\overline{a} \land \overline{b}) = (a \lor b \lor \overline{a}) \land (a \lor b \lor \overline{b})$$

$$= (b \lor 1) \land (a \lor 1) = 1 \land 1 = 1$$

$$(a \lor b) \land (\overline{a} \land \overline{b}) = (a \land \overline{a} \land \overline{b}) \lor (b \land \overline{a} \land \overline{b})$$

$$= (0 \land \overline{b}) \lor (0 \land \overline{a}) = 0 \lor 0 = 0$$

所以, $a \lor b \in C$ 。

再考察 a ∧ b, 因为

$$(a \wedge b) \vee (\overline{a} \vee \overline{b}) = (a \vee \overline{a} \vee \overline{b}) \wedge (b \vee \overline{a} \vee \overline{b})$$

$$= (\overline{b} \vee 1) \wedge (\overline{a} \vee 1) = 1 \wedge 1 = 1$$

$$(a \wedge b) \wedge (\overline{a} \vee \overline{b}) = (a \wedge b \wedge \overline{a}) \vee (a \wedge b \wedge \overline{b})$$

$$= (0 \wedge b) \vee (0 \wedge a) = 0 \vee 0 = 0$$

所以, $a \land b \in C$ 。

因此,C是子格。

---
#### 6-33

> 试证明:具有三个或更多个元素的链不是有补格。
> [6-3.(5)]

**证明**：

设具有三个或更多个元素的链为 $\langle A, \prec \rangle$ 。

对于任一元素  $a \in A$ ,且  $a \neq 0$ , $a \neq 1$ ,如果 a 有补元 b,即有  $a \lor b = 1$ , $a \land b = 0$ 。因为 $\langle A, \preceq \rangle$ 是链,所以必有  $a \preceq b$  或  $b \preceq a$ 。

若  $a \leq b$ ,则有  $a \wedge b = a$ ,这就导致 a = 0 的矛盾;

若 b ≤ a,则有  $a \lor b = a$ ,这又导致 a = 1 的矛盾。

这就表明a的补元b是不存在的。因此,这种链不是有补格。

---
#### 6-34

> 设 $\langle A, \leq \rangle$ 是一个有界格,对于 $x,y \in A$ ,证明:
> - a) 若  $x \lor y = 0$  则 x = y = 0;
> - b) 若 $x \land y = 1$ 则x = y = 1。
> [6-3.(6)]

**证明**：

a) 若 $x \lor y = 0$ 。由定义可知 $x \le 0, y \le 0$ ,由于0是全下界,所以不可能有x < 0 和y < 0,因此,x = y = 0。

b) 若  $x \land y = 1$ 。由定义可知  $1 \le x$ , $1 \le y$ ,由于 1 是全上界, 所以不可能有  $1 \le x$  和  $1 \le y$ ,因此,x = y = 1。

---
#### 6-35

**证明**：

在布尔代数中,有
$a \lor (\overline{a} \land b) = a \lor b$
$a \wedge (\overline{a} \vee b) = a \wedge b$  [6-4.(1)]
因为布尔代数是由布尔格所诱导的代数系统,而布尔格是有补分配格,所以就应有
$a \lor (\overline{a} \land b) = (a \lor \overline{a}) \land (a \lor b) = 1 \land (a \lor b) = a \lor b$
$a \wedge (\overline{a} \vee b) = (a \wedge \overline{a}) \vee (a \wedge b) = 0 \vee (a \wedge b) = a \wedge b$
---
#### 6-36

> 设 $\langle S, \lor, \land, \neg \rangle$ 是一个布尔代数, $x, y \in S$ ,证明: $x \le y$  当且仅当  $\overline{y} \le \overline{x}$ 。 【6-4.(2)】

**证明**：

由引理 6-4.1 可知

$\overline{y} \leq \overline{x}$ ,当且仅当 $\overline{y} \wedge \overline{x} = 0$

即有

$\overline{y} \leq \overline{x}$ ,当且仅当  $\overline{y} \wedge x = 0$

再由引理 6-4.1 即得

$x \land \overline{y} = 0$ ,当且仅当  $x \leq y$

因此,在布尔代数中, $x \leq y$  当且仅当  $\overline{y} \leq \overline{x}$ 。

---
#### 6-37

> 设 $\langle A, \vee, \wedge, \rangle$ 是一个布尔代数,如果在 A 上定义二元运算 $\oplus$ 为:
> $a \oplus b = (a \wedge \overline{b}) \vee (\overline{a} \wedge b)$

**证明**：

〈A, ①〉是一个阿贝尔群。

[6-4.(3)]

(i) 由  $\land$  ,  $\lor$  ,  $\dot{}$  这三个运算在 A 上都是封闭的,所以,运算 $\oplus$  在 A 上也是封闭的;

(ii) 对于任意的  $a,b,c \in A$

$(a \oplus b) \oplus c = ((a \land \overline{b}) \lor (\overline{a} \land b)) \oplus c$

$= (((a \wedge \overline{b}) \vee (\overline{a} \wedge b)) \wedge \overline{c})$

$\bigvee (\overline{((a \land \overline{b}) \lor (\overline{a} \land b))} \land c)$

$= (a \wedge \overline{b} \wedge \overline{c}) \vee (\overline{a} \wedge b \wedge \overline{c})$

$\bigvee (((\overline{a} \lor b) \land (a \lor b)) \land c)$

$= (a \wedge \overline{b} \wedge \overline{c}) \vee (\overline{a} \wedge \overline{b} \wedge \overline{c})$

$\bigvee (((a \land b) \lor (\overline{a} \land \overline{b})) \land c)$

$= (a \wedge \overline{b} \wedge \overline{c}) \vee (\overline{a} \wedge b \wedge \overline{c})$

$\forall (a \land b \land c) \lor (\overline{a} \land \overline{b} \land c)$

同理可得

$a \oplus (b \oplus c) = (a \land \overline{b} \land \overline{c}) \lor (\overline{a} \land b \land \overline{c}) \lor (\overline{a} \land \overline{b} \land c)$ 所以, $a \oplus (b \oplus c) = (a \oplus b) \oplus c$ ,即运算⊕满足结合性;

(iii) 因为

$a \oplus b = (a \land \overline{b}) \lor (\overline{a} \land b) = (b \land \overline{a}) \lor (\overline{b} \land a) = b \oplus a$ 所以,运算⊕满足可交换性;

(iv) 对于任意的  $a \in A$ ,有

$a \oplus 0 = 0 \oplus a = (0 \land \overline{a}) \lor (\overline{0} \land a) = 0 \lor (1 \land a) = 0 \lor a = a$

故0是A中关于运算⊕的幺元;

(v) 对于任意的  $a \in A$ ,有

$a \oplus a = (a \land \overline{a}) \lor (\overline{a} \land a) = 0 \lor 0 = 0$

这说明 A 中的每一个元素均以其自身为逆元。

因此,⟨A,⊕⟩是一个阿贝尔群。

---
#### 6-38

> 设 $\langle A, \vee, \wedge, - \rangle$ 是一个有限布尔代数, $a_1, a_2, \cdots, a_n$ 是该布尔代数中的全部原子。试证明:对于这些原子的任意一种排列  $a_{i_1}, a_{i_2}, \cdots, a_{i_n}$ ,都有
> $$\overline{\bigvee_{j=1}^{k} a_{i_j}} = \bigvee_{j=k+1}^{n} a_{i_j}$$

**证明**：

由引理 6-4.2 可知

$$\bigvee_{i=1}^{n} a_i = 1$$

由此可得  $\left(\bigvee_{j=1}^k a_{i_j}\right) \vee \left(\bigvee_{j=k+1}^n \dot{a}_{i_j}\right) = \bigvee_{i=1}^n a_{i_j} = \bigvee_{i=1}^n a_i = 1$

又由于对任意两个原子  $a_{\nu}$ ,  $a_{\sigma}$ , 均有  $a_{\nu}$   $\wedge a_{\sigma} = 0$ , 故有

$$\left(\bigvee_{j=1}^{k} a_{i_j}\right) \wedge \left(\bigvee_{j=k+1}^{n} a_{i_j}\right) = \bigvee_{j=1}^{k} \bigvee_{m=k+1}^{n} \left(a_{i_j} \wedge a_{i_m}\right) = 0$$

由此可见,  $\bigvee_{j=1}^{k} a_{i_j} \prod_{j=k+1}^{n} a_{i_j}$  是互为补元的。

因此,就有

$$\overline{\bigvee_{j=1}^{k} a_{i_j}} = \bigvee_{j=k+1}^{n} a_{i_j}$$

---
#### 6-39

> 在一个具有全上界 1 的格中,如果有元素 a 被 1 盖住,则称元素 a 为反原子。试证明,在任何一个有限布尔代数 $\langle A, \vee, \wedge, - \rangle$ 中,原子的个数必定与反原子的个数相等。

**证明**：

首先证明 A 中的任一原子 a ,其补元素  $\overline{a}$  必是一个反原子。用反证法,假设  $\overline{a}$  不是反原子,那么必定存在  $b \in A$  ,使得

$$\overline{a} \prec b \prec 1$$

若  $b \land a = 0$ ,则由引理 6-4.1 可知  $b \preceq \overline{a}$ ,这就与假设相矛盾, 所以  $b \land a \neq 0$ 。

由于 a 是原子,故  $b \land a = a$ ,即有  $a = b \land a \leq b$ ,又因有  $\overline{a} \prec b$ , 故得  $a \lor \overline{a} \leq b$ ,从而导致  $1 \leq b$  的矛盾。

由此可见,ā必是反原子。

因为在布尔代数中,任一元素有且仅有一个补元素,所以,在 有限布尔代数中,原子和反原子总是成对出现的,因此,在任何一 个有限布尔代数中,原子的个数必定等于反原子的个数。

---
#### 6-40

> 设 $\langle A, \vee, \wedge, \neg \rangle$ 是一个布尔代数,在 A 上定义二元运算  $a \wedge b = \overline{a \wedge b}$ ,则布尔代数中的运算都可用运算  $\wedge$  来表示。

**证明**：

对于任意的  $a,b \in A$ ,有

$$a \lor b = \overline{(a \lor b)} = \overline{(\overline{a} \land \overline{b})} = \overline{((a \land a) \land (\overline{b} \land \overline{b}))}$$

$$= \overline{((a \land a) \land (b \land b))} = (a \land a) \land (b \land b)$$

$$a \land b = \overline{(\overline{a} \land \overline{b})} = \overline{(a \land b)} = \overline{((a \land b) \land (a \land b))}$$

$$= (a \land b) \land (a \land b)$$

$$\overline{a} = a \land a = a \land a$$

---
#### 6-41

> 设 $\langle A, V, \Lambda, ^- \rangle$ 是一个布尔代数,如果在 A 上定义二 元运算+ ,。为:
> $$a+b=(a \wedge \overline{b}) \vee (\overline{a} \wedge b)$$
> $$a \cdot b=a \wedge b$$

**证明**：

$\langle A, +, \bullet \rangle$ 是以1为幺元的环。

[6-4.(4)]

由习题 6-37 可知,〈A,+〉是阿贝尔群;

由于运算  $\Lambda$  的封闭性和可结合性,故 $\langle A, \bullet \rangle$ 是半群;

对于任意的  $a,b,c \in A$ ,有

$$a \cdot (b+c) = a \wedge ((b \wedge \overline{c}) \vee (\overline{b} \wedge c)) = (a \wedge b \wedge \overline{c}) \vee (a \wedge \overline{b} \wedge c)$$

$$a \cdot b + a \cdot c = (a \wedge b) + (a \wedge c)$$

$$= ((a \wedge b) \wedge \overline{(a \wedge c)}) \vee (\overline{(a \wedge b)} \wedge (a \wedge c))$$

$$= ((a \land b) \land (\overline{a} \lor \overline{c})) \lor ((\overline{a} \lor \overline{b}) \land (a \land c))$$

$$=(a \wedge b \wedge \overline{c}) \vee (a \wedge \overline{b} \wedge c)$$

所以, $a \cdot (b+c) = a \cdot b + a \cdot c$ 。 **同理可证**, $(b+c) \cdot a = b \cdot a + c \cdot a$ 。 对于任意的  $a \in A$ ,有

$$1 \cdot a = 1 \land a = a, a \cdot 1 = a \land 1 = a$$

所以,1是关于运算•的幺元。

因此, $\langle A, +, \cdot \rangle$ 是以 1 为幺元的环。

---
#### 6-42

> 对于上一题中的二元运算十和•,证明:
> - a) (a+b)+b=a;
> - b)  $a \cdot (b+c) = (a \cdot b) + (a \cdot c);$
> - c) a+a=0;
> - d) a+0=a;
> e)
> $$a+1=\overline{a}$$
> .
> [6-4.(5)]

**证明**：

a) 由习题 6-37 可知,运算十是可结合的,所以

$$(a+b)+b=a+(b+b)=a+((b \wedge \overline{b}) \vee (\overline{b} \wedge b))$$
$$=a+(0 \vee 0)=a+0=(a \wedge \overline{0}) \vee (\overline{a} \wedge 0)$$
$$=a \vee 0=a$$

b) 在上一题中已获证。
c) 在 a)的证明中已可见。
d) 在 a)的证明中已可见。
e)  $a+1=(a \wedge \overline{1}) \vee (\overline{a} \wedge 1)=(a \wedge 0) \vee \overline{a}=0 \vee \overline{a}=\overline{a}$ .

---
#### 6-43

> 设  $K = \{1, 2, 5, 10, 11, 22, 55, 110\}$  是所有整因子的集合,证明:具有全上界 110 和全下界 1 的代数系统 $\langle K, LCM, GCD, '\rangle$  是一个布尔代数,这里,对于任意的  $x \in K, x' = 110/x$ 。 【6-4.(6)】
> ![](_page_24_Picture_6.jpeg)

**证明**：

显然,代数系统 $\langle K, LCM, GCD,'\rangle$ 是由格 $\langle K, |\rangle$ 所诱导的,其中|为整除关系。关于格 $\langle K, |\rangle$ 的哈斯图如图 6-15 所示。

由此哈斯图可见,其中不存在与书上图 6-9 中两个五元素格同构的子格,所以,格 $\langle K, | \rangle$ 是一个分配格。

因为对于任意一个  $x \in K$ ,存在 x' = 110/x,使得

$$LCM(x,x') = 110,GCD(x,x') = 1$$

例如,22' = 5,LCM (22,5) = 110,
$GCD(22,5) = 1;10' = 11,LCM(10,11) =$

110,GCD(10,11)=1;…,等等。所以,格 $\langle K, | \rangle$ 是一个有补格。 因此, $\langle K, LCM, GCD, ' \rangle$ 是一个布尔代数。

---
#### 6-44

> 设 $\langle K, \vee, \wedge, ' \rangle$ 和 $\langle L, \cup, \cap, - \rangle$ 是两个布尔代数,并设 f 是从 K 到 L 的满同态,即对于任意的  $x,y \in K$ ,有
> $$f(x \land y) = f(x) \cap f(y), f(x \lor y) = f(x) \cup f(y); f(x') = \overline{f(x)}$$
> 试证明:
> $$f(0_k) = 0_t$$
> $f(1_k)=1_i$
> 这里 $,0_{k},0_{l}$  和  $1_{k},1_{l}$  分别是相应的布尔代数中的全下界和全上界。 【6-4.(7)】

**证明**：

因为 f 是从 K 到 L 的满射, 故对任意的  $l \in L$ , 必存在

$_{k\in K}$ ,使得 f(k)=l。

又因  $l \cup f(0_k) = f(k) \cup f(0_k) = f(k \vee 0_k) = f(k) = l$ 和  $l \cap f(1_k) = f(k) \cap f(1_k) = f(k \wedge 1_k) = f(k) = l$ 故有  $f(0_k) \leq l$  和  $l \leq f(1_k)$ 。

由于 l 的任意性,所以  $f(0_k)$ 和  $f(1_k)$ 分别是 L 中的全下界和全上界。而布尔代数中的全下界和全上界都是唯一的。因此,必有  $f(0_k)=0_l$ ,  $f(1_k)=1_l$

---
#### 6-45

> 设 12 和 24 的整因子集合分别为  $K_1 = \{1,2,3,4,6,12\}$ 和  $K_2 = \{1,2,3,4,6,8,12,24\}$ ,试问  $\{K_1,LCM,GCD,'\}$ 和  $\{K_2,LCM,GCD,'\}$ 是布尔代数吗?

**解**：

因为 $|K_1|$ =6,而由推论 6-4.1 可知有限布尔格的元素个数必定等于 2",所以 $\langle K_1, \prec \rangle$ 不是布尔格,由此可知 $\langle K_1, LCM, GCD, '\rangle$ 就不是布尔代数。

因为 $\langle K_2$ ,LCM,GCD, $\rangle$  是由格 $\langle K_2$ , $\langle K_2 \rangle$  所 诱导的,这里《是整除关系,即对于  $k_1$ , $k_2 \in K_2$ ,  $k_1 \leq k_2$  当且仅当  $k_1$  整除  $k_2$ ,而由图 6-16 所示 的关于 $\langle K_2 \rangle$  的哈斯图可知 $\langle K_2 \rangle$  不是一个 有补格(因为 2,4,6,12 均没有补元),所以 $\langle K_2 \rangle$  图 6-  $\langle K_2 \rangle$  不是布尔格,因此, $\langle K_2 \rangle$  上CM,GCD, $\langle K_2 \rangle$  也不是布尔代数。

![](_page_24_Figure_23.jpeg)

---
#### 6-46

> 设 a,  $b_1$ ,  $b_2$ , …,  $b_r$  都是布尔代数 $\langle A, \lor, \land, \neg \rangle$ 的原子,那么, $a \leq (b_1 \lor b_2 \lor \dots \lor b_r)$ 当且仅当存在着  $i(1 \leq i \leq r)$  使得 $a=b_i$ 。
> [!tip] 6-4.(9)
> 

**证明**：

充分性 若  $a=b_i(1 \leq i \leq r)$ ,则有  $a=b_i \leq b_i \vee (b_1 \vee b_2 \vee \cdots \vee b_{i-1} \vee b_{i+1} \vee \cdots \vee b_r)$

必要性 用反证法。设  $a \leq (b_1 \vee b_2 \vee \cdots \vee b_r)$ 而不存在  $i(1 \leq i \leq r)$ ,使得  $a = b_i$ 。

因为  $a,b_1,b_2,\cdots,b_r$  都是原子,所以就有  $(a \wedge b_1) \vee (a \wedge b_2) \vee \cdots \vee (a \wedge b_r) = 0 \vee 0 \vee \cdots \vee 0 = 0$  现考察  $a \wedge \overline{(b_1 \vee b_2 \vee \cdots \vee b_r)}$ ,因为

$$a \wedge \overline{(b_1 \vee b_2 \vee \cdots \vee b_r)} = a \wedge (b_1 \vee b_2 \vee \cdots \vee b_r)$$

$$= (a \wedge b_1) \vee (a \wedge b_2) \vee \cdots \vee (a \wedge b_r)$$

$$= 0$$

所以,由引理 6-4.1 可知, $a \leq \overline{(b_1 \vee b_2 \vee \cdots \vee b_r)}$ ,再由引理 6-4.4 可知, $a \leq (b_1 \vee b_2 \vee \cdots \vee b_r)$ ,这就与假设相矛盾。

因此,必存在  $i(1 \leq i \leq r)$  使得  $a = b_i$ 。

---
#### 6-47

> 设  $b_1$ ,  $b_2$ , …,  $b_r$  是有限布尔代数〈A, V,  $\Lambda$ ,  $^-$ 〉中的所有原子,那么 y=0 当且仅当对每个 i 都有  $y \wedge b_i=0$ ,这里,  $1 \le i \le r_o$  【6-4.(10)】

**证明**：

必要性 是显然的。若
$$y=0$$
,必有  $y \wedge b_i=0$   $(i=1,2,\dots,r)$

充分性 用反证法。假设  $y \wedge b_i = 0$   $(i=1,2,\dots,r)$  而  $y \neq 0$ 。于是,由定理 6-4.2 可知,至少存在一个原子  $b_j$   $(1 \leq j \leq r)$ ,使得  $b_j \leq y$ ,从而导致  $y \wedge b_j = b_j \neq 0$  的矛盾。所以必有 y=0。

---
#### 6-48

> 设  $E(x_1,x_2,x_3)=(x_1 \land x_2) \lor (x_2 \land x_3) \lor (\overline{x_2} \land x_3)$ 是 布尔代数 $\langle \{0,1\}, \lor, \land, \neg \rangle$ 上的一个布尔表达式。试写出  $E(x_1,x_2,x_3)$ 的析取范式和合取范式。 【6-5.(1)】

**解**：

对于给出的布尔表达式

$E(x_1,x_2,x_3)=(x_1 \land x_2) \lor (x_2 \land x_3) \lor (\overline{x_2} \land x_3)$ 可以写出其对应的函数表,如表 6-2 所示。

表 6-2

| $x_1$ | $x_2$ | $x_3$ | $E(x_1,x_2,x_3)$ |
|-------|-------|-------|------------------|
| 0     | 0     | 0     |
| 0     | 0     | 1     |
| 0     | 1     | 0     |
| 0     | 1     | 1     |
| 1     | 0     | 0     |
| 1     | 0     | 1     |
| 1     | 1     | 0     | •
| 1     | 1     | 1     |
因为函数值为 1 所对应的有序三元组依次为〈0,0,1〉,〈0,1,1〉,〈1,0,1〉,〈1,1,0〉,〈1,1,1〉,所以可分别构造小项为  $\overline{x_1}$   $\wedge \overline{x_2}$   $\wedge x_3$  , $\overline{x_1}$   $\wedge x_2$   $\wedge x_3$  , $x_1$   $\wedge \overline{x_2}$   $\wedge x_3$  , $x_1$   $\wedge x_2$   $\wedge x_3$  , $x_1$   $\wedge x_2$   $\wedge x_3$  , $x_1$   $\wedge x_2$   $\wedge x_3$  , $x_1$   $\wedge x_2$   $\wedge x_3$  . 因此,布尔表达式  $E(x_1,x_2,x_3)$ 的析取范式为

$$E(x_1, x_2, x_3) = (\overline{x}_1 \wedge \overline{x}_2 \wedge x_3) \vee (\overline{x}_1 \wedge x_2 \wedge x_3) \vee (x_1 \wedge x_2 \wedge x_3)$$
$$\vee (x_1 \wedge x_2 \wedge \overline{x}_3) \vee (x_1 \wedge x_2 \wedge x_3)$$

又因为函数值为 0 所对应的有序三元组依次为〈0,0,0〉,〈(0,1,0),〈(1,0,0),所以可分别构造大项为  $x_1 \lor x_2 \lor x_3$ , $x_1 \lor \overline{x_2} \lor x_3$ , $\overline{x_1} \lor x_2 \lor x_3$ 。因此, $E(x_1,x_2,x_3)$ 的合取范式为

$$E(x_1,x_2,x_3) = (x_1 \lor x_2 \lor x_3) \land (x_1 \lor \overline{x_2} \lor x_3) \land (\overline{x_1} \lor x_2 \lor x_3)$$

---
#### 6-49

> 设  $E(x_1, x_2, x_3, x_4) = (x_1 \land x_2 \land \overline{x_3}) \lor (x_1 \land \overline{x_2} \land x_4)$   $\lor (x_2 \land \overline{x_3} \land \overline{x_4})$ 是布尔代数 $\langle \{0,1\}, \lor, \land, \neg \rangle$ 上的一个布尔表达式。试写出  $E(x_1, x_2, x_3, x_4)$ 的析取范式和合取范式。 【6-5.(2)】

**解**：

先写出布尔表达式  $E(x_1,x_2,x_3,x_4)$ 所对应的函数表,如表 6-3 所示。

表 6-3

| $x_1$ | $x_2$ | $x_3$ | *x* <sub>4</sub> | $E(x_1,x_2,x_3,x_4)$ |
|-------|-------|-------|-----------------------|----------------------|
| 0     | 0     | 0     | 0                     |
| 0     | 0     | 0     | 1                     |
| 0     | 0     | 1     | 0                     |
| 0     | 0     | 1     | 1                     |
| 0     | 1     | 0     | 0                     |
| 0     | 1     | 0     | 1                     |
| 0     | 1     | 1     | 0                     |
| 0     | 1     | 1     | 1                     |
| 1     | 0     | 0     | 0                     |
| 1     | 0     | 0     | 1                     |
| 1     | 0     | 1     | 0                     |
| 1     | 0     | 1     | 1                     |
| 1     | 1     | 0     | 0                     |
| 1     | 1     | 0     | 1                     |
| 1     | 1     | 1     | 0                     |
| 1     | 1     | 1     | 1                     |
由此可得, $E(x_1,x_2,x_3,x_4)$ 的析取范式为

$$E(x_1, x_2, x_3, x_4) = (\overline{x}_1 \wedge x_2 \wedge \overline{x}_3 \wedge \overline{x}_4) \vee (x_1 \wedge \overline{x}_2 \wedge \overline{x}_3 \wedge x_4)$$

$$\vee (x_1 \wedge \overline{x}_2 \wedge x_3 \wedge x_4) \vee (x_1 \wedge x_2 \wedge \overline{x}_3 \wedge \overline{x}_4)$$

$$\vee (x_1 \wedge x_2 \wedge \overline{x}_3 \wedge x_4)$$

而  $E(x_1,x_2,x_3,x_4)$ 的合取范式为

$$E(x_1, x_2, x_3, x_4) = (x_1 \lor x_2 \lor x_3 \lor x_4) \land (x_1 \lor x_2 \lor x_3 \lor \overline{x}_4)$$

$$\land (x_1 \lor x_2 \lor \overline{x}_3 \lor x_4) \land (x_1 \lor x_2 \lor \overline{x}_3 \lor \overline{x}_4)$$

$$\land (x_1 \lor \overline{x}_2 \lor x_3 \lor \overline{x}_4) \land (x_1 \lor \overline{x}_2 \lor \overline{x}_3 \lor \overline{x}_4)$$

$$\land (x_1 \lor \overline{x}_2 \lor \overline{x}_3 \lor \overline{x}_4) \land (\overline{x}_1 \lor x_2 \lor x_3 \lor x_4)$$

$$\land (\overline{x}_1 \lor x_2 \lor \overline{x}_3 \lor x_4) \land (\overline{x}_1 \lor \overline{x}_2 \lor \overline{x}_3 \lor x_4)$$

$$\land (\overline{x}_1 \lor \overline{x}_2 \lor \overline{x}_3 \lor \overline{x}_4)$$

---
#### 6-50

> 对于表 6-4 中的函数 f,试分别用析取范式和合取范式来表示。
> 表 6-4
> |         | f       |
> |---------|---------|
> | (0,0,0) |
> | (0,0,1) |
> | (0,1,0) |
> | (0,1,1) |
> | (1,0,0) |
> | (1,0,1) |
> | (1,1,0) |
> | (1,1,1) | 1 - 1
> |         |         |

**解**：

由表 6-4 可知, f 的析取范式为

$f = (\overline{x}_1 \land \overline{x}_2 \land \overline{x}_3) \lor (\overline{x}_1 \land x_2 \land \overline{x}_3)$  $\lor (x_1 \land \overline{x}_2 \land x_3) \lor (x_1 \land x_2 \land x_3)$

f的合取范式为

## 第七章 图论

#### 7-1

**证明**：

在任何有向完全图中,所有结点人度的平方之和等于所有结点的出度平方之和。
设有向完全图具有 n 个结点。对任一结点  $v_i$  均有  $\deg^+(v_i) + \deg^-(v_i) = n-1$
又因边数 =
$$\frac{1}{2}n(n-1) = \sum_{i=1}^{n} deg^{+}(v_{i}) = \sum_{i=1}^{n} deg^{-}(v_{i})$$
,故而
$$\sum_{i=1}^{n} [\deg^{-}(v_{i})]^{2} = \sum_{i=1}^{n} [(n-1) - \deg^{+}(v_{i})]^{2}$$
$$= \sum_{i=1}^{n} (n-1)^{2} - \sum_{i=1}^{n} 2(n-1) \deg^{+}(v_{i})$$
$$+ \sum_{i=1}^{n} [\deg^{-}(v_{i})]^{2}$$
$$= n(n-1) - 2(n-1) \sum_{i=1}^{n} \deg^{+}(v_{i})$$
$$+ \sum_{i=1}^{n} [\deg^{+}(v_{i})]^{2}$$
$$= n(n-1) - 2(n-1) \cdot \frac{1}{2}n(n-1)$$
$$+ \sum_{i=1}^{n} [\deg^{+}(v_{i})]^{2}$$
$$= \sum_{i=1}^{n} [\deg^{+}(v_{i})]^{2}$$
---
#### 7-2

> 至少有两个结点的简单图有两个相同度数的结点。

**解**：

设 G 是一个具有 n 个结点的简单图 ( $n \ge 2$ )。因为每个 4 结点仅仅能够与另外的 n-1 个结点邻接,所以,每个结点的度数 n-1。因此,在 n-10

$$0,1,2,\dots,n-1$$

由于度数是 0 的结点是孤立结点,而度数为 n-1 的结点是邻接其他n-1 个结点的,所以,在 G 中度数为 0 和度数为 n-1 的结点不可能同时出现。因此,在 G 中可以出现的度数应该分成以下两种情况:

(1)  $0,1,2,\dots,n-2$
(2)  $1,2,3,\dots,n-1$

无论是哪一种情况都最多有n-1种不同的度数。就第一种情况而言,我们可以设想具有编号为 $0,1,2,\cdots,n-2$ 的n-1只匣子,现将G中的结点按其度数放入与编号数相同的匣子中去。因为G中有n个结点,而匣子仅有n-1只,所以总有一只匣子包含两个或两个以上的结点,这些结点具有相同的度数。对于第二种情况,也可类似地证明。

---
#### 7-3

> 设  $d = (d_1, d_2, \dots, d_n)$ 是一个序列, $d_1 \ge d_2 \ge \dots \ge d_n \ge 0$  且  $d_i$  均为整数,若记  $d' = (d_2 - 1, d_3 - 1, \dots, d_{d_1 + 1} - 1, d_{d_1 + 2}, \dots, d_n)$ ,则 d 是简单图的度序列,当且仅当 d'是简单图的度序列。

**证明**：

必要性 设 d 是简单图 G 的度序列,且  $d(v_i) \ge d_i$ ,可 有以下两种情况:

(i) 若  $v_1$  关联的边正好是  $v_1v_2$ ,  $v_1v_3$ , …,  $v_1v_{d_1+1}$ ,则 d'显然

就是简单图 $G-v_1$  的度序列。

(ii) 若  $v_1$  所关联的边中,有  $v_1v_j \notin \{v_1v_2, v_1v_3, \dots, v_1v_{d_1+1}\}$ , 即  $j>d_1+1$ ,令

$$j_0 = \max\{j \mid v_1 v_j \in E(G)\} > d_1 + 1$$

$i_0 = \min\{i \mid v_1 v_i \in E(G)\} \le d_1 + 1$

则有

$v_1v_{j_0} \in E(G)$ ,当且仅当 $j > j_0$ 时, $x_1v_j \in E(G)$

$v_1v_{i_0} \notin E(G)$ ,当且仅当  $i < i_0$  时, $v_1v_i \in E(G)$

如图 7-8 所示。

现考察与顶点  $v_{i_0}$ 相 邻接的  $d_{i_0}$ 个结点,其中 必有一个顶点  $v_k$  与  $v_{j_0}$  不相 邻接,否则 就会产生  $d_{j_0} \geqslant d_{i_0} + 1 > d_{i_0}$ 的矛盾。

作新图  $G' = G - \{v_1v_{i_0}, v_{i_0}, v_{k}\} + \{v_1v_{i_0}, v_{k}\}$

![](_page_38_Picture_9.jpeg)

$v_k v_{j_0}$ },即得图 7-9。于是,G'仍是简单图,且有与 G 相同的度序

![](_page_38_Picture_11.jpeg)

列,只是 G'的 j。减小了,i。增大了。这个过程重复地做下去,总可得到与(i)相同的情况。

充分性 设简单图 G' 的度序列为 d',设 G 中的结点是  $v_2$ ,  $v_3$ , ...,  $v_n$ 。如果在

G'中加进一个新的顶点  $v_1$ ,并连结边  $v_1v_2$ ,  $v_1v_3$ , …,  $v_1v_{d_1+1}$ ,则得到一个新的简单图 G,它的度序列正好是 d。

---
#### 7-4

> a)任何一个图的结点集合均可分成两部分  $V_1$  和  $V_2$ ,使得由  $V_1$  和  $V_2$  所生成的子图的度数是偶数。
> b) 对于任何一个图的结点均可分成  $V_1$  和  $V_2$ ,使得由  $V_1$  生成的子图的度数为偶数,由  $V_2$  生成的子图的度数为奇数。(这里,子图的度数是指子图中所有结点的度数之和。)

**证明**：

a) 我们可限制在简单图中进行讨论,因为除去两条平 行边并不改变我们的断言。

如果每一个结点的度数均为偶数,那么我们就取  $V_1 = V(G)$ ,  $V_2 = \emptyset$ 。

如果 a 是一个奇数度的结点,设 S 是它的邻接点的集合,现 g g g g g g g g g g

$$V(G_1)=V(G)-\{a\}$$

$$(x,y) \in E(G_1)$$
,当且仅当
$$\begin{cases} (x,y) \notin E(G), \text{ 若 } x,y \in S \\ (x,y) \in E(G), \text{ 其他情况} \end{cases}$$

对结点数进行归纳,我们可设 $V(G_1)=W_1\cup W_2$ ,且 $W_1$ 和 $W_2$ 生成 $G_1$ 的具有偶数度的子图。

因为  $|S \cap W_1| + |S \cap W_2| = |s| \equiv 1 \pmod{2}$  我们可假设 $|S \cap W_1|$  是偶数且 $|S \cap W_2|$ 是奇数,取

$$V_1 = W_1 \cup \{a\}, V_2 = W_2$$

对于  $x \in V_1$  ,若  $x \notin S$  ,那么很明显地在  $G[V_1]$ 中它的度数是 偶数;若  $x \in S$  ,那么

$$\begin{aligned} d_{G[V_1]}(x) &= d_{G_1[W_1]}(x) - d_{G_1[W_1 \cap S]}(x) + d_{G[W_1 \cap S]}(x) + 1 \\ &= d_{G_1[W_1]}(x) - d_{G_1[W_1 \cap S]}(x) \\ &+ (|W_1 \cap S| - 1 - d_{G_1[W_1 \cap S]}(x)) + 1 \\ &= d_{G_1[W_1]}(x) - 2d_{G_1[W_1 \cap S]}(x) + |W_1 \cap S| \end{aligned}$$

等式右边的每一项都是偶数,所以, $d_{G[V,]}(x)$ 为偶数。

同样地,可以证明:对于  $x \in V_2$ ,它在  $G[V_2]$ 中有偶数度。

b) 任意增加一个新的结点 v,得到新的结点集  $V(G) \cap \{v\}$ , 由此得到一个新的图  $G_1$ ,由 a)可知, $V(G_1)$ 可分成两部分  $U_1$  和  $U_2$ ,使得  $U_1$  和  $U_2$  所生成的  $G_1$  的子图的度数均为偶数。现不妨设  $v \in U_2$ ,那么,取  $V_1 = U_1$ , $V_2 = U_2 - \{v\}$  就是 V(G) 所要求的一种划分。

---
#### 7-5

> 画出图 7-10 相对于完全图的补图。 【7-1.(2)】

**解**：

图 7-10 相对于完全图的补图如图 7-11 所示。

![](_page_39_Figure_0.jpeg)

![](_page_39_Figure_1.jpeg)

---
#### 7-6

> 证明图 7-12 中两个图不同构。
> [7-1.(3)]
> ![](_page_39_Figure_4.jpeg)
> 图 7-12

**证明**：

如果这两个图同构,那么对应结点的度数应相同。度数为3的两个结点 $v_1$ 与 $v_1$ 相对应。但与 $v_1$ 邻接的三个结点中一个结点 $v_3$ 度数为2,两个结点 $v_5$ , $v_6$ 度数为1,而与 $v_1$ 邻接的三个结点中有两个结点 $v_2$ , $v_3$ 度数为2,一个结点 $v_6$ 度数为1,故他们不同构。

---
#### 7-7

> 证明图 7-13 中两个图是同构的。 【7-1.(4)】
> ![](_page_39_Figure_8.jpeg)
> ![](_page_39_Figure_9.jpeg)
> 图 7-13

**证明**：

根据点与边的关联关系,我们建立双射  $g: v_i \rightharpoonup u_i$  (1 $\leq i$

∠10),便可知这两个图同构。

---
#### 7-8

> 一个图如果同构于它的补图,则该图称为自补图。
> - a) 试给出一个五个结点的自补图;
> - b) 一个图是自补图,其对应的完全图的边数必为偶数;
> - c) 是否有三个结点或六个结点的自补图。

**解**：

a) 五个结点的图 G 与它的补图  $\overline{G}$  如图 7-14 所示。对 G 与 $\overline{G}$  建立双射: $v_1 \rightarrow v_1$ , $v_2 \rightarrow v_3$ , $v_3 \rightarrow v_5$ , $v_4 \rightarrow v_2$ , $v_5 \rightarrow v_4$ 。显然这 两个图保持相应点边之间对应的关联关系,故  $G \simeq \overline{G}$ 。因此,G 是 无个结点的自补图。

![](_page_39_Figure_18.jpeg)

![](_page_39_Figure_19.jpeg)

[7-1,(5)]

图 7-14

b) 设图 G 是自补图 G 有 e 条边 G 对应的完全图的边数为 A G 的补图 G 的边数应为 A G 的 G 的边数应为 G G G G G G G G G G
c) 由 b)可知,自补图对应的完全图的边数为偶数。n个结点的完全图 $K_n$ 的边数为 $\frac{1}{2}n(n-1)$ ,当 n=3 或 n=6 时, $K_n$ 的边数为奇数,因此不存在三个结点或六个结点的自补图。

---
#### 7-9

> 对于任何一个具有 6 个结点的简单图,要末它包含一个三角形,要末它的补图包含一个三角形。

**解**：

设6个结点的简单图为 G。考察 G 中的任意一个结点 a,那么,另外5个结点中的任何一个结点,要末在 G 中与 a 邻接,

要末在 $\overline{G}$ 中与a 邻接。这样,就可把 5 个结点分成两类,将那些在 $\overline{G}$ 中与a 邻接的结点归成一类,而将那些在 $\overline{G}$ 中与a 邻接的结

点归在另一类。于是必有一类至少含有三个结点,不妨假设其中的三个结点为b,c,d,如图 7-15 所示。该图必是  $\widetilde{G}$  的子图(这里  $\widetilde{G}$  或者是 G 或者是  $\overline{G}$ )。如果边(b,c),(c,b,d)中有一条在  $\widetilde{G}$  中,那么这条边所 关联的两个结点都与 a 邻接;如果边(b,c),

![](_page_40_Picture_2.jpeg)

图 7-15

(c,d),(b,d)都不在  $\widetilde{G}$  中,那么都一定在  $\widetilde{G}$  的补图(或者是 $\overline{G}$ 或者是G)中,因此,由这三条边组成的三角形就在  $\widetilde{G}$  中。

---
#### 7-10

> 画出所有具有 5 个结点 3 条边以及 5 个结点 7 条边的简单图。

**解**：

采用枚举法并从中选择的办法,显然是不适宜的。我们先考虑 5 个结点三条边的情况。因为简单图中每个结点的度数 总边数,所以在这种图中就不可能有度数大于 3 的结点。很清楚地可以知道,在仅有一个具有度数为 3 的结点的图中,各个结点的度数应当是 3,1,1,1,0;而结点度数不大于 2 的图中,各结点的度数只可能是 2,2,2,0,0;2,2,1,1,0 和 2,1,1,1,1。因此,结点数为 5,边数为 3 的简单图为图 7-16 所示。

![](_page_40_Picture_7.jpeg)

因为具有n个结点的简单图的边数与它的补图的边数之和等于具有n个结点的完全图的边数。n个结点的完全图的边数为n(n-1)/2,所以,5个结点的完全图的边数为 $5\times4/2=10$ 。显然,两个具有n个结点的图是同构的,当且仅当它们的补图是同构的。因此,5个结点7条边的简单图,就是上述4个简单图的补图,即

<sub>为图 7-17 所示。</sub>

![](_page_40_Picture_10.jpeg)

![](_page_40_Picture_11.jpeg)

![](_page_40_Picture_12.jpeg)

![](_page_40_Picture_13.jpeg)

图 7-17

---
#### 7-11

**证明**：

简单图的最大度小于结点数。
[7-1,(6)]
设简单图 G 有 n 个结点。对任一结点 u,由于 G 没有 f f f f f f f f f f
---
#### 7-12

> 在无向图 G 中,从结点 u 到结点 v 有一条长度为偶数 的通路,从结点 u 到结点 v 又有一条长度为奇数的通路,则在 G 中必有一条长度为奇数的回路。 【7-2.(1)】

**证明**：

设从结点 u 到结点 v 长度为偶数的通路是  $ue_1u_1e_2u_2$  …  $e_{2k}v$ ,长度为奇数的通路是  $ve_1'u_1'e_2'u_2'$  …  $e_{2h-1}v$ ,那么路  $ue_1u_1e_2u_2$  …  $e_{2k}ue_{2h-1}'$  …  $u_2'e_2'u_1'e_1'u$  就是一条回路,它的边数 = 2k+(2h-1) .= 2(h+k)-1,是奇数,故这条回路的长度是奇数。

---
#### 7-13

> 若无向图 G 中恰有两个奇数度的结点,则这两个结点 2间必有一条路。 【7-2.(2)】

**证明**：

设无向图 G 中两个奇数度结点为 u 和 v。

从 u 开始构造一条迹,即从 u 出发经关联于结点 u 的边  $e_1$  到达结点  $u_1$  ,若  $\deg(u_1)$  为偶数,则必可由  $u_1$  再经关联于结点  $u_1$  的  $u_2$  到达结点  $u_2$  ,如此继续下去,每边只取一次,直到另一个奇数 度结点停止,由于图 G 只有两个奇数度结点,故该结点或是 u 或是 v 。如果是 v ,那么从 u 到 v 的一条路就构造好了。如果仍是结点 u ,此路是闭迹。闭迹上每个结点都关联偶数条边,而  $\deg(u)$  为奇数,所以至少还有一条关联于结点 u 的边不在此闭迹上。继续 从 u 出发,沿着该边到达另一个结点  $u'_1$ ,依次下去直到另一个奇数度结点停下。这样经有限次后必可到达结点 v ,这就是一条从 u 到 v 的路,如图 v 7-18 所示。

![](_page_41_Figure_0.jpeg)

---
#### 7-14

> 若图 G 是不连通的,则 G 的补图  $\overline{G}$  是连通的。
> [7-2,(3)]

**证明**：

若图  $G = \langle V, E \rangle$  是不连通的,可设图 G 的连通分支是  $G(V_1), G(V_2), \cdots, G(V_m)$  ( $m \ge 2$ )。由于任意两个连通分支 $G(V_1)$ 与  $G(V_i)(i\neq j)$  之间不连通,因此两个结点子集  $V_i$  与  $V_i$  之间的 所有连线都在图 G 的补图  $\overline{G}$  中。任取两个结点 u 和 v,有两种 情形:

a) u 和 v 分别属于两个不同结点子集  $V_i$  与  $V_i$ 。由上可知  $\overline{G}$ 包含边(u,v),故u和v在 $\overline{G}$ 中是连诵的。
b) u 和 v 属于同一个结点子集  $V_i$ 。可在另一个结点子集  $V_i$ 中取一个结点 w, 由上可知边 (u,w) 及边 (v,w) 均在  $\overline{G}$  中, 故邻接 边(u,w)和(w,v)组成的路连接结点 u 和 v,即 u 和 v 在 $\overline{G}$  中也是 连通的。

由此可知,当图 G不是连通图时, $\overline{G}$  必是连通图。

---
#### 7-15

> 在一个旅行团中共有14人,在山上休息时,他们想打 桥牌,而其中每个人都曾仅与其中的5个人合作过。现规定只有 4个人中任两人都未合作过,才能在一起打一局牌。这样,打了三 局就没法再打下去了。这时,来了另一位旅游者,他当然没有与该 旅行团中的任何人合作过。如果他也参加打牌,证明一定可以再 打一局桥牌。

**解**：

画一个具有 14 个结点的简单图,如果每个结点代表旅行 团中的一个人,如果相应于 $v_i,v_i$ 的两个人未合作过,则连接一条 边 $(v_i, v_i)$ ,这样,对于每一个结点  $v_i$ ,就有  $\deg v_i = 8$ 。

每打过一局牌,就要去掉两条边,三局牌共要去掉6条边,即

使这6条边关联不同的12个结点,那么至少还有两个结点的度数 们为8。设这两个结点之一为 v,,那么与 v, 邻接的 8 个结点中至 少有一个结点的度数不小于 7,否则,如果这 8 个结点的度数均≤ 6,则由于每个结点至少去掉 2 条边,故至少共去掉  $\frac{8\times(8-6)}{2}=8$ 条边,这与仅去掉 6 条边相矛盾。设 V。是与 v。邻接且度数≥7 的结点,那么 v。必至少与上述 8 个结点中的其余 7 个结点之一邻

接,否则,  $\deg v_a \leq 13 - 7 = 6$  矛 盾。设 v, 是与 v。邻接的结点, 则 v<sub>a</sub>, v<sub>a</sub>, v<sub>r</sub> 组成一个三角形,这 表示相应的三个人是两两未合 作过的,这三个人与新来的旅游 者(相应的结点为 v)一定可以 再打一局牌。即  $v_{\nu}$ ,  $v_{\alpha}$ ,  $v_{r}$  和 v组成一个 $K_4$ ,如图 7-19 所示。

![](_page_41_Picture_12.jpeg)

---
#### 7-16

> 考察 2n 所电话局,如果每一所电话局至少可以与另  $M_n$  所电话局通话,那么,在这 2n 所电话局中的任何两所电话局 之间都可以通话(也可能要通过另外的电话局)。

**证明**：

设 2n 所电话局为 2n 个结点,能通话的电话局之间连 -条边,这样就得到一个简单图 G。由题意可知,每个结点的度数  $\geq n, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1, \mathbb{N} \leq 1,$ 通的。

用反证法:设 G 是不连通的,也就是说在这个图中包含着至 92个的连通分支。共有 2n 个结点,故必存在一个最多具有 n 个 结点的连通分支,其中的每一个结点 p 仅可与该连通分支中的结 点连接,又因为图 G 是简单图,而简单图中每个结点的度数 $\leq$ 结 点数减 1,所以  $deg(p) \leq n-1$ ,这就与每个结点的度数 $\geq n$  的假设 相矛盾。因此,图 G 仅有一个连通分支,即 G 是连通的。

---
#### 7-17

> 如果在 n 个电话局中的任何两个电话局总是可以通 话的,那么至少存在 n-1 条直通线路。

**解**：

设 n 个电话局为 n 个结点,两个结点之间有连线,当且仅 当对应的这两个电话局可直通电话。因为任何两个电话局总可以 通话(可能中途要通过其他电话局),因此就可构成一个简单的连 通图。

可以证明,对于具有n个结点的简单连通图G,至少存在n-1条边。用数学归纳法,有

当 n=2 时,有一条边;

当 n=3 时,至少有两条边;

设 n=k 时,G 至少有 k-1 条边。

当增加一个结点v时,v必与G中的某个结点邻接,因此,具有k+1个结点的简单连通图至少有k条边。

---
#### 7-18

> 每个结点的度数至少为2的图必包含一个回路。

**解**：

设 L 是图 G 中最长路中的一条,设其长度为 m,这条路的一个端点设为 a,考察 G 中与 a 关联的那些边,这些边中任何一条边的另一端必在 L 上,否则,将这个结点加进 L 中就可得到一条更长的路。

如果 G 中每个结点的度数至少为 2,那么 a 也要关联于一条不在 L 上的边 e。若 e 是环,则 e 本身就是回路,否则,边 e 的另一个端点 b(与 a 不同的点)在 L 上,而连通 L 中 a 到 b 的子路与边 e,就组成一个回路。如图 7-20 所示。

![](_page_42_Figure_9.jpeg)

---
#### 7-19

> 设 G 为具有 n 个结点的简单图,且|E| > (n-1)(n-2)/2,则 G 是连通的。

**证明**：

用反证法。若 G 不连通,不妨设 G 可分成两个不相连通的子图  $G_1$  和  $G_2$ ,并假设  $G_1$  和  $G_2$  中的顶点数分别为  $n_1$  和  $n_2$ ,显然, $n_1+n_2=n$ 。因为  $n_i \ge 1$ ,所以  $n_i \le n-1$  (i=1,2)。

$$|E| \leq \frac{n_1(n_1-1)}{2} + \frac{n_2(n_2-1)}{2} \leq \frac{(n-1)(n_1+n_2-2)}{2}$$

$$= \frac{(n-1)(n-2)}{2}$$

与假设相矛盾。因此, G是连通的。

---
#### 7-20

> 设一个图包含一条连通结点 a 和 b 的迹以及连通结点 b 和 c 的迹,证明 a 与 c 也能沿着一条迹而到达。

**证明**：

设 G 是附合题意的图,很明显,从 a 可以到达 c ,只要先沿着连通 a 和 b 的迹  $L_1$  到 b ,然后再沿着连通 b 和 c 的迹  $L_2$  而到达 c 。然而,这不一定是一条迹。如图 7-21 所示,有一条连通 a 和 c 的迹,即由边 (a,d) , (d,f) , (f,c) 所组成的迹。

![](_page_42_Picture_16.jpeg)

一般地,利用迹 $L_1$ 和 $L_2$ ,总可用以下

的方法得到一条从 a 到 c 的迹:从结点 a 开始,沿着  $L_1$  的边走,直到  $L_2$  的结点(这个点可以与 a 相重,因为结点 b 就是同时属于两条迹的,所以这种点总是存在的),从这个点再沿着  $L_2$  走一直到达结点 c。所得到的就是一条从 a 到 c 的迹。

当然,也可以从b出发,沿着 $L_2$ 的边走,在这个过程中所包含的那些属于 $L_1$ 中的点集记为S, $S \neq \emptyset$ (至少 $b \in S$ ),设p是沿 $L_2$ 的边走时属于S的最后一个结点(在图 7-21 中  $S = \{b,e,d,f\}$ ,p=f)。这样,我们如果从a开始,沿着 $L_1$ 的边走直到p点,然后从p沿着 $L_2$ 继续走直到c,这样同样可得到从a到c的一条迹。

---
#### 7-21

> 在图 G 中,若 $|E| \ge |V| + 4$ ,则 G 中包含两个圈(它们的边集不相交)。

**证明**：

如果能证明|E| = |V| + 4时,G中必包含两个圈(它

们的边集不相交),那么,|E|>|V|+4时,更是如此。因此,只要证明|E|=|V|+4的情况即可。

用反证法:设G是满足|E| = |V| + 4且不包含两个圈(它们的边集不相交)的图中结点数最少的一个图。那么,必有

(1) G中最短圈的长度 g≥5;
(2) G的最小度数δ(G)≥3。

这是因为

(1) 若  $g \leq 4$ ,则在 G 中除去一个长度 $\leq 4$  的圈  $C_1$  中的边所得的图  $G_1$ ,有  $|E(G_1)| \geq |E| 4 = |V(G)| = |V(G_1)|$ 。由此可知  $G_1$  中必有圈  $G_2$ ,且  $C_1$  与  $C_2$  中的边集是不相交的。这就与假设相矛盾。因此, $g \geq 5$ 。
(2) 当  $\deg(v_0) = 2$ 。如果是环则去除这个环,即去掉一个结点和一条边;如果不是环,不妨设  $v_0 v_1$ ,  $v_0 v_2 \in E(G)$ ,则去除  $v_0$ ,增加一条边( $v_1$ ,  $v_2$ )。

当  $\deg(v_0) \leq 1$ 。对于  $\deg(v_0) = 1$  的情况,则在 G 中除去  $v_0$  及其所关联的边;对于  $\deg(v_0) = 0$  的情况,则在 G 中除去  $v_0$  及任一条边。

无论是什么情况,都是去掉一个点和一条边,所得到图都记为 $G_1$ 。很明显,对于 $G_1$ 来说,仍然满足|E|=|V|+4且不包含两个圈(它们的边集不相交)。然而,这时却有 $V(G_1)=V(G)-1$ ,即 $G_1$ 的结点数比G的顶点数少,这就与原来G的假设相矛盾。因此,必有 $\delta(G) \ge 3$ 。

由(2)及
$$\sum_{v \in V} \deg(v) = 2|E|$$
,得  $2|E| \geqslant 3|V|$ ,所以
$$\frac{3|V|}{2} \leqslant |E| = |V| + 4, |V| \leqslant 8$$

由(1),在 G 中必有一个最短圈  $C_0$ ,且  $E(C_0) \geqslant 5$ 。记  $C_0$  上的结点集为  $V_0$ ,由(2)可知,对任一  $v \in V_0$ ,均有  $\deg(v) \geqslant 3$ ,因为  $C_0$  是最短圈,所以, $V_0$  中结点之间的联线均在  $C_0$  上,因此,对于任一  $v_1 \in V_0$ ,都必有  $v_1' \in V$  且  $v_1' \notin V_0$ ,使得  $v_1 v_1' \in E$ ,这样就有

$$V_{1} = \{v'_{1} \mid v_{1} v'_{1} \in E, v_{1} \in V_{0}, v'_{1} \notin V_{0}\}$$

对于任一 $v_1 \in V_1$ ,在 $V_0$  中仅有一个点与它相关联,否则,就将导致在G中存在长度<  $\left[\frac{g}{2}\right]$  +2<  $g(g \ge 5)$  的圈的矛盾。故有 $|V_0|$  <  $|V_1|$ ,因此,

$$|V| \ge |V_0| + |V_1| \ge 2|V_0| = 2g \ge 2 \times 5 = 10$$

既要 $|V| \le 8$ ,又要 $|V| \ge 10$ ,这是不可能的。

由此可见,反证法中的假设是不能成立的。因此,当|E|=|V|+4时,在G中必含有两个圈(它们的边集不相交)。

---
#### 7-22

> 当且仅当G的一条边e不包含在G的回路中时,e才EG的割边。

**证明**：

必要性 设 e 是连通图 G 的割边,e 关联的两个结点 Eu 和 v 。如果 e 包含在 G 的一个回路中,那么除边 e=(u,v)外 还有一条分别以 u 和 v 为端点的路,所以删去边 e 后,G 仍为连通 图,这与 e 是割边相矛盾。

充分性 如果边 e 不包含在 G 的任一回路中,那么连接结点 u 和 v 只有边 e ,而不会有其他连接 u 和 v 的任何路。因为如果连接 u 和 v 还有不同与边 e 的路,此路与边 e 就组成一条包含边 e 的回路,从而导致矛盾。所以删去边 e 后,u 和 v 就不连通,故边 e 是割边。

---
#### 7-23

> 若 G 是一个简单图,且  $\delta(G) \geqslant |V| - 2$ ,则  $k(G) = \delta(G)$ 。

**证明**：

因为G是简单图,所以每个顶点的度数最多为|V| -1,现 $\delta(G) \geqslant |V|$  -2,所以只要讨论以下两种情况即可。

(1) 若
$$\delta(G) = |V| - 1$$
,则 $G = K_{|v|}$ ,因此
$$k(G) = |V| - 1 = \delta(G)$$

(2) 若  $\delta(G) = |V| - 2$ ,则必有两个结点不相邻接,设  $v_1$ , $v_2 \in V$  且  $v_1$  与  $v_2$  不相邻接。于是,对于任意的  $v_3 \in V$ ,都有  $v_1 v_3$ , $v_2 v_3 \in E$ 。因此,对于 V 中任意的 |V| - 3 个结点的集合  $V_1$ , $G - V_1$  一定是连通的,故必有  $k(G) \geqslant |V| - 2 = \delta(G)$ 。而由定理 7-2.2 知  $k(G) \leqslant \delta(G)$ ,所以  $k(G) = \delta(G)$ 。

---
#### 7-24

> 设 T 是一棵根树且不考虑方向,它的结点集合为V=
> ![](_page_44_Figure_1.jpeg)
> $\{x_1, x_2, \dots, x_n\}$ ,且  $d_{ij} = d(x_i, x_j)$ 表示  $x_i$  与  $x_j$  之间的距离(即  $x_i$  与  $x_j$  之间通路的长度),作矩阵  $D = (d_{ij})$ ,试证明  $\det D = -(n-1)(-2)^{n-2}$ 。

**证明**：

设  $x_1$  是树 T 的根,由于从  $x_1$  到任何一点  $x_i$  的通路是唯一的,所以  $d(x_i,x_j) = d(x_i,x_1) + d(x_j,x_1) -2d(x_i \wedge x_j,x_1)$

其中, $x_i \land x_i$  表示  $x_i$  和  $x_i$  的共同父亲。如图 7-22 所示。

在集合  $V = \{x_1, x_2, \dots, x_n\}$  上定义偏序关系  $\leq x_i \leq x_j$  当且仅 当从  $x_i$  到  $x_j$  有唯一的通路且  $x_i$  是  $x_j$  的祖先。对结点按长辈在 前的原则排一个序,现定义  $Z = (z_{ii})$ ,其中

$$z_{ij} = \begin{cases} 1, x_i \leqslant x_j \\ 0,$$
其他  $\end{cases}$
$A = \begin{pmatrix} 0 & 1 & 1 & \cdots & 1 \\ 1 & -2 & 0 & 0 \\ 1 & & -2 & 0 \\ \vdots & 0 & & \ddots & 0 \\ 1 & & & & -2 \end{pmatrix}$

再定义

记  $C = Z^T A Z$ 。

$$C_{ij} = \sum_{k=1}^{n} z_{k_i} \left( \sum_{l=1}^{n} a_{k_l} z_{l_j} \right) = \sum_{x_k \le x_i, x_j \le x_i} a_{kl}$$

因为除去  $a_{11}$ 外只有当 k=l 或 k=1 或 l=1 时  $a_{kl}\neq 0$ ,所以

$$C_{ij} = \sum_{x_k} 1 + \sum_{x_i} 1 + \sum_{x_k \leq x_i \atop \exists x_i \leq x_j} (-2)$$

$$= [d(x_i, x_1) + 1] + [d(x_j, x_1) + 1]$$

$$-2[d(x_i \land x_j, x_1) + 1]$$

$$= d(x_i, x_1) + d(x_j, x_1) - 2d(x_i \land x_j, x_1)$$

$$= d_{ii}$$

因此, $Z^TAZ=D$ ,

$\det D = \det Z^{T} A Z = \det A = -(n-1)(-2)^{n-2}$

---
#### 7-25

> 分析图 7-23,求:
> - a) 从A到F的所有通路;
> - b) 从A到F的所有迹;
> - c) A和F之间的距离;
> - d) k(G), $\lambda(G)$ 和  $\delta(G)$ 。
> ![](_page_44_Figure_19.jpeg)
> 图 7-23
> [7-2.(5)]

**解**：

a) 从A到F的通路有七条: ABCF,ABCEF,ABEF,ABECF

ADEF, ADECF, ADEBCF

b) 从 A 到 F 的迹有八条:

$Ae_1Be_2Ce_3F$ ,  $Ae_1Be_2Ce_6Ee_8F$ ,  $Ae_1Be_5Ee_6Ce_3F$

Ae1Be5Ee8F, Ae4De7Ee8F, Ae4De7Ee6Ce3F

Ae4 De7 Ee5 Be2 Ce3 F, Ae4 De7 Ee5 Be2 Ce6 Ee8 F

c) d(A,F) = 3.
d)  $k(G) = \lambda(G) = \delta(G) = 2$

---
#### 7-26

> 令 G 是一个至少有三个结点的连通图,证明下列命题 是等价的。
> - a) G 没有桥。
> - b) G的每二个结点在一条公共的闭迹上。
> - c) G的每一个结点和一条边在一条公共的闭迹上。
> - d) G的每二条边在一条公共的闭迹上。
> - e) 对G的每一对结点和每一条边,有一条联结这两个结点 而且含有这条边的迹。
> - f) 对 G 的每一对结点和每一条边,有一条联结这两个结点而不含有这条边的通路。
> - g) 对每三个结点,有一条联结任何两个结点而且含第三个结点的迹。 【7-2.(6)】

**证明**：

$a) \Rightarrow b$ ):设 G 是至少有三个结点的连通图,且 G 无桥。令u,v为G 中任意两个结点,下面对 u,v间的距离 d(u,v)

作归纳:

① 当 d(u,v)=1。因为 G 无桥,故在 G 中必有一条回路包含 e=(u,v), 这是因为若 e 不包含在任何回路中, 则 e 必是桥, 与题 设矛盾、所以当 d(u,v)=1 时,u,v 必在同一条公共闭迹上。

② 假设当 d(u, v) < k 时命题成立, $k \ge 2$ 。考察一条长为 k的 u-v 的一条通路,设 w 是这条路上结点 v 前面的那个结点, d(u,w)=k-1,由归纳假设 u,w 两个结点必在 G 的某一条闭迹  $P_1$ ,该闭迹由  $P_2$ ,  $P_2$  组成(如图 7-24 所示),因为  $P_3$  无桥,所以 G-(v,w)=G'必仍连通,因此 u-v 之间必有一条不包含(v,w)的迹 P'。 P'与  $P_1$ ,  $P_2$  间的关系有图 7-24(a), (b), (c) 的三种情 况。设 $x \neq P'$ 上与v最近且在 $P_1$ 或 $P_2$ 上的交点,不妨设x在  $P_1$ 上(图 7-24(a))。则以  $P_1$ 上的 u-x 段,续以 P'上的 x-v 段 为 $\theta_1$ ,以 $P_2$ 上u—w 段续以边(w,v)为 $\theta_2$ ,则 $\theta_1$   $\cup \theta_2$  就是G中通 过u,v的一条公共闭迹。其他两种情况(图 7-24(b),(c)),证法 相同。

所以 a)⇒b)成立。

b) $\Rightarrow$ c):设 u 为 G 中任意一点,e 为 G 中任意一条边,令 e= (v,w), 由 b)可知 u,v 有公共闭迹 Z。若  $w \in Z$ ,则  $e \in Z$ ,c)成立。

若  $w \notin Z$ , 设  $P_1$ ,  $P_2$  为两条不同的 u = v 的迹, 设 v, w 所在的 闭迹为Z'。令 $P'=Z'-\{e\}$ 为v-w不含e的迹。(图 7-24(d))令 u'是P'上与 $P_1$  或 $P_2$ 上的最后一个交点,不妨设u'在 $P_1$ 上,则以  $P_1$ 上的 u-u' 段续以 P'上的 u'-w 为  $Q_1$ ; 以  $P_2$  续以 e=(v,w)为  $Q_2$ ,则有  $Q_1 \cup Q_2$  组成的闭迹,包含 u 和 e。所以 c)成文。

当 u'=v 时,证明相同。

c) $\Rightarrow$ d): 设  $e_1$ ,  $e_2$  为 G 中任意两条边,  $e_1 = (u_1, v_1), e_2 =$  $(u_2,v_2)$ 。由 c)可知  $u_1$  和  $e_2$  在公共闭迹 Z 上,若  $v_1 \in Z$ ,则  $e_1 \in$ Z,故 d)成立。若  $v_1 \notin Z$ ,由 c)可知  $v_1$  和  $e_2$  也在一公共闭迹 Z'上。Z与Z'有图 7-24(e),(f),(g),(h),(i)各种情况。

设 $P_1$ 为Z上 $u_1-v_2$ 上的一段迹(不含 $u_2$ ), $P_2$ 为Z上 $u_1-u_2$

![](_page_45_Picture_9.jpeg)

图 7-24

上的一段迹(不含  $v_2$ ), P'为 Z'上  $v_1-v_2$  的一段迹(不含  $u_2$ )。再 设u'为P'上与 $P_1$ 或 $P_2$ 的最先一个交点(如图 7-24(f)所示). 则以P'的 $v_1 - u'$ 段续以 $P_1$ 的 $u' - v_2$ 为 $Q_1$ ,以 $e_1$ 续以 $P_2$ ,再续以  $e_2$  为  $Q_2$  ,则  $Q_1 \cup Q_2$  组成包含  $e_1e_2$  的公共闭迹。其余情况证法相同。

所以 c)⇒d)成立。

d)⇒e):设u,v为G中任意两点,e为G的任意一条边,若u,v邻接,则由 d)必有一条公共闭迹包含结点u,v和边e。

若 u,v 不邻接,由 G 连通,对结点 u 必有邻接边 e'=(u,s)。 故 e,e'必在同一闭迹上,设该闭迹为 Z。

① 若  $v \in Z$ ,则命题成立。
② 若  $v \notin Z$ ,因为 G 连通,故 v 与 Z 中每个结点至少有一条路,故也有一条迹。

设 w 是 Z 上离 v 最近的点,P 为 v-w 的最短的迹,以 Z 中含有 e 的 u-w 的迹,续以 P 即构成 u 到 v 含有 e 的迹。(见图 7-24(j))

当 w=u 时,情况类同。(见图 7-24(k))

故 d)⇒e)成立。

$e)\Rightarrow g):$ 设u,v,w为G中任意三点,因为G连通,故G中必有关联w的边e,由题设,u,v,e在一条迹上,即有一条以u,v为端点,且包含e的迹,即g)成立。

g)⇒a):用反证法。

若G中至少有一个桥,设为e,则G— $\{e\}$ 为不连通图,又G是至少三个结点的连通图,故在G中删除一边后,至少有一个连通分支含有两个或两个以上的结点。因为若不然G— $\{e\}$ 中至少有三个以上孤立结点,则加上任何一条边G不可能为连通图,与题设矛盾。

设u,v为 $G-\{e\}$ 的同一连通分支中的两个结点,令w为不属于该连通分支的G的另一个结点,因为 $G-\{e\}$ 为不连通图,故w必存在这样G中必不能存在一条u到v的且含有w的迹。因为若这样的迹存在,则删除这条迹上的任一边,w仍与u或v中至少存在一条w,故w属于u,v所在连通分支中,与假设矛盾。

所以 g)→a)成立。

a)⇒f):用反证法。

设 G 为至少三个结点的连通图,且 G 无桥。若 u,v 为 G 中任 意两个结点,且 G 中所有 u,v 之间的通路均含有某条边 e,则 G G G G G G G G G G

$f)\Rightarrow a)$ : 如果 G 中任意一对结点和每一条边,有一条联结这两个结点而不含有这条边的通路。G 为具有至少三个结点的连通图。

设 G 中有一桥 e ,则 G— $\{e\}$ 为不连通图,令  $G_1$  , $G_2$  为 G— $\{e\}$  中的两个不同连通分支, $G_1$  和  $G_2$  非空,设 u  $\in$   $G_1$  ,v  $\in$   $G_2$  ,在 G 中 因连通故 u—v 的任一条路上均含有边 e ,与题设矛盾。所以 G 中 不能有桥。

故 f)⇔a)成立。

综上各点,a),b),c),d),e),f),g)为等价命题。

---
#### 7-27

> 在图 7-25 中给出了一个有 向图,试求  $d\langle v_1, v_4 \rangle$ ,  $d\langle v_2, v_5 \rangle$  及  $d\langle v_3, v_5 \rangle$ 。此有向图对应的关系是否可传递? 如果不是可传递的,试求此图的传递  $v_2$  闭包。 【7-2.(7】
> ![](_page_46_Figure_21.jpeg)

**解**：

$$d\langle v_1, v_4\rangle = 3$$

$$d\langle v_2, v_5\rangle = 3$$

$$d\langle v_3, v_6\rangle = 3$$

此有向图对应的关系为:

$$R = \{\langle v_1, v_2 \rangle, \langle v_2, v_3 \rangle, \langle v_3, v_1 \rangle, \langle v_3, v_4 \rangle,$$

$\langle v_4, v_5 \rangle, \langle v_5, v_6 \rangle\}$

因为 $\langle v_1, v_2 \rangle \in R$ ,  $\langle v_2, v_3 \rangle \in R$  而 $\langle v_1, v_3 \rangle \notin R$ , 所以 R 不是可传递的。

关系 R 的传递闭包为:

$$f(R) = \{\langle v_1, v_1 \rangle, \langle v_1, v_2 \rangle, \langle v_1, v_3 \rangle, \langle v_1, v_4 \rangle, \ \langle v_1, v_5 \rangle, \langle v_1, v_6 \rangle, \langle v_2, v_1 \rangle, \langle v_2, v_2 \rangle, \ \langle v_2, v_3 \rangle, \langle v_2, v_4 \rangle, \langle v_2, v_5 \rangle, \langle v_2, v_6 \rangle, \ \langle v_3, v_1 \rangle, \langle v_3, v_2 \rangle, \langle v_3, v_3 \rangle, \langle v_3, v_4 \rangle, \ \langle v_3, v_5 \rangle, \langle v_3, v_6 \rangle, \langle v_4, v_5 \rangle, \langle v_4, v_6 \rangle, \ \langle v_5, v_6 \rangle \}$$

---
#### 7-28 试求图 7-25 中的有向图的强分图、单侧分图和弱分图。 【7-2.(8)】

该有向图所对应的强分图、单侧分图和弱分图分别如图 7-26(a)、(b)和(c)所示。

![](_page_47_Figure_3.jpeg)

![](_page_47_Figure_4.jpeg)

---
#### 7-29

> a) 证明:如果 G 是简单图,|V|=v,且  $\delta(G)\geqslant \frac{v}{2}$ ,则  $\lambda(G)=\delta(G)$ 。
> b) 找一个
> $$\delta(G) = \left[\frac{v}{2} - 1\right]$$
> ,且  $\lambda(G) < \delta(G)$  的简单图  $G$ 。

**解**：

a) 如图 7-27 所示,按 $\lambda(G)$ 的定义,存在 $\lambda$ 条边,除去这 $\lambda$ 条边后,就把 G 分成两个连通分支。不失一般性,假定

![](_page_47_Picture_8.jpeg)

$|V(G_1)|=l \leq \frac{v}{2}$ ,故有  $\delta \geq \frac{v}{2} \geq l$ ,于是  $\delta(l-1) \geq l(l-1)$ ,即[ $\delta-(l-1)$ ]· $l \geq \delta$ 。另一方面, $G_1$  中每个结点的度数 $\geq \delta$ ,而  $G_1$  的结点数为 l,至少有  $\delta-(l-1)$ 条边要伸向  $G_2$ ,故  $\lambda(G) \geq [\delta-(l-1)]$ · $l \geq \delta$ 。然而,由定理 7-2.2 可知  $\lambda \leq \delta$ ,因此,便得  $\lambda(G) = \delta(G)$ 。

b) 在  $K[\frac{v-1}{2}]$  上取一点 u,在  $K[\frac{v-1}{2}]$  上取一点 v,连结 u,v 得的边记为 e,这样所得的图记为 G,即

$$G = (K_{\lceil \frac{v+1}{2} \rceil} \cup K_{\lceil \frac{v-1}{2} \rceil}) + uv$$

其中 $u \in V(K_{\lceil \frac{v+1}{2} \rceil})$ , $v \in V(K_{\lceil \frac{v-1}{2} \rceil})$ 。

显然,e=(u,v)是 G 的一条割边,所以  $\lambda(G)=1$ 。

在  $v \ge 7$  的条件下, $\delta(G) = \delta\left(K_{\left[\frac{v-1}{2}\right]}\right) = \left[\frac{v-1}{2}\right] - 1 > 1 =$   $\lambda(G)$ ,所以,G 就是满足  $\lambda(G) < \delta(G)$  的简单图。

---
#### 7-30

> 一个有向图 *D* 是单侧连通的,当且仅当它有一条经过 每一结点的路。

**证明**：

充分性

给定有向图  $G=\langle V,E\rangle$ ,如果 G 有一条经过每一结点的路为  $v_1e_1v_2e_2\cdots v_{n-1}e_{n-1}v_n$ ,这里  $V=\{v_1,v_2,\cdots,v_n\}$ , $\{e_1,e_2,\cdots,e_{n-1}\}\subseteq E$ ,边  $e_i(1\leqslant i\leqslant n-1)$ 以结点  $v_i$  为起点,以  $v_{i+1}$  为终点。任给两个结点  $v_i$ , $v_m\in V$ ,不妨设  $l\leqslant m$ ,则  $v_le_lv_{l+1}e_{l+1}\cdots e_{m-1}v_m$  就是从结点  $v_l$ 出发到达结点  $v_m$  的路,故 G 是单侧连通的。

必要性

对结点数目 v 进行归纳。

当 v=1, v=2 时,单侧连通的图显然有一条经过该图中所有结点的路。

设 v=k 时,有一条经过每一结点的路  $v_1v_2\cdots v_p$ ,其中结点可能有重复,这条路的结点的下标只表示该路所经过结点的次序,显然  $k \le p$ 。例如图 7-28(a)给出的路  $u_1u_2u_3u_4u_5u_2u_3u_6u_7$ ,故  $v_1=u_1$ ,  $v_2=u_2$ ,  $v_3=u_3$ ,  $v_4=u_4$ ,  $v_5=u_5$ ,  $v_6=u_2$ ,  $v_7=u_3$ ,  $v_8=u_6$ ,  $v_9=u_7$ .

![](_page_48_Picture_3.jpeg)

当 v=k+1 时,取一结点 u,在图 G 中删去 u,使  $G-\{u\}$ 还是单侧连通图。根据归纳假设, $G-\{u\}$ 有一条经过每一个结点的路  $v_1v_2\cdots v_p$ 。令  $i=\max\{s|v_s$  到 u 有路}, $j=\min\{s|u$  到  $v_s$  有路}。假如 j>i+1,则必有 t 满足 i< t< j。由于图 G 是单侧连通的, $v_t$  与 u 之间有路。如果该路是从  $v_t$  到 u,则与  $i=\max\{s|v_s$  到 u 有路}矛盾。如果该路是从 u 到  $v_t$ ,则与  $j=\min\{s|u$  到  $v_s$  有路}矛盾。故而 j>i+1 不可能,只可能是  $j\leqslant i+1$ 。当 j=i+1 时,有经过每一结点的路  $v_1v_2\cdots v_i\cdots u\cdots v_{i+1}v_{i+2}\cdots v_p$ ,如图 7-28(b)所示。当  $j\leqslant i$  时,有经过每一结点的路  $v_1v_2\cdots v_j\cdots v_i\cdots u\cdots v_j\cdots v_jv_{i+1}\cdots v_p$ ,

如图 7-28(c)所示。

---
#### 7-31

> 试证明图的每一个结点和每一条边,都只包含于一个 弱分图中。

**证明**：

设结点 u 包含于两个不同的弱分图  $G_1 = \langle V_1, E_1 \rangle$ 和  $G_2 = \langle V_2, E_2 \rangle$ 中,即  $u \in V_1 \cap V_2$ 。由于略去边的方向后, $V_1$  中所有结点与 u 连通, $V_2$  中所有结点也与 u 连通,故  $V_1$  与  $V_2$  中所有结点连通,这与  $G_1$  为弱分图矛盾,故任一结点不可能包含于两个不同的弱分图中。

如果一条边包含于两个不同的弱分图中,该边所关联的两个 结点也包含于两个不同的弱分图中,这是不可能的,因此任一条边 也只能包含于一个弱分图中。

---
#### 7-32

> 求出图 7-29 中有向图的邻接矩阵 A,找出从  $v_1$  到  $v_4$  长度为 2 和 4 的路,用 计算  $A^2$ ,  $A^3$  和  $A^4$  来验证这结论。
> [7-3.(1)]

**解**：

$v_1$  到  $v_4$  长度为 2 的路有 1 条:  $v_1v_2v_4$ ;长度为 4 的路有 3 条:  $v_1v_2v_3v_2v_4$ ,  $v_1v_2v_4v_2v_4$  和  $v_1v_4v_3v_2v_4$ 。

$v_2$   $v_3$

图 7-29

$$A = \begin{pmatrix} 0 & 1 & 0 & 1 \\ 0 & 0 & 1 & 1 \\ 0 & 1 & 0 & 0 \\ 0 & 1 & 1 & 0 \end{pmatrix}, A^{2} = \begin{pmatrix} 0 & 1 & 2 & 1 \\ 0 & 2 & 1 & 0 \\ 0 & 0 & 1 & 1 \\ 0 & 1 & 1 & 1 \end{pmatrix}$$
$$A^{3} = \begin{pmatrix} 0 & 3 & 2 & 1 \\ 0 & 1 & 2 & 2 \\ 0 & 2 & 1 & 0 \\ 0 & 2 & 2 & 1 \end{pmatrix}, A^{4} = \begin{pmatrix} 0 & 3 & 4 & 3 \\ 0 & 4 & 3 & 1 \\ 0 & 1 & 2 & 2 \\ 0 & 3 & 3 & 2 \end{pmatrix}$$

---
#### 7-33

> 对于邻接矩阵 A 的简单有向图 G,它的距离矩阵定义 如下:
> $d_{ij} = \infty$ ,如果  $d\langle v_i, v_j \rangle = \infty$ ,  $d_{ij} = 0$ ,对所有的  $i = 1, 2, \dots, n$ ,  $d_{ii} = k$ ,这里 k 是使  $a_{ii}^{(k)} \neq 0$  的最小正整数。
> 确定由图 7-29 所示的有向图的距离矩阵,并指出  $d_{ij}=1$  是什么意义? 【7-3.(2)】

**解**：

距离矩阵 D(G)为:

$$D(G) = \begin{pmatrix} 0 & 1 & 2 & 1 \\ \infty & 0 & 1 & 1 \\ \infty & 1 & 0 & 1 \\ \infty & 1 & 2 & 0 \end{pmatrix}$$

$d_{ij}=1$ 表示存在边 $\langle v_i, v_j \rangle$ ,反之亦然。

---
#### 7-34

> 在图 7-30 中给出了一个有向图,试求该图的邻接矩阵,并求出可达性矩阵和距离矩阵。 【7-3.(3)】
> ![](_page_49_Picture_6.jpeg)

**解**：

邻接矩阵 A(G),可达性矩阵 P(G) 和距离矩阵 D(G)分别如下:

图 7-30

$$A(G) = \begin{pmatrix} 0 & 0 & 0 & 0 & 0 \\ 1 & 0 & 1 & 1 & 0 \\ 1 & 0 & 0 & 0 & 0 \\ 0 & 0 & 1 & 0 & 0 \\ 0 & 0 & 0 & 0 & 0 \end{pmatrix}, P(G) = \begin{pmatrix} 0 & 0 & 0 & 0 & 0 \\ 1 & 0 & 1 & 1 & 0 \\ 1 & 0 & 0 & 0 & 0 \\ 1 & 0 & 1 & 0 & 0 \\ 0 & 0 & 0 & 0 & 0 \end{pmatrix}$$

$$D(G) = \begin{pmatrix} 0 & \infty & \infty & \infty & \infty \\ 1 & 0 & 1 & 1 & \infty \\ 1 & \infty & 0 & \infty & \infty \\ 2 & \infty & 1 & 0 & \infty \\ \infty & \infty & \infty & \infty & 0 \end{pmatrix}$$

![](_page_49_Picture_11.jpeg)

![](_page_49_Picture_12.jpeg)

![](_page_49_Picture_13.jpeg)

图 7-31

$M(G): \begin{array}{|c|c|c|c|c|c|c|c|c|c|c|c|c|c|c|c|c|c|c$

由于

可见 M(G)的秩为 5。

原图是一个连通图,所以 M(G) 的秩等于结点数减 1,即 rank M(G)=6-1=5。

---
#### 7-36

**证明**：

设图 G 有 n 个结点,r 个最大连通子图,则图 G
---

## 第八章 形式语言与自动机

#### 8-1

> 设  $V = \{a,b,c\}$ ,求  $V^2$ , $V^3$ 。 [8-1.1]

**解**：

$V = \{a,b,c\}$

$V^2 = \{aa, ab, ac, ba, bb, bc, ca, cb, cc\}$

$V^3 = \{aaa, aab, aac, aba, abb, abc, aca, acb, acc, baa, bab, bac, bba, bbb, bbc, bca, bcb, bcc caa, cab, cac, cba, cbb, cbc, cca, ccb, ccc\}$

---
#### 8-2

> 设  $V = \{0,1\}$ ,试问二进制的 5 和 14 在什么集合中?

**解**：

因为V中每一元素长度为1, $V^2$  中每个元素长度为2,一般  $V^k$  中每个元素长度为k。5 的二进制为101,14 的二进制为1110。如果在二进制数前面不能添加0,则|101|=3,|1110|=4, 故而 $101 \in V^3$ , $1110 \in V^4$ 。

---
#### 8-3

> 给出有限字母表
> $$V, \bar{x} | V^k |$$
> 。 【8-1.2】

**解**：

因为  $V^k = \underbrace{V \times V \times \cdots \times V}_{k}$ ,  $V^k$  是字母表 V 上所有长度为

k 的串组成的集合,如果 V 有 n 个字母, |V| = n,则  $|V^k| = |V|^k$   $= n^k$ 。

---
#### 8-4

> 已知  $V = \{a,b\}$ 上语言  $L_1 = \{\lambda, ba, aba\}, L_2 = \{ba, bb\}$ 。 求  $L_1 \cup L_2, L_1 \cap L_2, L_1 \circ L_2, L_2^3, L_1'$ 。

**解**：

$$L_1 \cup L_2 = \{\lambda, ba, bb, aba\}$$

$$L_1 \cap L_2 = \{ba\}$$

$L_1 \circ L_2 = \{ba, bb, baba, babb, ababa, ababb\}$

$L_2^2 = \{baba, babb, bbba, bbbb\}$

$L_2^3 = \{bababa, bababb, babbba, babbbb, babbbb, babbbba, babbbb, babbba, babbbb, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbbba, babbba, babbba, babbba, babbba, babbba, babbba, babbba, babbba, babbba, babbba, babbba, babbba, babbba, babbba, babbba, babbba, babbba, babbba, babbba, babbba, babbba, babbba, babbba, babbba, babbba, babbba, babbba, b$

bbbaba, bbbabb, bbbbba, bbbbbb

$$L_1' = \{\lambda, ab, aba\}$$

---
#### 8-5 举一例子说明字母表 V 上语言  $L_1$ ,  $L_2$ ,  $L_3$  不等式成立:

$$(L_1 \cap L_2)L_3 \neq L_1L_3 \cap L_2L_3$$

如果V是由单字母组成,这种成立不等号的语言 $L_1$ , $L_2$ , $L_3$  找得到吗?

令
$$V = \{0,1\}, L_1 = \{0,11\}$$

$L_2 = \{01,11\}, L_3 = \{0,10\}$

那么

$$L_{1} \cap L_{2} = \{11\}, (L_{1} \cap L_{2})L_{3} = \{110,1110\}$$

$$L_{1}L_{3} = \{00,010,110,1110\}$$

$$L_{2}L_{3} = \{010,0110,110,1110\}$$

$$L_{1}L_{3} \cap L_{2}L_{3} = \{010,110,1110\}$$

$$(L_{1} \cap L_{2})L_{3} \subset L_{1}L_{3} \cap L_{2}L_{3}$$

故

由定理 8-1.3 可知,

$$(L_1 \cap L_2)L_3 \subseteq L_1L_3 \cap L_2L_3$$

要求等号不成立,即找一个串 $\omega,\omega\in L_1L_3\cap L_2L_3$ ,但 $\omega\notin(L_1\cap L_2)$  $L_3$ 。因为V仅含一个字母,设 $V=\{a\},\omega=\underbrace{aa\cdots a}_k(k\geqslant 1),\omega\in L_1L_3$ ,即有

同理
$$\omega = \underbrace{a \cdots a a \cdots a}_{i_1}, i_1 + j_1 = k', \underbrace{a \cdots a}_{i_1} \in L_1, \underbrace{a \cdots a}_{j_1} \in L$$
同理  $\omega \in L_2L_3$ ,  $\omega = \underbrace{a \cdots a a \cdots a}_{i_2}, i_2 + j_2 = k$   $\underbrace{a \cdots a}_{i_2} \in L_2, \underbrace{a \cdots a}_{j_2} \in L_3$

因为  $\omega \notin (L_1 \cap L_2)L_3$ ,故只要  $i_1 \neq i_2$  且  $L_1 = \{\underbrace{a \cdots a}_{i_1}\}$ ,  $L_2 = \{\underbrace{a \cdots a}_{i_1}\}$

$\{\underline{a}$   $\dots a\}$  就可以了。由此可知,当 V 只有一个字母时,仍有可能成立

$(L_1 \cap L_2)L_3 \neq L_1L_3 \cap L_2L_3$

例如  $L_1 = \{a\}, L_2 = \{aa\}, L_3 = \{a,aa\}$

$$(L_{1} \cap L_{2})L_{3} = \emptyset, L_{1}L_{3} \cap L_{2}L_{3} = \{aaa\}$$

$$(L_{1} \cap L_{2})L_{2} \neq L_{1}L_{3} \cap L_{2}L_{3}$$

---
#### 8-6

> 简化下列式子
> a)  $\Lambda \emptyset^*$ ;
> 则
> - b) Λ<sup>\*</sup>Ø\*;
> - c) A\* UØ\*;
> - d)  $(\emptyset \cup A)^*$ ;
> - e)  $(\Lambda \cup A)^*$ .
> [8-1.(4)]
> $\mathbf{M}$  a)  $\Lambda \varnothing^* = \Lambda(\Lambda \cup \varnothing \cup \varnothing^2 \cup \cdots) = \Lambda \Lambda = \Lambda$ .
> - b)  $\Lambda^* \varnothing^* = \Lambda^* \Lambda = (\Lambda \bigcup \Lambda \bigcup \Lambda^2 \bigcup \cdots) \Lambda = \Lambda \Lambda = \Lambda$ .
> - c)  $A^* \cup \emptyset^* = A^* \cup \bigwedge = A^*$
> - d)  $(\emptyset \bigcup A)^* = A^*$ .
> - e)  $(\Lambda \bigcup A)^* = (\Lambda^* A^*)^* = (\Lambda A^*)^* = (A^*)^* = A^*$
---
#### 8-7

> 设V是字母表,L是V上的一个语言。定义 $V^*$ 上的一个关系 $\sim$ ; $\alpha \sim \beta$  当且仅当对所有 $\omega$ , $\omega \in V^*$ ,有
> $$(\omega \alpha \varphi \in L) \Leftrightarrow (\omega \beta \varphi \in L)$$
> ,
> 证明~是一个等价关系。
> [8-1.(5)]

**证明**：

自反:对 V 上任一串  $\alpha$  ,显然有  $\alpha \sim \alpha$  。

对称:设V上串 $\alpha$ , $\beta$ 有 $\alpha$  $\sim$  $\beta$ 。由定义可知,对任意 $\omega$ , $\varphi$  $\in$ V\*,

$$(\omega \alpha \varphi \in L) \Leftrightarrow (\omega \beta \varphi \in L)$$

即  $ωαφ \in L$  与  $ωβφ \in L$  同真假,因此, $β \sim α$ .

传递: 设V上串 $\alpha$ ,  $\beta$ 和 $\gamma$ 有 $\alpha$  $\sim$  $\beta$ ,  $\beta$  $\sim$  $\gamma$ , 即对任意串 $\omega$  和 $\varphi$ ,  $\omega \alpha \varphi \in L$  与  $\omega \beta \varphi \in L$  同真假,  $\omega \beta \varphi \in L$  与  $\omega \gamma \varphi \in L$  同真假, 故而  $\omega \alpha \varphi \in L$  与  $\omega \gamma \varphi \in L$  同真假,  $\alpha \sim \gamma$ .

综上所述,~是等价关系。

---
#### 8-8

> 设A,B,C和D是V上任意语言,那么有
> - a)  $A\Lambda = \Lambda A = A$ ;
> - b)  $(B \cup C)A = BA \cup CA$ ;
> - c)  $A(B \cap C) \subseteq AB \cap AC$ ;
> - d)  $(B \cap C)A \subseteq BA \cap CA$ .
> [8-1,(6)]

**证明**：

a)  $A\Lambda = \{\alpha\lambda \mid \alpha \in A\} = \{\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = \{\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\} = A, \Lambda A = \{\lambda\alpha \mid \alpha \in A\}$

b) 因为 B⊆B∪C,所以 BA⊆(B∪C)A。同理 CA⊆(BUC)A,所以,BA∪CA⊆(B∪C)A。

任取  $\omega \in (B \cup C)A$ , 有  $\omega = \alpha\beta$ ,  $\alpha \in B \cup C$ ,  $\beta \in A$ 。当  $\alpha \in B$ 时, 有 $\omega \in BA$ 。当  $\alpha \in C$ 时, 有  $\omega \in CA$ , 所以,  $(B \cup C)A \subseteq BA \cup CA$ 。

综上所述,(BUC)A=BAUCA。

c) 因为  $B \cap C \subseteq B$ , $A(B \cap C) \subseteq AB$ 。 $B \cap C \subseteq C$ , $A(B \cap C) \subseteq AC$ 。所以, $A(B \cap C) \subseteq AB \cap AC$ 。

设  $A = \{c,cb\}$ ,  $B = \{ba\}$ ,  $C = \{a\}$  是  $V = \{a,b,c\}$  上的三个语言。 $B \cap C = \emptyset$ ,  $A(B \cap C) = \emptyset$ 。而  $AB = \{cba,cbba\}$ ,  $AC = \{ca,cba\}$ ,  $AB \cap AC = \{cba\}$ 。所以, $A(B \cap C) \subset AB \cap AC$ 。上式不能成立等号。

d) 与 c)类似。

---
#### 8-9

> 设  $A = \{\lambda, 0\}, B = \{0, 1\}$ 。列出下列集合的所有元素:
> - a)  $A^2$ ; b)  $B^3$ ; c) AB; d)  $A^+$ ; e)  $B^*$ . [8-1.(7)]

**解**：

a)  $A^2 = \{\lambda, 0, 00\}$ 。

b)  $B^3 = \{000,001,010,011,100,101,110,111\}$
c)  $AB = \{0,1,00,01\}$
d)  $A^{+} = A \cup A^{2} \cup A^{3} \cup \cdots = \{\lambda, 0\} \cup \{\lambda, 0, 00\} \cup \{\lambda, 0, 00, 000\} \cup \cdots = \{\lambda, 0, 00, 000, \cdots\} = \{0^{k} | k \ge 0\}_{0}$
e)  $B^* = \{0,1\}^* = \Lambda \cup B \cup B^2 \cup \dots = \{\lambda\} \cup \{0,1\} \cup \{00,01,10,11\} \cup \dots = \{a_1 a_2 \dots a_k | k \ge 0, a_i \in \{0,1\}, 1 \le i \le k\}$ 。  $B^*$  是由空 串及所有二进制串组成的集合。

---
#### 8-10

> 设 L 是字母表 V 上的语言。证明
> - a)  $L^mL^n=L^{m+n}$ ,其中  $m,n\geqslant 0$ ;
> - b)  $(L^m)^n = L^{mn}$ ,  $\sharp + m$ ,  $n \ge 0$ . [8-1.(8)]

**证明**：

a) 当m,n中有一为零时, $L^0 = \Lambda$ ,上式显然成立。

当  $m,n\geqslant 1$  时,对任一  $\omega\in L^mL^n$ ,有  $\omega=\alpha\beta$ , $\alpha\in L^m$ , $\beta\in L^n$ 。 故而

$$\alpha = \gamma_1 \gamma_2 \cdots \gamma_m, \gamma_i \in L(1 \leq i \leq m)$$

$$\beta = \theta_1 \theta_2 \cdots \theta_n, \theta_j \in L(1 \leq j \leq n)$$

$\alpha\beta = \gamma_1 \gamma_2 \cdots \gamma_m \theta_1 \theta_2 \cdots \theta_n \in L^{m+n}, L^m L^n \subseteq L^{m+n}$

反之,对任一 $\varphi \in L^{m+n}$ , $\varphi = \gamma_1 \gamma_2 \cdots \gamma_{m+n}$ , $\gamma_i \in L$ , $1 \leq i \leq m+n$ 。  $\Rightarrow \alpha = \gamma_1 \gamma_2 \cdots \gamma_m$ , $\beta = \gamma_{m+1} \gamma_{m+2} \cdots \gamma_{m+n}$ , $\alpha \in L^m$ , $\beta \in L^n$ , $\varphi \in L^m L^n$ ,  $L^{m+n} \subseteq L^m L^n$ ,因此, $L^m L^n = L^{m+n}$ 。 b) 当m,n中有一为零时, $(L^m)^n = \Lambda = L^{mn}$ 。当 $m,n \ge 1$ 时,由a)得:

$$(L^{m})^{n} = \underbrace{L^{m}L^{m}L^{m}\cdots L^{m}}_{n} = (L^{m}L^{m})\underbrace{L^{m}\cdots L^{m}}_{(n-2)}$$
$$= L^{2m}\underbrace{L^{m}\cdots L}_{n-2}^{m} = L^{3m}\underbrace{L^{m}\cdots L}_{(n-3)}^{m} = \cdots = L^{mn}$$

---
#### 8-11

> 写出字母表  $V = \{a; b, c\}$ 上串 aabcb 的所有前级,后 缀,真前缀,真后缀。

**解**：

串  $\omega = aabcb$  的前缀为 a, aa, aab, aabc, aabcb。后缀为 b, cb, bcb, abcb, aabcb。 真前缀为 a, aa, aab, aabc。 真后缀为 b, cb, bcb, abcb.

---
#### 8-12

> 任意给定有限字母表 V,证明:
> - a) V\* 是可列集;
> - b) V上任一语言 L 是有限集或可列集:
> - c) V上所有语言组成的集合是不可列集。

**证明**：

a) 设 $V = \{a_1, a_2, \dots, a_n\}, |V^k| = |V|^k = n^k, V_k$  是有限集。 $V^*$  是可列个有限集之并, $V^*$  是可列集。

b)  $L \neq V^*$  的子集, $V^*$  是可列集,L 是有限集或可列集。
c) V上所有语言组成的集合就是  $\mathcal{P}(V^*)$ ,因为  $V^*$  是可列集,  $\mathcal{P}(V^*)$  是不可列集。

---
#### 8-13

**证明**：

如果 A≠∅,A²=A,那么 A\*=A。反之成立吗?
$A^2 = A, A^3 = A^2 A = AA = A$ 。 一般有  $A^k = A(k \ge 2)$ 。
再证  $\Lambda \subseteq A$ 。用反证法,如果  $\lambda \notin A$ ,令 A 中长度最小的串为  $\omega, \omega \in A, |\omega| = i > 0$ 。因为  $A = A^2, \omega \in A^2, \omega = \omega_1 \omega_2, \omega_1, \omega_2 \in A$ 。由于  $\omega$  是 A 中长度最小的串, $|\omega_1| \geqslant i$ , $|\omega_2| \geqslant i$ , $|\omega| = |\omega_1| + |\omega_2| \geqslant 2i$ ,矛盾,因此  $\Lambda \subseteq A$ 。
$A^* = \bigwedge \bigcup A \bigcup A^2 \bigcup \cdots = \bigwedge \bigcup A \bigcup A \bigcup \cdots = \bigwedge \bigcup A = A$
反之,如果  $A\neq\emptyset$ , $A^*=A$  也可推得  $A=A^2$ 。因为  $\Lambda\subseteq A^*$ ,  $A^*=A$ ,  $\Lambda\subseteq A$ ,  $\lambda\in A$ 。一方面, A=A  $\Lambda\subseteq AA=A^2$ 。另一方面, A=A
$A^2 \subseteq A^* = A$ ,因此, $A = A^2$ 。
如果  $A=\emptyset$ ,显然有  $A=A^2=\emptyset$ ,但  $A^*=\Lambda$ ,  $A^*\neq A$ 。
---
#### 8-14

> 设 A 是 V 上的语言,那么有
> - a)  $AA^* = A^*A = A^+$ :
> - b)  $(A^*)^* = A^*A^* = A^*$ :
> - c)  $(A^*)^+ = (A^+)^* = A^*$ ;
> - d)  $A * A^+ = A^+ A^* = A^+$ :
> - e)  $(A^*B^*)^* = (A^* \cup B^*)^*$  [8-1.(10)]

**证明**：

a)  $AA^* = A \circ \bigcup_{i=0}^{\infty} A^i = \bigcup_{i=0}^{\infty} A^{i+1} = \bigcup_{j=1}^{\infty} A^j = A^+$ 。同理有  $A^*A = A^+$ 。

b) 先证  $A^*A^* = A^*$ 。

$A^*A^* = A^* \circ ( \land \bigcup A^+ ) = A^* \bigcup A^*A^+ , \text{ id } A^* \subseteq A^*A^*$

另一方面,对任一 $\alpha \in A^*A^*$ ,有 $\alpha = \beta \gamma$ , $\beta \in A^*$ , $\gamma \in A^*$ 。因为  $A^* = \bigcup_{i=0}^{\infty} A^i$ ,有 $\beta \in A^m$ , $\gamma \in A^n$ ,m, $n \geqslant 0$ 。 $\alpha = \beta \gamma \in A^{m+n} \subseteq A^*$ ,  $A^*A^* \subseteq A^*$ 。

由上可知,A\*A\*=A\*

再证 $(A^*)^* = A^*$ 。

因为 $(A^*)^2 = A^*A^* = A^*, (A^*)^3 = (A^*)^2A^* = A^*A^* = A^*,$ 可推得 $(A^*)^kA^* = A^*(k \ge 1)$ 。

$$(A^*)^+ = \bigcup_{k=1}^{\infty} (A^*)^k = \bigcup_{k=1}^{\infty} A^* = A^*$$
$$(A^*)^* = \bigwedge \bigcup (A^*)^+ = \bigwedge \bigcup A^* = A^*$$

c) 因为  $A^* \subseteq (A^*)^+$ 。另一方面, $(A^*)^+ \subseteq (A^*)^* = A^*$ 。因此, $(A^*)^+ = A^*$ 。

因为 $(A^+)^* \subseteq (A^*)^* = A^*, A \subseteq A^+, A^* \subseteq (A^+)^*$ 。因此 $(A^+)^* = A^*$ 。

d) 因为  $\land \subseteq A^*$   $, A^+ = \land A^+ \subseteq A^* A^+$  。另一方面,任取  $\alpha \in A^* A^+$   $, \alpha = \beta \gamma$   $, \beta \in A^*$   $, \gamma \in A^+$   $, \beta \in A^m$   $, m \ge 0$   $, \gamma \in A^n$   $, n \ge 1$   $, \alpha = \beta \gamma \in A^{m+n} \subseteq A^+$   $(m+n \ge 1)$  ,所以  $, A^* A^+ \subseteq A^+$  。

由上可知

$A * A^{+} = A^{+}$

同理可证

$A^+A^*=A^+$

e) 先证(A\* UB\*)\*⊆(A\* B\*)\*。

因为  $A^* = A^* \land \subseteq A^* B^*$ ,  $B^* \subseteq A^* B^*$ ,  $A^* \cup B^* \subseteq A^* B^*$ ,  $(A^* \cup B^*)^* \subseteq (A^* B^*)^*$ .

因为  $A^* \subseteq A^* \cup B^*$  ,  $B^* \subseteq A^* \cup B^*$  ,  $A^* B^* \subseteq (A^* \cup B^*)^2 \subseteq (A^* \cup B^*)^*$  , 所以  $(A^* B^*)^* \subseteq ((A^* \cup B^*)^*)^* = (A^* \cup B^*)^*$  . 由此可知,  $(A^* B^*)^* = (A^* \cup B^*)^*$

---
#### 8-15

**证明**：

如果 L 是镜像语言,那么,L'也是镜像语言。
[8-1.(11)]
L 是镜像语言,L=L'。因为 L=(L')',所以,L'=(L')',L'是镜像语言。
---
#### 8-16

> 给定语言 L,令  $\hat{L}=L\cap L'$ 。如果 L 是镜像语言, $\hat{L}$  必是镜像语言吗?反之,如果  $\hat{L}$  是镜像语言,L 必是镜像语言吗? [8-1.(12)]

**证明**：

L 是镜像语言,L=L', $\hat{L}=L\cap L'=L\cap L=L$ , $\hat{L}$  是镜像语言。

反之, $\hat{L}$  是镜像语言,L 不一定是镜像语言。例如, $L=\{0,01\}$ , $L'=\{0,10\}$ , $\hat{L}=L\cap L'=\{0\}$ , $\hat{L}$  是镜像语言, $L\neq L'$ ,L 不是镜像语言。

---
#### 8-17

> 设文法 G 具有下列生成规则:
> - a)  $\sigma \rightarrow aA, A \rightarrow BA, A \rightarrow aAB, A \rightarrow a, B \rightarrow b$ ;
> - b)  $\sigma \rightarrow aAB, BA \rightarrow BbA, A \rightarrow bB, B \rightarrow b$ ;
> - c)  $\sigma \rightarrow BBAA, BAB \rightarrow BB, \sigma \rightarrow c, A \rightarrow a, B \rightarrow AS, A \rightarrow a, B \rightarrow bb;$
> - d)  $A \rightarrow aB, B \rightarrow bA, \sigma \rightarrow bA, A \rightarrow a, B \rightarrow b$ :
> - e)  $\sigma \rightarrow Ba, A \rightarrow Bb, B \rightarrow Aa, A \rightarrow a, B \rightarrow b$
> 试问文法 G分别属于哪一型?

**解**：

a) 每一生成式形为  $A \rightarrow \omega$ , 左边只有一个非终结符, 该文 法属 2 型文法。

b) 每一生成式形为  $\varphi A \psi \rightarrow \varphi \omega \psi$ ,其中  $\omega \neq \lambda$ ,该文法属 1 型 文法。
c) 生成式 BAB→BB 是一条缩减规则,该文法属 0 型文法。
d)每一生成式形为  $D \rightarrow dE$  或  $D \rightarrow d$ ,该文法属 3 型文法,是 右线性文法。
e) 每一生成式形为 D→Ed 或 D→d,该文法属 3 型文法,是 左线性文法。

---
#### 8-18

> 给定前后文无关文法 G,它有下列生成式:
> $$\sigma \rightarrow aBA, B \rightarrow Aba, A \rightarrow bA, A \rightarrow c$$
> 求串 acbabc 的派生过程,画出派生树。

**解**：

串 acbabc 的派生过程为:

$\sigma \Rightarrow aBA \Rightarrow aAbaA \Rightarrow acbaA$

$\Rightarrow acbabA \Rightarrow acbabc$

派生树如图 8-21 所示。

---
#### 8-21

> 8-21** 给定文法  $G = (V_N, V_T, P, \sigma), V_N = \{\sigma, B, C\}, V_T = \{a,b,c\},$ 生成式集 P:
> - (1)  $\sigma \rightarrow a\sigma BC$ :
> - (2)  $\sigma \rightarrow aBC$ ; (3)  $CB \rightarrow BC$ ; (4)  $aB \rightarrow ab$ ;
> - (5)  $bB \rightarrow bb$ ; (6)  $bC \rightarrow bc$ ; (7)  $cC \rightarrow cc$ .

**证明**：

a)  $\sigma \Rightarrow a^n b^n c^n$ 。判断它属于哪一型文法。

b) 串  $a^nb^nc^n(n \ge 1)$  是 L(G) 中仅有的终结符串,由此可知  $L(G) = \{a^nb^nc^n | n \ge 1\}$ 。 【8-2.(3)】

该文法的生成式中只有  $CB \rightarrow BC$  不属于  $\varphi A \psi \rightarrow \varphi \omega \psi$  形式。但是我们引进新的非终结符 D 和 E,令  $V'_N = \{\sigma, B, C, D, E\}$ 。将生成式  $CB \rightarrow BC$  改为:  $CB \rightarrow DB$ , $DB \rightarrow DE$ , $DE \rightarrow BE$ , $BE \rightarrow BC$ 。那么,这些生成式都属于  $\varphi A \psi \rightarrow \varphi \omega \psi$  形式了,所以文法 G 是上下文有关文法。


由于生成式(4),(5),(6)和(7)的左端,在非终结符 B 或 C 的 左邻为终结符,因此在任何以  $\sigma$  开始的派生过程中未运用生成式 (2)之前不能运用他们。 $n-1(\geq 1)$ 次运用生成式(1)和 1 次运用

生成式(2),有

$$\sigma \stackrel{*}{\Rightarrow} a^n (BC)^n \quad (n \geqslant 1)$$

由于  $a^n(BC)^n$  中没有  $\sigma$  了,不能再运用生成式(1)或(2)。此时只能运用生成式(3)或(4)。生成式(3)将非终结符 B 和 C 位置互换,生成式(4)将非终结符 B 换为终结符 b。运用了生成式(4)后才可运用生成式(5)或(6),他们分别将非终结符 B 和 C 换为终结符 b 和 c。此时,字符串为:

$$a^n b^i c \alpha \quad (i \leq n)$$

其中  $\alpha$  是由 B 和 C 组成, B 的数目为 n-i, C 的数目为 n-1.

如果  $i < n, \alpha$  中至少有一个 B。在  $a^n b^i c \alpha$  的派生中只能运用生成式(3)或(7),因为(3)只能改变 B 和 C 的次序,(7)只能将非终结符 C 改为终结符 c,所以不管怎样交替运用生成式(3)或(7), $c\alpha$  中的非终结符 B 始终不能消失,因此不能得到由终结符组成的串。

如果 i=n,此时串为:

$$a^nb^nc\alpha$$

其中 $\alpha$ 由n-1个C组成。此时,在 $a^nb^nc\alpha$ 的派生中只能运用生成 (7)式了,重复使用生成(7)式就得终结符串 $a^nb^nc\alpha$ 。

---
#### 8-22

> 构造右线性文法,使它产生被3整除的非负数。画出对应的有限自动机的状态图。

**解**：

一个数被 3 整除当且仅当它的各位数字之和是 3 的倍数。为了方便起见,允许一个数可以以 0 开始,即允许有 024,005709 等数。

我们将 $\{0,1,2,\cdots,9\}$ 划分为三个集合, $A_0 = \{0,3,6,9\}$ , $A_1 = \{1,4,7\}$ , $A_2 = \{2,5,8\}$ 。 $A_0$  中数字可被 3 整除, $A_1$  中数字被 3 除 余 1, $A_2$  中数字被 3 除余 2。构造右线性文法  $G = (\{R_0,R_1,R_2\},\{0,1,2,3,4,5,6,7,8,9\},P,R_0)$ ,其中 P 为:

$$R_0 \rightarrow 0, R_0 \rightarrow 3, R_0 \rightarrow 6, R_0 \rightarrow 9$$

$R_1 \rightarrow 1, R_1 \rightarrow 4, R_1 \rightarrow 7$

$R_2 \rightarrow 2$ ,  $R_2 \rightarrow 5$ ,  $R_2 \rightarrow 8$   $R_0 \rightarrow 0R_0$ ,  $R_0 \rightarrow 3R_0$ ,  $R_0 \rightarrow 6R_0$ ,  $R_0 \rightarrow 9R_0$   $R_0 \rightarrow 1R_2$ ,  $R_0 \rightarrow 4R_2$ ,  $R_0 \rightarrow 7R_2$ ,  $R_0 \rightarrow 2R_1$   $R_0 \rightarrow 5R_1$ ,  $R_0 \rightarrow 8R_1$   $R_1 \rightarrow 0R_1$ ,  $R_1 \rightarrow 3R_1$ ,  $R_1 \rightarrow 6R_1$ ,  $R_1 \rightarrow 9R_1$   $R_1 \rightarrow 1R_0$ ,  $R_1 \rightarrow 4R_0$ ,  $R_1 \rightarrow 7R_0$ ,  $R_1 \rightarrow 2R_2$   $R_1 \rightarrow 5R_2$ ,  $R_1 \rightarrow 8R_2$   $R_2 \rightarrow 0R_2$ ,  $R_2 \rightarrow 3R_2$ ,  $R_2 \rightarrow 6R_2$ ,  $R_2 \rightarrow 9R_2$   $R_2 \rightarrow 1R_1$ ,  $R_2 \rightarrow 4R_1$ ,  $R_2 \rightarrow 7R_1$ ,  $R_2 \rightarrow 2R_0$  $R_2 \rightarrow 5R_0$ ,  $R_2 \rightarrow 8R_0$

由生成式可知,从  $R_0$  开始派生的数均能被 3 整除,从  $R_1$  开始派生的数被 3 除余 1,从  $R_2$  开始派生的数被 3 除余 2。文法 G 产生被 3 整除的非负数。例如数 523281 的派生过程为:

$R_0 \Rightarrow 5R_1 \Rightarrow 52R_2 \Rightarrow 523R_2 \Rightarrow 5232R_0 \Rightarrow 52328R_1 \Rightarrow 523281$  文法 G 对应的有限自动机的状态图如图 8-24 所示。

![](_page_47_Figure_16.jpeg)

---
#### 8-23

> a) 构造一个左线性文法  $G_1$ ,使  $L(G_1) = \{10^n | n \ge 0\}$ ; b) 构造一个右线性文法  $G_2$ ,使  $L(G_2) = \{ab^m | m \ge 0\} \cup \{c^n | n\}$
> $\geqslant 1$ } (8-2.(4)]

**解**：

a)  $G_1 = (V_N, V_T, P, \sigma), V_N = \{\sigma, A\}, V_T = \{0, 1\}, P:\sigma \rightarrow 1, \sigma \rightarrow A0, A \rightarrow A0, A \rightarrow 1, \sigma$

b)  $G_2 = (V_N, V_T, P, \sigma), V_N = \{\sigma, B, C\}, V_T = \{a, b, c\}, P: \sigma \rightarrow a, \sigma \rightarrow aB, B \rightarrow bB, B \rightarrow b, \sigma \rightarrow c, \sigma \rightarrow cC, C \rightarrow cC, C \rightarrow c \circ c$

---
#### 8-24

> 设文法 G 的生成式的形式都是  $A \rightarrow \varphi B$  和  $A \rightarrow \varphi$ ,其中  $A,B \in V_N, \varphi \in V_T^+$ 。试证 G 产生的语言能由右线性文法产生。
> [8-2.(5)]

**证明**：

设文法为  $G=(V_N,V_T,P,\sigma)$ ,其中  $V_T=\{a_1,a_2,\cdots,a_k\}$ 。构造新文法  $G'=(V_N',V_T',P',\sigma')$ ,令  $V_T'=V_T,\sigma'=\sigma$ 。G'的 牛成式集 P'根据 G 的生成式集 P 构造。

a) 对 P 中形为  $A \rightarrow \varphi$ ,  $A \rightarrow \varphi B$  的生成式, 如果  $\varphi$  是一个终结符, 那么在 P' 中保持不变。
b) 如果 P 中有生成式  $A \rightarrow \varphi$ ,  $\varphi = a_{i_1} a_{i_2} \cdots a_{i_p}$ 。在 G' 中增加新非终结符  $B_1$ ,  $B_2$ ,  $\cdots$ ,  $B_{p-1}$ , 将生成式  $A \rightarrow a_{i_1} a_{i_2} \cdots a_{i_p}$  改写为:

$$A \rightarrow a_{i_1} B_1, B_1 \rightarrow a_{i_2} B_2, \cdots, B_{p-2} \rightarrow a_{i_{p-1}} B_{p-1}, B_{p-1} \rightarrow a_{i_p}$$

c) 如果 P 中有生成式  $A \rightarrow \varphi B$ ,  $\varphi = b_{i_1} b_{i_2} \cdots b_{i_k}$ , 在 G' 中增加新非终结符  $C_1, C_2, \cdots, C_{k-1}$ 。将生成式  $A \rightarrow b_i, b_i, \cdots b_i, B$  改写为:

$$A \rightarrow b_{j_1} C_1, C_1 \rightarrow b_{j_2} C_2, \cdots, C_{k-2} \rightarrow b_{j_{k-1}} C_{k-1}, C_{k-1} \rightarrow b_{j_k} B$$

这样构造的新文法 G',有 L(G') = L(G)。且 G' 是右线性文法。

例如  $G=(\{\sigma,A\},\{0,1\},P,\sigma)$ ,其中  $P:\sigma\to 0,\sigma\to 10,\sigma\to 0A$ ,  $A\to 01A$ , $A\to 1$ 。构造  $G'=(\{\sigma,A,B,C\},\{0,1\},P',\sigma)$ ,其中  $P':\sigma\to 0,\sigma\to 1B$ , $B\to 0,\sigma\to 0A$ , $A\to 0C$ , $C\to 1A$ , $A\to 1$ 。G'为右线性文法,且 L(G')=L(G)。

---
#### 8-25

> 给定正则文法  $G=(V_N, V_T, P, \sigma)$ , 其中  $V_N = \{\sigma, A, B\}$ ,  $V_T = \{0,1\}$ , 生成式集 P 为:
> - (1)  $\sigma \rightarrow 0\sigma$ ;
> - (2)  $\sigma \rightarrow 1A$ ;
> - (3)  $A \rightarrow 0_{\sigma}$ ;
> - (4)  $A \rightarrow 1B$ :
> - (5)  $B \rightarrow 0\sigma$ ;
> - (6)  $B \rightarrow 0A$ ;
> - (7)  $\sigma \rightarrow 0$ ;
> - (8)  $\sigma \rightarrow 1$ :
> - (9)  $A \rightarrow 0$ ;
> (10)  $A \rightarrow 1$ ; (11)  $B \rightarrow 0$ .
> 描述 L(G),并写出 00110100011 的派生过程。

**解**：

构造接受 L(G)的有限状态接收器为: $M=(\{\sigma,A,B,C\},\{0,1\},\delta,\{\sigma\},\{C\})$ ,其中  $\delta$  为:

$$\delta(\sigma,0) = \{\sigma,C\}, \delta(\sigma,1) = \{A,C\}$$

$$\delta(A,0) = \{\sigma,C\}, \delta(A,1) = \{B,C\}$$

$$\delta(B,0) = \{\sigma,A,C\}$$

它的状态图如图 8-25 所示。

令 $\alpha \in \{0,1\}^*$ ,由状态图可知,当输入串是 $\alpha 0$ 时,M可处于状态 $\sigma$ ;当输入串是1或 $\alpha 01$ 时,M可处于状态A;当输入串是11或 $\alpha 011$ 时,M可处于状态B。当M处于状态B时,只有输入字母0时才能离开状态B而到达状态 $\sigma$ ,A或终态C。因此,当输入串含有三个以上连续的1,

![](_page_48_Figure_31.jpeg)

图 8-25

必被 M 拒绝,当输入串含有连续的 1 的个数不超过两个时,能被 M 接受。 $L(G)=L(M)=\{\omega | \omega \in (0,1)^+$  且  $\omega$  中不包含三个以上 连续的  $1\}$ 。

00110100011 的派生过程为:

$$\sigma \Rightarrow 0 \sigma \Rightarrow 00 \sigma \Rightarrow 001 A \Rightarrow 0011B$$

$$\stackrel{(5)}{\Rightarrow} 00110_{\sigma} \stackrel{(2)}{\Rightarrow} 001101A \stackrel{(3)}{\Rightarrow} 0011010_{\sigma}$$

$$\stackrel{\text{(1)}}{\Rightarrow} 00110100 \sigma \stackrel{\text{(1)}}{\Rightarrow} 001101000 \sigma$$

$$\Rightarrow$$
0011010001 $A$  $\Rightarrow$ 00110100011

---
#### 8-26

> 给出一个产生语言  $L = \{\omega | \omega \in \{0,1\}^*$  且  $\omega$  不含有两个相邻的  $1\}$ 的正则文法。

**解**：

产生语言 L 的正则文法为  $G = (\{\sigma, A\}, \{0, 1\}, P, \sigma)$ ,其中 P 为: $\sigma \to \lambda, \sigma \to 0$ , $\sigma \to 1$ , $\sigma \to 0\sigma$ , $\sigma \to 1A$ , $A \to 0\sigma$ , $A \to 0$ .

接受 L 的有限状态接收器 M 的状态图如图 8-26 所示。

![](_page_49_Figure_1.jpeg)

---
#### 8-27

> 给出一个产生语言  $L=\{\omega\omega' \mid \omega \in \{0,1\}^*\}$  的上下文有关文法。 [8-2.(7)]

**解**：

产生语言 L 的上下文有关 文法为  $G=(\{\sigma,A\},\{0,1\},P,\sigma)$ ,其 中 P 为: $\sigma \rightarrow \lambda$ , $\sigma \rightarrow 00$ , $\sigma \rightarrow 11$ , $\sigma \rightarrow$ 0A0, $\sigma \rightarrow 1A1$ , $A \rightarrow 0\sigma0$ , $A \rightarrow 1\sigma1$ , $A \rightarrow$ 00, $A \rightarrow 11$ .

图 8-26

---
#### 8-28

> 考察下列 0 型文法:
> $$G = (\{\sigma, A, B, C, D, E\}, \{0, 1\}, P, \sigma)$$
> #### 其中 P 为:
> - (1)  $\sigma \rightarrow ABC$ ;
> - (2)  $AB \rightarrow 0AD$ ;
> - (3)  $AB \rightarrow 1AE$ ;
> - (4)  $AB \rightarrow \lambda$ ;
> - $(5) D0 \rightarrow 0D;$
> - (6)  $D1 \rightarrow 1D$ ;
> - (7)  $E0 \rightarrow 0E$ ;
> - (8)  $E1 \rightarrow 1E$ :
> - (9)  $C \rightarrow \lambda$ ;
> - (10)  $DC \rightarrow B0C$ :
> - (11)  $EC \rightarrow B1C$ ;
> - (12)  $0B \rightarrow B0$ :
> (13)  $1B \rightarrow B1$ .
> 描述 L(G), 并写出 01100110 的派生过程。
> [8-2.(8)]

**解**：

该文法产生的语言为:

$$L(G) = \{\omega\omega \mid \omega \in \{0,1\}^*\}$$

01100110 的派生过程为:

$\sigma \Rightarrow ABC \Rightarrow 0ADC \Rightarrow 0AB0C \Rightarrow 01AE0C$

$\stackrel{(7)}{\Rightarrow} 01A0EC \stackrel{(11)}{\Rightarrow} 01A0B1C \stackrel{(12)}{\Rightarrow} 01AB01C \stackrel{(3)}{\Rightarrow} 011AE01C$

$\stackrel{(7)}{\Rightarrow} 011A0E1C \stackrel{(8)}{\Rightarrow} 011A01EC \stackrel{(11)}{\Rightarrow} 011A01B1C$

$\Rightarrow$  011A0B11C $\Rightarrow$  011AB011C $\Rightarrow$  0110AD011C

$\stackrel{(5)}{\Rightarrow} 0110A0D11C \stackrel{(6)}{\Rightarrow} 0110A01D1C \stackrel{(6)}{\Rightarrow} 0110A011DC$

$\begin{array}{c}
\stackrel{(10)}{\Rightarrow} 0110A011B0C \stackrel{(13)}{\Rightarrow} 0110A01B10C \stackrel{(13)}{\Rightarrow} 0110A0B110C \\
\stackrel{(12)}{\Rightarrow} 0110AB0110C \stackrel{(4)}{\Rightarrow} 01100110C \stackrel{(9)}{\Rightarrow} 01100110
\end{array}$

由上述派生过程可知:(1)式右端 ABC 中的 AB 用来产生字符串  $\omega\omega$  中左边的  $\omega$ , C 用来产生右边的  $\omega$ 。(2)式和(3)式分别用来产生左边  $\omega$  中的 0 和 1。如果产生 0,同时消去非终结符 B,产生终结符 D 来标志;如果产生 1,同时消去非终结符 B,产生终结符 E 来标志。(5)式和(6)式使 D 右移。(7)式和(8)式使 E 右移。(10)式和(11)式用来产生右边  $\omega$  中相应的 0 和 1,同时消去 D 或 E,恢复非终结符 B。(12)式和(13)式使 B 左移。(4)式和(9)式 在派生得到字符串  $\omega AB\omega C$  后,用来消去 AB 和 C,从而得到终结符 B

---
#### 8-29

> 构造有限状态机  $M=(Q,S,R,f,g,q_I)$ ,其中  $S=R=\{0,1,2,3\}$ ,对于 t>2,有 r(t)=m(t)+n(t),这里
> $$m(t) = \begin{cases} 2, & \text{mult} \ s(t-1) \not\equiv 0 \ \text{mult} \ 2 \\ 0, & \text{multiple} \end{cases}$$
> 和
> $$n(t) = \begin{cases} 1, & \text{mult} \ s(t-2) \not\equiv 1 \ \text{mult} \ 3 \\ 0, & \text{mult} \end{cases}$$
> 如果令 s(-1)=s(0)=0,确定 r(1)和 r(2)。
> [8-3.(1)]

**解**：

由 r(t)的定义可知,r(t)由 s(t-2)和 s(t-1)决定,因此,机器应有记忆 s(t-2)s(t-1)的功能。 M 有四个状态: A,B,C,D。他们与 s(t-2)s(t-1)的关系如表 8-6 所示。

表 8-6

| <b>水</b> 态   | A           | В           | С           | D           |
|--------------|-------------|-------------|-------------|-------------|
| s(t-2)s(t-1) | 10,12,30,32 | 00,02,20,22 | 11,13,31,33 | 01,03,21,
有限状态机 M 的状态图如图 8-27 所示。

对图 8-27 说明一下。如果机器处于状态 A,即 s(t-2)s(t-1)=10,12,30 或 32。当输入字母为 0,则:s(t-2)s(t-1)s(t)=

--

## 第九章 纠错码初步

#### 9-1

> 构造所有长度为 2 的二进制编码。找出能检查出单错的编码。是否存在能纠正单错的编码,为什么? 【9-1.(1)】

**解**：

长度为 2 的二进制串有四个:00,01,10,11。长度为 2 的二进制编码有  $2^4-1=15$  个。

$C_1 = \{00\}, C_2 = \{01\}, C_3 = \{10\}, C_4 = \{11\}, C_5 = \{00,01\},$   $C_6 = \{00,10\}, C_7 = \{00,11\}, C_8 = \{01,10\}, C_9 = \{01,11\}, C_{10} = \{10,11\}, C_{11} = \{00,01,10\}, C_{12} = \{00,01,11\}, C_{13} = \{00,10,11\},$   $C_{14} = \{01,10,11\}, C_{15} = \{00,01,10,11\},$

由于  $C_1$ ,  $C_2$ ,  $C_3$ ,  $C_4$  这四码个中只有一个码字, 任一位出错得到的都是废码, 因此这四个码都能纠错。

码  $C_5$ ,  $C_6$ ,  $C_9$ ,  $C_{10}$ ,  $C_{11}$ ,  $C_{12}$ ,  $C_{13}$ ,  $C_{14}$ ,  $C_{15}$  的海明距为 1, 不能检 查出单错。

码  $C_7$ ,  $C_8$  的海明距为 2, 能查出单错, 不能纠单错。

---
#### 9-2

> 写出下列单词的五单位电传码和 3:4码: CHINA, SHANGHAI。

**解**：

英文字母的五单位电传码和 3:4码可见:《离散数学》(上海科学技术文献出版社,1982.9)一书第 397 页,我们得五单位电传码为:
0111000101011000011011000001101010000101

3:4码为:

1001100101010111100001010100001101010101

---
#### 9-3

> 群计数码是先将传送的信息中码元"1"的数目用二进制数字表示,然后把此二进制数作为校验位,放在信息位后面,组成一个码字。如 10111 中有四个"1",4 的二进制为 100,故 10111 变为码字 10111100。写出所有信息位长五位所对应的群计数码,并说明群计数码能检单错,不能纠单错

**解**：

由于信息位长五位,至多含有五个"1",故需增加三位校验位,该码如表 9-6 所示。

如果信息位中有一位出错,改变了信息位中"1"的数目,与校验位表示的二进制数不符,是废码。如果校验位中有一位出错,同样出错后校验位表示的二进制数与信息位中"1"的数目不符,是废码。所以,群计数码能检单错。

码字 00101010 在第八位出错,码字 00111011 在第四位出错 均变成废码 00101011,所以不能纠单错。

---
#### 9-4

> 给定三个信息位  $c_1$ ,  $c_2$ ,  $c_3$  与两个校验位  $c_4$ ,  $c_5$ , 他们满足等式:
> $$c_1 + c_2 + c_3 + c_4 + c_5 = 0$$
> 写出重量均为2的所有码字,讨论它的检错纠错能力。
> 表 9-6
> |                  | 信     |                       | 息                     | 位  | í.                    | 校  | 验          | 位  | 码  |   |   |   | 字 |   |   |   |  |  |
> |------------------|-------|-----------------------|-----------------------|----|-----------------------|----|------------|----|----|---|---|---|---|---|---|---|--|--|
> |                  | $c_1$ | <i>c</i> <sub>2</sub> | <i>c</i> <sub>3</sub> | C4 | <i>c</i> <sub>5</sub> | C6 | <i>C</i> 7 | C8 |    |   | 俏 |   |   | 子 |   |   |  |  |
> | 88 <del>71</del> | 0     | 0                     | 0                     | 0  | 0                     | 0  | 0          | 0  | 0  | 0 | 0 | 0 | 0 | 0 | 0 | 0 |  |  |
> |                  | 0     | 0                     | 0                     | 0  | 1                     | 0  | 0          | 1  | 0  | 0 | 0 | 0 | 1 | 0 | 0 | 1 |  |  |
> |                  | 0     | 0                     | 0                     | 1  | 0                     | 0  | 0          | 1  | 0  | 0 | 0 | 1 | 0 | 0 | 0 | 1 |  |  |
> |                  | 0     | 0                     | 0                     | 1  | 1                     | 0  | 1          | 0  | 0  | 0 | 0 | 1 | 1 | 0 | 1 | 0 |  |  |
> |                  | 0     | 0                     | 1                     | 0  | 0                     | 0  | 0          | 1  | 0  | 0 | 1 | 0 | 0 | 0 | 0 | 1 |  |  |
> |                  | 0     | 0                     | 1                     | 0  | 1                     | 0  | 1          | 0  | 0  | 0 | 1 | 0 | 1 | 0 | 1 | 0 |  |  |
> |                  | 0     | 0                     | 1                     | 1  | 0                     | 0  | 1          | 0  | 0  | 0 | 1 | 1 | 0 | 0 | 1 | 0 |  |  |
> |                  | 0     | 0                     | 1                     | 1  | 1                     | 0  | 1          | 1  | 0  | 0 | 1 | 1 | 1 | 0 | 1 | 1 |  |  |
> |                  | 0     | 1                     | 0                     | 0  | 0                     | 0  | 0          | 1  | 0  | 1 | 0 | 0 | 0 | 0 | 0 | 1 |  |  |
> |                  | 0     | 1                     | 0                     | 0  | 1                     | 0  | 1          | 0  | 0  | 1 | 0 | 0 | 1 | 0 | 1 | 0 |  |  |
> |                  | 0     | 1                     | 0                     | 1  | 0                     | 0  | 1          | 0  | 0  | 1 | 0 | 1 | 0 | 0 | 1 | 0 |  |  |
> |                  | 0     | 1                     | 0                     | 1  | 1                     | 0  | 1          | 1  | 0  | 1 | 0 | 1 | 1 | 0 | 1 | 1 |  |  |
> |                  | 0     | 1                     | 1                     | 0  | 0                     | 0  | 1          | 0  | 0  | 1 | 1 | 0 | 0 | 0 | 1 | 0 |  |  |
> |                  | 0     | 1                     | 1                     | 0  | 1                     | 0  | 1          | 1  | 0  | 1 | 1 | 0 | 1 | 0 | 1 | 1 |  |  |
> |                  | 0     | 1                     | 1                     | 1  | 0                     | 0  | 1          | 1  | -0 | 1 | 1 | 1 | 0 | 0 | 1 | 1 |  |  |
> |                  | 0     | 1                     | 1                     | 1  | 1                     | 1  | 0          | 0  | 0  | 1 | 1 | 1 | 1 | 1 | 0 | 0 |  |  |
> |                  | 1     | 0                     | 0                     | 0  | 0                     | 0  | 0          | 1  | 1  | 0 | 0 | 0 | 0 | 0 | 0 | 1 |  |  |
> |                  | 1     | 0                     | 0                     | 0  | 1                     | 0  | 1          | 0  | 1  | 0 | 0 | 0 | 1 | 0 | 1 | 0 |  |  |
> |                  | 1     | 0                     | 0                     | 1  | 0                     | 0  | 1          | 0  | 1  | 0 | 0 | 1 | 0 | 0 | 1 | 0 |  |  |
> |                  | 1     | 0                     | 0                     | 1  | 1                     | 0  | 1          | 1  | 1  | 0 | 0 | 1 | 1 | 0 | 1 | 1 |  |  |
> |                  | 1     | 0                     | 1                     | 0  | 0                     | 0  | 1          | 0  | 1  | 0 | 1 | 0 | 0 | 0 | 1 | 0 |  |  |
> |                  | 1     | 0                     | 1                     | 0  | 1                     | 0  | 1          | 1  | 1  | 0 | 1 | 0 | 1 | 0 | 1 | 1 |  |  |
> |                  | 1     | 0                     | 1                     | 1  | 0                     | 0  | 1          | 1  | 1  | 0 | 1 | 1 | 0 | 0 | 1 | 1 |  |  |
> |                  | 1     | 0                     | 1                     | 1  | 1                     | 1  | 0          | 0  | 1  | 0 | 1 | 1 | 1 | 1 | 0 | 0 |  |  |
> |                  | 1     | 1                     | 0                     | 0  | 0                     | 0  | 1          | 0  | 1  | 1 | 0 | 0 | 0 | 0 | 1 | 0 |  |  |
> |                  | 1     | 1                     | 0                     | 0  | 1                     | 0  | 1          | 1  | 1  | 1 | 0 | 0 | 1 | 0 | 1 | 1 |  |  |
> |                  | 1     | 1                     | 0                     | 1  | 0                     | 0  | 1          | 1  | 1  | 1 | 0 | 1 | 0 | 0 | 1 | 1 |  |  |
> |                  | 1     | 1                     | 0                     | 1  | 1                     | 1  | 0          | 0  | 1  | 1 | 0 | 1 | 1 | 1 | 0 | 0 |  |  |
> |                  | 1     | 1                     | 1                     | 0  | 0                     | 0  | 1          | 1  | 1  | 1 | 1 | 0 | 0 | 0 | 1 | 1 |  |  |
> |                  | 1     | 1                     | 1                     | 0  | 1                     | 1  | 0          | 0  | 1  | 1 | 1 | 0 | 1 | 1 | 0 | 0 |  |  |
> |                  | 1     | 1                     | 1                     | 1  | 0                     | 1  | 0          | 0  | 1  | 1 | 1 | 1 | 0 | 1 | 0 | 0 |  |  |
> | _                | 1     | 1                     | 1                     | 1  | 1                     | 1  | 0          | 1  | 1  | 1 | 1 | 1 | 1 | 1 | 0 | 1 |  |  |

**解**：

该码如表 9-7 所示。

表 9-7

| 信<br>c <sub>1</sub> | 息<br>c <sub>2</sub> | 位<br>c3 | 校 § | d<br>cs |   | 码 |    | 字 |   |
|---------------------|---------------------|---------|-----|---------|---|---|----|---|---|
| 0                   | 0                   | 0       | 1   | 1       | 0 | 0 | 0  | 1 |
| 0                   | 0                   | 1       | 0   | 1       | 0 | 0 | 1  | 0 |
| 0                   | 0                   | 1       | 1   | 0       | 0 | 0 | 1  | 1 |
| 0                   | 1                   | 0       | 0   | 1       | 0 | 1 | 0  | 0 |
| 0                   | 1                   | 0       | 1   | 0       | 0 | 1 | 0  | 1 |
| 0                   | 1                   | 1       | 0   | 0       | 0 | 1 | 1  | 0 |
| 1                   | 0                   | 0       | 0   | 1       | 1 | 0 | o. | 0 |
| 1                   | 0                   | 0       | 1   | 0       | 1 | 0 | 0  | 1 |
| 1                   | 0                   | 1       | 0   | 0       | 1 | 0 | 1  | 0 |
| 1                   | 1                   | 0       | 0   | 0       | 1 | 1 | 0  | 0 |
由表 9-7 可知,该码的最小距为 2,能检单错不能纠单错。这种码的每个码字,其五个码元中,码元"1"占二位,码元"0"占三位,称为 2:3码,电传码中每个码字有三个"1",四个"0",是与它类似的码。

---
#### 9-5

> 已知字母 0,1 正确传送的概率是 0.98,试求:
> - a) CHINA 的五单位电传码只在前三位出错的概率;
> - b) CHINA 的五单位电传码有一位出错的概率。 【9-1.(3)】

**解**：

五单位电传码中每个字母用五位二进制表示,故CHINA的五单位电传码长 25 位。
a) 前三位出错的概率:

$$(1-0.98)^3 \cdot (0.98)^{22} \approx 5.13 \times 10^{-6}$$

b) 有一位出错的概率:

$$\binom{25}{1}(1-0.98)(0.98)^{24} \approx 0.3079$$

---
#### 9-6

> 一个字长十位的码字在传送过程中要求两位出错的概率不超过 10<sup>-3</sup>,试求字母正确传送的概率。 【9-1.(4)】

**解**：

设字母正确传送的概率为 x,字母出错的概率为 y=1-x,字长十位的码字两位出错的概率为:

$$\binom{10}{2} y^2 (1-y)^8 \approx \binom{10}{2} y^2 (1-8y)$$

由不等式

$$\binom{10}{2} y^2 (1-8y) \leq 10^{-3}$$

得  $y \le 4.7 \times 10^{-3}$ ,故字母正确传送的概率  $x \ge 0.9953$ 。

---
#### 9-7

> 给定码  $C = \{00000, 10001, 01100, 10101\}$ , **试求码** C 中任两个码字的海明距和  $d_{\min}(C)$ 。

**解**：

$$H(00000,10001) = 2$$
,  $H(00000,01100) = 2$
$H(00000,10101) = 3$ ,  $H(10001,01100) = 4$
$H(10001,10101) = 1$ ,  $H(01100,10101) = 3$
$d_{\min}(C) = 1$

---
#### 9-8 设 X,Y,Z 是线性码 C 中三个不同的码字,写出 H(X,Y) + H(Y,Z) = H(X,Z)

的充要条件,并加以证明。

[9-2,(2)]

令
$$X=x_1x_2\cdots x_n$$
,  $Y=y_1y_2\cdots y_n$ ,  $Z=z_1z_2\cdots z_n$ , 那么  $H(X,Y)=(x_1+y_1)+(x_2+y_2)+\cdots+(x_n+y_n)$  [註]  $H(Y,Z)=(y_1+z_1)+(y_2+z_2)+\cdots+(y_n+z_n)$   $H(X,Z)=(x_1+z_1)+(x_2+z_2)+\cdots+(x_n+z_n)$

使 H(X,Y)+H(Y,Z)=H(X,Z)成立的充要条件是对每一 $i(1 \le i \le n)$ ,有 $(x_i+y_i)+(y_i+z_i)=x_i+z_i$ 。显然,当 $x_i=z_i$ 时,必须有 $x_i=y_i=z_i$ 。当 $x_i\neq z_i$ 时, $y_i$ 可为任意值。因此上述等式成立的充要条件是如果码字X与码字Z的某一位的码元相同,那么码字Y的该位的码元也与X的对应位的码元相同。

---
#### 9-9

> 方阵码:计算机系统内部各部件之间交换数据常常是成块进行,这些数据排成方阵,我们对每一行,每一列都配上一位
> 奇(偶)校验位,这种码称为方阵码。以字长为 5 的 10 个码字为一组,如表 9-8 所示,分析它的检错,纠错能力。
> 表 9-8
> |           |   |   |   | 码 |   |   | 字 | Š |   |    | 组偶校验 |
> |-----------|---|---|---|---|---|---|---|---|---|----|------|
> |           | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 |
> | 低位 c1     | 0 | 0 | 1 | 1 | 0 | 1 | 1 | 0 | 1 | 1  |
> | $c_2$     | 1 | 0 | 1 | 1 | 0 | 0 | 1 | 1 | 0 | 1  |
> | $c_3$     | 1 | 0 | 0 | 1 | 1 | 1 | 0 | 0 | 0 | 1  |
> | C4        | 0 | 1 | 1 | 0 | 0 | 0 | 0 | 1 | 0 | 1  |
> | 高位 c5     | 1 | 1 | 1 | 1 | 0 | 1 | 0 | 0 | 0 | 1  |
> | 码字偶校验位 c6 | 1 | 0 | 0 | 0 | 1 | 1 | 0 | 0 | 1 | 1  |

**解**：

该数据组共有  $6 \times 11 = 66$  位,其中信息位为  $5 \times 10 = 50$ ,校验位为 16 位。用  $a_{ij}$ 表示 i 行 j 列的数。

(1) 一位出错。如  $a_{37}$ 出错,由 0 变成 1,那么第三行中"1"的数目由偶数(6)变成奇数(7),第七列中"1"的数目由偶数(2)变成奇数(3)。出错位就在"1"的数目为奇数的行和列的相交处,因此,可以纠 1 错。
(2) 两位出错。
a) 两位出错位在同一行(列),该行(列)的"I"的数目奇偶性不变,而这两个出错位所在的两列(行),改变了"I"的数目的奇偶性,由偶变奇。例如  $a_{34}$ , $a_{37}$ 出错,第三行仍含偶数个 1,第四、七列含有奇数个 1,能检 2 错。但由于  $a_{24}$ , $a_{27}$ 出错,也只改变第四、七列的奇偶性,不能纠 2 错。
b) 两位出错位不在同一行也不在同一列。例如  $a_{24}$ ,  $a_{37}$  出错,那么第二、三行与第四、七列要改变"1"的数目的奇偶性,能检2 错。但是, $a_{27}$ 与  $a_{34}$ 出错,其出错的现象相同,不能纠2 错。
(3) 三位出错。
a) 三个出错位在同一行(列),那么该行(列)及出错位所在的 三列(行)的"1"的数目由偶变奇,能检3错。
b) 两个出错位在同一行(列),另一个出错位在另一行(列),

<sup>[</sup>注] 和式中两个括弧式之间的"十"是普通加号,每个括弧式内的"十"是模 2 和,以下同。

那么后一行(列)的"1"的数目由偶变奇。再者,如果这三个出错位在不同的三列(行),就有三列(行)的"1"的数目由偶变奇。如果这三个出错位中有两位在同一列(行),另一位在另一列(行),后一列(行)的"1"的数目由偶变奇,能检 3 错。

c) 三个出错位中任意两个不在同一行也不在同一列,那么就有三行及三列的"1"的数目由偶变奇,能检3错。

但是, $a_{34}$ 、 $a_{39}$ 和  $a_{14}$ 三位同时出错,使第一行、第九列的"1"的数目由偶变奇,这与  $a_{19}$ 一位出错的现象相同,不能纠 3 错。

(4) 四位出错。如果四位出错位的位置恰好组成一矩形,例如  $a_{14}$ , $a_{19}$ , $a_{34}$ , $a_{39}$ 四位出错,各行,各列的"1"的数目未改变奇偶性,不能检 4 错。

总结上述,方阵码的检错与纠错能力如表 9-9 所示。

| "1"的数目 | 改变奇偶性 | 11. Ett. 62: Wer | 11 to the the 1994 |
|--------|-------|------------------|--------------------|
| 行 数    | 列 数   | 一出错位数            | 出错位置               |
| 1      | 1     | 1                | 出错行与出错列交叉处         |
| 0      | 2     |                  |                    |
| 2      | 0     | 2                |                    |
| 2      | 2     |                  |                    |
| 1      | 3     |                  |                    |
| 3      | 1     | 3                |                    |
| 3      | 3     |                  |                    |

表 9-9

---
#### 9-10 证明字长不超过 2k 的码不能纠 k 个错。字长不超过 k 的码不能检 k 个错。 【9-2.(3)】

字长不超过 2k 的码的极小距不超过 2k,由定理 9-2.4 可知,不能纠 k 个错。

字长不超过 k 的码的极小距不超过 k,由定理 9-2.3 可知,不能检 k 个错。

---
#### 9-11

> 给定线性码 C,如果  $d_{\min}(C) \geqslant k + k' + 1(k' \geqslant k)$ ,则码・546・
> C能查 k'个错且能纠 k 个错。请构造一个能纠单错且能查两个错的线性码。

**证明**：

$d_{\min}(C) \geqslant k + k' + 1 \geqslant k' + 1$ ,故 C 能查 k'个错。因为  $k' \geqslant k, d_{\min}(C) \geqslant k + k' + 1 \geqslant 2k + 1$ ,故 C 能纠 k 个错。

给定码  $C=\{0000,1111\}$ ,其中前三位  $c_1$ , $c_2$ , $c_3$  是信息位,第四位  $c_4$  是校验位,显然, $c_1+c_2+c_3+c_4=0$ ,是线性码。

$$d_{\min}(C) = 4 = 1 + 2 + 1, k = 1, k' = 2$$

能查两个错,纠单错。

---
#### 9-12

> 设 C 是一个线性分组码,它同时具有偶数重量和奇数 重量的码字。证明:偶数重量码字的数目等于奇数重量码字的 数目。

**证明**：

给定线性分组码 C,字长 n 位。任取码字 A, $B \in C$ , $A = a_1 a_2 \cdots a_n$ , $B = b_1 b_2 \cdots b_n$

因为码 C 是线性码,

$$a_1 + a_2 + \cdots + a_n = 0, b_1 + b_2 + \cdots + b_n = 0$$

两式相加得

$$(a_1+b_1)+(a_2+b_2)+\cdots+(a_n+b_n)=0$$

所以

$A+B\in C$

线性码中任两个码字之和也是该码中的码字。

设码字
$$A 与 B$$
中有  $a_{i_1} = b_{i_1} = 1, \dots, a_{i_k} = b_{i_k} = 1,$ 显然  $W(A+B) = W(A) + W(B) - 2k$

令 C 中重量为偶数的码字组成集合  $X = \{X_1, \dots, X_i\}$ ;重量为 奇数的码字组成集合  $Y = \{Y_1, \dots, Y_j\}$ 。那么, $Y_1 + X_1$ , $Y_1 + X_2$ ,…, $Y_1 + X_i \in C$ ,且对于  $1 \le h \le i$  有

$$W(Y_1+X_h)=W(Y_1)+W(X_h)-2m$$

m 是码字  $Y_1$  与  $X_h$  中同为 1 的码元的数目, $W(Y_1)$  是奇数, $W(X_h)$ 和 2m 是偶数, $W(Y_1+X_h)$  是奇数。因此, $Y_1+X_1$ ,…, $Y_1+X_i\in Y$ , $i\leq j$ 。

同理, $Y_1+Y_1,\dots,Y_1+Y_i\in X,j\leqslant i$ 。

由此可知,i=j,码 C中重量为偶数的码字数目等于重量为奇

数的码字数目。

---
#### 9-13

> 构造一个包含 8 位信息位且能纠 1 错的线性码。

**解**：

满足  $8 \le 2^k - k - 1$  的 k 的最小值为 k = 4,需要增加四位校验位。构成一致校验矩阵 H 可从长四位的十六个向量中除去零向量和四个单位向量还余下的十一个向量中任取八个即可,共有 $\binom{11}{8} = 165$  个。下列都是(12,8)线性分组码的一致校验矩阵。

$$H_{1} = \begin{pmatrix} 1 & 1 & 1 & 0 & 0 & 0 & 1 & 0 & 1 & 0 & 0$$

他们对应的(12,8)码从略。

---
#### 9-14 考察一个(8,4)码 C,它的校验位  $a_5$ , $a_6$ , $a_7$ , $a_8$  满足下列方程:

$$a_5 = a_1 + a_2 + a_4$$

$$a_6 = a_1 + a_3 + a_4$$

$$a_7 = a_1 + a_2 + a_3$$

$$a_8 = a_2 + a_3 + a_4$$

其中 $a_1,a_2,a_3,a_4$ 为信息位。求出这个码的一致校验矩阵。证明  $\min W(X) = 4$ ,且不存在可纠 2 错的(8,4)线性分组码。  $X \in C$   $X \neq 0$

[9-3.(3)]

上述方程可改写为矩阵形式:

$$(a_1 \ a_2 \ a_3 \ a_4 \ a_5 \ a_6 \ a_7 \ a_8) \begin{pmatrix} 1 & 1 & 1 & 0 \\ 1 & 0 & 1 & 1 \\ 0 & 1 & 1 & 1 \\ 1 & 1 & 0 & 1 \\ 1 & 0 & 0 & 0 \\ 0 & 1 & 0 & 0 \\ 0 & 0 & 1 & 0 \\ 0 & 0 & 0 & 1 \end{pmatrix} = \mathbf{0}$$

一致校验矩阵为:

$$H = \begin{pmatrix} 1 & 1 & 0 & 1 & 1 & 0 & 0 & 0 \\ 1 & 0 & 1 & 1 & 0 & 1 & 0 & 0 \\ 1 & 1 & 1 & 0 & 0 & 0 & 1 & 0 \\ 0 & 1 & 1 & 1 & 0 & 0 & 0 & 1 \end{pmatrix}$$

矩阵 H 中无零列向量,且任意两个,三个列向量之和不等于零向量。而第一、二,六和八列向量之和为零向量,所以,

$$\min_{\substack{X \in C \\ X \neq 0}} W(X) = 4$$

因为(8,4)线性分组码的一致校验矩阵 H 为:

$$H=(Q_{4\times 4} I_4)$$

由于  $Q_{4\times4}$ 中四个列向量都是四维,四维列向量中只有一个列向量,其四个分量全为 1,所以, $Q_{4\times4}$ 中至少有一个列向量,它的四个分量不能全为 1,设它为 $(a_1,a_2,a_3,a_4)^T$ 。如有  $a_1=0$ , $a_2=a_3=a_4=1$ ,则

$$\begin{pmatrix} a_1 \\ a_2 \\ a_3 \\ a_4 \end{pmatrix} + \begin{pmatrix} 0 \\ 1 \\ 0 \\ 0 \end{pmatrix} + \begin{pmatrix} 0 \\ 0 \\ 1 \\ 0 \end{pmatrix} + \begin{pmatrix} 0 \\ 0 \\ 0 \\ 1 \end{pmatrix} = \begin{pmatrix} 0 \\ 0 \\ 0 \\ 0 \\ 0 \end{pmatrix}$$

H 矩阵中和为零的列向量数≤4,即 W(C)≤4,不能纠2 错。

---
#### 9-15

> 写出一致校验矩阵 H1
> $$H_1 = \begin{pmatrix} 1 & 0 & 0 & 1 & 0 & 0 & 0 \\ 1 & 1 & 0 & 0 & 1 & 0 & 0 \\ 0 & 1 & 1 & 0 & 0 & 1 & 0 \\ 0 & 0 & 1 & 0 & 0 & 0 & 1 \end{pmatrix}$$
> 的(7,3)码中所有码字,并求出此码中非零码字的最小重量。
> [9-3.(4)]

**解**：

对应  $H_1$  的(7,3)码的校验位  $a_4$ , $a_5$ , $a_6$ , $a_7$  与信息位  $a_1$ , $a_2$ , $a_3$  之间有关系式:

$$\begin{cases} a_4 = a_1 \\ a_5 = a_1 + a_2 \\ a_6 = a_2 + a_3 \\ a_7 = a_3 \end{cases}$$

(7,3)码如表 9-10 所示。

表 9-10

| 码 字            | 信     | 息     | 位     |                | 校     | 硷 位   |            |
|----------------|-------|-------|-------|----------------|-------|-------|------------|
| H T            | $a_1$ | $a_2$ | $a_3$ | a <sub>4</sub> | $a_5$ | $a_6$ | <b>a</b>
| c <sub>1</sub> | 0     | 0     | 0     | 0              | 0     | 0     |
| c <sub>2</sub> | 0     | 0     | 1     | 0              | 0     | 1     |
| c <sub>3</sub> | 0     | 1     | 0     | 0              | 1     | 1     |
| C4             | 0     | 1     | 1     | 0              | 1     | 0     |
| c <sub>5</sub> | 1     | 0     | 0     | 1              | 1     | 0     |
| c <sub>6</sub> | 1     | 0     | 1     | 1              | 1     | 1     |
| C7             | 1     | 1     | 0     | 1              | 0     | 1     |
| c <sub>8</sub> | 1     | 1     | 1     | 1              | 0     | 0     |
非零码字的最小重量为

$$W(C_2) = W(C_3) = W(C_5) = 3$$

---
#### 9-16 写出习题 9-13 中一致校验矩阵  $H_1$ ,  $H_2$  和  $H_3$  所对应的生成矩阵。

$\mathbf{H}_1$ ,  $H_2$  和  $H_3$  所对应的生成矩阵  $G_1$ ,  $G_2$  和  $G_3$  为:

$$G_1 = \begin{vmatrix} 1 & 0 & 0 & 0 & 0 & 0 & 0 & 0 & 1 & 1 &$$

---
#### 9-17

> 求出海明码中校验位数不超过信息位数的最小信息 位数。

**解**：

信息位长 m 位,校验位长 k 位,他们满足不等式  $m \le 2^k - k - 1$

且还要求满足  $k \leq m$ ,最小的 m 等于 3。

---
#### 9-18

> 给定字长n位的海明码C,证明
> $\underbrace{e_{j}\notin C\cup(e_{1}\oplus C)\cup(e_{2}\oplus C)\cup\cdots\cup(e_{j-1}\oplus C)}_{n}$ 其中  $e_{i}=\underbrace{0\cdots010\cdots0}_{n}$ ,1 恰在第 i 位。

**证明**：

因为海明码 C 能纠单错且它是群码,所以 C 中非零码字的重量 $\geqslant 3$ ,而  $W(e_i)=1,e_i\notin C$ 。如果

$$e_i \in e_k \oplus C \quad (1 \leq k \leq j-1)$$

则有  $X \in C$ ,使

$$e_i = e_k \oplus X, X = e_i \oplus e_k, W(X) = 2$$

与C中非零码字的重量 $\geq$ 3矛盾。故

$$e_i \notin C \cup (e_1 \oplus C) \cup (e_2 \oplus C) \cup \cdots \cup (e_{i-1} \oplus C)$$

同理可证

$$e_j \notin C \bigcup (\bigcup_{i \neq j} (e_i \oplus C))$$

---
#### 9-19

> 给定(7,4)码,它的一致校验矩阵是
> $$H = \begin{pmatrix} 1 & 1 & 1 & 0 & 1 & 0 & 0 \\ 1 & 1 & 0 & 1 & 0 & 1 & 0 \\ 1 & 0 & 1 & 1 & 0 & 0 & 1 \end{pmatrix}$$
> 构造译码表,并求接收字 1000111, 0110010 和 1111111 的发送字。

**解**：

该(7,4)码如表 9-11 所示,译码表如表 9-12 所示。接收 字 1000111, 0110010, 1111111 的发送字分别为 1000111, 0110011,

表 9-11

| 1     | 言』    | 包包                    | Ì  | 校              | 验                     | 位  | 1     | 言!    | 息化                    | Ĭ  | 校              | 验  | 位  |
|-------|-------|-----------------------|----|----------------|-----------------------|----|-------|-------|-----------------------|----|----------------|----|----|
| $c_1$ | $c_2$ | <i>c</i> <sub>3</sub> | C4 | C <sub>5</sub> | <i>C</i> <sub>6</sub> | c7 | $c_1$ | $c_2$ | <i>c</i> <sub>3</sub> | C4 | c <sub>5</sub> | C6 | CI |
| 0     | 0     | 0                     | 0  | 0              | 0                     | 0  | 1     | 0     | 0                     | 0  | 1              | 1  |
| 0     | 0     | 0                     | 1  | 0              | 1                     | 1  | 1     | 0     | 0                     | 1  | 1              | 0  |
| 0     | 0     | 1                     | 0  | 1              | 0                     | 1  | 1     | 0     | 1                     | 0  | 0              | 1  |
| 0     | 0     | 1                     | 1  | 1              | 1                     | 0  | 1     | 0     | 1                     | 1  | 0              | 0  |
| 0     | 1     | 0                     | 0  | 1              | 1                     | 0  | 1     | 1     | 0                     | 0  | 0              | 0  |
| 0     | 1     | 0                     | 1  | 1              | 0                     | 1  | 1     | 1     | 0                     | 1  | 0              | 1  |
| 0     | 1     | 1                     | 0  | 0              | 1                     | 1  | 1     | 1     | 1                     | 0  | 1              | 0  |
| 0     | 1     | 1                     | 1  | 0              | 0                     | 0  | 1     | 1     | 1                     | 1  | 1              | 1  |
| 0000000                                             | 0001011                                             | 0010101                                             | 0011110                                             | 0100110                                             | 0101101                                             | 0110011                                             | 0111000                                             |
|-----------------------------------------------------|-----------------------------------------------------|-----------------------------------------------------|-----------------------------------------------------|-----------------------------------------------------|-----------------------------------------------------|-----------------------------------------------------|-----------------------------------------------------|
| 0000001                                             | 0001010                                             | 0010100                                             | 0011111                                             | 0100111                                             | 0101100                                             | 0110010                                             | 0111001                                             |
| 0000010                                             | 0001001                                             | 0010111                                             | 0011100                                             | 0100100                                             | 0101111                                             | 0110001                                             | 0111010                                             |
| 0000100                                             | 0001111                                             | 0010001                                             | 0011010                                             | 0100010                                             | 0101001                                             | 0110111                                             | 0111100                                             |
| 0001000                                             | 0000011                                             | 0011101                                             | 0010110                                             | 0101110                                             | 0100101                                             | 0111011                                             | 0110000                                             |
| 0010000                                             | 0011011                                             | 0000101                                             | 0001110                                             | 0110110                                             | 0111101                                             | 0100011                                             | 0101000                                             |
| -0100000                                            | 0101011                                             | 0110101                                             | 0111110                                             | 0000110                                             | 0001101                                             | 0010011                                             | 0011000                                             |
| 1000000                                             | 1001011                                             | 1010101                                             | 1011110                                             | 1100110                                             | 1101101                                             | 1110011                                             | 1111000                                             |
|                                                     |                                                     |                                                     |                                                     |                                                     |                                                     |                                                     |                                                     |
| 1000111                                             | 1001100                                             | 1010010                                             | 1011001                                             | 1100001                                             | 1101010                                             | 1110100                                             | 1111111                                             |
| 1000111<br>1000110                                  | 1001100<br>1001101                                  | 1010010<br>1010011                                  | 1011001<br>1011000                                  | 1100001<br>1100000                                  | 1101010<br>1101011                                  | 1110100<br>1110101                                  | 1111111<br>1111110                                  |
|                                                     |                                                     |                                                     |                                                     |                                                     |                                                     |                                                     |                                                     |
| 1000110                                             | 1001101                                             | 1010011                                             | 1011000                                             | 1100000                                             | 1101011                                             | 1110101                                             | 1111110                                             |
| 1000101<br>1000101                                  | 1001101<br>1001110                                  | 1010011<br>1010000                                  | 1011000<br>1011011                                  | 1100000<br>1100011                                  | 1101011<br>1101000                                  | 1110101<br>1110110                                  | 1111110<br>1111101                                  |
| 1000110<br>1000101<br>1000011                       | 1001101<br>1001110<br>1001000                       | 1010011<br>1010000<br>1010110                       | 1011000<br>1011011<br>1011101                       | 1100000<br>1100011<br>1100101                       | 1101011<br>1101000<br>1101110                       | 1110101<br>1110110<br>1110000                       | 1111110<br>1111101<br>1111011                       |
| 1000110<br>1000101<br>1000011<br>1001111            | 1001101<br>1001110<br>1001000<br>1000100            | 1010011<br>1010000<br>1010110<br>1011010            | 1011000<br>1011011<br>1011101<br>1010001            | 1100000<br>1100011<br>1100101<br>1101001            | 1101011<br>1101000<br>1101110<br>1100010            | 1110101<br>1110110<br>1110000<br>1111100            | 1111110<br>1111101<br>1111011<br>1110111            |
| 1000110<br>1000101<br>1000011<br>1001111<br>1010111 | 1001101<br>1001110<br>1001000<br>1000100<br>1011100 | 1010011<br>1010000<br>1010110<br>1011010<br>1000010 | 1011000<br>1011011<br>1011101<br>1010001<br>1001001 | 1100000<br>1100011<br>1100101<br>1101001<br>1110001 | 1101011<br>1101000<br>1101110<br>1100010<br>1111010 | 1110101<br>1110110<br>1110000<br>1111100<br>1100100 | 1111110<br>1111101<br>1111011<br>1110111<br>1101111 |

1111111。该码只能单纠错。

---
#### 9-20

> 给定码 C={00000,11111},证明它是一个群码并能纠
> 两个传送错误。构造译码表,确定接收字为 00101,01110,11011,01011 和 11111 的发送字。
> 表 9-13
> | 2                                       |       |
> |-----------------------------------------|-------|
> | 00000                                   | 11111 |
> | 00001                                   | 11110 |
> | 00010                                   | 11101 |
> | 00100                                   | 11011 |
> | 01000                                   | 10111 |
> | 10000                                   | 01111 |
> | 00011                                   | 11100 |
> | 00101                                   | 11010 |
> | 01001                                   | 10110 |
> | 10001                                   | 01110 |
> | 00110                                   | 11001 |
> | 01010                                   | 10101 |
> | 10010                                   | 01101 |
> | 01100                                   | 10011 |
> | 10100                                   | 01011 |
> | 000000000000000000000000000000000000000 |       |
> 11000

**证明**：

因为

$00000 {\bigoplus} 00000 = 11111 {\bigoplus} 11111$

$=000000 \in C$

00000⊕11111=11111⊕00000

$=111111 \in C$

由定理 5-4.7 可知、 $\langle C, \oplus \rangle$  是群码。 $d_{min}(C)$  = 5, 可纠 2 错。译码如表 9-13 所示,00101, 01110, 11011, 01011 和 11111 的发送字分别为 00000, 11111, 11111, 11111 和 11111。

00111

$$a_5 = a_1 + a_2 + a_3 + a_4$$
$a_6 = a_1 + a_2$
$a_7 = a_2 + a_3$
$a_8 = a_3 + a_4$

构造译码表,并求接收字为 00011010,11110000,10000111 **的发** 送字。

译码表如表 9-14 所示,该表的第一行是(8,4)码的各码字。接收字 00011010,11110000,10000111 的发送字分别为 00011001,11110000,10100111。

---
#### 9-22

> 构造出所有字长为 6 的循环码。

**解**：

字长为6的循环码的生成多项式是 $x^6+1$ 的因式。由于

$$x^6+1=(x+1)^2(x^2+x+1)^2$$

生成多项式有

$$g_1(x) = x + 1$$

和

$$g_2(x) = x^2 + x + 1$$

对应  $g_1(x)$ 的循环码的码多项式为:

$$C_{1}(x) = (m_{0} + m_{1}x + m_{2}x^{2} + m_{3}x^{3} + m_{4}x^{4})(1+x)$$

$$= m_{0} + (m_{0} + m_{1})x + (m_{1} + m_{2})x^{2}$$

$$+ (m_{2} + m_{3})x^{3} + (m_{3} + m_{4})x^{4}$$

$$+ m_{4}x^{5}$$

该循环码如表 9-15 所示。

对应  $g_2(x)$ 的循环码的码多项式为:

$$C_{2}(x) = (m_{0} + m_{1}x + m_{2}x^{2} + m_{3}x^{3})(1 + x + x^{2})$$

$$= m_{0} + (m_{0} + m_{1})x + (\dot{m}_{0} + m_{1} + m_{2})x^{2}$$

$$+ (m_{1} + m_{2} + m_{3})x^{3} + (m_{2} + m_{3})x^{4}$$

$$+ m_{3}x^{5}$$

表 9-14

| 00000000 | 00011001 | 00101011 | 00110010 | 01001110 | 01010111 | 01100101 | 01111100  |
|----------|----------|----------|----------|----------|----------|----------|-----------|
| 0000001  | 00011000 | 00101010 | 00110011 | 01001111 | 01010110 | 01100100 | 01111101  |
| 00000010 | 00011011 | 00101001 | 00110000 | 01001100 | 01010101 | 01100111 | 01111110  |
| 00000100 | 00011101 | 00101111 | 00110110 | 01001010 | 01010011 | 01100001 | 01111000  |
| 00001000 | 00010001 | 00100011 | 00111010 | 01000110 | 01011111 | 01101101 | 01110100  |
| 00010000 | 00001001 | 00111011 | 00100010 | 01011110 | 01000111 | 01110101 | 01101100  |
| 00100000 | 00111001 | 00001011 | 00010010 | 01101110 | 01110111 | 01000101 | 01011100  |
| 01000000 | 01011001 | 01101011 | 01110010 | 00001110 | 00010111 | 00100101 | 00111100  |
| 10000000 | 10011001 | 10101011 | 10110010 | 11001110 | 11010111 | 11100101 | 11111100  |
| 00000011 | 00011010 | 00101000 | 00110001 | 01001101 | 01010100 | 01100110 | 01111111  |
| 00000110 | 00011111 | 00101101 | 00110100 | 01001000 | 01010001 | 01100011 | 01111010  |
| 01100000 | 01111001 | 01001011 | 01010010 | 00101110 | 00100111 | 00000101 | 00011100  |
| 00001010 | 00010011 | 00100001 | 00111000 | 01000100 | 01011101 | 01100111 | 01110110  |
| 10100000 | 10111001 | 10001011 | 10010010 | 11101110 | 11110111 | 11000101 | 11011100  |
| 10000001 | 10011000 | 10101010 | 10110011 | 11001111 | 11010110 | 11100100 | 111111101 |
| 00100100 | 00111101 | 00001111 | 00010110 | 01101010 | 01110011 | 01000001 | 01011000  |
| 10001100 | 10010101 | 10100111 | 10111110 | 11000010 | 11011011 | 11101001 | 11110000  |
| 10001101 | 10010100 | 10100110 | 10111111 | 11000011 | 11011010 | 11101000 | 11110001  |
| 10001110 | 10010111 | 10100101 | 10111100 | 11000000 | 11011001 | 11101011 | 11110010  |
| 10001000 | 10010001 | 10100011 | 10111010 | 11000110 | 11011111 | 11101101 | 11110100  |
| 10000100 | 10011101 | 10101111 | 10110110 | 11001010 | 11010011 | 11100001 | 11111000  |
| 10011100 | 10000101 | 10110111 | 10101110 | 11010010 | 11001011 | 11111001 | 11100000  |
| 10101100 | 10110101 | 10000111 | 10011110 | 11100010 | 11111011 | 11001001 | 11010000  |
| 11001100 | 11010101 | 11100111 | 11111110 | 10000010 | 10011011 | 10101001 | 10110000  |
| 00001100 | 00010101 | 00100111 | 00111110 | 01000010 | 01011011 | 01101001 | 01110000  |
| 10001111 | 10010110 | 10100100 | 10111101 | 11000001 | 11011000 | 11101010 | 11110011  |
| 10001010 | 10010011 | 10100001 | 10111000 | 11000100 | 11011101 | 11101111 | 11110110  |
| 11101100 | 11110101 | 11000111 | 11011110 | 10100010 | 10111011 | 10001001 | 10010000  |
| 10000110 | 10011111 | 10101101 | 10110100 | 11001000 | 11010001 | 11100011 | 11111010  |
| 00101100 | 00110101 | 00000111 | 00011110 | 01100010 | 01111011 | 01001001 | 01010000  |
| 00001101 | 00010100 | 00100110 | 00111111 | 01000011 | 01011010 | 01101000 | 01110001  |
| 10101000 | 10110001 | 10000011 | 10011010 | 11100110 | 11111111 | 11001101 | 11010100  |
|          |          |          |          |          |          |          |           |

表 9-15

|       | 信     | 息     | 位     |       |                | 码  | 码                     |    | 字          |                       |
|-------|-------|-------|-------|-------|----------------|----|-----------------------|----|------------|-----------------------|
| $m_0$ | $m_1$ | $m_2$ | $m_3$ | $m_4$ | c <sub>1</sub> | c2 | <i>c</i> <sub>3</sub> | C4 | <i>C</i> 5 | <i>c</i> <sub>6</sub> |
| 0     | 0     | 0     | 0     | 0     | 0              | 0  | 0                     | 0  | 0          |
| 0     | 0     | 0     | 0     | 1     | 0              | 0  | 0                     | 0  | 1          |
| 0     | 0     | 0     | 1     | 0     | 0              | 0  | 0                     | 1  | 1          |
| 0     | 0     | 0     | 1     | 1     | 0              | 0  | 0                     | 1  | 0          |
| 0     | 0     | 1     | 0     | 0     | 0              | 0  | 1                     | 1  | 0          |
| 0     | 0     | 1     | 0     | 1     | 0              | 0  | 1                     | 1  | 1          |
| 0     | 0     | 1     | 1     | 0     | 0              | 0  | 1                     | 0  | 1          |
| 0     | 0     | 1     | 1     | 1     | 0              | 0  | 1                     | 0  | 0          |
| 0     | 1     | 0     | 0     | 0     | 0              | 1  | 1                     | 0  | 0          |
| 0     | 1     | 0     | 0     | 1     | 0              | 1  | 1                     | 0  | 1          |
| 0     | 1     | 0     | 1     | 0     | 0              | 1  | 1                     | 1  | 1          |
| 0     | 1     | 0     | 1     | 1     | 0              | 1  | 1                     | 1  | 0          |
| 0     | 1     | 1     | 0     | 0     | 0              | 1  | 0                     | 1  | 0          |
| 0     | 1     | 1     | 0     | 1     | 0              | 1  | 0                     | 1  | 1          |
| 0     | 1     | 1     | 1     | 0     | 0              | 1  | 0                     | 0  | 1          |
| 0     | 1     | 1     | 1     | 1     | 0              | 1  | 0                     | 0  | 0          |
| 1     | 0     | 0     | 0     | 0     | 1              | 1  | 0                     | 0  | 0          |
| 1     | 0     | 0     | 0     | 1     | 1              | 1  | 0                     | 0  | 1          |
| 1     | 0     | 0     | 1     | 0     | 1              | 1  | 0                     | 1  | 1          | .
| 1     | 0     | 0     | 1     | 1     | 1              | 1  | 0                     | 1  | 0          |
| 1     | 0     | 1     | 0     | 0     | 1              | 1  | 1                     | 1  | 0          |
| 1     | 0     | 1     | 0     | 1     | 1              | 1  | 1                     | 1  | 1          |
| 1     | 0     | 1     | 1     | 0     | 1              | 1  | 1                     | 0  | 1          |
| 1     | 0     | 1     | 1     | 1     | 1              | 1  | 1                     | 0  | 0          |
| 1     | 1     | 0     | 0     | 0     | 1              | 0  | 1                     | 0  | 0          |
| 1     | 1     | 0     | 0     | 1     | 1              | 0  | 1                     | 0  | 1          |
| 1     | 1     | 0     | 1     | 0     | 1              | 0  | 1                     | 1  | 1          |
| 1     | 1     | 0     | 1     | 1     | 1              | 0  | 1                     | 1  | 0          |
| 1     | 1     | 1     | 0     | 0     | 1              | 0  | 0                     | 1  | 0          |
| 1     | 1     | 1     | 0     | 1     | 1              | 0  | 0                     | 1  | 1          |
| 1     | 1     | 1     | 1     | 0     | 1              | 0  | 0                     | 0  | 1          |
| 1     | 1     | 1     | 1     | 1     | 1              | 0  | 0                     | 0  | 0          |
表 9-16

|       | 信     | 息     | Ž     |                | ě  | 4                     | <u>*</u> | 字          |   |
|-------|-------|-------|-------|----------------|----|-----------------------|----------|------------|---|
| $m_0$ | $m_1$ | $m_2$ | $m_3$ | c <sub>1</sub> | C2 | <i>c</i> <sub>3</sub> | C4       | <b>c</b> 5 | C |
| 0     | 0     | 0     | 0     | 0              | 0  | 0                     | 0        | 0          |
| 0     | 0     | 0     | 1     | 0              | 0  | 0                     | 1        | 1          |
| 0     | 0     | 1     | 0     | 0              | 0  | 1                     | 1        | 1          |
| 0     | 0     | 1     | 1     | 0              | 0  | 1                     | 0        | 0          |
| 0     | 1     | 0     | 0     | 0              | 1  | 1                     | 1        | 0          |
| 0     | 1     | 0     | 1     | 0              | 1  | 1                     | 0        | 1          |
| 0     | 1     | 1     | 0     | 0              | 1  | 0                     | 0        | 1          |
| 0     | 1     | 1     | 1     | 0              | 1  | 0                     | 1        | 0          |
| 1     | 0     | 0     | 0     | 1              | 1  | 1                     | 0        | 0          |
| 1     | 0     | 0     | 1     | 1              | 1  | 1                     | 1        | 1          |
| 1     | 0     | 1     | 0     | 1              | 1  | 0                     | 1        | 1          |
| 1     | 0     | 1     | 1     | 1              | 1  | 0                     | 0        | 0          |
| 1     | 1     | 0     | 0     | 1              | 0  | 0                     | 1        | 0          |
| 1     | 1     | 0     | 1     | 1              | 0  | 0                     | 0        | 1          |
| 1     | 1     | 1     | 0     | 1              | 0  | 1                     | 0        | 1          |
| 1     | 1     | 1     | 1     | 1              | 0  | 1                     | 1        | 0          |
该循环码如表 9-16 所示。

---
#### 9-23

> 对于任意正整数 n(≥2),证明(n,n-1)循环码中每一个码字必含有偶数个 1。

**证明**：

(n, n-1)循环码的码多项式 g(x)为一次多项式,

$$g(x)=1+x$$

由定理 9-6.1 可知,任一码多项式 C(x)是 1+x 的倍式,即

$$C(x) = (m_0 + m_1 x + \dots + m_{n-1} x^{n-1}) (1+x)$$

$$= m_0 + (m_0 + m_1) x + \dots + (m_{n-2} + m_{n-1}) x^{n-1}$$

$$+ m_{n-1} x^{n-1}$$

对应的码字为:

$$C=m_0(m_0+m_1)\cdots(m_{n-2}+m_{n-1})m_{n-1}$$

其各位和为:

$$m_0 + (m_0 + m_1) + \cdots + (m_{n-2} + m_{n-1}) + m_{n-1} = 0$$

故 C 中含有偶数个 1。

---
#### 9-24 对于(7,4)循环码 S,它的校验位  $c_s$ ,  $c_6$ ,  $c_7$  与信息位  $c_1$ ,  $c_2$ ,  $c_3$  和  $c_4$  满足下列方程:

$$\begin{pmatrix} c_5 \\ c_6 \\ c_7 \end{pmatrix} = \begin{pmatrix} 1 & 0 & 1 & 1 \\ 1 & 1 & 1 & 0 \\ 0 & 1 & 1 & 1 \end{pmatrix} \begin{pmatrix} c_1 \\ c_2 \\ c_3 \\ c_4 \end{pmatrix}$$

讨论它的一致校验矩阵与生成多项式之间的关系。 【9-5.(3)】

该(7,4)循环码的码字与相应的码多项式如表 9-17 所示。

表 9-17

| 码 字     | 码 多 项 式                                   |  |  |  |  |  |  |
|---------|-------------------------------------------|--|--|--|--|--|--|
| 0000000 | $0=0 \cdot g(x)$                          |  |  |  |  |  |  |
| 0001101 | $x^3 + x^4 + x^6 = x^3 g(x)$              |  |  |  |  |  |  |
| 0010111 | $x^2 + x^4 + x^5 + x^6 = (x^2 + x^3)g(x)$ |  |  |  |  |  |  |
| 0011010 | $x^2 + x^3 + x^5 = x^2 g(x)$              |  |  |  |  |  |  |
| 0100011 | $x+x^5+x^6=(x+x^2+x^3)g(x)$               |  |  |  |  |  |  |
| 0101110 | $x+x^3+x^4+x^5=(x+x^2)g(x)$               |  |  |  |  |  |  |
| 0110100 | $x + x^2 + x^4 = xg(x)$                   |  |  |  |  |  |  |
| 0111001 | $x+x^2+x^3+x^6=(x+x^3)g(x)$               |  |  |  |  |  |  |
| 1000110 | $1+x^4+x^5=(1+x+x^2)g(x)$                 |  |  |  |  |  |  |
| 1001011 | $1+x^3+x^5+x^6=(1+x+x^2+x^3)g(x)$         |  |  |  |  |  |  |
| 1010001 | $1+x^2+x^6=(1+x+x^3)g(x)$                 |  |  |  |  |  |  |
| 1011100 | $1+x^2+x^3+x^4=(1+x)g(x)$                 |  |  |  |  |  |  |
| 1100101 | $1+x+x^4+x^6=(1+x^3)g(x)$                 |  |  |  |  |  |  |
| 1101000 | $1+x+x^3=g(x)$                            |  |  |  |  |  |  |
| 1110010 | $1+x+x^2+x^5=(1+x^2)g(x)$                 |  |  |  |  |  |  |
| 1111111 | $1+x+x^2+x^3+x^4+x^5+x^6=(1+x^2+x^3)g(x)$ |  |  |  |  |  |  |

它的一致校验矩阵为:

558 •

$$H = \begin{pmatrix} 1 & 0 & 1 & 1 & 1 & 0 & 0 \\ 1 & 1 & 1 & 0 & 0 & 1 & 0 \\ 0 & 1 & 1 & 1 & 0 & 0 & 1 \end{pmatrix}$$

对应的生成矩阵为:

$$G = \begin{pmatrix} 1 & 0 & 0 & 0 & 1 & 1 & 0 \\ 0 & 1 & 0 & 0 & 0 & 1 & 1 \\ 0 & 0 & 1 & 0 & 1 & 1 & 1 \\ 0 & 0 & 0 & 1 & 1 & 0 & 1 \end{pmatrix}$$

从上表可知,G 的四行组成四个码字 1000110,0100011,0010111,0001101,其对应的码多项式为 $(1+x+x^2)g(x)$ , $(x+x^2+x^3)g(x)$ , $(x^2+x^3)g(x)$ 和 $x^3g(x)$ ,这四个码多项式是互相线性独立的。

# 参考文献

[1] Aho A. V., J. E. Hopcroft, and J. D. Ullman, "The Design and Analysis of Computer Algorithms", Reading, Mass.: Addison-Weley, 1974
[2] Brualdi, Richard A., "Introduction to Error-Correcting Codes", Prentice-Hall, Inc., 1970
[3] Denning, Peter J., Jack B. Dennis, Joseph E. Qualitz, "Machines, Languages, and Computation", Prentice-Hall, Inc., Englewood Cliffs, New Jersey, 1978
[4] Conald F. Stanat, David F. Mcallister "Discrete Mathematics in Computer Science" Prentice-Hall. Inc., 1977
[5] Erwin Engeler, "Introduction to the Theory of Compution", Academic Press, Inc. 1973
[6] Fred Hennie, "Introduction to Computability", Addison-Wesley Publishing Company, Inc. 1977
[7] Hopcroft, J. E., J. D. Ullman, "Introduction to Automata Theory, Languages, and Computation", Addison-Wesley Publishing Company, Inc., 1979
[8] Judith L. Gersting "Mathematical Structures For Computer Science"
W. H. Freeman and Company 1982
[9] Kohavi, Zvi, and Azaria Paz, "Theory of Machines and Computations", Academic Press New York and London, 1971
[10] Lin, Shu, "An Introduction to Error-Correcting Codes", Prentice-Hall, Inc., 1970
[11] Manna, Zohar, "Mathematical Theory of Computation", McGraw-Hill, 1974
[12] Marek, Wiktor "Elements of logic and foundations of mathematics in Problems" PWN-polish Scientific Publishers-Warszawa 1982
[13] Menry B. Laufer "Discrete Mathematics and Applied Modern Algebra", 1984 by PWS Publishers.
[14] Sigler L. E. "Exercises in Set Theory" Springer-Verlag New York560

1974

[15] Tramblay J. P. & R. Manohar "Discrete Mathematical Structures with Applications to Computer Science", 1975 by McGraw-Hill, Inc.
[16] William J. Gilbert "Modern Algebra with Applications", 1976 by John Wiley & Sons, Inc.
[17] 左孝凌,李为慥,刘永才编著. 离散数学. 上海:上海科学技术文献出版社,1982

![](_page_34_Figure_0.jpeg)

---

LinAster
SE10009 Discrete Mathematics, CQU
