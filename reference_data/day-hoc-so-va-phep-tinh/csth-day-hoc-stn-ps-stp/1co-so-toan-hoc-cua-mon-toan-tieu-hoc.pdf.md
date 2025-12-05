

TRÁN DIỄN HIẾN (Chủ biên)  
NGUYỄN THỦY CHUNG

# CƠ SỞ TOÁN HỌC CỦA MÔN TOÁN TIỂU HỌC

![Diagram showing a semicircle with diameter AB. A vertical line segment NM is drawn from the arc to the diameter, with M marked on the diameter and a right angle symbol at M.](30a26f2d17ca95672702bf50fb4f0242_img.jpg)

Diagram showing a semicircle with diameter AB. A vertical line segment NM is drawn from the arc to the diameter, with M marked on the diameter and a right angle symbol at M.

![Two overlapping triangles, one outlined in red and one outlined in black, illustrating geometric concepts.](64662465bba247703fdec49c8f3309f9_img.jpg)

Two overlapping triangles, one outlined in red and one outlined in black, illustrating geometric concepts.

![Logo of SP (Sư Phạm) University.](5fb340ad68b0c71df0b56698b137e35b_img.jpg)

Logo of SP (Sư Phạm) University.

NHÀ XUẤT BẢN ĐẠI HỌC SƯ PHẠM

## CHƯƠNG IV

## Cơ sở toán học của các tập hợp số trong môn Toán tiểu học

### I. Cơ sở toán học của số học các số tự nhiên ở Tiểu học

#### 1. Xây dựng tập số tự nhiên

##### 1.1. Song ảnh

**Dịnh nghĩa 4.1.** Cho  $X$  và  $Y$  là hai tập hợp. Quy tắc cho tương ứng mỗi phần tử  $x$  thuộc tập  $X$  với một phần tử duy nhất  $y = f(x)$  thuộc tập  $Y$  gọi là ảnh  $x$  từ tập  $X$  vào tập  $Y$  và ký hiệu là:

$$f: X \to Y$$

$$x \mapsto y = f(x)$$

Tập  $X$  gọi là miền xác định (hay tập nguồn), tập  $Y$  gọi là tập đích của ảnh  $x$ .

Với mỗi  $x \in X$  ta gọi  $f(x)$  là ảnh của phần tử  $x$ ,  $x$  là tạo ảnh của  $f(x)$  qua ảnh  $x$ .

$$M = (M)_{\text{ng} \leftarrow M}$$

Nếu  $A$  là tập con của  $X$  thì ta gọi tập:

$$f(A) = \{f(x) : x \in A\}$$

là ảnh của tập  $A$  qua ảnh  $x$ .

Trường hợp đặc biệt,  $f(X)$  gọi là tập ảnh của ảnh  $x$ .

**Dịnh nghĩa 4.2.** Cho  $f$  là ảnh  $x$  từ tập  $X$  vào tập  $Y$ . Ta gọi:

a)  $f$  là đơn ánh, nếu với mỗi  $x_1, x_2 \in X$ ,  $x_1 \neq x_2 \Rightarrow f(x_1) \neq f(x_2)$ . Hay với hai tạo ảnh khác nhau cho ta hai ảnh khác nhau.

b)  $f$  là toàn ánh, nếu với mỗi  $y \in Y$ ,  $\exists x \in X : f(x) = y$ . Hay  $f(X) = Y$ .

Trong trường hợp này ta nói  $f$  là ảnh  $x$  từ tập  $X$  lên tập  $Y$ .

c)  $f$  là song ảnh, nếu  $f$  vừa là đơn ánh vừa là toàn ánh.

**Ví dụ 4.1.** Cho  $X = \{a, b, c, d, e\}$ ;  $Y = \{1, 2, 3, 4, 5\}$ . Ta định nghĩa:

$$f: X \to Y$$

xác định bởi quy tắc:  $f(a) = f(e) = 1$ ;  $f(b) = 2$ ;  $f(c) = 3$  và  $f(d) = 4$ . Khi đó  $f$  là một ảnh  $x$  từ  $X$  vào  $Y$ ,  $f$  không phải là đơn ánh và cũng không phải là toàn ánh.

Ví dụ 4.2. Mối hàn số ta đã gặp trong trường phổ thông xác định một ánh xạ với miền xác định là tập xác định của hàm số đó vào tập số thực  $\mathbb{R}$ .

Chẳng hạn, hàm số  $y = 2^x - 1$  xác định một ánh xạ từ  $\mathbb{R}$  vào  $\mathbb{R}$  với quy tắc xác định là quy tắc xác định của hàm số đó.

Ánh xạ trên là đơn ánh nhưng không phải là toàn ánh.

Hàm số  $y = x^3 + 1$  cũng xác định một song ánh:

$$\varphi: \mathbb{R} \to \mathbb{R}$$

$$x \mapsto \varphi(x) = x^3 + 1$$

từ tập  $\mathbb{R}$  lên chính nó.

Ví dụ 4.3. Cho X là tập các điểm trên đoạn thẳng AB và Y là tập các điểm trên đoạn thẳng CD. Ta định nghĩa:

![Diagram showing two line segments AB and CD. A point M is on AB, and a point N is on CD. A line segment connects A to N and B to C, intersecting at O. M and N are marked on the respective segments.](1517552d07f4a8b389be86af8aff6424_img.jpg)

Diagram showing two line segments AB and CD. A point M is on AB, and a point N is on CD. A line segment connects A to N and B to C, intersecting at O. M and N are marked on the respective segments.

$$g: X \to Y$$
$$M \mapsto g(M) = N$$

trong đó M và N được xác định như hình vẽ. Khi đó g là song ánh từ tập X lên tập Y.

Ví dụ 4.4. Gọi A là tập con người đang sống trên Trái Đất và B là tập các tên gọi của những người đó. Nếu ta định nghĩa: Với mỗi  $a$  thuộc tập A cho  $\text{trung} \text{vi} \text{m} \text{ph} \text{ản} \text{t} \text{t} \text{r} \text{u} \text{b} = f(a)$  là tên của người đó thì ta được một toàn ánh từ A lên B nhưng không phải là đơn ánh (ta giả thiết là mỗi người chỉ có một tên gọi).

**Định nghĩa 4.3.** Cho  $f$  là song ánh từ tập X lên tập Y. Ta gọi ánh xạ:

$$f^{-1}: Y \to X$$

$$y \mapsto f^{-1}(y) = x$$

là ánh xạ ngược của  $f$ , nếu với mọi  $x \in X$  ta luôn có  $f^{-1}(f(x)) = x$ , hay với mọi  $y \in Y: f(f^{-1}(y)) = y$ .

Ví dụ 4.5. Ánh xạ ngược  $\varphi^{-1}$  của ánh xạ  $\varphi$  trong ví dụ 4.2 xác định bởi quy tắc  $\varphi^{-1}(y) = \sqrt[3]{y-1}$  với mỗi số thực  $y$ .

Ví dụ 4.6. Ánh xạ  $g$  trong ví dụ 4.3 có ánh xạ ngược  $g^{-1}$  xác định bởi quy tắc  $g^{-1}(N) = M$ .

**Dịnh nghĩa 4.4.** Cho:  $f: X \to Y$ ,  $g: Y \to Z$ .

Ta gọi ánh xạ:

$$h: X \to Z$$

là ánh xạ hợp (hay tích) của hai ánh xạ  $f$  và  $g$ .  
 $x \mapsto z = h(x) = g(f(x))$

Ví dụ 4.7. Khái niệm hàm hợp là trường hợp đặc biệt của ánh xạ hợp.

Ví dụ 4.8. Cho  $X$  và  $Y$  là hai tập hợp trong ví dụ 4.1 và  $Z = \{An, Cúc, Nga\}$ . Ta định nghĩa:  $f$  là ánh xạ trong Ví dụ 4.1 và  $g$  là ánh xạ từ  $Y$  vào  $Z$ :  $g(1) = An$ ,  $g(2) = Cúc$  và  $g(3) = g(4) = Nga$ . Khi đó ánh xạ tích:  $h: X \to Z$  xác định bởi quy tắc:  $h(a) = An$ ;  $h(b) = Cúc$ ;  $h(c) = h(d) = Nga$  và  $h(e) = An$ .

**Dịnh lí 4.1.** Tính chất của các phép toán trên ánh xạ:

1. Tích của hai đơn ánh là một đơn ánh.
2. Tích của hai toàn ánh là một toàn ánh.
3. Tích của hai song ánh là một song ánh.

*Chứng minh.*

(i) Giả sử  $f$  là đơn ánh từ  $X$  vào  $Y$ ,  $g$  là đơn ánh từ  $Y$  vào  $Z$ ;  $x_1, x_2$  là hai phần tử khác nhau thuộc  $X$ . Vì  $f$  là đơn ánh nên  $f(x_1) \neq f(x_2)$ . Vì  $g$  cũng là đơn ánh nên  $g(f(x_1)) \neq g(f(x_2))$  hay  $h(x_1) \neq h(x_2)$ .

(ii) và (iii) Tương tự (i).

##### 1.2. Tập hợp tương đương

**Dịnh nghĩa 4.5.** Cho  $X$  và  $Y$  là hai tập hợp. Ta nói rằng tập  $X$  tương đương với tập  $Y$ , ký hiệu là  $X \sim Y$ , nếu tồn tại song ánh  $f$  từ  $X$  lên  $Y$ .

Ví dụ 4.9. Tập  $X$  và tập  $Y$  trong Ví dụ 4.1 không tương đương với nhau.

Ví dụ 4.10. Theo Ví dụ 4.2 ta có tập các điểm thuộc đoạn thẳng  $AB$  tương đương với tập các điểm thuộc đoạn thẳng  $CD$ .

Ví dụ 4.11. Tập  $I$  gồm các số thực nằm giữa  $0$  và  $1$  ( $I = (0;1)$ ) tương đương với tập các số thực dương  $\mathbb{R}^+$ .

Thật vậy, song ánh  $f$  xác định bởi quy tắc:

$$f(x) = \frac{1}{x}.$$

Ví dụ 4.12. Tập (a; b) các số thực nằm giữa a và b và tập (c; d) các số thực nằm giữa c và d trong dương với nhau.

**Định lý 4.2.** (Tính chất của quan hệ tương đương giữa các tập hợp)

Quan hệ tương đương giữa các tập hợp thỏa mãn các tính chất sau đây:

(i) *Tính phản xạ*: Mọi tập A đều tương đương với chính nó.

(ii) *Tính đối xứng*: Nếu A tương đương với B thì B cũng tương đương với A.

(iii) *Tính bắc cầu*: Nếu A tương đương với B và B tương đương với C thì A tương đương với C.

##### 1.3. Tập hợp hữu hạn và vô hạn – Bán số tập hợp

**Định nghĩa 4.6.** Cho A là một tập hợp. Ta nói rằng:

a) A là tập vô hạn nếu A tương đương với một tập con thực sự của nó.

b) A là tập hữu hạn nếu A không phải là tập vô hạn, hay A không tương đương với mọi tập con thực sự của nó.

**Ví dụ 4.13.** Các tập X, Y trong Ví dụ 4.1 là hữu hạn.

**Ví dụ 4.14.** Tập các điểm thuộc một đoạn thẳng là tập vô hạn;

Tập các số nằm giữa hai số a và b là tập vô hạn.

**Định lý 4.3.** (Tính chất của tập hữu hạn)

(i) Mọi tập con của tập hữu hạn là tập hữu hạn.

(ii) Hợp của hai tập hữu hạn là một tập hữu hạn.

(iii) Tích Đế-các của hai tập hữu hạn là một tập hữu hạn.

*Chứng minh.*

(i) Giả sử A là tập hữu hạn và B là tập con của A. Giả sử B là tập vô hạn. Khi đó tồn tại tập con thực sự  $B' \subset B$  và tương đương với B. Theo định nghĩa, tồn tại song ánh:

$$f: B \to B'$$

Đặt  $A' = (A \setminus B) \cup B'$ . Ta dễ dàng chỉ ra rằng  $A'$  là tập con thực sự của A và tương đương với A. Suy ra A là tập vô hạn. Điều này trái với giả thiết.

Ta có điều phải chứng minh.

(ii) Giả sử A và B là hai tập hữu hạn. Ta chứng minh  $A \cup B$  cũng là tập hữu hạn. Trước hết ta xét trường hợp A và B là hai tập rời nhau.

Giả sử  $A \cup B$  là tập vô hạn. Khi đó tồn tại một đơn ánh  $f$  từ  $A \cup B$  vào chính nó nhưng không phải là toàn ánh, tức là:

$$\exists a \in A \cup B, \forall x \in A \cup B: f(x) \neq a. \text{ Ta có thể giả thiết } a \in A.$$

Đặt  $A_1 = f(A); B_1 = f(B)$  khi đó  $A \sim A_1, B \sim B_1, A_1 \cap B_1 = \emptyset$ .

Đặt  $A_2 = A_1 \cap B$  thì  $A_2 \subset B \setminus B_1; B_2$

Bằng phương pháp quy nạp ta dễ dàng suy ra: Hợp của một họ hữu hạn các tập hữu hạn là tập hữu hạn.

(iii) Giả sử  $A$  và  $B$  là hai tập hữu hạn. Ta chứng minh  $A \times B$  cũng là tập hữu hạn. Ta xét các trường hợp sau:

(a)  $B$  là tập rỗng. Hiển nhiên  $A \times B$  là tập hữu hạn.

(b)  $B = \{b\}$  thì  $A \times B = A \times \{b\}$ . Từ đây dễ dàng chỉ ra  $A \times B$  là tập hữu hạn.

(c)  $B = \{b_1, b_2, \dots, b_n\}$  thì  $A \times B = \bigcup_{i=1}^{n} A_i; A_i = A \times \{b_i\}, i=1, \dots, n$ .

Từ đây suy ra điều phải chứng minh.

**Định nghĩa 4.7.** Hai tập  $A$  và  $B$  tương đương với nhau ta nói chúng có cùng bản số. Ta dùng ký hiệu  $\text{Card} A$ , hoặc  $\overline{A}$ , để chỉ bản số của tập  $A$ .

Vậy nếu  $A = B$  thì  $\text{Card} A = \text{Card} B$ .

**Ví dụ 4.15.**  $\text{Card} \{\emptyset\} = \text{Card} \{x\}$ , với  $x$  là phần tử bất kì.

Hai tập  $X$  và  $Y$  trong Ví dụ 4.3 có cùng bản số.

Tập các điểm thuộc hai đoạn thẳng bất kì có cùng bản số.

Tập các số nằm giữa hai số  $a$ ,  $b$  và tập các số nằm giữa hai số  $c$ ,  $d$  có cùng bản số.

**Ví dụ 4.16.** Tập các điểm thuộc nửa đường tròn đường kính  $AB$  có cùng bản số với tập các điểm thuộc đường kính của đường tròn đó.

Thật vậy, mỗi điểm  $M$  thuộc đoạn thẳng  $AB$  ta cho tương ứng với điểm  $N$  thuộc nửa đường tròn theo hình vẽ dưới đây:

![Diagram showing a semicircle with diameter AB. A vertical line segment MN is drawn from the diameter AB up to the semicircle arc, with M on AB and N on the arc. M and N are endpoints of a diameter of the semicircle.](cf4d1dffb34bbf2d70050e4560ec180d_img.jpg)

Diagram showing a semicircle with diameter AB. A vertical line segment MN is drawn from the diameter AB up to the semicircle arc, with M on AB and N on the arc. M and N are endpoints of a diameter of the semicircle.

##### 1.4. Xây dựng tập số tự nhiên

**Định nghĩa 4.8.** Bản số của một tập hữu hạn gọi là một số tự nhiên. Ta dùng các chữ cái  $a, b, c, \dots$  để kí hiệu các số tự nhiên. Hay nói một cách khác, nếu  $A$  là tập hữu hạn thì bản số của tập  $A$  xác định một số tự nhiên và ký hiệu là  $a = \text{Card } A$ .

Tập tất cả các số tự nhiên ta kí hiệu là  $\mathbb{N}$ .

Ví dụ 4.17.

Card  $\emptyset$  là một số tự nhiên. Kí hiệu là 0.

Card  $\{\emptyset\}$  là một số tự nhiên. Kí hiệu là 1.

Card  $\{\emptyset, \{\emptyset\}\}$  là một số tự nhiên. Kí hiệu là 2.

##### 1.5. Hình thành khái niệm số tự nhiên trong môn Toán tiểu học

Trong chương trình môn Toán tiểu học, các khái niệm về số tự nhiên được trình bày trong môn Toán từ lớp 1 đến hết học kì I của lớp 4. Nó bao gồm các nội dung sau:

– Giới thiệu 10 chữ số cơ bản từ 0 đến 9.

– Hình thành khái niệm các số tự nhiên có một, hai và nhiều chữ số: hàng và lớp của một số tự nhiên.

– Giới thiệu cách đọc, viết và phân tích theo cấu tạo của một số tự nhiên.

– Giới thiệu khái niệm số chẵn, số lẻ, số tròn chục và số tròn trăm...

– Giới thiệu khái niệm số liên trước, số liền sau của một số tự nhiên và hai số tự nhiên liên tiếp.

Mười chữ số cơ bản từ 0 đến 9 được hình thành dựa trên công cụ *bản số* tập hợp. Nó được trình bày bằng ngôn ngữ đơn giản nhất phù hợp với học sinh tiểu học. Chẳng hạn, trong sách giáo khoa Toán 1:

– Từ biểu tượng hai con mèo, hai học sinh, hai chấm tròn,... dẫn đến số 2.

– Từ biểu tượng năm cái máy bay, năm cái kéo, năm chấm tròn,... dẫn đến số 5.

– Từ biểu tượng trong chậu có ba con cá: dùng vớt lân đầu vớt 1 con trong chậu còn 2 con, lân thứ hai vớt 1 con nữa còn 1 con và lân thứ ba vớt 1 con nữa thì trong chậu không còn con nào. Từ đó dẫn đến số 0.

Các số tự nhiên có hai, ba và nhiều chữ số được hình thành dựa trên công cụ là các que tính hoặc ô vuông.... phù hợp với học sinh của lớp đó. Chẳng hạn:

– Trong sách giáo khoa Toán 1: Từ biểu tượng một bó 10 que tính đặt cạnh 6 que tính dẫn đến số 16;

– Trong sách giáo khoa Toán 2: Từ biểu tượng một bảng có 100 ô vuông đặt cạnh bảng có 20 ô vuông và 5 ô vuông dẫn đến số 125;

- Trong sách giáo khoa Toán 3: Nhìn vào bảng ở cột nghìn ghi số 8, cột trăm ghi số 5, cột chục ghi số 6 và cột đơn vị ghi số 3 dẫn đến số 8563, đọc là tám nghìn năm trăm sáu mươi ba;

Khái niệm số tròn chục, tròn trăm thông qua những số tự nhiên cụ thể, học sinh hiểu số tròn chục là những số có hàng đơn vị bằng 0. Số tròn trăm là những số có hàng đơn vị và hàng chục bằng 0.

Khái niệm số liền trước, số liền sau được hình thành bằng hình ảnh trực quan trên tia số (SGK Toán 1).

Khái niệm số chẵn, số lẻ được hình thành dựa trên dấu hiệu chia hết cho 2 (SGK Toán 4): Số chia hết cho 2 là số chẵn, số không chia hết cho 2 là số lẻ.

#### 2. Cơ sở toán học của quan hệ thứ tự trong tập số tự nhiên ở Tiểu học

##### 2.1. Quan hệ thứ tự trong tập số tự nhiên

**Định nghĩa 4.9.** Cho  $a$  và  $b$  là hai số tự nhiên, trong đó  $a = \text{Card A}$  và  $b = \text{Card B}$ . Ta nói rằng:

a) Số tự nhiên  $a$  nhỏ hơn hoặc bằng số tự nhiên  $b$ , kí hiệu là  $a \le b$ , nếu

A tương đương với một tập con của B

b)  $a$  nhỏ hơn  $b$ , kí hiệu là  $a < b$ , nếu  $a \le b$  và  $a \ne b$ .

c)  $a$  lớn hơn hoặc bằng  $b$ , kí hiệu là  $a \ge b$ , nếu  $b \le a$ .

d)  $a$  lớn hơn  $b$ , kí hiệu là  $a > b$ , nếu  $b < a$ .

Các hệ thức  $a \le b$  và  $a \ge b$  gọi là các bất đẳng thức, các hệ thức  $a < b$  và  $a > b$  gọi là các bất đẳng thức nghiêm ngặt.

Ta thừa nhận mà không chứng minh bổ đề Căng-to (Cantor) sau đây:

**Bổ đề Căng-to.** Với hai tập A và B bất kì luôn xảy ra một trong hai khả năng dưới đây:

(i) A tương đương với một tập con của B;

(ii) B tương đương với một tập con của A.

Nếu đồng thời xảy ra cả hai khả năng trên thì A tương đương với B.

**Định lí 4.4.** (Tính chất của quan hệ thứ tự trong tập số tự nhiên)

Quan hệ thứ tự  $\le$  trong tập hợp N các số tự nhiên thỏa mãn các tính chất sau đây:

(i)  $\text{Phân xạ: } \forall a \in \mathbb{N}: a \le a$ ;

(ii)  $\text{Phản đối xứng: Nếu } a \le b \text{ và } b \le a \text{ thì } a = b$ .

(iii)  $\text{Bắc cầu: Nếu } a \le b; b \le c \text{ thì } a \le c$ .

(iv)  $\text{Không tồn tại số tự nhiên } a \text{ nhỏ hơn số } 0$ , hay  $0$  là số tự nhiên nhỏ nhất.

(v)  $\text{Không tồn tại số tự nhiên lớn nhất, hay mọi số tự nhiên } a \text{ đều tồn tại một số tự nhiên } b \text{ lớn hơn nó.}$

**Chứng minh.**

(i) Suy ra từ Định lý 4.2 (i).

(ii), (iii) Suy ra từ định nghĩa và bổ đề Căng-to.

(iv) Giả sử tồn tại số tự nhiên  $a = \text{Card } A$  và  $a < 0 = \text{Card } \emptyset$ . Như vậy  $A$  trong dương với tập con thực sự của  $\emptyset$ . Điều này vô lý.

(v) Giả sử  $a$  là số tự nhiên tùy ý  $a = \text{Card } A$ .

Rõ ràng là  $b = \text{Card } A \cup \{\emptyset\} > a$ .

Hệ quả. Tập số tự nhiên là vô hạn.

**Chứng minh.** Suy ra trực tiếp từ (v).

##### 2.2. Số tự nhiên liên trước, liên sau và số tự nhiên liên tiếp

**Định nghĩa 4.10.** Cho  $a$  là số tự nhiên,  $a = \text{Card } A$  và  $x$  là phần tử không thuộc tập  $A$ . Ta gọi số tự nhiên  $b = \text{Card } A \cup \{x\}$  là số liên sau của  $a$  và kí hiệu là  $a' = b$ .

Nếu  $b$  là số liên sau của  $a$  thì ta gọi  $a$  là số liên trước của  $b$  và kí hiệu là  $b = a'$ .

Hai số tự nhiên  $a$  và  $b$  nếu trên gọi là hai số tự nhiên liên tiếp.

**Định lý 4.5.** (Tính chất của số liên sau)

(i) Mỗi số tự nhiên  $a$  luôn có duy nhất số liên sau;

(ii) Số  $0$  không có số liên trước;

(iii) Nếu  $a$  và  $b$  là hai số tự nhiên sao cho  $a < b$  thì  $a' \le b$ .

**Chứng minh.**

(i)  $\text{Sự tồn tại:}$  Giả sử  $a$  là số tự nhiên,  $a = \text{Card } A$ . Theo định nghĩa: Số liên sau  $a' = \text{Card } A \cup \{x\}$  với  $x \notin A$ . Rõ ràng là  $\text{Card } A \cup \{x\}$  cũng là số tự nhiên.

**Tính duy nhất:** Giả sử  $b$  và  $c$  là hai số liên sau của  $a$ , trong đó  $b = \text{Card}A \cup \{x\}$ ,  $c = \text{Card}A \cup \{y\}$  với  $x$  và  $y$  đều không thuộc  $A$ . Rõ ràng là  $A \cup \{x\} \sim A \cup \{y\}$ . Từ đó suy ra  $b = c$ .

