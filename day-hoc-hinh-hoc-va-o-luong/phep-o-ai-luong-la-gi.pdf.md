

PTS. TRẦN DIỆN HIẾN  
VŨ QUỐC CHUNG

# SỐ VÀ ĐẠI LƯỢNG

TRƯỜNG ĐẠI HỌC SƯ PHẠM HÀ NỘI I  
HÀ NỘI - 1994

## CHƯƠNG IIPHÉP ĐO ĐẠI LƯƠNG

Mỗi đại lượng có một tập hợp những giá trị của nó, vấn đề đặt ra là biểu diễn được các giá trị của đại lượng. Chẳng hạn, để sản xuất một loại sản phẩm nào đó, cần tính toán xem phải có bao nhiêu nguyên vật liệu ứng với một đại lượng; loại thì tính bằng độ dài, loại thì tính bằng thể tích hay diện tích, loại thì tính bằng khối lượng. Ta cần phải chỉ ra những giá trị của các đại lượng cần biết cho sản xuất, vì thế phải biểu diễn được những giá trị này. Để giải quyết vấn đề này ta sẽ đặt trưng các giá trị của đại lượng bởi các số, lấy tập hợp số làm căn cứ chung. Nói một cách khác ta sẽ gán cho mỗi giá trị của đại lượng một số sao cho các quan hệ cơ bản giữa các giá trị của đại lượng vẫn được bảo toàn khi chuyển từ đại lượng sang số. Việc làm như vậy gọi là phép đo đại lượng. Trong nội dung tiết này ta chủ ý chủ yếu đến các đại lượng vô hướng cộng được và thừa nhận mọi đại lượng vô hướng đều có phép đo hay nói là đo được.

### I. ĐO ĐẠI LƯƠNG VÔ HƯỚNG CỘNG ĐƯỢC.

#### 1. Định nghĩa.

Giả  $(X, \sim, \le, +)$  là đại lượng vô hướng cộng được  $e \in X/\sim$ , e không phải là phần tử không của  $X/\sim$ .  $(R_+, +, \le)$  như đã biết là vị nhóm sắp thứ tự Acsimet. Ta gọi là phép đo của đại lượng vô hướng cộng được  $(X, \sim, \le, +)$  với đơn vị đo là e mọi ánh xạ

$$d: X/\sim \to R_+$$

thỏa mãn các điều kiện

i)  $d$  là đơn cấu vị nhóm đơn điệu.

ii)  $d(e) = 1$

Khi đó  $(X, \sim, \le, +)$  được gọi là đại lượng vô hướng cộng được và do được.

Với  $a \in X/\sim$ ,  $d(a)$  được gọi là số do của giá trị  $a$ .

#### 2. Tính chất của phép do.

2.1. Định lý: Giá sử  $(X, \sim, \le, +)$  là một đại lượng vô hướng cộng được và do được;  $e' \in X/\sim$  và  $e' \neq 0$ . Khi đó có một phép do đại lượng vô hướng cộng được với đơn vị do là  $e'$ .

Chứng minh:

Vì  $(X, \sim, \le, +)$  là một đại lượng vô hướng cộng được và do được nên theo định nghĩa phải có một phép do  $d$  nào đó với đơn vị do là  $e$  ứng với nó, chẳng hạn

$$d: X/\sim \to R_+, d(e) = 1.$$

$d$  là đơn cấu vị nhóm và  $e' \neq 0$  nên  $e' > 0$ , do đó  $d(e') > 0$  xét ánh xạ.

$$d': X/\sim \to IR_+$$

$$x \to d'(x) = \frac{d(x)}{d(e')}$$

Ta sẽ chứng minh  $d'$  là phép do đại lượng vô hướng cộng được  $(X, \sim, \le, +)$  với đơn vị do là  $e'$ .

Với mọi  $x, y \in X/\sim$  ta có:

$$d'(x + y) = \frac{d(x+y)}{d(e')} = \frac{d(x)+d(y)}{d(e)}$$

$$= \frac{d(x)}{d(e')} + \frac{d(y)}{d(e')} = d'(x) + d'(y)$$

với mọi  $x, y \in X/\sim$ ,  $x \le y$ , thì  $d(x) \le d(y)$  (d đơn điệu)  
nên

$$\frac{d(x)}{d(e')} \le \frac{d(y)}{d(e')} \text{ hay } d'(x) \le d'(y)$$

