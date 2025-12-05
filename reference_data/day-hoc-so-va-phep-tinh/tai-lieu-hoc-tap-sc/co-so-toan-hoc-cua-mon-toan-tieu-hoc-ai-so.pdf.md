

TRÁN DIỆN HIẾN (Chủ biên)  
NGUYỄN THỦY CHUNG

# CƠ SỞ TOÁN HỌC CỦA MÔN TOÁN TIỂU HỌC

![Geometric diagram showing a semicircle with diameter AB. A vertical line segment NM is drawn from the arc to the diameter, with a right angle symbol at M. A small square is placed at M, indicating a right angle.](30a26f2d17ca95672702bf50fb4f0242_img.jpg)

Geometric diagram showing a semicircle with diameter AB. A vertical line segment NM is drawn from the arc to the diameter, with a right angle symbol at M. A small square is placed at M, indicating a right angle.

![Two overlapping triangles: an outer red triangle and an inner white triangle, illustrating a geometric concept.](64662465bba247703fdec49c8f3309f9_img.jpg)

Two overlapping triangles: an outer red triangle and an inner white triangle, illustrating a geometric concept.

![Logo of SP (Sư Phạm) University.](5fb340ad68b0c71df0b56698b137e35b_img.jpg)

Logo of SP (Sư Phạm) University.

NHÀ XUẤT BẢN ĐẠI HỌC SƯ PHẠM

## CHƯƠNG V

## Cơ sở toán học của các phương pháp giải toán ở Tiểu học

### 1. Phương trình bậc nhất và các phương pháp giải toán: tính ngược từ cuối, phương pháp ứng dụng đồ thị và phương pháp đại số

#### 1. Biểu thức toán học

Biểu thức toán học là một cách kí hiệu chỉ rõ các phép toán và thứ tự thực hiện các phép toán đó trên các số hoặc các chữ nhận giá trị từ một tập hợp số  $T$  cho trước. Các số hoặc các chữ nhận giá trị xác định gọi là hằng số, các chữ nhận giá trị biến đổi (thuộc tập  $T$ ) gọi là biến số.

Tập các giá trị của biến số thuộc tập  $T$ , khi thay vào làm cho biểu thức toán học có nghĩa ta gọi là miền xác định của biểu thức đó.

Căn cứ vào các phép toán xuất hiện trong biểu thức, người ta phân chia biểu thức toán học thành: biểu thức nguyên (đa thức), phân thức, biểu thức đại số, biểu thức vô tỉ, biểu thức mũ, biểu thức lôgarit, biểu thức lượng giác.

Chẳng hạn:

$$F(x) = 4x^5 + 2x^4 - 5x^3 + x^2 - 12x + 1 \text{ là đa thức bậc } 5;$$

$$G(x) = \frac{x^3 - x^2 + 2}{x^2 - 1} \text{ là phân thức đại số};$$

$$H(x) = 2x^{11} - 3x^{12} + 2 \text{ là biểu thức mũ};$$

#### 2. Phương trình

Cho  $f(x)$  và  $g(x)$  là hai biểu thức toán học với miền xác định là  $D_f$  và  $D_g$  tương ứng. Ta gọi quan hệ:

$$f(x) = g(x) \quad (1)$$

là một phương trình với miền xác định là  $D = D_f \cap D_g$ .

Trong đó  $f(x)$  gọi là **vế trái** và  $g(x)$  gọi là **vế phải** của phương trình (1).

Mỗi giá trị  $a \in D$  khi thay vào ta được giá trị của hai vế của phương trình bằng nhau:  $f(a) = g(a)$  gọi là  **nghiệm** của phương trình (1).

Tập tất cả các nghiệm của phương trình (1) ta kí hiệu là  $S$ .

Công việc đi tìm tập  $S$  gọi là giải phương trình.

Nếu tập  $S$  chỉ có một phần tử thì ta nói phương trình (1) có duy nhất nghiệm; nếu tập  $S$  có k phần tử thì ta nói phương trình (1) có k nghiệm phân biệt; nếu  $S$  là tập vô hạn thì ta nói phương trình (1) có vô số nghiệm; nếu  $S$  là tập rỗng thì ta nói phương trình (1) vô nghiệm.

#### 3. Phương trình tương đương

Cho  $f_1(x) = g_1(x)$  (1) và  $f_2(x) = g_2(x)$  (2) là hai phương trình với tập hợp nghiệm là  $S_1$  và  $S_2$  tương ứng.

Ta nói rằng phương trình (1) tương đương với phương trình (2), kí hiệu là (1)  $\Leftrightarrow$  (2), nếu  $S_1 = S_2$ .

Hay nói cách khác: Hai phương trình gọi là tương đương nếu chúng có cùng tập nghiệm.

Khi giải phương trình, người ta bắt đầu từ những phương trình đơn giản. Sau đó khi gặp những phương trình mới phức tạp hơn, người ta sẽ biến đổi để đưa về những phương trình đã biết cách giải trước đó.

Một câu hỏi đặt ra là: Liệu trong quá trình biến đổi như thế có làm thay đổi tập nghiệm (làm mất nghiệm hoặc sinh thêm nghiệm mới) của phương trình đã cho không? Hay nói cách khác: Những phép biến đổi như thế nào sẽ không làm thay đổi tập hợp nghiệm (ta gọi là phép biến đổi tương đương các phương trình)?

Các định lý dưới đây giúp ta trả lời câu hỏi đó.

**Định lý 5.1.** Cho  $f(x) = g(x)$  (1) là một phương trình với miền xác định  $D$  và  $h(x)$  là một biểu thức xác định trên miền  $D$ . Khi đó, phương trình (1) tương đương với phương trình:

$$f(x) + h(x) = g(x) + h(x) \quad (1_h).$$

Hay nói cách khác: Nếu ta cộng hoặc trừ cả hai về của một phương trình với cùng biểu thức xác định trên miền xác định của phương trình đã cho thì ta nhận được một phương trình mới tương đương với phương trình đã cho.

**Ví dụ 5.1.** Phương trình:  $x^2 - 5x + 4 = 0$  tương đương với phương trình:  $2x^2 - 4x + 1 = x^2 - x - 3$ .

**Định lý 5.2.** Cho  $f(x) = g(x)$  (1) là một phương trình với miền xác định  $D$  và  $k(x)$  là một biểu thức xác định trên miền  $D$ . Khi đó:

Phương trình (1) tương đương với phương trình:

$$f(x)k(x) = g(x)k(x) \quad (1_k).$$

Hay nói cách khác: Nếu ta nhân hoặc chia cả hai vế của một phương trình với cùng biểu thức xác định và khác không trên miền xác định của phương trình đã cho thì ta nhận được một phương trình mới tương đương với phương trình đã cho.

Ví dụ 5.2. Phương trình:  $x^2 - 5x + 4 = 0$  tương đương với phương trình:  $x^4 - 5x^3 + 5x^2 - 5x + 4 = 0$ .

Thật vậy, vì  $x^4 - 5x^3 + 5x^2 - 5x + 4 = (x^2 - 5x + 4)(x^2 + 1)$ .

#### 4. Phương trình bậc nhất

Phương trình bậc nhất là một phương trình sau một số phép biến đổi tương đương ta đưa được về dạng:

$$ax + b = 0, \text{ trong đó } a \neq 0 \quad (1)$$

Phương trình bậc nhất (1) có duy nhất nghiệm là:

$$x = -\frac{b}{a}$$

Chẳng hạn, phương trình  $3x - 2 = x + 4$  có nghiệm là  $x = 3$ .

Từ cách giải phương trình bậc nhất ta hình thành một số phương pháp giải toán ở Tiểu học:

#### 4.1. Phương trình bậc nhất và phương pháp tính ngược từ cuối

Ví dụ 5.3. Tìm một số, biết rằng khi bớt số đó đi 3, sau đó chia cho 2 rồi cộng với 1,5, cuối cùng nhân với 4 được kết quả bằng 40.

Dùng kiến thức về giải phương trình bậc nhất, ta giải bài toán như sau:

Gọi số cần tìm là  $x$ ;

Khi bớt số đó đi 3 ta có:  $x - 3$ ;

Khi chia cho 2 ta được:  $(x - 3) : 2$ ;

Khi cộng với 1,5 ta được:  $(x - 3) : 2 + 1,5$ ;

Khi nhân với 4 ta được:  $[(x - 3) : 2 + 1,5] \times 4$ ;

Theo đề bài ta có phương trình:

$$[(x - 3) : 2 + 1,5] \times 4 = 40.$$

$$\text{Giải ra ta được } x = 20.$$

Ở Tiểu học, chưa có khái niệm về phương trình và giải phương trình, vận dụng các quy tắc về tìm thành phần chưa biết của phép tính, ta giải bài toán như sau:

Số trước khi nhân với 4 là:

$40 : 4 = 10$

Số trước khi cộng với 1,5 là:

$10 - 1,5 = 8,5$

Số trước khi chia cho 2 là:

$8,5 \times 2 = 17$

Số cần tìm là:

$17 + 3 = 20$

Cách giải trên đây ta gọi là *phương pháp tinh ngược từ cuối*.

**Chú ý:** 1) Có số toán học của phương pháp tinh ngược từ cuối là các quy tắc tìm thành phần chưa biết của phép tính.

2) Các bài toán về tinh ngược từ cuối có thể ra cho học sinh từ lớp 2. Ở mỗi lớp cần phù hợp với vòng số và kĩ năng tinh toán của lớp đó.

3) Phương pháp tinh ngược từ cuối không chỉ dùng để giải toán số học mà còn dùng để giải các bài toán có lời văn.

**Ví dụ 5.4.** Di Út đi chợ bán trứng. Lần thứ nhất bán một nửa số trứng thêm nửa quả, lần thứ hai bán một nửa số trứng còn lại thêm nửa quả thì còn lại hai chiếc trứng. Hỏi di Út đã mang bao nhiêu trứng ra chợ bán?

**Giải:** Số trứng còn lại sau lần bán thứ nhất là:

$$2 \text{ chiếc trứng} = 20 \text{ quả trứng}$$

$\frac{1}{2}$  quả 20 quả

![Diagram showing a line segment representing 20 quan (units). A segment of length 1/2 quan is marked, and the remaining length is 20 - 1/2 = 19/2 quan.](52c85d04214920e603ef11d9111ca915_img.jpg)

Diagram showing a line segment representing 20 quan (units). A segment of length 1/2 quan is marked, and the remaining length is 20 - 1/2 = 19/2 quan.

? quan

$$\left(20 + \frac{1}{2}\right) \times 2 = 41 \text{ (quả)}$$

Số trứng lúc đầu di Út mang ra chợ bán là:

$\frac{1}{2}$  quả 41 quả

![Diagram showing a line segment representing 41 quan (units). A segment of length 1/2 quan is marked, and the remaining length is 41 - 1/2 = 40/2 quan.](77a114bbffeee8b6fb9bceabfad03024_img.jpg)

Diagram showing a line segment representing 41 quan (units). A segment of length 1/2 quan is marked, and the remaining length is 41 - 1/2 = 40/2 quan.

? quan

$$\left(41 + \frac{1}{2}\right) \times 2 = 83 \text{ (quả)}$$

