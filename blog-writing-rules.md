# Quy tắc viết blog – hệ thống Fly (May Sports)

Tổng hợp ngày 18/11/2026 từ project SEO: các file nhật ký trong project (04/11–18/11/2026), memory của project và chat "Tự động đăng bài WordPress bằng n8n". Khi hai quy tắc mâu thuẫn, bản mới hơn được giữ; bản cũ ghi ở mục "Quy tắc đã thay thế" cuối file.

Ký hiệu: **[CẦN XÁC NHẬN]** = thông tin phải kiểm tra với đội vận hành trước khi đăng.

---

## 1. Site đích

| Site | Nền tảng | Ngôn ngữ | Trang đặt chỗ | Ghi chú |
|---|---|---|---|---|
| flysapa.com | Wix | VI (mặc định, không tiền tố), EN `/en`, KO `/ko`, ZH `/zh` | `/book-online` (`/en/book-online`, `/ko/…`, `/zh/book-online`) | Site chính Fly Sapa. Bài dịch phải gán `translationId` với bài gốc |
| flydalat.com | Wix | VI (locale EN đã bật nhưng chưa có bài) | `/book-online` + 2 thẻ đặt gói Gold/Diamond | Fly Dalat Paragliding, cùng hệ thống Fly Sapa |
| duluonsapa.vn | Wix | Chỉ VI, không làm đa ngôn ngữ | `/dat-ve`; chính sách: `/chinh-sach-bay` | Site độc lập, thương hiệu "Dù Lượn Sa Pa", tuyệt đối không nhắc Fly Sapa |
| sapaparagliding.com | WordPress | EN | theo site | Cùng công ty, CJ phụ trách SEO; đăng qua n8n + REST API |
| duluon.vn | – | VI/EN | `/hoc-du` (đăng ký khóa học) | May Paragliding School |
| flyhanoi.com, flyninhbinh.com | – | – | – | Site cùng hệ thống |

Đối thủ chính: paraglidingsapa.com. Mục tiêu: vượt đối thủ ở "dù lượn sapa", "sapa paragliding", "paragliding sapa".

---

## 2. Thương hiệu: được và không được nói

### flysapa.com
- Dùng "Fly Sapa" hoặc "Fly Sapa Paragliding". Không trộn "FlySapa" và "Sapa Paragliding" trong cùng bài (bản ZH dùng "FlySapa" ở title/meta).
- Thương hiệu tự gọi ở ngôi thứ ba ("Fly Sapa gợi ý…"); "chúng tôi" chỉ dùng ở phần dịch vụ/an toàn.

### flydalat.com
- Dùng "Fly Dalat" hoặc "Fly Dalat Paragliding".

### duluonsapa.vn
- Chỉ dùng: "Dù Lượn Sa Pa", "đội ngũ Dù Lượn Sa Pa", "đội ngũ duluonsapa.vn", "blog Dù Lượn Sa Pa".
- **Không bao giờ** nhắc Fly Sapa / flysapa: không trong chữ, alt ảnh, chú thích ảnh, FAQ, nguồn dẫn ("theo công bố của Fly Sapa"), không link mạng xã hội của flysapa.
- Email hiển thị: marketing@duluon.vn (không dùng info@flysapa.com). Hotline/Zalo: (+84) 58.414.6688.
- Không trùng chủ đề, không trùng câu chữ với blog VI của flysapa.com. Khi buộc phải cùng chủ đề, chọn góc khác (ví dụ bài cáp treo Fansipan: xoay quanh "khung giờ + kịch bản chi phí").
- Tỷ lệ nội dung: ≥60% bài về dù lượn, ≤40% du lịch Sa Pa chung.

