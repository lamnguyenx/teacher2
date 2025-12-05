

TRƯỜNG ĐẠI HỌC KINH TẾ QUỐC DÂN  
KHOA TOÁN KINH TẾ - BỘ MÔN ĐIỀU KHIỂN HỌC

# BÀI GIẢNG XÁC SUẤT & THỐNG KÊ TOÁN

NHÀ XUẤT BẢN THỐNG KÊ  
HÀ NỘI - 1999

# PHẦN THỨ HAI

## THỐNG KÊ TOÁN

Thống kê toán là bộ môn toán học nghiên cứu qui luật của các hiện tượng ngẫu nhiên có tính chất số lớn trên cơ sở thu nhập và xử lý các số liệu thống kê - các kết quả quan sát. Như vậy nội dung chủ yếu của thống kê toán là xây dựng các phương pháp thu thập và xử lý các số liệu thống kê nhằm rút ra các kết luận khoa học và thực tiễn.

Các phương pháp thống kê toán là công cụ để giải quyết nhiều vấn đề khoa học và thực tiễn này sinh trong các lĩnh vực khác nhau của tự nhiên và kinh tế xã hội.

## Chương VI. CƠ SỞ LÍ THUYẾT MẪU

### § 1. KHÁI NIỆM VỀ PHƯƠNG PHÁP MẪU

Trong thực tế thường phải nghiên cứu một tập hợp các phần tử đồng nhất theo một hay nhiều dấu hiệu định tính hoặc định lượng đặc trưng cho các phần tử đó. Chẳng hạn một doanh nghiệp phải nghiên cứu tập hợp các khách hàng của mình thì dấu hiệu định tính có thể là mức độ hài lòng của khách hàng đối với sản phẩm hoặc dịch vụ của doanh nghiệp, còn dấu hiệu định lượng là nhu cầu của khách hàng về số lượng sản phẩm của doanh nghiệp.

Để nghiên cứu tập hợp các phần tử này theo một dấu hiệu nhất định đòi hỏi người ta sử dụng phương pháp nghiên cứu toàn bộ, tức là thống kê toàn bộ tập hợp đó và phân tích từng phần tử của nó theo dấu hiệu nghiên cứu. Chẳng hạn để nghiên cứu dân số của một nước theo các dấu hiệu như tuổi tác, trình độ văn hóa, địa bàn cư trú, cơ cấu nghề nghiệp... có thể tiến hành tổng điều tra dân số và phân tích từng người theo các dấu hiệu trên, từ đó tổng hợp thành dấu hiệu chung cho toàn bộ dân số của nước đó. Tuy nhiên trong thực tế việc áp dụng phương pháp này gặp phải những khó khăn chủ yếu sau:

- Nếu qui mô của tập hợp quá lớn thì việc nghiên cứu toàn bộ sẽ đòi hỏi nhiều chi phí vật chất và thời gian.

- Nhiều khi cũng do qui mô của tập hợp quá lớn nên có thể xảy ra trường hợp tính trùng hoặc bỏ sót các phần tử của nó.

- Do qui mô nghiên cứu lớn mà trình độ tổ chức nghiên cứu lại hạn chế dẫn đến các sai sót trong quá trình thu thập thông tin ban đầu, hạn chế độ chính xác của kết quả phân tích.

- Trong nhiều trường hợp không thể năm được toàn bộ các phần tử của tập hợp cần nghiên cứu, do đó không thể tiến hành nghiên cứu toàn bộ được.

- Nếu các phần tử của tập hợp lại bị phá hủy trong quá trình nghiên cứu thì phương pháp nghiên cứu toàn bộ trở thành vô nghĩa...

Vì thế trong thực tế phương pháp nghiên cứu toàn bộ thường chỉ được áp dụng đối với các tập hợp có qui mô nhỏ, còn chủ yếu người ta áp dụng phương pháp nghiên cứu không toàn bộ, đặc biệt là phương pháp nghiên cứu chọn mẫu. Phương pháp này chủ trương từ tập hợp cần nghiên cứu chọn ra một phần tử (gọi là mẫu), phân tích các phần tử này và dựa vào đó mà suy ra các kết luận về tập hợp cần nghiên cứu. Nếu mẫu được chọn ra một cách ngẫu nhiên và xử lý bằng phương pháp xác suất thì vừa thu được các kết luận một cách nhanh chóng, dễ tổn kém mà vẫn đảm bảo độ chính xác cần thiết.

### § 2. TỔNG THỂ NGHIÊN CỨU