Đáp số: 83 quả trứng.

#### 4.2. Phương trình bậc nhất và phương pháp úng dụng đồ thị

Ví dụ 5.3 có thể giải cho học sinh tiêu học bằng cách khác như sau:

Theo đề bài ta có số đô:

![](46f43cb4ffd47565e7c0ca306d461435_img.jpg)

Diagram illustrating the steps of the graphical method for solving a system of equations. The steps are:  $-3$ ,  $:2$ ,  $+1,5$ ,  $\times 4$ , resulting in  $40$ .

Dựa vào số đô ta có số cần tìm là:

$$(40 : 4 - 1,5) \times 2 + 3 = 20.$$

Cách giải như trên ta gọi là phương pháp úng dụng đồ thị. Hình vẽ trên ta gọi là đồ thị của bài toán.

#### 4.3. Phương trình bậc nhất và phương pháp đại số

Ví dụ 5.3 còn có thể giải bằng cách sau:

Gọi số cần tìm là  $x$ :

Theo đề bài ta có:

$$(x-3) : 2 + 1,5 = 40$$

$$(x-3) : 2 + 1,5 = 40 : 4 \text{ (tìm thừa số trong phép nhân)}$$

$$(x-3) : 2 + 1,5 = 10$$

$$(x-3) : 2 = 10 - 1,5 \text{ (tìm số hạng trong phép cộng)}$$

$$(x-3) : 2 = 8,5$$

$$x-3 = 8,5 \times 2 \text{ (tìm số bị chia)}$$

$$(x-3) = 17$$

$$x = 17 + 3 \text{ (tìm số bị trừ)}$$

$$x = 20.$$

Cách giải như trên ta gọi là Phương pháp đại số hay còn gọi là phương pháp dùng chữ thay số.

Chú ý: Ở Tiểu học, nói chung người ta hạn chế dùng phương pháp đại số.

#### II. Hệ phương trình bậc nhất hai ẩn

##### 1. Định nghĩa

Hệ phương trình bậc nhất hai ẩn là một hệ phương trình sau một số phép biến đổi tương đương ta đưa được về dạng:

$$\begin{cases} ax + by = c \\ a'x + b'y = c' \end{cases}$$

trong đó các hệ số  $a$ ,  $a'$ ,  $b$ ,  $b'$  không đồng thời bằng 0.

##### 2. Phương pháp giải hệ phương trình bậc nhất

a) Phương pháp khử:

Ví dụ 5.5. Giải hệ phương trình:

$$\begin{cases} 3x - 5y = 4 & (1) \\ 4x + 3y = 15 & (2) \end{cases}$$

Giải: Nhân cả hai vế của phương trình (1) với 4 và phương trình (2) với 3 ta được:

$$\begin{cases} 12x - 20y = 16 & (3) \\ 12x + 9y = 45 & (4) \end{cases}$$

Trừ vế với vế của phương trình (4) cho phương trình (3) ta được:

$$29y = 29$$

$$y = 1.$$

Thay vào phương trình (1) ta được  $x = 3$ .

b) Phương pháp thế

Từ phương trình (1) ta tính được:

$$x = \frac{5y+4}{3} \quad (3).$$

Thay (3) vào phương trình (2) ta được:

$$4 \cdot \frac{5y+4}{3} + 3y = 15$$

$$20y + 16 + 9y = 45$$

$$y = 1.$$

Thay vào (3) ta được  $x = 3$ .

c) Phương pháp định thức

Ta có:

$$D = \begin{vmatrix} 3 & -5 \\ 4 & 3 \end{vmatrix} = 3 \cdot 3 - 4 \cdot (-5) = 29;$$

$$D_x = \begin{vmatrix} 4 & -5 \\ 15 & 3 \end{vmatrix} = 4 \cdot 3 - 15 \cdot (-5) = 87;$$

$$D_y = \begin{vmatrix} 3 & 4 \\ 4 & 15 \end{vmatrix} = 3 \cdot 15 - 4 \cdot 4 = 29.$$

Từ đây ta được:

$$x = \frac{D_x}{D} = 3; y = \frac{D_y}{D} = 1.$$

Từ cách giải hệ phương trình bậc nhất ta hình thành một số phương pháp giải toán ở Tiểu học:

3. Hệ phương trình bậc nhất dạng:  $\begin{cases} x + y = t \\ x - y = h \end{cases}$  và phương pháp

giải toán về tìm hai số biết tổng và hiệu của chúng

Ví dụ 5.6. Tổng của hai số bằng 60, hiệu của chúng bằng 10. Tìm hai số đó.

Trước hết ta dùng phương pháp toán sơ cấp giải bài toán trên:

Gọi số thứ nhất là  $x$ , số thứ hai là  $y$ . Theo đề bài ta có hệ phương trình:

$$\begin{cases} x + y = 60 \quad (1) \\ x - y = 10 \quad (2) \end{cases}$$

Cách 1:

Cộng về vế của (1) và (2) ta được:

$$2x = 70$$

$$x = 70 : 2$$

$$x = 35.$$

$$\text{Thay vào (1) ta được: } y = 60 - 35$$

$$y = 25.$$

Vậy hai số cần tìm là 35 và 25.

Cách 2:

Trừ về vế của (1) và (2) ta được:

$$2y = 50$$

$$y = 50 : 2$$

$$y = 25.$$

Thay vào (1) ta được:  $x = 60 - 25$

$$x = 35.$$

Vậy hai số cần tìm là 35 và 25.

Từ hai cách giải trên, ta diễn giải thành phương pháp giải cho học sinh tiểu học như sau:

###### Cách 1:

Theo đề bài ta có sơ đồ:

![](91be14371a97fb5ce9eeb29ae18d07c3_img.jpg)

Số thứ nhất: ?

Số thứ hai: 60

Số thứ hai: 10

Giả sử số thứ hai tăng thêm 10 đơn vị, như vậy ta được hai số bằng nhau và bằng số lớn.

Hai lần số lớn là:  $60 + 10 = 70$

Số lớn là:  $70 : 2 = 35$

Số bé là:  $60 - 35 = 25$

Trả lời: Hai số cần tìm là: 35 và 25.

Từ đây ta rút ra công thức:

$$\text{Số lớn} = (\text{Tổng} + \text{Hiệu}) : 2$$

###### Cách 2:

Theo đề bài ta có sơ đồ:

![](ca5f2304ffe22946414ffab54cd3fd93_img.jpg)

Số thứ nhất: ?

Số thứ hai: 60

Số thứ hai: 10

Giả sử số thứ nhất giảm 10 đơn vị, như vậy ta được hai số bằng nhau và bằng số bé.

Hai lần số bé là:  $60 - 10 = 50$

Số bé là:  $50 : 2 = 25$

Số lớn là:  $60 - 25 = 35$

Trả lời: Hai số cần tìm là: 35 và 25.

Từ đây ta rút ra công thức:

$$\text{Số bé} = (\text{Tổng} - \text{Hiệu}) : 2$$

Ở Tiểu học, hai cách giải trên đây ta gọi là phương pháp thế để giải bài toán về tìm hai số khi biết tổng và hiệu của chúng.

Ví dụ 5.6a. Chu Tư thu hoạch trên hai thửa ruộng được 18 tạ thóc, trong đó thửa thứ nhất thu hoạch được nhiều hơn thửa thứ hai 4 tạ. Hỏi chu Tư thu hoạch trên mỗi thửa ruộng được bao nhiêu tạ thóc?

Trước hết ta dùng phương pháp toán sơ cấp giải bài toán trên:

Gọi số thóc thu hoạch được trên thửa ruộng thứ nhất là  $x$  (tạ) và thửa ruộng thứ hai là  $y$  (tạ). Theo đề bài ta có hệ phương trình:

$$x + y = 18 \quad (1)$$

$$x - y = 4 \quad (2)$$

Cách 1:

Cộng về với về của (1) và (2) ta được:

$$2x = 22$$

$$x = 22 : 2$$

$$x = 11$$

Thay vào (1) ta được:

$$y = 18 - 11$$

$$y = 7$$

Trả lời: Chủ Tự thu hoạch trên thửa thứ nhất được 11 tạ thóc và trên thửa thứ hai được 7 tạ thóc.

Cách 2:

$$(1) + 2 = x + x$$

$$\frac{2}{2} = x$$

$$2y = 14$$

$$y = 14 : 2$$

$$y = 7$$

Thay vào (1) ta được:

$$x = 18 - 7$$

$$x = 11$$

Trả lời: Chủ Tự thu hoạch trên thửa thứ nhất được 11 tạ thóc và trên thửa thứ hai được 7 tạ thóc.

Từ hai cách giải trên, ta diễn giải thành phương pháp giải cho học sinh tiểu học như sau:

Cách 1:

Số thóc thu hoạch trên thửa ruộng thứ nhất là:

$$(18 + 4) : 2 = 11 \text{ (tạ)}$$

Số thóc thu hoạch trên thửa ruộng thứ hai là:

$$18 - 11 = 7 \text{ (tạ)}$$

Đáp số: Thửa thứ nhất: 11 tạ; Thửa thứ hai: 7 tạ

Cách 2:

Số thức thu hoạch trên thửa ruộng thứ hai là:  $(18 - 4) : 2 = 7$  (tạ)

Số thức thu hoạch trên thửa ruộng thứ nhất là:  $18 - 7 = 11$  (tạ)

Đáp số: Thửa thứ nhất: 11 tạ; Thửa thứ hai: 7 tạ.

Ở Tiểu học, hai cách giải trên đây ta gọi là phương pháp thế để giải bài toán về tìm hai số khi biết tổng và hiệu của chúng.

4. Hệ phương trình bậc nhất dạng:  $\begin{cases} x \pm y = s \\ ax - by = 0 \end{cases}$  và phương pháp

chia tỉ lệ

Ví dụ 5.7. Tổng của hai số bằng 84, trong đó số thứ nhất bằng  $\frac{2}{5}$  số thứ hai. Tìm hai số đó.

Trước hết ta dùng phương pháp toán sơ cấp giải bài toán trên:

Gọi số thứ nhất là  $x$ , số thứ hai là  $y$ . Theo đề bài ta có hệ phương trình:

$$\begin{cases} x + y = 84 \quad (1) \\ x = \frac{2}{5}y \quad (2) \end{cases}$$

Thay (2) vào (1) ta được:

$$2y + 5y = 84 \times 5$$

$$y = (84 : 7) \times 5$$

$$y = 60.$$

Thay vào (1) ta được:  $x = 84 - 60$

$$x = 24.$$

Vậy hai số cần tìm là 24 và 60.

Từ cách giải trên, ta diễn giải thành phương pháp giải cho học sinh tiểu học như sau:

Theo đề bài ta có sơ đồ:

![](3e983fa4b21ccaafb5595bcfbf4fbcac_img.jpg)

Số thứ nhất:  $\text{?}$

Số thứ hai:  $\text{?}$

Tổng số phần bằng nhau là:  $2 + 5 = 7$  (phần)

Giá trị của một phần là:  $84 : 7 = 12$

Số thứ hai là:  $12 \times 5 = 60$

