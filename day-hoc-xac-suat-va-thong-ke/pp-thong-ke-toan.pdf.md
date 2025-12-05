

TRẦN DIỄN HIẾN (Chủ biên)  
NGUYỄN THUÝ CHUNG

# CƠ SỞ TOÁN HỌC CỦA MÔN TOÁN TIỂU HỌC

![Geometric diagram showing a semicircle with diameter AB. A vertical line segment NM is drawn from N to M on AB, where M is the midpoint. A small orange square is placed at M, indicating a right angle.](30a26f2d17ca95672702bf50fb4f0242_img.jpg)

Geometric diagram showing a semicircle with diameter AB. A vertical line segment NM is drawn from N to M on AB, where M is the midpoint. A small orange square is placed at M, indicating a right angle.

![Two overlapping triangles, one orange and one blue, illustrating geometric concepts.](64662465bba247703fdec49c8f3309f9_img.jpg)

Two overlapping triangles, one orange and one blue, illustrating geometric concepts.

![Logo of SP (Sư Phạm) publishing house.](5fb340ad68b0c71df0b56698b137e35b_img.jpg)

Logo of SP (Sư Phạm) publishing house.

NHÀ XUẤT BẢN ĐẠI HỌC SƯ PHẠM

## CHƯƠNG II

## Phương pháp thống kê

### trong nghiên cứu khoa học giáo dục

### I. Các khái niệm cơ bản về thống kê toán học

#### 1. Đại cương về thống kê toán

Cho X là tập hợp (hữu hạn hoặc vô hạn) các đối tượng nào đó. Giả sử ta cần khảo sát một tính chất đặc trưng nào đó của các đối tượng trong tập hợp X (có thể là một đặc tính sinh học, một số đo, một chỉ số,...).

Có hai cách giải quyết yêu cầu nói trên:

– Cách thứ nhất: khảo sát lần lượt từng đối tượng của tập X về tính chất đặc trưng mà ta quan tâm để từ đó rút ra kết luận;

– Cách thứ hai: chọn ngẫu nhiên một số đối tượng đại diện theo một tiêu chí nào đó của tập X để khảo sát. Từ đó ta rút ra kết luận cần thiết.

Trong thực tế, làm theo cách thứ nhất thường gặp nhiều khó khăn: tổn kém về thời gian và vật chất, trong trường hợp các đối tượng được khảo sát bị hỏng sau mỗi lần khảo sát thì kết quả khảo sát sẽ không còn ý nghĩa. Vì vậy người ta thường phải chọn cách làm thứ hai.

Trong trường hợp này, ta gọi tập các đối tượng được chọn ra để khảo sát là tập mẫu, số phần tử của tập mẫu gọi là kích thước mẫu. Việc chọn từ tập hợp X ra các phần tử để khảo sát ta gọi là phép lấy mẫu. Dãy kết quả thu được trong khảo sát gọi là dãy số liệu quan sát. Tập X gọi là tập tổng quát.

**Ví dụ 2.1.** Ta cần xác định trọng lượng của các gói bánh xuất xưởng của một phân xưởng sản xuất bánh kẹo. Người ta lấy ngẫu nhiên 50 gói bánh từ lô hàng xuất xưởng của phân xưởng đó. Lần lượt cân từng gói. Kết quả ta thu được 50 số liệu về trọng lượng của các gói bánh này.

Ở đây: Tập tất cả các gói bánh trong lô hàng xuất xưởng của phân xưởng đó là tập tổng quát; 50 gói bánh được chọn ra để khảo sát là tập mẫu; số 50 là kích thước mẫu và 50 số liệu về trọng lượng của các gói bánh là dãy số liệu quan sát.

#### 2. Phương pháp chọn mẫu

Trong thực tế ta thường gặp hai cách chọn mẫu dưới đây:

a) *Chọn ngẫu nhiên có hoàn lại*: Theo cách lấy mẫu này thì sau khi lấy ngẫu nhiên một phần tử từ tập hợp tổng quát và khảo sát, ta trả lại phần tử đó vào tập hợp tổng quát trước khi chọn tiếp phần tử thứ hai (không loại trừ khả năng lần sau chọn lại phần tử đã chọn trước đó).

b) *Chọn ngẫu nhiên không hoàn lại*: Trong cách lấy mẫu này, ta không trả lại phần tử đã lấy ra vào tập tổng quát trước khi lấy tiếp phần tử khác.

**Chú ý:**

1. Vì ta cần cù vào kết quả khảo sát trên tập mẫu để rút ra kết luận cần thiết cho toàn bộ tập tổng quát về tính chất đặc trưng cần khảo sát nên các phần tử của tập mẫu phải đại diện một cách đúng đắn cho tập tổng quát.

2. Khi số phần tử của tập tổng quát đủ lớn thì sự sai khác trong kết quả khảo sát giữa hai cách chọn mẫu là không đáng kể.

#### 3. Hàm phân phối mẫu

**Định nghĩa 2.1.** Giả sử từ tập tổng quát X ta chọn tập mẫu có kích thước  $n$ . Khảo sát lần lượt từng phần tử của tập mẫu, ta nhận được dãy số liệu:

$$X_1, X_2, \dots, X_n.$$

Ta gọi dãy này là dãy các số liệu thống kê. Không làm mất tính tổng quát, ta có thể giả sử dãy đó sắp xếp theo giá trị tăng dần hay dãy không giảm (nếu không, ta sắp xếp lại thứ tự). Với mỗi số thực  $x$ , gọi  $n_x$  là số các số liệu trong dãy số liệu thống kê nói trên nhỏ hơn  $x$ .

Ta gọi hàm số  $F_n(x)$  xác định bởi quy tắc:

$$F_n(x) = \frac{n_x}{n}, \text{ với mỗi số thực } x,$$

là hàm phân phối mẫu (hay hàm phân phối thực nghiệm).

**Ví dụ 2.2.** Để xác định chiều cao trung bình của các cây bạch đàn trong một khu rừng bạch đàn, người ta chọn ngẫu nhiên 40 cây trong khu rừng đó. Do chiều cao từng cây và nhận được kết quả trong bảng sau:

| Chiều cao | 8m | 8,5m | 9m | 11m |
|-----------|----|------|----|-----|
| Số cây    | 5  | 12   | 15 | 8   |

Vậy bảng trên là dãy số liệu thống kê nhận được từ quan sát trên tập mẫu gồm 40 cây bạch đàn chọn ngẫu nhiên trong khu rừng bạch đàn đó.

Hàm phân phối mẫu được xác định bởi quy tắc sau:

$$F(x) = \begin{cases} 0, & \text{nếu } x < 8 \\ \frac{5}{40}, & \text{nếu } 8 \le x < 8.5 \\ \frac{12}{40}, & \text{nếu } 8.5 \le x < 9 \\ \frac{15}{40}, & \text{nếu } 9 \le x < 11 \\ \frac{8}{40}, & \text{nếu } x \ge 11 \end{cases} \quad F(x) = \begin{cases} 0, & \text{nếu } x \le 8 \\ \frac{5}{40}, & \text{nếu } 8 < x \le 8.5 \\ \frac{17}{40}, & \text{nếu } 8.5 < x \le 9 \\ \frac{32}{40}, & \text{nếu } 9 < x \le 11 \\ 1, & \text{nếu } x > 11 \end{cases}$$

#### 4. Đa giác tần suất và tổ chức đồ tần suất

Giả sử trong dãy  $n$  số liệu thống kê có  $k$  giá trị đôi một khác nhau:

$x_1, x_2, \dots, x_k$ ,

trong đó  $x_j$  xuất hiện trong dãy với tần số  $k_j$  sao cho:

$$k_1 + k_2 + \dots + k_k = n.$$

Ta gọi  $k_j$  là tần số và  $W_j = \frac{k_j}{n}$  là tần suất của  $x_j$  trong quan sát nói trên.

**Định nghĩa 2.2.** Ta gọi đường gấp khúc nối các điểm  $[x_1; W_1], [x_2; W_2], \dots, [x_k; W_k]$  trong mặt phẳng toạ độ (Oxy) là **đa giác tần suất** của mẫu trên.

**Ví dụ 2.3.** Đa giác tần suất của mẫu quan sát trong ví dụ 2.2 là đường gấp khúc nối các điểm:  $[8; 1/8]; [8.5; 3/10]; [9; 3/8]$  và  $[11; 1/5]$ .

![](9df11121dce75cf8f86a97e7d2840bd5_img.jpg)

Figure showing the polygon of frequencies (Đa giác tần suất) for the sample data. The horizontal axis represents the value  $x$  (from 8 to 11) and the vertical axis represents the frequency  $W$  (from 0 to 1). The polygon connects the points  $(8, 1/8)$ ,  $(8.5, 3/10)$ ,  $(9, 3/8)$ , and  $(11, 1/5)$ .

Ta chia đoạn  $[x_1; x_k]$  thành  $m$  phần bằng nhau, mỗi phần có độ dài:

$$h = \frac{x_k - x_1}{m}$$

Gọi  $T_i$  là tần suất các quan sát nằm trong khoảng thứ  $i$ , với  $i = 1, 2, \dots, m$ , tức là:

$$T_i = \frac{\text{Số quan sát trong khoảng } (x_i; x_i + h]}{n}$$

**Định nghĩa 2.3.** Tổ chức đồ tần suất là một đa giác hình bậc thang lập nên bởi các hình chữ nhật có đáy bằng khoảng chia thứ  $i$  trên trục hoành, chiều cao bằng tỉ số  $\frac{T_i}{h}$ , với  $i = 1, 2, \dots, m$ .

**Ví dụ 2.4.** Hãy thiết lập tổ chức đồ tần suất của quan sát trong ví dụ 2.2 với  $m = 4$ .

Ta có:

$$h = \frac{11 - 8}{4} = 0,75;$$

$$T_1 = \frac{\text{số } x_i \in [8; 8,75)}{40} = 0,425;$$

$$T_2 = \frac{\text{số } x_i \in [8,75; 9,5)}{40} = 0,375;$$

$$T_3 = \frac{\text{số } x_i \in [9,5; 10,25)}{40} = 0;$$

$$T_4 = \frac{\text{số } x_i \in [10,25; 11]}{40} = 0,2.$$

$$\frac{T_1}{0,75} = \frac{0,425}{0,75} = 0,57; \quad \frac{T_2}{0,75} = \frac{0,375}{0,75} = 0,5; \quad \frac{T_3}{0,75} = 0; \quad \frac{T_4}{0,75} = 0,4.$$

![Histogram showing the frequency distribution of data. The x-axis is labeled x, and the y-axis is labeled y. The bars represent the frequency of observations in intervals: [8; 8.75), [8.75; 9.5), [9.5; 10.25), and [10.25; 11]. The frequencies are 0.425, 0.375, 0, and 0.2, respectively. The height of the bars is indicated by dashed lines corresponding to the values 0.57, 0.5, 0, and 0.4 on the y-axis.](d6226b6d22b1babc1eeeb93e07cc9cc4_img.jpg)

Histogram showing the frequency distribution of data. The x-axis is labeled x, and the y-axis is labeled y. The bars represent the frequency of observations in intervals: [8; 8.75), [8.75; 9.5), [9.5; 10.25), and [10.25; 11]. The frequencies are 0.425, 0.375, 0, and 0.2, respectively. The height of the bars is indicated by dashed lines corresponding to the values 0.57, 0.5, 0, and 0.4 on the y-axis.

#### 5. Trung bình mẫu và phương sai mẫu

**Định nghĩa 2.4.** Giả sử  $x_1, x_2, \dots, x_n$  là dãy số liệu thống kê thu được từ một quan sát trên tập mẫu có kích thước  $n$ . Ta gọi số:

$$a) \bar{X}_n = \frac{x_1 + x_2 + \dots + x_n}{n}$$

là *trung bình* (hay *kì vọng*) *mẫu* trong quan sát nói trên.

$$b) S_n^2 = \frac{1}{n} \sum_{k=1}^{n} (x_k - \bar{X}_n)^2 \text{ là phương sai mẫu.}$$

$$c) S_n = \sqrt{\frac{1}{n} \sum_{k=1}^{n} (x_k - \bar{X}_n)^2} \text{ là độ lệch chuẩn mẫu.}$$

$$d) E_n = \frac{\sum_{k=1}^{n} |x_k - \bar{X}_n|}{n} \text{ là độ lệch tuyệt đối mẫu.}$$

**Chú ý:** Nếu dãy số liệu thống kê nhận  $k$  giá trị khác nhau  $x_1, x_2, \dots, x_k$  với  $n_1, n_2, \dots, n_k$  tương ứng thì *kì vọng* và *phương sai mẫu* được xác định bởi công thức:

$$\bar{X}_n = \frac{x_1 n_1 + x_2 n_2 + \dots + x_k n_k}{n}$$

$$S_n^2 = \frac{1}{n} \sum_{i=1}^{k} (x_i - \bar{X}_n)^2 n_i$$

**Ví dụ 2.5.** Trung bình mẫu trong Ví dụ 2.2 được xác định bởi công thức:

$$\bar{X}_{40} = \frac{8 \times 5 + 8,5 \times 12 + 9 \times 15 + 11 \times 8}{40} = 9,125.$$

Phương sai mẫu được xác định bởi công thức:

$$S_{40}^2 = \frac{(8-9,125)^2 \times 5 + (8,5-9,125)^2 \times 12 + (9-9,125)^2 \times 15 + (11-9,125)^2 \times 8}{40} \approx 0,98.$$

#### 6. Trung vị mẫu

**Định nghĩa 2.5.** *Trung vị mẫu* là số liệu nằm chính giữa dãy số liệu thống kê (sau khi đã sắp xếp các số liệu từ nhỏ đến lớn hoặc ngược lại) nếu kích thước mẫu  $n$  là số lẻ; là số trung bình cộng của  $x_m$  và  $x_{m+1}$  nếu  $n$  là số chẵn,  $n = 2m$ .

Một mẫu là giá trị trong dãy số liệu có tần số xuất hiện lớn nhất trong dãy số liệu đó.

Ví dụ 2.6. Mẫu trong ví dụ 2.2 có trung vị bằng 9 (vì kích thước mẫu  $n = 40$  và các giá trị thứ hai mươi và hai mươi một đều bằng 9); có một cũng bằng 9 (vì tần số xuất hiện của 9 trong dãy là lớn nhất (bằng 15)).