(ii) Suy ra từ Định lý 4.4.

(iii) Giả sử  $a$  và  $b$  là hai số tự nhiên, trong đó  $a < b$  và  $a = \text{Card} A$  và  $b = \text{Card} B$  sao cho  $A \subset B$ . Vì  $a < b$  nên tồn tại  $x \in B \setminus A$ . Đặt  $B' = A \cup \{x\}$ . Ta có:

$a' = \text{Card} B'$  và  $A \subset B' \subset B$  nên  $a' \le b$ .

**Hệ quả.** Giữa hai số tự nhiên  $a$  và số liên sau  $a'$  của nó không tồn tại một số tự nhiên nào khác.

Thật vậy, giả sử tồn tại số tự nhiên  $b$  sao cho  $a < b < a'$ . Từ đó suy ra  $a' \le b < a'$ . Điều này vô lý. Ta có điều phải chứng minh.

Ta gọi tính chất trên đây là *tính rời rạc* của tập số tự nhiên.

**Chú ý:** Đặt  $0 = \text{Card}\emptyset$ ;  $1 = \text{Card}\{\emptyset\}$ ;  $2 = 1'$ ;  $3 = 2'$ ;  $4 = 3'$ ; ... Cứ tiếp tục như trên ta nhận được đầy các số tự nhiên:

1; 2; 3; 4; ...; 10; 11; ...; 100; 101; ...

**Định nghĩa 4.11.** Cho  $A$  là tập con của tập số tự nhiên  $N$ . Ta nói rằng:

a)  $A$  là tập bị chặn trên (trong ưng bị chặn dưới) nếu tồn tại số tự nhiên  $M$  (trong ưng  $m$ ) sao cho:

$a \le M$  ( $a \ge m$ ),  $\forall a \in A$ .

Nếu tập  $A$  đồng thời bị chặn trên và bị chặn dưới thì ta gọi  $A$  là tập bị chặn.

b) Số tự nhiên  $M$  (trong ưng  $m$ ) gọi là số lớn nhất (trong ưng nhỏ nhất) của tập  $A$ , nếu  $M \in A$  ( $m \in A$ ) và  $a \le M$  ( $a \ge m$ )  $\forall a \in A$ .

Ta thừa nhận tính chất sau đây của tập số tự nhiên:

Mọi tập con khác rỗng bị chặn trên của tập số tự nhiên đều có số lớn nhất.

Mọi tập con khác rỗng của tập số tự nhiên đều có số nhỏ nhất.

##### 2.3. Quan hệ thứ tự trong tập số tự nhiên ở Tiểu học

Trong chương trình môn Toán tiểu học, quan hệ so sánh giữa các số tự nhiên được trình bày trong môn Toán từ lớp 1 đến hết học kì I của lớp 4 theo các giai đoạn:

- Từ các biểu tượng dần đến khái niệm so sánh giữa hai đối tượng;

- Hình thành các kĩ năng so sánh các số tự nhiên;

– Xây dựng các quy tắc số và giải các số tự nhiên;

– Tổng kết các tính chất của dãy số tự nhiên;

...

Bằng các biểu tượng, ngay từ tiết học đầu tiên sách giáo khoa Toán 1 hinh thành cho học sinh khái niệm *nhieu hon, it hon*.

Bằng công cụ bàn số, hinh thành cho học sinh khái niệm về quan hệ so sánh giữa các số tự nhiên. Chẳng hạn:

– Từ bức tranh 5 quả bóng và 3 quả bóng dẫn học sinh đến quan hệ so sánh  $3 < 5$  và  $5 > 3$  (SGK Toán 1)...

– Từ biểu tượng mô tả số 234 và biểu tượng mô tả số 235 dẫn đến quan hệ so sánh  $234 < 235$  và  $235 > 234$  (SGK Toán 2)...

Từ các hiện tượng tích lũy qua các số đến 10, đến 100, đến 1000, đến 10 000, sách giáo khoa Toán 3 rút ra cho học sinh quy tắc:

(1) *Trong hai số:*

– Số nào có ít chữ số hơn thì bé hơn;

– Số nào có nhiều chữ số hơn thì lớn hơn.

(2) Nếu hai số có số chữ số bằng nhau thì so sánh từng cặp chữ số ở cùng một hàng, kể từ trái sang phải.

(3) Nếu hai số có cùng số chữ số và từng cặp chữ số ở cùng một hàng đều giống nhau thì hai số đó bằng nhau.

(4) Dẫn hinh thành cho học sinh kĩ năng xác định số lớn nhất, số bé nhất trong một nhóm các số tự nhiên cho trước và sắp xếp chúng theo thứ tự tăng dần hoặc giảm dần.

Từ kiến thức về số tự nhiên đã học, sách giáo khoa Toán 4 chốt lại cho học sinh:

(a) Các số 0; 1; 2; 3; ...; 9; 10; ...; 100; ...; 1000; ... là các số tự nhiên;

(b) Các số tự nhiên xếp theo thứ tự từ bé đến lớn tạo thành dãy số tự nhiên:

0; 1; 2; 3; 4; 5; 6; 7; 8; 9; 10; 11; ...

(c) Có thể biểu diễn số tự nhiên trên tia số:

![](1a5e13c8676cf14beb6a2fed07927656_img.jpg)

Figure: A number line showing integers from 0 to 10, marked at 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10.

(d) Thêm 1 vào bất kì một số tự nhiên nào cũng được số tự nhiên liền sau nó. Vì vậy **không có số tự nhiên lớn nhất** và **dãy số tự nhiên có thể kéo dài mãi**.

(e) Bớt 1 ở bất kì số tự nhiên nào khác 0 ta cũng được số tự nhiên liền trước nó. Không có số tự nhiên nào liền trước số 0 nên số 0 là số tự nhiên bé nhất.

(g) Trong dãy số tự nhiên: Hai số liên tiếp thì hơn hoặc kém nhau 1 đơn vị.

3. Cơ sở toán học của các phép toán trong tập số tự nhiên ở Tiểu học

#### 3.1. Phép cộng và phép nhân

##### 3.1.1. Định nghĩa và tính chất

**Bổ đề 1.** Với hai số tự nhiên a và b luôn tồn tại hai tập hữu hạn rời nhau A và B sao cho  $a = \text{Card } A$  và  $b = \text{Card } B$ .

*Chứng minh.* Giả sử a và b là hai số tự nhiên, trong đó  $a = \text{Card } A$  và  $b = \text{Card } B$  với A và B là các tập hữu hạn.

Nếu  $A \cap B = \emptyset$  thì ta có điều phải chứng minh.

Chọn hai phần tử tùy ý  $x \neq y$ , ta đặt  $A' = A \times \{x\}$ ;  $B' = B \times \{y\}$  thì  $A'$  và  $B'$  đều là tập hữu hạn và  $A' \sim A$ ;  $B' \sim B$  nên  $a = \text{Card } A'$  và  $b = \text{Card } B'$ . Như vậy hai tập  $A'$  và  $B'$  thỏa mãn yêu cầu.

**Bổ đề 2.** Giả sử A, B,  $A'$  và  $B'$  là các tập hữu hạn sao cho

$$A \sim A', B \sim B'; A \cap B = A' \cap B' = \emptyset.$$

Khi đó:

$$(i) A \cup B \sim A' \cup B';$$

$$(ii) A \times B \sim A' \times B'.$$

**Định nghĩa 4.12.** Cho a và b là hai số tự nhiên, trong đó  $a = \text{Card } A$  và  $b = \text{Card } B$  với A và B là hai tập hữu hạn rời nhau. Ta gọi:

a) Tổng của hai số tự nhiên a và b là một số tự nhiên c, kí hiệu là  $c = a + b$ , trong đó  $c = \text{Card } (A \cup B)$ .

Quy tắc cho trong ứng mỗi cặp số tự nhiên a, b với một số tự nhiên c nói trên ta gọi là *phép cộng* các số tự nhiên, trong đó a và b gọi là các số hạng, c gọi là *tổng* và a + b cũng gọi là *tổng*.

b) Tích của hai số tự nhiên a và b là một số tự nhiên p, kí hiệu là  $p = a \times b$  (hoặc  $a \cdot b$  hoặc  $ab$ ), trong đó  $p = \text{Card } (A \times B)$ .

Quy tắc cho trong ứng mỗi cặp số tự nhiên a, b với một số tự nhiên p nói trên ta gọi là *phép nhân* các số tự nhiên, trong đó a, b gọi là các thừa số, p gọi là *tích* và a.b cũng gọi là *tích*.

**Nhận xét.** Từ định nghĩa, Định lý 4.3 và các Bổ đề 1, 2 ta dễ dàng suy ra:

a) Với mỗi cặp số tự nhiên  $a, b$  luôn tồn tại duy nhất số tự nhiên  $c$  là tổng của chúng.

b) Với mỗi cặp số tự nhiên  $a, b$  luôn tồn tại duy nhất số tự nhiên  $p$  là tích của chúng.

**Định lý 4.6.** (Tính chất của phép cộng và nhân)

(i) *Tính giao hoán:* Với mọi số tự nhiên  $a$  và  $b$  ta luôn có:

$$a + b = b + a; a \cdot b = b \cdot a.$$

(ii) *Tính kết hợp:* Với mọi số tự nhiên  $a, b, c$  ta luôn có:

$$a + (b + c) = (a + b) + c; a \cdot (b \cdot c) = (a \cdot b) \cdot c.$$

(iii) *Tính phân phối:* Với mọi số tự nhiên  $a, b, c$  ta luôn có:

$$a \cdot (b + c) = a \cdot b + a \cdot c.$$

(iv) *Phân tử trung lập:* Với mọi số tự nhiên  $a$  ta luôn có:

$$a + 0 = 0 + a = a; a \cdot 1 = 1 \cdot a = a.$$

(v) *Tính chất của số kề sau:* Với mọi số tự nhiên  $a$  ta luôn có: Số kề sau  $a' = a + 1$ .

**Chứng minh:** (i); (ii) và (iii) suy ra trực tiếp từ định nghĩa phép cộng, phép nhân và các tính chất giao hoán, kết hợp, phân phối của các phép toán trên tập hợp.

(i) Rõ ràng là:  $A \cup \emptyset = A$ ;  $A \times \{x\} = A$ . Từ đây suy ra điều phải chứng minh.

(ii) Theo định nghĩa số liền sau  $a' = \text{Card}A \cup \{x\} = \text{Card}A$  mà

$$\text{Card}A \cup \{x\} = \text{Card}A + \text{Card}\{x\} = a + 1.$$

**Chú ý:** Để đơn giản, ta quy ước:

a) Viết  $a + b + c$  thay cho  $a + (b + c)$  hoặc  $(a + b) + c$ ;

b) Viết  $a \cdot b \cdot c$  thay cho  $a \cdot (b \cdot c)$  hoặc  $(a \cdot b) \cdot c$ .

##### 3.1.2. Tính đơn điệu của phép cộng và phép nhân

**Định lý 4.7.** (Tính đơn điệu của phép cộng và phép nhân)

Với mọi số tự nhiên  $a, b, c$  ta luôn có:

$$(i) a \le b \Rightarrow a + c \le b + c; a \cdot c \le b \cdot c;$$

$$(ii) a + c = b + c \Rightarrow a = b: \text{Luật gián ước của phép cộng.}$$

$$a \cdot c = b \cdot c; c \ne 0 \Rightarrow a = b: \text{Luật gián ước của phép nhân.}$$

$$(iii) a+c < b+c \Rightarrow a < b.$$

$$a+c < b+c \Rightarrow a < b.$$

Chứng minh.

$$(i) \text{Giả sử } a = \text{Card A; } b = \text{Card B; } c = \text{Card C, trong đó } A \cap C = B \cap C = \emptyset. \text{ Nếu } a = b \text{ thì rõ ràng } a+c = b+c.$$

Nếu  $a < b$ , ta có thể coi  $A \subset B$ ,  $A \neq B$ . Khi đó:

$$A \cup C \subset B \cup C, A \cup C \neq B \cup C.$$

Từ đây suy ra  $a+c < b+c$ .

Tương tự đối với phép nhân.

(ii) Giả sử  $a+c = b+c$  và  $a < b$ . Theo chứng minh trên suy ra  $a+c < b+c$ . Điều này trái với giả thiết. Suy ra điều phải chứng minh.

Tương tự đối với phép nhân.

(iii) Suy ra từ (i).

**Nhận xét.** Từ định nghĩa ta suy ra phép cộng và phép nhân các số tự nhiên luôn thực hiện được.

##### 3.2. Phép trừ

**Định lý 4.8.** (Về sự tồn tại, tính duy nhất của hiệu hai số tự nhiên)

Giả sử  $a$  và  $b$  là hai số tự nhiên,  $b \le a$ . Khi đó tồn tại duy nhất số tự nhiên  $c$  sao cho  $b+c = a$ .

Chứng minh.

$$\text{Giả sử } a = \text{Card A; } b = \text{Card B; } B \subset A. \text{ Đặt } C = A \setminus B \text{ và } c = \text{Card C. (i)}$$

$$\text{Rõ ràng là: } A = B \cup C; B \cap C = \emptyset \text{ và } a = b+c.$$

**Định nghĩa 4.13.** Cho  $a$  và  $b$  là hai số tự nhiên, trong đó  $b \le a$ . Ta gọi số tự nhiên  $c$  trong Định lý 4.8 là hiệu của  $a$  và  $b$ , ký hiệu là  $c = a - b$ .

Quy tắc cho tương ứng mỗi cặp số tự nhiên  $a$ ,  $b$  với một số tự nhiên  $c$  nếu trên ta gọi là phép trừ các số tự nhiên.

**Định lý 4.9** (Về tính chất của phép trừ)

Với mọi số tự nhiên  $a$ ,  $b$ ,  $c$  ta luôn có:

$$a.(b-c) = a.b - a.c$$

néu một trong hai vé có nghĩa.

Chứng minh.

$$\text{Giả sử } b-c = d. \text{ Suy ra } b = c+d. \text{ Ta có:}$$

$$a.b = a.(c+d) = a.c + a.d.$$

$$\text{Từ đây suy ra } a.(b-c) = a.d = a.b - a.c.$$

**Nhận xét.** Từ định nghĩa ta suy ra phép trừ các số tự nhiên không phải luôn thực hiện được.

##### 3.3. Phép chia

##### 3.3.1. Quan hệ chia hết và phép chia hết trong tập số tự nhiên

**Định nghĩa 4.14.** Cho  $a$  và  $b$  là hai số tự nhiên, trong đó  $b$  khác 0. Ta nói rằng  $a$  chia hết cho  $b$ , kí hiệu là  $a:b$  (hay  $b$  chia hết  $a$ , kí hiệu là  $b|a$ ) nếu tồn tại số tự nhiên  $q$  sao cho:

$$a = bq.$$

Trong trường hợp này ta sẽ gọi  $a$  là số bị chia,  $b$  là số chia và  $q$  là thương của phép chia  $a$  cho  $b$  và viết là:

$$a : b = q \text{ hay } q = \frac{a}{b}.$$

Quy tắc cho tương ứng mỗi cặp số tự nhiên  $a, b$  với một số tự nhiên  $q$  nói trên ta gọi là phép chia các số tự nhiên.

###### Ví dụ 4.18.

15 chia hết cho 3 (hay 3 chia hết 15), vì  $15 = 3 \cdot 5$ . Ta viết:  $15 : 3 = 5$ .

132 chia hết cho 12 (hay 12 chia hết 132), vì  $132 = 12 \cdot 11$ . Ta viết:

$$132 : 12 = 11.$$

###### Định lý 4.10. (Tính chất của quan hệ chia hết)

1. Với mọi số tự nhiên  $a$  khác 0 ta luôn có  $a:a$ ;  $a:b$ ;
2. Nếu  $a:b$  và  $b:a$  thì  $a=b$ ;
3. Nếu  $a:b$  và  $b:c$  thì  $a:c$ ;
4. Số 0 chia hết cho mọi số tự nhiên khác 0;
5. Mọi số tự nhiên đều chia hết cho 1.

###### Chứng minh.

1. Rõ ràng, vì  $a = a \cdot 1$ .
2. Giả sử  $a:b$  và  $b:a$ . Suy ra tồn tại  $q, q' \in \mathbb{N}$  sao cho  $a = b \cdot q$  và  $b = a \cdot q'$ . Thay vào ta được  $a = a \cdot q \cdot q'$ . Suy ra  $q \cdot q' = 1$  hay  $q' = q^{-1} = 1$ . Thay vào ta được  $a = b$ .

1. Giả sử  $a:b$  và  $b:c$ . Suy ra tồn tại  $q, q' \in \mathbb{N}$  sao cho  $a = b \cdot q$  và  $b = c \cdot q'$ . Thay vào ta được  $a = c \cdot q \cdot q'$ . Suy ra điều phải chứng minh.

(iv) Rõ ràng là  $0 = b.0$ .

(v) Rõ ràng là  $a = 1.a$ .

**Nhận xét.** Mỗi phép chia hai số tự nhiên có không quá một thương.

Thật vậy, giả sử  $a$  và  $b$  là hai số tự nhiên và  $a : b = q$ ,  $a : a = b = q^1$ . Theo định nghĩa ta có:  $a = b.q$  và  $a = b.q^1$ . Suy ra  $b.q = b.q^1$ . Vì  $b$  khác 0 nên  $q = q^1$ .

###### 3.3.2. Phép chia có dư

**Định lý 4.11.** (Về phép chia có dư trong tập số tự nhiên).

Giả sử  $a$  và  $b$  là hai số tự nhiên, trong đó  $b \neq 0$ . Khi đó tồn tại duy nhất cặp số tự nhiên  $q$  và  $r$  sao cho:  $a = bq + r$ ;  $0 \le r < b$ .

*Chứng minh.*

a) **Sử tồn tại:** Giả sử  $a$  và  $b$  là hai số tự nhiên,  $b \neq 0$ .

Đặt  $A = \{m : bm \le a\}$ .

Rõ ràng là tập  $A$  khác rỗng và bị chặn trên nên nó có phần tử lớn nhất. Ta gọi phần tử lớn nhất là  $q$  và đặt  $r = a - bq$ . Khi đó:  $a = bq + r$ ;  $0 \le r < b$ .

b) **Tính duy nhất:** Giả sử tồn tại  $q_1, q_2, r_1, r_2 \in \mathbb{N}$ :  $a = bq_1 + r_1 = bq_2 + r_2$ ,  $0 \le r_1, r_2 < b$ . Giả sử  $q_1 \le q_2$ . Khi đó tồn tại số tự nhiên  $m$  sao cho  $q_2 = q_1 + m$ .

Ta có:

$$bq_2 + r_2 = b(q_1 + m) + r_2 = bq_1 + bm + r_2 = bq_1 + r_1.$$

Suy ra  $bm + r_2 = r_1$ . Vì  $r_1 < b$  nên điều này xảy ra khi và chỉ khi  $m = 0$ .

Vậy  $q_1 = q_2$  và  $r_1 = r_2$ . Ta có điều phải chứng minh.

**Định nghĩa 4.15.** Cho  $a$  và  $b$  là hai số tự nhiên, trong đó  $b \neq 0$ ,  $q$  và  $r$  là hai số nguyên dương,  $q$  là thương lớn nhất,  $r$  là số dư trong phép chia  $a$  cho  $b$ .

Quy tắc cho tương ứng mỗi cặp số tự nhiên  $a, b$  với một cặp số tự nhiên  $q$  và  $r$  nói trên ta gọi là phép chia có dư trong tập số tự nhiên.

**Chú ý:** Tự định nghĩa ta thấy rằng phép chia hết là trường hợp đặc biệt của phép chia có dư (khi số dư bằng 0).

Vì dụ 4.19.  $17 : 5 = 3$  (du 2);  $67 : 4 = 16$  (du 3);  $131 : 12 = 11$  (du 11).

##### 3.4. Các phép tính trong tập số tự nhiên ở Tiểu học

##### 3.4.1. Phép cộng và phép trừ trong tập số tự nhiên ở Tiểu học

Trong chương trình tiểu học, phép cộng và trừ các số tự nhiên được trình bày trong môn Toán từ lớp 1 đến hết học kì I của lớp 4 theo bốn giai đoạn:

– Dùng các biểu tượng dẫn đến ý nghĩa của phép cộng và ý nghĩa của phép trừ;

– Xây dựng các bảng cộng, trừ lâm cơ số để mở rộng các phép tính đó trong các vòng số lớn hơn;

– Xây dựng các quy tắc thực hành phép cộng và phép trừ;

– Mở rộng khái niệm mỗi phép tính để được khái niệm đầy tính, biểu thức.

Phép cộng và trừ các số trong phạm vi 10 (hay còn gọi là cộng trừ trong bảng) được hình thành dựa trên công cụ *bản số* tập hợp. Nó được trình bày bằng ngôn ngữ đơn giản nhất phù hợp với học sinh tiểu học. Chẳng hạn, trong sách giáo khoa Toán 1:

– Tự biểu tượng hai ô tô và một ô tô hoặc một con rùa và hai con rùa,... dẫn đến phép cộng  $2 + 1 = 3$  hoặc  $1 + 2 = 3$ .

– Tự biểu tượng bốn con cá và một con cá dẫn đến phép cộng  $4 + 1 = 5$  hoặc tư biểu tượng ba con vịt và hai con vịt dẫn đến phép cộng  $3 + 2 = 5$ ....

– Tự biểu tượng hai con ong đang đậu trên cánh hoa và một con bay đi dẫn đến phép trừ  $3 - 1 = 2$  và  $3 - 2 = 1$ ;

– Tự biểu tượng có bảy chấm tròn lấy đi 3 chấm tròn còn lại bốn chấm tròn dẫn đến phép trừ  $7 - 3 = 4$  và  $7 - 4 = 3$ ....

Trong sách giáo khoa Toán 2 và Toán 3 dẫn hình thành cho học sinh quy tắc thực hành phép cộng hoặc phép trừ các số có 2, 3 chữ số dựa trên công cụ là các que tính hoặc ô vuông.... phù hợp với học sinh của lớp đó. Chẳng hạn:

– Trong sách giáo khoa Toán 2: Tự biểu tượng 4 bó que tính đặt cạnh 7 que tính và 2 bó que tính đặt cạnh 5 que tính dẫn đến phép cộng  $47 + 25 = 72$  và qua đó hình thành quy tắc cộng các số có hai chữ số;

– Trong sách giáo khoa Toán 2: Tự biểu tượng 54 que tính, gồm 5 bó que tính đặt cạnh 4 que tính và 2 bó que tính đặt cạnh 3 que tính dẫn đến phép trừ  $57 - 23 = 34$  và qua đó hình thành quy tắc trừ các số có hai chữ số;

– Trong sách giáo khoa Toán 4: đưa vào quy tắc thực hành phép cộng và phép trừ đã học giới thiệu cho học sinh quy tắc thực hành phép cộng và phép trừ các số có nhiều chữ số.

...

##### 3.4.2. Phép nhân và phép chia trong tập số tự nhiên ở Tiểu học

Trong chương trình tiểu học, phép nhân và chia số tự nhiên được trình bày trong môn Toán từ lớp 2 đến hết học kì I của lớp 4 theo bốn giai đoạn:

###### a) Phép nhân:

- Dùng các biểu tượng kết hợp với phép cộng dẫn đến ý nghĩa của phép nhân;
- Xây dựng các bảng nhân lầm cơ sở để mở rộng phép nhân trong các vòng số lớn hơn;
- Xây dựng các quy tắc thực hành phép nhân;
- Mở rộng khái niệm phép nhân để được khái niệm đầy tính, biểu thức.

Trong sách giáo khoa Toán 2: Từ biểu tượng năm cặp chấm tròn gắn với đầy tính cộng:  $2 + 2 + 2 + 2 + 2 = 10$  ta dẫn đến phép nhân  $2 \times 5 = 10$ . Từ đó hình thành ý nghĩa của phép nhân.

Bảng nhân 2 được hình thành dựa trên các biểu tượng kết hợp với ý nghĩa của phép nhân. Chẳng hạn:

– Trong sách giáo khoa Toán 2: Từ biểu tượng các tấm bia có hai chấm tròn ta xây dựng bảng nhân 2;

