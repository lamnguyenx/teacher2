

VỤ TUẤN - NGUYỄN VĂN ĐOÀNH

# GIÁO TRÌNH TOÁN SỐ CẤP

(Dùng cho sinh viên ngành Giáo dục tiểu học  
các hệ chính quy, đại học, từ xa)

(Tái bản lần thứ nhất)

Nguyễn Thị Thanh Hằng

NHÀ XUẤT BẢN ĐẠI HỌC SƯ PHẠM

## Phần I

## ĐẠI SỐ CẤP

### BIỂU THỨC ĐẠI SỐ

#### §1. BIỂU THỨC ĐẠI SỐ

##### 1. Khái niệm biểu thức đại số

Một biểu thức toán học (hay biểu thức) là một cách kí hiệu chỉ rõ các phép toán và thứ tự thực hiện các phép toán đó trên các số và các chữ thay số thuộc một trường số K, trong đó K là trường số thực R, trường số phức C hoặc trường số hữu tỉ Q.

Biểu thức đại số là một biểu thức toán học trong đó các số và các chữ được nối với nhau bởi các phép toán cộng, trừ, nhân, chia và phép lũy thừa với số mũ hữu tỉ.

$$\text{Ví dụ:} \quad f(x) = \frac{5x - 7}{2 - x}$$

$$g(x, y) = \frac{5x - 3y}{2x - 7y}$$

$$u(a, b, c, d) = \frac{a}{2b} + cd$$

##### 2. Giá trị của biểu thức đại số

Một bộ đối số của một biểu thức đại số là một tập hợp các chữ khác nhau trong biểu thức đại số đó lấy theo một thứ tự xác định.

$$\text{Chẳng hạn } (a, b, c, d, k) \text{ là bộ đối số của biểu thức đại số } \frac{\sqrt{ab} - c}{d + k + a}.$$

Cũng có thể coi  $(d, k, b, c, a)$  là bộ đối số của biểu thức đại số này. Nếu thay một bộ đối số bằng các số thì ta được một bộ số. Khi thay một bộ số vào biểu

thức đại số và thực hiện các phép toán trong biểu thức đại số đó thì có thể xảy ra một trong hai khả năng:

1) Mọi phép toán đều thực hiện được và ta tính được một số xác định. Số đó là giá trị của biểu thức đại số ứng với bộ số đó.

2) Có ít nhất một trong các phép toán trong biểu thức đó không thực hiện được.

Nếu xảy ra trường hợp đầu thì bộ số đó được gọi là bộ số thừa nhận được. Tập tất cả các bộ số thừa nhận được của một biểu thức đại số được gọi là miền xác định của biểu thức đại số đó.

**Ví dụ:** Xét biểu thức đại số  $\frac{a^2 + \sqrt{bc} - d}{a+b}$  trên  $\mathbb{R}$  với bộ đối số  $(a, b, c, d)$ .

Bộ số  $(1, 1, 1, 2)$  là bộ số thừa nhận được. Giá trị của biểu thức đại số ứng với bộ số đó là  $\frac{1^2 + \sqrt{1 \cdot 1} - 2}{1+1} = 0$ . Bộ số  $(1, -1, 1, 2)$  không phải là bộ số thừa nhận được vì không thực hiện được phép toán  $\sqrt{-1}$ .

Cho các biểu thức đại số  $A_1, A_2, \dots, A_n$ . Miền xác định của các biểu thức đại số đó là tập hợp tất cả các bộ số thừa nhận được của bộ đối số gồm các chữ có mặt trong các biểu thức đại số đó lấy theo một thứ tự xác định.

**Ví dụ:** Xét hai biểu thức đại số

$$A_1 = \frac{1}{a-x},$$

$$A_2 = \frac{1}{\sqrt{ab}}$$

Bộ đối số của hai biểu thức là  $(a, b, x)$ . Miền xác định của hai biểu thức đó là các bộ  $(a, b, x)$  mà  $a \neq x, ab > 0$ .

Hai biểu thức đại số được gọi là **hằng đẳng** trên tập  $M$  thuộc miền xác định của chúng nếu đối với mỗi bộ số trong  $M$  các giá trị tương ứng của hai biểu thức đó bằng nhau.

**Ví dụ:** Hai biểu thức đại số  $a$  và  $\frac{a^2}{a}$  là hằng đẳng trên tập các số thực khác không.

Hai biểu thức đại số  $\frac{1}{a+x} - \frac{1}{a-x}$  và  $\frac{-2x}{a^2 - x^2}$  là hằng đẳng trên tập  $M = \{(a, x); a \neq x, a \neq -x\}$

#### §2. ĐA THỨC

Ta biết rằng lũy thừa với số mũ tự nhiên  $m$ ,  $n$  có các tính chất sau

$$a^m a^n = a^{m+n}$$

$$(a^m)^n = a^{m \cdot n}$$

$$(a \cdot b)^m = a^m b^m$$

Đơn thức là một biểu thức đại số trong đó các số và các chữ được nối với nhau chỉ bởi hai phép toán nhân và lũy thừa với số mũ tự nhiên.

Chẳng hạn, mỗi biểu thức sau là một đơn thức:

$$-\frac{15}{7}ab^2c^3, 8, a, 13mnp^4k^3.$$

Đa thức là một tổng đại số của một số đơn thức. Biểu thị một đa thức thành tích của một số đa thức được gọi là phân tích đa thức thành nhân tử.

Ví dụ:

$$1) 2x(x+y) + ax + ay = 2x(x+y) + a(x+y) = (x+y)(2x+a)$$

$$2) 4y^2 - 2m^2 = 2(2y^2 - m^2) = 2[(\sqrt{2}y)^2 - m^2] = 2(\sqrt{2}y - m)(\sqrt{2}y + m)$$

$$3) x^4 + 1 = x^4 + 2x^2 + 1 - 2x^2$$

$$= (x^2 + 1)^2 - (\sqrt{2}x)^2 = (x^2 + \sqrt{2}x + 1)(x^2 - \sqrt{2}x + 1)$$

#### §3. ĐA THỨC MỘT ĐỐI SỐ

##### 1. Định nghĩa

Biểu thức đại số có dạng:

$$P_n(x) = a_n x^n + a_{n-1} x^{n-1} + \dots + a_1 x + a_0$$

trong đó  $a_i \in \mathbb{R}$  và  $a_n \neq 0$  được gọi là đa thức một số dạng chính tắc. Các số  $a_m, a_{m-1}, \dots, a_1, a_0$  được gọi là các hệ số, đơn thức  $a_n x^n$  được gọi là đơn thức bậc cao nhất của đa thức, số  $n$  được gọi là bậc đa thức.

Hai đa thức một số dạng chính tắc được gọi là bằng nhau nếu chúng cùng bậc và các hệ số tương ứng bằng nhau.

Chẳng hạn, đa thức  $x^3 + 2x^2 + 1$  và đa thức  $ax^3 + bx^2 + 1$  bằng nhau khi và chỉ khi  $a = 1$ ,  $b = 2$ .

Ví dụ: Tìm các số  $\alpha$ ,  $\beta$ ,  $\gamma$  biết  $x^3 + 6x^2 + ax + \beta = (x + \gamma)^3$

Giải: Ta có  $(x + \gamma)^3 = x^3 + 3x^2\gamma + 3x\gamma^2 + \gamma^3$ . Do đó

$$3\gamma = 6$$

$$3\gamma^2 = \alpha$$

$$\beta = \gamma^3$$

Từ đó suy ra  $\gamma = 2$ ,  $\alpha = 12$ ,  $\beta = 8$

##### 2. Chia đa thức

###### a) Định nghĩa

- Nếu các đa thức  $P_n(x)$ ,  $Q_m(x)$ ,  $K_1(x)$  thỏa mãn điều kiện

$$P_n(x) = Q_m(x) \cdot K_1(x)$$

thì các các đa thức  $Q_m(x)$ ,  $K_1(x)$  được gọi là các ước của đa thức  $P_n(x)$ . Ta cũng nói  $P_n(x)$ chia hết cho  $Q_m(x)$  và  $K_1(x)$  là thương của phép chia  $P_n(x)$  cho  $Q_m(x)$ .

Có thể chứng minh rằng nếu một đa thức bậc  $n$  chia hết cho một đa thức bậc  $m$  thì thương của phép chia là một đa thức bậc  $n-m$ . Nói riêng, nếu đa thức  $P_n(x)$  chia hết cho đa thức  $Q_m(x)$  (hai đa thức cùng bậc) thì có một số  $c$  để  $P_n(x) = c \cdot Q_m(x)$ , nghĩa là các hệ số của hai đa thức này tương tự lệ.

Chẳng hạn, nếu đa thức  $2x^2 + bx + c$  chia hết cho đa thức  $x^2 - x + 1$  thì  $b = -2$ ,  $c = 2$ .

Ví dụ: Biết rằng đa thức  $2x^4 - x^3 + 2x^2 + 1$  chia hết cho đa thức  $x^2 - x + 1$ . Tìm thương của phép chia.

###### Giải:

$$2x^4 - x^3 + 2x^2 + 1 = (x^2 - x + 1)(ax^2 + bx + c)$$

$$= ax^4 + (b-a)x^3 + (a+c-b)x^2 + (b-c)x + c$$

$$\begin{cases} a = 2 \\ b - a = -1 \\ a + c \cdot b = 2 \\ b - c = 0 \\ c = 1 \end{cases}$$

Vậy  $a = 2$ ,  $b = 1$ ,  $c = 1$

• Cho hai đa thức  $P_n(x)$  và  $T_m(x)$  với  $m \le n$ . Khi đó có duy nhất các đa thức  $q_1(x)$  và  $r_k(x)$  sao cho

$$P_n(x) = T_m(x) \cdot q_1(x) + r_k(x)$$

trong đó:  $l = n - m$ ,  $0 \le k < m$

Khi đó ta nói đa thức  $P_n(x)$  chia cho đa thức  $T_m(x)$  được thương là đa thức  $q_1(x)$  và dư là đa thức  $r_k(x)$ .

Ví dụ: Tìm thương và dư của phép chia đa thức  $x^3 - x + 2$  cho đa thức  $x^2 + 1$

Giải:

Giả sử thương là đa thức  $ax + b$  và dư là đa thức  $cx + d$ , ta có

$$x^3 - x + 2 = (x^2 + 1)(ax + b) + cx + d = ax^3 + bx^2 + (a + c)x + (b + d)$$

$$\begin{cases} a = 1 \\ b = 0 \\ a + c = -1 \\ b + d = 2 \end{cases}$$

Giải ra ta được  $a = 1$ ,  $b = 0$ ,  $c = -2$ ,  $d = 2$ .

$$\text{Vậy } x^3 - x + 2 = (x^2 + 1)x + (-2x + 2)$$

b) Phương pháp xác định thương và dư của phép chia đa thức

Một đa thức bất kỳ  $P_n(x)$  chia cho đa thức  $T_m(x)$  với  $m \le n$  thì hoặc  $P_n(x)$  chia hết cho  $T_m(x)$  hoặc  $P_n(x)$  chia cho  $T_m(x)$  còn dư. Để xác định thương và dư của phép chia đa thức ta có thể làm theo phương pháp hệ số bất định hoặc thực hiện phép chia trực tiếp.

1) Phương pháp hệ số bất định

Cho đa thức  $P_n(x) = a_n x^n + a_{n-1} x^{n-1} + \dots + a_1 x + a_0$  bậc  $n$  và

$$T_m(x) = b_m x^m + b_{m-1} x^{m-1} + \dots + b_1 x + b_0$$

$$\text{Đặt } q_{n-m}(x) = \frac{a_n x^n - m}{b_m} + c_{n-m-1} x^{n-m-1} + \dots + c_1 x + c_0$$

$$r_1(x) = d_{m-1} x^{m-1} + d_{m-2} x^{m-2} + \dots + d_1 x + d_0$$

trong đó  $0 \le 1 \le m-1$ , các số  $c_{n-m-1}, \dots, c_1, c_0, d_{m-1}, \dots, d_1, d_0$  chưa xác định. Viết đẳng thức  $P_n(x) = T_m(x) \cdot q_{n-m}(x) + r_1(x)$ . Nhân các đa thức  $T_m(x)$  và  $q_{n-m}(x)$  và viết về phải dưới dạng chính tắc. Sử dụng định nghĩa hai đa thức bằng nhau ta nhận được một hệ phương trình. Giải hệ này ta tìm được các hệ số  $c_i$  và  $d_i$ . Nếu các số  $d_i$  bằng không thì  $P_n(x)$  chia hết cho  $T_m(x)$ . Nếu có ít nhất một hệ số  $d_i$  khác không thì  $P_n(x)$  chia cho  $T_m(x)$  còn dư.

Ví dụ: Chia đa thức  $2x^4 + x^3 - 5x^2 - x + 1$  cho đa thức  $x^2 - x$ .

Giải:

Giả sử thương là đa thức  $q_2(x) = 2x^2 + c_1 x + c_0$  và dư là đa thức  $r_1(x) = d_1 x + d_0$ . Ta có đồng nhất thức

$$2x^4 + x^3 - 5x^2 - x + 1 = (2x^2 + c_1 x + c_0)(x^2 - x) + d_1 x + d_0$$

Khai triển về phải và sắp xếp lại ta được

$$2x^4 + x^3 - 5x^2 - x + 1 = 2x^4 + (c_1 - 2)x^3 + (-c_1 + c_0)x^2 + (d_1 - c_0)x + d_0$$

$$\begin{cases} c_1 - 2 = 1 \\ -c_1 + c_0 = -5 \\ d_1 - c_0 = -1 \\ d_0 = 1 \end{cases}$$

$$\text{Ta có } \begin{cases} c_1 = 3 \\ c_0 = -2 \\ d_1 = -3 \\ d_0 = 1 \end{cases}$$

$$\text{Vậy } 2x^4 + x^3 - 5x^2 - x + 1 = (2x^2 + 3x - 2)(x^2 - x) - 3x + 1$$

2) Phương pháp chia trực tiếp

Ta minh hoạ phương pháp này trên một ví dụ cụ thể

Ví dụ: Chia đa thức  $2x^4 - 3x^3 + 4x^2 + 1$  cho đa thức  $x^2 - 1$

$$\begin{array}{r} 2x^2 - 3x + 4x^2 + 1 \\ 2x^4 - 2x^2 \\ \hline -3x^3 + 6x^2 + 1 \\ -3x^3 + 3x \\ \hline 6x^2 - 3x + 1 \\ 6x^2 - 6 \\ \hline -3x + 7 \end{array}$$

$$a^3 + b^3 = a^2 b + a b^2$$

$$(a-b)(a^2 + b^2)$$

Vậy thương là đa thức  $2x^2 - 3x + 6$  và dư là đa thức  $-3x + 7$ .

Trong trường hợp chung, khi chia đa thức  $P_n(x)$  cho đa thức  $T_m(x)$  ( $m \le n$ ) dưới dạng chính tắc, ta lấy dư thức bậc cao nhất của  $P_n(x)$  chia cho đơn thức bậc cao nhất của  $T_m(x)$ , ta được dư thức cao nhất của  $P_n(x)$  ta được một đa thức  $Q(x)$ . Lấy dư thức đó nhân với  $T_m(x)$  rồi trừ vào  $P_n(x)$  ta được một đa thức nào đó  $Q(x)$  bậc nhỏ hơn  $n$ . Tiếp tục chia đa thức  $Q(x)$  cho  $T_m(x)$ .

Quá trình tiếp tục cho đến khi nhận được đa thức có bậc nhỏ hơn  $m$ .

Ví dụ: Chia đa thức  $-3x^3 + 5x^4 + 3x - 1$  cho đa thức  $-x^2 + x + 1$

$$\begin{array}{r} -3x^3 + 5x^4 + 3x - 1 \\ -3x^3 + 3x^4 + 3x^3 \\ \hline -2x^4 - 3x^3 + 3x - 1 \\ -2x^4 - 2x^3 - 2x^2 \\ \hline -x^3 + 2x^2 + 3x - 1 \\ -x^3 + x^2 + x \\ \hline x^2 + 2x - 1 \\ x^2 - x - 1 \\ \hline 3x \end{array}$$

$$\text{Vậy } -3x^3 + 5x^4 + 3x - 1 = (-x^2 + x + 1)(3x^3 - 2x^2 + x - 1) + 3x$$

hoặc viết

$$\frac{-3x^3 + 5x^4 + 3x - 1}{-x^2 + x + 1} = 3x^3 - 2x^2 + x - 1 + \frac{3x}{-x^2 + x + 1}$$

##### 3. Định lý Bézout

• Ta áp dụng phương pháp hệ số bất định cho trường hợp chia một đa thức  $P_n(x) = a_n x^n + a_{n-1} x^{n-1} + \dots + a_1 x + a_0$  cho đa thức  $x - \alpha$ . Thương của phép chia là đa thức có dạng  $Q_{n-1}(x) = a_{n-1} x^{n-1} + b_{n-2} x^{n-2} + \dots + b_1 x + b_0$  có bậc  $n-1$  còn dư là đa thức không (nghĩa là  $r$  là một số)

Ta có đồng nhất thức

$$\begin{aligned} a_n x^n + a_{n-1} x^{n-1} + \dots + a_1 x + a_0 \\ = (a_n x^{n-1} + b_{n-2} x^{n-2} + \dots + b_1 x + b_0)(x - a) + r \end{aligned}$$

Theo phương pháp hệ số bất định ta có

$$\begin{cases} a_{n-1} = b_{n-2} - \alpha a_n \\ a_{n-2} = b_{n-3} - \alpha b_{n-2} \\ \vdots \\ a_1 = b_0 - \alpha b_1 \\ a_0 = r - \alpha b_0 \end{cases}$$

Từ đó ta nhận được công thức truy hồi để tìm các hệ số của đa thức thương và dư

$$b_{n-2} = a_{n-1} + \alpha a_n$$

$$b_{n-3} = a_{n-2} + \alpha b_{n-2}$$
.....
$$b_0 = a_1 + \alpha b_1$$

$$r = a_0 + \alpha b_0$$

Thực hành tính toán các hệ số của đa thức thương  $Q_{n-1}(x)$  và dư r theo sơ đồ sau (gọi là lược đồ Hooc-ne).

|   | an             | $a_{n-1}$        | a <sub>n-2</sub>  |                | aı                    | a <sub>o</sub> |
|---|----------------|------------------|-------------------|----------------|-----------------------|----------------|
|   |                | +                | +                 |                | +                     | + _            |
|   | $\downarrow$   | γαa <sub>n</sub> | αb <sub>n-2</sub> |                | $_{7}$ $\alpha b_{1}$ | αbυ            |
| α | a <sub>n</sub> | b <sub>n-2</sub> | ·b <sub>n-3</sub> | b <sub>1</sub> | b <sub>o</sub>        | r              |

$Vi\ d\mu$ : Dùng sơ đồ trên hãy chia đa thức  $-x^5+4x^3-8x^2+32$  cho đa thức x+2

| v. 11. 11. | □ <b>-1</b> 7 | 0 | 4     | -8  | 0   | 32            |                |
|------------|---------------|---|-------|-----|-----|---------------|----------------|
| te de      |               | + | * + X | +   | . + | +             | We to the acti |
|            | 28 3          | 2 | - 4   | . 0 | 16  | +<br>-32<br>0 |                |
| -2         | - 1           | 2 | 0     | -8  | 16  | 0             |                |

$$V_{4y} - x^5 + 4x^3 - 8x^2 + 32 = (x + 2)(-x^4 + 2x^3 - 8x + 16)$$

$\bullet$  Khi chia đa thức  $P_n(x)$  cho đa thức  $x-\alpha$  ta nhận được đồng nhất thức

$$P_n(x) = (x - \alpha)Q_{n-1}(x) + r$$