#### 7. Mô men mẫu

Định nghĩa 2.6. Ta gọi số:

a)  $M_k = \frac{1}{n} \sum_{i=1}^{n} x_i^k$  là mô men góc mẫu bậc  $k$ ;

b)  $C_k = \frac{1}{n} \sum_{i=1}^{n} (x_i - \bar{X}_n)^k$  là mô men trung tâm mẫu bậc  $k$ .

#### 8. Hệ số tương quan mẫu

Định nghĩa 2.7. Giả sử  $x_1, x_2, \dots, x_n$  và  $y_1, y_2, \dots, y_n$  là hai dãy số liệu thống kê thu được từ kết quả quan sát trên hai tập mẫu đều có kích thước  $n$ . Ta gọi số:

$$r = \frac{\sum_{k=1}^{n} x_k y_k - \left(\sum_{k=1}^{n} x_k\right) \left(\sum_{k=1}^{n} y_k\right)}{\sqrt{\left[n \sum_{k=1}^{n} x_k^2 - \left(\sum_{k=1}^{n} x_k\right)^2\right] \left[n \sum_{k=1}^{n} y_k^2 - \left(\sum_{k=1}^{n} y_k\right)^2\right]}}$$

là hệ số tương quan mẫu.

Chú ý: Đối khi ta tính hệ số tương quan mẫu bằng công thức sau:

$$r = \frac{\sum_{k=1}^{n} (x_k - \bar{X}_n)(y_k - \bar{Y}_n)}{\sqrt{\left[\sum_{k=1}^{n} (x_k - \bar{X}_n)^2\right] \left[\sum_{k=1}^{n} (y_k - \bar{Y}_n)^2\right]}}$$

Ví dụ 2.7. Trong một thí nghiệm trên bảy con chuột bạch để khảo sát sự tương quan giữa thời gian sống sót  $y$  của chuột và liều độc  $x$ , ta được các số liệu trong bảng sau:

| x | 0    | 1 | 2 | 3    | 4   | 5   | 6    |
|---|------|---|---|------|-----|-----|------|
| y | 4,25 | 3 | 3 | 1,75 | 1,5 | 0,5 | 0,25 |

Hãy tính hệ số tương quan  $r$  giữa  $x$  và  $y$ .

Bảng tính toán trực tiếp ta được:

$$\bar{X}_7 = 3; \bar{Y}_7 = 2,035;$$

$$\sum_{k=1}^{7} (x_k - \bar{X}_7)(y_k - \bar{Y}_7) = -18,5; \sum_{k=1}^{7} (x_k - \bar{X}_7)^2 = 28; \sum_{k=1}^{7} (y_k - \bar{Y}_7)^2 = 12,676.$$

Hệ số tương quan là:

$$r = \frac{-18,5}{\sqrt{28 \times 12,676}} = -0,98.$$

### II. Ước lượng tham số

Trong nghiên cứu khoa học, trong y tế, trong lao động sản xuất,... ta thường gặp và phải xử lý các bài toán dưới đây:

(i) Xác định khoảng ước lượng số trung bình  $a$  của các phần tử thuộc một tập tổng quát  $X$  cho trước dựa trên kết quả các số liệu quan sát trên một tập mẫu (có kích thước  $n$ ) lấy ra từ tập  $X$ .

(ii) Xác định khoảng ước lượng tần số xuất hiện của biến cố  $A$  trong tập tổng quát  $X$  cho trước dựa trên kết quả các số liệu quan sát trên tập mẫu (có kích thước  $n$ ) lấy ra từ tập  $X$ .

Trong lý thuyết thống kê toán, người ta đã tìm ra những công cụ để xử lý các bài toán nêu trên kèm theo độ tin cậy nhất định.

Trong mục này ta giới thiệu các công cụ này và thực hành vận dụng để xử lý những bài toán nêu trên gặp trong thực tế.

#### 1. Ước lượng và khoảng tin cậy của số trung bình hay kĩ vĩng a

Để xử lý những bài toán dạng này, ta sử dụng kết quả dưới đây (đã được chứng minh bằng lý thuyết thống kê toán):

Nếu kết quả quan sát trên một tập mẫu có kích thước  $n$  lấy từ một tổng thể có phân phối chuẩn có phương sai  $\sigma^2$  chưa biết, ta nhận được dãy các số liệu  $X_1, X_2, X_3, \dots, X_n$  thì số trung bình  $a$  của tổng thể có khoảng ước lượng (với mức ý nghĩa  $\alpha$  hoặc độ tin cậy  $\gamma = 1 - \alpha$ ) là:

$$\bar{X}_n - t_\alpha \frac{S_n^*}{\sqrt{n}} < a < \bar{X}_n + t_\alpha \frac{S_n^*}{\sqrt{n}},$$

trong đó hệ số  $t_\alpha$ :

- Đọc tra trong bảng phân phối chuẩn<sup>1</sup> sao cho  $\Phi(t_\alpha) = 1 - \frac{\alpha}{2}$ , nếu  $n \ge 30$ ;

- Đọc tra trong bảng phân phối Student<sup>2</sup> với  $n-1$  bậc tự do, nếu  $n < 30$ .

$S_n^{*2}$  là phương sai suy rộng được xác định bởi công thức:

$$S_n^{*2} = \frac{1}{n-1} \sum_{k=1}^{m} (X_k - \bar{X}_n)^2.$$

**Chú ý:** Trong phần dưới đây, nếu không nói gì thêm thì các tập tống quát mà ta xét đều có phân phối chuẩn.

**Ví dụ 2.8.** Để xác định chiều cao trung bình của các cây bạch đàn trong một khu rừng bạch đàn, người ta chọn ngẫu nhiên 50 cây trong khu rừng đó rồi đo chiều cao từng cây. Kết quả nhận được bảng số liệu sau:

| Chiều cao | 8m | 9m | 11m | 12m |
|-----------|----|----|-----|-----|
| Số cây    | 6  | 15 | 9   | 20  |

Biết rằng chiều cao các cây bạch đàn có phân phối chuẩn, tìm khoảng ước lượng chiều cao trung bình  $a$  của các cây bạch đàn trong khu rừng đó với độ tin cậy 99%.

Sau đó nếu ý nghĩa thực tiễn của các số liệu tìm được.

**Giải:**

Tra bảng phân phối chuẩn ta được  $t_{0,01} = 2,576$ . Ta có:

$$\bar{X}_{50} = \frac{1}{50} (8 \times 6 + 9 \times 15 + 11 \times 9 + 12 \times 20) = 10,44$$

$$S_{50}^{*2} = \frac{1}{49} [(8-10,44)^2 \times 6 + (9-10,44)^2 \times 15 + (11-10,44)^2 \times 9$$

$$+ (12-10,44)^2 \times 20] = 2,41.$$

Áp dụng công thức ta được khoảng ước lượng của chiều cao trung bình  $a$  của các cây bạch đàn trong khu rừng đó với độ tin cậy 99% là:

$$10,44 - 2,576 \sqrt{\frac{2,41}{50}} < a < 10,44 + 2,576 \sqrt{\frac{2,41}{50}}$$

$$9,88 < a < 11 \text{ hay } a \in (9,88\text{m}; 11\text{m}).$$

<sup>1,2</sup> Xem phần phụ lục.

Ý nghĩa thực tiễn của các số liệu tìm được là: Không dưới 99% số cây bạch đan trong khu rừng đó có chiều cao nằm trong khoảng 9,88m đến 11m, hay nói cách khác, số cây có chiều cao nhỏ hơn hoặc bằng 9,88m hay lớn hơn hoặc bằng 11m chiếm không quá 1%.

Ví dụ 2.9. Để xác định trọng lượng trung bình của các gói kẹo xuất xưởng, người ta chọn ngẫu nhiên 28 gói trong lô hàng xuất xưởng, cân từng gói và kết quả nhận được bảng số liệu sau:

| Trọng lượng | 285g | 290g | 295g | 300g | 310g |
|-------------|------|------|------|------|------|
| Số gói      | 2    | 5    | 13   | 3    | 5    |

Biết rằng trọng lượng của các gói kẹo có phân phối chuẩn, tìm khoảng ước lượng trọng lượng trung bình a của gói kẹo xuất xưởng của phân xưởng đó với độ tin cậy 90%.

Sau đó nêu ý nghĩa thực tiễn của các số liệu vừa tìm được.

**Giải:** Tra bảng phân phối Student ta được  $t_{0,90} = 1,71$ . Ta có:

$$\bar{X}_{28} = \frac{1}{28}(285 \times 2 + 290 \times 5 + 295 \times 13 + 300 \times 3 + 310 \times 5) \approx 296,61.$$

$$S_{28}^2 = \frac{1}{27}[(285 - 296,61)^2 \times 2 + (290 - 296,61)^2 \times 5 + (295 - 296,61)^2 \times 13 + (300 - 296,61)^2 \times 3 + (310 - 296,61)^2 \times 5] = 53,80.$$

Áp dụng công thức ta được khoảng ước lượng trọng lượng trung bình a của gói kẹo xuất xưởng của phân xưởng đó với độ tin cậy 90% là:

$$296,61 - 1,71 \sqrt{\frac{53,8}{28}} < a < 296,61 + 1,71 \sqrt{\frac{53,8}{28}}$$

$$294,24 < a < 298,98 \text{ hay } a \in (294,24g; 298,98g).$$

Ý nghĩa thực tiễn của các số liệu tìm được là: Không dưới 90% số gói kẹo xuất xưởng có trọng lượng nằm trong khoảng từ 294,24g đến 298,98g, hay nói cách khác, số gói kẹo có trọng lượng nhỏ hơn hoặc bằng 294,24g hay lớn hơn hoặc bằng 298,98g chiếm không quá 10%.

#### 2. Ước lượng và khoảng tin cậy của tỉ lệ hay xác suất p

Bài toán này thường gặp trong nhiều lĩnh vực khác nhau: chẳng hạn ước lượng tỉ lệ phế phẩm trong lô hàng xuất xưởng của một cơ sở sản xuất nào đó, tỉ lệ học sinh năm được luật về an toàn giao thông, tỉ lệ người mù chữ

ở một địa phương nào đó, tỉ lệ người khởi bệnh khi dùng một loại thuốc nào đó,...

Nói chung, ở đây ta lấy mẫu từ tổng thể có phân phối nhị thức có xác suất chưa biết  $p$  (chỉ xác suất hòng của một sản phẩm, chỉ xác suất năm được luật giao thông khi kiểm tra ngẫu nhiên một học sinh nào đó, chỉ xác suất khởi bệnh khi sử dụng loại thuốc,...). Trong phần này, ta tìm khoảng ước lượng của xác suất hay tỉ lệ  $p$  nói trên.

Để xử lý những bài toán dạng này, ta sử dụng kết quả dưới đây (đã được chứng minh bằng lý thuyết thống kê toán):

Nếu  $W$  là tần suất của biến cố  $A$  quan sát được trên một tập mẫu có kích thước  $n$  ( $W = \frac{m}{n}$ , với  $m$  là số lần xuất hiện biến cố  $A$  trong  $n$  phép thử) thì tỉ lệ hay xác suất  $p$  chưa biết của biến cố  $A$  trong tổng thể có khoảng ước lượng (với mức ý nghĩa  $\alpha$  hoặc độ tin cậy  $\gamma = 1 - \alpha$ ) là:

$$W - t_{\alpha} \sqrt{\frac{(1-W)}{n}} < p < W + t_{\alpha} \sqrt{\frac{W(1-W)}{n}},$$

trong đó hệ số  $t_{\alpha}$  được tra trong bảng phân phối chuẩn sao cho  $\Phi(t_{\alpha}) = 1 - \frac{\alpha}{2}$ .

**Ví dụ 2.10.** Để xác định tỉ lệ công nhân mắc bệnh nghề nghiệp trong một khu công nghiệp khai thác mỏ, người ta kiểm tra sức khoẻ cho 120 công nhân chọn ngẫu nhiên trong khu mỏ đó. Kết quả có 48 người mắc bệnh nghề nghiệp. Tìm khoảng ước lượng của tỉ lệ người mắc bệnh nghề nghiệp trong khu mỏ đó, với độ tin cậy 95%.

Sau đó nếu ý nghĩa thực tiễn của các số liệu vừa tìm được.

**Giải:**

Ta có:  $W = \frac{48}{120} = 0,40$ ;  $t_{0,05} = 1,96$ .

Áp dụng công thức ta có khoảng ước lượng của  $p$  với độ tin cậy 95% là:

$$0,40 - 1,96 \sqrt{\frac{0,40(1-0,40)}{120}} < p < 0,40 + 1,96 \sqrt{\frac{0,40(1-0,40)}{120}}$$

$0,3123 < p < 0,4877$  hay  $p \in (31,23\%; 48,77\%)$ .

Ý nghĩa thực tiễn của các số liệu trên đây là: Không dưới 95% số lân thư có tỉ lệ người mắc bệnh nằm trong khoảng từ 31,23% đến 48,77% hay số lân thư có tỉ lệ người mắc bệnh nằm ngoài khoảng trên chiếm không quá 5%.

Ví dụ 2.11. Để xác định tỉ lệ học sinh yêu thích môn Toán trong một trường tiểu học, người ta phát phiếu điều tra cho 160 học sinh của trường đó. Kết quả có 104 em trả lời thích học Toán và 56 em trả lời không thích học Toán vì toán khó.

a) Với độ tin cậy 99% hãy cho biết có ít nhất bao nhiêu phần trăm học sinh của trường đó thích học Toán?

b) Với độ tin cậy 85% hãy cho biết có tối đa bao nhiêu phần trăm học sinh của trường đó không thích học Toán?

Sau đó nêu ý nghĩa thực tiễn của các số liệu vừa tìm được.

Giải: Ta có:

$$W = \frac{104}{160} = 0,65; \bar{W} = 1 - W = 0,35; t_{0,01} = 2,576; t_{0,15} = 1,44.$$

a) Áp dụng công thức ta có khoảng ước lượng của  $p$  với độ tin cậy 99% là:

$$0,65 - 2,576 \sqrt{\frac{0,65(1-0,65)}{160}} < p < 0,65 + 2,576 \sqrt{\frac{0,65(1-0,65)}{160}}$$