### Chung cho mọi site
- Không claim tuyệt đối: không "phi công số 1 Việt Nam", "an toàn tuyệt đối".
- Không hứa ưu đãi chưa được đội ngũ xác nhận (giảm giá nhóm, giảm 5%…).
- Không viết review giả; câu chuyện/trích dẫn khách chỉ dùng khi có thật và khách đồng ý.
- Không hứa chắc về thời tiết, mây, tuyết, lúa chín ("tuyết không phải đặc sản chắc chắn có"). Thông tin tự nhiên ghi nguồn ("theo cổng thông tin du lịch…").
- Không nêu giá của đối thủ/OTA.
- Luôn nhấn mạnh an toàn là ưu tiên số một; phi công quyết định bay hay không dựa trên điều kiện thực tế.

---

## 3. Chính sách và dữ kiện dịch vụ được phép nói

Áp dụng cho toàn hệ thống (Sa Pa, Đà Lạt) và duluonsapa.vn:

| Mục | Nói thế nào |
|---|---|
| Trẻ em bay đôi | Cùng giá người lớn |
| Người đi cùng không bay | Miễn phí, đi cùng xe; chọn chờ ở điểm cất cánh hoặc bãi hạ cánh (hai nơi cách xa nhau) |
| Đưa đón | Miễn phí |
| Đặt cọc | Không cần đặt cọc. Thông điệp: khách của Dù Lượn Sa Pa là những người tuyệt vời, giữ lịch và chỉ hủy khi có sự cố |
| Phụ thu Lễ/Tết | Chỉ nói "một khoản phụ thu nhỏ dịp lễ, Tết; mức cụ thể báo khi đặt lịch". **Không công bố con số** |
| Thời tiết xấu | Chờ hoặc dời lịch. Đã thanh toán và có mặt ở điểm cất cánh mà không bay được vì thời tiết: hoàn 100% theo chính sách bay. Không hứa vượt chính sách |
| Thanh toán | Online hoặc tại văn phòng |
| Cặp đôi | Không có gói cặp đôi. Mỗi người mua 1 vé, bay 1 chuyến riêng |
| Khóa 3 giờ ở Sa Pa | Đang tạm dừng; nói "sẽ thông báo lại khi mở lại" |
| Khóa P1 May Paragliding School | Chạy hằng tuần T6–T7–CN (Lương Sơn cũ, nay Liên Sơn, Phú Thọ); 18.000.000đ; đăng ký qua duluon.vn/hoc-du |

### Dữ kiện tham khảo (kiểm tra lại trước khi đăng)
- **Sa Pa:** gói Tiêu chuẩn 2.390.000đ (GoPro), gói Cao cấp 3.190.000đ (Camera 360 + Flycam); Flycam hoặc Camera 360: 500.000đ/dịch vụ, combo 2 dịch vụ 800.000đ. Cân nặng 20–110 kg (tải dù đôi tối đa 220 kg). Cất cánh sườn nam Hàm Rồng ~1.750 m, hạ cánh bản Tả Van ~1.000 m; lộ trình Hàm Rồng → thung lũng Mường Hoa → Tả Van. Giấy phép bay số 6484, giấy phép kinh doanh 19/GCN-SVHTTDL. Thời gian bay 10–15 phút.
- **Đà Lạt:** GOLD 2.200.000đ, DIAMOND 2.500.000đ (chưa VAT); chương trình 90–120 phút; điểm bay trong KDL LangBiang (305 Langbiang), vé KDL đã gồm trong giá bay; cân nặng 20–110 kg; tuổi khoảng 3–80; giấy phép bay số 3583; hotline (+84) 392.98.96.98 [CẦN XÁC NHẬN có dùng Zalo/WhatsApp]. Khung giờ bay cụ thể: không nêu, chỉ viết "buổi sáng thường ổn định hơn, khung giờ do đội ngũ tư vấn" [CẦN XÁC NHẬN].
- **Phi công:** Kim Trần (Trần Hoàng Kim) – nhà vô địch dù lượn Việt Nam, nhà phân phối GIN Gliders tại VN. Câu EEAT "HLV trưởng Kim Tran trực tiếp phụ trách khóa học" [CẦN XÁC NHẬN].

---

## 4. Ngôn ngữ, văn phong