Từ đó ta có  $P_n(\alpha) = r$ . Vậy ta có định lý sau gọi là định lý Bé-tu

**Định lý:** Số dư của phép chia đa thức  $P_n(x)$  cho đa thức  $x - \alpha$  bằng giá trị của đa thức  $P_n(x)$  khi  $x = \alpha$ .

Ví dụ 1: Tìm dư của phép chia đa thức

$$P_4(x) = x^4 + x^3 + 3x^2 + 2x + 2 \text{ cho } x - 1$$

Giải:

Theo định lý Bé-tu ta có số dư  $r$  là

$$r = P_4(1) = 1 + 1 + 3 + 2 + 2 = 9$$

Ví dụ 2: Tìm giá trị của đa thức  $P_3(x) = 2x^3 - 4x^2 - x^2 + 1$  khi  $x = 7$

Giải:

Theo định lý Bé-tu  $P_3(7)$  bằng số dư của phép chia  $P_3(x)$  cho  $x - 7$

|   | 2 | -4 | 0  | -1  | 0    | 1     |
|---|---|----|----|-----|------|-------|
| 7 | 2 | 14 | 70 | 490 | 3423 | 23961 |
|   |   | 10 | 70 | 489 | 3423 | 23962 |

$$\text{Vậy } P_3(7) = 23962$$

**Chú ý:** Nếu chia đa thức  $P_n(x)$  cho đa thức  $ax + b$  ta nhận được số dư bằng giá trị của đa thức này khi  $x = -\frac{b}{a}$ , nghĩa là  $r = P_n\left(-\frac{b}{a}\right)$ .

Ví dụ 3: Tìm các số  $a$ ,  $b$  sao cho đa thức

$$P_3(x) = x^3 + ax^2 - x + b \text{ chia hết cho } x^2 - 1$$

Giải: Nếu  $P_3(x)$  chia hết cho  $x^2 - 1$  thì nó chia hết cho  $x - 1$  và  $x + 1$ . Do đó  $P_3(1) = 0$  và  $P_3(-1) = 0$

Từ đó ta có

$$1 + a - 1 + b = 0$$

$$-1 + a + 1 + b = 0$$

$$\text{Suy ra } a = -b$$

Vậy đa thức  $P_3(x) = x^3 + ax^2 - x - a$  chia hết cho  $x^2 - 1$  với mọi  $a$ .

Số  $\alpha$  được gọi là nghiệm của đa thức  $P_n(x)$  nếu với  $x = \alpha$  thì giá trị của đa thức bằng không, nghĩa là  $P_n(\alpha) = 0$ . Ta dễ dàng nhận được các hệ quả sau đây của định lý Bơ-du:

1) Đa thức  $P_n(x)$  chia hết cho  $x - \alpha$  khi và chỉ khi  $\alpha$  là nghiệm của đa thức  $P_n(x)$ .

2) Đa thức  $x^n - a^n$  chia hết cho  $x - a$  với mọi số tự nhiên  $n$ , ngoài ra

$$\frac{x^n - a^n}{x - a} = x^{n-1} + ax^{n-2} + a^2x^{n-3} + \dots + a^{n-2}x + a^{n-1}$$

3) Đa thức  $x^{2n} - a^{2n}$  chia hết cho  $x + a$  với mọi số tự nhiên  $n$ , ngoài ra

$$\frac{x^{2n} - a^{2n}}{x + a} = x^{2n-1} - ax^{2n-2} + a^2x^{2n-3} + \dots - a^{2n-3}x^2 + a^{2n-2}x - a^{2n-1}$$

4) Đa thức  $x^{2n+1} + a^{2n+1}$  chia hết cho  $x + a$  với mọi số tự nhiên  $n$ , ngoài ra

$$\frac{x^{2n+1} + a^{2n+1}}{x + a} = x^{2n} - ax^{2n-1} + a^2x^{2n-2} - \dots + a^{2n-2}x^2 - a^{2n-1}x + a^{2n}$$

Ví dụ:

$$1. \frac{x^5 - 32}{x - 2} = x^4 + 2x^3 + 4x^2 + 8x + 16$$

$$2. \frac{x^5 + 1}{x + 1} = x^4 - x^3 + x^2 - x + 1$$

$$3. \frac{x^{10} + 1}{x^2 + 1} = x^8 - x^6 + x^4 - x^2 + 1$$

Ví dụ: Chứng minh rằng với mọi số tự nhiên  $n$  số

$$4^{2n} - 3^{2n} + 2^{3n} - 1$$
 chia hết cho 7

Giải:

$$\text{Vì } 4^{2n} = 16^n, 3^{2n} = 9^n, 2^{3n} = 8^n \text{ nên ta có } 4^{2n} - 3^{2n} + 2^{3n} - 1 = 16^n - 9^n + 8^n - 1$$

Theo hệ quả 2, với mọi số tự nhiên  $n$ , số  $16^n - 9^n$  chia hết cho  $16 - 9 = 7$  và số  $8^n - 1$  chia hết cho số  $8 - 1 = 7$ . Vậy  $4^{2n} - 3^{2n} + 2^{3n} - 1$  chia hết cho 7.

**Chú ý:** Đối với một đa thức bất kì  $P_n(x)$  có thể không tồn tại đa thức  $x - \alpha$  để  $P_n(x)$  chia hết cho đa thức đó. Chẳng hạn, đa thức  $ax^2 + bx + c$ ,  $a \neq 0$  (còn gọi là tam giác bậc hai) với  $b^2 - 4ac < 0$  không chia hết cho đa thức  $x - \alpha$  nào.

#### §4. PHÂN THỨC ĐẠI SỐ

Biểu thức đại số có dạng  $\frac{A}{B}$  trong đó A, B là các đa thức được gọi là một phân thức đại số. A được gọi là tử thức, B được gọi là mẫu thức.

Miền xác định của phân thức đại số  $\frac{A}{B}$  là tập tất cả các bộ số thực nhận được của bộ đối số của các đa thức A và B sao cho giá trị của đa thức B ứng với mỗi bộ số đó không bằng không.

Hai phân thức đại số  $\frac{A}{B}$  và  $\frac{C}{D}$  được gọi là hàng đẳng trên tập con M của miền xác định nếu với các bộ số của M ta có  $AD = BC$ . Khi đó ta viết  $\frac{A}{B} = \frac{C}{D}$ .

Ví dụ:

$$1) \frac{x^2}{ax} = \frac{x}{a} \text{ trên tập } M = \{(a, x); ax \neq 0\}$$

$$2) \frac{x^2 - 1}{2(x + 1)} = \frac{x - 1}{2} \text{ trên tập } M = \{x; x \neq -1\}$$

$$3) \frac{xy + x}{x^2y + x^2} = \frac{1}{x} \text{ trên tập } M = \{(x, y); x \neq 0, y \neq -1\}$$

Đối với một đa thức bất kì P không bằng không trên miền xác định của phân thức đại số  $\frac{A}{B}$  thì

$$\frac{A}{B} = \frac{P \cdot A}{P \cdot B}, \quad \frac{A}{B} = \frac{P}{B}$$

$$\text{Ví dụ: } \frac{x^4 - 1}{(x^2 - 1)(x + 2)} = \frac{x^2 + 1}{x + 2} \text{ với } x \neq \pm 1, x \neq -2$$

Mẫu thức chung của hai phân thức đại số  $\frac{A}{B}$  và  $\frac{C}{D}$  là đa thức P chia hết cho B và chia hết cho D.

Ví dụ: Mẫu thức chung của hai phân thức  $\frac{x}{x+2}$  và  $\frac{3x-1}{x-2}$  là các đa thức  $x^2 - 4$ ,  $2(x^2 - 4)$ ,  $x(x^2 - 4)$

Mẫu thức chung nhỏ nhất của các phân thức đại số là mẫu thức chung mà mọi mẫu thức chung khác đều chia hết cho nó. Để tìm mẫu thức chung nhỏ nhất của các phân thức đại số ta phân tích mẫu thức của mỗi phân thức thành các nhân tử, khi đó mẫu thức chung là tích của các nhân tử đó (nếu có nhân tử chung trong hai phân tích nào đó thì ta chỉ lấy một lần với số mũ cao nhất).

Ví dụ: Đưa các phân thức đại số sau về các phân thức có mẫu thức chung

$$\frac{4}{x-y}, \frac{1}{x^2-y^2}, \frac{1}{x^3-y^3}$$

Giải:

$$x^2 - y^2 = (x - y)(x + y)$$

$$x^3 - y^3 = (x - y)(x^2 + xy + y^2)$$

Vậy mẫu thức chung nhỏ nhất là  $(x + y)(x - y)(x^2 + xy + y^2)$

$$\text{Do đó} \quad \frac{1}{x-y} = \frac{(x+y)(x^2+xy+y^2)}{(x+y)(x-y)(x^2+xy+y^2)}$$

$$\frac{1}{x^2-y^2} = \frac{x^2+xy+y^2}{(x+y)(x-y)(x^2+xy+y^2)}$$

$$\frac{1}{x^3-y^3} = \frac{x+y}{(x+y)(x-y)(x^2+xy+y^2)}$$

Tổng của hai phân thức đại số với mẫu thức chung là phân thức có tử thức là tổng của hai tử thức còn mẫu thức là mẫu thức chung đó

$$\frac{A}{C} + \frac{B}{C} = \frac{A+B}{C}$$

$$\frac{A}{C} - \frac{B}{C} = \frac{A-B}{C}$$

Thương của phép chia hai phân thức đại số được cho bởi quy tắc

$$\frac{A}{B} : \frac{C}{D} = \frac{A \cdot D}{B \cdot C}$$

Đối với phân thức đại số  $\frac{A}{B}$  và  $n$  là số tự nhiên thì

$$\left(\frac{A}{B}\right)^n = \frac{A^n}{B^n}$$

Vi dụ: Tìm các số  $a$ ,  $b$ ,  $c$  sao cho

$$\frac{1}{(x^2+1)(x+1)} = \frac{ax+b}{x^2+1} + \frac{c}{x+1}$$

Giải:

$$\begin{aligned}\frac{ax+b}{x^2+1} + \frac{c}{x+1} &= \frac{(ax+b)(x+1) + c(x^2+1)}{(x^2+1)(x+1)} \\ &= \frac{(a+c)x^2 + (a+b)x + b + c}{(x^2+1)(x+1)}\end{aligned}$$

Vậy  $(a+c)x^2 + (a+b)x + b + c = 1$ . Suy ra

$$\begin{cases} a+c=0 \\ a+b=0 \\ b+c=1 \end{cases}$$

suy ra  $b=c=\frac{1}{2}$ ,  $a=-\frac{1}{2}$ .

#### §5. SO SÁNH CÁC BIỂU THỨC ĐẠI SỐ

##### 1. Hằng đẳng thức

Hai biểu thức đại số  $A$  và  $B$  được gọi là hằng đẳng trên tập con  $M$  của miền xác định nếu đối với một bộ số bất kì của  $M$  thì giá trị của  $A$  và  $B$  bằng nhau. Khi đó ta nói rằng trên tập  $M$  có đẳng nhất thức  $A = B$  hoặc  $A^M = B^M$ .

Trong trường hợp không chỉ rõ tập M thì ta hiểu đồng nhất thức đó là đồng nhất thức trên miền xác định của các biểu thức đại số đó. Chẳng hạn  $a^2 + 2ab + b^2 = (a + b)^2$  là đồng nhất thức trên miền xác định, nghĩa là với mọi  $a$  và  $b$ . Hai biểu thức  $\frac{1}{(a+2)n}$  và  $\frac{1}{a+2}$  là hằng đẳng với  $a \neq 0$  và  $a \neq -2$ . Phép biến đổi hằng đẳng trên M là sự thay biểu thức đại số A bởi biểu thức đại số B hằng đẳng với nó trên tập M.

Ta có các tính chất sau đây của đồng nhất thức trên miền xác định hoặc trên một tập M của miền xác định

1. Nếu  $A = B$  thì  $B = A$
2. Nếu  $A = B$  thì  $A - B = 0$
3. Nếu  $A \neq B$ ,  $B = C$  thì  $A = C$

4) Nếu  $A = B$  và  $C$  là biểu thức đại số không bằng 0 (trên miền xác định hoặc trên M) thì

$$AC = BC, \frac{A}{C} = \frac{B}{C}$$

1. Nếu  $A = B$  và  $C = D$  thì  $A + C = B + D$ ,  $A - C = B - D$
2. Nếu  $A = B$  thì  $A + C = B + C$ ,  $A - C = B - C$
3. Nếu  $A = B$  và  $C = D \neq 0$  thì  $\frac{A}{C} = \frac{B}{D}$
4. Nếu  $A = B$  và  $C = D$  thì  $AC = BD$
5. Nếu  $A = B$  thì  $A^n = B^n$ ,  $n \in \mathbb{N}$
6. Nếu  $A^n = B^n$  và nếu  $A$ ,  $B$  chỉ nhận giá trị không âm thì  $A = B$ ,  $n \in \mathbb{N}$
7. Nếu  $A^{2n+1} = B^{2n+1}$  thì  $A = B$ ,  $n \in \mathbb{N}$
8. Nếu  $A = B$  thì  $2^n \sqrt{A} = 2^n \sqrt{B}$
9. Nếu  $A = B$  và nếu  $A$ ,  $B$  chỉ nhận giá trị không âm thì  $\sqrt{A} = \sqrt{B}$ ,  $n \in \mathbb{N}$

##### 2. Hằng bất đẳng thức

Cho hai biểu thức đại số  $A$  và  $B$ , và  $M$  là một tập con của miền xác định. Nếu với mỗi bộ số của  $M$ , giá trị của biểu thức  $A$  luôn lớn hơn (hoặc nhỏ hơn) giá trị của biểu thức  $B$  thì ta viết  $A > B$  (hoặc  $A < B$ ) và gọi là các hằng bất đẳng thức.

Chẳng hạn trên tập các số thực ta có  $a^2 + 1 > a^2$ ,  $a < a^2 + 1$

Ngoài các hàng bất đẳng thức  $A > B$ ,  $A < B$  ta còn xét các hàng bất đẳng thức  $A \ge B$ ,  $A \le B$ . Ta hiểu  $A \ge B$  (hoặc  $A \le B$ ) trên tập  $M$  nếu với mỗi bộ số bất kì trong  $M$  thì giá trị của biểu thức  $A$  lớn hơn hoặc bằng (hoặc nhỏ hơn hoặc bằng) giá trị của biểu thức  $B$ .

Ta có các tính chất sau của các hàng bất đẳng thức

1. Nếu  $A < B$  thì  $B > A$
2. Nếu  $A > B$  thì  $A - B > 0$
3. Nếu  $A > B$  và  $B > C$  thì  $A > C$
4. Nếu  $A > B$  thì  $A + C > B + C$ ,  $A - C > B - C$
5. Nếu  $A > B$  và  $C > D$  thì  $A + C > B + D$
6. Nếu  $A > B$  và  $C < D$  thì  $A - C > B - D$
7. Nếu  $A > B$  và  $C > 0$  thì  $AC > BC$
8. Nếu  $A > B$  và  $C < 0$  thì  $AC < BC$
9. Nếu  $A > B > 0$ ,  $C > D > 0$  thì  $AC > BD$
10. Nếu  $A > B$  thì  $A^{2n+1} > B^{2n+1}$ ,  $n \in \mathbb{N}$
11. Nếu  $A > B > 0$  thì  $A^n > B^n$ ,  $n \in \mathbb{N}$
12. Nếu  $A^{2n+1} > B^{2n+1}$  thì  $A > B$ ,  $n \in \mathbb{N}$
13. Nếu  $A^n > B^n$  và  $A > 0$ ,  $B > 0$  thì  $A > B$
14. Nếu  $A > B$  thì  $2^{2n} \sqrt{A} > 2^{2n} \sqrt{B}$ ,  $n \in \mathbb{N}$
15. Nếu  $A > B$  và  $B > 0$  thì  $\sqrt{A} > \sqrt{B}$ ,  $n \in \mathbb{N}$

16. Các tính chất tương tự như trên cũng đúng đối với các hàng bất đẳng thức  $A < B$ ,  $A \ge B$ ,  $A \le B$

##### 3. Phương pháp chứng minh các hàng bất đẳng thức

Để cho gọn ta gọi các hàng bất đẳng thức là bất đẳng thức. Rất khó nên lên phương pháp tổng quát chứng minh các bất đẳng thức đó tính đa dạng của bất đẳng thức cũng như phương pháp chứng minh. Tuy nhiên có thể nếu ra một số cách thường dùng sau đây.

1. Dựa vào định nghĩa, tức là xét tất cả các bộ số để chứng minh  $A > B$ .
2. Biến đổi tương đương. Để chứng minh  $A > B$  ta dùng các tính chất của bất đẳng thức và tính chất các phép toán trong các biểu thức đại số  $A, B$  để biến đổi về bất đẳng thức đúng  $C > D$ . Vì  $C > D$  đúng nên  $A > B$  đúng.
3. Dùng phương pháp quy nạp hoàn toàn.
4. Biến đổi hệ quả. Xuất phát từ bất đẳng thức đúng  $C > D$  ta biến đổi về bất đẳng thức  $A > B$

Vì  $C > D$  đúng nên  $A > B$  đúng.

5) Dùng phương pháp phân chứng.

Ta nêu một số ví dụ về chứng minh bất đẳng thức.

Ví dụ 1: Chứng minh rằng đối với hai số dương bất kì  $a, b$  ta có

$$4(a^3 + b^3) \ge (a + b)^3$$

Giải:

$$\begin{aligned}4(a^3 + b^3) - (a + b)^3 &= 3a^3 + 3b^3 - 3a^2b - 3ab^2 \\&= 3[(a^2 - a^3) + (b^3 - ab^2)] = 3[(a^2 - b) + b^2(b - a)] \\&= 3(a - b)(a^2 - b^2) = 3(a - b)^2(a + b)\end{aligned}$$

Vì  $(a - b)^2 \ge 0$ ,  $a + b > 0$  nên  $4(a^3 + b^3) - (a + b)^3 \ge 0$

Do đó  $4(a^3 + b^3) \ge (a + b)^3$

Ví dụ 2: Chứng minh rằng đối với mọi số tự nhiên  $n$  khác 0 ta có

$$\frac{1}{1^2} + \frac{1}{2^2} + \frac{1}{3^2} + \dots + \frac{1}{n^2} < 2$$

Giải:

Đối với các số tự nhiên  $k$ ,  $2 \le k \le n$ , ta có

$$\frac{1}{k^2} < \frac{1}{k(k-1)} = \frac{1}{k-1} - \frac{1}{k}$$

$$\begin{aligned}\text{Do đó. } \frac{1}{1^2} + \frac{1}{2^2} + \frac{1}{3^2} + \dots + \frac{1}{n^2} &< 1 + \left(1 - \frac{1}{2}\right) + \left(\frac{1}{2} - \frac{1}{3}\right) + \dots + \left(\frac{1}{n-1} - \frac{1}{n}\right) \\&= 2 - \frac{1}{n} < 2\end{aligned}$$

Ví dụ 3: Chứng minh rằng  $\frac{1}{a} + \frac{1}{b} + \frac{1}{c} \ge \frac{9}{a+b+c}$  nếu  $a, b, c > 0$ .

Giải:

$$\begin{aligned}(a+b+c)\left(\frac{1}{a} + \frac{1}{b} + \frac{1}{c}\right) &= 3 + \left(\frac{a}{b} + \frac{b}{a}\right) + \left(\frac{b}{c} + \frac{c}{b}\right) + \left(\frac{c}{a} + \frac{a}{c}\right) \\&= 9 + \left(\sqrt{\frac{a}{b}} - \sqrt{\frac{b}{a}}\right)^2 + \left(\sqrt{\frac{b}{c}} - \sqrt{\frac{c}{b}}\right)^2 + \left(\sqrt{\frac{c}{a}} - \sqrt{\frac{a}{c}}\right)^2 \ge 9\end{aligned}$$