**2.1. DINH NGHĨA.** Toàn bộ tập hợp các phần tử đồng nhất theo một dấu hiệu nghiên cứu định tính hoặc định lượng nào đó được gọi là tổng thể nghiên cứu hay thống kê.

Số lượng các phần tử của tổng thể được gọi là kích thước của tổng thể, ký hiệu là N. Thường thì kích thước N của tổng thể là hữu hạn, song nếu tổng thể quá lớn hoặc không thể năm được toàn bộ các phần tử của tổng thể ta có thể giả thiết rằng kích thước của tổng thể là vô hạn. Điều giả thiết này dựa trên cơ sở là khi tăng kích thước của tổng thể lên khả lớn thì thực tế không ảnh hưởng gì đến kết quả tính toán trên số liệu của từng bộ phận rút ra từ tổng thể đó.

Với mỗi tổng thể ta không nghiên cứu trực tiếp tổng thể đó mà thông qua một hay nhiều dấu hiệu đặc trưng cho tổng thể đó.

Chúng được gọi là *dấu hiệu nghiên cứu*, ký hiệu là  $\chi$ . Các dấu hiệu này có thể là định tính hoặc định lượng.

#### 2.2. CÁC PHƯƠNG PHÁP MÔ TẢ TỔNG THỂ

1. Giá sử trong tổng thể dấu hiệu nghiên cứu định lượng  $\chi$  nhận các giá trị  $x_1, x_2, \dots, x_n$  với các tần số tương ứng  $N_1, N_2, \dots, N_k$  ( $N_i$  là số phân tử của tổng thể có chung giá trị  $x_i$ ). Lực đó tổng thể có thể mô tả bằng bảng phân phối tần số sau:

| Giá trị của $\chi$ | $x_1$ | $x_2$ | $\dots$ | $x_i$ | $\dots$ | $x_k$ |
|--------------------|-------|-------|---------|-------|---------|-------|
| Tần số             | $N_1$ | $N_2$ | $\dots$ | $N_i$ | $\dots$ | $N_k$ |

Hiển nhiên

$$0 \le N_i \le N \quad \text{Vì} \quad \sum_{i=1}^{k} N_i = N \quad (6.2)$$

2. Nếu ký hiệu  $p_i$  ( $i = 1, k$ ) là tần suất của  $x_i$ , tức là tỷ số giữa tần số của  $x_i$  và kích thước của tổng thể thì

$$p_i = \frac{N_i}{N} \quad i = 1, k \quad (6.2)$$

và lực đó tổng thể còn có thể mô tả bằng bảng phân phối tần suất sau:

| Giá trị của $\chi$ | $x_1$ | $x_2$ | $\dots$ | $x_i$ | $\dots$ | $x_k$ |
|--------------------|-------|-------|---------|-------|---------|-------|
| Tần suất           | $p_1$ | $p_2$ | $\dots$ | $p_i$ | $\dots$ | $p_k$ |

Từ (6.1) và (6.2) suy ra

$$0 \le p_i \le 1 \quad \text{Vì}$$

$$\sum_{i=1}^{k} p_i = 1$$

Về mặt hình thức, bảng phân phối tần suất của tổng thể tương tự như bảng phân phối xác suất của biến ngẫu nhiên rời rạc. Nó phân ánh cơ cấu của tổng thể theo dấu hiệu  $\chi$ .

3. Nếu ký hiệu  $w_i$  ( $i = 1, k$ ) là tần số tích lũy của  $x_i$ , tức là tổng số các phần tử có giá trị nhỏ hơn  $x_i$ , thì

$$w_i = \sum_{x_j < x_i} N_j \quad (6.3)$$

và  $F(x_i)$  ( $i = 1, k$ ) là tần số tích lũy của  $x_i$ , tức là tổng số các phần tử có giá trị nhỏ hơn  $x_i$ , thì

$$w_i = \sum_{x_j < x_i} N_j \quad (6.3)$$

và  $F(x_i)$  ( $i = 1, k$ ) là tần suất tích lũy của  $x_i$ , tức là tỷ số giữa tần số tích lũy của nó và kích thước của tổng thể, thì

$$F(x_i) = \frac{w_i}{N} = \sum_{x_j < x_i} \frac{N_j}{N} \quad (6.4)$$

Tần suất tích lũy là một hàm của  $x_i$ , có tính chất giống như hàm phân bố xác suất của biến ngẫu nhiên rời rạc.