vậy  $d'$  là đơn cấu vị nhóm đơn điệu và

$$d'(e') = \frac{d(e')}{d(e')} = 1.$$

Do đó  $d'$  là phép đo đại lượng nhận  $e'$  làm đơn vị.

##### 2.2. Phép đổi đơn vị đo.

Giả sử  $d$  và  $d'$  là hai phép đo đại lượng vô hướng cộng được  $(X, \sim, \le, +)$  với các đơn vị đo tương ứng là  $e$  và  $e'$ . Việc chuyển từ phép đo  $d$  với đơn vị  $e$  sang phép đo  $d'$  với đơn vị  $e'$  được gọi là phép đổi đơn vị đo.

Theo kết quả chứng minh trong định lý 2.1 trên ta có:

$$d'(x) = \frac{d(x)}{d(e')}, \quad \forall x \in X/\sim.$$

$$d'(e) = \frac{d(e)}{d(e')} = \frac{1}{d(e')}$$

do đó có hệ thức biến đổi

$$d'(x) = d(x) \cdot d'(e) (*)$$

$$\text{và } d'(e) \cdot d(e') = 1$$

Công thức (\*) gọi là công thức đổi đơn vị đo.

Như vậy, khi chuyển từ đơn vị đo thứ nhất sang đơn vị đo thứ hai thì số đo đại lượng theo đơn vị đo thứ hai bằng số đo đại lượng theo đơn vị thứ nhất nhân với số đo của đơn vị đo thứ nhất theo đơn vị đo thứ hai.

#### 3. Tỉ số của hai giá trị của đại lượng vô hướng cộng được

##### 3.1. Định nghĩa:

Giả sử  $d$  là phép đo đại lượng vô hướng cộng được  $(X, \sim, \le, +)$ , ta gọi tỉ số hai giá trị  $a, b$  ( $b \neq 0$ ) của đại lượng này là tỉ số các số đo tương ứng  $d(a), d(b)$  của chúng và ta viết.

$$\frac{a}{b} = \frac{d(a)}{d(b)}$$

- Tỉ số  $\frac{a}{b}$  không phụ thuộc phép đo  $d$  mà chỉ phụ thuộc vào các giá trị  $a, b$  của đại lượng. Thật vậy, giả sử  $d'$  cũng là phép đo đại lượng vô hướng cộng được  $(X, \sim, \le, +)$  với đơn vị đo  $e'$ , ta có:

$$d'(a) = \frac{d(a)}{d(e')} \quad \text{và} \quad d'(b) = \frac{d(b)}{d(e')}$$

$$\text{Từ đó:} \quad \frac{d'(a)}{d'(b)} = \frac{d(a)}{d(e')} : \frac{d(b)}{d(e')} = \frac{d(a)}{d(b)}$$

##### 3.2 Biểu diễn giá trị một đại lượng

Giả sử  $d: X/\sim \to \mathbb{R}_+$  là một phép đo đại lượng vô hướng cộng được  $(X, \sim, \le, +)$  với đơn vị đo là  $e$ , và  $a \in X/\sim$ .

Khi đó:

$$\frac{a}{e} = \frac{d(a)}{d(e)} = d(a)$$

Đặt  $a = d(a)e$  và gọi đó là biểu diễn của giá trị  $a$  theo đơn vị  $e$ .

Vậy mỗi giá trị của đại lượng vô hướng cộng được đều biểu diễn được theo đơn vị của phép đo bằng số đo giá trị đó.

Chú ý:

1) Giá sử  $d$  là phép đo của đại lượng vô hướng cộng được  $(X, \sim, \le, +)$  với đơn vị  $e$ . Khi đó ảnh  $x$

$$D: x \to R_+$$

$$x \to D(x) = d(x)$$

Được gọi là phép đo của tập hợp  $X$  với đơn vị đo là  $e$ . Ta thường viết  $a = D(a)e$  thay cho ký hiệu  $a = d(a)e$  và gọi đó là biểu diễn của  $a$  theo đơn vị đo  $e$ .

2. Chỉ có thể so sánh và cộng các số đo đại lượng cùng loại (được hiểu là có cùng đơn vị đo), không thể so sánh và cộng các số đo đại lượng khác loại: nếu nhân số đo một đại lượng với một số tự nhiên hay tháp phân thì ta được một số đo đại lượng cùng loại. Chẳng hạn không thể so sánh  $1m$  với  $1$  giờ, hoặc cộng  $1m$  với  $20$  giây vì độ dài và thời gian là hai đại lượng khác nhau.