Số thứ nhất là:  $12 \times 2 = 24$

Trả lời: Hai số cần tìm là: 24 và 60.

Ở Tiểu học, cách giải trên đây ta gọi là phương pháp chia tỉ lệ để giải bài toán về tìm hai số khi biết tổng và tỉ số của chúng.

Ví dụ 5.7a. Hai đội vận tải được giao vận chuyển 480 tấn hàng. Số hàng của đội Hai vận chuyển được bằng  $\frac{5}{3}$  số hàng của đội Một. Hỏi mỗi đội đã vận chuyển được bao nhiêu tấn hàng?

Trước hết ta dùng phương pháp toán sơ cấp giải bài toán trên:

Gọi số hàng của đội Một vận chuyển được là  $x$  (tấn) và đội Hai là  $y$  (tấn). Theo đề bài ta có hệ phương trình:

$$x + y = 480 \quad (1)$$

$$y = \frac{5}{3}x \quad (2)$$

Thay (2) vào (1) ta được:

$$3x + 5x = 480 \times 3$$

$$8x = 480 \times 3$$

$$x = (480 : 8) \times 3$$

$$x = 180.$$

Thay vào (1) ta được:

$$y = 480 - 180$$

$$y = 300.$$

Trả lời: Đội Một vận chuyển được 180 tấn hàng, đội Hai vận chuyển được 300 tấn hàng.

Từ cách giải trên, ta diễn giải thành phương pháp giải cho học sinh tiểu học như sau:

Theo đề bài ta có sơ đồ:

Đội Một: ? tấn

Đội Hai: ? tấn

?

Tổng số phần bằng nhau là:  $3 + 5 = 8$  (phân)

Giá trị của một phần bằng nhau là:  $480 : 8 = 60$  (tấn)

Số hàng của đội Một vận chuyển được là:  $60 \times 3 = 180$  (tấn)

Số hàng của đội Hai vận chuyển được là:  $480 - 180 = 300$  (tấn)

Đáp số: Đội Một: 180 tấn hàng; Đội Hai: 300 tấn hàng.

Ở Tiểu học, cách giải trên đây ta gọi là phương pháp chia tỉ lệ để giải bài toán về tìm hai số khi biết tổng và tỉ số của chúng.

Ví dụ 5.8. Tìm hai số, biết rằng số thứ nhất gấp 4 lần số thứ hai và hơn số thứ hai 36 đơn vị.

Trước hết ta dùng phương pháp toán sơ cấp giải bài toán trên:

Gọi số thứ nhất là  $x$ , số thứ hai là  $y$ . Theo đề bài ta có hệ phương trình:

$$\begin{cases} x - y = 36 (1) \\ x = 4y \quad (2) \end{cases}$$

Thay (2) vào (1) ta được:

$$4y - y = 36$$

$$3y = 36$$

$$y = 36 : 3$$

$$y = 12.$$

Thay vào (1) ta được:  $x = 12 + 36$

$$x = 48.$$

Vậy hai số cần tìm là 48 và 12.

Từ cách giải trên, ta diễn giải thành phương pháp giải cho học sinh tiểu học như sau:

Theo đề bài ta có số đó:

? ?

Số thứ nhất:

![](ab8627e3c2a6ebd1ae6e06d78a0d4c00_img.jpg)

Diagram showing a line segment representing the total number. The total is divided into two parts, labeled 36 and 36, indicating the ratio 36:36.

Số thứ hai:

![](1a4655ab13ebfd068a33364361d525ff_img.jpg)

Diagram showing a line segment representing the total number. The total is divided into two parts, labeled 36 and 36, indicating the ratio 36:36.

?

Hiệu số phần bằng nhau là:  $4 - 1 = 3$  (phần)

Số thứ hai là:  $36 : 3 = 12$

Số thứ nhất là:  $12 + 36 = 48$

Trả lời: Hai số cần tìm là: 48 và 12.

Ở Tiểu học, cách giải trên đây ta gọi là phương pháp chia tỉ lệ để giải bài toán về tìm hai số khi biết hiệu và tỉ số của chúng.

Ví dụ 5.8a. Khối lớp Năm và khối lớp Bốn của Trường Tiểu học Kim Liên tham gia Tết trồng cây. Số cây của khối lớp Bốn trồng được bằng  $\frac{3}{5}$  số cây của khối lớp Năm và ít hơn số cây của khối lớp Năm 218 cây. Hỏi mỗi khối lớp trồng được bao nhiêu cây?

Trước hết ta dùng phương pháp toán sơ cấp giải bài toán trên:

Gọi số cây khối lớp Bốn trồng được là  $x$  (cây) và số cây khối lớp Năm trồng được là  $y$  (cây). Theo đề bài ta có hệ phương trình:

$$\begin{cases} y - x = 218 \quad (1) \\ x = \frac{3}{5}y \quad (2) \end{cases}$$

Thay (2) vào (1) ta được:

$$5y - 3y = 218 \times 5$$

$$2y = 218 \times 5$$

$$y = (218 : 2) \times 5$$

$$y = 545.$$

Thay vào (1) ta được:

$$x = 545 - 218$$

$$x = 327.$$

Trả lời: Khối lớp Bốn trồng được 327 cây và khối lớp Năm trồng được 545 cây.

Từ cách giải trên, ta diễn giải thành phương pháp giải cho học sinh tiểu học như sau:

Theo đề bài ta có số đồ:

Khối lớp Bốn:  $\frac{3}{5}$  số cây 218 cây

Khối lớp Năm:  $\frac{5}{3}$  số cây

Hiệu số phần bằng nhau là:  $5 - 3 = 2$  (phần)