Việc mô tả tổng thể theo dấu hiệu nghiên cứu  $\chi$  bằng bảng phân phối tần số, bảng phân phối tần suất và tần suất tích lũy cho thấy dấu hiệu định lượng  $\chi$  hoàn toàn có thể mô hình hóa bằng một biến ngẫu nhiên rời rạc  $X$ . Điều này cũng đúng đối với các tổng thể mang dấu hiệu  $\chi$  phân phối liên tục. Biến ngẫu nhiên  $X$  dùng để mô hình hóa dấu hiệu nghiên cứu  $\chi$  được gọi là biến ngẫu nhiên gốc, còn qui luật phân phối xác suất của nó gọi là qui luật phân phối gốc.

#### 2.3. CÁC THAM SỐ ĐẶC TRUNG CỦA TỔNG THỂ

Việc mô tả tổng thể theo dấu hiệu  $\chi$  bằng bảng phân phối tần số, bảng phân phối tần suất và tần suất tích lũy mới chỉ cung cấp những thông tin chung nhất về tổng thể đó. Trong thực tế nhiều khi người nghiên cứu cần quan tâm đến những thông tin tổng hợp phân ánh những khía cạnh quan trọng nhất của tổng thể theo dấu hiệu nghiên cứu đó. Những thông tin này được biểu hiện qua các tham số đặc trưng chủ yếu sau đây của tổng thể.

###### I. Trung bình tổng thể

Giả sử trong tổng thể kích thước  $N$  dấu hiệu định lượng  $\chi$  nhận các giá trị  $x_1, x_2, \dots, x_N$ . Trung bình tổng thể, ký hiệu là  $m$  là trung bình số học của các giá trị của dấu hiệu trong tổng thể.

$$m = \frac{1}{N} \sum_{i=1}^{N} x_i \quad (6.5)$$

Nếu trong tổng thể dấu hiệu  $\chi$  chỉ nhận được các giá trị  $x_1, x_2, \dots, x_k$  với các tần số tương ứng  $N_1, N_2, \dots, N_k$  thì trung bình tổng thể được xác định bằng biểu thức:

$$m = \frac{1}{N} \sum_{i=1}^{k} x_i N_i \quad (6.6)$$

Bản chất của trung bình tổng thể có thể làm rõ như sau:

Giả sử tổng thể kích thước  $N$  bao gồm các phân tử mang các giá trị khác nhau của dấu hiệu nghiên cứu  $\chi$  là  $x_1, x_2, \dots, x_N$ . Giả sử từ tập hợp này lấy ngẫu nhiên ra một phân tử thì xác suất để lấy được phân tử mang giá trị  $x_i$  hiện nhiên là  $\frac{1}{N}$  ( $i = 1, N$ ). Như vậy giá trị của dấu hiệu  $\chi$  có thể xem như một biến ngẫu nhiên  $X$  với các giá trị có thể là  $x_1, x_2, \dots, x_N$  và các xác suất tương ứng đều bằng  $\frac{1}{N}$ . Tức đó

$$E(X) = x_1 \frac{1}{N} + x_2 \frac{1}{N} + \dots + x_N \frac{1}{N} = \frac{1}{N} \sum_{i=1}^{N} x_i = m$$

Như vậy

$$m = E(X)$$

Mô rộng kết quả thu được cho tổng thể với dấu hiệu nghiên cứu liên tục ta thu được kết quả là nếu xem dấu hiệu nghiên cứu như biến ngẫu nhiên  $X$  thì trung bình tổng thể chính là kỳ vọng toán của biến ngẫu nhiên đó.

ngoài trung bình tổng thể  $m$  (mà thực chất là trung bình số học) là loại trung bình được sử dụng nhiều nhất, trong thực tế, tùy thuộc vào từng trường hợp người ta cần tính các loại trung bình sau.

a- Trung bình điều hòa: tương tự như trung bình số học, trong đó thay cho các giá trị của dấu hiệu nghiên cứu người ta dùng giá trị nghịch đảo của chúng. Như vậy nếu ký hiệu trung bình điều hòa là  $m_h$  thì ta có công thức:

$$m_h = \frac{N}{\sum_{i=1}^{n} \frac{1}{x_i}} \quad (6.7)$$

Nếu dấu hiệu của tổng thể nhận các giá trị  $x_1, x_2, \dots, x_k$  với tần số tương ứng  $N_1, N_2, \dots, N_k$  thì

$$m_h = \frac{N}{\sum_{i=1}^{k} \frac{N_i}{x_i}} \quad (6.8)$$