$$0,5529 < p < 0,7471 \text{ hay } p \in (55,29\%; 74,71\%).$$

Vậy với độ tin cậy 99% ta có thể khẳng định có ít nhất 55,29% số học sinh của trường đó thích học Toán.

Ý nghĩa thực tiễn của các số liệu trên đây là: Không dưới 99% lân khảo sát sẽ có kết quả tỉ lệ học sinh thích học Toán tối thiểu 55,29%.

b) Áp dụng công thức ta có khoảng ước lượng của  $p$  với độ tin cậy 85% là:

$$0,35 - 1,44 \sqrt{\frac{0,35(1-0,35)}{160}} < p < 0,35 + 1,44 \sqrt{\frac{0,35(1-0,35)}{160}}$$

$$0,2957 < p < 0,4043 \text{ hay } p \in (29,57\%; 40,43\%).$$

Vậy với độ tin cậy 85% ta có thể khẳng định có tối đa 40,43% số học sinh của trường đó không thích học Toán.

Ý nghĩa thực tiễn của các số liệu trên đây là: Không quá 85% lân khảo sát sẽ có kết quả tỉ lệ học sinh không thích học Toán tối đa là 40,43%.

Chú ý: Khi xử lý những bài toán mà kích thước mẫu quan sát quá bé ( $n \le 10$ ) và những bài toán tần suất quá nhỏ ( $W \le 0,1$ ) hoặc quá lớn

( $W \ge 0,9$ ) ta có thể sử dụng những kết quả đã cho trong bảng  $3^1$  và bảng  $4^2$  việc tính toán sẽ đơn giản hơn.

**Ví dụ 2.12.** Điều trị cho 8 bệnh nhân bằng một loại thuốc A, kết quả có 5 người khỏi bệnh. Với độ tin cậy 95% hãy cho ước lượng về tỉ lệ bệnh nhân khỏi bệnh khi được điều trị bằng loại thuốc A.

**Giải:**

→ Tra trong bảng 3 ứng với cột  $x = 3$  và  $n = 8$  ta được giới hạn dưới  $p_1 = 24,5\%$  và giới hạn trên  $p_2 = 91,5\%$ .

Vậy tỉ lệ người khỏi bệnh khi điều trị bằng loại thuốc A nằm trong khoảng từ 24,5% đến 91,5%.

**Ví dụ 2.13.** Để xác định tỉ lệ người mù chữ ở một tỉnh X, người ta kiểm tra ngẫu nhiên 12 000 người trong độ tuổi đi học, kết quả có 36 người không biết chữ. Tìm khoảng ước lượng của tỉ lệ người không biết chữ ở tỉnh X với độ tin cậy 95%.

**Giải:**

Gọi  $p$  là tỉ lệ người không biết chữ ở tỉnh X. Ta ước lượng  $p$  bằng tần suất  $W = \frac{36}{12000} = 0,003$ . Ta tra bảng 4:

Nhìn vào dòng 30, cột 6 trong bảng ta được hai số liệu: 25,2 và 49,8.

Cận dưới  $p_1$  và cận trên  $p_2$  của khoảng ước lượng được xác định như sau:

$$np_1 = 25,2. \text{ Suy ra } p_1 = 25,2 : 12000 = 0,0021.$$

$$np_2 = 49,8. \text{ Suy ra } p_2 = 49,8 : 12000 = 0,0042.$$

Vậy với độ tin cậy 95% ta có thể khẳng định tỉ lệ người không biết chữ trong tỉnh X trong khoảng từ 0,21% đến 0,42%.

### III. Kiểm định giả thiết thống kê

Trong phần này ta giải quyết các bài toán:

– So sánh số trung bình của mẫu quan sát với số trung bình theo lý thuyết để rút ra kết luận: Độ sai lệch là đáng kể hay không?

– So sánh tần suất của biến cố A trong mẫu quan sát với xác suất của biến cố A theo lý thuyết để rút ra kết luận: Độ sai lệch là đáng kể hay không?

– So sánh hai số trung bình trên hai mẫu quan sát để rút ra kết luận: Hai số trung bình theo lý thuyết sai lệch là đáng kể hay không? Số nào lớn hơn?

<sup>1,2</sup> Xem phần phụ lục.

— So sánh hai tần suất của biến cố A trong hai mẫu quan sát để rút ra kết luận: Hai xác suất của biến cố A theo lý thuyết sai lệch có đáng kể hay không? Số nào lớn hơn?

Thông tin duy nhất ta có ở đây là các số liệu quan sát trên tập mẫu. Đề giải quyết các bài toán dạng này, ta đưa ra:

*Trường hợp 1:*

**Giả thiết H:**  $a = a_0$ : Số trung bình mẫu và số trung bình theo lý thuyết có độ sai lệch không đáng kể (chấp nhận giả thiết H).

Hay:

**Đối thiết K:**  $a \neq a_0$ : Số trung bình mẫu và số trung bình theo lý thuyết có độ sai lệch đáng kể (bác bỏ giả thiết H và chấp nhận đối thiết K).

*Trường hợp 2:*

**Giả thiết H:**  $p = p_0$ : Tần suất của biến cố A trong quan sát trên tập mẫu và xác suất của biến cố A theo lý thuyết có độ sai lệch không đáng kể (chấp nhận giả thiết H).

**Đối thiết K:**  $p \neq p_0$ : Tần suất của biến cố A trong quan sát trên tập mẫu và xác suất của biến cố A theo lý thuyết có độ sai lệch đáng kể (bác bỏ giả thiết H và chấp nhận đối thiết K).

Khi bác bỏ hay chấp nhận giả thiết H ta có thể mất phải hai loại sai lầm sau đây:

- Sai lầm loại I: Ta bác bỏ giả thiết H trong khi H đúng.
- Sai lầm loại II: Ta chấp nhận giả thiết H trong khi H sai.

Ta cố gắng hạn chế tối thiểu cả hai loại sai lầm này. Nhưng khi kích thước mẫu cố định thì điều này khó khả thi. Do vậy người ta thường cho phép được mức sai lầm loại I với xác suất  $\alpha$  (thường gọi là mức ý nghĩa  $\alpha$  hay độ tin cậy  $1 - \alpha$ ). Sau đó hạn chế đến mức tối thiểu việc mức sai lầm loại II.

#### 1. Kiểm định giá trị trung bình a của tổng thể (so sánh số trung bình quan sát với số trung bình lý thuyết)

##### a) Kiểm định hai phía

Trong thực tế ta thường gặp vấn đề sau đây: Qua quan sát trên một tập mẫu có kích thước  $n$  (lấy từ tổng thể X nào đó) ta nhận được số trung bình mẫu  $\bar{X}$ . Mặt khác, ta đã biết số trung bình của các phân tử trong tập tổng quát

theo lí thuyết là  $a$ . Từ đây này sinh câu hỏi: Sự sai lệch giữa trung bình mẫu  $\bar{X}$  và trung bình theo lí thuyết  $a$  là đáng kể hay không?

Để xử lý những bài toán dạng này, ta sử dụng kết quả sau đây:

Giả sử kết quả quan sát trên tập mẫu có kích thước  $n$  với phương sai chưa biết ta nhận được dãy số liệu  $X_1, X_2, \dots, X_n$ .

Ta kiểm định giả thiết  $H: a = a_0$  với đối thiết  $K: a \neq a_0$  và mức ý nghĩa  $\alpha$  (hay độ tin cậy  $1 - \alpha$ ).

Trước hết ta tính:

$M = \frac{|\bar{X}_n - a_0| \sqrt{n}}{S_n^*}$ , trong đó  $\bar{X}_n$  là trung bình mẫu,  $S_n^*$  là độ lệch chuẩn

của mẫu, xác định bởi công thức:

$$S_n^* = \frac{1}{n-1} \sum_{k=1}^{n} (X_k - \bar{X})^2.$$

– Nếu  $M < t_\alpha$  thì ta chấp nhận giả thiết  $H: a = a_0$  với mức ý nghĩa  $\alpha$  (độ tin cậy  $1 - \alpha$ ).

– Nếu  $M \ge t_\alpha$  thì ta bác bỏ giả thiết  $H$  hay chấp nhận đối thiết  $K: a \neq a_0$ .

Ở đây:

– Nếu  $n \ge 30$  thì  $t_\alpha$  tra trong bảng phân phối chuẩn sao cho  $\Phi(t_\alpha) = 1 - \frac{\alpha}{2}$ .

– Nếu  $n < 30$  thì  $t_\alpha$  tra trong bảng phân phối Student với  $n - 1$  bậc tự do.

Ví dụ 2.14. Trọng lượng tiêu chuẩn của một gói kẹo xuất xưởng là 300g. Người ta chọn ngẫu nhiên 61 gói kẹo trong lô hàng xuất xưởng đem cân và nhận được trọng lượng trung bình của 61 gói đó là 299,3g và độ lệch chuẩn  $S_{61}^* = 7,2$ . Hỏi với mức ý nghĩa  $\alpha = 0,05$  trọng lượng của các gói kẹo xuất xưởng có đạt tiêu chuẩn hay không?

Giải:

Ở đây ta có giả thiết:  $a = 300$  và đối thiết:  $a \neq 300$ .

Vì  $n > 30$  nên tra bảng phân phối chuẩn ta được  $t_{0,05} = 1,96$ .

Áp dụng công thức ta có:

$$M = \frac{|299,3 - 300| \sqrt{61}}{7,2} \approx 0,76.$$

Vì  $0,76 < 1,96$  nên ta chấp nhận giả thiết H, tức là trọng lượng trung bình của các gói kẹo xuất xưởng bằng 300g với độ tin cậy 95%.

Ý nghĩa thực tiễn của các số liệu trên đây là: Số gói kẹo có trọng lượng khác 300g trong lô hàng xuất xưởng chiếm không quá 5%.

Ví dụ 2.15. Nuôi 15 con gà theo chế độ ăn riêng, sau ba tháng mức tăng trọng lượng của 15 con gà đó như sau:

3kg; 2,8kg; 3kg; 4kg; 2,5kg; 4kg; 3,5kg;

3kg; 4kg; 2kg; 3kg; 4kg; 3,2kg; 3,5kg; 4kg.

Biết mức tăng trọng trung bình của gà theo chế độ ăn bình thường là 2,8kg. Hỏi với độ tin cậy 95%, nếu gà được cho ăn theo chế độ riêng thì mức tăng trọng trung bình có thay đổi hay không?

Giải: Ta có giả thiết H:  $a = 2,8$  và đối thiết K:  $a \neq 2,8$ .

Ở đây ta có  $n = 15 < 30$ , tra bảng phân phối Student ta được  $t_{0,05} = 2,145$ .

Ta có:

$$\begin{aligned}\bar{X}_{15} &= (3 \times 4 + 2,8 + 4 \times 5 + 2,5 + 3,5 \times 2 + 2 + 3,2) : 15 = 3,3 \\S_{15}^2 &= [(3-3,3)^2 \times 4 + (2,8-3,3)^2 + (4-3,3)^2 \times 5 + (2,5-3,3)^2 \\&+ (3,5-3,3)^2 \times 2 + (2-3,3)^2 + (3,2-3,3)^2] : 14 \approx 0,39.\end{aligned}$$

Áp dụng công thức ta có:

$$M = \frac{|3,3 - 2,8| \sqrt{15}}{\sqrt{0,39}} \approx 3,101 > 2,145.$$

Vậy ta bác bỏ giả thiết H mà chấp nhận đối thiết K: Với chế độ ăn riêng, mức tăng trọng trung bình của gà khác 2,8kg với độ tin cậy 95%.

b) Kiểm định một phía khi phương sai chưa biết

Nếu  $\bar{X}_n > a_0$  thì ta kiểm định một phía theo công thức sau đây:

Giả sử kết quả quan sát trên tập mẫu có kích thước  $n$  với phương sai chưa biết ta nhận được dãy số liệu  $X_1, X_2, \dots, X_n$ .

Ta kiểm định giả thiết H:  $a = a_0$  với đối thiết K:  $a > a_0$  và mức ý nghĩa  $\alpha$  (hay độ tin cậy  $1 - \alpha$ ).

Trước hết ta tính:

$M = \frac{(\bar{X}_n - a_0)\sqrt{n}}{S_n^*}$ , trong đó  $\bar{X}_n$  là trung bình mẫu,  $S_n^*$  là độ lệch chuẩn của mẫu, xác định bởi công thức:

$$S_n^* = \frac{1}{n-1} \sum_{k=1}^{n} (X_k - \bar{X})^2.$$

- Nếu  $M < t_\alpha$  thì ta chấp nhận giả thiết H:  $a = a_0$  với mức ý nghĩa  $\alpha$  (độ tin cậy  $1 - \alpha$ ).

- Nếu  $M > t_\alpha$  thì ta bác bỏ giả thiết H hay chấp nhận đối thiết K:  $a > a_0$ .

Ở đây:

- Nếu  $n \ge 30$  thì  $t_\alpha$  tra trong bảng phân phối chuẩn sao cho  $\Phi(t_\alpha) = 1 - \frac{\alpha}{2}$ ;

- Nếu  $n < 30$  thì  $t_\alpha$  tra trong bảng phân phối Student với  $n-1$  bậc tự do.

**Chú ý:** Nếu  $\bar{X}_n < a_0$  thì ta kiểm định một phía theo công thức sau đây:

Kiểm định giả thiết H:  $a = a_0$  với đối thiết K:  $a < a_0$ , ta tính

$$M = \frac{(a_0 - \bar{X}_n)\sqrt{n}}{S_n^*}.$$

- Nếu  $M < t_\alpha$  thì ta chấp nhận giả thiết H:  $a = a_0$  với mức ý nghĩa  $\alpha$  (độ tin cậy  $1 - \alpha$ ).

- Nếu  $M > t_\alpha$  thì ta bác bỏ giả thiết H hay chấp nhận đối thiết K:  $a < a_0$ .

Ở đây:

- Nếu  $n \ge 30$  thì  $t_\alpha$  tra trong bảng phân phối chuẩn sao cho  $\Phi(t_\alpha) = 1 - \frac{\alpha}{2}$ ;

- Nếu  $n < 30$  thì  $t_\alpha$  tra trong bảng phân phối Student với  $n-1$  bậc tự do.