3) Đơn vị đo có thể chọn tùy ý, nhưng khi đơn vị này đã được xác định thì số đo đại lượng phụ thuộc vào đơn vị đo đã chọn.

Ví dụ:

a) Ta có đơn vị độ dài là mét, ký hiệu  $m$ . Nối cái bàn này dài  $1,8m$  có nghĩa là trong phép đo độ dài với đơn vị là mét thì độ dài cái bàn có số đo là  $1,8$ .

b) Lấy hai phép đo độ dài  $D$  và  $D'$  tương ứng với đơn vị  $met(m)$  và centimet ( $cm$ ). Ta có:

$$D'(m) = 100 \text{ và } D(cm) = 0,01.$$

$$\text{Rõ ràng } D'(m) \cdot D(cm) = 1.$$

Nếu đo đoạn thẳng  $a$  với phép đo  $D$  có đơn vị  $met(m)$  được  $D(a) = 5$  thì  $a = 5m$ .

Nếu đo đoạn thẳng  $a$  với phép đo  $D'$  có đơn vị centimet ( $cm$ ) thì:

$$D'(a) = D(a) \cdot D'(m) = 5 \cdot 100 = 500 \text{ và } a = 500 \text{ cm.}$$

### II. HỆ THỐNG ĐƠN VỊ ĐO

#### 1. Yêu cầu đối với đơn vị đo.

Việc đo đại lượng là một phép biểu diễn giá trị của đại lượng bằng các số, việc đề xuất khái niệm đơn vị của một phép đo là đương nhiên. Từ sự tồn tại của phép đo, ta đã chứng minh được sự tồn tại của đại lượng với đơn vị chọn trước. Song việc chọn một giá trị nào đó của đại lượng làm đơn vị không được tùy tiện ngẫu nhiên, mà phải căn cứ ở lý thuyết định tính của khoa học, ở khâu kĩ thuật thực hành và cả ở khả năng hoạt động thực tiễn. Thường đơn vị đo đại lượng được chọn phải đảm bảo các yêu cầu.

- Phân ảnh được thành tựu khoa học cơ bản và hiện đại nhất.

- Thuận tiện cho khâu kĩ thuật thực hành.

- Đơn vị chọn phải dễ đạt được độ chính xác cao và sát với thực tiễn sản xuất; phải dễ quan niệm, đồng thời dễ có những dụng cụ dễ đo lường.

Bây giờ ta sẽ đề cập mới liên quan giữa các đại lượng.

#### 2. Đại lượng cơ bản và đại lượng dẫn xuất.

Quan sát các đại lượng ta thấy có những đại lượng mà việc xác định lại dựa vào những đại lượng khác một cách trực tiếp hoặc lại phụ thuộc ở một mức độ nào đó. Từ đó ta có khái niệm đại lượng cơ bản và đại lượng dẫn xuất.

- Đại lượng cơ bản là đại lượng mà việc chọn đơn vị đo nó là độc lập. Trong phạm vi chương trình toán tiểu học ta có ba đại lượng cơ bản là: độ dài, khối lượng, và thời gian.

- Đại lượng dẫn xuất là đại lượng mà đơn vị đo nó được chọn suy từ những đơn vị của các đại lượng cơ bản. Ví dụ như vận tốc, (có thể coi là đại lượng vô hướng như đã lưu ý ở phần trước), đơn vị đo nó như ta đã biết phải dựa vào đơn vị

độ dài và đơn vị thời gian. Ta đã gặp một số đại lượng dẫn xuất từ ba đại lượng cơ bản trên trong phạm vi hình học và cơ học: diện tích, thể tích, vận tốc, gia tốc, lực, công...

Có những đại lượng vừa có thể chọn làm đại lượng cơ bản, vừa có thể chọn làm đại lượng dẫn xuất. Song ta cần lựa chọn sao cho được thuận lợi nhất cho hoạt động kĩ thuật và thực tiễn. Các đại lượng được chọn làm đại lượng cơ bản cần đạt các yêu cầu tối thiểu sau:

+ Chúng phải độc lập với nhau, chẳng hạn độ dài và thời gian là hai đại lượng độc lập với nhau, có thể chọn chúng làm đại lượng cơ bản. Song như ta đã biết độ dài và diện tích là hai đại lượng có liên quan mật thiết với nhau, vì thế độ dài và diện tích không thể đồng thời là đại lượng cơ bản được.