b- Trung bình nhân. Là căn bậc N của tích các giá trị của dấu hiệu trong tổng thể. Vay nếu ký hiệu trung bình nhân là  $m_g$  thì

$$m_g = \sqrt[N]{x_1 \cdot x_2 \cdot \dots \cdot x_N} \quad (6.9)$$

$$m_g = \sqrt[N]{x_1^{N_1} \cdot x_2^{N_2} \cdot \dots \cdot x_k^{N_k}} \quad (6.10)$$

nếu dấu hiệu chỉ nhận các giá trị  $x_1, \dots, x_k$  với tần số tương ứng  $N_1, \dots, N_k$ .

###### 2. Phương sai tổng thể

Phương sai tổng thể, ký hiệu là  $\sigma^2$ , là trung bình số học của bình phương các sai lệch giữa các giá trị của dấu hiệu trong tổng thể và trung bình tổng thể:

$$\sigma^2 = \frac{1}{N} \sum_{i=1}^{n} (x_i - m)^2 \quad (6.11)$$

Nếu các giá trị  $x_1, x_2, \dots, x_k$  của dấu hiệu có các tần số tương ứng là  $N_1, N_2, \dots, N_k$  với  $N_1 + N_2 + \dots + N_k = N$  thì

$$\sigma^2 = \frac{1}{N} \sum_{i=1}^{k} N_i (x_i - m)^2 \quad (6.12)$$

Do có thể viết

$$\sigma^2 = \frac{1}{N} \sum_{i=1}^{k} N_i (x_i - m)^2 = \sum_{i=1}^{k} \frac{N_i}{N} (x_i - m)^2 = \sum_{i=1}^{k} (x_i - m)^2 p_i$$

nên về thực chất phương sai tổng thể chính là phương sai của biến ngẫu nhiên trong tổng thể đó. Nếu phân ánh mức độ phân tán của các giá trị của dấu hiệu  $\chi$  xung quanh giá trị trung bình tổng thể.

Trong thực tế, để tiện cho việc tính toán phương sai tổng thể thường được tính bằng công thức

$$\sigma^2 = \frac{1}{N} \sum_{i=1}^{k} N_i x_i^2 - m^2 \quad (6.13)$$

Nếu lấy cân bắc hai của phương sai ta sẽ thu được độ lệch chuẩn tổng thể:

$$\sigma = \sqrt{\sigma^2} = \sqrt{\frac{1}{N} \sum_{i=1}^{k} (x_i - m)^2}$$

3. Một loại tổng thể thường được nghiên cứu trong thực tế là tổng thể kích thước  $N$ , trong đó  $M$  phân tử mang dấu hiệu nghiên cứu, còn  $N-M$  phân tử còn lại không mang dấu hiệu đó. Lúc đó  $\sigma^2$  suy từ tổng thể là tỷ số giữa số phân tử mang dấu hiệu nghiên cứu và kích thước của tổng thể:

$$p = \frac{M}{N} \quad (6.14)$$

Ta thấy rằng  $p$  chính là xác suất để lấy ngẫu nhiên một phân tử thì phân tử đó mang dấu hiệu nghiên cứu. Như vậy, nếu xem dấu hiệu nghiên cứu là biến ngẫu nhiên  $X$  phân phối theo quy luật không - một thì  $p$  chính là kỳ vọng toàn, tức là thực chất  $\sigma^2$  suy từ tổng thể là tỷ số giữa số phân tử mang dấu hiệu nghiên cứu  $X$  và phân ánh cơ cấu của tổng thể theo dấu hiệu nghiên cứu  $\chi$ .

Vì có thể đặc trưng dấu hiệu nghiên cứu trong tổng thể bằng một biến ngẫu nhiên  $X$ , nên các tham số đặc trưng khác của  $X$  như Mốt, Trung vị, Hệ số biến thiên, Hệ số bất đối xứng, Hệ số nhọn v.v... cũng đều là các tham số đặc trưng của tổng thể. Biểu

thực tính các tham số này giống như đã trình bày ở mục 3 chương III.

### §3. MẪU NGẪU NHỊEN

#### 3.1. CÁC PHƯƠNG PHÁP CHỌN MẪU