### 4.1 Tiếng Việt (flysapa.com, flydalat.com, duluonsapa.vn)
Theo giọng văn các trang tiếng Việt của flysapa.com (style guide 10/11/2026).

- **Xưng hô:** gọi người đọc là "bạn", không dùng "quý khách".
- **Tông giọng:** như người bạn bản địa sành đi, nhiệt tình, trẻ trung, nhiều thông tin thực tế.
- **Hai sắc thái:**
  - Bài du lịch/review điểm đến: sôi nổi, giàu hình ảnh, có từ lóng du lịch, mở bằng câu hỏi gợi cảm xúc.
  - Bài dịch vụ dù lượn (giá, an toàn, mẹo, so sánh gói): bình tĩnh, rõ ràng, đáng tin, rất ít từ lóng.
- **Từ lóng** (đặt trong ngoặc kép, mỗi đoạn tối đa 1–2 cụm): "sống ảo", "check-in", "chiếc view triệu đô", "tọa độ", "phá đảo", "bí kíp xương máu", "bỏ túi", "chill", "chữa lành", "hạt dẻ"… Không lạm dụng đến mức mất thông tin.
- **Hình ảnh vùng:** Sa Pa – "đại ngàn Tây Bắc", "phố núi mờ sương", "biển mây cuồn cuộn", "Nóc nhà Đông Dương" (Fansipan). Đà Lạt – "thành phố ngàn hoa", "phố núi cao nguyên", "đỉnh Langbiang".
- **Viết hoa (quy tắc của user, ưu tiên hơn cách site cũ đang làm):**
  - Sentence case cho tiêu đề và heading; tên riêng giữ nguyên.
  - Viết hoa chữ đầu sau dấu ":" (cả trong heading, bullet, câu).
  - Không viết hoa mỗi chữ kiểu "Giá Vé & Kinh Nghiệm".
- **Sa Pa / Sapa:** chọn một cách và giữ thống nhất trong cả bài (tiêu đề ưu tiên "Sa Pa"; bài dịch 18/11 dùng thống nhất "Sapa").
- **Lỗi cần tránh:** heading rỗng; lỗi gõ ("Báo gồm", "Loction"); chữ tiếng Anh sót trong bài/alt/nút (dùng "Đặt lịch bay ngay", không "BOOK NOW").

### 4.2 Tiếng Anh (sapaparagliding.com, flysapa.com/en)
- Mở bài: 1 câu dẫn ngắn rồi nhiều đoạn 1 câu, nhịp nhanh, không in nghiêng.
- H2 đặt dạng câu hỏi; H3 cho từng phương án.
- Bullet viết thường, kết bằng ";".
- Link nội bộ dạng "see our guide to…", "read [X]".
- FAQ dùng H3 cho mỗi câu hỏi (thống nhất với VI).
- Mọi ảnh phải có alt (bài EN cũ đang thiếu).
- Bài EN trên flysapa.com chỉ link sang bản `/en` (không link sang bài VI, không bỏ sót `/en`), bỏ tham số `?utm_source=…` trong link nội bộ.

### 4.3 Tiếng Hàn (flysapa.com/ko)
- Slug `<slug EN>-ko`; chuyên mục KO; alt và chú thích ảnh tiếng Hàn (kể cả chú thích ẩn); nút "지금 예약하기".
- Mỗi cụm chủ đề chỉ 1 bài trụ giữ từ khóa chính; bài còn lại nhắm từ khóa dài (후기 / 가볼 만할까 / 입장권…). Không 2 bài cùng từ khóa chính.
- Tên gọi thống nhất: 하늘 문 (Cổng Trời), 석조 성당, 박 폭포, 러브 폭포, 롱마이, 세오미띠, 나트랑, 따반, 렌탈.
- Cuối bài có khối "📌 함께 읽으면 좋은 글" (≥3 link nội bộ tới bài đã đăng); nguồn ngoài đặt trong "📎 참고 자료" (nofollow).