+ Đại lượng cơ bản phải là những đại lượng đơn giản, dễ nhận thức.

+ Đại lượng cơ bản phải chọn sao cho có thể đo được trực tiếp dễ dàng và chính xác.

#### 3. Đơn vị đo những đại lượng cơ bản.

31. Đơn vị độ dài: là met, kí hiệu m.

Ở cuối thế kỉ 18 người ta xác định mét bằng  $10^{-7}$  của một phần tư kinh tuyến trái đất. Song trong quá trình phát triển của khoa học, kĩ thuật trắc địa cũng phát triển và đo được kinh tuyến trái đất ngày một chính xác hơn; vì thế, giữ định nghĩa trên đây về mét sẽ có trở ngại là độ dài đo không ổn định. Đến cuối thế kỉ 19, người ta làm một chuẩn mét ở khả năng lúc đó và lấy làm cơ định. Muốn vậy, cần chọn và chế tạo chuẩn gốc bằng một kim loại không gỉ có nhiệt độ nóng chảy cao và có hệ số nở tương đối thấp. Người ta đã chọn platinum có pha iridium cho cứng hơn.

Một loại chuẩn gốc quốc tế và quốc gia đã được chế tạo,

đó là những thanh platin pha 10% iridium có độ dài 102cm, ở hai đầu có những vạch để xác định khoảng cách bằng 1 mét.

Chuẩn này đạt được độ chính xác tối 4.10<sup>-7</sup>. Độ chính xác này thỏa mãn được nhiều hoạt động sản xuất và kiểm thử, song do sự phát triển của khoa học gần đây nó không đáp ứng được yêu cầu nghiên cứu. Chúng hạn trong lĩnh vực nghiên cứu hạt nhân độ chính xác cần đạt từ 10<sup>-9</sup> đến 10<sup>-13</sup>, hơn nữa trong việc so sánh các chuẩn thế vi phải chịu tác động cơ học nên dễ mất chính xác: thực tế đã có những chuẩn dài ra và có những chuẩn ngắn đi. Để khắc phục nhược điểm này từ năm 1933 người ta đã tìm cách thay thế chuẩn platin bằng một chuẩn khác, đó là chuẩn bằng bao sông ánh sáng. Chuẩn này gắn liền với một hiện tượng tự nhiên về vật lý nên đạt độ chính xác cao hơn, đồng thời nó không phù hợp định chuẩn cũ với nghĩa là nếu chỉ cần độ chính xác 10<sup>-7</sup> thì chuẩn cũ và chuẩn mới về mét là như nhau.

3.2 Đơn vị khối lượng là kilogram, kí hiệu: kg. Kilogram là khối lượng của một khối bạch kim pha iridium hình trụ, có đường cao là 39mm và bằng đường kính đáy. Độ là chuẩn gốc quốc tế. Chuẩn này đạt độ chính xác khá cao, tối 3.10<sup>-9</sup> và đã đo được khối lượng của 1dm<sup>3</sup> nước ở 4°C là 0,999973 kg.

Về đơn vị khối lượng người ta cũng đã có dự định tìm một khối lượng tự nhiên như khối lượng quả đất hay khối lượng một điện tử đúng yến để làm chuẩn, song việc đo những khối lượng ấy hiện nay chưa đạt được độ chính xác cần thiết. Trước kia, để gắn cho kilogram một chuẩn tự nhiên, người ta lấy ki lô gam là khối lượng của 1dm<sup>3</sup> nước tinh khiết ở nhiệt độ 4°C. Song nó cũng có những khó khăn gấp phải với định nghĩa đó nên cùng với việc làm chuẩn mét bằng bạch kim người ta đã công nhận chuẩn kilogram như trên.

##### 3.3. Đơn vị thời gian là giây, kí hiệu s.

Trước đây người ta lấy ngày mặt trời trung bình làm chuẩn để xác định đơn vị thời gian. Giây là khoảng thời gian bằng một phân  $86.400$  của một ngày mặt trời trung bình. Song máy chục năm trở lại đây những quan sát thiên văn cho thấy ngày mặt trời trung bình không phải là hàng số vì chuyển động của trái đất quanh trục của nó không đều và người ta không tính trước được những biến thiên của vận tốc quay đó. Bây giờ chọn năm tropic làm chuẩn để xác định đơn vị thời gian là giây.