Các tham số đặc trưng của tổng thể có thể xác định được một cách trực tiếp nếu áp dụng phương pháp nghiên cứu toàn bộ tổng thể. Song do những hạn chế như đã xét ở mục §1, chẳng hạn qui mô quá lớn của tổng thể hay mức độ kém tin cậy của số liệu điều tra nên việc tính toán vừa khó khăn, tổn kém mà vẫn không thu được kết quả chính xác. Đã biết khi không thể nắm được kích thước của tổng thể (và phải coi N là vô hạn) thì thực tế là không thể nghiên cứu trực tiếp tổng thể được. Vì vậy thường người ta áp dụng phương pháp mẫu bằng cách chọn ra từ tổng thể n phần tử và chỉ tập trung nghiên cứu các phần tử đó mà thôi. Tập hợp n phần tử này được gọi là mẫu kích thước n.

Để có thể cần cù vào thông tin của mẫu đưa ra những kết luận đủ chính xác về dấu hiệu nghiên cứu trong tổng thể thì trước hết mẫu được chọn phải mang tính đại diện cho tổng thể, tức là phân ánh đúng đặc điểm của tổng thể theo dấu hiệu nghiên cứu đó. Để đảm bảo tính đại diện của mẫu và tiện cho việc mô hình hóa, mẫu được tạo lập với những giả thiết sau:

- Lấy lần lượt từng phần tử vào mẫu. Phương pháp này gọi là phương pháp đơn giản để phân biệt với cách lấy cùng một lúc nhiều phần tử vào mẫu.

- Mỗi phần tử được lấy vào mẫu một cách hoàn toàn ngẫu nhiên, tức là mọi phần tử của tổng thể đều có thể được lấy vào mẫu với khả năng như nhau.

- Các phần tử được lấy vào mẫu theo phương thức hoàn lai, tức là trước khi lấy phần tử thứ k thì trả lại tổng thể phần tử thứ (k-1) mà ta đã nghiên cứu xong ( $k = 2, n$ ).

nhieu dấu hiệu cùng một lúc.

4. **Mẫu phân tố.** Trong chọn mẫu phân tố, trước hết người ta phân tích tổng thể ra thành các tổ có độ thuận nhất cao để chọn ra các phân tử đại diện cho từng tổ. Việc phân tố có hiệu quả khi tổng thể nghiên cứu không thuận nhất theo dấu hiệu nghiên cứu. Sau khi đã phân tổ thì kích thước mẫu được phân bố cho mỗi tổ theo một qui tắc nào đó, chẳng hạn tỷ lệ thuận với kích thước mỗi tổ.

5. **Mẫu nhiều cấp.** Nếu các phân tử của tổng thể phân tán quá rộng và thiếu thông tin về chúng, người ta thường chọn mẫu theo nhiều cấp. Khi chọn nhiều cấp, ta có nhiều loại đơn vị chọn mẫu ở mỗi cấp, thường được gọi là đơn vị chọn mẫu ở mỗi cấp, ở mỗi cấp chỉ cần có thông tin về phân bố của dấu hiệu ở cấp ấy là đủ.

Việc chọn mẫu ở mỗi cấp có thể tiến hành theo phương pháp mẫu ngẫu nhiên đơn, mẫu ngẫu nhiên hệ thống, mẫu chum hay mẫu phân tố.

#### 3.2. ĐỊNH NGHĨA MẪU NGẪU NHỊEN

Giả sử theo một phương pháp nào đó từ tổng thể lấy ra n phần tử tạo nên mẫu kích thước n. Vì mẫu được lấy ra theo nguyên tắc đơn giản, ngẫu nhiên và hoàn lại nên có thể hình hóa mẫu được chọn như sau.

Gọi  $X_i$  là giá trị của dấu hiệu  $\chi$  do lượng được trên phân tử thứ  $i$  của mẫu ( $i = 1, n$ ). Vì có thể mô hình hóa dấu hiệu  $\chi$  bằng một biến ngẫu nhiên  $X$  với một qui luật phân phối xác suất nào đó nên việc chọn mẫu kích thước n theo nguyên tắc trên có thể xem như tiến hành n phép thử độc lập đối với  $X$  và lúc đó các giá trị  $X_i$  của dấu hiệu thu được trên mẫu có thể xem như các biến ngẫu nhiên thu được qua việc tiến hành n phép thử độc lập đối với biến ngẫu nhiên  $X$ . Tùy do ta có định nghĩa sau:

Định nghĩa. Mẫu ngẫu nhiên kích thước  $n$  là tập hợp của  $n$  biến ngẫu nhiên độc lập  $X_1, X_2, \dots, X_n$  được thành lập từ biến ngẫu nhiên  $X$  và có cùng qui luật phân phối xác suất với  $X$ .

Mẫu ngẫu nhiên thường được ký hiệu là

$$W = (X_1, X_2, \dots, X_n)$$