– Trong sách giáo khoa Toán 3: Từ biểu tượng các tấm bia có chín chấm tròn ta xây dựng bảng nhân 9;

Trong sách giáo khoa Toán 3 và Toán 4 dẫn hình thành cho học sinh quy tắc thực hành phép nhân các số có hai, ba chữ số dựa trên các bảng nhân đã có.

Lần lượt từ phép nhân (ngoài bảng) với số có một chữ số đến phép nhân với số có hai, ba và nhiều chữ số.

###### b) Phép chia:

- Dùng các biểu tượng kết hợp với phép nhân dẫn đến ý nghĩa của phép chia;

– Xây dựng các bảng chia lầm cơ sở để mở rộng phép chia trong các vòng số lớn hơn;

- Xây dựng các quy tắc thực hành phép chia;

- Mở rộng khái niệm phép chia để được khái niệm đầy tính, biểu thức.

Trong sách giáo khoa Toán 2: Tứ biểu tượng 6 ô vuông chia thành hai phần bằng nhau ta dẫn đến phép chia:  $6:2=3$ ; để tìm số ô trong mỗi phần và dẫn đến phép chia:

$$6:3=2 \text{ để tìm số phần khi biết mỗi phần có } 3 \text{ ô.}$$

Bằng chia được hình thành dựa trên các biểu tượng kết hợp với phép nhân. Chẳng hạn:

- Trong sách giáo khoa Toán 2: Tứ biểu tượng các tấm bia có hai chấm tròn và phép nhân ta xây dựng bảng chia 2;

- Trong sách giáo khoa Toán 3: Tứ biểu tượng các tấm bia có chín chấm tròn và phép nhân ta xây dựng bảng chia 9;

Trong sách giáo khoa Toán 4 và Toán 4 dân hình thành cho học sinh quy tắc thực hành phép chia cho số có hai, ba chữ số dựa trên các bảng nhân và bảng chia đã có.

Làm luật từ phép chia (người bảng) cho số có một chữ số đến phép chia cho số có hai, ba và nhiều chữ số.

###### 3.4.3. Giới thiệu thành phần các phép tính

Trong chương trình môn Toán lớp 2, ta lần lượt giới thiệu các thành phần của mỗi phép tính cộng, trừ, nhân, chia:

![](6b09b11992389190c93c33a3e80d6fa9_img.jpg)

| 35      | 24      | 59   | 35 | → Số hạng |
|---------|---------|------|----|-----------|
| ↓       | ↓       | ↓    | 24 | → Số hạng |
| Số hạng | Số hạng | Tổng | 59 | → Tổng    |

Chú ý:  $35 + 24$  cùng gọi là tổng

![](99acc13de9c992bf42e0fcdddf0b09d3_img.jpg)

| 59        | 35     | 24   | 59 | → Số bị trừ |
|-----------|--------|------|----|-------------|
| ↓         | ↓      | ↓    | 35 | → Số trừ    |
| Số bị trừ | Số trừ | Hiệu | 24 | → Hiệu      |

Chú ý:  $59 - 35$  cùng gọi là hiệu

![](04c52bd4e8f924f176fa4d9dcc138e85_img.jpg)

| 2       | 5       | 10   | 2  | → Thừa số |
|---------|---------|------|----|-----------|
| ↓       | ↓       | ↓    | 5  | → Thừa số |
| Thừa số | Thừa số | Tích | 10 | → Tích    |

Chú ý:  $2 \times 5$  cùng gọi là tích

![](3102c32204f998dba666e1e915d5babf_img.jpg)

Diagram illustrating the relationship between three quantities: Số bị chia (Dividend), Số chia (Divisor), and Thương (Quotient). The diagram shows the numbers 6, 2, and 3 associated with these quantities, suggesting the equation  $6 \div 2 = 3$ .

Chú ý:  $6 : 2$  cũng gọi là thương

##### 3.4.4. Tính chất của các phép tính trong tập số nguyên

Trong chương trình môn Toán tiểu học, từ lớp 1, khi dạy mỗi phép tính ta chú ý giới thiệu các tính chất của phép tính đó (giao hoán, kết hợp, tính chất của số 0, tính chất của số 1,...) như những hiện tượng riêng lẻ, đến lớp 4 sách giáo khoa tổng kết mỗi tính chất đó thành các quy tắc: **tính chất giao hoán**, **tính chất kết hợp**, quy tắc nhân một số với một tổng hoặc một hiệu, quy tắc chia một tổng (hoặc một hiệu hoặc một tích hoặc một thương) cho một số, tính chất của số 0, số 1, ... Chẳng hạn:

- Khi dạy phép cộng trong bảng, cho học sinh nhận xét:

$$2 + 3 = 3 + 2 (= 5); 3 + 6 = 6 + 3 (= 9).$$

- Khi dạy phép cộng các số có hai, ba và nhiều chữ số, cho học sinh nhận xét:

| a     | 20             | 350               | 1208                 |
|-------|----------------|-------------------|----------------------|
| b     | 30             | 250               | 2764                 |
| a + b | $20 + 30 = 50$ | $350 + 250 = 600$ | $1208 + 2764 = 3972$ |
| b + a | $30 + 20 = 50$ | $250 + 350 = 600$ | $2764 + 1208 = 3972$ |

Từ đó rút ra tính chất giao hoán của phép cộng: **Khi đổi chỗ các số hạng trong một tổng thì tổng không thay đổi.**

Cũng tương tự ta giới thiệu tính chất giao hoán của phép nhân bằng cách cho học sinh nhận xét:

| a  | b  | c  | $(a + b) + c$          | $a + (b + c)$          |
|----|----|----|------------------------|------------------------|
| 5  | 4  | 6  | $(5 + 4) + 6 = 15$     | $5 + (4 + 6) = 15$     |
| 35 | 15 | 20 | $(35 + 15) + 20 = 70$  | $35 + (15 + 20) = 70$  |
| 28 | 49 | 51 | $(28 + 49) + 51 = 128$ | $28 + (49 + 51) = 128$ |

Từ đó rút ra tính chất kết hợp của phép cộng: **Khi cộng một tổng với một số ta có thể cộng số thứ nhất với tổng của hai số còn lại.**

Tương tự ta giới thiệu tính chất kết hợp của phép nhân.

- Trong sách giáo khoa Toán 2, từ các hiện tượng:

$$1 \times 2 = 1 + 1 = 2$$

$$1 \times 3 = 1 + 1 + 1 = 3$$

$$1 \times 4 = 1 + 1 + 1 + 1 = 4$$

ta rút ra tính chất: 1 nhân với số nào cũng bằng chính nó.

Tương tự ta giới thiệu các tính chất còn lại của số 1 và số 0.

– Trong sách giáo khoa Toán 4, từ nhận xét:

$$4 \times (3 + 5) = 4 \times 8 = 32$$

$$4 \times 3 + 4 \times 5 = 12 + 20 = 32$$

ta rút ra quy tắc: Khi nhân một số với một tổng, ta có thể nhân số đó với từng số hạng của tổng rồi cộng các kết quả lại.

Tương tự ta giới thiệu các tính chất còn lại.

#### 4. Lí thuyết chia hết trong tập số tự nhiên và các bài toán về chia hết trong tập số tự nhiên ở Tiểu học

##### 4.1. Ước chung lớn nhất

##### 4.1.1. Định nghĩa

Cho a và b là các số tự nhiên, trong đó b khác 0. Ta nói rằng:

a) b là ước của a nếu a chia hết cho b.

Nếu b là ước của a thì ta còn nói a là bội của b.

b) Số tự nhiên d là ước chung của a và b, nếu d đồng thời là ước của a và của b.

Từ định nghĩa ta dễ dàng suy ra:

a) Tập  $U(a)$  các ước của a luôn khác rỗng và bị chặn bởi a, vì rõ ràng  $1 \in U(a)$ .

b) Tập  $UC(a; b) = U(a) \cap U(b)$  các ước chung của a và b luôn khác rỗng và bị chặn trên.

Ví dụ 4.20.

$$U(12) = \{1; 2; 3; 4; 6; 12\}$$

$$UC(12; 18) = \{1; 2; 3; 6\}$$

**Định nghĩa 4.16.** Cho a và b là hai số tự nhiên, trong đó ít nhất một số khác 0. Ta gọi số d lớn nhất trong số các ước chung của hai số a, b là ước chung lớn nhất của chúng. Ta ký hiệu là  $d = (a; b)$  (hay  $d = UCLN(a; b)$ ).

**Nhận xét.** Rõ ràng với hai số tự nhiên không cùng bằng 0 luôn tồn tại duy nhất ước chung lớn nhất.

$$\text{Ví dụ 4.21.} (12; 18) = 6; (15; 60) = 15; (8; 15) = 1.$$

**Chú ý:** Trong tự ta định nghĩa: Ước chung lớn nhất của  $n$  số tự nhiên không cùng bằng 0 là số lớn nhất trong số các ước chung của  $n$  số đó.

$$\text{Ví dụ 4.22.} (12; 18; 42) = 6; (8; 24; 72) = 8; (18; 12; 25) = 1.$$

##### 4.1.2. Tính chất của ước chung lớn nhất

**Định lí 4.12.** (Về tính chất của ước chung lớn nhất)

(i) Nếu  $a$  chia hết cho  $b$  thì  $(a; b) = b$ ;  
(ii) Nếu  $a : b = q$  (đư  $r$ ) thì  $(a; b) = (b; r)$ .

*Chứng minh.*

(i) Tự chứng minh.

(ii) Ta chứng minh  $UC(a; b) = UC(b; r)$ .

Thật vậy, nếu  $m$  là ước chung của  $a$  và  $b$  thì  $m$  cũng là ước của  $r = a - bq$ . Suy ra  $m$  là ước chung của  $b$  và  $r$ .

Đảo lại, giả sử  $m$  là ước chung của  $b$  và  $r$ . Vậy  $m$  cũng là ước của  $a = bq + r$ .

Suy ra  $m$  là ước chung của  $a$  và  $b$ . Ta có điều phải chứng minh.

**Định lí 4.13.** (Về thuật toán  $O$ -co-lit)

Muốn tìm ước chung lớn nhất của hai số tự nhiên ta làm như sau:

a) Lấy số lớn chia cho số nhỏ. Nếu phép chia không dư thì số nhỏ sẽ là ước chung lớn nhất của hai số đã cho;

b) Nếu phép chia còn dư thì ta lại lấy số nhỏ chia cho số dư như trên và cứ tiếp tục như thế cho đến khi phép chia không dư thì dừng lại. Số chia cuối cùng trong phép chia không dư đó sẽ là ước chung lớn nhất của hai số đã cho.

*Chứng minh.*

Giả sử  $a$  và  $b$  là hai số tự nhiên. Nếu  $a$  chia hết cho  $b$  thì theo Định lí 4.12:  $b = (a; b)$ .

Trường hợp  $a$  không chia hết cho  $b$ , giả sử  $a = bq_1 + r_1$ . Ta thực hiện liên tiếp các phép chia:

$$b = r_1 q_2 + r_2$$

$$r_1 = r_2 q_3 + r_3$$

...

Sau một số bước (nhiều nhất là b bước) thì phép chia sẽ không còn dư:

$$r_{n-1} = r_n q_{n+1}$$

$$\text{Vì } r_1 > r_2 > r_3 > \dots > r_{n-1} > r_n$$

$$\text{Theo Định lý 4.12 thì } (a; b) = (b; r_1) = (r_1; r_2) = \dots = (r_{n-1}; r_n) = r_n$$

Ví dụ 4.23. Dùng thuật toán O-co-lit tìm ước chung lớn nhất của 21 và 77.

Ta thực hiện liên tiếp các phép chia:

$$77 : 21 = 3 \text{ (du 14);}$$

$$21 : 14 = 1 \text{ (du 7);}$$

$$14 : 7 = 2.$$

$$\text{Vậy } (21; 77) = 7.$$

**Định lý 4.14.** (Tính chất của ước chung lớn nhất)

(i)  $\overline{d} = (a; b)$ , điều kiện cần và đủ là  $d$  là ước chung của  $a$ ,  $b$  và  $d$  chia hết cho mọi ước chung của  $a$ ,  $b$ :

$$\text{(ii) } (ma; mb) = m(a; b) \text{ với mọi số tự nhiên } m \text{ khác } 0;$$

$$\text{(iii) } \left( \frac{a}{m}; \frac{b}{m} \right) = \frac{1}{m}(a; b) \text{ với mọi số tự nhiên } m \text{ là ước chung của } a \text{ và } b.$$

**Chứng minh.**

$$\text{(i) Điều kiện đủ: Rõ ràng.}$$

**Điều kiện cần:** Suy ra từ chứng minh thuật toán O-co-lit.

(ii) Nhận cả hai về của mỗi đẳng thức trong chứng minh thuật toán O-co-lit ta được thuật toán O-co-lit đối với ma và mb.

$$\text{Vậy } (ma; mb) = m r_n = m(a; b).$$

$$\text{(iii) Ta có } (a; b) = \left( m \cdot \frac{1}{m} a; m \cdot \frac{1}{m} b \right) = m \left( \frac{1}{m} a; \frac{1}{m} b \right). \text{ Từ đây suy ra điều}$$

phải chứng minh.

##### 4.2. Bội chung nhỏ nhất

##### 4.2.1. Định nghĩa

Cho  $a$  và  $b$  là các số tự nhiên, trong đó  $b$  khác 0. Ta nói rằng số tự nhiên  $m$  là **bội chung của  $a$  và  $b$**  nếu  $m$  đồng thời là bội của  $a$  và của  $b$ .

Từ định nghĩa ta dễ dàng suy ra:

$$\text{a) Tập } B(a) \text{ các bội của } a \text{ gồm các số tự nhiên } d \text{ sao cho } d \text{ là bội của } a.$$

b) Tập  $BC(a; b) = B(a) \cap B(b)$  các bội chung của  $a$  và  $b$  là một tập vô hạn, vì nó chứa các số dạng  $nb$ , với  $n$  là số tự nhiên.

Ví dụ 4.24.  $B(12) = \{0; 12; 24; 36; 48; \dots\}$ .

$BC(12; 8) = \{0; 24; 48; \dots\}$ .

**Dịnh nghĩa 4.17.** Cho a và b là hai số tự nhiên đều khác 0. Ta gọi số  $c$  nhỏ nhất khác 0 trong số các bội chung của hai số  $a$ , b là **bội chung nhỏ nhất** của chúng. Ta ký hiệu là

$$c = [a; b] \text{ (hay } c = BCNN(a; b)\text{)}$$

**Nhận xét.** Rõ ràng với hai số tự nhiên đều khác 0 luôn tồn tại duy nhất bội chung nhỏ nhất.

$$Ví dụ 4.25. [12; 8] = 24; [15; 60] = 60; [8; 15] = 120.$$

**Chú ý:** Tương tự ta định nghĩa: **Bội chung nhỏ nhất của n số tự nhiên đều khác 0** là số nhỏ nhất khác 0 trong số các bội chung của n số đó.

$$Ví dụ 4.26. [12; 8; 20] = 120; [8; 24; 72] = 72; [18; 12; 25] = 900.$$

**Nhận xét.** Từ định nghĩa ta dễ dàng suy ra: Nếu  $a > 0$  và  $a$  chia hết cho b thì  $[a; b] = a$ .

#### 4.3. Số nguyên tố

##### 4.3.1. Định nghĩa

Cho p là số tự nhiên lớn hơn 1. Ta gọi p là **số nguyên tố** nếu p chỉ chia hết cho 1 và chính nó.

Tập tất cả các số nguyên tố ta ký hiệu là P.

Số tự nhiên a lớn hơn 1 không phải là số nguyên tố ta gọi là **hợp số**.

Tập tất cả các hợp số ta ký hiệu là H. Như vậy:

$$N = P \cup H \cup \{0, 1\}.$$

Chẳng hạn, 3, 5, 7, 11, 17, ... là các số nguyên tố và 4, 12, 15, 28, ... là các hợp số. Hai số 0 và 1 không phải là số nguyên tố và cũng không phải là hợp số.

##### 4.3.2. Tính chất của số nguyên tố

###### Định lý 4.15.

1. Ước nhỏ nhất khác 1 của một số tự nhiên lớn hơn 1 là một số nguyên tố.
2. Tập P tất cả các số nguyên tố là vô hạn.
3. Giả sử a là số tự nhiên. Nếu mọi ước khác 1 của a đều lớn hơn  $\sqrt{a}$  thì a là số nguyên tố, hay nói cách khác: Nếu a là hợp số thì nó có một ước khác 1 và không vượt quá  $\sqrt{a}$ .

###### Chứng minh.

(i) Giả sử  $p$  là ước nhỏ nhất khác 1 của  $a$  nhưng  $p$  là hợp số. Theo định nghĩa sẽ tồn tại  $q$ ,  $s$  sao cho  $p = qs$ , trong đó  $1 < q < p$ . Vì  $a$  chia hết cho  $p$  và  $p$  chia hết cho  $q$  nên  $a$  chia hết cho  $q$ . Vậy  $q$  là ước khác 1 của  $a$ . Điều này vô lý, vì  $p$  là ước nhỏ nhất khác 1 của  $a$ .

(ii) Giả sử tập  $P$  hữu hạn,  $P = \{p_1, p_2, \dots, p_n\}$ . Đặt  $p = p_1 p_2 \dots p_n + 1$ . Nếu  $p$  là hợp số thì  $p$  có một ước nguyên tố  $q$  (là ước nhỏ nhất khác 1 của  $p$ ). Vì tập  $P$  hữu hạn nên  $q = p_i$ , với  $1 \le i \le n$ . Suy ra  $q$  chia hết  $p - p_1 p_2 \dots p_n = 1$ . Điều này vô lý. Vậy  $p$  là số nguyên tố mà  $p \notin P$ . Suy ra tập  $P$  là vô hạn.

(iii) Giả sử  $a$  là hợp số lớn hơn 1. Vậy ước nhỏ nhất khác 1 của  $a$  là số nguyên tố, ta kí hiệu là  $p$ . Ta có  $a = p \cdot q$ . Vì  $p$  là ước nhỏ nhất của  $a$  nên  $p \le q$  hay  $p^2 \le pq = a$  hay  $p \le \sqrt{a}$ . Ta có điều phải chứng minh.

**Chú ý:** Tính chất (iii) trong định lý trên cho ta thuật toán để kiểm tra một số tự nhiên  $a$  có phải là số nguyên tố hay không:

a) Tim các số nguyên tố không vượt quá  $\sqrt{a}$ .

b) Lần lượt kiểm tra mỗi số nguyên tố đó có phải là ước của  $a$  hay không, nếu tất cả các số nguyên tố đó đều không phải là ước của  $a$  thì  $a$  là số nguyên tố.

Vận dụng thuật toán trên đây ta thiết lập bảng các số nguyên tố nhỏ hơn một số tự nhiên  $n$  cho trước.

Chẳng hạn, lập bảng các số nguyên tố không vượt quá 100:

| 1 /  | 2    | 3    | 4 /  | 5    | 6 /  | 7    | 8 /  | 9 /  | 10 /  |
|------|------|------|------|------|------|------|------|------|-------|
| 11   | 12 / | 13   | 14 / | 15 / | 16 / | 17   | 18 / | 19   | 20 /  |
| 21 / | 22 / | 23   | 24 / | 25 / | 26 / | 27 / | 28 / | 29   | 30 /  |
| 31   | 32 / | 33 / | 34 / | 35 / | 36 / | 37   | 38 / | 39 / | 40 /  |
| 41   | 42 / | 43   | 44 / | 45 / | 46 / | 47   | 48 / | 49 / | 50 /  |
| 51 / | 52 / | 53   | 54 / | 55 / | 56 / | 57 / | 58 / | 59   | 60 /  |
| 61   | 62 / | 63 / | 64 / | 65 / | 66 / | 67 / | 68 / | 69 / | 70 /  |
| 71   | 72 / | 73   | 74 / | 75 / | 76 / | 77 / | 78 / | 79   | 80 /  |
| 81 / | 82 / | 83   | 84 / | 85 / | 86 / | 87 / | 88 / | 89   | 90 /  |
| 91 / | 92 / | 93 / | 94 / | 95 / | 96 / | 97   | 98 / | 99 / | 100 / |

Cách làm như sau:

1) Các số nguyên tố nhỏ hơn  $\sqrt{100}$  là 2, 3, 5, 7.

2) Lần lượt gạch bỏ các số trong bảng là bội của 2, 3, 5, 7.

3) Các số còn lại không bị gạch sẽ là các số nguyên tố nhỏ hơn 100!

Bảng số nguyên tố trên đây ta gọi là *sàng O-ra-to-so-ten*.

##### 4.3.3. Số nguyên tố cùng nhau và số nguyên tố *sánh đôi*

**Định nghĩa 4.18.** Cho a và b là hai số *tự nhiên*. Ta nói rằng a và b là hai số *nguyên tố cùng nhau nếu* (a; b) = 1.

Ta nói  $a_1, a_2, \dots, a_n$  là các số *nguyên tố cùng nhau*; 24 và 35 là hai số nguyên tố cùng nhau.

**Ví dụ 4.27.** 8 và 15 là hai số *nguyên tố cùng nhau*; 24 và 35 là hai số *nguyên tố cùng nhau*.

12, 65, 77, 437 là các số *nguyên tố cùng nhau*.

##### 4.3.4. Tính chất của ước chung lớn nhất và bội chung nhỏ nhất

**Định lý 4.16.** (Về tính chất của ước chung lớn nhất)

(i) Nếu a và c nguyên tố cùng nhau thì (ab; c) = (b; c).  
(ii) Nếu ab chia hết cho c, trong đó a và c là hai số *nguyên tố cùng nhau* thì b chia hết cho c.

(iii) Nếu a đồng thời chia hết cho b và c, trong đó b và c là hai số *nguyên tố cùng nhau* thì a chia hết cho tích của b và c.

(iv) Giả sử ước chung lớn nhất của a và b bằng d. Khi đó tồn tại cặp số tự nhiên m và n sao cho  $a = dm$ ;  $b = dn$ , trong đó m và n là hai số *nguyên tố cùng nhau*.

*Chứng minh.*

(i) Giả sử  $d = (ab; c)$  và  $d' = (b; c)$ . Ta có:

- d là ước chung của ab và c nên d cũng là ước chung của ab và bc. Suy ra d là ước của (ab; bc) = b(a; c) = b. Vậy d là ước chung của b và c. Suy ra d là ước của (b; c) = d' (1).

- d' là ước chung của b và c nên d' cũng là ước chung của ab và c nên d' là ước của (ab; c) = d (2).

Từ (1) và (2) suy ra  $d = d'$ .

(ii) Giả sử ab chia hết cho c. Suy ra (ab; c) = c. Mật khác, theo (i) ta có (b; c) = (ab; c) = c. Suy ra b chia hết cho c. Ta có điều phải chứng minh.

(iii) Tự chứng minh.

(iv) Giá sử  $(a; b) = d$ . Suy ra tồn tại số tự nhiên  $m$ ,  $n$  sao cho  $a = dm$ ,  $b = dn$ . Nếu  $m$  và  $n$  không nguyên tố cùng nhau thì tồn tại  $d'$  khác 1 sao cho  $m = d'p$  và  $n = d'q$ .

Thay vào ta được  $a = dd'p$  và  $b = dd'q$ . Điều này trái với giả thiết  $d$  là ước chung lớn nhất của  $a$  và  $b$ .

Ví dụ 4.28. Chứng minh rằng tích của ba số tự nhiên liên tiếp chia hết cho 6.

**Giải:** Giá sử  $a$  là một số tự nhiên. Đặt  $T = a(a+1)(a+2)$ . Ta chứng minh  $T$  chia hết cho 6.

Thật vậy, rõ ràng là  $T$  chia hết cho 2, vì trong hai số tự nhiên liên tiếp phải có một số chẵn (1).

- Nếu  $a$  chia hết cho 3 thì  $T$  chia hết cho 3;

- Nếu  $a$  chia cho 3 dư 1 thì  $a+2$  chia hết cho 3 nên  $T$  chia hết cho 3;

- Nếu  $a$  chia cho 3 dư 2 thì  $a+1$  chia hết cho 3 nên  $T$  chia hết cho 3.

