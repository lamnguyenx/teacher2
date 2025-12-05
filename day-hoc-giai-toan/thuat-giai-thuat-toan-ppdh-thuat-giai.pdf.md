

Sai lầm: So đồ suy luận  $\frac{A \to B, B}{A}$  không phải là một quy tắc suy luận hợp logic, tức là lập luận trên đã vi phạm yêu cầu (iii).

Thứ tư, người giáo viên còn cần hình thành ở học sinh những tri thức phương pháp về chiến lược giải toán chứng minh (có tính chất tìm đoán) theo con đường tập luyện những hoạt động ăn khớp với những tri thức này (xem mục 5.3.3, chương IV).

### 2.4.4. *Phân bậc hoạt động chứng minh*

Dựa trên những tư tưởng chủ đạo của quan điểm hoạt động (xem mục 5.4, chương IV), cần phân bậc hoạt động chứng minh để điều khiển học sinh học tập hoạt động này. Sự phân bậc theo một tiêu chí bao quát là cần cù vào tính độc lập của hoạt động của học sinh thể hiện ở ba mức độ:

- Hiểu chứng minh;
- Trình bày lại được chứng minh;
- Độc lập tiến hành chứng minh.

Ba mức độ này chỉ so sánh được với nhau đối với cùng một bài toán. Thật vậy, *hiểu chứng minh* ở một bài toán khó rất có thể khó khăn hơn *độc lập chứng minh* ở một bài toán dễ.

# 3. DẠY HỌC QUY TẮC, PHƯƠNG PHÁP

Thực ra, những quy tắc, phương pháp không hoàn toàn độc lập với định nghĩa và định lý. Có những quy tắc, phương pháp dựa vào một định nghĩa hay định lý, có khi chỉ là một hình thức phát biểu khác của một định nghĩa hay định lý. Tuy nhiên, việc dạy học loại hình tri thức này có những nét riêng, vì vậy nó được trình bày tách biệt trong mục này.

Chương IV, mục 5.3 đã đề cập việc dạy học những quy tắc, phương pháp được phân biệt theo ba cấp độ tùy theo vai trò của ngôn ngữ, hoặc chia thành hai thể loại tùy theo chúng có được quy định tường minh trong chương trình phổ thông hay không.

Mục này sẽ trình bày việc dạy học quy tắc, phương pháp được phân biệt dựa trên khái niệm thuật toán.

## 3.1. Những thuật toán và những quy tắc tự thuật toán

### 3.1.1. Khái niệm về thuật toán và quy tắc tự thuật toán

Hằng ngày con người tiếp xúc với rất nhiều bài toán từ đơn giản đến phức tạp. Đối với một số bài toán, tồn tại những quy tắc xác định mô tả quá trình giải. Từ đó, người ta đi đến khái niệm trực giác về thuật toán và khái niệm này đã được dùng từ lâu, kéo dài suốt mấy nghìn năm trong lịch sử toán học.

*Thuật toán* theo nghĩa trực giác được hiểu như một dãy hữu hạn những chỉ dẫn thực hiện được một cách đơn trị, kết thúc sau một số hữu hạn bước và đem lại kết quả là biến đổi thông tin vào (INPUT) của một lớp bài toán thành thông tin ra (OUTPUT) mô tả lời giải của lớp bài toán đó.

Đây chưa là một định nghĩa chính xác mà chỉ là một cách phát biểu, giúp ta hình dung khái niệm thuật toán một cách trực giác.

Ở trường phổ thông, học sinh được làm việc với nhiều thuật toán như cộng, trừ, nhân, chia những số tự nhiên và số hữu tỉ, tìm ước chung lớn nhất, bội chung nhỏ nhất của hai số, giải hệ hai phương trình bậc nhất hai ẩn, giải phương trình bậc hai dưới dạng chuẩn, giải phương trình bậc nhất đối với  $\sin x$  và  $\cos x$ ,...

Ta sẽ mô tả tỉ mỉ cách giải phương trình bậc hai dưới dạng chuẩn để minh hoạ khái niệm thuật toán.

Ví dụ. Giải phương trình bậc hai  $ax^2 + bx + c = 0$ , trong đó  $a \neq 0$  (hình 7.8).

Trong quá trình dạy học, ta cũng thường gặp một số quy tắc tự chua mang đủ các đặc điểm đặc trưng cho thuật toán, nhưng có một số trong các đặc điểm đó và đã tỏ ra có hiệu lực trong việc chỉ dẫn hành động và giải toán. Đó là những *quy tắc tự thuật toán* được hiểu như một dãy hữu hạn những chỉ dẫn thực hiện được theo một trình tự xác định nhằm biến đổi thông tin vào của một lớp bài toán thành thông tin ra mô tả lời giải của lớp bài toán đó.