### 4.4 Tiếng Trung (flysapa.com/zh)
- Chỉ chữ giản thể (zh-CN). Slug bài mới `<slug EN>-zh`; không đổi slug bài đã đăng.
- Thuật ngữ: Sapa = 沙坝 (đưa 沙巴 vào meta/mở bài như tên gọi khác, không dùng 萨帕); 滑翔伞; 动力三轮滑翔伞（Paramotor Trike）; 双人滑翔伞/双人带飞; 飞行员; 芒花谷, 汉戎山, 塔万村, 番西邦, 猫猫村, 河内. "Fly Sapa/FlySapa" là tên riêng, không dịch.
- SEO title ≤ ~30 chữ Hán, meta 50–75 chữ Hán, có "沙坝（沙巴）"; không để đuôi tiếng Việt "| Dù lượn Fly Sapa".
- Có thể nêu thanh toán WeChat Pay/Alipay. CTA về `/zh/book-online`; khối "📖 延伸阅读" đọc thêm.

---

## 5. Dàn ý chuẩn

### 5.1 Bài review điểm đến (VI)
1. **Mở bài 2 đoạn ngắn:** đoạn 1 câu hỏi/cảnh gợi cảm xúc, từ khóa chính in đậm; đoạn 2 nêu băn khoăn của người đọc rồi hứa hẹn "Hãy cùng [anchor từ khóa](trang chủ) khám phá… ngay dưới đây!" (đây là link trang chủ duy nhất). Ảnh đầu bài, alt có từ khóa. Bản flysapa VI hiện để mở bài in nghiêng.
2. Dòng "cập nhật tháng X/2026".
3. **Khối thông tin nhanh** ngay dưới mở bài: "**Vị trí:** …", "**Giờ mở cửa:** …", "**Giá vé:** …", "**Đường đi thực tế:** …".
4. **H2 đánh số, viết theo câu hỏi tìm kiếm:** "1. X ở đâu? Hướng dẫn di chuyển", "2. Giá vé X mới nhất 2026", "3. X có gì chơi?"…
5. Bảng cho giá vé, so sánh gói/lựa chọn; có thể có bảng "so sánh nhanh" đầu bài.
6. Lịch trình theo giờ ("**8h00 – 11h00:** …"), luôn chèn 1 khung giờ bay dù lượn.
7. Ghi chú: "→ **Lưu ý:** …", "**→ Phù hợp với:** …", "**Mẹo thực tế từ Fly Sapa:** …". Emoji ⚠️ ✅ 👉 dùng tiết kiệm; emoji đầu heading chỉ cho bài mẹo/checklist.
8. **"Review khách quan: Điểm cộng & điểm trừ".**
9. **Mục dù lượn (H2 gần cuối):** ví dụ "Nâng tầm chuyến đi với trải nghiệm 'bay giữa biển mây' cùng Fly Sapa": so góc nhìn mặt đất và trên cao, lộ trình bay, 3 bullet cất cánh / bay / hạ cánh, phi công chứng chỉ quốc tế bay kèm 1-1, quay GoPro, link "bay dù lượn cùng…" tới trang đặt chỗ.
10. **FAQ 3–5 câu** (H3), trả lời bằng "→" hoặc thẳng "Có." / "Không." rồi giải thích.
11. **Kết bài:** 1 câu tóm giá trị, lời kêu gọi cảm xúc ("Hãy xách balo lên và đi…"), nhắc dù lượn, có thể thêm dòng "📞 **Hotline / Zalo / WhatsApp:** …".