**Ví dụ 2.16.** Trọng lượng tiêu chuẩn của một gói kẹo xuất xưởng là 300g. Người ta chọn ngẫu nhiên 61 gói kẹo trong lô hàng xuất xưởng đem cân và nhận được trọng lượng trung bình của 61 gói đó là 288g và độ lệch

chuẩn  $S_{61}^* = 7,2$ . Hỏi với mức ý nghĩa  $\alpha = 0,05$  trọng lượng của các gói kẹo xuất xưởng có nhẹ hơn trọng lượng tiêu chuẩn hay không?

**Giải:**

Ở đây ta kiểm định giả thiết:  $a = 300$  và đối thiết:  $a < 300$ .

Vì  $n > 30$  nên tra bảng phân phối chuẩn ta được  $t_{0,05} = 1,96$ .

Áp dụng công thức ta có:

$$M = \frac{(300 - 288) \sqrt{61}}{7,2} \approx 13,02.$$

Vì  $13,02 > 1,96$  nên ta bác bỏ giả thiết H và chấp nhận đối thiết K:  $a < a_0$  tức là trọng lượng trung bình của các gói kẹo xuất xưởng nhẹ hơn trọng lượng tiêu chuẩn với độ tin cậy 95%.

**Ví dụ 2.17.** Nuôi 15 con gà theo chế độ ăn riêng, sau ba tháng mức tăng trọng lượn của 15 con gà đó như sau:

3kg; 2,8kg; 3kg; 4kg; 2,5kg; 4kg; 3,5kg;

3kg; 4kg; 2kg; 3kg; 4kg; 3,2kg; 3,5kg; 4kg.

Biết mức tăng trọng trung bình của gà theo chế độ ăn bình thường là 2,8kg. Hỏi với độ tin cậy 95%, nếu gà được cho ăn theo chế độ riêng thì mức tăng trọng trung bình có cao hơn trước hay không?

**Giải:** Ta có giả thiết H:  $a = 2,8$  và đối thiết K:  $a > 2,8$ .

Ở đây ta có  $n = 15 < 30$ , tra bảng phân phối Student ta được  $t_{0,05} = 2,145$ .

Ta có:

$$\bar{X}_{15} = \frac{(3 \times 4 + 2,8 + 4 \times 5 + 2,5 + 3,5 \times 2 + 2 + 3,2)}{15} = 3,3$$

$$S_{15}^2 = \left[ (3-3,3)^2 \times 4 + (2,8-3,3)^2 + (4-3,3)^2 \times 5 + (2,5-3,3)^2 \right. \\ \left. + (3,5-3,3)^2 \times 2 + (2-3,3)^2 + (3,2-3,3)^2 \right] : 14 \approx 0,39.$$

Áp dụng công thức ta có:

$$M = \frac{(3,3 - 2,8) \sqrt{15}}{\sqrt{0,39}} \approx 3,101 > 2,145.$$

Vậy ta bác bỏ giả thiết H mà chấp nhận đối thiết K: Với chế độ ăn riêng, mức tăng trọng trung bình của gà cao hơn 2,8kg.

#### 2. Kiểm định giả thiết về tỉ lệ hay xác suất $p$ (so sánh tỉ lệ hay xác suất thu được từ quan sát với xác suất của biến có $A$ theo lý thuyết)

##### 2.1. Kiểm định hai phía

Giả sử kết quả quan sát trên tập mẫu có kích thước  $n \ge 30$  ta thấy có  $k$  lần xuất hiện biến có  $A$ .

Ta kiểm định tỉ lệ hay xác suất  $p$  của biến có  $A$  với giả thiết  $H: p = p_0$  và đối thiết  $K: p \ne p_0$  và mức ý nghĩa  $\alpha$  (hay độ tin cậy  $1 - \alpha$ ).

Trước hết ta tính:

$$V_{\alpha} = \frac{|W - p_0| \sqrt{n}}{\sqrt{p_0 (1 - p_0)}}, \text{ trong đó } W = \frac{k}{n} \text{ là tỉ lệ hay xác suất của biến có } A \text{ trong quan sát.}$$

– Nếu  $V_{\alpha} < t_{\alpha}$  thì ta chấp nhận giả thiết  $H$  với mức ý nghĩa  $\alpha$  (hay độ tin cậy  $1 - \alpha$ );

– Nếu  $V_{\alpha} \ge t_{\alpha}$  thì ta bác bỏ giả thiết  $H$  hay chấp nhận đối thiết  $K$  với mức ý nghĩa  $\alpha$  (hay độ tin cậy  $1 - \alpha$ ) ở đây  $t_{\alpha}$  tra trong bảng  $1$  sao cho  $\Phi(t_{\alpha}) = 1 - \frac{\alpha}{2}$ .

**Ví dụ 2.18.** Ở một địa phương tỉ lệ mắc bệnh  $A$  đã được xác định nhiều lần là 34%. Sau một đợt điều trị bằng một loại thuốc, người ta kiểm tra lại 120 người thấy còn 24 người mắc bệnh  $A$ .

Hỏi với độ tin cậy 95% tỉ lệ người mắc bệnh  $A$  ở địa phương đó sau khi được điều trị bằng loại thuốc nêu trên có thay đổi không?

**Giải:**

Ở đây ta có  $n = 120$ ;  $W = \frac{24}{120} = 0,2$ ;  $\alpha = 0,05$ .

Tra bảng ta được:  $t_{0,05} = 1,96$ ; giả thiết  $H: p = 0,34$  với đối thiết  $K: \bar{p} \ne 0,34$ .

$$V_{0,05} = \frac{|0,2 - 0,34| \sqrt{120}}{\sqrt{0,34 \cdot 0,66}} \approx 3,24.$$

Vì  $3,24 > 1,96$  nên ta bác bỏ giả thiết  $p = 0,34$ . Vậy tỉ lệ người mắc bệnh  $A$  ở địa phương có thay đổi.

##### 2.2. Kiểm định một phía

Trong công thức trên:

a) Nếu  $W > p_0$  thì ta kiểm định giả thiết  $H: p = p_0$  với đối thiết  $K: p > p_0$  như sau:

+ Nếu  $V = \frac{(W - p_0) \sqrt{n}}{\sqrt{p_0 (1 - p_0)}} > t_\alpha$  thì ta bác bỏ giả thiết  $H: p = p_0$  mà chấp nhận đối thiết  $K: p > p_0$ .

+ Nếu  $V = \frac{(W - p_0) \sqrt{n}}{\sqrt{p_0 (1 - p_0)}} < t_\alpha$  thì ta chấp nhận giả thiết  $H: p = p_0$ .

b) Nếu  $W < p_0$  thì ta kiểm định giả thiết  $H: p = p_0$  với đối thiết  $K: p < p_0$  như sau:

+ Nếu  $V = \frac{(p_0 - W) \sqrt{n}}{\sqrt{p_0 (1 - p_0)}} > t_\alpha$  thì ta bác bỏ giả thiết  $H: p = p_0$  mà chấp nhận đối thiết  $K: p > p_0$ .

+ Nếu  $V = \frac{(p_0 - W) \sqrt{n}}{\sqrt{p_0 (1 - p_0)}} < t_\alpha$  thì ta chấp nhận giả thiết  $H: p = p_0$ .

Trong ví dụ 2.18 ta có:

$$\frac{(0,34 - 0,2) \sqrt{120}}{\sqrt{0,34 (1 - 0,34)}} \approx 3,23 > 1,96.$$

Vậy ta kết luận tỉ lệ người mắc bệnh ở địa phương đó sau một đợt điều trị giảm đi.

#### 3. So sánh hai giá trị trung bình của hai mẫu quan sát

Trong thực tế ta thường phải so sánh hiệu quả của hai phương pháp dạy học tác động tới kết quả học tập của học sinh, hiệu quả của hai phương pháp điều trị trong y học tác động tới hiệu quả khỏi bệnh của bệnh nhân, tác dụng của hai loại phân bón tới năng suất của cây trồng,...

Dưới đây ta giải quyết các bài toán dạng này:

Để so sánh hai số trung bình của hai tổng thể có phân phối chuẩn có cùng phương sai  $\sigma^2$  đưa vào hai trung bình mẫu  $\bar{X}_A$ ,  $\bar{X}_B$  thu được trên hai mẫu quan sát có kích thước  $n_A$  và  $n_B$  (trong đó  $n_A + n_B > 60$ ), ta kiểm định giả thiết  $H: a_1 = a_2$  với đối thiết  $K: a_1 \neq a_2$  với ý nghĩa  $\alpha$  (hay độ tin cậy  $1 - \alpha$ ).

Trước hết ta tính:

$$u = \frac{|\bar{X}_A - \bar{X}_B|}{\sqrt{\frac{S_A^2}{n_A} + \frac{S_B^2}{n_B}}}, \text{ trong đó } S_A \text{ và } S_B \text{ theo thứ tự là độ lệch chuẩn mẫu}$$

quan sát trên các mẫu A và B.

– Nếu  $u < t_\alpha$  thì ta chấp nhận giả thiết H:  $a_1 = a_2$  với mức ý nghĩa  $\alpha$  (hay độ tin cậy  $1 - \alpha$ ).

– Nếu  $u \ge t_\alpha$  thì ta bác bỏ giả thiết H mà chấp nhận đối thiết K:  $a_1 \neq a_2$ .

Ở đây  $t_\alpha$  tra trong bảng phân phối chuẩn sao cho  $\Phi(t_\alpha) = 1 - \frac{\alpha}{2}$ .

##### 3.1. Trường hợp tổng kích thước hai mẫu lớn hơn 60

Để giải quyết các bài toán dạng này, ta sử dụng kết quả sau đây:

Ví dụ 2.19. Để so sánh trọng lượng trẻ sơ sinh là con so với con dại ở một bệnh viện phụ sản, người ta tiến hành một quan sát như sau:

– Theo dõi trọng lượng của 95 trẻ sơ sinh là con so, nhận được trọng lượng trung bình của 95 cháu này bằng 2798g và độ lệch chuẩn bình phương  $S_A^2 = 190000$ .

– Theo dõi trọng lượng của 105 trẻ sơ sinh là con dại, nhận được trọng lượng trung bình của 105 cháu này bằng 3166g và độ lệch chuẩn bình phương  $S_B^2 = 200704$ .

Với độ tin cậy 95%, hãy cho biết trọng lượng trung bình của trẻ sơ sinh là con so và trẻ sơ sinh là con dại ở bệnh viện đó có khác nhau không.

**Giải:**

Ở đây ta có  $\bar{X}_A = 2798$ ;  $n_A = 95$  và  $S_A^2 = 190000$ .

$\bar{X}_B = 3166$ ;  $n_B = 105$  và  $S_B^2 = 200704$ ,  $\alpha = 0,05$ .

Tra bảng ta được  $t_{0,05} = 1,96$ . Ta có:

$$u = \frac{|\bar{X}_A - \bar{X}_B|}{\sqrt{\frac{S_A^2}{n_A} + \frac{S_B^2}{n_B}}} = \frac{|2798 - 3166|}{\sqrt{\frac{190000}{95} + \frac{200704}{105}}} \approx 5,88 > 1,96.$$

Vậy ta kết luận: Trọng lượng trung bình của trẻ sơ sinh là con so và con dại ở bệnh viện phụ sản đó khác nhau.

##### 3.2. Trường hợp phương sai chưa biết và tổng kích thước hai mẫu nhỏ hơn 60

Để so sánh hai số trung bình của hai tổng thể có phân phối chuẩn có cùng phương sai  $\sigma^2$  dựa vào hai trung bình mẫu  $\bar{X}_A$ ,  $\bar{X}_B$  thu được trên hai mẫu quan sát có kích thước  $n_A$  và  $n_B$  (trong đó  $n_A + n_B < 60$ ) ta lập tỉ số:

$$u = \frac{|\bar{X}_A - \bar{X}_B|}{S_{A,B} \sqrt{\frac{1}{n_A} + \frac{1}{n_B}}}$$

trong đó:

$$S_{A,B}^2 = \frac{\sum_{i=1}^{n_A} (x_A - \bar{X}_A)^2 + \sum_{i=1}^{n_B} (x_B - \bar{X}_B)^2}{n_A + n_B - 2}$$

hoặc:

$$S_{A,B}^2 = \frac{\sum_{i=1}^{n_A} x_A^2 - \frac{1}{n_A} \left(\sum_{i=1}^{n_A} x_A\right)^2 + \sum_{i=1}^{n_B} x_B^2 - \frac{1}{n_B} \left(\sum_{i=1}^{n_B} x_B\right)^2}{n_A + n_B - 2}$$

Ta kiểm định giả thiết  $H: a_1 = a_2$ , đối thiết  $K: a_1 \neq a_2$ , với mức ý nghĩa  $\alpha$  (hay độ tin cậy  $1 - \alpha$ ).

- Nếu  $u < t_\alpha$  thì ta chấp nhận giả thiết  $H$  và kết luận hai số trung bình khác nhau không có ý nghĩa;

- Nếu  $u \ge t_\alpha$  thì ta bác bỏ giả thiết  $H$  và chấp nhận đối thiết  $K$ .

Ở đây  $t_\alpha$  được tra trong bảng phân phối Student với  $n_A + n_B - 2$  bậc tự do.

**Ví dụ 2.20.** Để so sánh mức tăng trọng của hai giống gà, người ta chăm sóc chúng với cùng một chế độ thức ăn. Sau một thời gian, người ta chọn ngẫu nhiên 12 con từ đàn thứ nhất và 15 con từ đàn thứ hai, cân từng con và nhận được bảng số liệu sau:

Đàn thứ nhất:

| Trọng lượng (kg) | 2,5 | 3 | 3,2 | 3,5 | 4 |
|------------------|-----|---|-----|-----|---|
| Số lượng (con)   | 1   | 3 | 4   | 2   | 2 |

Đàn thứ hai:

| Trọng lượng (kg) | 2 | 2,8 | 3,5 | 4,2 |
|------------------|---|-----|-----|-----|
| Số lượng (con)   | 2 | 2   | 6   | 5   |

Giả sử các quan sát trên độc lập và có phân phối chuẩn  $N(a_1, \sigma^2)$  và  $N(a_2, \sigma^2)$ . Với mức ý nghĩa 0,1 hãy so sánh mức tăng trọng của hai giống gà nói trên.