Lúc đó việc thực hiện một phép thử đối với mẫu ngẫu nhiên  $W$  chính là thực hiện một phép thử đối với mỗi thành phần của mẫu. Giả sử  $X_1$  nhận giá trị  $x_1$ ;  $X_2$  nhận giá trị  $x_2$ ;  $\dots$   $X_n$  nhận giá trị  $x_n$ . Tập hợp  $n$  giá trị  $x_1, x_2, \dots, x_n$  tạo thành một giá trị của mẫu ngẫu nhiên, hay còn gọi là một mẫu cụ thể, ký hiệu

$$\omega = (x_1, x_2, \dots, x_n)$$

Thí dụ 3. Gọi  $X$  là số chấm xuất hiện khi tung một con xúc xắc,  $X$  là biến ngẫu nhiên với bảng phân phối xác suất sau.

| X | 1             | 2             | 3             | 4             | 5             | 6             |
|---|---------------|---------------|---------------|---------------|---------------|---------------|
| P | $\frac{1}{6}$ | $\frac{1}{6}$ | $\frac{1}{6}$ | $\frac{1}{6}$ | $\frac{1}{6}$ | $\frac{1}{6}$ |

Nếu tung con xúc xắc 3 lần và gọi  $X_i$  là số chấm xuất hiện trong lần tung thứ  $i$  ( $i = 1, 3$ ) thì ta có 3 biến ngẫu nhiên độc lập, có cùng qui luật phân phối xác suất với  $X$ . Vây ta có mẫu ngẫu nhiên kích thước  $n = 3$ ,  $W = (X_1, X_2, X_3)$  được xây dựng từ biến ngẫu nhiên gốc  $X$ .

Thực hiện một phép thử đối với mẫu ngẫu nhiên này tức là tung cụ thể ba lần. Giả sử lần thứ nhất được 6 chấm, lần thứ hai được 5 chấm, lần thứ ba được 1 chấm thì ta thu được một mẫu cụ thể  $\omega = (6, 5, 1)$ . Nếu thực hiện một phép thử khác với  $W$  lại thu được một giá trị khác của nó, chẳng hạn  $\omega = (2, 1, 4)$ ...

Ta chú ý rằng với cách xây dựng mẫu ngẫu nhiên như vậy thì các biến ngẫu nhiên  $X_1, X_2, \dots, X_n$  của mẫu không những có cùng dạng phân phối xác suất với biến ngẫu nhiên gốc  $X$ , tức là có cùng hàm phân bố xác suất  $F(x)$  mà các tham số đặc trưng của chúng cũng bằng các tham số đặc trưng của  $X$ , tức là:

$$E(X_1) = E(X_2) = \dots = E(X_N) = E(X) = M \quad (6.15)$$

$$V(X_1) = V(X_2) = \dots = V(X_N) = V(X) = \sigma^2$$

Chẳng hạn trong thí dụ trên mọi  $X_i$  ( $i = 1, 3$ ) đều có bảng phân phối xác suất như đã nêu ở trên, khi đó:

$$E(X_i) = \frac{1}{6} (1 + 2 + 3 + 4 + 5 + 6) = \frac{21}{6} = E(X)$$

$$V(X_i) = \frac{1}{6} (1^2 + 2^2 + 3^2 + 4^2 + 5^2 + 6^2) - \left(\frac{21}{6}\right)^2 = \frac{35}{12} = V(X)$$

#### 3.3. CÁC PHƯƠNG PHÁP MÔ TẢ MẪU NGẪU NHIÊN

1. Giả sử từ tổng thể với biến ngẫu nhiên gốc  $X$  rút ra một mẫu kích thước  $n$ , trong đó giá trị  $x_1$  xuất hiện với tần số  $n_1$ ,  $x_2$  xuất hiện với tần số  $n_2$ , ...,  $x_k$  xuất hiện với tần số  $n_k$ . Lúc đó sau khi các  $x_i$  đã được sắp xếp theo trình tự tăng dần giá trị cụ thể của mẫu  $\omega$  có thể mô tả bằng bảng phân phối tần số thực nghiệm sau

| $x_i$ | $x_1$ | $x_2$ | $\dots$ | $x_i$ | $\dots$ | $x_k$ |
|-------|-------|-------|---------|-------|---------|-------|
| $n_i$ | $n_1$ | $n_2$ | $\dots$ | $n_i$ | $\dots$ | $n_k$ |

Hiển nhiên là  $n_1 + n_2 + \dots + n_k = n$

2. Nếu ký hiệu

$$f_i = \frac{n_i}{n} \quad (6.16)$$