Giá trị của một phần bằng nhau là:  $218 : 2 = 109$  (cây)

Số cây của khối lớp Năm trồng được là:  $109 \times 5 = 545$  (cây)

Số cây của khối lớp Bốn trồng được là:  $545 - 218 = 327$  (cây)

Đáp số: Khối lớp Bốn: 327 cây; Khối lớp Năm: 545 cây.

Ở Tiểu học, cách giải trên đây ta gọi là phương pháp chia tỉ lệ để giải bài toán về tìm hai số khi biết hiệu và tỉ số của chúng.

5. Hệ phương trình bậc nhất dạng: 
$$\begin{cases} x + y = m \\ ax + by = n \end{cases}$$
 và phương pháp giải

thiết tạm

Ví dụ 5.9.

Vừa gà, vừa chó

Bó lại cho tròn

Có mười sáu con

Bốn mươi chẵn chẵn.

Hỏi có bao nhiêu con gà? Bao nhiêu con chó?

Trước hết ta dùng phương pháp toán sơ cấp giải bài toán trên:

Gọi số gà là  $x$  (con), số chó là  $y$  (con). Theo đề bài ta có hệ phương trình:

$$\begin{cases} x + y = 16 \quad (1) \\ 2x + 4y = 40 \quad (2) \end{cases}$$

Nhân cả hai về của (1) với 2 ta được:

$$\begin{cases} 2x + 2y = 32 \quad (1') \\ 2x + 4y = 40 \quad (2') \end{cases}$$

Trừ về với về của (2') cho (1') ta được:

$$2y = 8$$

$$y = 4$$

Thay vào (1) ta được:  $x = 16 - 4 = 12$ .

Trả lời: Có 12 con gà và 4 con chó.

Từ cách giải trên, ta diễn giải thành phương pháp giải cho học sinh tiểu học như sau:

Giá sử tất cả 16 con đều là gà.

Tổng số chẵn là:  $16 \times 2 = 32$  (chẵn)

Số chẵn hụt đi là:  $40 - 32 = 8$  (chẵn)

Mỗi con chó hơn một con gà số chẵn là:  $4 - 2 = 2$  (chẵn)

Vì mỗi con chó bớt đi 2 chẵn nên tất cả hụt đi 8 chẵn.

Số con chó là:  $8 : 2 = 4$  (con)

Số con gà là:  $16 - 4 = 12$  (con)

Đáp số: 12 con gà và 4 con chó.

Ở Tiểu học, cách giải trên đây ta gọi là phương pháp giả thiết tạm.

Tương tự, nếu giả sử tất cả đều là chó, ta sẽ được cách giải thứ hai.

**Chú ý:** Ngoài cách giải trên, bài toán này còn có cách giải “mẹo” như sau: Giả sử mỗi con chó co 2 chân, mỗi con gà co 1 chân.

Số chân đếm được là:  $40 : 2 = 20$  (chân)

Giả sử mỗi con chó co thêm 1 chân nữa. Số chân đếm được là 16 chân.

Số con chó là:  $20 - 16 = 4$  (con)

Số con gà là:  $16 - 4 = 12$  (con).

**Ví dụ 5.9a.** Một lớp học dùng 13 đoạn ông nước gồm hai loại dài 8m và dài 5m để lắp đặt một đoạn đường ở dài 77m. Hỏi lớp học phải dùng mỗi loại bao nhiêu ông để khi lắp đặt không phải cắt một ông nào?

Turroc hết ta dùng phương pháp toán sơ cấp giải bài toán trên:

Gọi số ông loại 8m là  $x$  (ông) và số ông loại 5m là  $y$  (ông). Theo đề bài ta có hệ phương trình:

$$(1) 000011 = x + 2y$$

$$(2) x + y = 13 \quad (1)$$

$$(8x + 5y = 77) \quad (2)$$

Nhân cả hai về của (1) với 8 ta được:

$$8x + 8y = 104 \quad (1')$$

$$8x + 5y = 77 \quad (2')$$

Trừ về số của (1') cho (2') ta được:

$$3y = 27$$

$$y = 9$$

Thay vào (1) ta tính được  $x = 4$ .

Trả lời: T lớp học dùng 4 ông loại 8m và 9 ông loại 5m.

Tur cách giải trên, ta diễn giải thành phương pháp giải cho học sinh tiểu học như sau:

Giả sử dùng tất cả 13 ông loại 8m. Nếu mỗi con gà co 2 chân thì số ông 8m là:

Chiều dài đường ở lắp được là:  $13 \times 8 = 104$  (m)

Chiều dài đường ở tăng thêm là:  $104 - 77 = 27$  (m)

Mỗi ông loại 8m dài hơn một ông loại 5m là:

$$8 - 5 = 3 \quad (m)$$

Số ông loại 5m là:

$$27 : 3 = 9 \text{ (ông)}$$

Số ông loại 8m là:

$$13 - 9 = 4 \text{ (ông)}$$

Đáp số: 4 ông loại 8m và 9 ông loại 5m.

6. Hệ phương trình bậc nhất dạng: 
$$\begin{cases} ax+by=c \\ a'x+b'y=c' \end{cases}$$
 và phương pháp khử

Ví dụ 5.10. Mẹ mua 5kg gạo tẻ và 3kg gạo nếp hết 114 000 đồng. Một lần khác, mẹ mua 7kg gạo tẻ và 4kg gạo nếp cùng loại hết 156 000 đồng. Tính giá tiền 1kg gạo mỗi loại.

Trước hết ta dùng phương pháp toán sơ cấp giải bài toán trên:

Gọi giá tiền 1kg gạo tẻ là x (đồng), giá tiền 1kg gạo nếp là y (đồng). Theo đề bài ta có hệ phương trình:

$$\begin{cases} 5x + 3y = 114000 \quad (1) \\ 7x + 4y = 156000 \quad (2) \end{cases}$$

Nhân cả hai về của (1) với 4, của (2) với 3 ta được:

$$\begin{cases} 20x + 12y = 456000 \quad (1') \\ 21x + 12y = 468000 \quad (2') \end{cases}$$

Trừ về với về của (2') cho (1') ta được:  $x = 12 000$ .

Thay vào (1) ta được:  $y = 18 000$ .

Trả lời: Giá tiền 1kg gạo tẻ là 12 000 đồng và kg gạo nếp là 18 000 đồng.

Từ cách giải trên, ta điền giải thành phương pháp giải cho học sinh tiều học như sau:

Giả sử số gạo mỗi loại lần 1 mua tăng gấp 4 lần, lần 2 mua tăng gấp 3 lần. Vậy ta có:

20kg gạo tẻ và 12kg gạo nếp giá 456 000 đồng.

21kg gạo tẻ và 12kg gạo nếp giá 468 000 đồng.

Số gạo tẻ lần 2 mua nhiều hơn lần 1 là:  $21 - 20 = 1 \text{ (kg)}$

Số tiền lần 2 mua nhiều hơn lần 1 là:  $468000 - 456000 = 12000 \text{ (đồng)}$

Số gạo nếp hai lần mua là như nhau, vậy 12 000 đồng là giá tiền của 1kg gạo tẻ.

Giá tiền 1kg gạo nếp là:  $(114000 - 12000 \times 5) : 3 = 18000 \text{ (đồng)}$

Đáp số: 12 000 đồng 1kg gạo tẻ; 18 000 đồng 1kg gạo nếp

Ở Tiều học, cách giải trên ta gọi là phương pháp khử.

7. Hệ phương trình bậc nhất dạng:  $\begin{cases} ax - y = c \\ y - bx = c' \end{cases}$  và giải toán về tìm hai số biết hai hiệu số

Ví dụ 5.11. Một tổ lớp được giao lập đặt một đoạn đường ởng nước. Trong kho có hai loại ống: dài 7m và dài 9m, số lượng bằng nhau. Chủ thợ cã tính rằng: nếu dùng loại ống 7m thì thiếu 11m, nếu dùng loại ống 9m thì thừa 17m. Hỏi trong kho có bao nhiêu ống mỗi loại và chiều dài đường ống cần lập đặt là bao nhiêu mét?

Trước hết ta dùng phương pháp toán sơ cấp giải bài toán trên:

Gọi số ống mỗi loại là  $x$  (ống), chiều dài đường ống cần lập đặt là  $y$  (m). Theo đề bài ta có hệ phương trình:

$$\begin{cases} 9x - y = 17(1) \\ y - 7x = 11(2) \end{cases}$$

Cộng về với về của (1) và (2) ta được:

$$2x = 28$$

$$x = 14.$$

Thay vào (2) ta được:  $y = 109$ .

Trả lời: Chiều dài đường ống cần lập đặt là 109m và trong kho có 14 ống mỗi loại.

Từ cách giải trên, ta diễn giải thành phương pháp giải cho học sinh tiểu học như sau:

Mỗi ống loại 9m dài hơn một ống loại 7m là:

$$9 - 7 = 2 \text{ (m)}$$

Chiều dài đường ống bằng loại 9m dài hơn chiều dài đường ống lập đặt bằng loại ống 7m là:

$$11 + 17 = 28 \text{ (m)}$$

Số ống mỗi loại là:

$$28 : 2 = 14 \text{ (ống)}$$

Chiều dài đường ống là:

$$7 \times 14 + 11 = 109 \text{ (m)}$$

Đáp số: 109m; 14 ống.

Ở Tiểu học, cách giải trên đây ta gọi là phương pháp giải toán về tìm hai số biết hai hiệu số.

**Ví dụ 5.12.** Dãy năm học, cô giáo chủ nhiệm lớp 4C xếp chỗ ngồi cho các bạn. Cô nhằm tính: nếu xếp mỗi bàn 3 học sinh thì 4 học sinh không có chỗ ngồi; nếu xếp mỗi bàn 4 học sinh thì thừa 2 bàn không có học sinh ngồi. Hỏi lớp 4C có bao nhiêu học sinh và bao nhiêu cái bàn?

*Trước hết ta dùng phương pháp toán sơ cấp giải bài toán trên:*

Gọi số bàn là  $x$  (cái), số học sinh của lớp 4C là  $y$  (học sinh). Theo đề bài ta có hệ phương trình:

$$\begin{cases} 4x - y = 4.2 \ (1) \\ y - 3x = 4 \ (2) \end{cases}$$

Cộng về vế của (1) và (2) ta được:  $x = 12$ .

Thay vào (2) ta được:  $y = 40$ .

Trả lời: Lớp đó có 40 học sinh và 12 cái bàn.

*Từ cách giải trên, ta diễn giải thành phương pháp giải cho học sinh tiêu học như sau:*

Mỗi bàn ngồi 4 học sinh hơn một bàn ngồi ba học sinh là:

$$4 - 3 = 1 \text{ (học sinh)}$$

Tổng số học sinh ngồi mỗi bàn 4 học sinh hơn tổng số học sinh ngồi mỗi bàn 3 học sinh là:

$$4 + 4 \times 2 = 12 \text{ (học sinh)}$$

Số cái bàn là:

$$12 : 1 = 12 \text{ (cái)}$$

Số học sinh là:

$$3 \times 12 + 4 = 40 \text{ (học sinh)}$$

Đáp số: 40 học sinh; 12 cái bàn.

#### 8. Phép quy nạp hoàn toàn và phương pháp thử chọn

Trong chương I chúng ta đã làm quen với phép quy nạp hoàn toàn. Ở Tiếng học, người ta vận dụng phép suy luận này trong giải nhiều bài toán cho học sinh tiểu học. Dưới đây chúng ta minh họa một số ví dụ.

**Ví dụ 5.13.** Tích của tử số và mẫu số của một phân số lớn hơn 1 bằng 315, khi chia cả tử số và mẫu số của phân số đó cho 3 ta được một phân số tối giản. Tìm phân số đó.

**Giải:** Số 315 có thể phân tích thành tích của các cặp số sau: 1 và 315; 3 và 105; 5 và 63; 7 và 45; 9 và 35; 15 và 21.

Các phân số cần tìm có thể là:

$$\frac{315}{1}, \frac{105}{3}, \frac{63}{5}, \frac{45}{7}, \frac{35}{9}, \frac{21}{15}$$

Ta có bảng sau:

| a<br>b          | $\frac{a}{b} : 3$ = phân số tối giản? | Kết luận |
|-----------------|---------------------------------------|----------|
| $\frac{315}{1}$ | $\frac{315}{1} : 3 = \frac{315}{1:3}$ | Loại     |
| $\frac{105}{3}$ | $\frac{105}{3} : 3 = \frac{35}{1}$    | Chọn     |
| $\frac{63}{5}$  | $\frac{63}{5} : 3 = \frac{63}{5:3}$   | Loại     |
| $\frac{45}{7}$  | $\frac{45}{7} : 3 = \frac{45}{7:3}$   | Loại     |
| $\frac{35}{9}$  | $\frac{35}{9} : 3 = \frac{35}{9:3}$   | Loại     |
| $\frac{21}{15}$ | $\frac{21}{15} : 3 = \frac{7}{5}$     | Chọn     |

Vậy các phân số cần tìm là:  $\frac{105}{3}$  và  $\frac{21}{15}$ .

Cách giải như trên, ta gọi là *phương pháp thử chọn*.

**Vi dụ 5.14.** Một khu đất hình chữ nhật có diện tích  $735\text{m}^2$ , chiều rộng

bằng  $\frac{3}{5}$  chiều dài. Hỏi cần bao nhiêu chiếc cọc để rào xung quanh khu đất đó? Biết rằng khoảng cách giữa hai cọc bằng  $0,5\text{m}$  và ở một góc người ta để lối ra vào rộng  $3\text{m}$ .

**Giải:** Số  $735$  có thể là tích của các cặp số tự nhiên sau:  $1$  và  $735$ ;  $3$  và  $245$ ;  $5$  và  $147$ ;  $7$  và  $105$ ;  $21$  và  $35$ .

Bằng phương pháp thử chọn ta tìm được chiều rộng của khu đất là  $21\text{m}$ , chiều dài là  $35\text{m}$ .

Chu vi khu đất là:  $(21 + 35) \times 2 = 112\text{ (m)}$

Số cọc cần dùng là:  $(112 - 3) : 0,5 + 1 = 219\text{ (cọc)}$

Dáp số:  $219\text{ cọc}$ .

Ví dụ 5.15. Ví dụ 5.9 có thể giải bằng phương pháp thử chọn như sau:

Ta có bảng sau:

| Số con chó | Số con gà | Tổng số chân                         | Kết luận |
|------------|-----------|--------------------------------------|----------|
| 1          | 15        | $4 \times 1 + 15 \times 2 = 34 < 40$ | Loại     |
| 2          | 14        | $4 \times 2 + 14 \times 2 = 36 < 40$ | Loại     |
| 3          | 13        | $4 \times 3 + 13 \times 2 = 38 < 40$ | Loại     |
| 4          | 12        | $4 \times 4 + 12 \times 2 = 40 = 40$ | Chọn     |

Mỗi khi tăng 1 con chó và giảm 1 con gà thì tổng số chân tăng thêm 2.

Nếu số chó lớn hơn 4 thì số chân lớn hơn 40.

Vậy có 12 con gà và 4 con chó.

#### 9. Yếu tố đại số trong môn Toán tiểu học

Trong chương trình môn Toán tiểu học, nội dung về các yếu tố đại số được trình bày trong môn Toán lớp 4 và 5. Nó bao gồm các nội dung:

- Khái niệm về biểu thức số và giá trị của biểu thức số;
- Khái niệm về biểu thức chứa chữ và giá trị số của biểu thức chứa chữ;
- Ứng dụng biểu thức chứa chữ để phát biểu các tính chất của các phép toán và quy tắc thực hành tính toán;
- Ứng dụng biểu thức chứa chữ để xây dựng công thức tính chu vi, diện tích và thể tích các hình;

– Ứng dụng của yếu tố đại số để hình thành các phương pháp giải toán cho học sinh tiểu học.

## BÀI TẬP CHƯƠNG V

Anh (chị) hãy giải các bài toán sau cho học sinh tiểu học:

Bài 1. Nếu có số toán học của phương pháp tính ngược từ cuối. Cho ví dụ minh hoạ.

Bài 2. Tìm một số, biết rằng khi bớt số đó đi 3, sau đó chia cho 2 rồi cộng với 1,5 và cuối cùng nhân với 4 được kết quả bằng 60.

Bài 3. Tổng của ba số bằng 180. Sau khi chuyển từ số thứ nhất sang số thứ hai 12 đơn vị, sang số thứ ba 16 đơn vị. Cuối cùng chuyển từ số thứ hai sang số thứ ba 15 đơn vị ta được ba số bằng nhau. Tìm ba số đó.