$$\text{Vậy } \frac{1}{a} + \frac{1}{b} + \frac{1}{c} \ge \frac{9}{a+b+c}$$

Ví dụ 4: Chứng minh rằng nếu  $a, b, c$  là những số dương và  $a+b+c=1$  thì

$$\sqrt{4a+1} + \sqrt{4b+1} + \sqrt{4c+1} < 5$$

Giải:

$$\begin{aligned}\sqrt{4a+1} + \sqrt{4b+1} + \sqrt{4c+1} &< \sqrt{4a^2 + 4a + 1} + \sqrt{4b^2 + 4b + 1} \\&+ \sqrt{4c^2 + 4c + 1} = \sqrt{(2a+1)^2} + \sqrt{(2b+1)^2} + \sqrt{(2c+1)^2} \\&= 2a+1+2b+1+2c+1 = 2(a+b+c)+3 = 5\end{aligned}$$

$$\text{Vậy } \sqrt{4a+1} + \sqrt{4b+1} + \sqrt{4c+1} < 5$$

Ví dụ 5: Cho hai số không âm  $a_1, a_2$ . Chứng minh rằng  $\frac{a_1+a_2}{2} \ge \sqrt{a_1 a_2}$ .

Dǎng thức xảy ra khi và chỉ khi  $a_1 = a_2$  (bắt dǎng thức Cõsi)

$$\text{Giải: } \frac{a_1+a_2}{2} - \sqrt{a_1 a_2} = \frac{a_1+a_2-2\sqrt{a_1 a_2}}{2} = \frac{(\sqrt{a_1}-\sqrt{a_2})^2}{2} \ge 0$$

$$\text{Vậy } \frac{a_1+a_2}{2} \ge \sqrt{a_1 a_2} \text{ và dǎng thức xảy ra khi } \sqrt{a_1} - \sqrt{a_2} = 0 \text{ iuy } a_1 = a_2$$

Ví dụ 6: Chứng minh rằng nếu  $a_1, a_2, \dots, a_n$  ( $n \ge 2$ ) là những số dương sao cho  $a_1 a_2 \dots a_n = 1$  thì

$$a_1 + a_2 + \dots + a_n \ge n$$

$$\text{Dǎng thức xảy ra khi } a_1 = a_2 = \dots = a_n$$

Giải:

Ta chứng minh bằng phương pháp quy nạp. Với  $n = 2$ . Giả sử  $a_1, a_2$  là hai số dương và  $a_1 a_2 = 1$ . Theo bất đẳng thức Côsi ta có

$$\frac{a_1 + a_2}{2} \ge \sqrt{a_1 a_2} = \sqrt{1} = 1$$

Vậy  $a_1 + a_2 \ge 2$  và có dấu đẳng thức khi và chỉ khi  $a_1 = a_2$ . Giả sử bất đẳng thức được chứng minh với  $n = k$ , nghĩa là

$$a_1 + a_2 + \dots + a_k \ge k$$

và có dấu đẳng thức khi  $a_1 = a_2 = \dots = a_k$

Ta cần chứng minh bất đẳng thức đúng với  $n = k + 1$ .

$$\text{Nếu } a_1 = a_2 = \dots = a_{k+1} \text{ thì } a_1 + a_2 + \dots + a_{k+1} = k + 1.$$

Nếu có ít nhất một số chẵng hạn  $a_k < 1$ . Khi đó có ít nhất một số lớn hơn 1. Chẵng hạn  $a_{k+1} > 1$ . Theo giả thiết quy nạp ta có

$$a_1 + a_2 + \dots + a_{k-1} + a_k a_{k+1} \ge k$$

$$\begin{aligned} \text{Do đó} & a_1 + a_2 + \dots + a_{k-1} + a_k + a_{k+1} \ge k - a_k a_{k+1} + a_k + a_{k+1} \\ & = (k+1) + (1-a_k)(a_{k+1}-1) \ge k+1, \text{ vì } 1-a_k > 0 \text{ và } a_{k+1}-1 > 0 \end{aligned}$$

Vậy bất đẳng thức được chứng minh.

Ví dụ 7:

Cho  $n$  số không âm  $a_1, a_2, \dots, a_n$ . Chứng minh rằng (bất đẳng thức Côsi mở rộng)

$$\frac{a_1 + a_2 + \dots + a_n}{n} \ge \sqrt[n]{a_1 a_2 \dots a_n}$$

Bất đẳng thức xảy ra khi và chỉ khi  $a_1 = a_2 = \dots = a_n$ .

Giải:

Nếu một trong các số  $a_i$  bằng 0 thì hiển nhiên bất đẳng thức đúng.

Bây giờ giả sử  $a_1 a_2 \dots a_n > 0$ . Đặt

$$c = \sqrt[n]{a_1 a_2 \dots a_n}, \text{ ta có } \frac{a_1}{c} \cdot \frac{a_2}{c} \dots \frac{a_n}{c} = 1 \text{ và } \frac{a_i}{c} > 0. \text{ Theo ví dụ 6 ta có}$$

$$\frac{a_1}{c} + \frac{a_2}{c} + \dots + \frac{a_n}{c} \ge n$$

Suy ra  $\frac{a_1 + a_2 + \dots + a_n}{n} \ge \sqrt[n]{a_1 a_2 \dots a_n}$  và có dấu đẳng thức khi và chỉ

$$\text{ khi } a_1 = a_2 = \dots = a_n$$

Ví dụ 8:

Cho hai bộ  $n$  số  $(a_1, a_2, \dots, a_n)$ ,  $(b_1, b_2, \dots, b_n)$ . Chứng minh rằng (bất đẳng thức Cési-Bunhia cổ pxki)

$$\left( \sum_{i=1}^{n} a_i b_i \right)^2 \le \left( \sum_{i=1}^{n} a_i^2 \right) \left( \sum_{i=1}^{n} b_i^2 \right)$$

Dấu đẳng thức xảy ra khi và chỉ khi  $b_i = ta_i$ ,  $i = 1, \dots, n$ .

Giải:

$$\text{Ta có } (a_i - b_i)^2 \ge 0, \forall t \in \mathbb{R}, i = 1, 2, \dots, n.$$

$$\text{Do đó } a_i^2 + 2a_i b_i + b_i^2 \ge 0. \text{ Cộng các vế của bất đẳng thức ta có}$$

$$(a_1^2 + a_2^2 + \dots + a_n^2) t^2 - 2(a_1 b_1 + a_2 b_2 + \dots + a_n b_n) t + b_1^2 + b_2^2 + \dots + b_n^2 \ge 0$$

$$\text{Suy ra } \Delta' = (a_1 b_1 + a_2 b_2 + \dots + a_n b_n)^2 - (a_1^2 + a_2^2 + \dots + a_n^2)(b_1^2 + \dots + b_n^2) \le 0$$

$$\text{Do đó } (a_1 b_1 + a_2 b_2 + \dots + a_n b_n)^2 \le (a_1^2 + a_2^2 + \dots + a_n^2)(b_1^2 + b_2^2 + \dots + b_n^2) \text{ và}$$

có dấu bằng khi và chỉ khi  $b_i = ta_i$ .

Ví dụ 9: Chứng minh rằng với  $a$  là một số thực dương và  $r$  là số hữu tỉ lớn hơn 1, ta có (bất đẳng thức Becnuli)

$$(1 + a)^r > 1 + ra$$

Giải:

$$\text{Giả sử } r = \frac{m}{n}, m > n. \text{ Theo bất đẳng thức Cési mở rộng ta có}$$
$$\frac{n(1+ra) + m - n}{m} > \sqrt{(1+ra)^m} \quad (\text{Chú ý rằng ở đây không có dấu bằng vì } 1+ra > 1)$$

$$\text{Suy ra } 1 + \frac{n}{m} ra > (1+ra)^{\frac{n}{m}}. \text{ Nhưng } \frac{n}{m} = \frac{1}{r}, \text{ do đó } 1 + a > (1+ra)^{\frac{1}{r}} \text{ hay}$$
$$(1+a)^r > 1 + ra$$

Ví dụ: Chứng minh rằng với  $n$  số thực tùy ý  $a_1, a_2, \dots, a_n$  ta có

$$|a_1 + a_2 + \dots + a_n| \le |a_1| + |a_2| + \dots + |a_n|$$

Giải:

Nếu  $a_1 > 0$  với  $j = \overline{1, n}$  hoặc  $a_1 < 0$  với  $j = \overline{1, n}$  thì hiển nhiên  $|a_1 + \dots + a_n| = |a_1| + \dots + |a_n|$ .

Nếu các  $a_i$  có dấu trái nhau, để tính  $|a_1 + a_2 + \dots + a_n|$  ta tính riêng tổng các số cùng dấu, rồi lấy tổng lớn trừ tổng bé thì rõ ràng ta có

$$|a_1 + a_2 + \dots + a_n| < |a_1| + |a_2| + \dots + |a_n|$$

##### 4. Các áp dụng của bất đẳng thức

Ta nên một số ví dụ về áp dụng bất đẳng thức để tìm giá trị lớn nhất và giá trị nhỏ nhất.

Ví dụ 1: Chứng minh rằng trong các hình chữ nhật nội tiếp đường tròn bán kính  $R$ , hình vuông là hình có diện tích lớn nhất.

Giải:

Giả sử  $x, y$  là kích thước của hình chữ nhật nội tiếp. Khi đó  $x > 0, y > 0$  và  $x^2 + y^2 = 4R^2$

Giả sử  $S$  là diện tích hình chữ nhật,  $S = xy$ . Theo bất đẳng thức Côsi ta có

$$\frac{x^2 + y^2}{2} \ge \sqrt{x^2 y^2} = xy = S$$

Vậy  $S \le 2R^2$  và  $S = 2R^2$  khi và chỉ khi  $x = y$ . Nghĩa là hình chữ nhật là hình vuông.

Chú ý: Từ bất đẳng thức Côsi mở rộng ta suy ra rằng

1) Nếu tổng các số dương  $a_1, a_2, \dots, a_n$  bằng  $a$  thì tích của các số dương này nhận giá trị lớn nhất là  $\left(\frac{a}{n}\right)^n$  khi  $a_1 = a_2 = \dots = a_n = \frac{a}{n}$ .

2) Nếu tích của các số dương  $a_1, a_2, \dots, a_n$  bằng  $b$  thì tổng của chúng nhận giá trị nhỏ nhất là  $n\sqrt[n]{b}$  khi  $a_1 = a_2 = \dots = a_n = \sqrt[n]{b}$ .

Ví dụ 2: Cho các số  $x, y, z$  thỏa mãn điều kiện  $xy + yz + zx = 4$ . Tìm giá trị nhỏ nhất của  $A = x^4 + y^4 + z^4$ .

Giải:

Áp dụng bất đẳng thức Côsi-Bunhiacópxki cho hai bộ ba số  $(1, 1, 1)$ ,  $(x^2, y^2, z^2)$  ta có

$$(x^2 + y^2 + z^2)^2 \le (1^2 + 1^2 + 1^2)(x^4 + y^4 + z^4) = 3(x^4 + y^4 + z^4)$$

$$x^4 + y^4 + z^4 \ge \frac{1}{3}(x^2 + y^2 + z^2)^2$$

Lại áp dụng bất đẳng thức Côsi-Bunhiacópxki cho hai bộ ba số  $(x, y, z)$  và  $(y, z, x)$  ta có

$$(x^2 + y^2 + z^2)^2 \ge (xy + yz + zx)^2 = 16$$

$$\text{Vậy } A = x^4 + y^4 + z^4 \ge \frac{16}{3}.$$

$$\text{Đẳng thức xảy ra khi và chỉ khi } x = y = z = \pm \frac{2\sqrt{3}}{3}.$$

$$\text{Vậy giá trị nhỏ nhất của } A \text{ là } \frac{16}{3}.$$

Ví dụ 3: Tìm giá trị nhỏ nhất của hàm số  $f(x) = x + \frac{a}{x}$  với  $x > 0$  và  $a$  là hằng số dương.

Giải:

Theo bất đẳng thức Côsi

$$x + \frac{a}{x} \ge 2\sqrt{x \cdot \frac{a}{x}} = 2\sqrt{a}$$

$$\text{Có dấu đẳng thức khi và chỉ khi } x = \frac{a}{x} \text{ hay } x = \sqrt{a}$$

$$\text{Vậy giá trị nhỏ nhất của } f(x) \text{ là } 2\sqrt{a}.$$

Ví dụ 4: Tìm giá trị lớn nhất của hàm số

$$f(x) = (1-x)^3(1+3x) \text{ với } -\frac{1}{3} < x < 1.$$

Giải:

Biến đổi biểu thức  $f(x)$

$$f(x) = (1-x)^3(1+3x) = (1-x)(1-x)(1-x)(1+3x)$$

Vì  $1 - x > 0$ ,  $1 + 3x > 0$  và  $(1 - x) + (1 - x) + (1 - x) + (1 + 3x) = 4$  nên ta có

$$\sqrt{(1-x)^3(1+x)} \le 1 \text{ hay } (1-x)^3(1+3x) \le 1$$

Có dấu đẳng thức khi và chỉ khi  $1 - x = 1 + 3x$ , tức là  $x = 0$

Vậy giá trị lớn nhất của  $f(x)$  bằng 1.

Vì dụ 5: Tìm giá trị lớn nhất của hàm số

$$f(x) = x^2 \sqrt{4 - x^2} \text{ với } -2 \le x \le 2$$

Giải:

Các hàm số  $f(x)$  và  $\frac{1}{4}f(x)^2$  đạt giá trị lớn nhất với cùng một giá trị của đối số vì  $f(x) \ge 0$

$$\text{Ta có } \frac{1}{4}f(x)^2 = \frac{x^4}{4}(4 - x^2) = \frac{1}{2}x^2 \cdot \frac{1}{2}x^2 \cdot (4 - x^2)$$

Áp dụng bất đẳng thức Côsi cho ba số  $\frac{1}{2}x^2$ ,  $\frac{1}{2}x^2$  và  $(4 - x^2)$  ta có

$$\frac{\frac{1}{2}x^2 + \frac{1}{2}x^2 + 4 - x^2}{3} \ge \sqrt[3]{\frac{x^4}{4}(4 - x^2)}$$

hay  $\frac{4}{3} \ge \sqrt[3]{\frac{x^4}{4}(4 - x^2)}$ . Có dấu đẳng thức khi và chỉ khi  $\frac{1}{2}x^2 = 4 - x^2$  hay

$$x = \pm \frac{2\sqrt{6}}{3}$$

Vậy giá trị lớn nhất của  $f(x)$  là  $f\left(\pm \frac{2\sqrt{6}}{3}\right) = \frac{16\sqrt{3}}{9}$  đạt được khi

$$x = \pm \frac{2\sqrt{6}}{3}$$

#### §6. DẤU CỦA CÁC BIỂU THỨC $ax + b$ VÀ $ax^2 + bx + c$ TRÊN TRƯỜNG SỐ THỰC $\mathbb{R}$

Da thức một đối số  $ax + b$ ,  $a \neq 0$  được gọi là một **nhị thức bậc nhất**, còn da thức một đối số  $ax^2 + bx + c$ ,  $a \neq 0$  được gọi là một tam thức bậc hai. Ta xét dấu của các da thức này, nghĩa là xét xem với những giá trị nào của  $x$  thì giá trị của da thức là số dương, với những giá trị nào của  $x$  thì giá trị của da thức là số âm.

##### 1. Dấu của $ax + b$ , $a \neq 0$

Ta có  $ax + b > 0 \Leftrightarrow ax > -b$ ,  $x > -\frac{b}{a}$  nếu  $a > 0$  và tương đương với  $x < -\frac{b}{a}$  nếu  $a < 0$ . Tương tự đối với trường hợp  $ax + b < 0$ . Ta có  $ax + b = 0$  khi  $x = -\frac{b}{a}$ .

Như vậy ta có:

Giá trị của  $p(x) = ax + b$  là một số cùng dấu với  $a$  nếu  $x > -\frac{b}{a}$  và trái dấu với  $a$  nếu  $x < -\frac{b}{a}$ .

Ví dụ: Xét dấu biểu thức  $f(x) = (2x + 1)(x - 5)$ .

Giải:

| $x$      | $-\infty$ | $-\frac{1}{2}$ | 5 | $+\infty$ |
|----------|-----------|----------------|---|-----------|
| $2x + 1$ | -         | 0              | + | +         |
| $x - 5$  | -         |                | - | 0         |
| $f(x)$   | +         | 0              | - | 0         |

Như vậy ta có  $f(x) > 0$  khi  $x < -\frac{1}{2}$  hoặc  $x > 5$

$$f(x) < 0 \text{ khi } -\frac{1}{2} < x < 5$$

2. Dấu của  $ax^2 + bx + c$ ,  $a \neq 0$

Ta có  $f(x) = ax^2 + bx + c = a\left(x + \frac{b}{2a}\right)^2 - \frac{\Delta}{4a^2}$ , trong đó  $\Delta = b^2 - 4ac$ .

Do đó

1) Nếu  $\Delta < 0$  thì  $\left(x + \frac{b}{2a}\right)^2 - \frac{\Delta}{4a^2} > 0$  với  $\forall x \in \mathbb{R}$ . Suy ra  $af(x) = a\left[\left(x + \frac{b}{2a}\right)^2 - \frac{\Delta}{4a^2}\right] > 0$  với  $\forall x \in \mathbb{R}$ , nghĩa là giá trị của  $f(x)$  là một số cùng

dấu với  $a$  với  $\forall x \in \mathbb{R}$ .

2) Nếu  $\Delta = 0$  thì  $f(x) = 0$  khi  $x = -\frac{b}{2a}$ , còn với  $x \neq -\frac{b}{2a}$  ta có

$af(x) = a^2\left(x + \frac{b}{2a}\right)^2 > 0$ . Vậy giá trị của  $f(x)$  là một số cùng dấu với  $a$  với mọi  $x \neq -\frac{b}{2a}$ .

3) Nếu  $\Delta > 0$  thì  $f(x) = 0$  khi và chỉ khi

$$\left(x + \frac{b}{2a}\right)^2 = \frac{\Delta}{4a^2} \text{ hay } x = \frac{-b \pm \sqrt{\Delta}}{2a}. \text{ Đặt } x_1 = \frac{-b - \sqrt{\Delta}}{2a}, x_2 = \frac{-b + \sqrt{\Delta}}{2a}.$$

ta có  $f(x) = a(x - x_1)(x - x_2)$ . Giả sử  $x_1 < x_2$ , ta có

| x                            | $x_1$            | $x_2$ |                  |   |                  |
|------------------------------|------------------|-------|------------------|---|------------------|
| $x - x_1$                    | -                | 0     | +                | + |                  |
| $x - x_2$                    | -                | -     | 0                | + |                  |
| $(x - x_1)(x - x_2)$         | +                | 0     | -                | 0 | +                |
| $f(x) = a(x - x_1)(x - x_2)$ | cùng dấu với $a$ | 0     | trái dấu với $a$ | 0 | cùng dấu với $a$ |

Như vậy ta có:

Giả trị của  $f(x)$  là số cùng dấu với a nếu  $x < x_1$  hoặc  $x > x_2$ .

Giả trị của  $f(x)$  là số trái dấu với a nếu  $x_1 < x < x_2$ .

Từ các kết quả trên ta cũng suy ra ngay được kết quả sau đây

Cho tam thức bậc hai  $f(x) = ax^2 + bx + c$ ,  $a \neq 0$  và một số thực  $\alpha$

1) Nếu  $af(\alpha) < 0$  thì  $f(x)$  có hai nghiệm phân biệt  $x_1 < x_2$  và  $x_1 < \alpha < x_2$ .

