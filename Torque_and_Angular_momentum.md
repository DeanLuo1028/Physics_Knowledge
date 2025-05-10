# **力矩與角動量**

---

## 🔹 **前言**
力矩與角動量是轉動力學的核心觀念，與「力與動量」在直線運動中的關係類似。

---

## 🔹 **一、力矩（Torque）**

### 1. 定義：

力矩是「力使物體轉動」的能力，就像力使物體直線加速一樣。

$$
\boldsymbol{\tau} = \boldsymbol{r} \times \boldsymbol{F}
$$

若考慮大小（純量）：

$$
\tau = r F \sin \theta
$$

其中：

* $\tau$： 力矩（單位：N·m）
* $r$： 力作用點與轉軸的距離（向量或純量）
* $F$： 力的大小
* $\theta$： $\boldsymbol{r}$ 和 $\boldsymbol{F}$ 之間的夾角

📝 **最大力矩發生在力與位移垂直（θ = 90°）時。**

---

### 2. 右手法則（方向判定）

* 手指指向 $\boldsymbol{r}$，
* 彎向 $\boldsymbol{F}$，
* 大拇指指的方向，就是 $\boldsymbol{\tau}$ 的方向（即旋轉軸方向）。

---

## 🔹 **二、角動量（Angular Momentum）**

### 1. 定義：

角動量是描述「轉動狀態」的物理量，對應直線運動的動量 $\boldsymbol{p} = m\boldsymbol{v}$。

$$
\boldsymbol{L} = \boldsymbol{r} \times \boldsymbol{p} = \boldsymbol{r} \times m\boldsymbol{v}
$$

如果是繞固定軸旋轉的剛體，則：

$$
L = I \omega
$$

其中：

* $L$：角動量（單位：kg·m²/s）
* $I$：轉動慣量（moment of inertia）
* $\omega$：角速度

---

## 🔹 **三、力矩與角動量的關係**

就像 $F = \frac{dp}{dt}$（力與動量），

轉動中有：

$$
\boldsymbol{\tau} = \frac{d\boldsymbol{L}}{dt}
$$

📌 意義：**力矩會改變角動量**。

---

## 🔹 **四、角動量守恆定律**

若**淨外力矩為零**，則：

$$
\frac{d\boldsymbol{L}}{dt} = 0 \Rightarrow \boldsymbol{L} = \text{常數}
$$

這就是**角動量守恆**！

✅ 常見應用：

* 花式溜冰選手收手轉得更快（ $I\downarrow \Rightarrow \omega\uparrow$）
* 行星繞太陽運動，近日點速度快、遠日點速度慢（開普勒第二定律的推論）

---

## 🔹 **五、轉動慣量（I）的基本概念**

轉動慣量是質量分佈對轉動的「慣性」：

$$
I = \sum m_i r_i^2 \quad \text{（離散）}, \quad \text{或} \quad I = \int r^2\,dm \quad \text{（連續）}
$$

轉動慣量（Moment of Inertia）是「物體轉動時的慣性大小」，類似直線運動中的「質量」。

* 質量大 → 不容易推動
* 轉動慣量大 → 不容易轉動

👉 **轉動慣量不只和質量有關，還和質量分布有關！**

舉例：

* 你拿兩個啞鈴，如果一個放在手心、另一個手臂伸直，哪個轉起來比較吃力？
  答：**手臂伸直**，因為質量離旋轉中心遠，轉動慣量就大。

---

## 🔹 **六、常見公式總結：**

| 直線運動                   | 轉動對應                        |
| ---------------------- | --------------------------- |
| $F = ma$               | $\tau = I \alpha$           |
| $p = mv$               | $L = I \omega$              |
| $W = F \cdot d$        | $W = \tau \cdot \theta$     |
| $KE = \frac{1}{2}mv^2$ | $KE = \frac{1}{2}I\omega^2$ |
| 沒外力 $\Rightarrow p$守恆 | 沒外力矩 $\Rightarrow L$守恆 |

---

## 🌟例題：

一名花式溜冰選手原地旋轉時，雙手水平張開，轉速為 $\omega_1 = 2.0\ \text{rad/s}$，其轉動慣量為 $I_1 = 4.0\ \text{kg·m}^2$。
後來她將雙手收進身體，使得轉動慣量變為 $I_2 = 1.6\ \text{kg·m}^2$。

請問：

1. 她轉速變為多少？
2. 她的角動量有沒有變？為什麼？

---

## ✅ 解題：使用**角動量守恆**

題目給的：

* 初始轉動慣量： $I_1 = 4.0$
* 初始角速度： $\omega_1 = 2.0$
* 收手後轉動慣量： $I_2 = 1.6$
* 求收手後的角速度 $\omega_2$
因為選手沒受到外力矩（在地上轉），所以**角動量守恆**：

$$
I_1 \omega_1 = I_2 \omega_2
$$

代入數值：

$$
4.0 \times 2.0 = 1.6 \times \omega_2
\Rightarrow \omega_2 = \frac{8.0}{1.6} = 5.0\ \text{rad/s}
$$

### ✅ 答案：

1. 收手後轉速變成 **5.0 rad/s**
2. **角動量不變**，因為系統沒有外力矩，根據角動量守恆定律！