### 5.2 Bài dịch vụ dù lượn (VI)
- Mở bài nêu thẳng câu hỏi tìm kiếm, in đậm (ví dụ "**bay dù lượn Sa Pa giá bao nhiêu**"), rồi nói bài sẽ giải đáp gì.
- Số liệu cụ thể: giá từng gói, các khoản đã gồm, thời gian bay, tổng thời gian trải nghiệm, độ cao, giới hạn cân nặng.
- Danh sách "đã bao gồm": xe đưa đón, phi công, thiết bị, bảo hiểm, ảnh/video, hướng dẫn an toàn.
- Câu an toàn: "Chúng tôi luôn đặt an toàn lên hàng đầu — xin đừng thúc ép phi công bay khi thời tiết chưa an toàn."
- Mẹo hành động: xếp lịch bay vào ngày đầu chuyến đi, đặt sớm mùa cao điểm, mặc gì, ăn nhẹ, dọn bộ nhớ điện thoại, "CHẠY, KHÔNG DỪNG LẠI!" khi cất cánh.
- Bảng tóm tắt/trả lời nhanh ở đầu bài để nhắm featured snippet.

### 5.3 Quy định riêng cho duluonsapa.vn
- Mỗi bài: FAQ 4–6 câu + FAQ schema; khối CTA giữa bài và cuối bài (CTA về `/dat-ve`).
- ≥5 ảnh/video thật, alt tiếng Việt mô tả.
- Hộp tác giả cuối bài: đội ngũ Dù Lượn Sa Pa – người làm việc hằng ngày ở Sa Pa. Dòng "Cập nhật: 11/2026 · Nguồn giá: …" dưới tiêu đề.