2) Nếu  $af(\alpha) > 0$  thì đa thức  $f(x)$  có thể không có nghiệm. Trong trường hợp  $f(x)$  có hai nghiệm  $x_1 < x_2$  thì  $\alpha < x_1$  hoặc  $\alpha > x_2$ .

Ví dụ 1: Xét dấu các tam thức bậc hai

a)  $f(x) = -3x^2 + 2x - 5$

b)  $f(x) = 5x^2 + 6x + 1$

Giải:

a)  $\Delta = 4 - 60 = -56$ . Vì  $a = -3 < 0$  nên  $f(x) < 0$  với  $\forall x \in \mathbb{R}$

b) nghiệm của  $f(x)$  là  $-1$  và  $-\frac{1}{5}$  và  $a = 5 > 0$ .

Do đó  $f(x) > 0$  với  $\forall x \in (-\infty, -1) \cup (-\frac{1}{5}, +\infty)$

$$f(x) < 0 \text{ với } \forall x \in (-1, -\frac{1}{5})$$

Ví dụ 2: Tìm các giá trị của m để

$$f(x) = mx^2 + (m-1)x + m - 1$$

luôn âm với mọi  $x \in \mathbb{R}$ .

Giải:

$$f(x) < 0, \forall x \in \mathbb{R} \Leftrightarrow \begin{cases} a = m < 0 \\ \Delta < 0 \end{cases}$$

$$Ta \text{ có } \Delta = (m-1)^2 - 4m(m-1) = (1-m)(3m+1)$$

Vậy  $\Delta < 0 \Leftrightarrow m < -\frac{1}{3}$  hoặc  $m > 1$

Do đó,  $f(x) < 0$  với  $\forall x \in \mathbb{R}$  khi  $m < -\frac{1}{3}$ .

Ví dụ 3: Với giả trị nào của  $m$  thì tam thức bậc hai  $f(x) = (m-5)x^2 - 4mx + m-2$  có hai nghiệm phân biệt bé hơn 2.

*Giải:*

Một tam thức bậc hai có hai nghiệm phân biệt bé hơn 2 khi chỉ khi

$$\begin{cases} \Delta > 0 \text{ (để có nghiệm phân biệt)} \\ af(2) > 0 \text{ (để 2 ở ngoài khoảng hai nghiệm)} \\ 2 > \frac{x_1 + x_2}{2} \text{ (để hai nghiệm bé hơn 2)} \end{cases}$$

Tính toán cụ thể ta có

$$\begin{cases} 3m^2 + 7m - 10 > 0 \\ (m-5)(-3m-22) > 0 \Leftrightarrow \\ \frac{10}{m-5} < 0 \end{cases} \quad \begin{cases} m < -\frac{10}{3} \\ m > 1 \end{cases} \quad \begin{cases} -\frac{22}{3} < m < 5 \\ m < 5 \end{cases}$$

Vậy  $f(x)$  có hai nghiệm phân biệt bé hơn 2 khi

$$-\frac{22}{3} < m < -\frac{10}{3} \text{ hoặc } 1 < m < 5.$$

### BÀI TẬP CHƯƠNG I

#### Bài tập §1, §2, §3, §4

##### 1. Phân tích đa thức thành nhân tử

1. $2x(x + y) + ax + ay$ .
2. $4y^2 - 2m^2$ .
3. $a^2 + a - ab - b$ .
4. $n^2 + 2n - 8$ .
5. $x^4 + 1$ .

##### 2. Chứng minh rằng các đa thức sau nhận các giá trị không âm với các giá trị số khác nhau của $x, y, z$ .

1. $x^2 - 2x + 2y^2 + 8y + 9$ .
2. $(x^2 - xy + y^2)^3 + (x^2 + xy + y^2)^3$ .
3. $x^2 + 19y^2 + 6z^2 - 8xy - 4xz + 12yz$ .

##### 3. a) Chia đa thức $-12x^4 + 4x^3 - 3x^2 + 4x^3 + 8x^2 - 1$ cho đa thức $x^2 + 1$ .

1. Chia đa thức  $12x^4 + 4x^3 + 9x + 3$  cho  $3x - 2$ .

##### 4. Tim dư của phép chia đa thức $x^3 - 3x^2 + 5x + 7$ cho đa thức $2x + 1$ .

##### 5. Xét xem đa thức $x^4 + 4x^3 + 5x + 8$ có chia hết cho

1. $x + 2$ .
2. $x + 1$ .

##### 6. Rút gọn phân thức

$$A = a : \frac{a - 1}{2} - \frac{a^3 + 3a(a - 1)}{2a^2 + 2a} \cdot \frac{-4a}{a^2 + 1 - 2a} - \frac{4a^2}{a^2 - 1}$$

##### 7. Rút gọn biểu thức

$$A = \frac{\sqrt{(x+2)^2} - 8x}{\sqrt{x} - \frac{2}{\sqrt{x}}}$$

### Bài tập §5.

1. Chứng minh rằng  $x^8 - x^7 + x^6 - x^5 + 1 > 0$ ,  $\forall x \in \mathbb{R}$ .

2. Chứng minh rằng với  $n \in \mathbb{N}$ ,  $n > 1$  ta có

$$\frac{1}{n+1} + \frac{1}{n+2} + \dots + \frac{1}{2n} > \frac{1}{2}.$$

3. Chứng minh rằng  $\frac{1}{n+1} + \frac{1}{n+2} + \dots + \frac{1}{3n+1} < 2$ ,  $n \in \mathbb{N}$ .

4. Cho  $n$ ,  $p$  là hai số tự nhiên lớn hơn 1. Chứng minh rằng

$$\frac{1}{n+1} - \frac{1}{n+p+1} < \frac{1}{(n+2)^2} + \dots + \frac{1}{(n+p)^2} < \frac{1}{n} - \frac{1}{n+p}.$$

5. Chứng minh rằng  $\sqrt[n]{n!} \ge \sqrt{n}$ .

6. Chứng minh rằng  $1 + \frac{1}{\sqrt{2}} + \frac{1}{\sqrt{3}} + \dots + \frac{1}{\sqrt{n}} > 2\sqrt{n+1} - 2$ .

7. Chứng minh rằng  $abc > (a+b-c)(a+c-b)(b+c-a)$  nếu  $a$ ,  $b$ ,  $c$ ,  $a+b-c$ ,  $a+c-b$ ,  $b+c-a$  là những số dương.

8. Chứng minh rằng  $\frac{a}{b} + \frac{b}{c} + \frac{c}{a} \ge 3$  nếu  $a$ ,  $b$ ,  $c$  là những số dương.

9. Chứng minh rằng  $\frac{a}{b+c} + \frac{b}{c+a} + \frac{c}{a+b} \ge \frac{3}{2}$  nếu  $a$ ,  $b$ ,  $c$  là những số dương.

10. Chứng minh rằng nếu  $p_1, p_2, \dots, p_n$  là những số dương thì

$$(p_1x_1 + \dots + p_nx_n)^2 \le (p_1 + \dots + p_n)(p_1x_1^2 + \dots + p_nx_n^2).$$

11. Chứng minh rằng  $2 < \left(1 + \frac{1}{n}\right)^n < 3$ .

12. Chứng minh rằng  $\frac{a^2 + 2}{\sqrt{a^4 + 1}} \ge 2$  với mọi  $a \in \mathbb{R}$ .

13. Chứng minh rằng  $a^1 + b^1 + c^1 \ge abc(a + b + c)$  với mọi số thực  $a, b, c$ .

14. Chứng minh

$$a) (x_1 + x_2 + \dots + x_n) \left( \frac{1}{x_1} + \frac{1}{x_2} + \dots + \frac{1}{x_n} \right) \ge n^2$$

với  $x_1, x_2, \dots, x_n$  là những số dương.

$$b) |a_1 + a_2 + \dots + a_n| \le \sqrt{n(a_1^2 + a_2^2 + \dots + a_n^2)}$$

15. Chứng minh  $\frac{a^2}{b+c} + \frac{b^2}{c+a} + \frac{c^2}{a+b} \ge \frac{a+b+c}{2}$  với  $a, b, c$  là những số dương.

16. Chứng minh rằng  $\sqrt{(a+c)(b+d)} \ge \sqrt{ab} + \sqrt{cd}$  với  $a, b, c, d$  là những số dương.

17. Chứng minh rằng, nếu  $a, b$  là các số dương thì

$$(\sqrt{a} + \sqrt{b})^8 \ge 64ab(a+b)^2.$$

18. Tìm giá trị dương nhỏ nhất của hàm số  $f(x) = \frac{2x^3 + 3}{x}$ .

19. Tìm giá trị lớn nhất của hàm số  $g(x) = \frac{x^2}{x^4 + 4}$ .

20. Cho  $(a, b)$  là nghiệm của phương trình  $2x + y = 3$ . Tìm giá trị nhỏ nhất của

$$a) A = a^2 + b^2$$

$$b) B = 2a^2 + b^2$$

### Bài tập §6

1. Xét dấu các tam thức bậc hai

a)  $f(x) = -x^2 + 3x - 5$ .

b)  $f(x) = 2x^2 - 5x + 2$ .

2. Xét dấu biểu thức

$$f(x) = \frac{2x^2 - x - 1}{x^2 - 4}.$$

3. Xét dấu biểu thức  $f(x) = \frac{x-2}{x^2-3x+3}$ .

4. Tìm m để  $f(x) = x^2 - mx + 1$  luôn nhận giá trị dương với mọi x.

## Chương II

## PHƯƠNG TRÌNH. HỆ PHƯƠNG TRÌNH

#### §1. PHƯƠNG TRÌNH MỘT ẨN SỐ

##### 1. Khái niệm phương trình

Cho hai biểu thức đại số một đối số  $f(x)$  và  $g(x)$  có cùng miền xác định  $D \subset K$  ( $K = \mathbb{Q}, \mathbb{R}$  hoặc  $\mathbb{C}$ )

Bài toán tìm tất cả các số  $x_0 \in D$  sao cho  $f(x_0) = g(x_0)$  được gọi là *giải phương trình* một ẩn số  $f(x) = g(x)$ . Đối số  $x$  được gọi là *ẩn số*. Số  $x_0$  được gọi là *một nghiệm* của phương trình  $f(x) = g(x)$ . Tập  $D$  được gọi là *tập xác định* của phương trình.

Tập hợp  $S = \{x_0 \in D: f(x_0) = g(x_0)\}$  là tập các nghiệm của phương trình  $f(x) = g(x)$ . Nếu  $S = \emptyset$  ta nói phương trình vô nghiệm, nếu  $S$  có một phần tử thì ta nói phương trình có một nghiệm duy nhất, nếu  $S$  có vô số phần tử thì ta nói phương trình có vô số nghiệm.

**Ghi chú:** Nếu không chú thích gì thêm, ta luôn hiểu phương trình được xét trên tập  $\mathbb{R}$ .

Ví dụ:

1)  $3x - 1 = 1 - 5x$  có nghiệm là  $x = \frac{1}{4}$

2) Phương trình  $3x^2 - 5x + 4 = 0$  vô nghiệm vì  $3x^2 - 5x + 4 > 0$  với mọi  $x$

#### 2. Phương trình tương đương và phương trình hệ quả

Giả sử  $f_1(x), f_2(x), g_1(x), g_2(x)$  là những biểu thức đại số một đối số trên trường  $K$  và có cùng miền xác định  $D \subset K$ .

**Dịnh nghĩa 1.2.1:** Hai phương trình

$$f_1(x) = g_1(x) \quad (1)$$

$$f_2(x) = g_2(x) \quad (2)$$

được gọi là *tương đương với nhau trên  $K$*  nếu hai tập nghiệm của chúng trùng nhau.

Nói cách khác, hai phương trình (1) và (2) tương đương với nhau nếu mỗi nghiệm của phương trình (1) là nghiệm của phương trình (2) và ngược lại.

Nếu kí hiệu tập nghiệm của phương trình (1) là  $S_1$  còn tập nghiệm của phương trình (2) là  $S_2$  thì

$$(1) \Leftrightarrow (2) \text{ khi và chỉ khi } S_1 = S_2$$

**Dịnh nghĩa 1.2.2:** Phương trình (2) được gọi là hệ quả của phương trình (1) trên trường số  $K$  nếu mỗi nghiệm của phương trình (1) là nghiệm của phương trình (2). Kí hiệu  $(1) \Rightarrow (2)$ .

Như vậy  $(1) \Rightarrow (2)$  khi và chỉ khi  $S_1 \subset S_2$ .

**Chú ý:** Mọi phương trình vô nghiệm trên  $K$  đều tương đương với nhau vì có cùng tập nghiệm là tập rỗng.

Ví dụ:

1) Hai phương trình  $3 - x = \frac{1}{x} - \frac{1}{3}$  và  $3 - x + 2x^2 = \frac{1}{x} - \frac{1}{3} + 2x^2$  là tương đương.

2) Hai phương trình  $x^2 - 1 = 0$  và  $\frac{1}{x-1} = 1 + \frac{1}{x-1}$  không tương đương vì phương trình thứ nhất có hai nghiệm  $x = \pm 1$  còn phương trình thứ hai chỉ có một nghiệm  $x = -1$ .

##### 3. Phép biến đổi tương đương

**Dịnh nghĩa 1.3.1:** Một phép biến đổi thực hiện trên một phương trình để được một phương trình tương đương được gọi là phép biến đổi tương đương.

Một phép biến đổi thực hiện trên một phương trình để được một phương trình hệ quả được gọi là phép biến đổi hệ quả.

Phép biến đổi hằng đẳng mà không làm thay đổi miền xác định là phép biến đổi tương đương.

**Dịnh lý 1.3.1:** Cho phương trình  $f(x) = g(x)$  có tập xác định  $D \subset K$ . Nếu  $h(x)$  có nghĩa trên  $D$  thì phương trình  $f(x) + h(x) = g(x) + h(x)$  tương đương với phương trình đã cho.

**Chứng minh:** Giả sử  $x_0 \in D$ . Khi đó  $h(x_0) \in K$  nên  $f(x_0) = g(x_0) \Leftrightarrow f(x_0) + h(x_0) = g(x_0) + h(x_0)$ . Điều đó có nghĩa các tập nghiệm của hai phương trình là trùng nhau.

**Hệ quả 1.3.1:** Phương trình  $f(x) + h(x) = g(x)$  tương đương với phương trình  $f(x) = g(x) - h(x)$ .

Nói cách khác, chuyển về và đổi dấu một biểu thức của một phương trình ta được một phương trình tương đương.

**Chú ý:** Điều kiện  $h(x)$  có nghĩa trên  $D$  là điều kiện đủ để hai phương trình tương đương nhưng phải là điều kiện át có. Chẳng hạn, trên trường số phức  $C$  hai phương trình

$$x^4 = 1$$

$$\text{và } x^4 - \frac{2}{3x+5} = 1 - \frac{2}{3x+5}$$

là tương đương vì có cùng tập nghiệm là  $\{1, \pm i\}$ , mặc dù  $h(x) = \frac{2}{3x+5}$

không xác định tại  $x = -\frac{5}{3}$ .

**Dịnh lý 1.3.2:** Nếu  $h(x)$  có nghĩa và khác không trên tập xác định  $D$  của phương trình  $f(x) = g(x)$  thì phương trình này và phương trình  $f(x)h(x) = g(x)h(x)$  là tương đương với nhau.

**Chứng minh:** Giả sử  $x_0 \in D$ . Khi đó  $h(x_0) \in K$  và  $h(x_0) \neq 0$  nên  $f(x_0) = g(x_0) \Leftrightarrow f(x_0)h(x_0) = g(x_0)h(x_0)$ .

Điều đó chứng tỏ các tập nghiệm của hai phương trình trùng nhau.

**Hệ quả 1.3.2:** Nhân hai vế của một phương trình với cùng một biểu thức khác không thì được một phương trình tương đương.

Ví dụ:

1) Hai phương trình

$$x^2 - 5x + 6 = 3x - 1$$

$$(x^2 - 5x + 6)(x^3 + x + 1) = (3x - 1)(x^2 + x + 1)$$

là tương đương trên  $R$  vì  $h(x) = x^2 + x + 1 > 0$  với mọi  $x \in R$ . Hai phương trình có cùng nghiệm là 1 và 7.

2) Hai phương trình

$$x^2 - 1 = 3$$

$$(x^2 - 1)(x + 5) = 3(x + 5)$$

không tương đương vì với  $x = -5$  thì  $x + 5 = 0$ . Phương trình đầu có hai nghiệm 2 và  $-2$  còn phương trình thứ hai có ba nghiệm 2,  $-2$  và  $-5$ .

Chú ý: Điều kiện  $h(x)$  có nghĩa và khác không trên D chỉ là điều kiện đủ để hai phương trình  $f(x) = g(x)$  và  $f(x)h(x) = g(x)h(x)$  là tương đương chứ không phải là điều kiện át có. Chẳng hạn, hai phương trình  $x^2 + x + 11 = 8$   $- 3x$  và  $\frac{x^2 + x + 11}{5 - x} = \frac{8 - 3x}{5 - x}$  là tương đương vì cùng có nghiệm là  $-1$  và  $-3$  mặc dù  $\frac{1}{5 - x}$  không xác định tại  $x = 5$ .

##### 4. Giải phương trình

Giải phương trình thực chất là thực hiện liên tiếp các phép biến đổi tương đương để nhận được một phương trình đơn giản có thể thấy ngay nghiệm của nó.

Nếu trong quá trình biến đổi có lục thực hiện phép biến đổi hệ quả thì phương trình nhận được có thêm các nghiệm mà phương trình đầu không có. Những nghiệm đó được gọi là các nghiệm ngoại lai. Để loại chúng ta thực hiện phép thử vào phương trình đầu.

$$\text{Ví dụ: Phương trình } \sqrt{4 - 3x - x^2} = x - 1 \quad (1)$$

Bình phương hai vế ta được

$$\begin{aligned} 4 - 3x - x^2 &= x^2 - 2x + 1 \\ \Leftrightarrow 2x^2 + x - 3 &= 0 \quad (2) \\ \Leftrightarrow x &= 1, x = -\frac{3}{2} \end{aligned}$$

Phương trình (1) chỉ có một nghiệm  $x = 1$ , vì với  $x = -\frac{3}{2}$  thì vế phải của

(1) là một số âm trong khi vế trái là một số dương.

### §2. CÁC PHƯƠNG TRÌNH MỘT ẨN THƯỜNG GẶP

#### 1. Phương trình bậc nhất một ẩn

###### a) Định nghĩa

Dịnh nghĩa 2.1.1: Phương trình bậc nhất một ẩn trên trường số  $K$  là phương trình có dạng chính tắc  $ax = b$ ,  $a$  và  $b$  thuộc  $K$ ,  $a \neq 0$

###### b) Giải và biện luận phương trình $ax = b$

Nếu  $a \neq 0$ , phương trình  $ax = b$  có một nghiệm duy nhất  $x = \frac{b}{a}$

Nếu  $a = 0$  thì phương trình trở thành  $0x = b$ . Vì vậy nếu  $b \neq 0$  phương trình vô nghiệm, nếu  $b = 0$  thì mọi  $x \in K$  đều là nghiệm (Phương trình có vô số nghiệm).

Bằng tóm tắt về giải và biện luận phương trình  $ax = b$

| ax = b            |                                      |
|-------------------|--------------------------------------|
| $a \neq 0$        | Có nghiệm duy nhất $x = \frac{b}{a}$ |
| $a = 0, b \neq 0$ | Vô nghiệm                            |
| $a = 0, b = 0$    | Nghiệm đúng với mọi $x \in K$        |

Ví dụ 1: Giải và biện luận phương trình

$$m^2x + 2 = 4x + m(3m + 5) \quad (1)$$