Từ các kết quả trên ta suy ra  $T$  chia hết cho 3 (2).

Vì 2 và 3 là hai số nguyên tố cùng nhau nên từ (1) và (2) ta suy ra  $T$  chia hết cho 2.3 = 6. Ta có điều phải chứng minh.

Ví dụ 4.29. Tìm nghiệm nguyên dương của hệ phương trình sau:

$$\begin{cases} x+y=120 & (1) \\ (x;y)=15 & (2) \end{cases}$$

**Giải:** Từ (2) ta có  $(x; y) = 15$ . Theo tính chất (iv) suy ra tồn tại hai số tự nhiên  $m$ ,  $n$  sao cho  $a = 15m$  và  $b = 15n$ , trong đó  $(m; n) = 1$ . Thay vào phương trình (1) ta được:

$$15m + 15n = 120 \text{ hay } m + n = 8.$$

Số 8 có thể phân tích thành tổng của 0 và 8; 1 và 7; 2 và 6; 3 và 5; 4 và 4.

Vì  $(m; n) = 1$  nên  $m$  và  $n$  chỉ có thể là 1 và 7 hoặc 3 và 5.

Thay vào ta được nghiệm của hệ đã cho là:

$$\begin{cases} x_1 = 15; & x_2 = 105; & x_3 = 45; & x_4 = 75 \\ y_1 = 105; & y_2 = 15; & y_3 = 75 & y_4 = 45 \end{cases}$$

**Định lý 4.17.** (Về tính chất của bội chung nhỏ nhất)

(i) Với mọi số tự nhiên  $a$ ,  $b$  đều khác 0 ta luôn có:

$$[a;b] = \frac{ab}{(a;b)}$$

(ii) Nếu  $a$  và  $b$  là hai số nguyên tố cùng nhau thì  $[a; b] = ab$ .

(iii) Với mọi số tự nhiên  $m$  khác 0 ta luôn có  $[am; bm] = m[a; b]$ .

Chứng minh.

(i) Giả sử  $d = (a; b)$ . Theo định lý 4.16 tồn tại cặp số tự nhiên  $m, n$  sao cho  $a = dm, b = dn$ , trong đó  $(m; n) = 1$ . Đặt  $u = \frac{ab}{d}$ . Ta chứng minh  $u = [a; b]$ .

Thật vậy, ta có  $u = \frac{dm \cdot dn}{d} = dmn = an = bm$ . Vậy  $u$  là bội chung của  $a$  và  $b$ .

Đảo lại, giả sử  $v$  là bội chung của  $a$  và  $b$  vậy  $v = ak$  và  $ak$  chia hết cho  $b$ . Suy ra  $\frac{ak}{d} \to mk$ ;  $n$ . Vì  $(m; n) = 1$  nên  $k$  chia hết cho  $n$  hay  $k = nq$ . Thay

vào ta được  $v = anq = uq$ . Vậy  $v$  là bội của  $u$ . Ta có điều phải chứng minh.

(ii) Suy ra từ (i).

(iii) Ta có  $[ma; mb] = \frac{ma \cdot mb}{(ma; mb)} = \frac{ma \cdot mb}{m(a; b)} = \frac{ab}{(a; b)} = [a; b]$ .

**Chú ý:** Tự định lý trên đây ta dễ dàng suy ra: Điều kiện cần và đủ để  $m = [a; b]$  là  $m$  là bội chung của  $a$  và  $b$  và  $m$  chia hết mọi bội chung của hai số đó.

Ta thừa nhận mà không chứng minh định lý sau đây:

**Dịnh lý 4.18.**

Giả sử  $a, b, c$  là ba số tự nhiên, trong đó:

$$a = p_1^{a_1} p_2^{a_2} \dots p_n^{a_n};$$

$$b = p_1^{b_1} p_2^{b_2} \dots p_n^{b_n};$$

$$c = p_1^{c_1} p_2^{c_2} \dots p_n^{c_n},$$

trong đó  $p_1, p_2, \dots, p_n$  là các số nguyên tố đôi một khác nhau,  $\alpha_i, \beta_j, \gamma_k$  là các số tự nhiên. Khi đó:

$$a) (a; b; c) = p_1^{m_1} p_2^{m_2} \dots p_n^{m_n};$$

$$b) [a; b; c] = p_1^{k_1} p_2^{k_2} \dots p_n^{k_n},$$

trong đó  $m_i = \min \{\alpha_i; \beta_i; \gamma_i\}$ ;  $k_i = \max \{\alpha_i; \beta_i; \gamma_i\}$  với  $i, j = 1, 2, \dots, n$ .

Dịnh lý trên có thể phát biểu thành lời dưới dạng một quy tắc như sau: Muốn tìm UCLN hoặc BCNN của hai hay nhiều số tự nhiên ta làm như sau:

a) Phân tích chung thành tích của các thừa số nguyên tố đôi một khác nhau;  
b) Ước chung lớn nhất của các số đã cho bằng tích của các thừa số chung với số mũ nhỏ nhất;  
c) Bội chung nhỏ nhất của các số đã cho bằng tích của các thừa số chung và riêng với số mũ lớn nhất.

Ví dụ 4.30. Ước chung lớn nhất của hai số tự nhiên bằng 7, bội chung nhỏ nhất của chúng bằng 105. Tìm hai số đó.

**Giải:** Gọi hai số cần tìm là  $a$  và  $b$ . Theo đề bài ta có  $(a; b) = 7$  và  $[a; b] = 105$ . Vì  $(a; b) = 7$  theo Định lý 4.16 tồn tại các số tự nhiên  $m, n$  sao cho  $a = 7m$  và  $b = 7n$ , trong đó  $m$  và  $n$  là hai số nguyên tố cùng nhau. Theo định lý 4.17 ta có:

$$[a; b] = \frac{a \cdot b}{(a; b)}$$

$$\text{Thay vào ta được: } 105 = \frac{7m \cdot 7n}{7} \Rightarrow m \cdot n = 15.$$

Số 15 có thể phân tích thành tích của 1.15 hoặc 3.5.

Thay vào ta được các cặp số cần tìm là: 7 và 105 hoặc 21 và 35.

Ví dụ 4.31. Cho  $a = 240$ ;  $b = 8820$  và  $c = 7425$ . Tìm ước chung lớn nhất và bội chung nhỏ nhất của ba số đó.

**Giải:** Ta có:

$$240 = 2^4 \cdot 3 \cdot 5; 8820 = 2^2 \cdot 3^2 \cdot 5 \cdot 7^2 \text{ và } 7425 = 3^3 \cdot 5^2 \cdot 11.$$

Áp dụng quy tắc trên ta được:

$$(240; 8820; 7425) = 3 \cdot 5 = 15;$$
$$[240; 8820; 7425] = 2^4 \cdot 3^2 \cdot 5 \cdot 7^2 \cdot 11 = 5821200.$$

#### 4.4. Hệ ghi số cơ số g và hệ thập phân ở Tiểu học

##### 4.4.1. Định nghĩa hệ ghi số cơ số g

**Định lý 4.19.** Cho  $a$  là số tự nhiên lớn hơn 0 và  $g$  là số tự nhiên lớn hơn 1. Khi đó tồn tại các số tự nhiên  $c_0, c_1, c_2, \dots, c_n$  sao cho:

$$a = c_n g^n + c_{n-1} g^{n-1} + c_{n-2} g^{n-2} + \dots + c_1 g + c_0, (*)$$

trong đó  $0 \le c_i \le g-1$ ;  $i = 0, 1, \dots, n$ ;  $c_n \ne 0$ .

Dạng biểu diễn trên đây là duy nhất đối với mỗi cặp số tự nhiên  $a, g$ .

Chứng minh.

Thực hiện liên tiếp các phép chia cho  $g$ , gọi số dư trong mỗi bước chia đó theo thứ tự là  $c_0, c_1, c_2, \dots, c_n$  ta có:

$$a = gq_0 + c_0$$

$$q_0 = gq_1 + c_1$$

$$q_1 = gq_2 + c_2$$

...

$$q_{n-2} = gq_{n-1} + c_{n-1}$$

$$q_{n-1} = g \cdot 0 + c_n$$

trong đó  $0 \le c_i \le g-1$ ;  $c_n \ne 0$ . Lần lượt thay các đẳng thức trên (từ dưới lên) ta được:

$$a = c_n g^n + c_{n-1} g^{n-1} + c_{n-2} g^{n-2} + \dots + c_1 g + c_0.$$

Ta sẽ chứng minh dạng biểu diễn trên đây là duy nhất. Thật vậy, giả sử:

$$a = c_n g^n + c_{n-1} g^{n-1} + c_{n-2} g^{n-2} + \dots + c_1 g + c_0$$

và  $a = b_n g^n + b_{n-1} g^{n-1} + b_{n-2} g^{n-2} + \dots + b_1 g + b_0$ .

Vi  $c_0$  và  $b_0$  đều là số dư trong phép chia  $a$  cho  $g$  nên  $c_0 = b_0$ . Lập luân trong tự ta được các hệ số  $c_i = b_i$  với  $i = 1, 2, \dots, n$ .

Ta có điều phải chứng minh.

**Định nghĩa 4.19.** Giả sử  $a$  và  $g$  là hai số tự nhiên được biểu diễn bởi đẳng thức (\*) trong định lý 4.19. Trong trường hợp này ta viết:

$$a = \overline{c_n c_{n-1} \dots c_1 c_0}$$

| $\Sigma$ | $\Sigma$ | $\Sigma$ | $\Sigma$ | $\Sigma$ | $\Sigma$ | $\Sigma$ |
|----------|----------|----------|----------|----------|----------|----------|
| $\Sigma$ | $\Sigma$ | $\Sigma$ | $\Sigma$ | $\Sigma$ | $\Sigma$ | $\Sigma$ |
| $\Sigma$ | $\Sigma$ | $\Sigma$ | $\Sigma$ | $\Sigma$ | $\Sigma$ | $\Sigma$ |
| $\Sigma$ | $\Sigma$ | $\Sigma$ | $\Sigma$ | $\Sigma$ | $\Sigma$ | $\Sigma$ |
| $\Sigma$ | $\Sigma$ | $\Sigma$ | $\Sigma$ | $\Sigma$ | $\Sigma$ | $\Sigma$ |

Ví dụ 4.32.

$$13 = 1.2^3 + 1.2^2 + 1 = 1.2^3 + 1.2^2 + 0.2 + 1. \text{ Vậy } 13 = \overline{1101_2}.$$

$$54 = 1.7^2 + 5 = 1.7^2 + 0.7 + 5. \text{ Vậy } 54 = \overline{105_7}.$$

$$54 = 4.11 + 10. \text{ Đặt } \alpha = 10 \text{ ta có } 54 = \overline{4\alpha_{11}}.$$

$$503 = 3.12^2 + 5.12 + 11. \text{ Đặt } \beta = 11 \text{ ta có } 503 = \overline{35\beta_{12}}.$$

**Chú ý:**

1) Để biểu diễn một số tự nhiên  $a$  trong hệ  $g$ -phan ta phải dùng các chữ số từ 0 đến  $g-1$ .

2) Khi cơ số  $g$  lớn hơn 10 thì 10 chữ số cơ bản từ 0 đến 9 không đủ để biểu diễn, vì vậy ta phải bổ sung thêm các kí tự mới (ngoài 10 chữ số cơ bản) đó là:

$$\alpha = 10; \beta = 11; \delta = 12; \dots$$

3) Để biểu diễn số tự nhiên  $a$  trong hệ  $g$ -phan ta thực hiện liên tiếp các phép chia cho  $g$  cho đến khi được thương bằng 0 thì dừng lại. Số dư trong các phép chia đó sẽ là các chữ số cơ biểu diễn  $a$  trong hệ  $g$ -phan.

##### 4.4.2. So sánh các số trong hệ ghi số cơ số $g$

Khi thực hành so sánh các số trong hệ  $g$ -phan, ta vận dụng quy tắc dưới đây:

$$\text{Giả sử } a = c_n c_{n-1} c_{n-2} \dots c_1 c_0 \quad \text{và } b = b_m b_{m-1} b_{m-2} \dots b_1 b_0.$$

a) Nếu  $n < m$  thì  $a < b$ ;

b) Nếu  $n = m$  thì  $a$  và  $b$  có cùng số chữ số. Trong trường hợp này ta lần lượt so sánh các chữ số cùng hàng từ trái sang phải. Số nào có chữ số đầu tiên lớn hơn thì số đó lớn hơn.

$$\text{Ví dụ 4.33. } \overline{792_g} < \overline{1032_g}; \quad \overline{2411_g} > \overline{414_g};$$

$$\overline{2108_g} < \overline{2703_g}; \quad \overline{31105_g} > \overline{31015_g}.$$

##### 4.4.3. Các phép toán trong hệ ghi số cơ số $g$

a) Phép cộng và trừ

$$\text{Ví dụ 4.34. Hãy lập bảng cộng trong hệ cơ số } g = 7.$$

| + | 0 | 1  | 2  | 3  | 4  | 5  | 6  |
|---|---|----|----|----|----|----|----|
| 0 | 0 | 1  | 2  | 3  | 4  | 5  | 6  |
| 1 | 1 | 2  | 3  | 4  | 5  | 6  | 10 |
| 2 | 2 | 3  | 4  | 5  | 6  | 10 | 11 |
| 3 | 3 | 4  | 5  | 6  | 10 | 11 | 12 |
| 4 | 4 | 5  | 6  | 10 | 11 | 12 | 13 |
| 5 | 5 | 6  | 10 | 11 | 12 | 13 | 14 |
| 6 | 6 | 10 | 11 | 12 | 13 | 14 | 15 |

Cách diễn như sau: chẳng hạn:

+ Ta muốn điền vào ô có hàng bằng 2, cột bằng 3: ta lấy  $2 + 3 = 5 < 7$ .  
Vậy ta điền 5 vào ô đó;

+ Ta muốn điền vào ô có hàng bằng 6, cột bằng 5: ta lấy  $6 + 5 = 11 > 7$ . Ta lấy 11 chia cho 7 được thương bằng 1 dư 4. Kết quả sẽ là 14. Vậy ta điền 14 vào ô đó.

Ta có quy tắc sau:

Muốn điền vào một ô bất kì trong bảng cộng của hệ g-phân, ta lấy số chỉ hàng cộng với số chỉ cột của ô đó: nếu kết quả nhỏ hơn cơ số thì viết luôn, nếu kết quả từ cơ số lớn, ta chia cho cơ số rồi đọc từ thương đến số dư.

$$\text{Ví dụ 4.35. Tính: } \overline{5476_8} + \overline{4725_8}$$

Trước hết ta viết lại phép tính theo cột dọc:

$$\begin{array}{r} 5476_8 \\ + 4725_8 \\ \hline \end{array}$$

$$\begin{array}{r} 4725 \\ + 12423 \\ \hline \end{array}$$

$$\text{Vậy: } \overline{5476_8} + \overline{4725_8} = \overline{12423_8}$$

Cách làm như sau:

+ Cộng lần lượt từ phải sang trái;

$$+ 6 + 5 = 11. \text{ Lấy 11 chia cho 8 được thương bằng 1, dư 3. Ta viết 3 nhỏ 1.}$$

$$+ 7 + 2 = 9, \text{ nhỏ 1 bằng 10. Lấy 10 chia cho 8 được thương bằng 1 dư 2.}$$

Ta viết 2 nhỏ 1.

+ Cử tiếp tục như thế...

$$\text{Ví dụ 4.36. Tính: } \overline{2031_9} - \overline{745_9}$$

Trước hết ta viết lại phép tính theo cột dọc:

$$\begin{array}{r} 2031_9 \\ - 745_9 \\ \hline \end{array}$$

$$\begin{array}{r} 2031_9 \\ - 745_9 \\ \hline \end{array}$$

$$\text{Vậy: } \overline{2031_9} - \overline{745_9} = \overline{1175_9}$$

Cách làm như sau:

+ Trừ lần lượt từ phải sang trái;

$$+ 1 \text{ không trừ được 5, mượn } 1 \text{ (lấy } 1 + 9 = 10 \text{) rồi lấy } 10 \text{ trừ } 5 \text{ bằng } 5, \text{ viết } 5 \text{ nhỏ } 1.$$

$$+ 4 \text{ nhỏ } 1 \text{ bằng } 5; 3 \text{ không trừ được } 5, \text{ mượn } 1 \text{ (} 3 + 9 = 12 \text{) rồi lấy } 12 \text{ trừ } 5 \text{ bằng } 7, \text{ viết } 7 \text{ nhỏ } 1.$$

+ Cử tiếp tục như thế...

b) Phép nhân và chia

Ví dụ 4.37. Hãy lập bảng nhân trong hệ cơ số  $g = 6$ .

| $\times$ | 1 | 2  | 3  | 4  | 5  |
|----------|---|----|----|----|----|
| 1        | 1 | 2  | 3  | 4  | 5  |
| 2        | 2 | 4  | 10 | 12 | 14 |
| 3        | 3 | 10 | 13 | 20 | 23 |
| 4        | 4 | 12 | 20 | 24 | 32 |
| 5        | 5 | 14 | 23 | 32 | 41 |

Cách diễn nhr sau: chẵng hạn:

+ Ta muốn điền vào ô có hàng bằng 3, cột bằng 1: ta lấy  $3 \times 1 = 3 < 6$ .  
Vậy ta điền 3 vào ô đó;

+ Ta muốn điền vào ô có hàng bằng 5, cột bằng 4: ta lấy  $5 \times 4 = 20 > 6$ .  
Ta lấy 20 chia cho 6 được thương bằng 3 dư 2. Kết quả sẽ là 32. Vậy ta điền 32 vào ô đó.

Ta có quy tắc sau:

Muốn điền vào một ô bất kì trong bảng nhân của hệ  $g$ -phan, ta lấy số chỉ hàng nhân với số chỉ cột của ô đó; nếu kết quả nhỏ hơn cơ số thì viết luôn, nếu kết quả từ cơ số trở lên, ta chia cho cơ số rồi đọc từ thương đến số dư.

Ví dụ 4.38. Tính:  $435_6 \times 54_6$ .

Trước hết ta viết lại phép tính theo cột dọc:

432 (6)

$\times 54$

3012

3444

41452

Vậy:  $435_6 \times 54_6 = 41452_6$ .

Cách làm như sau:

+ Nhân lần lượt từ phải sang trái;

+ Ở tích riêng thứ nhất:  $4 \times 2 = 8$ . Lấy 8 chia cho 6 được thương bằng 1, dư 2. Ta viết 2 nhớ 1.

+  $4 \times 3 = 12$ , nhớ 1, bằng 13. Lấy 13 chia cho 6 được thương bằng 2 dư 1. Ta viết 1 nhớ 2.

+ Cứ tiếp tục như thế...

Ví dụ 4.39. Tính:  $\overline{14443 : 32_5}$ .

Trước hết ta viết lại phép tính theo cột dọc:

$$\begin{array}{r} 14443 \\ - 114 \\ \hline 304 \\ - 233 \\ \hline 213 \end{array}$$

$$\begin{array}{r} 201 \\ - 12 \\ \hline \end{array}$$

Vậy:  $\overline{14443 : 32_5} = \overline{243_5}$  (du  $\overline{12_5}$ ).

Cách làm như sau:

+ Chia lần lượt từ trái sang phải;

+ Ý làn chia thứ nhất:  $144 : 32$  được thương bằng 2.

$$\text{Lấy } 2_5 \times 32_5 = \overline{114_5}. \text{ Lấy } \overline{144_5} - \overline{114_5} = \overline{30_5}.$$

+ Hạ tiếp 4 ta được  $\overline{304_5}$ , rồi tiếp tục chia như trên.

+ Cứ tiếp tục như thế...

##### 4.4.4. Các phép toán trong hệ nhị số cơ số 5

- Trong môn Toán ở trường tiểu học, học sinh chủ yếu được thực hành (dém, so sánh, tính toán,...) trong hệ cơ số  $g = 10$  hay còn gọi là hệ thập phân.

Trong hệ thập phân: cứ 10 đơn vị của hàng sau có giá trị bằng 1 đơn vị ở hàng liền trước nó.

- Ngoài hệ thập phân, học sinh cũng được làm quen với một số hệ cơ số khác, chẳng hạn:

+ Hệ cơ số  $g = 2$  hay còn gọi là hệ nhị phân, ở Tiểu học thường gọi là tá. Trong hệ nhị phân: cứ 2 đơn vị của hàng sau có giá trị bằng 1 đơn vị ở hàng liền trước nó.

+ Hệ cơ số  $g = 12$  hay còn gọi là hệ thập nhị phân, ở Tiểu học thường gọi là tá. Trong hệ thập nhị phân: cứ 12 đơn vị của hàng sau có giá trị bằng 1 đơn vị ở hàng liền trước nó.

+ Hệ cơ số  $g = 60$  hay còn gọi là hệ lục thập phân. Phép đếm này ta gặp trong phép đo thời gian: 1 giờ = 60 phút; 1 phút = 60 giây. Trong hệ lục thập phân: cứ 60 đơn vị của hàng sau có giá trị bằng 1 đơn vị ở hàng liền trước nó.

- Khi biểu diễn các số tự nhiên trong hệ thập phân ta cần lưu ý:

+ Ta sẽ viết 2047; 672 thay cho  $\overline{2047}_{10}$ ;  $\overline{672}_{10}$ .

+ Khi biểu diễn một số tự nhiên có ít nhất một chữ số chưa xác định ta phải dùng dấu gạch ngang trên số đó. Trong trường hợp này, ta quy ước: mỗi ký tự viết dưới dấu gạch ngang biểu diễn một chữ số từ 0 đến 9, chữ số đầu tiên kể từ bên trái khác 0. Chẳng hạn:  $\overline{abcd}$ ;  $\overline{2a4b}$ ;  $\overline{16a}$ ;

+ Khi đặt phép tính theo cột dọc thì không cần dùng dấu gạch ngang trên số đó, chẳng hạn:

$\overline{abcd}$

$\overline{ba6m}$

##### 4.5. Các dấu hiệu chia hết cho 2, 3, 4, 5, 9, 25 và 11

**Định lí 4.20.** Số tự nhiên a chia hết cho 2 khi và chỉ khi chữ số hàng đơn vị của nó bằng 0, 2, 4, 6 hoặc 8.

*Chứng minh.*

Giả sử  $a = c_n c_{n-1} \dots c_1 c_0$ . Ta có:

$$a = c_n 10^n + c_{n-1} 10^{n-1} + \dots + c_1 10 + c_0 = (c_n 10^n + c_{n-1} 10^{n-2} + \dots + c_1) 10 + c_0.$$

Từ đây suy ra a chia hết cho 2 khi và chỉ khi  $c_0$  chia hết cho 2 hay  $c_0 = 0, 2, 4, 6$  hoặc 8. Ta có điều phải chứng minh.

**Định lí 4.21.** Số tự nhiên a chia hết cho 5 khi và chỉ khi chữ số hàng đơn vị của nó bằng 0 hoặc 5.

*Chứng minh.* Tương tự chứng minh Định lí 4.20.

**Định lí 4.22.** Số tự nhiên a chia hết cho 3 (hoặc 9) khi và chỉ khi tổng các chữ số của nó chia hết cho 3 (hoặc 9).

*Chứng minh.*

Giả sử  $a = c_n c_{n-1} \dots c_1 c_0$ . Ta có:

$$a = c_n 10^n + c_{n-1} 10^{n-1} + \dots + c_1 10 + c_0$$

$$= c_n (9+1)^n + c_{n-1} (9+1)^{n-1} + \dots + c_1 (9+1) + c_0$$

$$= T_n 9 + (c_n + c_{n-1} + \dots + c_1 + c_0)$$

$$= T_n 9 + (c_n + c_{n-1} + \dots + c_1 + c_0)$$

Từ đây suy ra a chia hết cho 3 (hoặc 9) khi và chỉ khi  $c_n + c_{n-1} + \dots + c_1 + c_0$  chia hết cho 3 (hoặc 9) hay tổng các chữ số của a chia hết cho 3 (hoặc 9).

Ta có điều phải chứng minh.

**Dịnh lý 4.23.** Số tự nhiên a chia hết cho 4 (hoặc 25) khi và chỉ khi số tạo bởi hai chữ số tận cùng của nó chia hết cho 4 (hoặc 25).

