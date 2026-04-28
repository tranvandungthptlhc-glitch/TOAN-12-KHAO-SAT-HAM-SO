# Khảo sát và Vẽ đồ thị hàm số 
## 1. Sơ đồ khảo sát chung (4 Bước cốt lõi)
- Bước 1: Tìm Tập xác định (TXĐ)
- Bước 2: Khảo sát sự biến thiên
    - Tính đạo hàm $y'$. Tìm các điểm $y'=0$ hoặc không xác định.
    - Tìm giới hạn tại vô cực và các đường tiệm cận (nếu có).
    - Lập Bảng biến thiên (BBT).
    - Kết luận các khoảng đồng biến/nghịch biến và cực trị.
- Bước 3: Vẽ đồ thị
    - Tìm các điểm đặc biệt: Giao điểm với trục $Ox$, $Oy$.
    - Vẽ các đường tiệm cận (nếu có).
    - Xác định tâm đối xứng, trục đối xứng.
    - Vẽ đồ thị đi qua các điểm đã xác định.
## 2. Hàm số Đa thức Bậc 3: $y = ax^3 + bx^2 + cx + d \quad (a \neq 0)$
- Tập xác định: $D = \mathbb{R}$
- Giới hạn: $\lim_{x \to \pm\infty} y = \pm\infty$ (Phụ thuộc vào dấu của $a$)
- Đạo hàm: $y' = 3ax^2 + 2bx + c$ (Là một tam thức bậc 2)
- Phân loại dáng đồ thị (Dựa vào số nghiệm của $y'=0$):
    - Trường hợp 1: $y'=0$ có 2 nghiệm phân biệt
        - Hàm số có 2 cực trị (1 cực đại, 1 cực tiểu).
        - Dáng đồ thị: Hình chữ "N" (nếu $a>0$) hoặc chữ "N" ngược (nếu $a<0$).
    - Trường hợp 2: $y'=0$ có nghiệm kép hoặc vô nghiệm
        - Hàm số luôn đồng biến (nếu $a>0$) hoặc luôn nghịch biến (nếu $a<0$).
        - Không có cực trị. Đồ thị là một đường cong đi lên hoặc đi xuống hoàn toàn.
- Tính chất đặc biệt:
    - Đồ thị luôn nhận điểm uốn (nghiệm của phương trình đạo hàm cấp hai $y'' = 0$) làm tâm đối xứng.
<img src="https://ibb.co/twLhfqKM" width="300"><br> 
## 3. Hàm phân thức Bậc 1 / Bậc 1: $y = \frac{ax+b}{cx+d} \quad (c \neq 0, ad-bc \neq 0)$
- Tập xác định: $D = \mathbb{R} \setminus \{-\frac{d}{c}\}$
- Đạo hàm: $y' = \frac{ad-bc}{(cx+d)^2}$
    - Luôn mang MỘT DẤU (hoặc luôn $>0$, hoặc luôn $<0$) trên từng khoảng xác định.
    - Hàm số KHÔNG CÓ cực trị.
- Đường Tiệm cận:
    - Tiệm cận đứng (TCĐ): $x = -\frac{d}{c}$
    - Tiệm cận ngang (TCN): $y = \frac{a}{c}$
- Dáng đồ thị (Hypebol):
    - Gồm 2 nhánh nằm ở 2 góc phần tư đối diện nhau, bị chia cắt bởi 2 đường tiệm cận.
    - Nhận giao điểm của 2 đường tiệm cận $I(-\frac{d}{c}; \frac{a}{c})$ làm tâm đối xứng.
## 4. Hàm phân thức Bậc 2 / Bậc 1: $y = \frac{ax^2+bx+c}{mx+n} \quad (a \neq 0, m \neq 0)$
- Tập xác định: $D = \mathbb{R} \setminus \{-\frac{n}{m}\}$
- Đường Tiệm cận 
    - Tiệm cận đứng (TCĐ): $x = -\frac{n}{m}$ (với điều kiện tử số không nhận giá trị này làm nghiệm).
    - Tiệm cận xiên (TCX): Thực hiện phép chia đa thức tử cho mẫu, ta được $y = px + q + \frac{R}{mx+n}$. Đường thẳng $y = px + q$ chính là TCX.
- Đạo hàm và Sự biến thiên:
    - Phương trình $y'=0$ thường dẫn đến một phương trình bậc 2.
    - Nếu $y'=0$ có 2 nghiệm phân biệt $\Rightarrow$ Hàm số có 2 cực trị.
    - Nếu $y'=0$ vô nghiệm hoặc nghiệm kép $\Rightarrow$ Hàm số không có cực trị.
- Dáng đồ thị:
    - Bị chia cắt bởi 1 Tiệm cận đứng và 1 Tiệm cận xiên.
    - Nhận giao điểm của TCĐ và TCX làm tâm đối xứng.