![](ad04aa6cb9e7fb36bb7a91e817e2d314_img.jpg)

Flowchart illustrating the solution of a quadratic equation  $ax^2 + bx + c = 0$  using the discriminant  $\Delta = b^2 - 4ac$ .

1. Start (Bắt đầu)
2. Calculate discriminant  $\Delta = b^2 - 4ac$
3. Decision:  $\Delta < 0$  (Negative discriminant)
   - If true: Output "Phương trình vô nghiệm" (Equation has no solution)
   - If false: Proceed to next decision
4. Decision:  $\Delta = 0$  (Zero discriminant)
   - If true: Output "Phương trình có nghiệm kép" (Equation has one repeated solution)
   - If false: Proceed to next decision
5. Decision:  $\Delta > 0$  (Positive discriminant)
   - If true: Output "Phương trình có 2 nghiệm phân biệt" (Equation has two distinct solutions)
   - If false: Output "Phương trình có 2 nghiệm phân biệt" (Equation has two distinct solutions)
6. End (Kết thúc)

Formulas for the solutions:

- One repeated solution:  $x_1 = x_2 = \frac{-b}{2a}$
- Two distinct solutions:  $x_1 = \frac{-b + \sqrt{\Delta}}{2a}$  and  $x_2 = \frac{-b - \sqrt{\Delta}}{2a}$

Hình 7.8

Quy tắc tựa thuật toán phân biệt với thuật toán như sau:

- Mỗi chỉ dẫn trong quy tắc có thể chứa mô tả hành động một cách xác định;
- Kết quả thực hiện mỗi chỉ dẫn có thể không đơn vị;
- Quy tắc không bảo đảm chắc chắn rằng sau một số hữu hạn bước thì đem lại kết quả là lời giải của lớp bài toán.

Mặc dù có một số hạn chế nói trên so với thuật toán, quy tắc tựa thuật toán cũng vẫn là những tri thức phương pháp có ích cho quá trình hoạt động và giải toán.

Ví dụ. Quy tắc tính đạo hàm của hàm  $y = f(x)$

Bước 1: Lấy một số gia  $\Delta x$  của đối số, tính số gia tương ứng  $\Delta y$  của hàm số:

$$\Delta y = f(x + \Delta x) - f(x)$$

Bước 2: Lập tỉ số  $\frac{\Delta y}{\Delta x}$

Bước 3: Tìm giới hạn  $\lim_{\Delta x \to 0} \frac{\Delta y}{\Delta x}$

Giới hạn trên (nếu có) là đạo hàm của hàm số  $y = f(x)$  tại điểm  $x$ .

Trong ví dụ trên, chỉ dẫn ở bước 3 không mô tả một cách xác định việc tìm  $\lim_{\Delta x \to 0} \frac{\Delta y}{\Delta x}$ . Vì vậy, đương nhiên có những học sinh tuy áp dụng

quy tắc này trong ví dụ này nhưng vẫn không tính được đạo hàm của một hàm số cụ thể nào đó, mặc dù đạo hàm này tồn tại.

### 3.1.2. Dạy học thuật toán và quy tắc tự thuật toán

Trong dạy học thuật toán hoặc quy tắc tự thuật toán có một số điều cần lưu ý:

- **Thứ nhất**, nên cho học sinh biết nhiều hình thức thể hiện một quy tắc, tạo điều kiện thuận lợi cho họ nắm vững nội dung từng bước và trình tự thực hiện các bước của quy tắc đó.

Ví dụ. Giải phương trình bậc hai  $ax^2 + bx + c = 0$ , ( $a \neq 0$ )

(i) Công thức

Theo sách giáo khoa, phương pháp giải phương trình bậc hai dạng chuẩn đã được trình bày dưới dạng công thức.

Trường hợp học sinh đã học sơ đồ khôi và ngôn ngữ phỏng trình, ta còn có thể biểu diễn phương pháp giải phương trình bậc hai nhờ các phương tiện đó.

(ii) Sơ đồ khôi (xem ví dụ ở mục 3.1.1)

(iii) Ngôn ngữ phỏng trình

Thuật toán phương trình 2

biến  $a$ ,  $b$ ,  $c$ ,  $D$ ,  $x_1$ ,  $x_2$ : thực;  $y$ : văn bản;  
bắt đầu

$D := b^2 - 4ac$ ;

nếu  $D < 0$

thì  $y :=$  "phương trình vô nghiệm"

còn nếu  $D = 0$

thì bất đầu

$y$  := "phương trình có nghiệm kép";

$x_1 := -b/(2a)$ ;  $x_2 := x_1$

kết thúc

còn bất đầu

$y$  := "phương trình có hai nghiệm phân biệt";