là tần suất xuất hiện giá trị  $x_i$  trong mẫu thì lúc đó giá trị của mẫu  $\omega$  còn có thể mô tả bằng pha phân phối tần suất thực nghiệm sau

| $x_i$ | $x_1$ | $x_2$ | $\dots$ | $x_i$ | $\dots$ | $x_k$ |
|-------|-------|-------|---------|-------|---------|-------|
| $f_i$ | $f_1$ | $f_2$ | $\dots$ | $f_i$ | $\dots$ | $f_k$ |

Từ (6.16) suy ra  $f_1 + f_2 + \dots + f_k = 1$

Thí dụ 4. Gạt ngẫu nhiên 365 điểm trọng lúa của một huyện thu được các số liệu được sắp xếp thành bảng sau

| Năng suất<br>(tạ/ha) | 25 | 30 | 33 | 34 | 35  | 36 | 37 | 39 | 40 |
|----------------------|----|----|----|----|-----|----|----|----|----|
| Số điểm gạt          | 6  | 13 | 38 | 74 | 106 | 85 | 30 | 10 | 3  |
| tương ứng            |    |    |    |    |     |    |    |    |    |

Như vậy giá trị của mẫu đã được mô tả dưới dạng bảng phân phối tần số thực nghiệm. Còn bảng phân phối tần suất thực nghiệm có dạng

| $x_i$ | 25    | 30    | 33    | 34    | 35    | 36    | 37    | 39    | 40    |
|-------|-------|-------|-------|-------|-------|-------|-------|-------|-------|
| $f_i$ | 0,016 | 0,036 | 0,104 | 0,203 | 0,290 | 0,233 | 0,082 | 0,027 | 0,009 |

3. Nếu ký hiệu  $\omega_i$  ( $i = \overline{1, k}$ ) là tần số tích lũy của  $x_i$

$$\omega_i = \sum_{x_j < x_i} n_j \quad (6.17)$$

và  $F^*(x_i)$  là tần suất tích lũy của  $x_i$

$$F^*(x_i) = \frac{\omega_i}{n} = \sum_{x_j < x_i} \frac{n_j}{n} \quad (6.18)$$

thì  $F^*(x_i)$  là một hàm của  $x_i$  và gọi là hàm phân bố thực nghiệm của mẫu.

Khác với hàm phân bố xác suất  $F(x)$  của biến ngẫu nhiên gốc  $X$  trong tổng thể xác định xác suất của biến cố  $X < x$ , hàm phân bố thực nghiệm  $F^*(x)$  xác định tần suất của biến cố đó. Theo định lý Bernoulli, tần suất của biến cố  $X < x$  tức là  $F^*(x)$  sẽ hội tụ theo xác suất về xác suất  $F(x)$  của biến cố đó, tức là  $F^*(x)$  và  $F(x)$  sai khác nhau không đáng kể. Từ đó có thể dùng hàm phân bố thực nghiệm của mẫu để biểu diễn một cách gần đúng qui luật phân phối gốc  $F(x)$  của tổng thể.

4. Để mô tả số liệu mẫu một cách rõ ràng hơn cho phép đưa ra những nhận xét sơ bộ ban đầu về tổng thể, người ta còn xây dựng các loại đồ thị khác nhau của phân phối thực nghiệm.

- Da giac tan so la mot duong gay khuc ma cac doan thang  
cua no noi cac diem  $(x_1, n_1)$ ,  $(x_2, n_2)$ ...  $(x_k, n_k)$  tren mat phang.

- Da giac tan suat la mot duong gay khuc ma cac doan thang  
cua no noi cac diem  $(x_1, f_1)(x_2, f_2)$ ...  $(x_k, f_k)$  tren mat phang.

Thi du 5. Ve da giac tan suat của phân phối thực nghiệm  
sau:

![](0a8d173734e4e46c344178e8d21bcbc3_img.jpg)

Figure 6.1 shows a histogram (Da giac tan suat) for a discrete probability distribution. The horizontal axis ( $x_i$ ) is labeled with values 1, 3, 5, 7. The vertical axis ( $f_i$ ) is labeled with values 0.1, 0.3, 0.4, 0.2. The bars represent the frequencies  $f_i$  for the classes  $x_i$ .

Hình 6.1. Da giac tan suat

Da giac tan suat thường được dùng để mô tả các số liệu mẫu  
theo thời gian.