Năm tropic là khoảng thời gian mặt trời xuất phát từ điểm xuân phân trở lại điểm ấy sau khi đi được một vòng hoàng dao. (Vòng hoàng dao là quỹ đạo chuyển động của mặt trời quay chung quanh trái đất). Người ta đo được khả chính xác năm tropic và tính được cả biên thiên của năm tropic. Cứ mỗi thế kỉ năm tropic lại ngắt đi mất  $0,5303$  giây. Vì năm tropic không phải là hàng số cho nên người ta đã chọn cụ thể năm tropic  $1900$  làm chuẩn để xác định đơn vị thời gian. Ta có định nghĩa của đơn vị thời gian là giây như sau:

Giây là một phân  $31556925,9797$  của năm tropic tính cho năm  $1900$ .

Với định nghĩa này ta đạt độ chính xác tới  $10^{-9}$ . Độ chính xác này đáp ứng được yêu cầu của khoa học và kĩ thuật hiện đại, trong khi đó với định nghĩa giây lấy ngày mặt trời trung bình làm chuẩn thì chỉ đạt được độ chính xác  $10^{-7}$ .

Như vậy, ta đã làm quen đơn vị chuẩn của ba đại lượng cơ bản. Để cho thuận tiện trong sản xuất và kĩ thuật, mỗi đơn vị có những ước và bội của nó:

- Đơn vị độ dài:

Deximet (dm):  $1 \text{ dm} = 10^{-1} \text{ m}$

Centimet (cm):  $1 \text{ cm} = 10^{-2} \text{ m}$

Milimet (mm);  $1 \text{ mm} = 10^{-3} \text{ m}$

Micromet ( $\mu\text{m}$ );  $1 \mu\text{m} = 10^{-6} \text{ m}$

Décamet (dam);  $1 \text{ dam} = 10 \text{ m}$

Hectomet (hm);  $1 \text{ hm} = 10^2 \text{ m}$

Kilomet (km);  $1 \text{ km} = 10^3 \text{ m}$

- Đơn vị khối lượng

Hectogram (hg);  $1 \text{ hg} = 10^{-1} \text{ kg}$

Decagram (dag);  $1 \text{ dag} = 10^{-2} \text{ kg}$

Gram (g);  $1 \text{ g} = 10^{-3} \text{ kg}$

Decigram (dg);  $1 \text{ dg} = 10^{-4} \text{ kg}$

Centigram (cg);  $1 \text{ cg} = 10^{-6} \text{ kg}$

Tạ;  $1 \text{ tạ} = 10^2 \text{ kg}$

Tấn;  $1 \text{ tấn} = 10^3 \text{ kg}$

- Đơn vị thời gian

Phút;  $1 \text{ phút} = 60 \text{ s}$

Giờ (h);  $1 \text{ h} = 60 \text{ phút} = 36 \cdot 10^2 \text{ s}$

1 ngày = 24 h.

1 tuần lễ = 7 ngày.

1 tháng = 30 ngày (31 ngày)

1 năm = 12 tháng

1 thế kỉ = 100 năm

1 thiên niên kỉ = 1000 năm.

#### 4. Đơn vị những đại lượng dẫn xuất.

Gọi L, M, T lần lượt là đại lượng độ dài, khối lượng và thời gian. Mỗi đại lượng dẫn xuất và từ đó đơn vị của nó sẽ

được xác định bởi một biểu thức liên hệ giữa  $L$ ,  $M$ ,  $T$  gọi là thứ nguyên.

4.1. Đơn vị diện tích là mét vuông ( $m^2$ )

Mét vuông là diện tích một hình vuông có cạnh là 1m.

$$S = ab \text{ với } a = b = 1\text{m.}$$

Thứ nguyên là  $L^2$ .

4.2. Đơn vị thể tích là mét khối ( $m^3$ )

Mét khối là thể tích của một hình lập phương có cạnh là 1m.

$$V = abc \text{ với } a = b = c = 1\text{m}$$

Thứ nguyên là  $L^3$ .

4.3. Đơn vị khối lượng riêng là kilogram trên mét khối ( $\text{kg}/\text{m}^3$ ).

Kilogram trên mét khối là khối lượng riêng của một vật đồng chất có khối lượng 1kg và thể tích là  $1\text{m}^3$ .