**Chứng minh.**

Giả sử  $a = c_n c_{n-1} \dots c_1 c_0$ . Ta có:

$$a = c_n 10^n + c_{n-1} 10^{n-1} + \dots + c_1 10 + c_0$$

$$= (c_n 10^{n-2} + c_{n-1} 10^{n-3} + \dots + c_1) 100 + c_1 c_0$$

Từ đây suy ra a chia hết cho 4 (hoặc 25) khi và chỉ khi  $c_1 c_0$  chia hết cho 4 (hoặc 25) hay số tạo bởi hai chữ số tận cùng của a chia hết cho 4 (hoặc 25).

Ta có điều phải chứng minh.

**Dịnh lý 4.24.** Số tự nhiên a chia hết cho 11 khi và chỉ khi hiệu giữa tổng các chữ số hàng chẵn và tổng các chữ số hàng lẻ của nó chia hết cho 11.

**Chứng minh.**

Giả sử  $a = c_n c_{n-1} \dots c_1 c_0$ . Ta có:

$$a = c_n 10^n + c_{n-1} 10^{n-1} + \dots + c_1 10 + c_0$$

$$= c_n (11-1)^n + c_{n-1} (11-1)^{n-1} + \dots + c_1 (11-1) + c_0$$

$$= 11(T_n + (-1)^n c_n + 11T_{n-1} + (-1)^{n-1} c_{n-1} + \dots + 11T_1 - c_1 + c_0)$$

$$= 11(T_n + T_{n-1} + \dots + T_1) + (c_0 + c_2 + c_4 + \dots + c_{2k}) - (c_1 + c_3 + \dots + c_{2k-1}).$$

Từ đây suy ra a chia hết cho 11 khi và chỉ khi hiệu giữa tổng các chữ số hàng chẵn và tổng các chữ số hàng lẻ của nó chia hết cho 11. Ta có điều phải chứng minh.

**Ví dụ 4.40.** Tìm một số tự nhiên n nằm giữa 5000 và 6000 sao cho số đó chia hết cho 6, 9 và 25.

**Giải:** Vì n nằm giữa 5000 và 6000 nên nó có dạng  $n = 5abc$ . Vì n chia hết cho 25 nên  $bc$  chia hết cho 25, mặt khác n chia hết cho 6 nên nó phải là số chẵn. Suy ra  $n = 5a00$  hoặc  $n = 5a50$ .

a) Xét trường hợp  $n = \overline{5a50}$ : vì  $n$  chia hết cho 9 nên  $5 + a + 5 + 0 = a + 10$  chia hết cho 9. Suy ra  $a = 8$ . Thay vào ta được  $n = 5850$ .

b) Xét trường hợp  $n = \overline{5a00}$ : vì  $n$  chia hết cho 9 nên  $5 + a + 0 + 0 = a + 5$  chia hết cho 9. Suy ra  $a = 4$ . Thay vào ta được  $n = 5400$ .

Vì dụ 4.41. Cho số tự nhiên a. Viết các chữ số của a theo thứ tự ngược lại ta được số tự nhiên b lớn gấp 3 lần a. Chứng minh rằng b chia hết cho 9.

**Giải:** Giả sử  $a = \overline{c_1 c_2 \dots c_k}$ . Viết các chữ số của a theo thứ tự ngược lại ta được số tự nhiên  $b = \overline{c_k c_{k-1} \dots c_1} = 3a$  (1).

Từ đây suy ra b chia hết cho 3. Theo dấu hiệu chia hết cho 3 ta suy ra:  $s = c_k + c_{k-1} + \dots + c_2 + c_1$  chia hết cho 3. Như vậy, a cũng có tổng các chữ số chia hết cho 3 nên a chia hết cho 3, viết  $a = 3q$ .

Thay vào (1) ta được  $b = 9q$ . Như vậy b chia hết cho 9. Suy ra tổng các chữ số của b chia hết cho 9. Tổng các chữ số của a cũng chia hết cho 9.

Suy ra a chia hết cho 9. Ta có điều phải chứng minh.

Vì dụ 4.42. Tìm số chẵn có ba chữ số sao cho số đó chia hết cho 5, 9 và 11.

**Giải:** Gọi số cần tìm là  $n = \overline{abc}$ . Vì  $n$  là số chẵn chia hết cho 5 nên  $c = 0$ . Thay vào ta được  $n = \overline{ab0}$ . Vì  $n$  chia hết cho 11 nên  $a - b$  chia hết cho 11. Suy ra  $a = b$ .

Mặt khác  $n$  chia hết cho 9 nên  $a + b + 0 = a + b$  chia hết cho 9. Suy ra  $a + b$  chia có thể bằng 0, 9 hoặc 18.

Từ các kết quả trên đây suy ra  $a = b = 9$ . Thay vào ta được  $n = 990$ .

Vì dụ 4.43. Chứng minh rằng trong 11 số tự nhiên bất kì luôn tồn tại hai số mà hiệu của chúng chia hết cho 2 và 5.

**Giải:** Với 11 số tự nhiên ta có 11 chữ số hàng đơn vị ứng với các số đó. Vì chỉ có 10 chữ số hàng đơn vị khác nhau  $(0, 1, 2, \dots, 9)$  nên phải có 2 trong 11 số đó có cùng chữ số hàng đơn vị. Hiệu của hai số này sẽ là số chẵn chục nên nó chia hết cho cả 2 và 5.

#### 4.6. Các bài toán về chia hết ở Tiểu học

Sách giáo khoa Toán 4 giới thiệu cho học sinh các dấu hiệu chia hết cho 2, 3, 5 và 9. Cụ thể là:

a) Dấu hiệu chia hết cho 2:

- Các số có chữ số tận cùng bằng 0, 2, 4, 6 hoặc 8 thì chia hết cho 2.

- Các số có chữ số tận cùng bằng 1, 3, 5, 7 hoặc 9 thì không chia hết cho 2.

b) Dấu hiệu chia hết cho 5:

- Các số có chữ số tận cùng bằng 0 hoặc 5 thì chia hết cho 5.

- Các số không có chữ số tận cùng bằng 0 và 5 thì không chia hết cho 5.

c) Dấu hiệu chia hết cho 9:

- Các số có tổng các chữ số chia hết cho 9 thì chia hết cho 9.

- Các số có tổng các chữ số không chia hết cho 9 thì không chia hết cho 9.

d) Dấu hiệu chia hết cho 3:

- Các số có tổng các chữ số chia hết cho 3 thì chia hết cho 3.

- Các số có tổng các chữ số không chia hết cho 3 thì không chia hết cho 3.

Ngoài các dấu hiệu nêu trên, để giải các bài toán nâng cao về chia hết ở Tiểu học, ta cần bổ sung một số tính chất. Chẳng hạn:

1) Một số khi chia cho 2 dư 1 thì chữ số hàng đơn vị của nó bằng 1, 3, 5, 7 hoặc 9.

2) Một số khi chia cho 5 dư 1 thì chữ số hàng đơn vị của nó bằng 1 hoặc 6; dư 2 thì chữ số hàng đơn vị của nó bằng 2 hoặc 7; dư 3 thì chữ số hàng đơn vị của nó bằng 3 hoặc 8; dư 4 thì chữ số hàng đơn vị của nó bằng 4 hoặc 9.

3) Số tự nhiên a và tổng các chữ số của nó luôn có cùng số dư khi chia cho 3 (hoặc 9).

4) Hiệu của hai số có cùng số dư khi chia cho k là một số chia hết cho k.

Dưới đây ta minh họa một số ví dụ:

Ví dụ 4.44. Cho sáu chữ số 0, 1, 2, 3, 4, 5. Từ sáu chữ số đó có thể viết được bao nhiêu:

a) Số chẵn có bốn chữ số khác nhau?

b) Số có bốn chữ số khác nhau chia hết cho 5?

c) Số có bốn chữ số khác nhau khi chia cho 5 dư 3?

d) Số lẻ có bốn chữ số chia hết cho 5?

Giải: a) Mỗi số cần tìm có dạng  $abc0$  hoặc  $abc2$ ;  $abc4$  hoặc  $abc6$ .

Ta xét các số thuộc nhóm 1:

- Có 5 cách chọn a;

- Có 4 cách chọn b;

- Có 3 cách chọn c.

Vậy số các số viết được thuộc nhóm 1 là:  $5 \times 4 \times 3 = 60$  (số).

Bây giờ ta xét các số thuộc nhóm 2 và nhóm 3:

- Có 4 cách chọn a;

- Có 4 cách chọn b;

- Có 3 cách chọn c.

Vậy số các số viết được thuộc nhóm 2 và nhóm 3 là:

$$4 \times 4 \times 3 \times 2 = 96 \text{ (số)}.$$

Số các số chẵn có bốn chữ số khác nhau viết được từ sáu chữ số đã cho là:

$$60 + 96 = 156 \text{ (số)}.$$

b) Mỗi số cần tìm có dạng  $\overline{abc0}$  hoặc  $\overline{abc5}$ . Ta xét các số thuộc nhóm 1:

- Có 5 cách chọn a;

- Có 4 cách chọn b;

- Có 3 cách chọn c.

Vậy số các số viết được thuộc nhóm 1 là:  $5 \times 4 \times 3 = 60$  (số).

Bây giờ ta xét các số thuộc nhóm 2:

- Có 4 cách chọn a;

- Có 4 cách chọn b;

- Có 3 cách chọn c.

Vậy số các số viết được thuộc nhóm 2 là:

$$4 \times 4 \times 3 = 48 \text{ (số)}.$$

Số các số có bốn chữ số khác nhau chia hết cho 5 viết được từ sáu chữ số đã cho là:

$$60 + 48 = 108 \text{ (số)}.$$

c) Mỗi số cần tìm có dạng  $\overline{abc3}$ . Ta thấy:

- Có 4 cách chọn a;

- Có 4 cách chọn b;

- Có 3 cách chọn c.

Vậy số các số có bốn chữ số khác nhau khi chia cho 5 dư 3 viết được từ sáu chữ số đã cho là:  $4 \times 4 \times 3 = 48$  (số).

d) Mỗi số cần tìm có dạng  $\overline{abc5}$ . Ta thấy:

- Có 4 cách chọn a;

- Có 5 cách chọn b;

- Có 5 cách chọn c.

Vậy số cách số là có bốn chữ số chia hết cho 5 viết được từ sáu chữ số đã cho là:  $4 \times 5 \times 5 = 100$  (số).

**Vi dụ 4.45.** Thay a và b bởi chữ số thích hợp để được số tự nhiên  $n = \overline{a54b}$  là số nhỏ nhất có bốn chữ số khác nhau chia hết cho 3 và 5.

**Giải:** Vì n chia hết cho 5 nên  $c = 0$  hoặc  $c = 5$ . Vì n có bốn chữ số khác nhau nên  $c = 0$ . Thay vào ta được  $n = \overline{a540}$ . Vì n chia hết cho 3 nên  $a + 5 + 4 + 0 = a + 9$  chia hết cho 3. Suy ra  $a = 0, 3, 6$  hoặc 9. Số nhỏ nhất cần tìm là 3540.

**Vi dụ 4.46.** Hãy viết thêm vào bên trái số 302 một chữ số và bên phải hai chữ số để nhận được số nhỏ nhất có sáu chữ số khác nhau chia hết cho 9.

**Giải:** Gọi chữ số viết thêm vào bên trái là a, hai chữ số viết thêm vào bên phải là b, c. Số cần tìm có dạng  $n = \overline{a302bc}$ . Vì n chia hết cho 5 nên  $c = 0$  hoặc  $c = 5$ . Mặt khác, vì n có sáu chữ số khác nhau nên  $c = 5$ . Thay vào ta được  $n = \overline{a302b5}$ .

Vì n chia hết cho 9 nên  $a + 3 + 0 + 2 + b + 5 = a + b + 10$  chia hết cho 9. Suy ra  $a + b = 8$  hoặc  $a + b = 17$ .

a) Nếu  $a + b = 17$  thì  $a = 8$ ;  $b = 9$  hoặc  $a = 9$ ;  $b = 8$ . Thay vào ta được số 830295 và 930285.

b) Nếu  $a + b = 9$ . Số 9 có thể biểu diễn thành tổng của các cặp số sau: 0 và 9 (loại); 1 và 8 (chọn); 2 và 7 (loại); 3 và 6 (loại); 4 và 5 (loại). Thay vào ta được số 130285 và 830215.

Số nhỏ nhất cần tìm là 130 285.

**Vi dụ 4.47.** Cho năm chữ số 0, 5, 6, 7, 8. Tự năm chữ số đó có thể viết được bao nhiêu số?

a) Có ba chữ số khi chia cho 5 dư 3?

b) Có ba chữ số khác nhau khi chia cho 5 dư 2?

c) Có ba chữ số khác nhau khi chia cho 5 dư 1 và chia cho 9 dư 5?

**Giải:** a) Số cần tìm có dạng  $n = \overline{ab8}$ . Ta thấy:

- Có 4 cách chọn a;

- Có 5 cách chọn b.

Vậy số các số có ba chữ số khi chia cho 5 dư 3 viết được từ năm chữ số đã cho là:  $4 \times 5 = 20$  (số).

b) Số cần tìm có dạng  $n = \overline{ab7}$ . Ta thấy:

- Có 3 cách chọn a;

- Có 3 cách chọn b.

Vậy số các số có ba chữ số khác nhau khi chia cho 5 dư 3 viết được từ năm chữ số đã cho là:  $3 \times 3 = 9$  (số).

c) Số cần tìm có dạng  $n = \overline{ab6}$ . Vì n chia cho 9 dư 5 nên  $a + b + 6$  chia cho 9 dư 5. Suy ra  $a + b = 8$  hoặc  $a + b = 17$  (loại).

Với  $a + b = 8$ . Trong năm chữ số đã cho, số 8 có thể phân tích thành tổng của 0 với 8.

Vậy số có ba chữ số khi chia cho 5 dư 1, cho 9 dư 5 viết được từ năm chữ số đã cho là 806.

**Ví dụ 4.48.** Thay a và b bởi các chữ số thích hợp để được số tự nhiên  $n = \overline{a37b}$  là số chẵn lớn nhất có bốn chữ số khi chia cho 3 dư 2, chia cho 5 dư 3.

**Giải:** Số cần tìm có dạng  $n = \overline{a37b}$ . Vì n chia cho 5 dư 3 nên  $c = 3$  hoặc 8. Mặt khác, n là số chẵn nên  $c = 8$ . Thay vào ta được  $n = \overline{a378}$ .

Vì n chia cho 3 dư 2 nên  $a + 3 + 7 + 8 = a + 18$  chia cho 3 dư 2. Suy ra  $a = 2, 5, 8$ . Thay vào ta được các số 2378; 5378; 8378.

Số lớn nhất cần tìm là 8378.

### II. Cơ sở toán học của tập phân số ở Tiểu học

#### 1. Quan hệ tương đương và tập thương

##### 1.1. Định nghĩa và tính chất của quan hệ tương đương

**Định nghĩa 4.20.** Cho X là một tập hợp. Mỗi tập con R của tích Đề-các  $X \times X$  ta gọi là một quan hệ hai ngôi trên tập X.

Ta nói rằng hai phần tử a, b của tập X có quan hệ hai ngôi R hay còn nói a quan hệ R với b, kí hiệu là  $aRb$ , nếu  $(a; b) \in R$ .

**Định nghĩa 4.21.** Cho R là quan hệ hai ngôi trên tập X. Ta nói rằng quan hệ hai ngôi R có tính chất:

a) *Phản xạ*, nếu  $aRa$  với mọi phần tử a thuộc tập X;

b) *Đối xứng*, nếu:  $\forall a, b \in X, aRb \rightarrow bRa$ ;

c) Bác cầu, nếu:  $\forall a, b, c \in X, aRb$  và  $bRc \rightarrow aRc$

Quan hệ hai ngôi  $R$  gọi là quan hệ tương đương nếu  $R$  có tính chất phản xạ, đối xứng và bắc cầu.

Nếu  $R$  là quan hệ tương đương, ta sẽ viết  $a \sim b$  thay cho  $aRb$ .

Ví dụ 4.49. Nếu trên tập các số tự nhiên  $\mathbb{N}$  ta định nghĩa: Hai số tự nhiên  $a$  và  $b$  có quan hệ  $e$  khi và chỉ khi chúng có cùng chữ số tận cùng thì ta dễ dàng chỉ ra rằng  $e$  là một quan hệ tương đương xác định trên tập  $\mathbb{N}$ .

Ví dụ 4.50. Gọi  $A$  là tập tất cả các sinh của lớp 5A. Trong tập  $A$  ta định nghĩa: Hai học sinh  $a \sim b$  nếu chúng ngồi cùng bàn.

Ta dễ dàng chỉ ra rằng  $\sim$  là một quan hệ tương đương xác định trên tập  $A$ .

Ví dụ 4.51. Quan hệ đồng dạng hoặc quan hệ bằng nhau giữa các hình tam giác là những quan hệ tương đương trên tập tất cả các tam giác trên mặt phẳng.

Ví dụ 4.52.

- Quan hệ vuông góc và quan hệ song song giữa các đường thẳng trong mặt phẳng đều không phải là quan hệ tương đương.

- Quan hệ chia hết giữa các số tự nhiên không phải là quan hệ tương đương trên tập số tự nhiên  $\mathbb{N}$ .

- Quan hệ “là bạn” trong một tập thể người cũng không phải là quan hệ tương đương.

##### 1.2. Định lý về tập thương

Định nghĩa 4.22. Cho  $\sim$  là quan hệ tương đương xác định trong tập  $X$  và  $a \in X$ . Ta gọi tập:

$$C(a) = \{x \in X : x \sim a\}$$

là lớp tương đương của phần tử  $a$ . Phần tử  $a$  gọi là phần tử đại diện của lớp  $C(a)$ .

Ta gọi tập tất cả các lớp tương đương:

$$\{C(x) : x \in X\}$$

là tập thương của tập  $X$  chia theo quan hệ tương đương  $\sim$ . Kí hiệu là  $X/\sim$ .

Ví dụ 4.53. Tìm tập thương của tập các số tự nhiên  $\mathbb{N}$  chia theo quan hệ tương đương  $e$  “có cùng chữ số tận cùng” trong Ví dụ 4.49.

**Giải:** Ta phải làm hai việc: Chứng minh  $e$  là quan hệ tương đương (xem Ví dụ 4.49) và xác định tập thương  $\frac{N}{e}$ .

Với mỗi số tự nhiên  $a$  thì  $C(a)$  là tập các số tự nhiên có cùng chữ số tận cùng với  $a$ . Nếu ta kí hiệu  $C(i)$  là tập các số tự nhiên có chữ số tận cùng bằng  $i$  với  $i = 0, 1, 2, \dots, 9$  thì:

$$\frac{N}{e} = \{C(0); C(1); C(2); \dots; C(9)\}.$$

**Ví dụ 4.54.** Tìm tập thương của tập  $A$  các em học sinh của lớp 5A chia theo quan hệ tương đương ~ “ngôi cùng bàn” trong Ví dụ 4.50.

**Giải:** Ta phải làm hai việc: Chứng minh ~ là quan hệ tương đương (xem Ví dụ 4.50) và xác định tập thương  $\frac{A}{~}$ .

Với mỗi học sinh  $a$  của lớp 5A thì  $C(a)$  là tập các học sinh ngồi cùng bàn với  $a$ . Vì vậy mỗi phân tử của tập thương  $\frac{A}{~}$  là một bàn có học sinh ngồi trong lớp đó.

**Định lý 4.25.** (Về tính chất của tập thương)

Giả sử  $e$  là quan hệ tương đương xác định trên tập  $X$  và  $a, b \in X$ .

Khi đó:

1. $C(a) \neq \emptyset$ ;
2. $C(a) = C(b) \Leftrightarrow a \sim b$ ;
3. $C(a) = C(b) \Leftrightarrow C(a) \cap C(b) \neq \emptyset$ .

*Chứng minh.*

(i) Rõ ràng là  $a \in C(a)$ . Từ đó suy ra điều phải chứng minh.

(ii) *Điều kiện cần:* Hiển nhiên.

*Điều kiện đủ:* Giả sử  $a \sim b$  và  $x \in C(a) \Leftrightarrow x \sim a \Leftrightarrow x \sim b \Leftrightarrow x \in C(b) \Leftrightarrow C(a) = C(b)$ .

(iii) *Điều kiện cần:* Hiển nhiên.

*Điều kiện đủ:* Giả sử  $C(a) \cap C(b) \neq \emptyset \Leftrightarrow \exists x \in C(a) \cap C(b) \Leftrightarrow x \sim a; x \sim b \Leftrightarrow a \sim b \Leftrightarrow C(a) = C(b)$ .

**Chú ý:** Định lý 4.25 cho ta biết: Nếu trong tập  $X$  xác định một quan hệ tương đương thì ta có thể phân chia tập  $X$  thành các tập con khác rỗng, đôi một không giao nhau sao cho hợp các tập con đó cho ta cà tập  $X$ .

Phép phân chia này trở thành cơ sở của việc mở rộng các tập hợp số trong toán học.

#### 2. Xây dựng tập số hữu tỉ không âm

##### 2.1. Sự cần thiết phải xây dựng tập số hữu tỉ không âm

Nếu dùng lại ở tập số tự nhiên thì nhiều phép chia không thực hiện được, chẳng hạn  $3:7, 25:8, 1:6, \dots$

Nếu dùng lại ở tập số tự nhiên thì nhiều số do của các phép đo đại lượng không thực hiện được, chẳng hạn, không thể biểu diễn số do  $12\text{cm}$ ;  $2\text{m } 4\text{dm}$  bằng đơn vị là mét; không thể biểu diễn  $100\text{g}$ ;  $300\text{g}$ ;  $4\text{kg } 25\text{g}$  bằng đơn vị là ki-lô-gam,...

Trong môn Toán ở trường phổ thông, nhiều tính chất của các phép toán về phân số (tính chất giao hoán, tính chất kết hợp, tính chất phân phối của phép cộng và phép nhân,...) không chứng minh được chặt chẽ mà phải thừa nhận (thông qua một số ví dụ minh hoạ).

Trong thực tế cuộc sống lao động và sản xuất, do yêu cầu phát triển của các ngành khoa học và kỹ thuật luôn đặt ra yêu cầu giải quyết những tồn tại nêu trên.

Vì vậy, trong phần này ta mở rộng tập số tự nhiên thêm các số mới để trong tập hợp số mới đó khắc phục những hạn chế nêu trên.

##### 2.2. Xây dựng tập số hữu tỉ không âm

Mỗi cặp số thứ tự  $(a; b)$ , trong đó  $a$  là số tự nhiên,  $b$  là số tự nhiên khác 0 ta sẽ gọi là một *phân số không âm* (hay để cho gọn, ta sẽ gọi là *phân số*). Tập tất cả các phân số ta kí hiệu là  $\mathbb{P}$ . Như vậy  $\mathbb{P} = \mathbb{N} \times \mathbb{N}^*$ , trong đó  $\mathbb{N}^*$  là tập các số tự nhiên khác 0.

Để chỉ phân số, ta dùng ký hiệu  $\frac{a}{b}$  thay cho  $(a; b)$ . Trên tập  $\mathbb{P}$  ta định nghĩa quan hệ hai ngôi " $\sim$ " như sau:

Hai phân số  $\frac{a}{b}$ ;  $\frac{c}{d}$  gọi là tương đương, ký hiệu là  $\frac{a}{b} \sim \frac{c}{d}$ , nếu  $ad = cd$ .

Chẳng hạn,  $\frac{1}{2} \sim \frac{4}{8}$ ;  $\frac{3}{4} \sim \frac{9}{12}$ ;  $\dots$ ;  $\frac{1}{2}$  không tương đương với  $\frac{2}{5}$ ;  $\frac{3}{4}$  không tương đương với  $\frac{4}{3}$ ;  $\dots$

Ta dễ dàng chỉ ra rằng " $\sim$ " là quan hệ tương đương xác định trên tập các phân số  $\mathbb{P}$ . Theo định lý 4.24 ta có thể phân chia tập  $\mathbb{P}$  thành các lớp tương đương và nhận được tập thương  $\mathbb{P}/\sim = \left\{ C\left(\frac{a}{b}\right) : \frac{a}{b} \in \mathbb{P} \right\}$ .

