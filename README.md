Dữ liệu của https://www.tratencongty.com/ được chia thành 2 dạng:
- Dạng bảng ở web chính : thẻ div(search-result) trả về các trường : "Tên công ty, mã số thuế, đại diện pháp luật" (dạng bảng này cào nhanh hơn với 1p/50 công ty)
- Dạng bảng sau khi trỏ và tên công ty : thẻ div(jumbotron) trả về toàn bộ các trường, tuy nhiên thời gian chạy rất lâu 

Cách sử dụng:
- Chạy trước file tesy.ipynb : trả về toàn bộ dữ liệu có trong thẻ div search-result (dạng bảng nên trả về kết quả rất nhanh)
- Sau đó chạy file cty.ipynb : kết quả tạm thời sẽ trả về các số điện thoại (các trường còn lại bị trả về N/A nên đã lược bỏ)
- Sau khi trả về file excel, một số lần kết quả sẽ bị thay đổi thứ tự --> dùng hàm vlookup để trả về giá trị