$$P = \frac{m}{V} \text{ với } m = 1\text{kg}, V = 1\text{m}^3$$

Thứ nguyên là  $L^{-3} M$ .

4.4. Đơn vị vận tốc là mét trên giây ( $\text{m}/\text{s}$ ). Mét trên giây là vận tốc của một chuyển động đều đi được đoạn đường 1m trong thời gian một giây.

$$v = \frac{1}{t}, \text{ với } l = 1\text{m}, t = 1\text{s}$$

Thứ nguyên là  $L T^{-1}$ .

4.5. Đơn vị gia tốc là mét trên giây bình phương ( $\text{m}/\text{s}^2$ )

Mét trên giây bình phương là gia tốc của 1 vật có vận tốc thay đổi đều 1 mét trên giây trong thời gian một giây:

$$a = \frac{v_2 - v_1}{t} \quad \text{với } v_2 - v_1 = 1 \text{m/s và } t = 1 \text{ s}$$

Thứ nguyên là  $L \cdot T^{-2}$

4.6. Đơn vị lực (và trọng lượng) là Niuoton (N). Niuoton là lực gây cho 1 vật có khối lượng 1kg, gia tốc  $1 \frac{m}{s^2}$ .

$$F = ma \quad \text{với } m = 1 \text{ kg, } a = 1 \frac{m}{s^2}$$

Thứ nguyên là  $L \cdot M \cdot T^{-2}$

4.7. Đơn vị áp suất là Niuoton trên mét vuông ( $N/m^2$ ). Niuoton trên mét vuông là áp suất gây nên trên diện tích phẳng  $1 m^2$  bởi một hệ học vuông góc với diện tích và phân bố đều mà tổng là một Niuoton.

$$P = \frac{F}{S} \quad \text{với } F = 1 \text{ N và } S = 1 \text{ m}^2$$

Thứ nguyên là  $L^{-1}MT^{-2}$

4.8. Đơn vị trọng lượng riêng là Niuoton trên mét khối ( $N/m^3$ ). Niuoton trên mét khối là trọng lượng riêng của một vật đóng chất có trọng lượng là 1 Niuoton và thể tích là  $1 m^3$ .

$$v = \frac{F}{V} \quad \text{với } F = 1 \text{ N và } V = 1 \text{ m}^3$$

Thứ nguyên là  $L^{-2}MT^{-2}$

4.9. Đơn vị công và năng lượng là Jun (J).

Jun là công tạo nên khi một lực 1 Niuoton điền điểm đặt 1 mét theo hướng của lực.

$$A = F \cdot S \quad \text{với } F = 1 \text{ N và } S = 1 \text{ m (1 J = 1 Nm)}$$

Thứ nguyên là  $L^2MT^{-2}$

4.10. Đơn vị công suất là oat (W).

Oát là công suất được xác định khi một công 1 Jun được sản ra trong thời gian 1 giây.

$$P = \frac{A}{t} \text{ với } A = 1 \text{ Jun và } t = 1 \text{ s (1w = 1J/s)}$$

Thứ nguyên, là  $L^2 \text{MT}^{-3}$

Cùng như các đại lượng cơ bản, các đại lượng dẫn xuất trên đây trong thực tế cũng còn dùng những đơn vị khác nữa, đó là các ước và bội của những đơn vị đã nêu. Một số đại lượng nêu ở trên là đại lượng vectơ, nhưng ta giả thiết bỏ qua được yếu tố phương và chiều.

### BÀI TẬP CHƯƠNG II

1. Giả sử  $d$  là một phép đo của đại lượng vô hướng cộng được  $(X, \sim, \le, +)$  với đơn vị đo là  $e$  và  $x \in X/\sim$ .

1) Chứng minh rằng tập hợp

$$N_x = \{n.x \mid n \in N\}$$

là một vị nhóm con của vị nhóm  $(X/\sim, +)$ .

2) Chứng minh rằng  $d(n.x) = nd(x)$ ,  $\forall n \in N$

Dặc biệt  $d(ne) = n$

3) Chứng minh rằng với  $n, m \in N$ , nếu  $n \le m$  thì  $nx \le mx$ . Dặc biệt  $ne \le me$ .

2. Giả sử phép đo  $d$  của đại lượng vô hướng cộng được  $(X, \sim, \le, +)$  với đơn vị  $e$  là đẳng cấu. Chứng minh rằng.