$x_1 := (-b + \sqrt{D}) / (2a)$ ;

$x_2 := (-b - \sqrt{D}) / (2a)$

kết thúc

kết thúc.

• *Thứ hai*, cần trình bày rõ các bước trong những ví dụ cụ thể theo một sơ đồ nhất quán trong một thời gian thích đáng.

Cách trình bày này có thể được minh họa qua việc giải phương trình bậc hai  $3x^2 - 5x + 2 = 0$  như sau:

- Xác định  $a$ ,  $b$ ,  $c$ :  $a = 3$ ,  $b = -5$ ,  $c = 2$

- Tính biệt số:  $\Delta = b^2 - 4ac = (-5)^2 - 4.3.2 = 25 - 24 = 1$

- Kết luận:  $\Delta > 0$  nên phương trình có hai nghiệm phân biệt

$$x_1 = \frac{-b + \sqrt{\Delta}}{2a} = \frac{-(-5) + 1}{2.3} = \frac{6}{6} = 1$$

$$x_2 = \frac{-b - \sqrt{\Delta}}{2a} = \frac{-(-5) - 1}{2.3} = \frac{4}{6} = \frac{2}{3}$$

Biện pháp trên được sử dụng để cho quy tắc động lại dưới dạng đã được tri hoá theo một sơ đồ nhất quán trong cách trình bày của học sinh khi luyện tập và được áp dụng trong một thời gian đủ dài để họ nắm vững và vận dụng tốt quy tắc đó.

• *Thứ ba*, cần tập luyện cho học sinh thực hiện tốt những chỉ dẫn nêu trong thuật toán hoặc trong quy tắc tựa thuật toán. Nếu chủ thể không biết thực hiện những chỉ dẫn như vậy thì dù có học thuộc quy tắc tổng quát cũng không thể áp dụng nó vào những trường hợp cụ thể. Chẳng hạn, trong ví dụ giải phương trình bậc hai, dù cho học sinh có thuộc công thức, nhưng nếu không nắm vững các phép tính trên số hữu tỉ thì có thể phạm sai lầm khi tính biệt số hoặc khi áp dụng các công thức tính nghiệm và do đó không giải được bài toán đặt ra.

■ *Thứ tư*, cần làm cho học sinh ý thức được và biết sử dụng các cấu trúc điều kiện cơ bản để quyết định trình tự các bước. Trong ba cấu trúc điều kiện cơ bản là: tuân tự, phân nhánh và lặp thì ở trường phổ thông, cấu trúc tuân tự được dùng một cách tự nhiên, cấu trúc lặp hiện nay mới được sử dụng tường minh khi lập trình cho máy tính, còn cấu trúc phân nhánh xuất hiện rõ nét và phổ biến. Trong khi dạy học những thuật toán và những quy tắc tựa thuật toán, dù cho chúng được biểu diễn dưới bất kỳ hình thức nào, cần đặc biệt nhấn mạnh, hướng dẫn cho học sinh sử dụng đúng cấu trúc này, kể cả trường hợp có nhiều hành động phân nhánh lồng nhau (xem ví dụ về giải phương trình bậc hai ở trên, đặc biệt là các hình thức diễn tả (ii) và (iii)).

■ *Thứ năm*, thông qua dạy học những thuật toán và quy tắc tựa thuật toán, cần có ý thức góp phần phát triển tư duy thuật toán cho học sinh.

Phát triển tư duy thuật toán trong nhà trường phổ thông là cần thiết vì những lí do sau đây:

(i) Tư duy thuật toán giúp học sinh hình dung được việc tự động hoá trong những lĩnh vực hoạt động khác nhau của con người, góp phần khắc phục sự ngăn cách giữa nhà trường và xã hội tự động hoá. Nó giúp học sinh thấy được nền tảng của việc tự động hoá, cụ thể là nhận thức rõ đặc tính hình thức, thuần túy máy móc của quá trình thực hiện thuật toán, đó là cơ sở cho việc chuyển giao một số chức năng của con người cho máy thực hiện;

(ii) Tư duy thuật toán giúp học sinh làm quen với cách làm việc trong khi giải bài toán bằng máy tính điện tử. Thật vậy, thiết kế thuật toán là một khâu rất cơ bản của việc lập trình. Tư duy thuật toán tạo điều kiện cho học sinh thực hiện tốt khâu đó;

(iii) Tư duy thuật toán giúp học sinh học tập tốt những môn học ở nhà trường phổ thông, rõ nét nhất là môn Toán.

Nó tạo điều kiện thuận lợi cho học sinh lĩnh hội kiến thức và rèn luyện kỹ năng, kỹ xảo khi học các phép tính trên những tập hợp số, giải phương trình bậc nhất, bậc hai,...

