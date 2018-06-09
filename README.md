# marth
## 函数的概念
      第1章  函数
    §1 函数的概念
    一、区间、邻域
    自然数集 N
    整数集 Z
    有理数集 Q
    实数集 R
    文章来源：http://www.codelast.com/
    建立数轴后：

    建立某一实数集A与数轴上某一区间对应
    区间：设有数 a,b,a<b ，则称实数集 {x|a<x<b} 为一个开区间，记为 (a,b) 
    即  (a,b)={x|a<x<b} 
    a称为 (a,b) 的左端点，b称为 (a,b) 的右端点。
    a∉(a,b),b∉(a,b)

    闭区间： [a,b]={x|a≤x≤b} 
    a∈[a,b],b∈[a,b] 
    文章来源：http://www.codelast.com/
    半开区间： [a,b)={x|a≤x≤b},a∈[a,b),b∉[a,b) 
    (a,b]={x|a<x≤b},a∈(a,b],b∉(a,b] 
    a，b都是确定的实数，称 (a,b),[a,b),(a,b],[a,b] 为有限区间，“ b−a ”称为区间长度。

    记号：
    +∞ ——正无穷大
    −∞ ——负无穷大

    区间：
    [a,+∞)={x|a≤x} 
    (a,+∞)={x|a<x} 
    (−∞,b]={x|x≤b} 
    (−∞,b)={x|x<b} 
    称为无穷区间（或无限区间）
    文章来源：http://www.codelast.com/

    邻域：设有两个实数 a,δ(δ>0) ，则称实数集 {x|a−δ<x<a+δ} 为点 a 的 δ 邻域，记为 N(a,δ) 

    a 称为 N(a,δ) 的中心， δ>0 称为邻域 N(a,δ) 的半径。

    【正文】
    去心邻域：把 N(a,δ) 的中心点 a 去掉，称为点 a 的去心邻域，记为 N(a^,δ)={x|0<|x−a|<δ}=N(a,δ)∖{a} 
    注：其中， ∖{a} 表示去掉由 a 这一个数组成的数集。

    二、函数概念
    例1. 设圆的半径为 x(x>0) ，它的面积 A=πx2 ，当 x 在 (0,+∞) 内任取一个数值（记为 ∀x∈(0,+∞) ）时，由关系式 A=πx2 就可以确定A的对应数值。
    文章来源：http://www.codelast.com/
    例2. 设有半径为 r 的圆，作圆的内接正 n 边形，每一边对应的圆心角 α=2πn ，周长 Sn=n⋅2rsinπn ，当边数 n 在自然数集 N(n≥3) 任取一个数，通过关系式 Sn=2nrsinπn 就有一个 Sn 对应确定数值。


    函数定义：设有数集 X,Y ， f 是一个确定的对应法则，对 ∀x∈X ，通过对应法则 f 都有唯一的 y∈Y 与 x 对应，记为 x→fy ，或 f(x)=y ，则称 f 为定义在 X 上的函数。
    其中 X 称为 f 的定义域，常记为 Df 。
    X ——自变量， Y ——因变量。
    当 X 遍取 X 中的一切数时，那么与之对应的 y 值构成一个数集 Vf={y|y=f(x),x∈X} ，称 Vf 为函数 f 的值域。
    文章来源：http://www.codelast.com/
    注意：
    （1）一个函数是由 x,y 的对应法则 f 与 x 的取值范围 X 所确定的。把“对应法则 f ”、“定义域”称为函数定义的两个要素。
    例如， y=arcsin(x2+2) 这个式子，由于 x2+2>2 ，而只有当 |x2+2|≤1 时， arcsin 才有意义，因此这个式子不构成函数关系。
    又例如， y=lnx2 与 y=2lnx 不是同一个函数，因为定义域不同。而 y=lnx2 与 y=2ln|x| 是同一个函数，因为定义域相同。

    （2）函数的值域是定义域和对应法则共同确定的。

    （3）确定函数定义域时，注意：若函数有实际意义，需依据实际问题是否有意义来确定。
    若函数不表示某实际问题，则定义域为自变量所能取得的使函数 y=f(x) 成立的一切实数所组成的数值。
    函数的几何意义：设函数 y=f(x) 定义域为 Df ， ∀x∈Df ，对应函数值 y=f(x) 在 XOY 平面上得到点 (x,y) ，当 x 遍取 Df 中一切实数时，就得到点集 P={(x,y)|y=f(x),x∈Df} 。点集 P 称为函数 y=f(x) 的图形。
    文章来源：http://www.codelast.com/
    三、函数的几个简单性质
    1. 函数的有界性
    若 ∃M>0,s.t.|f(x)|≤M,x∈I ，则称 y=f(x) 在区间 I 上有界。否则称 f(x) 在 I 上无界。
    注： s.t. 是“使得，满足于”的意思， I 表示某个区间。
    例如， y=sinx 在 I=(−∞,+∞) )上是有界的（因为 |sinx|≤1,x∈(−∞,+∞) ）。
    又如， y=1x2+1 在 (−∞,+∞) 上有界。

    对任何正数 M>0 （无论多么大），总 ∃x1∈I,s.t.|f(x1)|>M ，则称 f(x) 在 I 上无界。
    例如， y=1x 在 (0,1) 内无界。
    证明：
    对给定的 M>0 （不妨设 M>1 ），无论M多么大，必存在 x1=1/2M∈(0,1) ，使 f(x1)=1/1/2M=2M>M 
    函数的上界、下界：若 ∃M （不局限于正数）， s.t.f(x)≤M,∀x∈I ，则称 f(x) 在区间 I 上有界。任何一个数 N>M ， N 也是 f(x) 的一个上界。
    若 ∃P,s.t.f(x)≥P,∀x∈I ，则称 f(x) 在区间 I 上有下界。若 Q<P ，则 Q 也是一个下界。

    f(x) 在区间 I 上有界 ⇔f(x) 在 I 上既有下界又有上界（“ ⇔ ”表示充分必要条件）。
      证明：
      设 f(x) 在 I 上有界，根据定义， ∃M>0,s.t.|f(x)|≤M,∀x∈I 。
      |f(x)|≤M⇔−M≤f(x)≤M 
      因此 f(x) 有下界 −M ，也有上界 M （对 ∀x∈I ）
      反之，设 f(x) 在 I 上既有下界 m ，又有上界 N ，即  m≤f(x)≤N 
      如果 m=N=0 ，则 f(x)≡0,∀x∈I 
      因此 f(x) 在 I 上有界。
      文章来源：http://www.codelast.com/
      如果 m,N 不同时为零，取 M=max{|m|,|N|}>0 ，
      则  −M≤−|m|≤m≤f(x)≤N≤|N|≤M 
      即  −M≤f(x)≤M⇒|f(x)|≤M,∀x∈I 
      因此 f(x) 在 I 上有界。

      2. 函数的单调性
      若函数 f(x) 在区间 I 上，对任何 x1,x2∈I ，且 x1<x2 ，恒有 f(x1)<f(x2) ，则称 f(x) 在 I 上是严格单调增的。
      若 x1<x2 ，恒有 f(x1)≤f(x2) ，则称 f(x) 在区间 I 上广义单调增（或直接称为单调增，或称非减的）。
      若 x1<x2 ，恒有 f(x1)>f(x2) ，则称 f(x) 在 I 上严格单调减。
      类似地，也有广义单调减（单调减，非增的）的概念。
      文章来源：http://www.codelast.com/
      例如， y=x2,Df=(−∞,+∞) 
      在 (0,+∞) 上， y=x2 严格单增。
      在 (−∞,0) 上， y=x2 严格单减。

      又如，取整函数（取一个数的整数部分）：

      y=[x]=⎧⎩⎨⎪⎪⎪⎪⎪⎪⎪⎪⎪⎪⎪⎪−1,−1≤x<00,0≤x<11,1≤x<22,2≤x<3......
      其函数图形如下：

      取整函数是一个广义单增/单调增/非减函数。
      文章来源：http://www.codelast.com/
      3. 函数的奇偶性
      若 f(x) 在关于原点对称的区间 I 上满足 f(−x)=f(x) ，则称 f(x) 为偶函数。
      若满足 f(−x)=−f(x) ，则称 f(x) 为奇函数。
      偶函数图形关于 y 轴对称（例如： cosx,x2 ）
      奇函数图形关于原点对称（例如： sinx,x3 ）
      4. 函数的周期性
      设 f(x) 的定义域为 Df ，如果存在非零的常数 T,s.t. 对任意的 x∈Df ，有 (x±T)∈Df ，且 f(x+T)=f(x) ，则称 f(x) 为周期函数， T 称为 f(x) 的周期（通常周期是指最小正周期）。
      文章来源：http://www.codelast.com/
      四、 复合函数，反函数
      1. 复合函数
      设 y=u−−√,u=1−x2 ，把 u=1−x2 代入 y=u−−√ 中，得到 y=1−x2−−−−−√ ，称为由 y=u−−√ 与 u=1−x2 复合而成的复合函数。
      一般定义：
      设 y=f(u) 是数集 Y 上的函数（ Y 是 f(u) 的定义域）， u=φ(x) 的定义域为 X ，值域为 Yφ ，且 Yφ≠Φ （ Φ 表示空集）， Yφ⊆Y （表示 Yφ 是 Y 的子集），这时，对 ∀x∈X ，通过 u 都有唯一的 y 值与之对应，从而在 X 上产生一个新函数，用 f⋅φ （中间是一个实心的点）表示，称 f∘φ （中间是一个空心的圈）为 X 上的复合函数：
      f→f⋅φy ，或  y=f[φ(x)] 
      y=f[φ(x)] 的定义域：由 u=φ(x) 的定义域中使函数 u=φ(x) 的值域 Yφ 满足 Yφ⊆Y 的那一部分实数组成。