**Giải:**

Ta có:  $n_1 + n_2 - 2 = 12 + 15 - 2 = 25$ . Tra bảng phân phối Student với 25 bậc tự do ta được  $t_{0,1} = 1,711$ .

$$\bar{X}_A = (2,5 + 3 \times 3 + 3,2 \times 4 + 3,5 \times 2 + 4 \times 2) : 12 = 3,275.$$

$$\bar{X}_B = (2 \times 2 + 2,8 \times 2 + 3,5 \times 6 + 4,2 \times 5) : 15 = 3,44.$$

$$\sum_{i=1}^{12} (x_A - \bar{X}_A)^2 = (2,5 - 3,275)^2 + (3 - 3,275)^2 \times 3 + (3,2 - 3,275)^2 \times 4 \\ + (3,5 - 3,275)^2 \times 2 + (4 - 3,275)^2 \times 2 \approx 2.$$

$$\sum_{i=1}^{15} (x_B - \bar{X}_B)^2 = (2 - 3,44)^2 \times 2 + (2,8 - 3,44)^2 \times 2 + (3,5 - 3,44)^2 \times 6 \\ + (4,2 - 3,44)^2 \times 5 = 7,876.$$

$$S_{A,B}^2 = \frac{2 + 7,876}{12 + 15 - 2} = 0,395; S_{A,B} \approx 0,63.$$

$$u = \frac{|3,275 - 3,44|}{0,63 \sqrt{\frac{1}{12} + \frac{1}{15}}} \approx 0,676 < 1,711.$$

Vậy với mức ý nghĩa 10% ta chấp nhận giả thiết  $H: a_1 = a_2$  hay mức tăng trọng của hai giống gà nói trên khác nhau không đáng kể.

##### 3.3. Kiểm định một phía khi phương sai chưa biết

Kiểm định một phía khi phương sai chưa biết (ta giả sử  $\sigma_1^2 = \sigma_2^2$ ).

a) Nếu  $\bar{X}_A < \bar{X}_B$  và  $n_A + n_B > 60$  thì ta kiểm định giả thiết  $H_0: a_1 = a_2$  với đối thiết  $K: a_1 < a_2$  như sau:

$$+ \text{Nếu } u = \frac{(\bar{X}_B - \bar{X}_A)}{S_{A,B} \sqrt{\frac{1}{n_A} + \frac{1}{n_B}}} > t_\alpha \text{ thì ta bác bỏ giả thiết H mà chấp nhận đối thiết K: } a_1 < a_2, \text{ trong đó hệ số } t_\alpha \text{ tra trong tự mục trên.}$$

$$+ \text{Nếu } u = \frac{(\bar{X}_B - \bar{X}_A)}{S_{A,B} \sqrt{\frac{1}{n_A} + \frac{1}{n_B}}} < t_\alpha \text{ thì ta chấp nhận giả thiết H.}$$

b) Nếu  $\bar{X}_A < \bar{X}_B$  và  $n_A + n_B < 60$  thì ta kiểm định giả thiết  $H_0: a_1 = a_2$  với đối thiết  $K: a_1 < a_2$  như sau:

$$+ \text{Nếu } u = \frac{(\bar{X}_B - \bar{X}_A)}{S_{A,B} \sqrt{\frac{1}{n_A} + \frac{1}{n_B}}} > t_\alpha \text{ thì ta bác bỏ giả thiết H mà chấp nhận đối thiết K: } a_1 < a_2, \text{ trong đó hệ số } t_\alpha \text{ tra trong bảng phân phối Student với } n_B + n_A - 2 \text{ bậc tự do.}$$

$$+ \text{Nếu } u = \frac{(\bar{X}_B - \bar{X}_A)}{S_{A,B} \sqrt{\frac{1}{n_A} + \frac{1}{n_B}}} < t_\alpha \text{ thì ta chấp nhận giả thiết H.}$$

#### 4. So sánh hai xác suất theo lý thuyết dựa trên tần suất thu được từ mẫu quan sát

Giả sử kết quả quan sát trên hai phép thử Bernoulli ta nhận được dãy số liệu sau:

- Số phép thử trong dãy thử nhất là  $n_1$ , số lần xuất hiện biến cố  $A$  là  $k_1$  và xác suất của biến cố  $A$  trong mỗi phép thử là  $p_1$ .

- Số phép thử trong dãy thử hai là  $n_2$ , số lần xuất hiện biến cố  $A$  là  $k_2$  và xác suất của biến cố  $A$  trong mỗi phép thử là  $p_2$ .

Ta kiểm định giả thiết  $H: p_1 = p_2$  với đối thiết  $K: p_1 \neq p_2$  ở mức ý nghĩa  $\alpha$  (hay độ tin cậy  $1 - \alpha$ ).

Trước hết ta tính:

$$d = \frac{\left| \frac{k_1}{n_1} - \frac{k_2}{n_2} \right|}{\sqrt{\left( \frac{1}{n_1} + \frac{1}{n_2} \right) \cdot \frac{k_1 + k_2}{n_1 + n_2} \cdot \left( 1 - \frac{k_1 + k_2}{n_1 + n_2} \right)}}$$

- Nếu  $d < t_\alpha$  thì chấp nhận giả thiết  $H: p_1 = p_2$ .

- Nếu  $d \ge t_\alpha$  thì bác bỏ giả thiết  $H$  hay chấp nhận đối thiết  $K: p_1 \neq p_2$ .

Ở đây hệ số  $t_\alpha$  tra trong bảng phân phối chuẩn sao cho  $\Phi(t_\alpha) = 1 - \frac{\alpha}{2}$ .

**Ví dụ 2.21.** Cùng một loại hạt giống lấy từ trong kho người ta đem gieo trên hai vườn umber khác nhau: trong vườn thứ nhất người ta gieo 100 hạt có 80 hạt nảy mầm; trong vườn thứ hai người ta gieo 125 hạt có 90 hạt nảy mầm. Hãy so sánh tỉ lệ hạt giống nới trên nảy mầm khi đem gieo trong hai vườn umber đó với mức ý nghĩa 5%.

**Giải:** Ở đây  $n_1 = 100$ ,  $k_1 = 80$ ;  $n_2 = 125$ ,  $k_2 = 90$  và  $\alpha = 5\%$ .

Tra bảng ta được  $t_\alpha = 1,96$ .

Ta có:

$$d = \frac{\left| \frac{80}{100} - \frac{90}{125} \right|}{\sqrt{\left( \frac{1}{100} + \frac{1}{125} \right) \cdot \frac{80+90}{100+125} \cdot \left( 1 - \frac{80+90}{100+125} \right)}} \approx 0,003324.$$

Vậy tỉ lệ hạt giống nảy mầm khi gieo trên hai vườn umber trên được coi là như nhau.

**Chú ý:** Nếu  $\frac{k_1}{n_1} < \frac{k_2}{n_2}$  thì ta đưa về bài toán kiểm định giả thiết:

$H_0: p_1 = p_2$  với đối thiết  $K: p_1 < p_2$  với mức ý nghĩa  $\alpha$ .

Tiêu chuẩn kiểm định giả thiết  $H_0$  ở đây là:

Giả thiết  $H_0$  bị bác bỏ ở mức  $\alpha$ , nếu:

$$Z = \sqrt{\left(\frac{1}{n_1} + \frac{1}{n_2}\right) \left(\frac{k_1 + k_2}{n_1 + n_2}\right) \left(1 - \frac{k_1 + k_2}{n_1 + n_2}\right)} > t_{\alpha}$$

và chấp nhận giả thiết  $H_0$ , nếu  $Z \le t_{\alpha}$ .

Tương tự đối với trường hợp  $\frac{k_1}{n_1} > \frac{k_2}{n_2}$ .

### IV. YẾU TỐ THỐNG KÊ TRONG MÔN TOÁN TIỂU HỌC

Yếu tố thống kê là một trong năm mạch kiến thức của môn Toán ở Tiểu học. Nó gồm các nội dung sau:

(a) Dãy số liệu thống kê;

(b) Bảng số liệu thống kê;

(c) Biểu đồ;

(d) Số trung bình của dãy số liệu;

(e) Giải toán về thống kê.

#### 1. Dãy số liệu thống kê

Giới thiệu cho học sinh:

(a) Các khái niệm cơ bản của dãy số liệu: số số hạng của dãy số liệu, thứ tự của số hạng,...

(b) Cách đọc và phân tích các số liệu của dãy;

(c) Biết xử lý số liệu của dãy ở mức độ đơn giản;

(d) Thực hành lập dãy số liệu từ một quan sát cụ thể.

#### 2. Bảng số liệu thống kê

Giới thiệu cho học sinh:

(a) Cấu tạo của bảng số liệu thống kê: hàng và cột, bảng đơn, bảng kép;

(b) Cách đọc và phân tích số liệu trong bảng;

(c) Biết cách xử lý số liệu trong bảng;

(d) Thực hành lập bảng số liệu từ một quan sát cụ thể.

#### 3. Biểu đồ

Giới thiệu cho học sinh:

(a) Cấu tạo của ba loại biểu đồ: biểu đồ tròn, biểu đồ cột và biểu đồ hình quạt;

(b) Biết cách đọc và phân tích số liệu trong mỗi loại biểu đồ;

(c) Thực hành lập biểu đồ từ một quan sát cụ thể.

#### 4. Giá trị trung bình của các số liệu thống kê

Giới thiệu cho học sinh:

(a) Khái niệm về số trung bình cộng;

(b) Quy tắc tìm số trung bình cộng của hai hay nhiều số;

(c) Thực hành tìm số trung bình cộng của các số liệu quan sát.

#### 5. Giải toán về thống kê số liệu

Các bài toán về thống kê số liệu ở Tiểu học có thể phân ra thành các dạng cơ bản:

(a) Thực hành đọc và phân tích các số liệu thống kê;

(b) Thực hành xử lý các số liệu thống kê;

(c) Thực hành lập dãy số liệu, bảng số liệu và biểu đồ từ một quan sát cụ thể;

(d) Thực hành giải toán với các số liệu trên biểu đồ.

Ví dụ 2.22. (xem [3], trang 24, bài 1)

Biểu đồ sau đây nói về số cây khối lớp Bón và khối lớp Năm đã trồng.

![](55e77a2d107de672b3d756dbdfc1e88a_img.jpg)

Bar chart showing the number of trees planted by Grade 4 (Bón) and Grade 5 (Năm) students.

The Y-axis represents the number of trees (Số cây), ranging from 0 to 50. The X-axis represents the Grade (Lớp).

| Grade (Lớp) | Number of Trees (Số cây) |
|-------------|--------------------------|
| 4A          | 35                       |
| 4B          | 28                       |
| 4C          | 45                       |
| 5A          | 40                       |
| 5B          | 22                       |

Nhìn vào biểu đồ trên hãy trả lời các câu hỏi sau:

a) Những lớp nào đã tham gia trồng cây?

b) Lớp 4A trồng được bao nhiêu cây? Lớp 5B trồng được bao nhiêu cây? Lớp 5C trồng được bao nhiêu cây?

c) Khối lớp Năm có mấy lớp tham gia trồng cây? Là những lớp nào?

d) Lớp nào trồng được nhiều cây nhất?

Trong bài tập này:

- Các câu a, b cùng có cho học sinh kĩ năng đọc số liệu trên biểu đồ cột;
- Các câu c, d cùng có cho học sinh kĩ năng phân tích số liệu trên biểu đồ cột.

Ví dụ 2.23. (xem [3], trang 33, bài 2)

Biểu đồ dưới đây nói về số thóc gia đình bác Hà đã thu hoạch được trong ba năm 2000, 2001, 2002:

| Năm 2000 | <img alt="Three bags of rice"/> |
|----------|---------------------------------|
| Năm 2001 | <img alt="Three bags of rice"/> |
| Năm 2002 | <img alt="Five bags of rice"/>  |

**Chú ý:** Mỗi ![Bag of rice icon]() chỉ 10 tạ thóc.

Dựa vào biểu đồ trên, hãy trả lời các câu hỏi sau đây:

1. Năm 2002 gia đình bác Hà thu hoạch được bao nhiêu tạ thóc?
2. Năm 2002 gia đình bác Hà thu hoạch nhiều hơn năm 2000 bao nhiêu tạ thóc?
3. Cả ba năm gia đình bác Hà thu hoạch được bao nhiêu tạ thóc? Năm nào thu hoạch được nhiều thóc nhất? Năm nào thu hoạch được ít thóc nhất?

Các câu trong bài tập này rèn cho học sinh kĩ năng đọc và phân tích số liệu trong biểu đồ tròn. Thực hành xử lý số liệu trên biểu đồ tròn. Đồng thời tích hợp kiến thức giữa biểu đồ tròn với các mạch kiến thức khác; do lượng và giải toán.

Ví dụ 2.24. (xem [4], trang 9, bài 2)

Kết quả điều tra về sở thích ăn hoa quả của 120 bạn học sinh mồ tạt trên biểu đồ hình quạt như hình bên.

Nhìn vào biểu đồ, em hãy cho biết:

1. Có bao nhiêu bạn thích ăn na?
2. Số bạn thích ăn na gấp bao nhiêu lần số bạn thích ăn cam?

![](2c637344ff0da5ad653151532d4041a9_img.jpg)

Biểu đồ hình quạt (Pie Chart) cho biết tỷ lệ sở thích ăn hoa quả của 120 bạn học sinh mồ tạt:

- Mít: 15%
- Cam: 20%
- Xoài: 25%
- Na: 40%

Trong bài tập này, học sinh được cùng cố kĩ năng đọc và xử lý số liệu trên biểu đồ quạt. Thông qua đó, giúp học sinh cùng cố kĩ năng tính toán về tỉ số phần trăm.

**Ví dụ 2.25.** (xem [3], bài 3, tiết 34)

Tàu Thắng Lợi trong ba tháng đầu năm đã đánh bắt được số cá như sau:

Tháng 1: 5 tấn; Tháng 2: 2 tấn; Tháng 3: 6 tấn.

Hãy vẽ tiếp biểu đồ sau đây:

![](97d95cd0cbe6c0c801edb6a4aaa5fc1c_img.jpg)