(iv) Tư duy thuật toán cũng góp phần phát triển những năng lực trí tuệ chung như phân tích, tổng hợp, khái quát hoá,... và hình thành những

phẩm chất của người lao động mới như tính ngã nắp, kĩ luật, tính phê phán và thói quen tự kiểm tra,...

Tu duy thuật toán liên hệ chất chẽ với khái niệm thuật toán đã được trình bày ở mục 3.1.1. Phương thức tư duy này thể hiện ở những hoạt động sau đây:

(i) Thực hiện những hoạt động theo một trình tự xác định phù hợp với một thuật toán cho trước;

(ii) Phân tích một hoạt động thành những hoạt động thành phần được thực hiện theo một trình tự xác định;

(iii) Mô tả chính xác quá trình tiến hành một hoạt động;

(iv) Khái quát hoá một hoạt động trên những đối tượng riêng lẻ thành một hoạt động trên một lớp đối tượng;

(v) So sánh những con đường khác nhau cùng thực hiện một công việc và phát hiện con đường tối ưu.

Thành phần đầu thể hiện khả năng thực hiện thuật toán có sẵn.

Bốn thành phần sau thể hiện khả năng xây dựng thuật toán mới (ít nhất là mới đối với học sinh). Các thành phần này có thể được phát biểu văn tết như sau:

(i) Thực hiện thuật toán đã biết;

(ii) Phân tách hoạt động;

(iii) Tương minh hoá thuật toán;

(iv) Khái quát hoá hoạt động;

(v) Chọn con đường tối ưu.

Tu duy nói chung và tu duy thuật toán nói riêng chỉ có thể hình thành và phát triển trong hoạt động. Vì vậy, để phát triển tu duy thuật toán, cần tổ chức cho học sinh tập luyện các hoạt động (i) – (v) nói trên. Dạy học những thuật toán và những quy tắc tự thuật toán là những cơ hội thuận lợi để thực hiện việc này. Làm như vậy sẽ tác động tích cực tới việc thực hiện mục tiêu kép: vừa làm cho học sinh nắm vững tri thức và kỹ năng toán học, vừa giúp họ phát triển tu duy thuật toán, một yếu tố văn hóa quan trọng trong đời sống hiện nay.

## 3.2. Những quy tắc, phương pháp tìm đoán

Cùng với những thuật toán và quy tắc tự thuật toán, ta không được lãng quên một số quy tắc, phương pháp có tính chất tìm đoán như quy lô về quen, khái quát hoá, tương tự hoá, phương pháp tìm lời giải của bài toán,...

Hiện nay, những quy tắc, phương pháp như vậy thường không phải là đối tượng dạy học tường minh trong nhà trường phổ thông. Trong điều kiện đó, những quy tắc, phương pháp này thường được thực hiện theo hai con đường tùy từng trường hợp cụ thể:

- Thông báo tri thức phương pháp trong quá trình hoạt động;
- Tập luyện cho học sinh những hoạt động ăn khớp những quy tắc, phương pháp mà ta mong muốn họ biết thực hiện.

Hai con đường này đã được trình bày trong các mục 5.3.2 và 5.3.3 của chương IV.

Những quy tắc, phương pháp tìm đoán chỉ là những gọi ý giải quyết vấn đề chứ không phải là những thuật toán bảo đảm chắc chắn dẫn tới thành công. Vì vậy, khi cho học sinh sử dụng chúng, cần rèn luyện cho họ tính mềm dẻo, linh hoạt, biết điều chỉnh phương hướng, thay đổi phương pháp khi cần thiết. Sẽ không có gì đáng ngại nếu học sinh không thành công khi áp dụng một quy tắc, phương pháp tìm đoán nào đó. Điều quan trọng là tới một lúc nào đó, họ phải phát hiện ra sự lâm đờng, biết thay đổi phương hướng và cuối cùng đi tới thành công. Đó chính là học phát hiện và giải quyết vấn đề. Đó chính là học cách học, một yêu cầu cần bản đối với mục tiêu và phương pháp dạy học hiện nay.

# 4. DẠY HỌC GIẢI BÀI TẬP TOÁN HỌC

## 4.1. Vai trò của bài tập trong quá trình dạy học

Bài tập toán học có vai trò quan trọng trong môn Toán. Điều cần bản là bài tập có vai trò giá mang hoạt động của học sinh. Thông qua giải bài tập, học sinh phải thực hiện những hoạt động nhất định bao gồm cả nhận diện và thể hiện định nghĩa, định lí, quy tắc hay phương pháp, những hoạt động toán học phức hợp, những hoạt động trí tuệ phổ biến trong Toán học, những hoạt động trí tuệ chung và những hoạt động ngôn ngữ