$$\text{Giải: } (1) \Leftrightarrow (m^2 - 4)x = 3m^2 + 5m - 2$$

Ta xét các trường hợp sau

Nếu  $m \neq \pm 2 \Leftrightarrow m^2 - 4 \neq 0$  thì phương trình có nghiệm duy nhất

$$x = \frac{3m - 1}{m - 2}$$

Nếu  $m = 2$ , phương trình có dạng  $0x = 20$ . Vô nghiệm

Nếu  $m = -2$ , phương trình có dạng  $0x = 0$ . Phương trình nghiệm đúng với mọi  $x \in R$ .

Ví dụ 2: Giải và biện luận theo a, b phương trình sau

$$ax + b = \frac{3x + 2ab}{3} = \frac{1}{2} \quad (2)$$

$$\text{Giải: } (2) \Leftrightarrow 6(a-1)x = 4ab - 6b + 3$$

Nếu  $a \neq 1$ , phương trình có một nghiệm duy nhất

$$x = \frac{4ab - 6b + 3}{6(a-1)}$$

Nếu  $a = 1$ , phương trình trở thành  $0x = -2b + 3$ .

Khi đó, nếu  $b \neq \frac{3}{2}$  thì phương trình vô nghiệm, còn nếu  $b = \frac{3}{2}$  thì phương trình nghiệm đúng với mọi  $x \in \mathbb{R}$ .

Ví dụ 3: Ở một nhà trê, các cháu được chia thành các nhóm, mỗi nhóm có một cô phụ trách. Nếu mỗi nhóm có 6 cháu thì 4 cháu chưa có ai phụ trách. Nếu mỗi nhóm có 8 cháu thì thừa một cô. Hỏi có bao nhiêu cháu và bao nhiêu cô phụ trách?

Giải:

Cọi  $x$  là số cô phụ trách,  $x \in \mathbb{N}$ ,  $x \neq 0$ , thì số cháu ở nhà trê là  $6x + 4$  hoặc  $8(x - 1)$ . Vậy ta có phương trình

$$6x + 4 = 8(x - 1)$$

$$\Leftrightarrow 2x = 12 \Leftrightarrow x = 6$$

Vậy số cô là 6, số cháu là 40.

Chú ý: Ở tiểu học có thể giải như sau

Nếu bắt đầu 2 cháu ở mỗi nhóm 8 cháu thì có 6 cháu trong số đó được cô thừa phụ trách và còn 4 cháu chưa có ai phụ trách. Vậy số cháu bắt ra là  $6 + 4 = 10$  cháu.

$$\text{Số cô là } 10 : 2 + 1 = 6 \text{ cô.}$$

$$\text{Số cháu là } (6 - 1) \cdot 8 = 40 \text{ cháu.}$$

#### 2. Phương trình bậc hai một ẩn

###### a) Định nghĩa

**Dịnh nghĩa 2.2.1:** Phương trình bậc hai đối với ẩn  $x$  trên trường  $K$  là phương trình có dạng chình tắc  $ax^2 + bx + c = 0$  ( $1$ ) a, b, c thuộc  $K$ ,  $a \neq 0$ .

###### b) Cách giải

Ta có  $ax^2 + bx + c = a\left(x + \frac{b}{2a}\right)^2 - \frac{\Delta}{4a^2}$ , trong đó  $\Delta = b^2 - 4ac$  được gọi là biệt số của phương trình (1). Như vậy ta có

Nếu  $\Delta > 0$  thì  $ax^2 + bx + c = 0 \Leftrightarrow x + \frac{b}{2a} = \pm \frac{\sqrt{\Delta}}{2a}$ . Phương trình (1) có hai nghiệm phân biệt

$$x_1 = \frac{-b - \sqrt{\Delta}}{2a}, \quad x_2 = \frac{-b + \sqrt{\Delta}}{2a}$$

Nếu  $\Delta = 0$  thì phương trình (1) có nghiệm kép

$$x_1 = x_2 = -\frac{b}{2a}$$

Nếu  $\Delta < 0$  thì phương trình (1) không có nghiệm thực. Tuy nhiên, trên trường số phức C thì  $\sqrt{\Delta} = \pm i\sqrt{-\Delta}$ . Do đó phương trình có hai nghiệm phức liên hợp

$$x_1 = \frac{-b + i\sqrt{-\Delta}}{2a}, \quad x_2 = \frac{-b - i\sqrt{-\Delta}}{2a}$$

###### Bảng tóm tắt

|              |                      | $ax^2 + bx + c = 0$                                                       |
|--------------|----------------------|---------------------------------------------------------------------------|
|              |                      | $\Delta = b^2 - 4ac$                                                      |
| $\Delta > 0$ | Hai nghiệm phân biệt | $x_{1,2} = \frac{-b \pm \sqrt{\Delta}}{2a}$                               |
| $\Delta = 0$ | Một nghiệm kép       | $x_1 = x_2 = -\frac{b}{2a}$                                               |
| $\Delta < 0$ | Không có nghiệm thực | Có hai nghiệm phức liên hợp $x_{1,2} = \frac{-b \pm i\sqrt{-\Delta}}{2a}$ |

Chú ý: Nếu trong phương trình  $ax^2 + bx + c = 0$  có  $b = 2b'$  thì  $\Delta = 4b'^2 - 4ac = 4(b'^2 - ac)$ .

Kí hiệu  $\Delta' = b^2 - ac$  và gọi là biệt số thu gọn của phương trình. Khi đó trong trường hợp  $\Delta > 0$  (hay  $\Delta' > 0$ ) thì  $x_{1,2} = \frac{-b \pm \sqrt{\Delta'}}{a}$

###### c) Định lý Viet

**Định lý 2.2.1:** Nếu phương trình bậc hai  $ax^2 + bx + c = 0$  có hai nghiệm  $x_1$  và  $x_2$  thì

$$S = x_1 + x_2 = -\frac{b}{a} \quad \text{và} \quad P = x_1 x_2 = \frac{c}{a}.$$

**Định lý 2.2.2:** Nếu  $x_1 + x_2 = S$ ,  $x_1 x_2 = P$  và  $S^2 \ge 4P$  thì hai số  $x_1$ ,  $x_2$  là nghiệm của phương trình bậc hai

$$x^2 - Sx + P = 0$$

Độc giả hãy tự chứng minh các định lý trên.

**Ví dụ 1:** Xác định m để phương trình

$$3x^2 + 4(m-1)x + m^2 - 4m + 1 = 0$$

có hai nghiệm phân biệt  $x_1$ ,  $x_2$  thỏa mãn điều kiện

$$\frac{1}{x_1} + \frac{1}{x_2} = \frac{x_1 + x_2}{2}$$

Giải

Điều kiện để phương trình có hai nghiệm phân biệt khác không

$$\bullet \Delta' = 4(m-1)^2 - 3(m^2 - 4m + 1) = m^2 + 4m + 1$$

$$\Delta' > 0 \Leftrightarrow \begin{cases} m < -2 - \sqrt{3} \\ m > -2 + \sqrt{3} \end{cases}$$

$$\bullet \text{Mặt khác } P = x_1 x_2 = \frac{1}{3}(m^2 - 4m + 1) \neq 0$$

$$\Leftrightarrow m \neq 2 \pm \sqrt{3}$$

$$\text{Ta có } \frac{1}{x_1} + \frac{1}{x_2} = \frac{x_1 + x_2}{2} \Leftrightarrow (x_1 + x_2)\left(\frac{1}{x_1 x_2} - \frac{1}{2}\right) = 0$$

Theo định lý Viet ta có

$$\frac{4(m-1)}{3}\left(\frac{3}{m^2-4m+1} - \frac{1}{2}\right) = 0 \Leftrightarrow \begin{cases} m = -1 \\ m = 1 \\ m = 5 \end{cases}$$

Kết hợp các điều kiện ta có

Phương trình đã cho có hai nghiệm phân biệt thỏa mãn điều kiện của dấu bởi khi  $m = 1$ ,  $m = 5$

$$\text{Vì } \text{đu} 2: \text{ Cho } f(x) = 2x^2 + 2(m+1)x + m^2 + 4m + 3$$

Khi hiệu  $x_1, x_2$  là nghiệm của  $f(x)$ . Hãy tìm giá trị lớn nhất của biểu thức  $A = |x_1 x_2 - 2x_1 - 2x_2|$ .

**Giải:**

Điều kiện để phương trình có hai nghiệm là

$$\Delta' = (m+1)^2 - 2(m^2 + 4m + 3) \ge 0$$

$$\Leftrightarrow (m+1)(-m-5) \ge 0 \Leftrightarrow -5 \le m \le -1 \quad (1)$$

Với điều kiện đó ta có

$$A = \left| \frac{m^2 + 4m + 3}{2} + 2m + 2 \right| = \left| \frac{m^2 + 8m + 7}{2} \right|$$

Ta có  $m^2 + 8m + 7 = (m+1)(m+7)$  nên với  $m$  thỏa mãn điều kiện (1) thì  $m^2 + 8m + 7 \le 0$ . Suy ra

$$A = \frac{-m^2 - 8m - 7}{2} = \frac{9 - (m+4)^2}{2} \le \frac{9}{2}$$

và  $A = \frac{9}{2}$  khi và chỉ khi  $m+4=0$  hay  $m=-4$

Vậy giá trị lớn nhất của  $A$  là  $\frac{9}{2}$ .

**Định lý 2.2.3:** Điều kiện cần và đủ để phương trình  $f(x) = ax^2 + bx + c = 0$  ( $a \ne 0$ ) có một nghiệm  $x_1 = 1$  là  $a+b+c=0$ . Khi đó nghiệm kia là  $x_2 = \frac{c}{a}$

**Định lý 2.2.4:** Điều kiện át có và đủ để phương trình  $ax^2 + bx + c = 0$ ,  $a \ne 0$ , có một nghiệm  $x_1 = -1$  là  $-a-b+c=0$ . Khi đó nghiệm kia là  $x_2 = -\frac{c}{a}$ .

Độc giả hãy tự chứng minh các định lý này.

Ví dụ 3: Giải và biện luận phương trình

$$(1 - 2m + m^2)x^2 + m(2 - m)x - 1 = 0$$

Giải:

$$a = 1 - 2m + m^2 = 0 \Leftrightarrow m = 1$$

Nếu  $m \neq 1$ , khi đó  $a + b + c = 1 - 2m + m^2 + 2m - m^2 - 1 = 0$  nên phương trình có nghiệm  $x_1 = 1$  và  $x_2 = \frac{-1}{1 - 2m + m^2}$ .

Nếu  $m = 1$  thì phương trình trở thành  $x - 1 = 0$ , có nghiệm  $x = 1$ .

Vậy nếu  $m \neq 1$  nghiệm  $x_1 = 1$ ,  $x_2 = \frac{-1}{(m-1)^2}$ .

nếu  $m = 1$ , nghiệm  $x = 1$ .

##### 3. Phương trình bậc ba. Công thức Cardanô

e) Định nghĩa

**Định nghĩa 2.3.1:** Phương trình bậc ba của  $x$  trên trường  $K$  là phương trình có dạng chính tắc

$$ax^3 + bx^2 + cx + d = 0 \quad (1)$$

trong đó  $a, b, c, d$  là các số của trường  $K$ ,  $a \neq 0$

**Nhận xét:** Vì  $a \neq 0$  nên

$$ax^3 + bx^2 + cx + d = a\left(x^3 + \frac{b}{a}x^2 + \frac{c}{a}x + \frac{d}{a}\right) = 0.$$

tương đương với phương trình

$$x^3 + a_1x^2 + b_1x + c_1 = 0, \text{ với } a_1 = \frac{b}{a}, b_1 = \frac{c}{a}, c_1 = \frac{d}{a} \quad (2)$$

Nếu đặt ẩn phụ  $y = x + \frac{a_1}{3} \Leftrightarrow x = y - \frac{a_1}{3}$  thì thay vào (2) ta được

$$\left(y - \frac{a_1}{3}\right)^3 + a_1\left(y - \frac{a_1}{3}\right)^2 + b_1\left(y - \frac{a_1}{3}\right) + c_1 = 0$$

$$\Leftrightarrow y^3 + \left(-\frac{a_1^2}{3} + b_1\right)y + \frac{2a_1^3}{27} - \frac{a_1b_1}{3} + c_1 = 0$$

$$\text{Dặt } p = -\frac{a_1^2}{3} + b_1, q = \frac{2a_1^3}{27} - \frac{a_1b_1}{3} + c_1 \text{ thì ta nhận được phương trình}$$

$$y^3 + py + q = 0 \quad (3)$$

Vậy việc giải phương trình bậc ba (1) được đưa về việc giải phương trình bậc ba thu gọn (3)

###### b) Cách giải

**Bài toán 1:** Giải phương trình  $x^3 + px + q = 0$  trên trường số phức C.

**Giải:**

Dặt ẩn phụ  $x = u + v$ . Khi đó phương trình trở thành

$$(u+v)^3 + p(u+v) + q = 0$$

$$\Leftrightarrow u^3 + v^3 + q + (u+v)(3uv + p) = 0$$

Trong hệ thức trên nếu đặt  $3uv + p = 0$  thì  $u^3 + v^3 + q = 0$  và ta có hệ phương trình của hai ẩn phụ  $u, v$ .

$$\begin{cases} u^3 + v^3 = -q \\ uv = -\frac{p}{3} \end{cases} \Leftrightarrow \begin{cases} u^3 + v^3 = -q \\ u^3 v^3 = -\frac{p^3}{27} \end{cases}$$

Như vậy  $u^3, v^3$  là hai nghiệm của phương trình bậc hai

$$z^3 + qz - \frac{p^3}{27} = 0$$

Giải phương trình này ta được

$$z_1 = -\frac{q}{2} + \sqrt{\frac{q^2}{4} + \frac{p^3}{27}}, \quad z_2 = -\frac{q}{2} - \sqrt{\frac{q^2}{4} + \frac{p^3}{27}}$$

Suy ra

$$u = \sqrt{-\frac{q}{2} + \sqrt{\frac{q^2}{4} + \frac{p^3}{27}}}, \quad v = \sqrt{-\frac{q}{2} - \sqrt{\frac{q^2}{4} + \frac{p^3}{27}}}$$

Do đó nghiệm của phương trình  $x^3 + px + q = 0$  là

$$x = u + v = \sqrt[3]{-\frac{q}{2} + \sqrt{\frac{q^2}{4} + \frac{p^3}{27}}} + \sqrt[3]{-\frac{q}{2} - \sqrt{\frac{q^2}{4} + \frac{p^3}{27}}} \quad (4)$$

Công thức (4) được gọi là công thức Càcđanô mang tên nhà toán học Ý, người tìm ra công thức này năm 1945 là Gerelamo Cardano (1501 – 1576).

**Chú ý:** Trên trường số phức C phương trình  $x^3 + px + q = 0$  có ba nghiệm phức. Ta sẽ chỉ ra cách tìm cụ thể ba nghiệm đó từ công thức Càcđanô.

Ta biết, trên C căn bậc ba của 1 có ba giá trị là

$$1, \varepsilon = -\frac{1}{2} + i\frac{\sqrt{3}}{2}, \varepsilon^2 = -\frac{1}{2} - i\frac{\sqrt{3}}{2}$$

Suy ra u và v có ba giá trị tương ứng là

$$u_1, u_2 = u_1\varepsilon, u_3 = u_1\varepsilon^2$$

$$v_1, v_2 = v_1\varepsilon, v_3 = v_1\varepsilon^2$$

Các cặp  $u, v$  sao cho chúng thỏa mãn hệ thức  $uv = -\frac{p}{3}$ .

$$\text{Giả sử } u_1v_1 = -\frac{p}{3}. \text{ Khi đó}$$

$$u_2v_3 = u_1\varepsilon v_1\varepsilon^2 = u_1v_1 = -\frac{p}{3}$$

$$u_3v_2 = u_1\varepsilon^2 v_1\varepsilon = u_1v_1 = -\frac{p}{3}$$

Vậy có công thức tính ba nghiệm là

$$\begin{cases} x_1 = u_1 + v_1 \\ x_2 = u_2 + v_3 = u_1\varepsilon + v_1\varepsilon^3 \\ x_3 = u_3 + v_2 = u_1\varepsilon^2 + v_1\varepsilon \end{cases} \quad (5)$$

**Ví dụ:** Giải phương trình  $x^3 - 3x^2 - 3x + 11 = 0$  trên C

Giải:

Đặt  $x = y + 1 \Leftrightarrow y = x - 1$ . Ta có

$$(y+1)^3 - 3(y+1)^2 - 3(y+1) + 11 = 0 \Leftrightarrow y^3 - 6y + 6 = 0$$

Áp dụng công thức Cardanô,  $p = -6$ ,  $q = 6$ , ta có

$$u = \sqrt[3]{-3 + \sqrt{9 - \frac{6^2}{27}}} = \sqrt[3]{-2 - \frac{\sqrt{2}}{2}}$$

$$uv = -\frac{p}{3} \Rightarrow v = -\frac{p}{3u} = -\frac{\sqrt{4}}{3u}$$

$$y_1 = u + v = -\frac{\sqrt{2}}{2} - \frac{\sqrt{4}}{3u}$$

$$y_2 = ue + ve^2 = \frac{1}{2} \left( \sqrt[3]{2} + \sqrt[3]{4} \right) + i \frac{\sqrt{3}}{2} \left( \sqrt[3]{4} - \sqrt[3]{2} \right)$$

$$y_3 = ue^3 + ve^3 = \frac{1}{2} \left( \sqrt[3]{2} + \sqrt[3]{4} \right) - i \frac{\sqrt{3}}{2} \left( \sqrt[3]{4} - \sqrt[3]{2} \right)$$

Từ đó suy ra

$$\begin{cases} x_1 = -\frac{\sqrt{2}}{2} - \frac{\sqrt{4}}{3u} \\ x_2 = \frac{1}{2} \left( \sqrt[3]{2} + \sqrt[3]{4} \right) + i \frac{\sqrt{3}}{2} \left( \sqrt[3]{4} - \sqrt[3]{2} \right) + 1 \\ x_3 = \frac{1}{2} \left( \sqrt[3]{2} + \sqrt[3]{4} \right) - 1 - i \frac{\sqrt{3}}{2} \left( \sqrt[3]{4} - \sqrt[3]{2} \right) \end{cases}$$

Bài toán 2: Giải phương trình  $x^3 + px + q = 0$  trên R

Giải: 1) Nếu  $\frac{q^2}{4} + \frac{p^3}{27} > 0 \Rightarrow \sqrt{\frac{q^2}{4} + \frac{p^3}{27}}$  là một số thực. Chọn một căn

bậc ba thực  $u_1$ . Vì  $u_1 v_1 = -\frac{p}{3}$  và  $u_1 \in R$  nên  $v_1 \in R$ . Ta có  $x_1 = u_1 + v_1 \in R$ .

Tính  $x_2, x_3$  theo công thức (5)

$$x_2 = u_1 e + v_1 e^2 = -\frac{u_1 + v_1}{2} + i \frac{(u_1 - v_1)\sqrt{3}}{2}$$

$$x_3 = u_1 e^2 + v_1 e = -\frac{u_1 + v_1}{2} - i \frac{(u_1 - v_1)\sqrt{3}}{2}$$

Vậy  $x_2, x_3$  là hai nghiệm phức liên hợp

$$2) \text{ Nếu } \frac{q^2}{4} + \frac{p^3}{27} = 0 \text{ thì } u = v = \sqrt[3]{-\frac{q}{2}}$$

Chọn  $u_1$  thực thì  $x_1 = 2u_1$  là nghiệm thực của phương trình. Vì  $e^2 + e^3 = -1$  nên

$$x_2 = u_1(e + e^3) = -u_1$$

$$x_3 = u_1(e^2 + e) = -u_1$$