Bar chart showing the data for the first three months of the year (January, February, March).

The Y-axis is labeled (Tấn) and ranges from 0 to 5. The X-axis is labeled (Tháng) and shows months 1, 2, and 3.

Legend (in Vietnamese):

- 0005 mĂN
- 1005 mĂN
- 2005 mĂN

The bars represent the quantity of fish caught (Tấn):

- Tháng 1: 5 tấn (Bar reaches 5 on the Y-axis).
- Tháng 2: 2 tấn (Bar reaches 2 on the Y-axis).
- Tháng 3: 6 tấn (Bar reaches 6 on the Y-axis).

Bài toán trên bước đầu hình thành cho học sinh kĩ năng vẽ biểu đồ ở mức độ đơn giản.

**Ví dụ 2.26.** (xem [2], bài 2, trang 138)

Dưới đây là bảng thống kê số cây bản Na trồng được trong 4 năm:

| Năm      | 2000     | 2001     | 2002     | 2003     |
|----------|----------|----------|----------|----------|
| Loại cây |          |          |          |          |
| Thông    | 1875 cây | 2167 cây | 1980 cây | 2540 cây |
| Bạch đàn | 1745 cây | 2040 cây | 2165 cây | 2515 cây |

Dựa vào bảng trên hãy trả lời các câu hỏi sau đây:

a) Năm 2002 bản Na trống được nhiều hơn năm 2000 bao nhiêu cây bạch đàn?

b) Năm 2003 trống được tất cả bao nhiêu cây thông và cây bạch đàn?

Bài toán trên giúp học sinh rèn kỹ năng đọc, phân tích và xử lý số liệu của bảng số liệu thống kê. Thông qua đó, bài toán tích hợp giữa mạch kiến thức thống kê với giải toán có lời văn và giáo dục môi trường.

Ví dụ 2.27. (xem [2], bài 4, trang 139)

Trong cuộc thi chào mừng ngày Nhà giáo Việt Nam, các bạn khối lớp Ba đã đạt được các giải sau đây:

Văn nghệ: 3 giải nhất và 2 giải ba;

Kể chuyện: 2 giải nhất, 1 giải nhì và 4 giải ba;

Cờ vua: 1 giải nhất và 2 giải nhì.

Hãy viết số thích hợp vào bảng thống kê các giải của khối lớp Ba đạt được (theo mẫu):

| Giải | Môn | Văn nghệ | Kể chuyện | Cờ vua |
|------|-----|----------|-----------|--------|
| Nhất |     | 3        |           |        |
| Nhì  |     | 0        |           |        |
| Ba   |     | 2        |           |        |

Thông qua ví dụ này, bước đầu học sinh thực hành lập bảng số liệu thống kê.

Ví dụ 2.28. (xem [2], bài 1, trang 135)

Bốn bạn Dũng, Hà, Hưng, Quân có chiều cao theo thứ tự là:

129cm, 132cm, 125cm, 135cm.

Dựa vào dãy số liệu trên hãy trả lời các câu hỏi sau:

a) Hùng cao bao nhiêu xăng-ti-mét?

Dũng cao bao nhiêu xăng-ti-mét?

Hà cao bao nhiêu xăng-ti-mét?

Quân cao bao nhiêu xăng-ti-mét?

b) Dũng cao hơn Hùng bao nhiêu xăng-ti-mét?

Hà thấp hơn Quân bao nhiêu xăng-ti-mét?

Bài tập trên rèn cho học sinh kỹ năng đọc và phân tích số liệu của dãy số liệu thống kê.

## BÀI TẬP CHƯƠNG II

Bài 1. Trong kết quả của phép chọn mẫu, người ta nhận được dãy số liệu sau:  $-3; 2; -1; -3; 5; -3; 2$ .

a) Hãy xác định hàm phân phối mẫu.

b) Tính trung bình và phương sai mẫu.

Bài 2. Cung hời như bài 1 đối với dãy số liệu sau:

$2; -1; 2; -1; -4, 5; 2; 2; -1; 5$ .

Bài 3. Kết quả đo chiều cao của 10 cây giống trong một vườn uom cây cho ta dãy số liệu sau:

$2,31m; 2,28m; 2,29m; 2,28m; 2,32m$ ;

$2,28m; 2,32m; 2,29m; 2,31m; 2,32m$ .

Tìm kì vọng và phương sai mẫu trong quan sát nói trên.

Bài 4. Kết quả quan sát trên một tập mẫu có kích thước  $n$  lấy từ một tổng thể có phân phối chuẩn với phương sai đã biết  $\sigma^2$ . Với độ tin cậy  $\gamma$ , hãy cho ước lượng về số trung bình  $a$  của tổng thể, nếu:

a)  $\sigma^2 = 9; n = 36; \gamma = 95\%$ ;

b)  $\sigma^2 = 9; n = 36; \gamma = 99\%$ ;

c)  $\sigma^2 = 0,16; n = 81; \gamma = 95\%$ .

Bài 5. Giả sử kết quả quan sát trên tập mẫu có kích thước  $n = 25$  lấy từ một tổng thể có phân phối chuẩn ta thu được trung bình mẫu  $\bar{X}_{25} = 12,7$  và phương sai mẫu  $S_{25}^* = 0,25$ . Tìm khoảng ước lượng của số trung bình  $a$  của tổng thể với độ tin cậy 95%.

Bài 6. Để ước lượng độ dày trung bình của các tấm vật liệu do một xí nghiệp sản xuất, người ta tiến hành đo 5 tấm và thu được dãy số liệu sau:

$2,015cm; 2,025cm; 2,015cm; 2,020cm; 2,015cm$ .

Hãy cho ước lượng về độ dày trung bình của các tấm vật liệu xuất xưởng của xí nghiệp đó với độ tin cậy 95%. Biết rằng độ dày các tấm vật liệu là biến ngẫu nhiên có phân phối chuẩn.

Bài 7. Để ước lượng tuổi thọ trung bình của các bóng đèn xuất xưởng trong một nhà máy sản xuất bóng đèn, người ta theo dõi tuổi thọ của 16 bóng đèn trong lô hàng xuất xưởng. Kết quả thu được tuổi thọ trung bình của 16 bóng đèn đó là 1200 giờ và độ lệch tiêu chuẩn mẫu là 2,4 giờ. Biết tuổi thọ bóng đèn là biến ngẫu nhiên có phân phối chuẩn, hãy cho ước

lượng về tuổi trung bình của các bóng đèn của nhà máy đó với độ tin cậy 95%.

Bài 8. Điều tra doanh số hàng tháng của 100 hộ kinh doanh một loại hàng, người ta thu được bảng số liệu sau:

| Doanh số (triệu đồng) | 115 | 116 | 117 | 118 | 119 | 120 |
|-----------------------|-----|-----|-----|-----|-----|-----|
| Số hộ đạt             | 10  | 15  | 20  | 30  | 15  | 10  |

Với độ tin cậy 95%, hãy cho ước lượng về doanh số trung bình của các hộ kinh doanh mặt hàng đó, biết rằng doanh số là biến ngẫu nhiên phân phối theo luật chuẩn.

Bài 9. Đề ước lượng năng suất trung bình của giống lúa đang trồng ở một địa phương, người ta thống kê năng suất của 100 thửa ruộng trồng loại lúa trên và kết quả ghi trong bảng sau đây:

| Năng suất (ta/ha) | 42 | 44 | 46 | 48 | 50 | 52 |
|-------------------|----|----|----|----|----|----|
| Số thửa           | 7  | 13 | 25 | 35 | 15 | 5  |

Hãy cho ước lượng năng suất trung bình của giống lúa đó với độ tin cậy 98%. Biết rằng năng suất lúa là biến ngẫu nhiên phân phối theo luật chuẩn.

Bài 10. Trọng lượng trung bình của các gói hàng xuất xưởng trong một nhà máy sản xuất bánh kẹo là biến ngẫu nhiên phân phối theo luật chuẩn. Biết độ lệch tiêu chuẩn của các gói hàng đã kiểm tra là 1,2kg. Với độ tin cậy 90% thì kích thước mẫu cần chọn là bao nhiêu để sai số ước lượng không vượt quá 0,3?

Bài 11. Đề xác định tỉ lệ hạt giống này mầm trong lô hạt giống của một công ty giống và cây trồng, người ta lấy ngẫu nhiên 1000 hạt giống từ trong kho đem gieo, kết quả có 932 hạt này mầm. Hãy cho ước lượng về tỉ lệ hạt giống này mầm của công ty đó.

Bài 12. Xét nghiệm máu cho 10 000 người ở một địa phương X, kết quả có 40 người mắc bệnh A. Với độ tin cậy 99% hãy cho ước lượng về tỉ lệ người mắc bệnh A ở địa phương đó.

Bài 13. Khi phát phiếu thăm dò cho 200 nhân viên của một công ty X về một chủ trương của Ban giám đốc, kết quả có 146 người ủng hộ chủ trương đó. Với độ tin cậy 98% hãy cho ước lượng về tỉ lệ người của công ty đó ủng hộ chủ trương trên của Ban giám đốc.

**Bài 14.** Trong chiến dịch vận động tranh cử tổng thống ở một quốc gia X, người ta phỏng vấn ngẫu nhiên 2000 cử tri thì có 1120 người trả lời sẽ bầu cho ứng cử viên A. Với độ tin cậy 90% ta có thể khẳng định ứng cử viên đó sẽ giành được ít nhất bao nhiêu phần trăm phiếu bầu?

**Bài 15.** Đề xác định tỉ lệ học sinh yêu thích môn Tiếng Việt ở một trường tiểu học, người ta phát phiếu điều tra cho 130 em học sinh của trường đó. Kết quả có 85 em trả lời thích học Tiếng Việt và 45 em trả lời không thích vì khả năng diễn đạt kém.

a) Với độ tin cậy 98% ta có thể khẳng định tối đa có bao nhiêu phần trăm học sinh của trường đó yêu thích môn Tiếng Việt?

b) Với độ tin cậy 95% ta có thể khẳng định tối thiểu có bao nhiêu phần trăm học sinh của trường đó không thích môn Tiếng Việt?

**Bài 16.** Thời gian đóng bọt vào một bao là biến ngẫu nhiên có phân phối chuẩn với  $\sigma = 0,3$  phút.

a) Theo dõi 36 bao thấy thời gian trung bình để đóng 1 bao hàng là 1,2 phút. Với độ tin cậy 85%, hãy cho ước lượng về thời gian trung bình để đóng một bao hàng đó.

b) Nếu muốn độ dài khoảng tin cậy giảm đi 2 lần thì phải chọn kích thước mẫu là bao nhiêu?

**Bài 17.** Đề xác định số lượng một loài chim quý hiếm đang sinh sống trong một khu rừng, người ta tiến hành một quan sát như sau: bắt ngẫu nhiên 40 con chim thuộc loài đó, buộc vải đỏ vào chân từng con rồi thả lại khu rừng. Một thời gian sau, người ta lại bắt 90 con chim loài đó, kiểm tra có 5 con có vải đỏ buộc ở chân.

a) Với độ tin cậy 95% ta có thể khẳng định ít nhất còn bao nhiêu con chim loài đó đang sinh sống trong khu rừng nói trên?

b) Với độ tin cậy 95% ta có thể khẳng định còn tối đa bao nhiêu con chim loài đó đang sinh sống trong khu rừng nói trên?

**Bài 18.** Đề xác định số lượng cá trong một đầm nuôi cá, người ta tiến hành một quan sát như sau: bắt ngẫu nhiên 120 con cá trong đầm, xẻ đuôi từng con, rồi thả lại vào đầm. Sau một thời gian, người ta lại bắt ngẫu nhiên 300 con, kiểm tra có 12 con bị xẻ đuôi.

a) Với độ tin cậy 95% ta có thể khẳng định tối thiểu có bao nhiêu con cá đang sống trong khu đầm đó?

b) Với độ tin cậy 95% ta có thể khẳng định tối đa có bao nhiêu con cá đang sinh sống trong khu đầm đó?

Bài 19. Để kiểm tra hiệu quả sử dụng loại thuốc kháng sinh A để điều trị một loại bệnh B, người ta đã dùng loại thuốc đó để điều trị cho 9 bệnh nhân mắc bệnh B. Kết quả có 6 người khỏi bệnh. Với độ tin cậy 95% hãy cho ước lượng về tỉ lệ bệnh nhân khỏi bệnh khi dùng loại thuốc A.

Bài 20. Trọng lượng tiêu chuẩn của một bao thức ăn gia súc khi xuất xưởng là 20kg. Người ta cân ngẫu nhiên 100 bao thức ăn xuất xưởng thu được

| Trọng lượng (kg)  | 19 | 20 | 21 | 22 | 23 |
|-------------------|----|----|----|----|----|
| Số sản phẩm (bao) | 10 | 60 | 20 | 5  | 5  |

Với mức ý nghĩa  $\alpha = 5\%$ , hỏi trọng lượng các bao hàng xuất xưởng có đạt tiêu chuẩn hay không? Biết rằng trọng lượng các bao hàng là biến ngẫu nhiên phân phối theo luật chuẩn với độ lệch chuẩn  $S = 2$ kg.

Bài 21. Điều tra chi phí trong một tháng của 45 sinh viên ta thấy trung bình mỗi sinh viên đó chi hết 475 000 đồng/tháng. Hãy kiểm định giả thiết: mức chi phí trung bình của mỗi sinh viên trong một tháng là 500 000 đồng với mức ý nghĩa  $\alpha = 0,1$ . Biết rằng chi phí trong một tháng của sinh viên có phân phối chuẩn với độ lệch chuẩn bằng 3000 đồng.

Bài 22. Mì chính được đóng theo tiêu chuẩn 453g một gói. Coi trọng lượng của gói mì chính tuân theo luật chuẩn với độ lệch chuẩn bằng 36g. Kiểm tra ngẫu nhiên 81 gói nhận được trọng lượng trung bình là 448g với mức ý nghĩa  $\alpha = 0,01$  có thể kết luận các gói mì chính xuất xưởng đạt tiêu chuẩn được không?

Bài 23. Qua theo dõi người ta thấy rằng một loại xe chạy hết quãng đường AB tiêu hao hết 50 lít xăng một lượt. Sau khi đoạn đường đó được nâng cấp, người ta theo dõi mức tiêu hao xăng của 30 chuyen xe chạy trên tuyến đường AB thu được bảng số liệu sau:

| Mức xăng tiêu hao (lít) | 48,5 | 49,5 | 50 | 50,5 | 51 |
|-------------------------|------|------|----|------|----|
| Số chuyen xe            | 5    | 10   | 10 | 3    | 2  |

Với mức ý nghĩa  $\alpha = 0,05$ , hãy cho kết luận về mức xăng tiêu hao sau khi đoạn đường được nâng cấp có giảm đi không.

**Bài 24.** Định mức thời gian hoàn thành một sản phẩm là nửa giờ. Qua theo dõi thực tế thời gian hoàn thành một sản phẩm của 35 công nhân ta thu được bảng số liệu sau:

| Thời gian (phút) | 25 | 26 | 28 | 30 | 32 | 35 |
|------------------|----|----|----|----|----|----|
| Số công nhân     | 8  | 2  | 8  | 10 | 4  | 3  |

Với mức ý nghĩa  $\alpha = 0,1$ , hãy cho biết kết luận có nên thay đổi định mức hay không. Biết rằng thời gian hoàn thành một sản phẩm là biến ngẫu nhiên phân phối theo quy luật chuẩn.

**Bài 25.** Qua theo dõi, tỉ lệ trứng vịt nở thành vịt con của một trại áp trứng đạt tỉ lệ 80%. Khi sử dụng loại máy áp trứng mới, người ta áp thử 100 trứng bằng máy áp đó có 85 quả nở. Với mức ý nghĩa 10% hãy cho kết luận dùng máy áp mới thì tỉ lệ trứng nở có cao hơn không. Biết rằng tỉ lệ trứng nở thành vịt con là một biến ngẫu nhiên phân phối theo quy luật chuẩn.

**Bài 26.** Tỉ lệ phế phẩm cho phép ở một nhà máy là 5%. Kiểm tra ngẫu nhiên 300 sản phẩm của nhà máy đó có 24 sản phẩm là phế phẩm. Với mức ý nghĩa  $\alpha = 0,05$ , hãy cho kết luận tỉ lệ phế phẩm của nhà máy có vượt giới hạn cho phép hay không.

**Bài 27.** Để so sánh hiệu quả chăn nuôi gà bằng hai loại thức ăn khác nhau, người ta tiến hành một quan sát như sau:

– Dùng loại thứ nhất chăn nuôi 100 con gà, sau một tháng mỗi con tăng trung bình 1,1kg. Độ lệch chuẩn trong quan sát tính được  $S_1 = 0,2$ kg.

– Dùng loại thứ hai chăn nuôi 150 con gà, sau một tháng mỗi con tăng trung bình 1,2kg. Độ lệch chuẩn trong quan sát tính được  $S_2 = 0,3$ kg.

Với mức ý nghĩa  $\alpha = 0,05$ , hãy cho kết luận về hiệu quả của hai loại thức ăn trên có khác nhau không. Giả thiết rằng mức tăng trọng của gà có phân phối chuẩn.

**Bài 28.** Để so sánh hiệu quả của hai biện pháp canh tác đối với một giống lúa, người ta tiến hành một quan sát như sau:

– Áp dụng biện pháp canh tác thứ nhất trên cánh đồng rộng 100ha thì thu được năng suất trung bình 10 tấn/ha. Với độ lệch chuẩn trong quan sát  $S_1 = 1$  tấn/ha.

– Áp dụng biện pháp canh tác thứ hai trên cánh đồng 50ha thì thu được năng suất trung bình 9,5 tấn/ha với độ lệch chuẩn trong quan sát  $S_2 = 0,9$  tấn/ha.

Với mức ý nghĩa  $\alpha = 0,01$ , hãy cho kết luận về hiệu quả của hai biện pháp canh tác đối với giống lúa đó có khác nhau không. Ta coi năng suất lúa tuân theo quy luật chuẩn.

**Bài 29.** Để so sánh hiệu quả của hai loại vắc xin A và B dùng chữa bệnh cúm gà. Người ta tiến hành một quan sát như sau:

- Dùng loại vắc xin A chữa cho 120 con gà có 85 con khỏi.

- Dùng loại vắc xin B chữa cho 90 con gà cùng đàn có 71 con khỏi.

Với mức ý nghĩa 5% hãy cho kết luận về tỉ lệ gà được chữa khỏi bệnh cúm khi dùng hai loại vắc xin nói trên có tương đương không.

**Bài 30.** Để so sánh tỉ lệ học sinh năm được luật lệ về an toàn giao thông của hai trường Tiểu học A và B người ta tiến hành một quan sát như sau:

- Kiểm tra ngẫu nhiên 150 học sinh của trường A có 96 em năm được luật.

- Kiểm tra 120 em học sinh của trường B có 75 em năm được luật.

Với mức ý nghĩa 1%, hãy cho kết luận về tỉ lệ học sinh năm được luật giao thông của hai trường có như nhau không.

**Bài 31.** Để so sánh trọng lượng trung bình của trẻ sơ sinh ở thành thị và nông thôn, người ta tiến hành một quan sát như sau: cân trọng lượng của 8000 trẻ sơ sinh ở khu vực nông thôn, kết quả nhận được trọng lượng trung bình của số cháu này là 3kg và độ lệch tiêu chuẩn là 0,9kg; 2000 trẻ sơ sinh ở khu vực thành thị, kết quả nhận được trọng lượng trung bình của số cháu này là 3,2kg và độ lệch chuẩn bằng 0,4kg. Với mức ý nghĩa 5% có thể khẳng định trọng lượng trung bình của trẻ sơ sinh ở khu vực thành thị nặng hơn nông thôn được không. Biết rằng trọng lượng trung bình của trẻ sơ sinh là biến ngẫu nhiên có phân phối chuẩn.

**Bài 32.** Người ta áp dụng phương pháp dạy học A để dạy cho một lớp 42 học sinh và phương pháp dạy học B để dạy cho một lớp 35 học sinh (trình độ tương đương nhau). Sau khoá học, người ta cho hai lớp cùng làm một bài kiểm tra, kết quả đạt được như sau:

| Điểm số  | 4 | 5 | 6 | 7  | 8  | 9 | 10 |
|----------|---|---|---|----|----|---|----|
| Lớp      |   |   |   |    |    |   |    |
| Thứ nhất | 2 | 3 | 0 | 6  | 19 | 8 | 4  |
| Thứ hai  | 3 | 0 | 7 | 10 | 6  | 2 | 7  |

Với độ tin cậy 95%, có thể khẳng định phương pháp dạy học nào đạt hiệu quả cao hơn không? Biết rằng điểm trung bình của học sinh là biến ngẫu nhiên có phân phối chuẩn.

Bài 33. Người ta dùng hai loại thức ăn khác nhau để chăn nuôi hai đàn thuộc cùng một giống gà. Sau hai tháng, kết quả tăng trọng của mỗi đàn như sau:

| Loại thức ăn | Số gà | Mức tăng trọng trung bình | Độ lệch chuẩn |
|--------------|-------|---------------------------|---------------|
| I            | 100   | 1,1kg                     | 0,2           |
| II           | 150   | 1,2kg                     | 0,3           |

Với mức ý nghĩa 5%, có thể kết luận gà ăn thức ăn loại nào có mức tăng trọng cao hơn không?

Bài 34. Kiểm tra chất lượng sản phẩm của hai phân xưởng sản xuất phụ tùng xe máy, ta thu được bảng số liệu sau:

| Phân xưởng | Số sản phẩm được kiểm tra | Số phế phẩm |
|------------|---------------------------|-------------|
| I          | 1800                      | 54          |
| II         | 1200                      | 30          |

Với độ tin cậy 95%, có thể kết luận tỉ lệ chính phẩm của phân xưởng nào cao hơn không?

Bài 35. Để kiểm tra tỉ lệ học sinh của hai trường tiểu học năm được luật lệ về an toàn giao thông, người ta kiểm tra ngẫu nhiên 150 học sinh trường thứ nhất, kết quả có 115 em năm được luật và 140 học sinh của trường thứ hai có 110 em năm được luật. Với độ tin cậy 99%, có thể kết luận trường nào có tỉ lệ học sinh năm được luật cao hơn không?

## PHỤ LỤC

Bảng 1. Hàm phân bố chuẩn  $\phi(t) = \frac{1}{\sqrt{2\pi}} \int_{-\infty}^{t} e^{-\frac{1}{2}x^2} dx$  (t từ -3,9 đến 0)

| t         | 0      | 1    | 2    | 3    | 4    | 5    | 6    | 7    | 8    | 9    |
|-----------|--------|------|------|------|------|------|------|------|------|------|
| -0,0      | 0,5000 | 4960 | 4920 | 4880 | 4840 | 4801 | 4761 | 4721 | 4681 | 4641 |
| -0,1      | 4602   | 4526 | 4522 | 4483 | 4443 | 4404 | 4364 | 4325 | 4286 | 4247 |
| -0,2      | 4207   | 4168 | 4129 | 4090 | 4052 | 4013 | 3974 | 3936 | 3897 | 3859 |
| -0,3      | 3821   | 3783 | 3745 | 3707 | 3669 | 3632 | 3594 | 3557 | 3520 | 3483 |
| -0,4      | 3446   | 3409 | 3372 | 3336 | 3300 | 3264 | 3228 | 3192 | 3156 | 3132 |
| -0,5      | 0,3085 | 3050 | 3015 | 2981 | 2946 | 2912 | 2877 | 2843 | 2810 | 2776 |
| -0,6      | 2743   | 2709 | 2676 | 2643 | 2611 | 2578 | 2546 | 2514 | 2483 | 2451 |
| -0,7      | 2420   | 2389 | 2358 | 2327 | 2297 | 2266 | 2236 | 2206 | 2177 | 2148 |
| -0,8      | 2119   | 2090 | 2061 | 2033 | 2005 | 1977 | 1949 | 1922 | 1894 | 1867 |
| -0,9      | 1841   | 1814 | 1788 | 1762 | 1736 | 1711 | 1685 | 1660 | 1635 | 1611 |
| -1,0      | 0,1587 | 1562 | 1539 | 1515 | 1492 | 1469 | 1446 | 1423 | 1401 | 1379 |
| -1,1      | 1357   | 1335 | 1314 | 1292 | 1291 | 1251 | 1230 | 1210 | 1190 | 1170 |
| -1,2      | 1151   | 1131 | 1112 | 1093 | 1075 | 1056 | 1038 | 1020 | 1003 | 0985 |
| -1,3      | 0968   | 0951 | 0934 | 0918 | 0901 | 0885 | 0869 | 0853 | 0838 | 0823 |
| -1,4      | 0808   | 0793 | 0778 | 0764 | 0749 | 0735 | 0721 | 0708 | 0694 | 0681 |
| -1,5      | 0,0668 | 0655 | 0643 | 0630 | 0618 | 0606 | 0594 | 0582 | 0571 | 0559 |
| -1,6      | 0548   | 0537 | 0526 | 0516 | 0505 | 0495 | 0485 | 0475 | 0465 | 0455 |
| -1,7      | 3446   | 0436 | 0427 | 0418 | 0409 | 0401 | 0392 | 0384 | 0375 | 0367 |
| -1,8      | 0359   | 0351 | 0344 | 0336 | 0329 | 0322 | 0314 | 0317 | 0301 | 0294 |
| -1,9      | 0288   | 0281 | 0274 | 0268 | 0262 | 0256 | 0250 | 0244 | 0239 | 0233 |
| -2,0      | 0,0288 | 0222 | 0217 | 0212 | 0207 | 0202 | 0197 | 0192 | 0188 | 0183 |
| -2,1      | 0179   | 0174 | 0170 | 0166 | 0162 | 0158 | 0154 | 0150 | 0146 | 0143 |
| -2,2      | 0139   | 0136 | 0132 | 0129 | 0125 | 0122 | 0119 | 0116 | 0113 | 0110 |
| -2,3      | 0107   | 0104 | 0102 | 0099 | 0096 | 0094 | 0091 | 0089 | 0087 | 0084 |
| -2,4      | 0982   | 0080 | 0078 | 0075 | 0073 | 0071 | 0069 | 0068 | 0066 | 0064 |
| -2,5      | 0,0062 | 0060 | 0059 | 0057 | 0055 | 0054 | 0052 | 0051 | 0049 | 0048 |
| -2,6      | 0047   | 0045 | 0044 | 0043 | 0041 | 0040 | 0039 | 0038 | 0037 | 0036 |
| -2,7      | 0035   | 0034 | 0033 | 0032 | 0031 | 0030 | 0029 | 0028 | 0027 | 0026 |
| -2,8      | 0026   | 0025 | 0024 | 0023 | 0023 | 0022 | 0021 | 0021 | 0020 | 0019 |
| -2,9      | 0019   | 0018 | 0018 | 0017 | 0016 | 0016 | 0015 | 0015 | 0014 | 0014 |
| t         | -3,0   | -3,1 | -3,2 | -3,3 | -3,4 | -3,5 | -3,6 | -3,7 | -3,8 | -3,9 |
| $\phi(t)$ | 0,0013 | 0010 | 0007 | 0005 | 0003 | 0002 | 0002 | 0001 | 0001 | 0000 |

Bảng 1. Hàm phân bố chuẩn  $\phi(t) = \frac{1}{\sqrt{2\pi}} \int_{-\infty}^{t} e^{-\frac{1}{2}x^2} dx$  ( $t = 0$  đến  $+3,9$ )