- Khi dấu hiệu nghiên cứu có phân phối liên tục thì nên xây  
dựng biểu đồ tán so hoặc biểu đồ tán suát. Để làm điều đó  
khoảng chia tất cả các giá trị quan sát được của mẫu được chia  
ra thành một số đoạn có chiều dài bằng  $h$  và tại mỗi đoạn đưa  
vào các tần số hoặc tần suất tương ứng với đoạn đó. Như vậy  
biểu đồ tán số sẽ là một hình bậc thang tạo nên bởi nhiều hình  
chữ nhật có đáy bằng  $h$  và chiều cao bằng  $\frac{n_i}{h}$ . Lúc đó diện tích  
của hình chữ nhật thứ  $i$  bằng  $h \cdot \frac{n_i}{h} = n_i$  - tổng tần số ứng với đoạn

thứ i, vì vậy diện tích của tất cả các hình chữ nhật sẽ bằng kích thước mẫu n.

Tương tự biểu đồ tán suất là một hình bắc thang tạo nên bởi nhiều hình chữ nhật có đáy bằng h và chiều cao bằng  $\frac{f_i}{h}$ . Lục đồ diện tích của hình chữ nhật thứ i bằng  $\frac{f_i}{h} = f_i$ , và diện tích của toàn bộ hình bắc thang đó sẽ bằng một.

**Thí dụ 6.** Về biểu đồ tán số của phân phối thực nghiệm cho ô bảng sau

Bảng 6.3

| Đoạn giá trị chiếu<br>dài $h = 5$ | Tổng các tán số<br>tương ứng $n_i$ | $\frac{n_i}{h}$ |
|-----------------------------------|------------------------------------|-----------------|
| 5 - 10                            | 4                                  | 0,8             |
| 10 - 15                           | 6                                  | 1,2             |
| 15 - 20                           | 16                                 | 3,2             |
| 20 - 25                           | 36                                 | 7,2             |
| 25 - 30                           | 24                                 | 4,8             |
| 30 - 35                           | 10                                 | 2,0             |
| 35 - 40                           | 4                                  | 0,8             |

![Histogram showing the frequency distribution of the sample data. The x-axis represents the class intervals (0 to 40) and the y-axis represents the frequency (n_i/h). The bars are centered at 5, 10, 15, 20, 25, 30, and 35, with heights corresponding to the frequencies 0.8, 1.2, 3.2, 7.2, 4.8, 2.0, and 0.8 respectively.](fc857414626a8d94d132e12d9afe52a4_img.jpg)

Histogram showing the frequency distribution of the sample data. The x-axis represents the class intervals (0 to 40) and the y-axis represents the frequency (n\_i/h). The bars are centered at 5, 10, 15, 20, 25, 30, and 35, with heights corresponding to the frequencies 0.8, 1.2, 3.2, 7.2, 4.8, 2.0, and 0.8 respectively.

Hình 6.2 Biểu đồ tán số

Với các dấu hiệu nghiên cứu là định tính thì người ta thường mô tả các số liệu mẫu bằng biểu đồ hình bánh xe. Đó là một hình tròn được chia ra thành nhiều bộ phận tương ứng với cơ cấu của pham trù xuất hiện trong mẫu.

Thí dụ 7. Điều tra ngẫu nhiên 100 khách hàng của doanh nghiệp thì thấy các khách hàng được phân theo tỷ lệ sau đây về tầng lớp xã hội (bảng 6.4).

Bảng 6.4

| Tầng lớp xã hội | Số khách hàng | Tỷ lệ |
|-----------------|---------------|-------|
| Công nhân       | 35            | 0,35  |
| Nông dân        | 40            | 0,40  |
| Thương nhân     | 15            | 0,15  |
| Trí thức        | 10            | 0,10  |
| Tổng số         | 100           | 1     |

Vẽ biểu đồ hình bánh xe về cơ cấu của 100 khách hàng được điều tra (hình 6.3)

![Pie chart showing the distribution of 100 customers by social class. The percentages are: Công nhân (35%), Nông dân (40%), Thương nhân (15%), and Trí thức (10%).](a706c91f074ac2840c161a3d4a7c0f91_img.jpg)

Pie chart showing the distribution of 100 customers by social class. The percentages are: Công nhân (35%), Nông dân (40%), Thương nhân (15%), and Trí thức (10%).

Hình 6.3. Biểu đồ hình bánh xe

Đồ thị của phân phối mẫu có thể vẽ để dạng như việc sử dụng các phần mềm cho máy vi tính. Mọi phần mềm thông kê như Excel, SPSS, MFit, Stata đều có chương trình cho phép vẽ