Do đó ta có nghiệm kép  $x_2 = x_3$

3) Nếu  $\frac{q^2}{4} + \frac{p^3}{27} < 0$ . Khi đó hai căn bậc ba trong công thức Cardanô cho ba giá trị của  $u$  và  $v$  từng đôi liên hợp với nhau. Ta chọn  $u_1, v_1$  là hai số phức liên hợp thỏa mãn hệ thức  $u_1 v_1 = -\frac{p}{3} \in \mathbb{R}$ . Khi đó  $x_1 = u_1 + v_1 \in \mathbb{R}$ . Ta tính  $x_2, x_3$  theo công thức (5)

$$x_2 = u_1 e + v_1 e^2 \text{ là một số thực}$$

$$x_3 = u_1 e^2 + v_1 e \text{ là một số thực}$$

Ví dụ: Giải phương trình  $x^3 - 7x + 6 = 0$  trên  $\mathbb{R}$

Giải:

$$p = -7, q = 6 \text{ nên } \frac{q^2}{4} + \frac{p^3}{27} = 9 - \frac{343}{27} < 0$$

Theo chứng minh trên, phương trình có ba nghiệm thực phân biệt tính theo công thức

$$x = \sqrt[3]{-3 + \frac{10\sqrt{3}}{9}i} + \sqrt[3]{-3 - \frac{10\sqrt{3}}{9}i}$$

Tính ra ta được ba nghiệm thực phân biệt là 1, 2, -3.

Chú ý: Bằng cách phân tích ra thừa số ta cũng giải được phương trình trên.

Vì  $1 - 7 + 6 = 0$  nên phương trình có nghiệm  $x_1 = 1$ .

Chia đa thức  $x^3 - 7x + 6$  cho  $x - 1$  ta được

$$x^3 - 7x + 6 = (x-1)(x^2 + x - 6)$$

Phương trình  $x^2 + x - 6 = 0$  có hai nghiệm thực  $x_2 = 2$ ,  $x_3 = -3$

Bằng tóm tắt

1) Giải phương trình trên trường số phức C

$$x^3 + px + q = 0 \quad (p, q \in \mathbb{C})$$

$$x = u + v = \sqrt[3]{-\frac{q}{2} + \sqrt{\frac{q^2}{4} + \frac{p^3}{27}}} + \sqrt[3]{-\frac{q}{2} - \sqrt{\frac{q^2}{4} + \frac{p^3}{27}}}$$

Lấy một giá trị của căn bậc ba  $u_1$  của  $u$

$$\begin{cases} x_1 = u_1 + v_1, \text{ trong đó } u_1, v_1 = -\frac{p}{3} \\ x_2 = u_1 \varepsilon + v_1 \varepsilon^2 \\ x_3 = u_1 \varepsilon^2 + v_1 \varepsilon \end{cases}$$

2) Giải phương trình trên trường số thực R

$$x^3 + px^2 + q = 0 \quad (p, q \in \mathbb{R})$$

$$\frac{q^2}{4} + \frac{p^3}{27} > 0$$

Phương trình có một nghiệm thực

$$\frac{q^2}{4} + \frac{p^3}{27} = 0$$

Phương trình có hai nghiệm thực phân biệt (trong đó có một nghiệm kép) hoặc có nghiệm bội ba.

$$\frac{q^2}{4} + \frac{p^3}{27} < 0$$

Phương trình có ba nghiệm thực phân biệt

4. Phương trình đa thức với hệ số nguyên

Định nghĩa 2.4.1: Phương trình đa thức với hệ số nguyên là phương trình có dạng chính tắc

$$a_n x^n + a_{n-1} x^{n-1} + \dots + a_1 x + a_0 = 0 \quad (1)$$

trong đó  $a_n, a_{n-1}, \dots, a_1, a_0$  là những số nguyên và  $a_n \neq 0$ . Ta chỉ xét việc tìm nghiệm hữu tỉ của phương trình (1)

$$\text{Giải: } (1) \Leftrightarrow \sqrt{2x^2 - mx} = \sqrt{x^2 - 4}$$

$$\Leftrightarrow \begin{cases} 2x^2 - mx = x^2 - 4 & (2) \\ x^2 - 4 \ge 0 & (3) \end{cases}$$

$$(2) \Leftrightarrow x^2 - mx + 4 = 0 \quad (4)$$

$$(3) \Leftrightarrow x \ge 2 \text{ hoặc } x \le -2$$

Vậy phương trình (1) có nghiệm khi và chỉ khi phương trình (4) có nghiệm ngoài khoảng  $(-2, 2)$ . Điều đó tương đương với

$$\begin{cases} m \ge 4 \\ m \le -4 \end{cases}$$

Vậy  $m \le -4$  hoặc  $m \ge 4$  thì phương trình có nghiệm

### §3. HỆ PHƯƠNG TRÌNH

#### 1. Phương trình nhiều ẩn

###### a) Định nghĩa

Cho hai biểu thức đại số  $f(x_1, x_2, \dots, x_n)$  và  $g(x_1, x_2, \dots, x_n)$  có các miền xác định lần lượt là  $D_1$  và  $D_2$ . Kí hiệu

$$D = D_1 \cap D_2$$
 là miền xác định của hai biểu thức và giả sử  $D \neq \emptyset$ .

Bài toán tìm tất cả các bộ số của  $D$  sao cho giá trị của hai biểu thức bằng nhau được gọi là *giải phương trình*  $f(x_1, x_2, \dots, x_n) = g(x_1, x_2, \dots, x_n)$ . Bộ số  $(a_1, a_2, \dots, a_n) \in D$  sao cho  $f(a_1, a_2, \dots, a_n) = g(a_1, a_2, \dots, a_n)$  được gọi là nghiệm của phương trình.

Tập  $S = \{(a_1, a_2, \dots, a_n) \in D: f(a_1, a_2, \dots, a_n) = g(a_1, a_2, \dots, a_n)\}$  được gọi là tập nghiệm của phương trình (1).

Ta nói: Phương trình (1) vô nghiệm nếu  $S = \emptyset$

Phương trình (1) có nghiệm duy nhất nếu  $S$  chỉ có một phần tử.

Phương trình (1) có vô số nghiệm (hoặc vô định) nếu  $S$  có vô số phần tử.

###### b) Các phép biến đổi tương đương

Giả sử  $f_1, f_2, f_3$  là những biểu thức đại số của bộ đối số  $(x_1, x_2, \dots, x_n)$  trên trường K và có miền xác định D.

**Dịnh nghĩa 3.1.1:** Hai phương trình  $f_1 = g_1$  (2) và  $f_2 = g_2$  (3) được gọi là tương đương với nhau trên trường K nếu tập nghiệm của chúng trùng nhau.

Nếu kí hiệu tập nghiệm của phương trình (2) là  $S_1$ , của phương trình (3) là  $S_2$  thì

$$((2) \Leftrightarrow (3)) \Leftrightarrow (S_1 = S_2)$$

**Dịnh nghĩa 3.1.2:** Phương trình  $f_2 = g_2$  (3) được gọi là phương trình hệ quả của phương trình  $f_1 = g_1$  (2) trên trường K nếu mỗi nghiệm của phương trình (2) đều là nghiệm của phương trình (3).

Nói cách khác  $((2) \Rightarrow (3)) \Leftrightarrow (S_1 \subset S_2)$

**Dịnh nghĩa 3.1.3:** Một phép biến đổi thực hiện trên một phương trình để được một phương trình tương đương với nó được gọi là phép biến đổi tương đương. Còn nếu được một phương trình hệ quả thì gọi là phép biến đổi hệ quả.

Dưới đây là các định lý về phép biến đổi tương đương. Cách chứng minh chúng tương tự như đối với phương trình một ẩn (Dịnh lý 1.3.1 và 1.3.2).

**Dịnh lý 3.1.1:** Nếu biểu thức  $h(x_1, x_2, \dots, x_n)$  xác định trên tập xác định D của phương trình  $f = g$  thì phương trình  $f + h = g + h$  tương đương với phương trình đã cho.

**Dịnh lý 3.1.2:** Nếu  $h(x_1, x_2, \dots, x_n)$  xác định và khác không trên tập xác định D của phương trình  $f = g$  thì phương trình  $f h = g h$  tương đương với phương trình đã cho.

#### 2. Hệ phương trình

###### a) Định nghĩa

Giả sử cho m biểu thức đại số  $f_1, f_2, \dots, f_m$  của bộ n đối số  $(x_1, x_2, \dots, x_n)$  xác định trên tập D. Bài toán tìm tất cả các bộ số của D sao cho giá trị của các biểu thức  $f_1, f_2, \dots, f_m$  tương ứng với bộ số đó đều bằng không gọi là giải hệ m phương trình của n ẩn số.

$$\left\{ \begin{array}{l} f_1(x_1, x_2, \dots, x_n) = 0 \\ f_2(x_1, x_2, \dots, x_n) = 0 \\ \dots \\ f_m(x_1, x_2, \dots, x_n) = 0 \end{array} \right. \quad (1)$$

Bộ số  $(a_1, a_2, \dots, a_n) \in D$  sao cho  $f_i(a_1, a_2, \dots, a_n) = 0$  với  $i = 1, 2, \dots, m$  được gọi là một nghiệm của hệ phương trình (1).

Cho hai hệ phương trình của các ẩn số  $x_1, x_2, \dots, x_n$ . Hai hệ phương trình được gọi là tương đương với nhau nếu chúng có cùng tập nghiệm.

Chú ý rằng mọi hệ vô nghiệm đều tương đương với nhau vì có cùng tập nghiệm là tập rỗng.

###### b) Các phép biến đổi tương đương

**Định lý 3.2.1:** Nếu  $f_1(x_1, x_2, \dots, x_n) = 0$  tương đương với phương trình  $x_1 = \varphi(x_2, x_3, \dots, x_n)$  thì hệ phương trình

$$\left\{ \begin{array}{l} f_1(x_1, x_2, \dots, x_n) = 0 \\ f_2(x_1, x_2, \dots, x_n) = 0 \\ \dots \\ f_m(x_1, x_2, \dots, x_n) = 0 \end{array} \right. \quad (2)$$

tương đương với hệ phương trình

$$\left\{ \begin{array}{l} x_1 = \varphi(x_2, \dots, x_n) \\ f_2(\varphi(x_2, \dots, x_n), x_2, x_3, \dots, x_n) = 0 \\ \dots \\ f_m(\varphi(x_2, \dots, x_n), x_2, x_3, \dots, x_n) = 0 \end{array} \right. \quad (3)$$

**Chứng minh:** Giả sử  $(a_1, a_2, \dots, a_n) \in D$  là nghiệm của phương trình  $f_1(x_1, x_2, \dots, x_n) = 0$  thì nó là nghiệm của phương trình  $x_1 = \varphi(x_2, x_3, \dots, x_n)$  và ngược lại, tức là

$$f_1(a_1, a_2, \dots, a_n) = 0 \Leftrightarrow a_1 = \varphi(a_2, a_3, \dots, a_n)$$

$$f_i(a_1, a_2, \dots, a_n) = 0 \Leftrightarrow f_i = (\varphi(a_2, \dots, a_n), a_2, \dots, a_n) = 0$$

$$i = 2, 3, \dots, m$$

Điều đó chứng tỏ (2)  $\Leftrightarrow$  (3)

Dịnh lí trên cho phép đưa bài toán giải hệ phương trình của  $n$  ẩn số về việc giải hệ phương trình của  $n-1$  ẩn số. Đó là phương pháp khử ẩn bằng phép thế.

Ví dụ: Giải hệ phương trình

$$\begin{cases} y - x = 1 \\ x^2 - y^2 + 4x = 1 \end{cases}$$

Giải: Vì  $y - x = 1 \Leftrightarrow y = x + 1$ . Vây hệ đã cho tương đương với hệ

$$\begin{cases} y = x + 1 \\ x^2 - (x+1)^2 + 4x = 1 \end{cases} \Leftrightarrow \begin{cases} y = x + 1 \\ 2x = 2 \end{cases}$$

Vây nghiệm của hệ là  $\begin{cases} x = 1 \\ y = 2 \end{cases}$

**Dịnh lí 3.2.2:** Giả sử  $k_{ij} \in K$ ,  $k_{ij} \neq 0$ . Khi đó hai hệ phương trình sau là tương đương.

$$\begin{cases} f_1 = 0 \\ f_2 = 0 \\ \dots \\ f_m = 0 \end{cases} \quad \Leftrightarrow \quad \begin{cases} f_1 = 0 \\ k_{12}f_1 + k_{22}f_2 = 0 \\ \dots \\ k_{1m}f_1 + k_{2m}f_2 + \dots + k_{mm}f_m = 0 \end{cases} \quad (5)$$

**Chứng minh:** Giả sử  $(a_1, a_2, \dots, a_n) \in D$  là nghiệm của phương trình  $f_i = 0$ , nghĩa là  $f_i(a_1, a_2, \dots, a_n) = 0$  với  $i = 1, 2, \dots, m$ .

Khi đó, rõ ràng ta có

$$\begin{aligned} k_{ii}f_i(a_1, a_2, \dots, a_n) + \dots + k_{ii}f_i(a_1, a_2, \dots, a_n) &= 0 \\ (i = 2, 3, \dots, m) \end{aligned}$$

Ngược lại, nếu  $(a_1, a_2, \dots, a_n) \in D$  là nghiệm của hệ phương trình (5) thì  $f_i(a_1, a_2, \dots, a_n) = 0$ . Do đó, từ  $k_{12}f_1 + k_{22}f_2 = 0$  suy ra  $f_2(a_1, a_2, \dots, a_n) = 0$ .

Lí luận tương tự ta có

$$f_3(a_1, a_2, \dots, a_n) = 0, \dots, f_m(a_1, a_2, \dots, a_n) = 0$$

Vậy  $(a_1, a_2, \dots, a_n)$  là nghiệm của hệ (4).

Dịnh lí trên cho phép biến đổi tương đương một hệ phương trình về một hệ phương trình mà về trái là tổ hợp tuyến tính các về trái của hệ phương trình ban đầu. Đó là phương pháp cộng đại số.

Ví dụ: Giải hệ phương trình

$$\begin{cases} f_1 = x^2 + y^2 + 3y + 1 = 0 \\ f_2 = x^2 + y^2 + y - 3 = 0 \end{cases}$$

Giải: Hệ đã cho tương đương với hệ

$$\begin{cases} f_1 = x^2 + y^2 + 3y + 1 = 0 \\ f_1 - f_2 = 2y + 4 = 0 \end{cases} \Leftrightarrow \begin{cases} x^2 + y^2 + 3y + 1 = 0 \\ y = -2 \end{cases}$$

$$\Leftrightarrow \begin{cases} x = 1 \\ y = -2 \end{cases} \text{ và } \begin{cases} x = -1 \\ y = -2 \end{cases}$$

Phép biến đổi một hệ phương trình thành một hệ phương trình tương đương với nó được gọi là phép biến đổi tương đương. Giải hệ phương trình là thực hiện liên tiếp các phép biến đổi tương đương cho đến khi tính được nghiệm.

### §4. CÁC HỆ PHƯƠNG TRÌNH THƯỜNG GẶP

#### 1. Hệ phương trình tuyến tính trên trường số K

###### a) Định nghĩa

Dịnh nghĩa 4.1.1: Hệ m phương trình tuyến tính (hoặc bậc nhất) của n ẩn số  $x_1, x_2, \dots, x_n$  là hệ phương trình có dạng:

$$\begin{cases} a_{11}x_1 + a_{12}x_2 + \dots + a_{1n}x_n = b_1 \\ a_{21}x_1 + a_{22}x_2 + \dots + a_{2n}x_n = b_2 \\ \dots \dots \dots \\ a_{m1}x_1 + a_{m2}x_2 + \dots + a_{mn}x_n = b_m \end{cases} \quad (1)$$

trong đó  $a_{ij}$  và  $b_i$  thuộc trường K;  $i = 1, 2, \dots, m$ ;  $j = 1, 2, \dots, n$ . Với hệ phương trình (1) ta lập các bảng số

$$A = \begin{bmatrix} a_{11} & a_{12} & \dots & a_{1n} \\ a_{21} & a_{22} & \dots & a_{2n} \\ \vdots & \vdots & \ddots & \vdots \\ a_{m1} & a_{m2} & \dots & a_{mn} \end{bmatrix}, \quad B = \begin{bmatrix} a_{11} & a_{12} & \dots & a_{1n} & b_1 \\ a_{21} & a_{22} & \dots & a_{2n} & b_2 \\ \vdots & \vdots & \ddots & \vdots & \vdots \\ a_{n1} & a_{n2} & \dots & a_{nn} & b_n \end{bmatrix}$$

Các bảng số A và B được gọi là **lần lượt là ma trận hệ số** và **ma trận mở rộng** của hệ (1).

**Dịnh nghĩa 4.1.2:** Các phép biến đổi tương đương sau đây của hệ phương trình tuyến tính được gọi là các phép biến đổi sơ cấp.

1) **Đổi chỗ hai phương trình** của hệ cho nhau

2) **Nhân hai về của một phương trình với cùng một số khác không**

3) **Cộng vào hai về của một phương trình các về tương ứng của phương trình khác sau khi đã nhân với cùng một số khác không.**

b) **Các dạng đặc biệt của hệ phương trình tuyến tính**

**Dịnh nghĩa 4.1.3:** Cho hệ phương trình tuyến tính (1)

Nếu  $b_1 = b_2 = \dots = b_m = 0$  thì hệ (1) được gọi là **hệ phương trình tuyến tính thuần nhất**.

Nếu A là ma trận vuông ( $m = n$ ) có các phần tử  $a_{ij} \neq 0$ , các phần tử  $a_{ij} = 0$  với mọi  $j < i$  (các phần tử nằm ở phía góc dưới bên trái của A) thì A gọi là **ma trận tam giác và hệ phương trình (1) được gọi là hệ tam giác.**

Nếu  $m < n$  (tức A và B là các ma trận chữ nhật nằm ngang) mà  $a_{ij} = 0$  với  $j < i$  thì B gọi là **ma trận hình thang** và hệ phương trình (1) được gọi là **hệ hình thang**. Ta quy ước trong ma trận hình thang không có dòng nào mà mọi phần tử đều bằng không hoặc nếu có thì các dòng đó là những dòng cuối cùng của ma trận.

c) **Cách giải hệ phương trình tuyến tính**

1) **Giải hệ tam giác**

$$\begin{cases} a_{11}x_1 + a_{12}x_2 + \dots + a_{1n}x_n = b_1 \\ a_{22}x_2 + \dots + a_{2n}x_n = b_2 \\ \vdots \\ a_{nn}x_n = b_n \end{cases}$$

Dùng phương pháp thế ẩn liên tiếp từ dưới lên  $x_n, x_{n-1}, \dots, x_1$  ta được một nghiệm duy nhất của hệ phương trình.

Ví dụ: Giải hệ phương trình

$$\begin{cases} 2x_1 + x_2 - x_3 = 5 \\ -x_2 - 3x_3 = 1 \\ -7x_3 = 7 \end{cases}$$

Giải: Từ  $-7x_3 = 7$  suy ra  $x_3 = -1$ . Thay  $x_3 = -1$  vào phương trình thứ hai ta được

$$-x_2 + 3 = 1 \Rightarrow x_2 = 2$$

Thay  $x_3 = -1$  và  $x_2 = 2$  vào phương trình thứ nhất ta được

$$2x_1 + 2 + 1 = 5 \Rightarrow x_1 = 1$$

Vậy hệ có một phương trình duy nhất  $(1, 2, -1)$

2) Giải hệ hình thang

$$\begin{cases} a_{11}x_1 + a_{12}x_2 + a_{13}x_3 + \dots + a_{1n}x_n = b_1 \\ a_{22}x_2 + a_{23}x_3 + \dots + a_{2n}x_n = b_2 \\ \dots \\ a_{sn}x_s + \dots + a_{sn}x_n = b_s \end{cases}$$