1) Với mọi  $n \in N^*$ , có  $x \in X$  sao cho  $d(x) = \frac{1}{n}$

2) Với mọi  $\frac{a}{b} \in Q_+$ , có  $y \in X$  sao cho  $d(y) = \frac{a}{b}$

3. Giả sử  $d$  là một phép đo của đại lượng vô hướng cộng

được  $(X, \sim, \le, +)$  với đơn vị đo là e, D là phép đo của tập hợp X với đơn vị đo e. Chứng minh rằng với  $x, y \in X$ ,  $D(x) = D(y)$   $\Leftrightarrow x \sim y$ .

4. Giả sử d là một phép đo của đại lượng vô hướng cộng được  $(X, \sim, \le, +)$  với đơn vị đo là e,  $n \in \mathbb{N}^*$ . Tìm phép đo d' của đại lượng này và tìm đơn vị đo của phép đo d' sao cho với mọi  $x \in X$ ,  $x \neq 0$  có:

$$\frac{d(x)}{d'(x)} = n$$

5. Giả sử  $(X, \sim, \le, +)$  là một đại lượng vô hướng cộng được và đo được. Chứng minh rằng:

$$\frac{x+y}{z} = \frac{x}{z} + \frac{y}{z}; \frac{0}{z} = 0$$

với mọi  $x, y, z \in X \sim$  và  $z \neq 0$

6. Hãy nêu một vài ví dụ về đại lượng đã gặp trong chương trình toán tiểu học, chứng tỏ rằng có nhiều phép đo với đơn vị khác nhau đối với cùng một đại lượng.

7. Nhiệt kế chỉ ngày thứ hai là  $25^\circ\text{C}$ , ngày thứ 3 giảm  $5^\circ\text{C}$ , ngày thứ tư tăng  $3^\circ\text{C}$ , ngày thứ 5 và 6 tăng  $4^\circ\text{C}$ , ngày thứ 7 giảm  $6^\circ\text{C}$ . Nhiệt độ giữa ngày thứ hai và ngày khác nhau là

(A)  $-40^\circ\text{C}$  C:  $+5^\circ\text{C}$

(B)  $+7^\circ\text{C}$  D:  $+4^\circ\text{C}$

Hãy đánh dấu (x) vào chỗ đúng.

8. Tàu hỏa chạy với tốc độ  $37\text{km}/\text{giờ}$  thì chạy quãng đường  $78\text{km}$  sẽ mất khoảng thời gian là:

(A):  $0,7$  giờ (C):  $1,2$  giờ (E):  $2,1$  giờ

(B):  $0,5$  giờ (D):  $2,0$  giờ

Hãy đánh dấu (x) vào chỗ đúng

9. Sửa được đo lượng bởi (danh dấu (x) vào đơn vị đúng)

(A) kg; (B) miligam; (C) lít; (D) mét

## HƯỚNG DẪN TƯ HỌC

### 1. Những kiến thức chuẩn bị:

Học viên cần ôn lại để nắm vững các kiến thức đã học trong chương I, trong lý thuyết tập hợp và cấu trúc đại số. Cụ là:

- Cấu trúc đại số của các tập hợp  $N$ ,  $\mathbb{Q}_+$ ,  $\mathbb{R}_+$ .
- Khái niệm vị nhóm và cách chứng minh một tập hợp cùng với phép toán cho trước là vị nhóm.
- Khái niệm đồng cấu vị nhóm đơn điệu, đơn cấu và đẳng cấu.

Ngoài ra cần xem lại việc trình bày vấn đề đại lượng trong chương trình toán tiểu học nhờ lý thuyết tập hợp, cấu trúc đại số, cấu trúc thứ tự.

### 2. Yêu cầu lý thuyết.

Học viên cần nắm được

- Khái niệm về đại lượng vô hướng cộng được và do được. Định nghĩa phép đo đại lượng vô hướng cộng được.

- Một số tính chất của phép đo suy từ định nghĩa: Các đối tượng thuộc cùng một lớp tương đương có cùng một số đo; đối tượng lớn hơn có số đo lớn hơn; nếu một đối tượng được hợp thành bởi hai đối tượng thành phần không có phần chung thì số đo đại lượng của đối tượng hợp thành là tổng của các số đo đại lượng của các đối tượng thành phần. Biết lấy ví dụ trong chương trình toán tiểu học minh hoạ.

- Phát biểu và chứng minh định lý về sự tồn tại phép đo với đơn vị chọn trước. Tùy do nếu được ví dụ minh hoạ trong một đại lượng có thể tồn tại nhiều phép đo với đơn vị khác nhau. Các đơn vị đo có thể chọn tùy ý, nhưng khi đơn vị này đã xác định thì số đo đại lượng phụ thuộc vào đơn vị đã chọn.

- Nắm vững cách biểu diễn giá trị một đại lượng theo đơn vị của phép đo. Biết cách chuyển số đo giá trị của đại lượng từ đơn vị này sang đơn vị khác.

- Nắm vững hệ thống đơn vị đo, đặc biệt các đơn vị đo các đại lượng trong chương trình toán tiểu học. Mối liên hệ giữa các đơn vị đo trong cùng một loại đại lượng (khối lượng, diện tích, thể tích, độ dài, thời gian).

### 3. Hướng dẫn giải bài tập.

Các dạng bài tập.

1) Cho trước đại lượng vô hướng cộng được  $(X, \sim, \le, +)$  và một ánh xạ  $f: X/\sim \to R_+$ .