Mỗi lổp tương đương  $C(\frac{a}{b})$  là một tập hợp các phân số bằng nhau

(bằng phân số  $\frac{a}{b}$ ). Chẳng hạn:

$$C\left(\frac{1}{2}\right) = \left\{1; \frac{2}{4}; \frac{3}{6}; \frac{45}{90}; \frac{120}{240}; \dots\right\};$$

$$C\left(\frac{3}{4}\right) = \left\{\frac{3}{4}; \frac{6}{8}; \frac{9}{12}; \dots; \frac{45}{60}; \dots; \frac{75}{100}; \dots\right\}.$$

Mỗi lổp tương đương  $C(\frac{a}{b})$  ta sẽ gọi là một số hữu tỉ không âm (đề cho

gon ta gọi là số hữu tỉ), kí hiệu là  $r = C(\frac{a}{b})$ . Tập tất cả các số hữu tỉ không âm ta kí hiệu là  $Q_+$ . Như vậy  $Q_+ = P_+$ .

**Chú ý:**

1) Mỗi số hữu tỉ không âm  $r = C(\frac{a}{b})$  là một tập hợp các phân số bằng phân số  $\frac{a}{b}$ . Đề cho gon, ta sẽ dùng kí hiệu  $\frac{a}{b}$  để chỉ số hữu tỉ  $r = C(\frac{a}{b})$ .

Chẳng hạn: Ta dựng kí hiệu  $\frac{1}{2}$  để chỉ số hữu tỉ  $r = C(\frac{1}{2})$ ;  $\frac{9}{5}$  để chỉ số hữu tỉ  $r = C(\frac{9}{5})$ ;

ti  $r = C(\frac{9}{5})$ ;

2) Mỗi số hữu tỉ không âm  $r$  chỉ có duy nhất đại diện là phân số tối giản.

Thật vậy, giả sử  $\frac{p}{q}$  và  $\frac{p'}{q'}$  là hai phân số tối giản cùng là đại diện của số hữu tỉ  $r$ . Theo định nghĩa lổp tương đương ta có  $\frac{p}{q} \sim \frac{p'}{q'}$ . Suy ra  $p'q' = p'q$ . Vì  $UCLN(p; q) = UCLN(p'; q') = 1$  nên  $p = p'$  và  $q = q'$ . Suy ra điều phải chứng minh.

Ta quy ước: Khi nói đến phân số đại diện của số hữu tỉ  $r$  ta hiểu là phân số tối giản  $\frac{p}{q}$  đó.  $\left\{ \frac{p}{q} \right\} = \left\{ \frac{p'}{q'} \right\} = \frac{p}{q}$

3) Mối số tự nhiên  $a$  có thể biểu diễn dưới dạng một phân số là  $\frac{a}{1}$ . Vì vậy mỗi số tự nhiên  $a$  cũng xác định duy nhất số hữu tỉ  $r$  có phân số đại diện là  $\frac{a}{1}$ . Thành thử tập số tự nhiên  $N$  có thể coi là bộ phận của tập số hữu tỉ  $\mathbb{Q}+$ .

4) Ta quy ước số hữu tỉ xác định bởi  $C\left(\frac{0}{1}\right)$  là 0 và số hữu tỉ xác định bởi  $C\left(\frac{1}{1}\right)$  là 1.

#### 3. Quan hệ thứ tự trong tập số hữu tỉ không âm

Ở phổ thông ta đã biết:

+  $\frac{3}{7} < \frac{5}{7}$ . Vây ta có thể so sánh hai số hữu tỉ  $r = C\left(\frac{3}{7}\right)$  và  $s = C\left(\frac{5}{7}\right)$  được hay không?

+  $\frac{2}{7} < \frac{3}{5}$ . Vây ta có thể so sánh hai số hữu tỉ  $r = C\left(\frac{2}{7}\right)$  và  $s = C\left(\frac{3}{5}\right)$  được hay không?

Một cách tổng quát: Hãy đưa ra một quy tắc để có thể so sánh hai số hữu tỉ bất kì  $r = C\left(\frac{a}{b}\right)$  và  $s = C\left(\frac{c}{d}\right)$ . Đáp ứng yêu cầu này bằng định nghĩa dưới đây:

**Định nghĩa 4.23.** Cho hai số hữu tỉ  $r = C\left(\frac{a}{b}\right)$  và  $s = C\left(\frac{c}{d}\right)$ . Ta nói rằng:

a) Số hữu tỉ  $r$  nhỏ hơn hoặc bằng số hữu tỉ  $s$ , kí hiệu là  $r \le s$ , nếu  $ad \le bc$ .

b) Số hữu tỉ  $r$  nhỏ hơn số hữu tỉ  $s$ , kí hiệu là  $r < s$ , nếu  $r \le s$  và  $r \ne s$ ;

c) Số hữu tỉ  $r$  lớn hơn hoặc bằng số hữu tỉ  $s$ , kí hiệu là  $r \ge s$  nếu  $s \le r$ ;

d) Số hữu tỉ  $r$  lớn hơn số hữu tỉ  $s$ , kí hiệu là  $r > s$ , nếu  $s < r$ .

Các hệ thức  $r \le s$  và  $r \ge s$  ta gọi là các bất đẳng thức, các hệ thức  $r < s$  và  $r > s$  gọi là các bất đẳng thức nghiêm ngặt.

**Nhận xét.** Bằng định nghĩa trên đây, ta đã đưa việc so sánh các số hữu tỉ về so sánh các số tự nhiên.

Ví dụ 4.55.

$$+) C\left(\frac{3}{7}\right) < C\left(\frac{5}{7}\right) \text{ vì } 3.7 < 5.7;$$

$$+) C\left(\frac{5}{9}\right) > C\left(\frac{3}{11}\right) \text{ vì } 5.11 > 9.3;$$

$$+) C\left(\frac{2}{5}\right) = C\left(\frac{6}{15}\right) \text{ vì } 2.15 = 5.6.$$

**Định lí 4.26.** (Về tính chất của quan hệ thứ tự trong tập  $\mathbb{Q}^+$ )

(i) Việc so sánh hai số hữu tỉ không phụ thuộc vào sự lựa chọn các phân số đại diện của chúng;

(ii) Quan hệ thứ tự có tính chất phản xạ: Với mọi số hữu tỉ  $r$  ta luôn có  $r \le r$ ;

(iii) Quan hệ thứ tự có tính chất phản đối xứng: Với mọi số hữu tỉ  $r$ ,  $s$  ta luôn có:  $(r \le s \text{ và } s \le r) \rightarrow r = s$ ;

(iv) Quan hệ thứ tự có tính chất bắc cầu: Với mọi số hữu tỉ  $r$ ,  $s$ ,  $t$  ta luôn có:  $(r \le s \text{ và } s \le t) \rightarrow r \le t$ .

**Chứng minh.**

(i) Giả sử  $\frac{a}{b}, \frac{a'}{b'}$  là hai phân số đại diện của số hữu tỉ  $r$  và  $\frac{c}{d}, \frac{c'}{d'}$  là hai phân số đại diện của số hữu tỉ  $s$ , trong đó  $ad \le bc$ . Ta sẽ chứng minh  $a'd' \le b'c'$ .

Thật vậy, theo giả thiết:  $ab' = a'b$ ;  $cd' = c'd$ . Giả sử  $a'd' > b'c'$ . Áp dụng tính chất của tập số tự nhiên ta có:

$a'bc'd' = ab'c'd$  và  $adc'b' < bca'd'$  (điều này vô lý). Ta có điều phải chứng minh.

(ii) và (iii) Rõ ràng.

(iv) Giả sử  $r = \frac{a}{b}$ ;  $s = \frac{c}{d}$ ;  $t = \frac{m}{n}$ , trong đó

$$r \le s, s \le t \rightarrow ad \le bc; cn \le md \rightarrow adcn \le bcmd \rightarrow an \le mb \rightarrow r \le t.$$

**Định lí 4.27.**

(i) Tính trù mật của tập số hữu tỉ: Xem giữa hai số hữu tỉ khác nhau tồn tại vô số các số hữu tỉ khác chúng;

(ii) **Tiền đề  $\text{Ac-si-mét}$ :** Mọi số hữu tỉ đều bị chặn trên bởi một số tự nhiên, hay nói cách khác, với mọi số hữu tỉ  $r$  luôn tồn tại số tự nhiên  $n$  sao cho  $r < n$ .

Chứng minh.

(i) Giả sử  $r = \frac{a}{b}$ ,  $s = \frac{c}{d}$  là hai số hữu tỉ, trong đó  $r > s$ . Suy ra  $ad > bc$ .

Đặt  $t = \frac{ad+bc}{2bd}$ . Ta có:

$$\frac{c}{d} = \frac{2bc}{2bd} < \frac{ad+bc}{2bd} < \frac{2ad}{2bd} = \frac{a}{b}.$$

Từ đây suy ra  $r > t > s$ . Ta có điều phải chứng minh.

(ii) Giả sử  $r = \frac{a}{b}$ . Theo nguyên lý  $\text{Ac-si-mét}$ , trong tập số tự nhiên tồn tại số tự nhiên  $n$  sao cho  $nb > a$ . Suy ra  $n > r$ .

#### 4. Các phép toán trong tập số hữu tỉ không âm

##### 4.1. Phép cộng và phép nhân

##### 4.1.1. Định nghĩa và ví dụ

**Dịnh nghĩa 4.24.** Cho  $r$  và  $s$  là hai số hữu tỉ không âm, trong đó  $r = C\left(\frac{a}{b}\right)$ ;  $s = C\left(\frac{c}{d}\right)$ . Ta gọi:

a) **Tổng** của hai số hữu tỉ  $r$  và  $s$  là một số hữu tỉ  $t$ , kí hiệu là  $t = r + s$ , trong đó  $t = C\left(\frac{ad+bc}{bd}\right)$ . Quy tắc cho tương ứng mỗi cặp số hữu tỉ  $r$ ,  $s$  với một số hữu tỉ  $t$  nói trên ta gọi là phép cộng các số hữu tỉ, trong đó  $r$  và  $s$  gọi là các số hạng,  $t$  là tổng và  $r + s$  cũng gọi là tổng.

b) **Tích** của hai số hữu tỉ  $r$  và  $s$  là một số hữu tỉ  $p$ , kí hiệu là  $p = r \times s$  (hoặc  $r, s$  hoặc  $rs$ ), trong đó  $p = C\left(\frac{ac}{bd}\right)$ . Quy tắc cho tương ứng mỗi cặp số hữu tỉ  $r$ ,  $s$  với một số hữu tỉ  $p$  nói trên ta gọi là phép nhân các số hữu tỉ, trong đó  $r$  và  $s$  gọi là các thừa số,  $p$  gọi là tích và  $r \times s$  cũng gọi là tích.

**Ví dụ 4.56.** Cho  $r$  và  $s$  là hai số hữu tỉ có phân số đại diện tương ứng là  $\frac{4}{9}$  và  $\frac{7}{12}$ . Ta có:

$$r+s=C\left(\frac{4.12+9.7}{9.12}\right)=C\left(\frac{37}{36}\right)$$

$$rs=C\left(\frac{4.7}{9.12}\right)=C\left(\frac{7}{27}\right).$$

**Chú ý:** Tự định nghĩa ta chứng minh tổng và tích của hai số hữu tỉ không phụ thuộc vào việc lựa chọn các phân số đại diện của chúng.

Hay nói cách khác: Với hai số hữu tỉ bất kì  $r$  và  $s$  luôn tồn tại duy nhất số hữu tỉ  $t$  là tổng và một số hữu tỉ  $p$  là tích của chúng.

Giả sử  $\frac{a}{b}, \frac{a'}{b'}$  là hai phân số đại diện của số hữu tỉ  $r$  và  $\frac{c}{d}, \frac{c'}{d'}$  là hai phân số đại diện của số hữu tỉ  $s$ . Ta sẽ chứng minh

$$C\left(\frac{ad+bc}{bd}\right)=C\left(\frac{a'd'+b'c'}{b'd'}\right).$$

Thật vậy, theo giả thiết:  $ab' = a'b$ ;  $cd' = c'd$ . Áp dụng tính chất của tập số tự nhiên ta có:

$$ab'dd' = a'b'dd' \text{ và } cd'bb' = c'dbb' \text{ hay } (ad+bc)b'd' = (a'd'+b'c')bd.$$

Từ đây suy ra tổng của hai số hữu tỉ không phụ thuộc vào việc lựa chọn các phân số đại diện của chúng.

Tương tự ta chứng minh được tính duy nhất của tích hai số hữu tỉ.

##### 4.1.2. Tính chất của phép cộng và phép nhân

**Định lý 4.28.** (Tính chất của phép cộng và phép nhân các số hữu tỉ)

Giả sử  $r, s, t$  là ba số hữu tỉ bất kì. Khi đó:

(i) **Tính chất giao hoán:**

$$r+s=s+r \text{ và } r.s=s.r.$$

(ii) **Tính chất kết hợp:**

$$(r+s)+t=r+(s+t) \text{ và } (r.s).t=r.(s.t).$$

(iii) **Tính chất của số 0 và số 1:**

$$r+0=0+r=r \text{ và } r.1=1.r=r.$$

(iv) **Tính chất phân phối:**

$$r.(s+t)=r.s+r.t \text{ và } (s+t).r=s.r+t.r.$$

(v) **Luật gian ước:**

$$r+t=s+t \text{ suy ra } r=s \text{ và } r.t=s.t, \text{ với } t \neq 0 \text{ suy ra } r=s.$$

(vi) **Phản từ nghịch đảo:** Với mọi số hữu tỉ  $r \neq 0$  luôn tồn tại duy nhất số nghịch đảo  $r^{-1}$  của  $r$  sao cho  $r \cdot r^{-1} = 1$ .

(vii) Tích của hai số hữu tỉ bằng 0 khi và chỉ khi ít nhất một trong hai số đó bằng 0.

**Chứng minh.**

(i), (ii), (iii), (iv): Suy ra trực tiếp từ tính chất của các phép toán trong tập số tự nhiên.

(v) Giả sử  $\frac{a}{b}, \frac{c}{d}, \frac{m}{n}$  theo thứ tự là các phân số đại diện của các số hữu tỉ  $r, s, t$ . Theo định nghĩa ta có:

$$r+t = C\left(\frac{an+bm}{bn}\right); s+t = C\left(\frac{cn+dm}{dn}\right). \quad \text{Vì } r+t = s+t \text{ nên:}$$

$(an+bm)dn = bn(cn+dm)$  hay  $andn + bmdn = bncn + bndm$ . Suy ra  $ad = bc$ .

Từ đây suy ra điều phải chứng minh.

Tương tự ta chứng minh luật gian ước đối với phép nhân.

$$(vi) \text{Giả sử } r = C\left(\frac{a}{b}\right) \neq 0 \Rightarrow a \neq 0. \text{ Đặt } r^{-1} = C\left(\frac{b}{a}\right) \text{ sẽ là số nghịch đảo của } r.$$

$$(vii) \text{Giả sử } r = C\left(\frac{a}{b}\right), s = C\left(\frac{c}{d}\right) \text{ thỏa mãn } rs = 0. \text{ Theo định nghĩa ta có } \frac{ac}{bd} = 0.$$

Suy ra  $ac = 0$ . Theo tính chất của phép nhân các số tự nhiên ta có  $a = 0$  hoặc  $b = 0$ . Từ đây suy ra  $r = 0$  hoặc  $s = 0$ .

**Định lý 4.29.** (Tính đơn điệu của phép cộng và phép nhân các số hữu tỉ).

Giả sử  $r, s$  và  $t$  là số hữu tỉ bất kì. Ta có:

Nếu  $r \le s$  thì  $r+t \le s+t$  và  $rt \le st$ .

Đặc biệt, nếu  $r < s$  và  $t > 0$  thì  $rt < st$ .

**Chứng minh.**

Giả sử  $\frac{a}{b}, \frac{c}{d}, \frac{m}{n}$  theo thứ tự là các phân số đại diện của các số hữu tỉ  $r, s, t$ .

Theo định nghĩa ta có:

$$r+t = C\left(\frac{an+bm}{bn}\right); s+t = C\left(\frac{cn+dm}{dn}\right). \text{ Vì } r \le s \text{ nên: } ad \le bc.$$

Làm luật biến đổi ta được:

$$andn + bmdn \le cnbn + dmbn \text{ hay } (an + bm)dn \le (cn + dm)bn.$$

Từ đây suy ra điều phải chứng minh.

Tương tự ta chứng minh tính đơn điệu của phép nhân.

##### 4.2. Phép trừ

**Định nghĩa 4.25.** Cho  $r$  và  $s$  là hai số hữu tỉ không âm, trong đó  $r = C\left(\frac{a}{b}\right); s = C\left(\frac{c}{d}\right)$ . Ta gọi hiệu của hai số hữu tỉ  $r$  và  $s$  là một số hữu tỉ  $u$ , khi hiệu là  $u = r - s$ , trong đó  $u = C\left(\frac{ad - bc}{bd}\right)$ , nếu  $ad - bc$  là số tự nhiên.

Quy tắc cho tương ứng mỗi cặp số hữu tỉ  $r$ ,  $s$  với một số hữu tỉ  $u$  nói trên ta gọi là phép trừ các số hữu tỉ, trong đó  $r$  là số bị trừ,  $s$  là số trừ và  $u$  là hiệu và  $r - s$  cũng gọi là hiệu.

**Ví dụ 4.57.** Cho  $r$  và  $s$  là hai số hữu tỉ có phân số đại diện tương ứng là  $\frac{8}{9}$  và  $\frac{7}{12}$ . Ta có:  $r - s = C\left(\frac{8.12 - 9.7}{9.12}\right) = C\left(\frac{11}{36}\right)$ .

**Định lý 4.30.** (Tính chất của phép trừ các số hữu tỉ)

Giả sử  $r$ ,  $s$ ,  $t$  là ba số hữu tỉ bất kì. Khi đó:

$$(i) r - s = u \text{ khi và chỉ khi } u + s = r;$$

$$(ii) r(s - t) = rs - rt, \text{ nếu một trong hai về có nghĩa.}$$

Chứng minh.

(i) Giả sử  $\frac{a}{b}, \frac{c}{d}, \frac{m}{n}$  theo thứ tự là các phân số đại diện của các số hữu tỉ  $r$ ,  $s$ ,  $u$ . Theo định nghĩa ta có  $r - s = C\left(\frac{ad - bc}{bd}\right) = C\left(\frac{m}{n}\right) = u$  khi và chỉ khi:

$$\text{and } -bcn = bdm \text{ hay } \text{and } = bdm + bcn. \text{ Suy ra } \frac{a}{b} = \frac{dm + cn}{dn}.$$

Từ đây suy ra điều phải chứng minh.

(ii) Đặt  $u = s - t$ , từ (i) ta suy ra  $s = u + t$ . Ta có:

$$rs = r(u + t) = ru + rt = r(s - t) + rt.$$

Từ đây ta suy ra điều phải chứng minh.

##### 4.3. Phép chia

**Dịnh lý 4.31.** Giả sử  $r$  và  $s$  là hai số hữu tỉ, trong đó  $s$  khác 0. Khi đó tồn tại duy nhất số hữu tỉ  $q$  sao cho  $qs = r$ .

Chứng minh.

Vi  $s \neq 0$  nên theo Định lý 4.28 tồn tại số hữu tỉ nghịch đảo  $s^{-1}$ . Đặt  $q = rs^{-1}$ .

**Dịnh nghĩa 4.26.** Ta gọi số hữu tỉ  $q$  trong Định lý 4.31 là thương của hai số hữu tỉ  $r$  và  $s$ , ký hiệu là  $q = r : s$ .

Quy tắc cho trường ứng mỗi cặp số hữu tỉ  $r$ ,  $s$  với một số hữu tỉ  $q$  nói trên gọi là phép chia các số hữu tỉ, trong đó  $r$  là số bị chia,  $s$  là số chia và  $q$  là thương,  $r : s$  cũng gọi là thương.

**Ví dụ 4.58.** Cho  $r$  và  $s$  là hai số hữu tỉ có phân số đại diện tương ứng là  $\frac{8}{9}$  và  $\frac{7}{12}$ . Ta có:

$$r : s = C\left(\frac{8.12}{9.7}\right) = C\left(\frac{32}{21}\right)$$

**Nhận xét.** Từ các kết quả trên ta thấy:

1. Phép cộng và phép nhân các số hữu tỉ (không âm) luôn thực hiện được.
2. Phép trừ các số hữu tỉ không phải bao giờ cũng thực hiện được.
3. Phép chia một số hữu tỉ bất kì cho một số hữu tỉ khác 0 luôn thực hiện được.

#### 5. Nội dung dạy học phân số ở Tiểu học

Trong chương trình môn Toán tiểu học, nội dung về phân số được trình bày trong môn Toán lớp 4 và 5. Nó bao gồm các nội dung sau:

- Hình thành khái niệm phân số;
- So sánh các phân số;
- Các phép tính về phân số;
- Hỗn số;
- Giải toán về phân số.

##### 5.1. Hình thành khái niệm phân số ở Tiểu học

Khái niệm về phân số được trình bày trong môn Toán lớp 4 và 5, bao gồm các nội dung sau:

- Thông qua các biểu tượng hình thành khái niệm phân số (nhờ hon 1);

- Tự phép chia có dư dẫn đến khái niệm phân số;

- Giới thiệu cách đọc, viết và nhận biết cấu tạo của một phân số;

- Giới thiệu khái niệm hỗn số.

Chẳng hạn:

- Từ biểu tượng một hình (hình tròn, hình vuông, băng giấy....) được chia thành các phần bằng nhau, trong đó có một số phần được tô màu ta hinh thành khái niệm phân số nhỏ hon 1.

- Thông qua một số bài toán về phép chia có dư (chẳng hạn, chia 3 cái bánh cho 4 người, chia 5 quả cam cho 4 người,... ta dẫn đến các phân số  $\frac{3}{4}$ ,  $\frac{5}{4}$ , ...); để hình thành khái niệm phân số (nhờ hon hoặc lớn hon 1).

Từ các khái niệm trên, rút ra kết luận cho học sinh:

1) Cấu tạo của một phân số gồm: từ số là số tự nhiên viết trên gạch ngang; mẫu số là số tự nhiên khác 0 viết dưới gạch ngang.

2) Thương của phép chia một số tự nhiên cho một số tự nhiên khác 0 có thể viết thành một phân số, từ số là số bị chia và mẫu số là số chia.

3) Mối số tự nhiên có thể viết thành một phân số có từ số là số tự nhiên đó và mẫu số bằng 1.

- Từ nhu cầu biểu diễn 2 cái bánh và  $\frac{3}{4}$  cái bánh, ta hình thành cho học sinh khái niệm hỗn số  $\frac{3}{4}$ .

##### 5.2. Quan hệ so sánh các phân số ở Tiểu học

Trong chương trình môn Toán tiểu học, quan hệ so sánh giữa các phân số được trình bày trong môn Toán lớp 4, gồm các nội dung sau:

- Giới thiệu khái niệm phân số bằng nhau (chính là khái niệm phân số tương đương ta đã xây dựng ở phần trên).

- Hình thành khái niệm và cùng cố các kĩ năng rút gọn phân số,

- Hình thành khái niệm và xây dựng quy tắc quy đồng mẫu số các phân số;

- Xây dựng các quy tắc so sánh hai phân số (có cùng mẫu số và không cùng mẫu số).

Chẳng hạn:

- Từ biểu tượng một bàng giấy ta hình thành cho học sinh khái niệm hai phân số bằng nhau;
- Trên cơ sở khái niệm hai phân số bằng nhau, ta hình thành khái niệm và quy tắc rút gọn phân số, khái niệm và quy tắc quy đồng mẫu số các phân số;
- Bằng các hình ảnh trực quan, hình thành cho học sinh quy tắc so sánh hai phân số (có cùng hoặc không cùng mẫu số).

##### 5.3. Xây dựng các phép toán trong tập phân số

Các phép toán trong tập phân số được hình thành cho học sinh lớp 4 theo bốn bước:

1. Từ các bài toán thực tế kết hợp với các biểu tượng, hình thành ý nghĩa của mỗi phép toán;
2. Hình thành quy tắc thực hành mỗi phép toán (cộng, trừ, nhân và chia các phân số);
3. Giới thiệu tính chất của các phép tính về phân số.
4. Rèn kĩ năng thực hành các phép tính.

Cụ thể là:

- Dùng biểu tượng bàng giấy được chia thành các phần bằng nhau, sách giáo khoa (SGK) hình thành ý nghĩa và quy tắc thực hành phép cộng (hoặc phép trừ) hai phân số có cùng mẫu số.
- Vận dụng phương pháp quy đồng mẫu số, SGK hình thành ý nghĩa và quy tắc thực hành phép cộng (hoặc phép trừ) hai phân số không cùng mẫu số.
- Từ một bài toán thực tế về tính diện tích hình chữ nhật kết hợp với biểu tượng về mảnh bia được chia thành các phần bằng nhau, SGK hình thành ý nghĩa và quy tắc thực hành phép nhân hai phân số.
- Từ một bài toán thực tế về tính chiều dài hình chữ nhật khi biết diện tích và chiều rộng của hình đó, SGK hình thành ý nghĩa và quy tắc thực hành phép chia hai phân số.
- Các tính chất (giao hoán, kết hợp, phân phối, nhân một số với một tổng...) của các phép toán về phân số được suy ra trực tiếp từ các tính chất tương ứng của các phép toán trên tập số tự nhiên thông qua phép suy luận tương tự (trong các tiết luyện tập).

##### 5.4. Giải toán về phân số ở Tiểu học

Các bài toán về phân số ở Tiểu học có thể phân chia thành bốn dạng:

Dạng 1. Toán về cấu tạo phân số;

Dạng 2. Toán về so sánh phân số;

Dạng 3. Toán về các phép toán trên phân số;

Dạng 4. Toán có vận điều hinh trên tập phân số;

Sau đây ta minh hoạ ví dụ cho từng dạng toán.

**Dạng 1. Toán về cấu tạo phân số**

**Ví dụ 4.59.** Viết các phân số:

a) Có tổng của tử số và mẫu số bằng 8;

b) Lớn hơn 1 và có tích của tử số và mẫu số bằng 12.

**Giải:** a) Số 8 có thể phân tích thành tích của các cặp số: 0 và 8; 1 và 7;

2 và 6; 3 và 5; 4 và 2. Các phân số có tổng của tử số và mẫu số bằng 8 là:

$$\frac{0}{8}, \frac{1}{7}, \frac{2}{6}, \frac{3}{5}, \frac{4}{4}$$

b) Số 12 có thể phân tích thành tích của các cặp số sau: 1 và 12; 2 và 6; 3 và 4. Các phân số lớn hơn 1 có tích của tử số và mẫu số bằng 12 là:

$$\frac{12}{1}, \frac{6}{2}, \frac{4}{3}$$

**Ví dụ 4.60.** Tích của tử số và mẫu số của một phân số nhỏ hơn 1 bằng 315, khi chia cả tử và mẫu của phân số đó cho 3 ta được phân số tối giản. Tìm phân số đó.

**Giải:** Số 315 có thể phân tích thành tích của các cặp số sau: 1 và 315; 3 và 105; 5 và 63; 7 và 45; 9 và 35; 15 và 21.

Các phân số bé hơn 1 có tích của tử số và mẫu số bằng 315 là:

$$\frac{1}{315}, \frac{3}{105}, \frac{5}{63}, \frac{7}{45}, \frac{9}{35}, \frac{15}{21}$$

Bằng phương pháp thử chọn ta nhận được phân số cần tìm là:  $\frac{3}{105}, \frac{15}{21}$ .

**Ví dụ 4.61.** Rút gọn phân số:

$$\text{a)} \frac{232323}{414141}$$

$$\text{b)} \frac{132132}{231231}$$

**Giải:** Ta có:

$$a) \frac{232323}{414141} = \frac{232323 \cdot 10101}{414141 \cdot 10101} = \frac{23}{41}$$

$$b) \frac{132132}{231231} = \frac{132132 \cdot 1001}{231231 \cdot 1001} = \frac{132}{231} = \frac{132 \cdot 33}{231 \cdot 33} = \frac{4}{7}$$

**Dạng 2. Toán về so sánh phân số**

**Ví dụ 4.62.** Sắp xếp các phân số:

$$a) \frac{5}{7}, \frac{3}{4}, \frac{5}{8} \text{ theo thứ tự từ lớn đến bé;}$$

$$b) \frac{4}{7}, \frac{2}{5}, \frac{8}{11} \text{ theo thứ tự từ bé đến lớn.}$$

**Giải:** a) Quy đồng mẫu số các phân số đã cho ta được:

$$\frac{5}{7} = \frac{40}{56}, \frac{3}{4} = \frac{42}{56}, \frac{5}{8} = \frac{35}{56}. \text{ Vì } \frac{42}{56} > \frac{40}{56} > \frac{35}{56} \text{ nên các phân số đã cho xếp theo thứ tự từ lớn đến bé là: } \frac{3}{4}, \frac{5}{7}, \frac{8}{11}$$

b) Quy đồng tử số các phân số đã cho ta được:

$$\frac{4}{7} = \frac{8}{14}, \frac{2}{5} = \frac{8}{20}. \text{ Vì } \frac{8}{20} < \frac{8}{14} < \frac{8}{11} \text{ nên các phân số đã cho xếp theo thứ tự từ bé đến lớn là: } \frac{2}{5}, \frac{4}{7}, \frac{8}{11}$$

**Ví dụ 4.63.** Không quy đồng mẫu số, hãy viết các phân số sau theo thứ tự từ bé đến lớn:

$$\frac{45}{7}, \frac{35}{9}, \frac{17}{4}.$$

$$\text{Giải: Ta có: } \frac{45}{7} = 6\frac{3}{7}; \frac{35}{9} = 3\frac{8}{9}; \frac{17}{4} = 4\frac{1}{4}. \text{ Vì } 3 < 4 < 6 \text{ nên các phân số đã cho xếp theo thứ tự từ bé đến lớn là: } \frac{3}{9}, \frac{4}{4}, \frac{7}{4}$$

**Dạng 3. Toán về các phép toán trên phân số**

**Ví dụ 4.64.** Tính giá trị của các biểu thức sau:

$$a) \frac{1414}{2121} + \frac{1313}{1414};$$

$$b) \frac{135135}{189189} - \frac{112112}{224224}$$

Giải:

$$a) \frac{1414}{2121} + \frac{1313}{1414} = \frac{14}{21} + \frac{13}{42} = \frac{28}{42} + \frac{39}{42} = \frac{67}{42}$$

$$b) \frac{135135}{189189} - \frac{112112}{224224} = \frac{135}{189} - \frac{112}{224} = \frac{5}{7} - \frac{1}{2} = \frac{10-7}{14} = \frac{3}{14}$$

Ví dụ 4.65. Tính:

$$a) \frac{9}{14} + \frac{5}{8} + \frac{6}{7} + \frac{17}{24};$$

$$b) \frac{2013}{2015} \times \frac{2008}{2011} \times \frac{2015}{2012} \times \frac{2011}{2013} \times \frac{1006}{1004}.$$

Giải: Áp dụng tính chất giao hoán và tính chất kết hợp của phép cộng và phép nhân ta có:

$$a) \frac{9}{14} + \frac{5}{8} + \frac{6}{7} + \frac{17}{24} = \left(\frac{9}{14} + \frac{6}{7}\right) + \left(\frac{5}{8} + \frac{17}{24}\right) \\ = \frac{9+12}{14} + \frac{15+17}{24} = \frac{21}{14} + \frac{32}{24} + \frac{3}{2} + \frac{4}{8} = \frac{9+8}{6} = \frac{17}{6}$$

$$b) \frac{2013}{2015} \times \frac{2008}{2011} \times \frac{2015}{2012} \times \frac{2011}{2013} \times \frac{1006}{1004}$$

$$= \left(\frac{2013}{2015} \times \frac{2015}{2012}\right) \times \left(\frac{2008}{2011} \times \frac{2011}{2013}\right) \times \frac{1006}{1004}$$

$$= \frac{2013}{2012} \times \frac{2008}{2013} \times \frac{1006}{1004} = \frac{2008}{2012} \times \frac{1006}{1004} = 1004 \times 2 \times 1006 = 1$$

Dạng 4. Toán có vấn đề hình trên tập phán số

Ví dụ 4.66. Hai bà đi chợ bán trứng, sau khi nhẩm tính, một bà bảo: "2/5 số trứng của tôi gấp 1,5 lần 4/7 số trứng của bà và 2/5 số trứng của tôi nhiều hơn 4/7 số trứng của bà là 40 quả". Hỏi mỗi bà đã mang bao nhiêu trứng ra chợ bán?

Giải: Vì 1,5 =  $\frac{3}{2}$  nên theo đề bài ta có sơ đồ sau:

$\frac{2}{5}$  số trứng của bà thứ nhất:

![](851d99765a6fe09d94a024c53bd9fe40_img.jpg)

Diagram showing a line segment divided into 5 equal parts. The first part is labeled "quả" (egg). The total length is labeled 40 quả.

$\frac{4}{7}$  số trứng của bà thứ hai:

![](3881b390d52f27a35faedfc170916c86_img.jpg)

Diagram showing a line segment divided into 7 equal parts. The first part is labeled "quả" (egg). The total length is labeled 40 quả.

$\frac{2}{5}$  số trứng của bà thứ nhất là:  $40 \times 3 = 120$  (quả)

Số trứng của bà thứ nhất mang ra chợ bán là:

$$120 : 2 \times 5 = 300 \text{ (quả)}$$

$\frac{4}{7}$  số trứng của bà thứ hai là:  $40 \times 2 = 80$  (quả)

Số trứng của bà thứ hai mang ra chợ bán là:

$$80 : 4 \times 7 = 140 \text{ (quả)}$$

Đáp số: 300 quả và 140 quả.

Ví dụ 4.67. Hai đội vận tải được giao vận chuyển một lô hàng: sau khi

Đội I vận chuyển được  $\frac{3}{5}$  số hàng được giao và Đội II vận chuyển được  $\frac{3}{8}$  số hàng được giao thì số hàng còn lại của cả hai đội là 560 tấn, trong đó số hàng còn lại của Đội I bằng  $\frac{3}{4}$  số hàng của Đội II. Hỏi lúc đầu mỗi đội được giao vận chuyển bao nhiêu tấn hàng?

Giải: Theo đề bài ta có sơ đồ sau:

![](78b0ee96122867acbf9f918929159b77_img.jpg)

Diagram showing a line segment representing the total amount of cargo (560 tấn). The segment is divided into 5 equal parts. The first part is labeled "tấn". The total length is labeled 560 tấn.

Số hàng còn lại của Đội II:

$$\text{Số hàng còn lại của Đội I là: } 560 : (3 + 4) \times 3 = 240 \text{ (tấn)}$$

$$\text{Số hàng còn lại của Đội II là: } 560 - 240 = 320 \text{ (tấn)}$$

$$\text{Số hàng của Đội I được giao vận chuyển lúc đầu là:}$$

![](de242efdfd538be72e313b61ea15717b_img.jpg)

Diagram showing a line segment representing the total amount of cargo (240 tấn). The segment is divided into 5 equal parts. The first part is labeled "tấn". The total length is labeled 240 tấn.

$$240 : 2 \times 5 = 600 \text{ (tấn)}$$

Số hàng của Đội II được giao vận chuyển lúc đầu là:

![](3bce6bece036404fcfe7605bd52c22fe_img.jpg)

Diagram showing a long line segment divided into 320 equal parts. The question mark indicates the number of rows (tầng).

$$320 : 5 \times 8 = 512 \text{ (tầng)}$$

Đáp số: Đội I: 600 tầng hàng.

Đội II: 512 tầng hàng.

### III. Cơ sở toán học của tập số thập phân ở Tiểu học

#### 1. Phân số thập phân

Các phân số  $\frac{3}{10}$ ;  $\frac{116}{100}$ ;  $\frac{35}{1000}$ ;  $\frac{12}{1}$ ; ... đều có mẫu số là lũy thừa của 10 với số mũ tự nhiên. Các phân số dạng này ta thường gặp trong các phép đo đại lượng, chẵng hạn:

- Chiều dài cạnh bàn là 1m 25cm hay 1m  $\frac{25}{100}$  m;

- Gói hàng cân nặng 365g hay  $\frac{365}{1000}$  kg;

...

**Định nghĩa 4.26.** Phân số  $\frac{a}{b}$  gọi là phân số thập phân nếu mẫu số  $b$  của nó là lũy thừa của 10 với số mũ tự nhiên ( $b = 10^n$ ,  $n \in \mathbb{N}$ ).

Chẳng hạn các phân số  $\frac{3}{10}$ ;  $\frac{116}{100}$ ;  $\frac{35}{1000}$ ;  $\frac{12}{1}$ ; ... là những phân số thập phân.

Phân số  $\frac{3}{4}$  không phải là phân số thập phân, nhưng  $\frac{3}{4}$  lại bằng phân số thập phân  $\frac{75}{100}$ . Từ đây ta đi đến định nghĩa sau:

**Định nghĩa 4.27.** Phân số  $\frac{a}{b}$  gọi là biểu diễn được dưới dạng phân số thập phân nếu nó bằng một phân số thập phân nào đấy.

Chẳng hạn, các phân số  $\frac{1}{2}; \frac{24}{25}; \frac{15}{8}; \dots$  là những phân số biểu diễn được dưới dạng phân số thập phân; các phân số  $\frac{2}{3}; \frac{9}{14}; \frac{35}{24}; \dots$  không biểu diễn được dưới dạng phân số thập phân.

Dưới đây ta đưa ra một dấu hiệu để nhận biết một phân số có biểu diễn được dưới dạng phân số thập phân hay không.

**Dịnh lý 4.32.** (Điều kiện để phân số biểu diễn được dưới dạng phân số thập phân)

Để phân số tối giản  $\frac{p}{q}$  biểu diễn được dưới dạng phân số thập phân, điều kiện cần và đủ là mẫu số  $q$  của nó không chia hết nguyên tố nào khác ngoài 2 và 5.

*Chứng minh.*

*Điều kiện đủ.* Giả sử  $q$  chỉ có ước nguyên tố là 2 và 5. Vậy  $q = 2^m 5^n$ .

Giả sử  $n \le m$ . Ta có  $\frac{p}{q} = \frac{p}{2^m 5^n} = \frac{p \cdot 2^{m-n}}{2^m 5^n} = \frac{p \cdot 2^{m-n}}{10^n}$ . Vậy phân số  $\frac{p}{q}$  biểu diễn được dưới dạng phân số thập phân.

*Điều kiện cần.* Giả sử phân số tối giản  $\frac{p}{q} = \frac{a}{10^n}$ . Suy ra  $a \cdot q = p \cdot 10^n$ .

Giả sử  $k$  là một ước nguyên tố khác 2 và 5 của  $q$ . Suy ra  $k$  là ước của  $p$ . Vậy  $k = UCP(q)$ . Vì phân số  $\frac{p}{q}$  tối giản nên  $k = 1$ . Ta có điều phải chứng minh.

*Ví dụ 4.68.*

- Các phân số  $\frac{127}{40}; \frac{13}{16}; \frac{31}{125}$  đều tối giản và mẫu số của chúng chỉ có ước nguyên tố là 2 hoặc 5 nên chúng biểu diễn được dưới dạng phân số thập phân.

- Các phân số  $\frac{7}{9}; \frac{13}{14}; \frac{31}{120}$  đều tối giản và mẫu số của mỗi phân số đó có ước nguyên tố khác 2 và 5 nên chúng không biểu diễn được dưới dạng phân số thập phân.

Phân số  $\frac{21}{14} = \frac{3}{2} = \frac{13}{65} = \frac{1}{5}$  đều biểu diễn được dưới dạng số thập phân.

#### 2. Số thập phân không âm

Để tiện lợi trong tính toán và sử dụng, người ta đưa ra một cách biểu diễn riêng cho các phân số thập phân.

**Định nghĩa 4.28.** Số hữu tỉ  $r$  gọi là số thập phân không âm (để cho gọn, ta gọi là số thập phân) nếu nó có một đại diện là phân số thập phân hay nói cách khác: Phân số đại diện của nó biểu diễn được dưới dạng phân số thập phân.

Tập tất cả các số thập phân (không âm) ta ký hiệu là  $\mathbb{Q}_{+0}$ .

**Ví dụ 4.69.**

$$\frac{123}{10}; \frac{9}{16}; \frac{8}{100}; \frac{13}{40}; \frac{47}{10000} \in \mathbb{Q}_{+0}$$

$$\frac{9}{7}; \frac{17}{12}; \frac{17}{30} \notin \mathbb{Q}_{+0}$$

Như chúng ta đã biết, mỗi số thập phân có một cách biểu diễn là phân số thập phân. Cách biểu diễn này có nhược điểm là cũng kênh, không tiện lợi trong thực hành tính toán. Vì vậy, ta thường biểu diễn các số thập phân dưới dạng thu gọn, chẳng hạn:

$$+ \frac{123}{10} = 12,3 \text{ và đọc là: mươi hai đơn vị nguyên và ba phần mười của đơn vị hoặc để cho gọn ta đọc: mươi hai phẩy ba.}$$

$$+ \frac{71}{100} = 0,71 \text{ và đọc là: không đơn vị nguyên và bảy mươi một phần một trăm của đơn vị hoặc để cho gọn ta đọc: không phẩy bảy mươi một.}$$

$$+ \frac{43}{10000} = 0,0043 \text{ và đọc là không đơn vị nguyên và bốn mươi ba phần mươi nghìn của đơn vị hoặc để cho gọn ta đọc: không phẩy không bốn bốn ba.}$$

Vậy dạng thu gọn của số thập phân là dạng viết không có mẫu số của phân số thập phân theo quy tắc dưới đây:

— Bỏ mẫu số, đồng thời dùng dấu phẩy phân chia các chữ số của tử số thành hai nhóm: nhóm thứ nhất đứng bên phải dấu phẩy có số chữ số bằng

số chữ số 0 ở mẫu số; nhóm thứ hai đựng bên trái dấu phẩy gồm các chữ số còn lại của tử số.

– Nếu số chữ số của tử số ít hơn hay bằng số chữ số 0 ở mẫu số thì ta viết thêm những chữ số 0 vào trước từ số trước khi dùng dấu phẩy phân chia.

Số đúng bên trái dấu phẩy gọi là phần nguyên, nhóm các chữ số đúng bên phải dấu phẩy gọi là phần thập phân của số đó.

Chẳng hạn, số thập phân 32,0013 có phần nguyên là 32 và phần thập phân là nhóm các chữ số 0013.

Như vậy mỗi số thập phân có hai cách biểu diễn: dạng phân số và dạng thu gọn.

#### 3. Quan hệ thứ tự trong tập số thập phân không âm

Vì  $Q_{+10} \subset Q_+$ , nên để so sánh hai số thập phân ta đưa về so sánh hai số hữu tỉ tương ứng. Cụ thể là:

**Định nghĩa 4.29.** Cho  $r$  và  $s$  là hai số thập phân. Ta nói rằng số thập phân  $r$  nhỏ hơn hoặc bằng số thập phân  $s$ , ký hiệu là  $r \le s$ , nếu số hữu tỉ  $r$  nhỏ hơn hoặc bằng số hữu tỉ  $s$ .

Ví dụ 4.70.

Hãy so sánh hai số thập phân  $r = 9,63$  và  $s = 12,1$ .

Ta có  $9,63 = \frac{963}{100} < \frac{121}{10} = 12,1$ .

Xây dựng quan hệ thứ tự trong tập số thập phân như trên có ưu điểm về phương diện lý thuyết, nhưng có nhược điểm là công kênh trong thực hành so sánh (phải đưa về số so sánh các phân số). Vì vậy khi so sánh các số thập phân, ta thường sử dụng một trong hai quy tắc sau đây:

**Quy tắc 1.** Muốn so sánh một số thập phân với một số thập phân ta làm như sau:

1) Làm cho số chữ số ở phần thập phân của chúng bằng nhau (bằng cách viết thêm chữ số 0 vào những hàng còn thiếu);

2) Bỏ dấu phẩy, ta nhận được hai số tự nhiên;

3) So sánh hai số tự nhiên vừa nhận được, số nào lớn hơn thì số thập phân tương ứng với nó sẽ lớn hơn. Nếu hai số tự nhiên bằng nhau thì hai số thập phân tương ứng cũng bằng nhau.

**Quy tắc 2.** Muốn so sánh một số thập phân với một số thập phân ta làm như sau:

1) So sánh phần nguyên với phần nguyên, số nào có phần nguyên lớn hơn sẽ lớn hơn;

2) Nếu phần nguyên của chúng bằng nhau thì ta so sánh chữ số phần mười, số nào có chữ số phần mười lớn hơn sẽ lớn hơn;

3) Nếu chữ số phần mười của chúng cũng bằng nhau thì ta so sánh chữ số phần trăm và cứ tiếp tục như thế cho đến khi gặp hàng lớn hơn.

4) Nếu phần nguyên và các chữ số ở phần thập phân của chúng đều bằng nhau thì hai số đó bằng nhau.

Ví dụ 4.71. Hãy so sánh hai số thập phân  $r = 9,63$  và  $s = 12,1$ .

Cách 1. Ta có  $12,1 = 12,10$ . Vì  $963 < 1210$  nên  $9,63 < 12,1$ .

Cách 2. Vì  $9 < 12$  nên  $9,63 < 12,1$ .

#### 4. Số thập phân vô hạn tuần hoàn

Trong tập số tự nhiên  $\mathbb{N}$  ta đã chỉ ra rằng giữa hai số tự nhiên  $a$  và số liên sau của nó là một khoảng trống. Trong tập số hữu tỉ  $\mathbb{Q}$ , ta đã chỉ ra rằng giữa hai số hữu tỉ bất kì luôn tồn tại vô số các số hữu tỉ khác chúng.

Định lí dưới đây khẳng định tính chất tương tự của tập số thập phân  $\mathbb{Q}_{10}$  như trong tập số hữu tỉ:

Định lí 4.33. (Về tính trừ mật của tập số thập phân)

Với mọi số hữu tỉ  $r$ , với mọi số tự nhiên  $k$ , tồn tại một số thập phân  $t$  sao cho:

$$r - \frac{1}{10^k} < t < r + \frac{1}{10^k}$$

Hay nói cách khác: Mỗi số hữu tỉ  $r$  đều có thể xếp xi bời một số thập phân  $t$  với sai số nhỏ tùy ý.

Chứng minh.

Giả sử  $r \in \mathbb{Q}_+$ ;  $k \in \mathbb{N}$ . Theo tiên đề Ac-si-mét, tồn tại số tự nhiên  $n$  sao cho  $r < n$ . Ta đặt:

$X = \{a \in \mathbb{N}: a \le 10^k r\}$ . Rõ ràng là  $X \subset \mathbb{N}$ ,  $X \neq \emptyset$  và bị chặn trên. Từ đây suy ra  $X$  có phần tử lớn nhất, kí hiệu là  $M$ . Thẻ thì  $M \le 10^k r < M + 1$  hay  $\frac{M}{10^k} \le r < \frac{M}{10^k} + \frac{1}{10^k}$ .

Đặt  $t = \frac{M}{10^k}$  ta được điều phải chứng minh.

**Chú ý:** Định lý 4.33 khẳng định về mặt lý thuyết sự tồn tại của số thập phân t nhưng chưa đưa ra thuật toán để tìm số thập phân này.

Trong thực hành tính toán ta tìm t như sau: Giả sử ta phải tìm số thập phân  $x$  số hữu tỉ  $t = \frac{a}{b}$  với sai số nhỏ hơn  $10^{-k}$ .

Giả sử  $M$  là thương gần đúng của phép chia  $a.10^k$  chia cho  $b$ . Khi đó  $t = \frac{M}{10^k}$  là số thập phân cần tìm.

**Ví dụ 4.72.** 1) Hãy xác định số hữu tỉ  $t = \frac{7}{11}$  bởi một số thập phân với sai số nhỏ hơn  $10^{-5}$ .