trong đó  $s < n$  (số phương trình nhỏ hơn số ẩn),  $a_{ii} \neq 0$  với  $i = 1, 2, \dots, s$ . Ta chuyển các số hạng chứa  $x_{s+1}, \dots, x_n$  sang về phải

$$\begin{cases} a_{11}x_1 + a_{12}x_2 + \dots + a_{1s}x_s = b_1 - a_{1(s+1)}x_{s+1} - \dots - a_{1n}x_n \\ a_{22}x_2 + \dots + a_{2s}x_s = b_2 - a_{2(s+1)}x_{s+1} - \dots - a_{2n}x_n \\ \dots \\ a_{ss}x_s = b_s - a_{s(s+1)}x_{s+1} - \dots - a_{sn}x_n \end{cases}$$

Gắn cho các ẩn  $x_{s+1}, \dots, x_n$  các giá trị xác định tùy ý

$$x_{s+1} = \alpha_{s+1}, \dots, x_n = \alpha_n$$

ta được một hệ tam giác. Giải hệ tam giác này ta xác định  $x_1 = \alpha_1, x_2 = \alpha_2, \dots, x_s = \alpha_s$ .

Khi đó  $(\alpha_1, \alpha_2, \dots, \alpha_{s+1}, \dots, \alpha_n)$  là một nghiệm của hệ phương trình. Vì có thể lấy tùy ý các giá trị  $\alpha_{s+1}, \dots, \alpha_n$  nên hệ phương trình có vô số nghiệm.

Ta gọi các ẩn  $x_{s+1}, \dots, x_n$  là các ẩn tự do còn các ẩn  $x_1, x_2, \dots, x_s$  là các ẩn chính.

Ví dụ: Giải hệ phương trình

$$\begin{cases} x_1 + 2x_2 + 4x_3 + 6x_4 = 1 \\ -2x_2 + x_3 - x_4 = 2 \end{cases}$$

Giải: Hệ đã cho tương đương với hệ

$$\begin{cases} x_1 + 2x_2 = 1 - 4x_3 - 6x_4 \\ -2x_2 = 2 - x_3 + x_4 \end{cases}$$

Gắn cho các ẩn tự do các giá trị tuy ý  $x_3 = \alpha$ ,  $x_4 = \beta$  ta được hệ tam giác

$$\begin{cases} x_1 + 2x_2 = 1 - 4\alpha - 6\beta \\ -2x_2 = 2 - \alpha + \beta \end{cases}$$

$$\text{Giải ra ta được } x_2 = -1 + \frac{1}{2}\alpha - \frac{1}{2}\beta$$

$$x_1 = 3 - 5\alpha - 5\beta$$

Vậy nghiệm của hệ đã cho là

$$(3 - 5\alpha - 5\beta, -1 + \frac{1}{2}\alpha - \frac{1}{2}\beta, \alpha, \beta)$$

trong đó  $\alpha, \beta$  là hai số tùy ý.

3) Giải hệ phương trình tuyến tính tổng quát bằng phương pháp khử dần liên tiếp (phương pháp của Gaoxd).

Bằng các phép biến đổi sơ cấp ta đưa hệ phương trình tuyến tính tổng quát về hệ tam giác hoặc hệ hình thang rồi dùng cách giải đã biết đối với các hệ đặc biệt đó.

Xét hệ phương trình

$$\begin{cases} a_{11}x_1 + a_{12}x_2 + \dots + a_{1n}x_n = b_1 & (1) \\ a_{21}x_2 + a_{22}x_3 + \dots + a_{2n}x_n = b_2 & (2) \\ \dots & \\ a_{m1}x_1 + a_{m2}x_2 + \dots + a_{mn}x_n = b_m & (m) \end{cases} \quad (I)$$

Đầu tiên ta khử ẩn  $x_1$  từ phương trình (2) trở xuống bằng cách cộng vào hai vế của các phương trình (i) hai vế tương ứng của phương trình (1) sau khi nhân với  $-\frac{a_{1i}}{a_{11}}$ ,  $i = 2, \dots, m$

Ta được hệ phương trình

$$\begin{cases} a_{11}x_1 + a_{12}x_2 + \dots + a_{1n}x_n = b_1 \\ a_{22}x_2 + \dots + a'_{2n}x_n = b'_2 \\ \dots \\ a'_{m2}x_2 + \dots + a'_{mn}x_n = b'_n \end{cases} \quad (\text{II})$$

Hệ (II) tương đương với hệ (I).

Trong hệ (II) có thể xuất hiện các phương trình dạng đặc biệt sau đây

$$0.x_1 + 0.x_2 + \dots + 0.x_n = 0$$

$$\text{hoặc} \quad 0.x_1 + 0.x_2 + \dots + 0.x_n = b \neq 0$$

Nếu gặp phương trình thứ nhất (phương trình luôn nghiệm đúng với mọi  $x_1, x_2, \dots, x_n$ ) thì ta loại bỏ phương trình khởi hệ, còn nếu gặp phương trình thứ hai thì ta kết luận hệ phương trình (I) là vô nghiệm.

Tiếp theo, trong hệ (II) ta khử ẩn  $x_2$  từ phương trình thứ ba trở xuống. Quá trình khử ẩn liên tiếp sẽ kết thúc sau một số hữu hạn bước. Ta sẽ gặp một trong ba trường hợp sau

1) Hệ thu được có phương trình vô nghiệm

2) Hệ thu được là hệ tam giác

3) Hệ thu được là hệ hình thang

Khi đó, nếu gặp trường hợp thứ nhất thì hệ vô nghiệm, nếu gặp hai trường hợp sau thì ta đã biết cách giải.

Ví dụ 1: Giải hệ phương trình

$$\begin{cases} x_1 + 2x_2 = -1 \quad (1) \\ 3x_1 - 5x_2 = 8 \quad (2) \\ -2x_1 + 7x_2 = -9 \quad (3) \end{cases} \quad (\text{I})$$

Giải: Bước 1: Khử  $x_1$  trong các phương trình (2) và (3)

$$\text{(I)} \Leftrightarrow \begin{cases} x_1 + 2x_2 = -1 \\ -11x_2 = 11 \\ 11x_2 = -11 \end{cases} \quad (\text{II})$$

Bước 2: Khử  $x_1$  trong phương trình thứ ba

$$(II) \Leftrightarrow \begin{cases} x_1 + 2x_2 = -1 \\ -11x_2 = 11 \\ 0x_2 = 0 \end{cases}$$

Loại bỏ phương trình thứ ba, giải hệ tam giác ta được nghiệm duy nhất của phương trình là  $(1, -1)$

Chú ý: Ta nhận thấy rằng việc biến đổi tương đương một hệ phương trình tuyến tính thực chất là biến đổi các số trong ma trận mở rộng của nó. Do đó có thể chỉ cần viết quá trình biến đổi ở ma trận mở rộng. Chẳng hạn quá trình biến đổi trên đây có thể biểu diễn như sau

$$\begin{bmatrix} 1 & 2 & -1 \\ 3 & -5 & 8 \\ -2 & 7 & -9 \end{bmatrix} \rightarrow \begin{bmatrix} 1 & 2 & -1 \\ 0 & -11 & 11 \\ 0 & 11 & -11 \end{bmatrix} \rightarrow \begin{bmatrix} 1 & 2 & -1 \\ 0 & -11 & 11 \\ 0 & 0 & 0 \end{bmatrix}$$

Đó là quy tắc thực hành để giải hệ phương trình tuyến tính

Ví dụ 2: Giải hệ

$$\begin{cases} x_1 + 2x_2 - 5x_3 + x_4 = 1 \\ -2x_2 - 3x_2 + 7x_3 + 3x_4 = 4 \\ 3x_1 + 8x_2 - 11x_3 - 3x_4 = -2 \\ -x_1 + 5x_2 + 4x_3 + 2x_4 = 10 \end{cases}$$

Giải: Thực hiện phép biến đổi trên ma trận mở rộng của hệ

$$\begin{bmatrix} 1 & 2 & -5 & 1 & 1 \\ -2 & -3 & 7 & 3 & 4 \\ 3 & 8 & -11 & -3 & -2 \\ -1 & 5 & 4 & 2 & 10 \end{bmatrix} \rightarrow \begin{bmatrix} 1 & 2 & -5 & 1 & 1 \\ 0 & 1 & -3 & 5 & 6 \\ 0 & 2 & 4 & -6 & -5 \\ 0 & 7 & -1 & 3 & 11 \end{bmatrix}$$

$$\rightarrow \begin{bmatrix} 1 & 2 & -5 & 1 & 1 \\ 0 & 1 & -3 & 5 & 6 \\ 0 & 0 & 10 & -16 & -17 \\ 0 & 0 & 20 & -32 & -31 \end{bmatrix} \rightarrow \begin{bmatrix} 1 & 2 & -5 & 1 & 1 \\ 0 & 1 & -3 & 5 & 6 \\ 0 & 0 & 10 & -16 & -17 \\ 0 & 0 & 0 & 0 & 3 \end{bmatrix}$$

Hệ có một phương trình vô nghiệm. Vậy hệ vô nghiệm.

Ví dụ 3: Giải hệ phương trình

$$\begin{cases} x_1 + 2x_2 - 2x_3 + x_4 = 0 \\ -4x_1 - x_2 + 10x_3 - 5x_4 = 0 \\ -2x_1 + 3x_2 + 7x_3 - 2x_4 = 0 \end{cases}$$

Giải: Biến đổi trên ma trận mở rộng

$$\begin{bmatrix} 1 & 2 & -2 & 1 \\ -4 & -1 & 10 & -5 \\ -2 & 3 & 7 & -2 \end{bmatrix} \rightarrow \begin{bmatrix} 1 & 2 & -2 & 1 \\ 0 & 7 & 2 & -1 \\ 0 & 7 & 3 & 0 \end{bmatrix} \rightarrow \begin{bmatrix} 1 & 2 & -2 & 1 \\ 0 & 7 & 2 & -1 \\ 0 & 0 & 1 & 1 \end{bmatrix}$$

Hệ phương trình nhận được có dạng

$$\begin{cases} x_1 + 2x_2 - 2x_3 + x_4 = 0 \\ 7x_2 + 2x_3 - x_4 = 0 \Leftrightarrow \begin{cases} x_1 + 2x_2 - 2x_3 = -x_4 \\ 7x_2 + 2x_3 = x_4 \\ x_3 + x_4 = 0 \end{cases} \end{cases}$$

Gán cho  $x_4$  giá trị tùy ý.  $x_4 = t$ , ta tính được

$$x_3 = -t, x_2 = \frac{3}{7}t, x_1 = -\frac{27}{7}t$$

Vậy nghiệm của hệ đã cho là

$$\left( -\frac{27}{7}t, \frac{3}{7}t, -t, t \right)$$

trong đó  $t$  là một số tùy ý.

**Nhận xét:** Hệ phương trình thuần nhất có ít nhất một nghiệm  $(0, 0, \dots, 0)$  gọi là nghiệm tầm thường.

Nếu hệ phương trình tuyến tính thuần nhất có số phương trình bé hơn số ẩn thì sau một số hữu hạn phép biến đổi ta đưa được nó về dạng hệ hình thang. Do đó hệ có vô số nghiệm.

#### 2. Hệ phương trình bậc cao trên $\mathbb{R}$

###### a) Hệ phương trình thuần nhất bậc cao

Biểu thức đại số  $f(x_1, x_2, \dots, x_n)$  được gọi là **thuần nhất** (hay **đẳng cấp**) cấp  $k$  đối với các đối số  $x_i$  ( $i = 1, 2, \dots, n$ ) nếu với  $t \in \mathbb{R}$ , ta có

$$f(t x_1, t x_2, \dots, t x_n) = t^k f(x_1, x_2, \dots, x_n)$$

Ví dụ:

$$1) f(x, y) = x^2y^2 + 8x^2y^2 - 3xy^3 + 7y^4 \text{ là thuần nhất cấp 4 vì } f(tx, ty) = t^4 f(x, y)$$

$$2) f(x, y, z) = \frac{x^2y^2 + y^2z^2 + z^2x^2}{x + 2y + 3z} \text{ là thuần nhất bậc ba vì } f(tx, ty, tz) = t^3 f(x, y, z).$$

Một hệ phương trình được gọi là **thuần nhất** nếu mỗi phương trình của hệ đều có dạng  $f(x_1, x_2, \dots, x_n) = a$ , trong đó  $a$  là hằng số,  $f(x_1, x_2, \dots, x_n)$  là biểu thức thuần nhất.

Ta xét cách giải hệ phương trình thuần nhất hai ẩn:

$$\begin{cases} f_1(x, y) = a \\ f_2(x, y) = b \end{cases}$$

Đưa vào ẩn phụ  $t$  bằng cách đặt  $y = tx$  hoặc  $x = ty$ . Sau đó thay  $y = tx$  (hoặc  $x = ty$ ) vào hệ phương trình thì sẽ khử được  $x, y$  và tìm được  $t$ . Từ giá trị cụ thể của  $t$  ta tính được  $x, y$ .

Ví dụ: Giải hệ phương trình

$$\begin{cases} y^3 - x^3 = 1 \\ y^2x - 2xy^2 + x^3 = -2 \end{cases} \quad (1)$$

**Giải:** Ta thấy rằng  $x \neq 0$ . Đặt  $y = tx$ , thay vào hệ phương trình ta được