Kiểm tra  $f$  có là phép đo hay không.

Cách giải:

Theo định nghĩa phép đo đại lượng, cần chỉ ra  $f$  là đơn cấu:

$$\forall x, y \in X/\sim, f(x + y) = f(x) + f(y)$$

$f$  là đơn điều

$$\forall x, y \in X/\sim, x \le y, f(x) \le f(y).$$

$$\exists e \in X/\sim: f(e) = 1$$

2) Vận dụng các tính chất của phép đo (đơn cấu, đơn điều).

Ví dụ:

1) Cho đại lượng vô hướng cộng được và đo được  $(X, \sim, \le, +)$   $d$  là một phép đo đại lượng này với đơn vị  $e$ ,  $d$  là một đẳng cấu. Với mỗi  $k \in R_+$ ,  $k \ne 0$  xét ánh xạ:

$$k: R_+ \to R_+$$

$$\alpha \to k\alpha$$

Hãy chứng tỏ rằng  $kd$  là phép đo đại lượng  $(X, \sim, \le, +)$ .  
Chứng minh:

Ta có các ánh xạ  $d$  và  $k$  thỏa mãn:

$$X/\sim \to R \to R_+$$

nên  $k.d$  là ánh xạ:

$$k.d: X/\sim \to R_+$$

- Với mọi  $x, y \in X/\sim$

$$\begin{aligned}(k.d)(x + y) &= k.d(x + y) = k[d(x) + d(y)] \\&= k.d(x) + k.d(y) = (k.d)(x) + (k.d)(y)\end{aligned}$$

nên  $k.d$  là đơn cấu.

- Với mọi  $x, y \in X/\sim$ ,  $x \le' y \Rightarrow d(x) \le d(y)$  vì  $d$  đơn điệu  
vì  $k \in R_+$ ,  $k \ne 0 \Rightarrow k > 0$  nên  $k.d(x) \le k.d(y)$  hay  $(k.d)(x) \le (k.d)(y)$

Vậy  $k.d$  đơn điệu.

Với  $\forall k > 0 \Rightarrow \frac{1}{k} \in R_+$ . Vì  $d$  là đẳng cấu nên  $\exists e' \in X/\sim$ :

$$d(e') = \frac{1}{k}. \text{ Khi đó:}$$

$$(k.d)(e') = k.d(e') = k \cdot \frac{1}{k} = 1$$

Vậy  $k.d$  là phép đo đại lượng  $(X, \sim, \le, +)$  với đơn vị đo là  $e'$

Ví dụ 2: Xét câu 2 (bài tập 2).

Giả sử phép đo  $d$  của đại lượng vô hướng cộng được  $(X, \sim, \le, +)$  với đơn vị  $e$  là đẳng cấu. Chứng minh rằng: với mọi  $n \in N^*$ ,  $\exists x \in X : d(x) = \frac{1}{n}$

Chứng minh:

Có  $d: X/\sim \to R_+$  là đẳng cấu và  $d(e) = 1$

$$\forall n \in N^* \Rightarrow \frac{1}{n} \in R_+. \text{ Vì } d \text{ là đẳng cấu nên } \exists y \in X/\sim \text{ sao cho } d(y) = \frac{1}{n}. \text{ Khi đó } \forall x: x \sim y \text{ đều có } d(x) = \frac{1}{n}.$$