2) Hãy xác định số hữu tỉ  $t = \frac{43}{22}$  bởi một số thập phân với sai số nhỏ hơn  $10^{-3}$ .

**Giải:** 1) Ta chia  $7.10^5$  cho 11 được thương là 63636 (đư 4). Vậy số thập phân cần tìm là 0,63636.

2) Ta chia  $43.10^3$  cho 22 được thương là 1954 (đư 12). Vậy số thập phân cần tìm là 1,954.

Trong các phân trước, ta đã biết rằng mỗi phân số tối giản  $t = \frac{a}{b}$  có hai khả năng:

— Nếu mẫu số  $b$  không chứa ước nguyên tố nào khác 2 và 5 thì  $r$  là một số thập phân;

— Nếu mẫu số  $b$  có chứa ước nguyên tố khác cả 2 và 5 thì  $r$  không phải là số thập phân. Trong trường hợp này, theo Định lý 4.33 thì  $r$  có thể xác định bởi một số thập phân với sai số nhỏ tùy ý.

Trong phân này, ta chỉ ra rằng những số hữu tỉ như thế có thể biểu diễn bởi một số “thập phân” theo nghĩa rộng.

Trước hết ta bắt đầu bằng một bài toán cụ thể: Hãy xác định số  $r = \frac{13}{11}$  bởi các số thập phân với những sai số khác nhau. Vận dụng phương pháp tiến hành ở phần trên ta được các kết quả sau:

- Nếu sai số không vượt quá  $\frac{1}{100}$  thì ta được số 1,18;

- Nếu sai số không vượt quá  $\frac{1}{10000}$  thì ta được số 1,1818;

- Nếu sai số không vượt quá  $10^{-6}$  thì ta được số 1,181818;

...

Cứ tiếp tục quá trình trên đây ta đi đến kết quả sau:

- Không bao giờ nhận được một số thập phân bằng  $\frac{13}{11}$ .

- Cứ tiếp tục mãi quá trình trên đây ta nhận được số “thập phân” có vô số chữ số ở phần thập phân.

- Các chữ số ở phần thập phân sẽ lặp lại một cách tuần hoàn có chu kỳ bằng 18. Trong trường hợp này ta viết:

$$\frac{13}{11} = 1,181818\dots \text{ hay } \frac{13}{11} = 1,(18)$$

và gọi là “số thập phân vô hạn tuần hoàn” với chu kỳ bằng 18.

Tiếp theo ta xét bài toán tương tự đối với phân số  $r = \frac{855}{22}$ . Lập luận tương tự như trên ta nhận được kết quả sau:

- Nếu sai số không vượt quá  $10^{-3}$  ta được số thập phân 38,863;

- Nếu sai số không vượt quá  $10^{-5}$  ta được số thập phân 38,86363;

- Nếu sai số không vượt quá  $10^{-7}$  ta được số thập phân 38,8636363.

$$\text{Vậy } \frac{855}{22} = 38,8636363\dots$$

Ta nhận được số thập phân vô hạn tuần hoàn nhưng chu kỳ (là 63) không bắt đầu ngay sau dấu phẩy mà bắt đầu từ chữ số thập phân thứ hai. Nhưng số như thế, ta gọi là số thập phân vô hạn tuần hoàn tấp. Trong trường hợp này ta viết:  $r = 38,8(63)$ .

Một cách tổng quát: Giả sử phân số  $\frac{a}{b}$  không phải là số thập phân.

Ta thực hiện liên tiếp các phép chia a cho b (bằng cách thêm chữ số 0 vào bên phải số dư sau mỗi bước chia và tiếp tục chia) ta sẽ gặp lại số dư r nào đó mà đã gặp trong bước chia trước đó. Khi đó quá trình sẽ lặp lại vì vậy các chữ số ở thương cũng sẽ lặp lại một cách tuần hoàn. Số thập phân

nhận được có vô số chữ số ở phần thập phân, trong đó có một nhóm chữ số lập đi lập lại một cách tuần hoàn. Nhóm chữ số lập lại đó là thương bộ phận giữa hai số dư bằng nhau gọi là chu kì của số thập phân vô hạn tuần hoàn đó. Nếu chu kì bất đầu ngay sau dấu phẩy thì gọi là số thập phân vô hạn tuần hoàn đơn, ngược lại, gọi là số thập phân vô hạn tuần hoàn tạp.

#### 5. Nội dung dạy học số thập phân ở Tiểu học

Trong chương trình môn Toán tiểu học, nội dung về số thập phân được trình bày trong môn Toán lớp 5, bao gồm:

- Hình thành khái niệm số thập phân;
- So sánh các số thập phân;
- Các phép tính về số thập phân;
- Giải toán về số thập phân.

##### 5.1. Hình thành khái niệm số thập phân ở Tiểu học

Khai niệm về số thập phân trong môn Toán lớp 5 bao gồm các nội dung sau:

- Hình thành khái niệm số thập phân;
- Giới thiệu cách đọc, viết và nhận biết cấu tạo của một số thập phân;
- Giới thiệu các hàng của một số thập phân;
- Dùng số thập phân để biểu diễn các số đo đại lượng.

Chẳng hạn: Thông qua các thao tác cụ thể, khái niệm "số thập phân" được hình thành cho học sinh theo hai con đường:

Số thập phân là cách viết không có mẫu số của phân số thập phân, chẳng hạn:

$$\frac{1}{10} = 0,1; \frac{8}{100} = 0,08; \frac{1024}{1000} = 1,024; \dots$$

Số thập phân là cách biểu diễn các số đo đại lượng (từ nhiều đơn vị đo về một đơn vị đo hoặc từ đơn vị đo nhỏ hơn về đơn vị đo lớn hơn), chẳng hạn:

$$3m 7dm = 3,7m; 12m = 0,012km; 3kg 50g = 3,050kg;$$

$$2 \text{ tấn } 35kg = 2,035 \text{ tấn}; 458cm^2 = 0,0458m^2; \dots$$

Từ các khái niệm trên, rút ra kết luận cho học sinh:

- Cấu tạo của một số thập phân gồm: phần nguyên là số tự nhiên đứng bên trái dấu phẩy và phần thập phân là nhóm các chữ số đứng bên phải dấu phẩy. Giữa phần nguyên và phần thập phân được phân cách nhau bởi

dấu phẩy. Chẳng hạn số 12,045 có phần nguyên là 12, phần thập phân là 045 và đọc là mười hai phẩy không trăm bốn mươi lăm.

Từ cấu tạo của số thập phân, ta hình thành khái niệm các hàng phẩy mười, phần trăm, phần nghìn của số thập phân. Chẳng hạn, số thập phân 12,045 có chữ số hàng phẩy mười là 0, hàng phẩy trăm là 4 và hàng phẩy nghìn là 5.

##### 5.2. Quan hệ so sánh các số thập phân ở Tiểu học

Tương tự như đối với phân số, khi so sánh hai số thập phân ta hướng tới hai tình huống:

– Số này lớn hơn hoặc bé hơn số kia;

– Rút ra kết luận hai số đó bằng nhau.

Thông qua phép đo đại lượng (độ dài) ta đưa việc so sánh các số thập phân về số sánh các số tự nhiên (mà học sinh đã thành thạo trước đó). Cụ thể: Tùi bài toán "So sánh  $35,7m$  và  $35,698m$ " ta lần lượt đưa ra nhận xét:

– Phân nguyên của chúng bằng nhau (đều bằng 35m);

– Phần thập phân của  $35,7m$  là  $\frac{7}{10}m = 700mm$ ; phần thập phân của  $35,698m$  là  $\frac{698}{100}m = 698mm$ . Vì  $700mm > 698mm$  nên  $\frac{7}{10}m > \frac{698}{100}m$ .

Do đó  $35,7m > 35,698m$ .

Từ đây ta rút ra quy tắc: Muốn so sánh hai số thập phân ta làm như sau:

a) So sánh phần nguyên của hai số đó. Số nào có phần nguyên lớn hơn sẽ lớn hơn;

b) Nếu phần nguyên của chúng bằng nhau thì so sánh phần thập phân, lần lượt từ hàng phẩy mười, phần trăm, phần nghìn,.... đến cùng một hàng nào đó, số thập phân nào có chữ số ở hàng tương ứng lớn hơn sẽ lớn hơn.

c) Nếu phần nguyên và các chữ số ở phần thập phân của hai số đó bằng nhau thì hai số đó bằng nhau.

Đồng thời, sách giáo khoa cũng rút ra quy tắc: Nếu viết thêm (hoặc xóa đi) chữ số 0 ở cuối phần thập phân của một số thập phân thì ta được một số thập phân bằng nó.

##### 5.3. Xây dựng các phép toán trong tập số thập phân ở Tiểu học

Các phép trong tập số thập phân được trình bày trong mòn Toán lớp 5 theo năm bước:

1. Từ các bài toán thực tế hình thành ý nghĩa của mỗi phép toán;
2. Hình thành quy tắc thực hành mỗi phép toán (cộng, trừ, nhân và chia các số thập phân);
3. Giới thiệu tính chất của các phép tính về số thập phân;
4. Giới thiệu các quy tắc tính nhẩm: nhân, chia nhẩm với 10; 100; 1000;...
5. Rèn kĩ năng thực hành các phép tính.

Cụ thể là:

- Từ bài toán về cộng độ dài hai đoạn thẳng; SGK hình thành ý nghĩa và quy tắc thực hành phép cộng hai số thập phân;

- Củng tương tự như vậy đối với phép trừ;

- Từ một bài toán thực tế về tính chu vi một hình tam giác có ba cạnh bằng nhau, SGK hình thành ý nghĩa và quy tắc thực hành phép nhân các số thập phân;

- Phép chia các số thập phân được giới thiệu qua các bước:

- + Chia một số thập phân cho một số tự nhiên;
- + Chia một số tự nhiên cho một số tự nhiên có thương là số thập phân;
- + Chia một số tự nhiên cho một số thập phân;
- + Chia một số thập phân cho một số thập phân.

Ở mỗi bước đều xuất phát từ một bài toán thực tế về số đo đại lượng độ dài.

- Các tính chất (giao hoán, kết hợp, phân phối, nhân một số với một tổng,...) của các phép toán về số thập phân được suy ra trực tiếp từ các tính chất tương ứng của các phép toán trên tập số tự nhiên thông qua phép suy luận trong tự (trong các tiết luyện tập).

##### 5.4. *Giải toán về số thập phân ở Tiểu học*

Các bài toán về số thập phân ở Tiểu học có thể phân chia thành bốn dạng:

**Dạng 1.** Toán về cấu tạo số thập phân;

**Dạng 2.** Toán về so sánh số thập phân;

**Dạng 3.** Toán về các phép toán trên số thập phân;

**Dạng 4.** Toán về tỉ số phần trăm.

Dưới đây ta minh hoạ ví dụ cho từng dạng toán.

**Dạng 1. Toán về cấu tạo số thập phân**

**Ví dụ 4.73.** Viết các số sau đây dưới dạng số thập phân:

a)  $\frac{7}{100}$ ; b)  $\frac{123}{10}$ ; c)  $\frac{9}{40}$ .

Giải: a)  $\frac{7}{100} = 0,07$ ; b)  $\frac{123}{10} = 12,3$ ; c)  $\frac{9}{40} = \frac{225}{1000} = 0,225$ .

Ví dụ 4.74. Viết các số đo sau đây dưới dạng số thập phân:

a) 25dm 5cm với đơn vị là mét;  
b) 70g với đơn vị là ki-lô-gam;  
c) 5dm $^2$  8cm $^2$  với đơn vị là mét vuông;  
d) 2m $^2$  5cm $^2$  với đơn vị là đề-xi-mét vuông.

Giải:

a) 25dm 5cm =  $\frac{255}{100}$  cm = 2,55m;  
b) 70g =  $\frac{70}{1000}$  kg = 0,070kg;  
c) 5dm $^2$  8cm $^2$  =  $\frac{508}{10000}$  m $^2$  = 0,0508m $^2$ ;  
d) 2m $^2$  5cm $^2$  =  $\frac{20005}{100}$  = 200,05dm $^2$ .

Ví dụ 4.75. Cho ba chữ số 0, 1, 2. Hãy viết tất cả các số thập phân có ba chữ số ở cả phân nguyên và phân thập phân nhỏ hơn 20 sao cho mỗi chữ số đã cho xuất hiện trong cách viết đúng 1 lần.

Giải: Các số thập phân cần tìm là:

0,12; 0,21;  
1,02; 1,20; 10,2; 12,0;  
2,01; 2,10.

Ví dụ 4.76. Các chữ số ở hàng phân mười và hàng phân trăm của một số thập phân có hai chữ số ở phần thập phân là hai số chẵn liên tiếp viết theo thứ tự tăng dần. Tích các chữ số ở phần thập phân bằng phần nguyên của số đó. Các chữ số ở cả phân nguyên và phần thập phân đều khác nhau. Tìm số thập phân đó.

Giải: Phần thập phân của số thập phân cần tìm có thể là:  
02; 24; 46; 68.

Ta có bảng sau:

| Phần thập phân | Phần nguyên | Số thập phân | Kết luận |
|----------------|-------------|--------------|----------|
| 02             | 0           | 0,02         | Loại     |
| 24             | 8           | 8,24         | Chọn     |
| 46             | 24          | 24,64        | Loại     |
| 68             | 48          | 48,68        | Loại     |

Số thập phân cần tìm là 8,24.

##### Dạng 2. Toán về so sánh số thập phân

Ví dụ 4.77. Viết các số thập phân:

a) 5,90; 8,293; 9,029; 4,94 theo thứ tự từ bé đến lớn;

b) 72,037; 72,730; 72,703; 72,307 theo thứ tự từ lớn đến bé.

Giải: a) Các số đã cho viết theo thứ tự từ bé đến lớn là:

4,94; 5,90; 8,293; 9,029.

b) Các số đã cho viết theo thứ tự từ lớn đến bé là:  
72,730; 72,703; 72,307; 72,037.

Ví dụ 4.78. Viết năm số thập phân nằm giữa hai số 2,5 và 2,6.

Giải: Các số thập phân cần tìm là: 2,51; 2,52; 2,53; 2,54; 2,55.

Ví dụ 4.79. Thay a bởi chữ số thích hợp để:

$0,46 < 0,4\overline{a}6 < 0,485$ .

Giải: - Đèo  $0,46 < 0,4\overline{a}6$  thì  $a = 6, 7, 8$  hoặc 9;

- Đèo  $0,4\overline{a}6 < 0,485$  thì  $a = 1, 2, 3, 4, 5, 6$  hoặc 7;

- Từ đó suy ra đề  $0,46 < 0,4\overline{a}6 < 0,485$  thì  $a = 6$  hoặc  $a = 7$ .

##### Dạng 3. Toán về các phép toán trên số thập phân

Ví dụ 4.80. Tìm y:

a)  $51,42 - y = 3,45 : 0,12$ ;

b)  $8,64 \times y = 1,836 : 0,25$ ;

c)  $y : 5,6 = 0,8 \times 2,25$ ;

d)  $2,85 : \bar{y} = 1,4 : 0,65$ .

Giải:

a)  $51,42 - y = 3,45 : 0,12$

b)  $8,64 \times y = 1,836 : 0,25$

$51,42 - y = 28,75$

$y = 51,42 - 28,75$

$y = 22,67$ .

$$c) y: 5,6 = 0,8 \times 2,25$$

$$d) 2,85 : y = 1,4 - 0,65$$

$$y: 5,6 = 1,8$$

$$2,85 : y = 0,75$$

$$y = 1,8 \times 5,6$$

$$y = 2,85 : 0,75$$

$$y = 10,08$$

$$y = 3,8$$

$$\text{Ví dụ 4.81. Cho: } A = \frac{(x+4,25):0,5}{(5,25-4,75)\times 2,5}$$

$$a) \text{ Tìm } A \text{ khi } x = 5;$$

$$b) \text{ Tìm } x \text{ để } A = 12.$$

**Giải:** a) Thay  $x = 5$  ta có:

$$A = \frac{(5+4,25):0,5}{(5,25-4,75)\times 2,5} = \frac{9,25:0,5}{0,5\times 2,5} = \frac{18,5}{1,25} = 14,8$$

$$b) \text{ Khi } A = 12 \text{ ta có:}$$

$$\frac{(x+4,25):0,5}{(5,25-4,75)\times 2,5} = 12$$
$$\frac{(x+4,25):0,5}{0,5\times 2,5} = 12$$

$$\frac{(x+4,75):0,5}{1,25} = 12$$

$$(x+4,75):0,5 = 12 \times 1,25$$

$$(x+4,75):0,5 = 15$$

$$x+4,75 = 15 \times 0,5$$

$$x+4,75 = 7,5$$

$$x = 7,5 - 4,75$$

$$x = 2,75$$

**Ví dụ 4.82.** Tính giá trị biểu thức sau bằng cách hợp lý:

$$a) \frac{0,2 \times 213 \times 7 + 0,14 \times 2460 + 54,1 \times 14}{1+4+7+1+64-365}$$

$$b) \frac{(213,78 - 43,75 \times 0,37) \times (49,6 \times 0,25 - 24,8 \times 8)}{5,13 \times 2,45 - 12,48 \times 0,75}$$

**Giải:** a) Ta có:

$$0,2 \times 213 \times 7 + 0,14 \times 2460 + 54,1 \times 14 = 1,4 \times 213 \times 1,4 \times 246 + 541 \times 1,4 = 1,4 \times (213 + 246 + 541) = 1,4 \times 1000 = 1400$$

Triếp theo ta tính giá trị của biểu thức ở mẫu:  $1 + 4 + 7 + \dots + 64$  là tổng các số hạng của dãy số cách đều có số hạng đầu bằng 1, số hạng cuối bằng 64, khoảng cách bằng 3 và số số hạng của dãy số đó là:

$$(64 - 1) : 3 + 1 = 22 \text{ (số hạng)}$$

Giá trị của biểu thức ở mẫu là:

$$(1 + 64) \times 22 : 2 - 365 = 350.$$

Giá trị của biểu thức đã cho là:

$$\frac{1400}{350} = 4.$$

b) Ta nhân xét:

$$49,6 : 0,25 - 24,8 \times 8 = 49,6 \times 4 - 49,6 \times 4 = 0.$$

Vậy giá trị của biểu thức đã cho bằng 0.

**Ví dụ 4.83.** Tìm một số thập phân, biết rằng khi chia số đó cho 2 rồi trừ đi 1,8 sau đó nhân với 2,5 ta được kết quả bằng 37,5.

Giải: Số trước khi nhân với 2,5 là:

$$37,5 : 2,5 = 15$$

Số trước khi bớt đi 1,8 là:

$$15 + 1,8 = 16,8$$

Số cần tìm là:

$$16,8 \times 2 = 33,6.$$

**Ví dụ 4.84.** Thay mỗi chữ trong phép tính sau bởi chữ số thích hợp để được phép tính đúng:

$$a) \overline{8a}, \overline{ba} + \overline{cl}, 4d = \overline{d4,1c};$$

$$b) \overline{13}, \overline{ab} : 2,6 = \overline{a, b}.$$

Giải: a) Ta viết lại phép tính như sau:

$$8a, b a$$

$$c 1, 4 d$$

$$d 4, 1 c$$

Theo kết quả phép tính thì phép cộng chữ số hàng chục không nhớ, suy ra phép cộng chữ số hàng chục chỉ có thể là:  $8 + 1 = 9$ . Vậy  $c = 1$  và  $d = 9$ .

Thay vào phép tính ta sẽ tìm được  $a = 2$  và  $b = 6$ .

Thay vào ta được phép tính cần tìm là:

$$82,62 + 11,49 = 94,11.$$

b) Ta viết lại phép tính như sau:

$$\overline{13a}, \overline{ab} = \overline{a}, b \times 2,6 \text{ hay}$$

$$13 + \overline{0, ab} = \overline{0, ab} \times 26$$

$$\overline{0, ab} \times 26 - \overline{0, ab} = 13$$

$$\overline{0, ab} \times (26 - 1) = 13$$

$$\overline{0, ab} \times 25 = 13$$

$$\overline{0, ab} = 13 : 25 = 0,52 \text{ suy ra } a = 5 \text{ và } b = 2.$$

Thay vào ta được phép tính cần tìm là:

$$13,52 : 2,6 = 5,2.$$

##### Dạng 4. Toán về tỉ số phần trăm

**Ví dụ 4.85.** Lớp 5A có 40 học sinh, trong đó có 22 học sinh nữ. Hỏi số học sinh nữ chiếm bao nhiêu phần trăm số học sinh của cả lớp?

**Giải:** Tỉ số phần trăm học sinh nữ của lớp 5A là:

$$22 : 40 = 0,55$$

$$0,55 = 55\%$$

Đáp số: 55%.

**Ví dụ 4.86.** Lãi suất tiết kiệm 0,65%/tháng. Cô Thu gửi tiết kiệm 80 000 000 đồng. Hỏi sau một tháng cô được bao nhiêu tiền lãi?

**Giải:** Số tiền lãi của cô Thu sau một tháng là:

$$80000000 : 100 \times 0,65 = 520000 \text{ (đồng)}$$

Đáp số: 520 000 đồng.

**Ví dụ 4.87.** Trong kho có 60 tấn gạo nếp. Số gạo nếp chiếm 15% tổng số gạo trong kho. Hỏi trong kho có tất cả bao nhiêu tấn gạo?

**Giải:** Tổng số gạo trong kho là:

$$60 : 15 \times 100 = 400 \text{ (tấn)}$$

Đáp số: 400 tấn gạo.

**Ví dụ 4.88.** Một người bán chiếc quạt với giá 200 000 đồng thì được lãi 10% giá bán. Hỏi để lãi 15% giá gốc thì người đó phải bán chiếc quạt với giá bao nhiêu tiền?

**Giải:** Lãi 10% giá bán có nghĩa là: Nếu ta coi giá bán là 100% thì tiền lãi chiếm 10%, tiền gốc chiếm 90%.

Giá gốc của chiếc quạt đó là:  
 $200000 : 100 \times 90 = 180000$  (đồng).

Lãi 15% giá gốc có nghĩa là: Nếu ta coi giá gốc là 100% thì tiền lãi bằng 15% và giá bán bằng 115%.

Để lãi 15% giá gốc thì người đó phải bán chiếc quạt với giá là:  
 $180000 : 100 \times 115 = 207000$  (đồng).

Đáp số: 207 000 đồng.

Ví dụ 4.89. Khi tăng bán kính của một hình tròn thêm 10% thì diện tích hình đó sẽ tăng thêm bao nhiêu phần trăm?

Giải: Theo đề bài ta có:

$$R_{\text{mới}} = \frac{110}{100} R_{\text{cũ}} = \frac{11}{10} R_{\text{cũ}};$$

$$S_{\text{mới}} = R_{\text{mới}} \times R_{\text{mới}} \times 3,14 = \frac{11}{10} R_{\text{cũ}} \times \frac{11}{10} R_{\text{cũ}} \times 3,14$$

$$= \frac{121}{100} R_{\text{cũ}} \times R_{\text{cũ}} \times 3,14 = 121\% S_{\text{cũ}}$$

Diện tích hình tròn đó sẽ tăng:

$$121\% - 100\% = 21\%.$$

Đáp số: 21%.

## BÀI TẬP CHƯƠNG IV

Bài 1. Cho X là tập các tam giác, Y là tập các đường tròn.

a) Quy tắc cho tương ứng mỗi tam giác với một đường tròn ngoại tiếp nó có phải là ánh xạ hay không? Tại sao?

b) Quy tắc cho tương ứng mỗi đường tròn với tam giác nội tiếp trong đường tròn đó có phải là ánh xạ hay không? Tại sao?

Bài 2. Cho  $X = \{1; 2; 3; 4; 5; 6\}$ .

a) Hãy thiết lập một ánh xạ từ X vào chính nó.

b) Hãy thiết lập một toán ánh từ X vào chính nó.

c) Có thể thiết lập một đơn ánh mà không phải là toán ánh từ X vào chính nó không? Tại sao?

Bài 3. Cho  $X = \{a; b; c; d; e\}$  và  $Y = \{1; 2; 3; 4\}$ .

a) Hãy thiết lập một toán ánh từ X lên Y.

b) Có thể thiết lập một song ánh từ X lên Y không? Tại sao?