$$\begin{cases} x^3(t^3 - 1) = 1 \\ x^3(t^3 - 2t + 1) = -2 \end{cases} \quad (1')$$

Từ đó ta có:

$$2x^3(t^3 - 1) = -x^3(t^2 - 2t + 1) \text{ hay } x^3(t - 1)(2t^2 + 3t + 1) = 0$$

$$\text{Rút gọn cho } x^3 \text{ ta được } t = 1, t = -1, t = -\frac{1}{2}$$

Thay lần lượt giá trị của  $t$  vào phương trình đầu của hệ (1'). Ta có

Với  $t = 1$  hệ vô nghiệm

$$\text{Với } t = -\frac{1}{2} \text{ ta có } x^3(-\frac{1}{8} - 1) = 1 \Rightarrow x^3 = -\frac{8}{9} \Rightarrow x = -\frac{2\sqrt[3]{3}}{3} \text{ và } y = \frac{\sqrt[3]{3}}{3}$$

$$\text{Với } t = -1 \text{ thì } x^4 = -\frac{1}{2} \Rightarrow x = -\frac{\sqrt[4]{4}}{2} \text{ và } y = \frac{\sqrt[4]{4}}{2}$$

Vậy nghiệm của hệ

$$\left( -\frac{2\sqrt[4]{3}}{3}, \frac{\sqrt[4]{3}}{3} \right), \left( -\frac{\sqrt[4]{4}}{2}, \frac{\sqrt[4]{4}}{2} \right)$$

###### b) Hệ đối xứng

Một hệ phương trình được gọi là hệ đối xứng nếu thực hiện một phép hoán vị trên các ẩn thì mỗi phương trình của hệ lại chuyển thành một phương trình của hệ và toàn bộ hệ không thay đổi.

Dễ giải hệ khác phương trình đối xứng hai ẩn trên R

$$\{f(x, y) = a$$

$$\{g(x, y) = b$$

ta thường dùng một trong hai cách đặt ẩn phụ sau đây

Cách 1: Đặt  $y = tx$  hoặc  $x = ty$

Cách 2: Đặt  $u = x + y$ ,  $v = xy$  với điều kiện  $u^2 \ge 4v$

Ví dụ 1: Giải hệ phương trình

$$\begin{cases} x^2 = 3x - y \\ y^2 = 3y - x \end{cases} \quad (1)$$

Giải: Đặt  $y = tx$ , ta có

$$x^2 = x(3 - t)$$

$$t^2 x^2 = x(3t - x)$$

$$\text{Khi đó, } t^3 - 3t^2 + 3t - 1 = 0 \Rightarrow (t-1)^3 = 0 \Rightarrow t = 1$$

$$\Rightarrow y = x \Rightarrow \text{hoặc } x = y = 0 \text{ hoặc } x = y = 2$$

Vậy hệ có hai nghiệm  $(0, 0)$  và  $(2, 2)$

Ví dụ 2: Giải hệ phương trình

$$x^4 + y^4 = 82$$

$$x + y^2 = 2$$

**Giải:** Đặt  $u = x + y$ ,  $v = xy$  ta có

$$x^1 + y^1 = (x^2 + y^2)^2 - 2x^2y^2 = [(x + y)^2 - 2xy]^2 - 2x^2y^2$$

Vậy ta có hệ phương trình của hai ẩn phụ  $u, v$

$$\begin{cases} (u^2 - 2v)^2 - 2v^2 = 82 \\ u = 2 \end{cases}$$

Thay  $u = 2$  vào phương trình đầu ta được

$$v^2 - 8v - 33 = 0 \rightarrow v_1 = -3, v_2 = 11$$

Từ đó ta có hai hệ phương trình

$$\begin{cases} x + y = 2 \\ xy = -3 \end{cases} \quad \begin{cases} x + y = 2 \\ xy = 11 \end{cases}$$

Hệ phương trình thứ nhất cho hai nghiệm  $(-1, 3)$  và  $(3, -1)$

Hệ phương trình thứ hai vô nghiệm.

Vậy hệ phương trình đã cho có hai nghiệm  $(-1; 3), (3; -1)$ .

c) Các hệ phương trình khác

Ta nên một số cách giải hệ phương trình ba ẩn bậc cao qua các ví dụ.

Ví dụ 1: Giải hệ phương trình

$$\begin{cases} xy = 2 \\ xz = 3 \\ yz = 6 \end{cases}$$

**Giải:** Nhân vế với vế của cả ba phương trình ta được  $x^2y^2z^2 = 36$ . Suy ra  $xyz = \pm 6$ . Chia phương trình này cho các phương trình của hệ (chia vế với vế) ta nhận được hai nghiệm của hệ phương trình là  $(1, 2, 3)$  và  $(-1, -2, -3)$ .

Ví dụ 2: Giải hệ phương trình

$$\begin{cases} x + y + z = 0 \\ x^2 + y^2 - z^2 = 20 \\ x^4 + y^4 - z^4 = 560 \end{cases}$$

**Giải:** Từ phương trình thứ nhất ta có  $x + y = -z$ .

Từ phương trình thứ hai ta có  $x^2 + y^2 = (x + y)^2 - 2xy = 20 + z^2$

Suy ra  $z^2 - 2xy = 20 + z^2$  hay  $xy = -10$

Từ phương trình thứ ba ta có

$$x^1 + y^1 = (x^2 + y^2)^2 - 2x^2y^2 = 560 + z^1$$

$$\Leftrightarrow (20 + z^2)^2 - 200 = 560 + z^1$$

$$\Leftrightarrow 40z^2 = 360 \Leftrightarrow z = \pm 3$$

Do đó  $x + y = -z = \pm 3$

Cùng với  $xy = -10$  ta tìm được 4 nghiệm của hệ phương trình  
(5, -2, -3), (-2, 5, -3), (-5, 2, 3), (2, -5, 3).

d) Hệ phương trình vô tỉ

Ta lấy một số ví dụ về hệ phương trình vô tỉ.

Ví dụ 1: Giải hệ

$$\left\{ \begin{array}{l} \sqrt{\frac{2x-1}{y+2}} + \sqrt{\frac{y+2}{2x-1}} \\ x + y = 2 \end{array} \right. \quad (1) \quad (2)$$

Giải: Điều kiện  $(2x-1)(y+2) > 0$

$$\Leftrightarrow \begin{cases} x > \frac{1}{2}, y > -2 \\ x < \frac{1}{2}, y < -2 \end{cases}$$

Đặt  $t = \frac{2x-1}{y+2}$ ,  $t > 0$ , ta có

$$\begin{aligned} (1) &\Leftrightarrow \sqrt{t} + \frac{1}{\sqrt{t}} = 2 \Leftrightarrow (\sqrt{t} - 1)^2 = 0 \Leftrightarrow t = 1 \text{ hay } \frac{2x-1}{y+2} = 1 \\ &\Leftrightarrow 2x - 1 = y + 2 \end{aligned} \quad (3)$$

$$(2) \Leftrightarrow y = 2 - x. \text{ Thay vào (3) ta được } x = \frac{5}{3}, y = \frac{1}{3}$$

Vậy nghiệm của hệ là  $\left(\frac{5}{3}, \frac{1}{3}\right)$

Ví dụ 2: Giải hệ

$$\begin{cases} \sqrt{x^2 + y^2} + \sqrt{2xy} = 8\sqrt{2} \\ \sqrt{x} + \sqrt{y} = 4 \end{cases}$$

Giải:

Đặt  $u = \sqrt{x} \ge 0$ ,  $v = \sqrt{y} \ge 0$ , ta có hệ

$$\begin{cases} \sqrt{u^4 + v^4} + \sqrt{2}uv = 8\sqrt{2} \\ u + v = 4 \end{cases}$$

Đặt  $S = u + v$ ,  $P = uv$ ,  $S^2 \ge 4P$  ta được  $S = 4$ ,  $P = 4$

Vậy  $u, v$  là các nghiệm của phương trình

$$t^2 - 4t + 4 = 0 \Leftrightarrow t_1 = t_2 = 2$$

Suy ra  $u = v = 2 \Rightarrow x = y = 4$

Vậy nghiệm của hệ là  $(4, 4)$

### §5. ÁP DỤNG VÀO VIỆC GIẢNG DẠY TOÁN Ở TIỂU HỌC

Nhiều bài toán ở tiểu học có thể giải bằng cách lập phương trình hoặc hệ phương trình. Không những thế, việc giải các bài toán đó bằng cách lập phương trình hoặc hệ phương trình giúp định hướng hoặc suy ra trực tiếp cách giải các bài toán đó ở tiểu học. Ta sẽ minh hoạ điều đó trên các ví dụ cụ thể.

Ví dụ 1: 3 lọ nước đỏ và 2 lọ nước xanh giá 2300 đồng

2 lọ nước đỏ và 3 lọ nước xanh giá 2200 đồng

Tính giá tiền một lọ nước mỗi loại.

• Giải bài toán bằng cách lập hệ phương trình

Gọi  $x$  là giá tiền 1 lọ nước đỏ,  $y$  là giá tiền 1 lọ nước xanh (điều kiện  $x > 0$ ,  $y > 0$ )

Từ giả thiết ta có hệ phương trình

$$\begin{cases} 3x + 2y = 2300 \quad (1) \\ 2x + 3y = 2200 \quad (2) \end{cases}$$

(I)

$$(I) \iff \begin{cases} 6x + 4y = 4600 \\ 6x + 9y = 6600 \end{cases} \iff \begin{cases} 6x + 4y = 4600 \\ 5y = 2000 \end{cases} \\ \iff \begin{cases} y = 400 \\ x = 500 \end{cases}$$

**Nhận xét:** Nhân cả hai về của phương trình (1) với 2 tương đương với giả thiết rằng số tiền mua 6 lọ mực đỏ và 4 lọ mực xanh là 4600 đồng. Nhân hai về của phương trình (2) với 3 tương đương với giả thiết rằng số tiền mua 6 lọ mực đỏ và 9 lọ mực xanh là 6600 đồng.

Vi vậy có thể giải bài toán bằng cách dùng giả thiết tạm.

• Cách giải ở tiểu học

Số tiền mua 6 lọ mực đỏ là 4 lọ mực xanh là:

$$2300 \times 2 = 4600 \text{ đồng}$$

Số tiền mua 6 lọ mực đỏ và 9 lọ mực xanh là:

$$2200 \times 3 = 6600 \text{ đồng}$$

Số tiền mua 9 - 4 = 5 lọ mực xanh là:

$$6000 - 4600 = 2000 \text{ đồng}$$

Giá tiền một lọ mực xanh là:

$$2000 : 5 = 400 \text{ đồng}$$

Giá tiền mua 3 lọ mực đỏ là:

$$2300 - 2 \times 400 = 1500 \text{ đồng}$$

Giá tiền một lọ mực đỏ là:

$$1500 : 3 = 500 \text{ đồng}$$

**Ví dụ 2:** Có 18 ô tô gồm ba loại: loại 4 bánh chở 5 tấn, loại 6 bánh chở 6 tấn, loại 8 bánh chở 6 tấn. Các xe đó có tất cả 106 bánh và chở được 101 tấn. Hỏi mỗi loại có bao nhiêu xe?

• Giải bài toán bằng cách lập hệ phương trình

Gọi  $x$  là số xe 4 bánh,  $y$  là số xe 6 bánh,  $z$  là số xe 8 bánh.

Điều kiện:  $x, y, z$  là các số tự nhiên khác không ( $x, y, z < 18$ ). Theo giả thiết ta có hệ phương trình

$$\begin{cases} x + y + z = 18 & (1) \\ 4x + 6y + 8z = 106 & (2) \\ 5x + 6y + 6z = 101 & (3) \end{cases}$$

$$\begin{array}{l} (1) \Leftrightarrow \begin{cases} 5x + 6y + 6z = 101 \\ 4x + 6y + 8z = 106 \\ 6x + 6y + 6z = 108 \end{cases} \Leftrightarrow \begin{cases} 5x + 6y + 6z = 101 \\ 4x + 6y + 8z = 106 \\ x = 7 \end{cases} \\ \Leftrightarrow \begin{cases} x = 7 \\ y + z = 11 \\ 6y + 8z = 78 \end{cases} \Leftrightarrow \begin{cases} x = 7 \\ y + z = 11 \\ 2z = 12 \end{cases} \Leftrightarrow \begin{cases} x = 7 \\ y = 5 \\ z = 6 \end{cases} \end{array}$$

Nhận xét:

Nhân phương trình (1) với 6 rồi trừ từng vế với phương trình (3) để nhận được kết quả  $x = 7$ . Điều đó có nghĩa, ta đã giả thiết mỗi xe đều chở 6 tấn và do đó số tấn hàng chở thêm được là 7 tấn. Như vậy có 7 xe loại 4 bánh chở 5 tấn.

Nhân hai vế của phương trình  $y + z = 11$  với 6 tương đương với giả thiết là 11 xe còn lại mỗi xe đều có 6 bánh. Khi đó số bánh xe thừa ra là 12 bánh. Từ đó suy ra số xe 8 bánh là 6.

Vì vậy có thể giải bài toán bằng cách giả thiết tạm ở tiêu học.

##### • Cách giải ở tiêu học

Nếu 18 xe, mỗi xe đều chở 6 tấn thì số tấn hàng chở được là  $18 \times 6 = 108$  tấn. Số tấn hàng dư ra là  $108 - 101 = 7$  tấn. Dư ra 7 tấn là do mỗi xe loại 4 bánh chở thêm 1 tấn. Do đó số xe loại 4 bánh là 7 xe.

Số xe loại 6 bánh và 8 bánh là  $18 - 7 = 11$  xe.

Số bánh của hai loại xe này là  $106 - 7.4 = 78$  bánh.

Lại giả thiết tạm: Nếu 11 xe mỗi xe đều có 6 bánh thì số bánh xe là  $11 \times 6 = 66$  bánh.

Như vậy số bánh xe hụt đi  $78 - 66 = 12$  bánh.

Số bánh hụt đi đó do mỗi xe 8 bánh đã lấy đi 2 bánh.

Vậy số xe 8 bánh là  $12 : 2 = 6$  xe.

Số xe loại 6 bánh là  $11 - 6 = 5$  xe.

#### • Cách giải khác

Nếu hệ phương trình (I) được biến đổi như sau

$$(I) \Leftrightarrow \begin{cases} x + y + z = 18 \\ 2x - 2z = 2 \end{cases} \Leftrightarrow \begin{cases} x + y + z = 18 \\ x - z = 1 \end{cases} \Leftrightarrow \begin{cases} x = 7 \\ z = 6 \\ x = 7 \\ x = 7 \end{cases} \Leftrightarrow \begin{cases} x = 7 \\ z = 6 \\ y = 5 \end{cases}$$

Khi đó ta có cách giải ở tiểu học sau đây:

Giả sử mỗi xe đều chở 6 tấn thì số tấn hàng dư ra là  $18.6 - 101 = 7$  tấn.

Dư 7 tấn là do mỗi xe loại 4 bánh chở thêm 1 tấn, do đó có 7 xe loại 4 bánh.

Giả sử mỗi xe đều có 6 bánh thì số bánh xe chênh lên là  $18.6 - 106 = 2$  bánh.

Do đó số xe loại 4 bánh nhiều hơn số xe loại 8 bánh là 1 xe. Vậy số xe loại 8 bánh là  $7 - 1 = 6$  xe.

Số xe loại 6 bánh là  $18 - (7 + 6) = 5$  xe.

Ví dụ 3: Một trăm con trâu, một trăm bò cỏ. Trâu đúng ăn 5, trâu nằm ăn 3, lụkhu trâu già 3 con 1 bò. Hỏi có mấy trâu đúng, mấy trâu nằm, mấy trâu già?

• Giải bài toán bằng cách lập hệ phương trình

Đặt  $x$ ,  $y$ ,  $z$  lần lượt là số trâu đúng, số trâu nằm, số trâu già. Điều kiện  $x, y, z$  là các số nguyên dương ( $x, y, z < 100$ ). Theo giả thiết ta có hệ phương trình

$$(I) \begin{cases} x + y + z = 100 \\ 5x + 3z + \frac{1}{3}z = 400 \end{cases} \Leftrightarrow \begin{cases} x + y + z = 100 \\ 15x + 9y + z = 300 \end{cases} \Leftrightarrow \begin{cases} x + y = 100 - z \\ 15x + 9y = 300 - z \end{cases}$$

Gán cho  $z$  một giá trị tùy ý  $t$  ta có nghiệm của hệ (I) là

$$\begin{cases} x = -100 + \frac{4}{3}t \\ y = 200 - \frac{7}{3}t \\ z = t \end{cases}$$

Ta cần chọn  $t$  thích hợp để  $x, y, z$  nghiệm đúng bài toán. Vì  $x$  và  $y$  là các số nguyên dương nên  $t = 3k$  với  $k \in \mathbb{N}$  (tập các số tự nhiên khác không) và  $25 < k < \frac{200}{7} < 29$

Thử chọn

$$k = 26 \text{ thì } x = 4, y = 18, z = 78$$

$$k = 27 \text{ thì } x = 8, y = 11, z = 81$$

$$k = 28 \text{ thì } x = 12, y = 4, z = 84$$

Cả ba trường hợp đó đều thỏa mãn. Vậy bài toán có ba đáp án

1) Trâu đúng 4, trâu năm 18, trâu già 78

2) Trâu đúng 8, trâu năm 11, trâu già 81

3) Trâu đúng 12, trâu năm 4, trâu già 84

#### • Cách giải ở tiểu học

Nếu số bò có trâu già ăn là  $k$  bò thì số trâu già là  $3k$  còn số trâu đúng và trâu năm là  $100 - 3k$ .

Nếu mỗi con trâu đúng và năm đều ăn 3 bò thì  $3(100 - 3k)$  nhỏ hơn  $100 - k$ . Suy ra  $k > 25$ .

Nếu mỗi con trâu đúng và năm đều ăn 5 bò thì  $5(100 - 3k)$  lớn hơn  $100 - k$ . Suy ra  $k < 29$ .

Vậy số trâu già chỉ có thể là 78, 81 hoặc 84.

Nếu số trâu già là 78 thì số trâu đúng và trâu năm là  $100 - 78 = 22$  và ăn  $100 - (78 : 3) = 74$  bò cỏ. Nếu mỗi trâu đúng và trâu năm đều ăn 5 bò cỏ, nghĩa là mỗi trâu năm ăn thêm hai bò cỏ thì số cỏ phải thêm là  $5 \times 22 - 74 = 36$  bò. Do đó số trâu năm là  $36 : 2 = 18$ . Số trâu đúng là  $22 - 18 = 4$ .

Lập luận tương tự cho hai trường hợp còn lại ta nhận được ba đáp án như cách giải bằng hệ phương trình.

Ví dụ 4: Khi cộng một số thập phân với một số tự nhiên, do số suất một học sinh đã chép nhầm dấu phẩy ở số thập phân lùi sang bên phải một hàng và chép nhầm dấu cộng thành dấu trừ nên được kết quả là 219,3.

Tim hai số đó biết kết quả đúng là 38,43.

#### • Giải bài toán bằng cách lập hệ phương trình

Gọi số thập phân là  $x$ , số tự nhiên là  $y$ , ta có

$$\begin{cases} x + y = 38,43 \\ 10x - y = 219,3 \end{cases} \quad (I)$$

$$(I) \Leftrightarrow \begin{cases} x + y = 38,43 \\ 11x = 257,73 \end{cases} \Leftrightarrow \begin{cases} x = 23,43 \\ y = 15 \end{cases}$$

Vậy số thập phân là 23,43.

Số tự nhiên là 15.

**Nhận xét:** Qua cách giải bài toán bằng cách lập hệ phương trình ta thấy tổng của hai số 219,3 và 38,43 là 11 lần số thập phân. Lí giải được điều đó bằng cách ô tiêu học thi ta sẽ nhận được một cách giải ô tiêu học.

##### • Cách giải ô tiêu học

![](c959fda5679ea6470e0810c8c29eb823_img.jpg)

Diagram illustrating the relationship between the numbers 219.3, 38.43, and 10 times 219.3 (257.73). The diagram shows a horizontal line segment representing 219.3. A vertical segment labeled 38.43 is shown above the line, with its right end aligned with the right end of the 219.3 segment. A dashed line segment labeled 10 times 219.3 (257.73) is shown below the line, with its right end aligned with the right end of the 38.43 segment. The segment 257.73 is further divided into two parts: 10 times 219.3 (257.73) and 38.43. The segment 10 times 219.3 is marked with 10 segments of 219.3, and the segment 38.43 is marked with 15 segments of 38.43.

Biểu diễn số thập phân là đoạn thẳng AB, số tự nhiên là đoạn thẳng CD. Theo sơ đồ ta có

$$11 \text{ lần số thập phân là } 38,43 + 219,3 = 257,73$$

$$\text{Số thập phân là } 257,73 : 11 = 23,43$$

$$\text{Số tự nhiên là } 38,43 - 23,43 = 15$$

Ví dụ 5: Hai bể nước chứa tất cả  $5 \text{m}^3$  nước. Người ta mở vòi lấy nước ra mỗi phút 25 lit ở bể thứ nhất, 35 lit ở bể thứ hai. Sau nửa giờ thì đóng vòi lại, khi đó lượng nước trong hai bể còn lại bằng nhau. Hỏi lúc đầu mỗi bể chứa bao nhiêu lit nước?

#### • Giải bài toán bằng cách lập hệ phương trình

Gọi số lit nước ở bể thứ hai là  $x$ , số lit nước ở bể thứ nhất là  $y$ . Điều kiện  $x, y$  là các số dương  $x, y < 5$ . Từ giả thiết ta có

$$\begin{cases} x + y = 5000 \\ x - 30.35 = y - 30.25 \end{cases} \quad \text{hay} \quad \begin{cases} x + y = 5000 \\ x - y = 300 \end{cases} \quad (I)$$

$$(I) \Leftrightarrow \begin{cases} x + y = 5000 \\ x = 2650 \end{cases} \Leftrightarrow \begin{cases} x = 2650 \\ y = 2350 \end{cases}$$

Số nước lúc đầu ở mỗi bể là 2350 lít, 2650 lít.

**Nhận xét:** Qua các giải bài toán bằng cách lập hệ phương trình ta thấy tổng số nước ở hai bể là 5000 lít, còn hiệu là 300 lít. Đó là bài toán tìm hai số biết tổng và hiệu của hai số đó.

#### • Cách giải ở tiểu học

Ta thấy số nước ở bể thứ hai nhiều hơn số nước ở bể thứ nhất là

$$30 \times 35 - 30 \times 25 = 300 \text{ lít}$$

Biểu diễn số nước ở hai bể bằng đoạn thẳng

![](ebce469575e197e659de896b83c7a9cc_img.jpg)

Diagram showing two horizontal segments representing the water volume in the two tanks. The left segment is labeled 5000. The right segment is labeled 300. The right segment is labeled "Số nước bể thứ nhất" (Water volume of tank 1) and the left segment is labeled "Số nước bể thứ hai" (Water volume of tank 2).

Ta có hai lần số nước của bể thứ nhất là

$$5000 - 300 = 4700 \text{ lít}$$

Số nước ở bể thứ nhất là

$$4700 : 2 = 2350 \text{ lít}$$

Số nước ở bể thứ hai là

$$5000 - 2350 = 2650 \text{ lít}$$

**Ví dụ 6:** Tổng hai số là 10,47. Nếu số hạng thứ nhất gấp lên 5 lần, số hạng thứ hai gấp lên 3 lần thì tổng sẽ là 44,59. Tìm hai số đó.

##### • Giải bài toán bằng cách lập hệ phương trình

Gọi số thứ nhất là  $x$ , số thứ hai là  $y$ , ta có

$$\begin{cases} x + y = 10,47 \\ 5x + 3y = 44,59 \end{cases} \Leftrightarrow \begin{cases} x + y = 10,47 \\ 2x = 13,18 \end{cases} \Leftrightarrow \begin{cases} x = 6,59 \\ y = 3,88 \end{cases}$$

Vậy hai số phải tìm là 6,59 và 3,88

**Nhận xét:** Nhân hai về của phương trình  $x + y = 10,47$  với 3 tương đương với giả thiết là mỗi số hạng đều gấp ba lần. Tổng mới là  $3 \times 10,47 = 31,41$

Từ đó có cách giải bài toán này ở tiểu học bằng cách giả thiết tạm.

• Cách giả ở tiểu học

Nếu mỗi số hạng đều gấp lên 3 lần thì tổng sẽ là

$$3 \times 10,47 = 31,41$$

Hai lần số hạng thứ nhất là

$$44,59 - 31,41 = 13,18$$

Số thứ nhất là

$$13,18 : 2 = 6,59$$

Số hạng thứ hai là

$$10,47 - 6,59 = 3,88$$

Ví dụ 7: Tìm một số biết rằng nếu lấy số đó cộng với 6 rồi chia cho 5 sau đó lấy thương tìm được trừ đi 2, được bao nhiêu nhân với 8 thì kết quả là 32.

• Giải bài toán bằng cách lập phương trình

Gọi số phải tìm là  $x$ . Ta có

$$[(x + 6) : 5 - 2] \cdot 8 = 32 \Leftrightarrow \frac{x + 6}{5} - 2 = 4 \Leftrightarrow \frac{x + 6}{5} = 6 \Leftrightarrow x + 6 = 30 \Leftrightarrow x = 24$$

Vậy số phải tìm là 24

**Nhận xét:** Qua cách giải bài toán bằng cách lập phương trình ta thấy có thể tính  $x$  bằng cách tính ngược từ dưới lên.

• Cách giải ở tiểu học

Số phải tìm cộng với 6 rồi chia cho 5, lấy thương tìm được trừ đi 2 là  $32 : 8 = 4$ .

$$\text{Số phải tìm cộng với } 6 \text{ rồi chia cho } 5 \text{ là } 4 + 2 = 6$$

$$\text{Số phải tìm cộng với } 6 \text{ là } 5,6 = 30$$

$$\text{Số phải tìm là } 30 - 6 = 24$$