| t         | 0      | 1    | 2     | 3    | 4    | 5    | 6    | 7    | 8    | 9    |
|-----------|--------|------|-------|------|------|------|------|------|------|------|
| 0,0       | 0,5000 | 5040 | 5080  | 5120 | 5160 | 5199 | 5239 | 5279 | 5319 | 5359 |
| 0,1       | 5398   | 5438 | 5478  | 5517 | 5557 | 5596 | 5636 | 5675 | 5714 | 5753 |
| 0,2       | 5793   | 5832 | 5871  | 5910 | 5948 | 5987 | 6026 | 6064 | 6103 | 6141 |
| 0,3       | 6179   | 6217 | 6265  | 6293 | 6331 | 6368 | 6406 | 6443 | 6480 | 6517 |
| 0,4       | 6554   | 6591 | 6628  | 6664 | 6700 | 6736 | 6772 | 6808 | 6844 | 6879 |
| 0,5       | 0,6915 | 6950 | 6985  | 7019 | 7054 | 7088 | 7123 | 7157 | 7190 | 7224 |
| 0,6       | 7257   | 7290 | 7324  | 7357 | 7389 | 7422 | 7454 | 7486 | 7517 | 7549 |
| 0,7       | 7580   | 7611 | 7642  | 7673 | 7704 | 7734 | 7764 | 7794 | 7823 | 7852 |
| 0,8       | 7881   | 7910 | 7939  | 7967 | 7995 | 8023 | 8058 | 8078 | 8106 | 8133 |
| 0,9       | 8159   | 8186 | 8212  | 8238 | 8264 | 8289 | 8315 | 8340 | 8365 | 8389 |
| 1,0       | 0,8413 | 8438 | 8461  | 8485 | 8508 | 8531 | 8554 | 8577 | 8599 | 8621 |
| 1,1       | 8463   | 8665 | 8686  | 8708 | 8729 | 8749 | 8770 | 8790 | 8810 | 8830 |
| 1,2       | 8849   | 8869 | 8888  | 8907 | 8925 | 8944 | 8962 | 8980 | 8997 | 9015 |
| 1,3       | 9032   | 9049 | 9066  | 9082 | 9099 | 9115 | 9131 | 9147 | 9162 | 9177 |
| 1,4       | 9192   | 9207 | 9222  | 9236 | 9251 | 9265 | 9279 | 9292 | 9306 | 9319 |
| 1,5       | 0,9332 | 9345 | 9357  | 9370 | 9382 | 9394 | 9406 | 9418 | 9429 | 9441 |
| 1,6       | 9452   | 9463 | 9474  | 9484 | 9495 | 9505 | 9515 | 9525 | 9535 | 9545 |
| 1,7       | 9554   | 9564 | 9573  | 9582 | 9591 | 9599 | 9608 | 9616 | 9625 | 9633 |
| 1,8       | 9641   | 9649 | 9656  | 9664 | 9671 | 9678 | 9686 | 9693 | 9699 | 9706 |
| 1,9       | 9713   | 9719 | 97262 | 9732 | 9738 | 9744 | 9750 | 9756 | 9764 | 9767 |
| 2,0       | 0,9773 | 9778 | 9783  | 9788 | 9793 | 9798 | 9803 | 9808 | 9812 | 9817 |
| 2,1       | 9821   | 9826 | 9830  | 9834 | 9838 | 9842 | 9846 | 9850 | 9854 | 9857 |
| 2,2       | 9861   | 9864 | 9868  | 9871 | 9875 | 9878 | 9881 | 9884 | 9887 | 9890 |
| 2,3       | 9893   | 9896 | 9898  | 9901 | 9904 | 9906 | 9909 | 9911 | 9913 | 9916 |
| 2,4       | 9918   | 9920 | 9922  | 9925 | 9927 | 9929 | 9931 | 9932 | 9934 | 9936 |
| 2,5       | 0,9938 | 9940 | 9941  | 9943 | 9945 | 9946 | 9948 | 9949 | 9951 | 9952 |
| 2,6       | 9953   | 9955 | 9956  | 9957 | 9959 | 9960 | 9961 | 9962 | 9963 | 9964 |
| 2,7       | 9965   | 9966 | 9967  | 9968 | 9969 | 9970 | 9971 | 9972 | 9973 | 9974 |
| 2,8       | 9974   | 9975 | 9976  | 9977 | 9977 | 9978 | 9979 | 6679 | 9980 | 9981 |
| 2,9       | 9981   | 9982 | 9982  | 9983 | 9984 | 9984 | 9985 | 9985 | 9986 | 9986 |
| t         | 3,0    | 3,1  | 3,2   | 3,3  | 3,4  | 3,5  | 3,6  | 3,7  | 3,8  | 3,9  |
| $\phi(t)$ | 0,9987 | 9990 | 9993  | 9995 | 9996 | 9997 | 9998 | 9999 | 9999 | 9999 |

Bảng 2. Phân phối Student  $P[T > t_{\alpha}] = \alpha$ 

| Số bậc tự do | Mức ý nghĩa $\alpha$ (tiêu chuẩn 2 phía) |       |       |       |       |        |
|--------------|------------------------------------------|-------|-------|-------|-------|--------|
|              | k                                        | 0,10  | 0,05  | 0,02  | 0,01  | 0,002  |
| 1            | 6,31                                     | 12,7  | 31,82 | 63,7  | 318,2 | 637,0  |
| 2            | 2,92                                     | 4,3   | 6,97  | 9,92  | 22,33 | 3,16   |
| 3            | 2,35                                     | 3,18  | 4,54  | 5,84  | 10,22 | 1,29   |
| 4            | 2,13                                     | 2,78  | 3,75  | 4,60  | 7,17  | 8,61   |
| 5            | 2,01                                     | 2,57  | 3,37  | 4,30  | 5,89  | 6,86   |
| 6            | 1,94                                     | 2,45  | 3,14  | 3,71  | 5,21  | 5,96   |
| 7            | 1,39                                     | 2,36  | 3,00  | 3,50  | 4,79  | 5,40   |
| 8            | 1,86                                     | 2,31  | 2,90  | 3,36  | 4,50  | 5,04   |
| 9            | 1,83                                     | 2,26  | 2,82  | 3,25  | 4,30  | 4,78   |
| 10           | 1,81                                     | 2,23  | 2,76  | 3,17  | 4,14  | 4,59   |
| 11           | 1,80                                     | 2,20  | 2,72  | 3,11  | 4,03  | 4,44   |
| 12           | 1,78                                     | 2,18  | 2,68  | 3,05  | 3,93  | 4,32   |
| 13           | 1,77                                     | 2,16  | 2,65  | 3,01  | 3,85  | 4,22   |
| 14           | 1,76                                     | 2,14  | 2,62  | 2,98  | 3,79  | 4,14   |
| 15           | 1,75                                     | 2,13  | 2,60  | 2,95  | 3,73  | 4,07   |
| 16           | 1,75                                     | 2,12  | 2,58  | 2,92  | 3,69  | 4,01   |
| 17           | 1,71                                     | 2,11  | 2,57  | 2,90  | 3,65  | 3,96   |
| 18           | 1,73                                     | 2,10  | 2,55  | 2,88  | 3,61  | 3,92   |
| 19           | 1,73                                     | 2,09  | 2,54  | 2,86  | 3,58  | 3,88   |
| 20           | 1,73                                     | 2,09  | 2,53  | 2,85  | 3,55  | 3,85   |
| 21           | 1,72                                     | 2,08  | 2,52  | 2,83  | 3,53  | 3,82   |
| 22           | 1,72                                     | 2,07  | 2,51  | 2,82  | 3,51  | 3,79   |
| 23           | 1,71                                     | 2,07  | 2,50  | 2,81  | 3,49  | 3,77   |
| 24           | 1,71                                     | 2,06  | 2,49  | 2,80  | 3,47  | 3,73   |
| 25           | 1,71                                     | 2,06  | 2,49  | 2,79  | 3,45  | 3,72   |
| 26           | 1,71                                     | 2,06  | 2,48  | 2,78  | 3,44  | 3,71   |
| 27           | 1,71                                     | 2,05  | 2,47  | 2,77  | 3,42  | 3,69   |
| 28           | 1,70                                     | 2,05  | 2,46  | 2,76  | 3,40  | 3,66   |
| 29           | 1,70                                     | 2,05  | 2,46  | 2,76  | 3,40  | 3,66   |
| 30           | 1,70                                     | 2,04  | 2,46  | 2,75  | 3,39  | 3,65   |
| 40           | 1,68                                     | 2,02  | 2,42  | 2,70  | 3,31  | 3,55   |
| 60           | 1,67                                     | 2,00  | 2,39  | 2,66  | 3,23  | 3,46   |
| 120          | 1,66                                     | 1,98  | 2,36  | 2,62  | 3,17  | 3,37   |
|              | 1,64                                     | 1,96  | 2,33  | 2,58  | 3,09  | 3,29   |
|              | 0,05                                     | 0,025 | 0,01  | 0,005 | 0,001 | 0,0005 |

Mức ý nghĩa  $\alpha$  (tiêu chuẩn một phía)

Bảng 3. Khoảng tin cậy của tỉ lệ  $p = \frac{X}{n}$  của mẫu bé

( $1 < n \le 10$  (với  $p = 5\%$ ))

| Y  | X         |              |             |              |               |               |               |               |               |               |               |
|----|-----------|--------------|-------------|--------------|---------------|---------------|---------------|---------------|---------------|---------------|---------------|
|    | 0         | 1            | 2           | 3            | 4             | 5             | 6             | 7             | 8             | 9             | 10            |
| 4  | 0<br>60,2 | 0,6<br>80,6  | 6,8<br>93,2 | 19,4<br>99,4 | 39,9<br>100,0 |               |               |               |               |               |               |
| 5  | 0<br>52,2 | 0,5<br>71,16 | 5,3<br>85,3 | 14,7<br>94,7 | 28,4<br>99,5  | 47,8<br>100,0 |               |               |               |               |               |
| 6  | 0<br>45,9 | 0,4<br>64,1  | 4,3<br>77,7 | 11,8<br>88,2 | 22,3<br>95,7  | 35,9<br>99,6  | 54,1<br>100,0 |               |               |               |               |
| 7  | 0<br>41,0 | 0,4<br>57,9  | 3,7<br>71,0 | 9,9<br>80,6  | 11,8<br>90,1  | 29,0<br>96,3  | 42,1<br>99,6  | 59,0<br>100,0 |               |               |               |
| 8  | 0<br>36,9 | 0,3<br>52,7  | 3,2<br>65,2 | 8,5<br>75,5  | 15,7<br>84,3  | 24,5<br>91,5  | 34,8<br>96,8  | 47,3<br>99,7  | 63,1<br>100,0 |               |               |
| 9  | 0<br>33,6 | 0,3<br>48,3  | 7,5<br>70,1 | 7,5<br>70,1  | 13,7<br>18,8  | 21,2<br>86,3  | 29,9<br>92,5  | 40,0<br>97,2  | 51,7<br>99,7  | 66,4<br>100,0 |               |
| 10 | 0<br>30,8 | 0,3<br>44,5  | 6,7<br>65,2 | 6,7<br>65,2  | 12,2<br>73,8  | 18,7<br>81,3  | 26,2<br>87,8  | 34,8<br>93,3  | 44,4<br>97,5  | 55,5<br>99,7  | 69,2<br>100,0 |

Bảng 4. Khoảng tin cậy của tỉ lệ bé  $p \le 0,1$  hoặc  $p \ge 0,9$  (với  $p = 5\%$ )

(Các giá trị của  $np_1$  và  $np_2$  khi  $p \le 0,1$ )

| X  | 0             | 1              | 2             | 3             | 4             | 5             | 6             | 7             | 8             | 9             |               |
|----|---------------|----------------|---------------|---------------|---------------|---------------|---------------|---------------|---------------|---------------|---------------|
| 00 |               | 0,025<br>5,572 | 0,24<br>7,22  | 0,62<br>8,76  | 1,09<br>10,24 | 1,62<br>11,67 | 2,20<br>13,06 | 2,81<br>14,42 | 3,45<br>15,76 | 4,12<br>17,08 |               |
| 10 | 4,8<br>18,4   | 5,5<br>19,7    | 6,2<br>21,0   | 6,9<br>22,3   | 7,6<br>23,6   | 8,3<br>24,9   | 9,0<br>26,1   | 9,8<br>27,3   | 10,6<br>28,5  | 11,4<br>29,7  |               |
| 20 | 12,2<br>30,9  | 13,0<br>32,1   | 13,8<br>33,3  | 14,6<br>34,5  | 15,4<br>35,7  | 16,2<br>36,9  | 17,0<br>38,1  | 17,8<br>39,3  | 18,6<br>40,5  | 19,9<br>41,7  |               |
| 30 | 20,2<br>42,8  | 21,0<br>44,0   | 21,8<br>45,2  | 22,7<br>46,3  | 23,5<br>47,5  | 24,4<br>48,6  | 25,2<br>49,8  | 26,1<br>50,9  | 26,9<br>52,1  | 57,8<br>55,3  |               |
| 40 | 28,6<br>54,4  | 29,5<br>55,5   | 30,3<br>56,7  | 31,2<br>57,8  | 32,0<br>59,0  | 32,9<br>60,1  | 33,7<br>61,3  | 34,6<br>62,5  | 35,4<br>63,6  | 36,3<br>64,7  |               |
| 50 | 37,1<br>65,9  | 38,0<br>67,0   | 38,8<br>68,2  | 39,7<br>69,3  | 40,5<br>70,5  | 41,4<br>71,6  | 42,3<br>72,7  | 43,1<br>73,9  | 44,0<br>75,0  | 44,9<br>76,1  |               |
| 60 | 45,8<br>77,2  | 46,6<br>78,4   | 47,5<br>79,5  | 48,4<br>80,6  | 49,3<br>81,8  | 40,2<br>82,9  | 51,0<br>84,0  | 51,9<br>85,1  | 52,8<br>86,2  | 53,7<br>87,3  |               |
| 70 | 54,6<br>88,4  | 55,5<br>89,5   | 53,3<br>90,7  | 57,2<br>91,8  | 58,1<br>92,9  | 58,0<br>94,0  | 59,9<br>95,1  | 60,8<br>96,2  | 61,7<br>97,3  | 62,6<br>98,4  |               |
| 80 | 63,4<br>99,6  | 64,3<br>100,7  | 65,5<br>101,8 | 66,1<br>102,9 | 67,0<br>104,0 | 67,9<br>105,1 | 68,8<br>106,2 | 69,7<br>107,3 | 70,8<br>108,4 | 71,5<br>109,5 | 10            |
| 90 | 72,4<br>110,6 | 73,3<br>111,7  | 74,2<br>112,8 | 75,1<br>113,9 | 76,0<br>155,0 | 76,9<br>116,1 | 77,8<br>117,2 | 78,7<br>118,3 | 79,6<br>119,4 | 80,5<br>120,5 | 81,4<br>121,6 |