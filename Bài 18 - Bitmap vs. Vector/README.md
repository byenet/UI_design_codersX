# Bài 18 - Bitmap vs Vector  
![Imgur](https://i.imgur.com/590uNUm.png)  

* Ảnh Bitmap và ảnh vector là hai khái niệm phổ biến trong lĩnh vực thiết kế in ấn và thiết kế đồ hoạ 2D. Dù là Client hay designer, bạn cũng cần biết rõ sự khác nhau giữa hai kiểu ảnh này để đảm bảo chất lượng sản phẩm cuối cùng.  

### Ảnh Bitmap  
![Imgur](https://i.imgur.com/9T7tkpB.jpg)  

* Bitmap ( raster image ) là một dạng lưới ảnh gồm một loạt các chấm pixel nhỏ. Mỗi pixel là một hình vuông gán với một màu và vị trí khác nhau tạo nên hình ảnh. Định dạng phổ biến của bitmap được sử dụng trên web là PNG, JPG, BMP, JPEG và GIF.
* Có thể nói ảnh Bitmap là ảnh được tạo bởi ma trận 2 chiều của các điểm ảnh. 
* Các loại ảnh bitmap: thường có trên mạng, thiết bị androi, iOS hoặc phần mềm lập trình như: c#, c++
*  Đồ hoạ của bitmap có thể chỉnh sửa bằng cách xoá và thay đổi màu của từng pixel, sử dụng phần mềm chuyên dụng là Photoshop.  


### Ảnh Vector  

![Imgur](https://i.imgur.com/F0u7ml8.jpg)  

*  Khác với bitmap, hình ảnh vector không dựa trên mẫu pixel mà sử dụng các công thức toán học tập hợp các đường thẳng và đường cong, từ đó tạo ra hình tròn hoặc hình đa giác. Vector được lưu phổ biế dưới dạng PDF,SVG(scalable vector graphics), CDR(CorelDRAW), AI(Adobe Illustrator)… Vector sử dụng phần mềm chuyên dụng là Adobe Illustrator hoặc Corel.  
*  Vì phải lưu trữ thông tin màu cho từng pixel riêng lẻ, hình ảnh bitmap thường chiếm nhiều không gian hơn ảnh vector. Bạn có thể dễ dàng phân biệt bitmap và vector bằng cách phóng to hình ảnh. Khi ảnh bitmap được phóng to, những pixel riêng lẻ trở nên rõ hơn, tạo thành các cạnh lởm chởm làm cho tổng thể hình ảnh trở nên mờ đi. Ngược lại, dù hình ảnh vector bị phóng to vẫn sẽ mịn như ban đầu.  

### Ưu điểm và nhược điểm của bitmap và vector  

<p align = "center">
	<img src = "https://i.imgur.com/YjAmIDM.jpg"/> 
</p>   

#### Bitmap: 
* Điểm cộng: 
	* Vì ảnh bitmap có nhiều hiệu ứng in và màu đa dạng hơn vector, nên rất phù hợp cho bạn chỉnh sửa hình ảnh chuyên nghiệp và sửa đổi ấn phẩm in ấn chuyên âu.

	* Hiện nay có khá nhiều phần mềm hỗ trợ cho phép bạn chuyển và xử lí ảnh bitmap sang phần mềm khác mà không làm giảm chất lượng

	* Thích hợp để in các ấn phẩm quảng cáo khổ nhỏ như poster, card visit, tờ rơi, bìa tạp chí… 

* Điểm trừ 
	* Khi file bitmap của bạn không đạt chuẩn độ phân giải thì sản phẩm in ra sẽ gặp tình trạng vỡ, mờ ảnh khi phóng to.
	
	* Vậy làm thế nào để khắc phục nhược điểm ảnh nhoè?  
		* Đơn giản thôi, bạn cần tăng mật độ các điểm pixel của ảnh. Hãy chú ý đến các đơn vị đo lường như DPI ( số chấm trên mỗi inch ) hoặc PPI ( số pixel trên mỗi inch ).   

![Imgur](https://i.imgur.com/24JbGlI.jpg)   

#### Vector: 
* Điểm cộng:
	* Khác với bitmap, bạn vẫn sẽ có hình ảnh chất lượng tốt dù xuất file với kích thước lớn, bởi đặc điểm tự động cập nhật lại điểm ảnh, số lượng và vị trí của điểm đó.

	* Bạn có thể thoải mái phóng to hay thu nhỏ hình ảnh mà không làm mờ, gỉam chất lượng hình ảnh vector

	* Thích hợp để in các ấn phẩm khổ lớn như logo công ty, backdrop, standee, banner bởi độ sắc nét cao.

* Điểm trừ : 
	* Vì ảnh vector giới hạn các tone màu cơ bản nên khi xử lí file vector, bạn sẽ gặp khó khăn trong việc xử lí màu hơn.  
	
![Imgur](https://i.imgur.com/KRI4dKI.jpg)  

* Như vậy, có thể nhận thấy ảnh vector thường được lựa chọn nhiều hơn bởi sự thay đổi kích thước linh hoạt, sản phẩm xuất ra yêu cầu ảnh ít dung lượng hơn ảnh bitmap. Bên cạnh đó, ảnh vector khi hiển thị trên màn hình độ phân giải cao hoặc máy in sẽ sắc nét hơn bitmap. Tuy nhiên, hiện nay các thiết bị đầu ra như máy in, máy chiếu đều sử dụng thiết bị thiết bị raster, điều này đồng nghĩa tất cả các đối tượng bao gồm ảnh vector trước khi xuất ra đều phải chuyển sang dạng ảnh bitmap. Vì thế ảnh bitmap vẫn đóng vai trò cần thiết, và rất quan trọng đối với designer làm trong lĩnh vực thiết kế in ấn.