### 5.4 Quy định riêng cho flydalat.com
- Khối CTA cuối bài: dòng đậm "✈️ Ngắm Đà Lạt từ trên cao cùng Fly Dalat" + đoạn dẫn viết riêng theo chủ đề + nút "Đặt lịch bay ngay" (/book-online, màu #E62214) + 2 thẻ đặt Gold/Diamond.
- Bỏ mục "Có thể bạn quan tâm" trong thân bài (bài liên quan đã đặt trong phần thiết lập).
- Bài trụ "9 lưu ý trước khi bay" là đích ưu tiên của link sang bài khác.

---

## 6. Độ dài

| Loại bài | Độ dài |
|---|---|
| flysapa.com VI (bài mới, bài làm mới) | ~1.700–2.600 chữ; bài làm mới đưa lên 2.000–2.300 chữ |
| duluonsapa.vn | 1.200–1.800 chữ (bài lớn như cáp treo Fansipan: 1.800–2.200) |
| flydalat.com | 1.500–1.800 chữ (thực tế các bài dịch vụ ~2.000 tính cả bảng) |
| Bài KO | ≥2.500 ký tự |
| Ảnh | Khoảng 1 ảnh mỗi H2 |

---

## 7. Từ khóa và SEO onpage

### 7.1 Chung
- Mỗi bài: 1 từ khóa chính + 2 từ khóa phụ (đặt trong SEO keywords của Wix / focus keyword).
- Từ khóa chính có ở: tiêu đề, SEO title, meta, đoạn mở đầu, ít nhất 1 H2, alt ảnh bìa.
- **Tiêu đề bài:** từ khóa chính + năm 2026 + lợi ích/móc câu ("Review X: Giá vé mới nhất và 7 góc check-in 'triệu view'"). Tránh tiêu đề clickbait lệch với nội dung.
- **SEO title:** dưới 60 ký tự, từ khóa chính đứng đầu. Trang tĩnh duluonsapa.vn theo mẫu "[Từ khóa] | Dù Lượn Sa Pa".
- **Meta description (VI):** 140–160 ký tự, mở bằng động từ ("Khám phá", "Cập nhật", "Bật mí", "Trọn bộ"), nêu 2–3 lợi ích, có thể nhắc thương hiệu, kết bằng "Xem ngay!" / "Đọc ngay!".
- Heading không nhảy cấp (H2 → H3); không H1 trong thân bài.
- Slug không dấu, ngắn, nối gạch ngang. **Không đổi slug bài đã đăng**; nếu buộc phải đổi thì đặt 301.

### 7.2 Phân vai từ khóa (tránh ăn thịt từ khóa)
- **flysapa.com:** "dù lượn sapa" dồn về trang chủ; bài blog không nhắm từ khóa này trong title/heading.
- **duluonsapa.vn:** trang chủ là trang đích duy nhất cho "dù lượn sapa", "sapa paragliding", "paragliding sapa"; blog nhắm từ khóa dài và làm cụm chủ đề trỏ về trang chủ.
- Hai bài cùng chủ đề: phân vai theo ý định tìm kiếm (ví dụ đèo Ô Quy Hồ = lái xe qua đèo; Cổng trời Ô Quy Hồ = mua vé khu du lịch), link qua lại.

---

## 8. Link nội bộ và link ngoài

### 8.1 Quy tắc chung (bản chốt mới nhất)
- **4–6 link nội bộ mỗi bài:**
  - **Đúng 1 link về trang chủ**, anchor từ khóa, đặt ở mở bài (hoặc trong đoạn CTA).
  - **1 link trang đặt chỗ** (flysapa/flydalat `/book-online`, duluonsapa `/dat-ve`). Nếu đã có nút đặt lịch thì không thêm link chữ trùng.
  - **2–4 link ngữ cảnh** sang bài liên quan, anchor là tên địa danh/chủ đề ("đèo Ô Quy Hồ", "thung lũng Mường Hoa").
  - Không spam link blog.
- **3 bài liên quan (related posts)** đặt trong phần thiết lập bài: cùng ngôn ngữ, đã xuất bản, khác với các bài đã link trong thân bài.
- Không link tới bài còn nháp (gỡ link, giữ chữ; gắn lại khi bài đích được đăng). Bài link chéo nhau thì đăng theo thứ tự hoặc cùng lúc.
- Ngoại lệ: bài hub (ví dụ "Sa Pa mùa nào đẹp") được phép nhiều link hơn để trỏ tới các bài theo tháng.

### 8.2 Anchor trang chủ theo site
| Site | Anchor |
|---|---|
| flysapa.com VI | "dù lượn Sapa", "sapa paragliding", "paragliding sapa" |
| flydalat.com | "dù lượn Đà Lạt", "Fly Dalat", "Dalat Paragliding" (đã dùng thêm: "Fly Dalat Paragliding", "dù lượn Langbiang") |
| duluonsapa.vn | Xoay vòng "dù lượn Sapa", "Sapa Paragliding", "paragliding Sapa", "bay dù lượn Sa Pa" |

### 8.3 Link ngoài
- Mọi link ra ngoài để **nofollow** (Google Maps, mạng xã hội, nguồn tham khảo…).
- **Ngoại lệ:** link sang site cùng hệ thống (flysapa.com, flydalat.com, duluonsapa.vn, sapaparagliding.com, duluon.vn, flyhanoi.com, flyninhbinh.com) để **dofollow**, đặt theo ngữ cảnh trong bài liên quan (không đặt link toàn site ở footer). Riêng duluonsapa.vn vẫn không nhắc tên Fly Sapa trong chữ.
- Nguồn tham khảo dùng nguồn chính thống (Sun World, Tổng cục Du lịch, báo địa phương…).

---

## 9. Ảnh

- Alt bằng ngôn ngữ của bài, mô tả cụ thể kèm từ khóa ("Góc nhìn Ô Quy Hồ từ điểm check-in Cây cô đơn tại Cổng trời"). Không để alt là tên file, không alt tiếng Việt không dấu.
- Ảnh bìa bắt buộc có alt.
- Chú thích ảnh (VI): "(Ảnh: sưu tầm)" hoặc "(Ảnh: Fly Sapa)" trên flysapa.com; trên duluonsapa.vn không ghi "Fly Sapa".
- Ưu tiên ảnh thật của đội ngũ/ảnh có sẵn trên site.

---

## 10. Độ tin cậy và cập nhật

- Ghi "cập nhật tháng X/2026" với giá vé, giờ mở cửa; ghi tháng cập nhật thực tế, không đoán.
- Giá vé và giờ mở cửa xác minh với nguồn chính thức trước khi đăng; giá chưa chắc thì đánh dấu [CẦN XÁC NHẬN].
- Bài giá vé rà lại mỗi quý (tháng 2, 5, 8, 11) và đăng lại để làm mới.
- Đưa con số cụ thể: giá, km, phút, độ cao, giờ mở cửa.
- Khi đổi giá, cập nhật mọi bài có giá đó (kể cả bản dịch).

---

## 11. Định dạng Google Doc cho automation (Auto Publish)

Luồng: AI agent/người viết tạo 1 thư mục Drive theo slug (Google Doc chứa thân bài + ảnh bìa + ảnh inline) → thêm 1 dòng vào tab **Auto Publish** của sheet "2026 SEO Master SEO tập đoàn FLY" với `status = draft` → người duyệt đổi sang `ready` → n8n đăng (WordPress REST API hoặc Wix Ricos) và ghi `post_id`, `post_url`, `published` (cột P–T chỉ n8n ghi).

**Trên Sheet (không viết trong Doc):** `site`, `title`, `slug`, `seo_title`, `meta_description` (cũng là excerpt), `focus_keyword`, `category`, `tags`, `doc_url`, `cover_url`, `cover_alt`, `images` (`1.jpg|alt;2.jpg|alt`), `publish_date` (`YYYY-MM-DD HH:MM`, giờ VN), `author`.

**Trong Doc:**
- Không viết tiêu đề bài; không dùng Heading 1/Title.
- Mục lớn dùng style Heading 2, mục con Heading 3 (không in đậm chữ to thay heading).
- Mỗi heading phải có ít nhất 1 đoạn văn.
- Bold dùng ít; danh sách dùng bullet/numbered list của Docs; bảng dùng Table của Docs.
- Link: bôi đen anchor → Ctrl+K; không dán URL trần.
- Ảnh: không dán ảnh vào Doc; đặt một dòng riêng `[[1.jpg | Caption]]` (EN bỏ phần caption). Alt lấy từ cột `images`.
- Nút CTA: một dòng chỉ có 1 link, bắt đầu bằng `>>` (ví dụ `>> [Đặt lịch bay tại Fly Sapa](/book-online)`).
- FAQ: mỗi câu hỏi là Heading 3.
- Không đổi font/màu/cỡ chữ, không tô nền, không text box, cột, drawing, ngắt trang.
- Mở bài VI in nghiêng (Ctrl+I) với 1 link trang chủ ở đoạn 2; EN không nghiêng.

---

## 12. Quy trình lưu và đăng trên Wix

- Bài mới và bài sửa lưu ở dạng **nháp** để user duyệt, chưa xuất bản.
- Trước khi ghi, kiểm tra bài có đang được người khác sửa không (xem `editedDate` / thay đổi chờ duyệt); không ghi đè bài user đang tự sửa.
- Bài dịch: gán `translationId` với bài gốc; link nội bộ trỏ sang bản cùng ngôn ngữ.
- Sau khi đăng: kiểm tra slug thật, request indexing trong GSC.

---

## 13. Quy tắc đã thay thế (để tham khảo)

| Quy tắc cũ | Thay bằng |
|---|---|
| flysapa VI 3–5 link nội bộ (09/11, 12/11) | 4–6 link: 1 trang chủ, 1 booking, 2–4 bài liên quan |
| duluonsapa.vn 1–3 link về trang chủ mỗi bài (outline 06/11) | Đúng 1 link trang chủ, 1 `/dat-ve`, còn lại ≤4 |
| flydalat 1–2 link trang chủ + mục "Có thể bạn quan tâm" trong thân bài | 1 link trang chủ, bỏ mục "Có thể bạn quan tâm" |
| Mọi link ngoài nofollow, kể cả site cùng công ty | Site cùng hệ thống để dofollow |
| Outline duluonsapa 06/11 ghi phụ thu người đi cùng 250k, lễ 300k, Tết 500k, mục "có đặt cọc không" | Người đi cùng miễn phí; phụ thu lễ Tết không công bố số; không đặt cọc |
