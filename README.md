# Pre-CPP cho Visual Studio Code Windows

Tải Visual Studio Code tại [đây](https://code.visualstudio.com/download)

Sau khi tải, nếu muốn các bạn có thể bật auto save bằng cách vào File > Auto Save

![autosave](https://user-images.githubusercontent.com/48942146/139658430-14abf90b-1116-45cc-b0a5-69e34bac6587.png)

Hướng dẫn gồm 12 bước

#### Bước 1: Cài [TDM-GCC-64 build 10.3.0](https://github.com/jmeubank/tdm-gcc/releases/download/v10.3.0-tdm64-2/tdm64-gcc-10.3.0-2.exe)

1. Đầu tiên các bạn sẽ thấy màn hình như trong ảnh, bấm nút **Create**:

![01](https://user-images.githubusercontent.com/48942146/134608773-f921ff61-9f9d-478a-b083-a2ecbc589a5b.png)

2. Chọn như trong ảnh và bấm **Next**

![02](https://user-images.githubusercontent.com/48942146/134609522-90d0f468-6361-421f-b624-4d69c79ab015.png)

3. Chọn đường dẫn như ảnh và bấm **Next**

![03](https://user-images.githubusercontent.com/48942146/134609585-85bc8212-757b-436d-be4a-90727ce3c88f.png)

4. Ở đây các bạn có 3 sự lựa chọn:

- **TDM-GCC Recomended, C/C++**: bộ cài tiêu chuẩn
- **TDM-GCC Recomended, All Packages**: dành cho bạn nào có dung lượng dư dả cỡ 2GB là đủ, sẽ cài toàn bộ những gì TDM-GCC có
- **Custom**: dành cho các chuyên gia biết mình cần gì và muốn gì

Sau khi chọn xong các bạn bấm **Install** để cài đặt

**Nếu lỡ có 1 file notepad được mở thì đừng ngại ngùng mà tắt nó đi**

![04](https://user-images.githubusercontent.com/48942146/134611361-4b02eee3-1698-4a9d-8c2a-a3f0818d78f8.png)

#### Bước 2: Cài [Extension C++ cho Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools)
#### Bước 3: Tải [tại đây](https://github.com/Noboroto/Pre-CPP/archive/refs/heads/master.zip), giải nén
#### Bước 4: Tạo thư mục chứa code, như trong hình, thư mục của mình có tên CPP, các bạn có thể đặt tên bất kì nhưng **HẠN CHẾ SỬ DỤNG NGÔN NGỮ KHÁC TIẾNG ANH**

![06](https://user-images.githubusercontent.com/48942146/135854262-e12047dd-7d0d-4252-86e6-ec69718f3812.png)

### Bước 5: Copy thư mục `.vscode` từ thư mục vừa giải nén đưa vào bên trong thư mục CPP vừa tạo

![15](https://user-images.githubusercontent.com/48942146/135854947-6471e889-907d-4fcc-830e-5dec2cae6590.png)
![07](https://user-images.githubusercontent.com/48942146/135854976-6e7c33f5-af1d-4251-927d-2ae1be939e0d.png)

### Bước 6: Mở Visual Studio Code lên, chọn File > Open Folder

![08](https://user-images.githubusercontent.com/48942146/135856096-ed76a69e-d6f2-4154-a632-5de1be2ba445.png)

### Bước 7: Chọn folder CPP vừa tạo (không double click) và chọn Select Folder

![09_LI](https://user-images.githubusercontent.com/48942146/135856330-46f8837e-5f1b-499f-96f0-a7d7d7c2fbfc.jpg)

### Bước 8: Chọn như trên ảnh 
Chọn `Trust the authors of all file in the parent folder`
Chọn `Yes, I trust the authors. Trust folder and enable all features`

![10](https://user-images.githubusercontent.com/48942146/135856685-d77e3f77-ff9a-4d9d-8e91-4e0100301117.png)

### Bước 9: Các bạn DOUBLE CLICK vào vùng trống (vùng tô xanh như hình) để tạo file code mới
Đặt tên file code có dạng x.cpp
VD: helloworld.cpp

**Có thể bấm nút được khoanh màu xanh dương để tạo file mới**
**Lưu ý không tạo file trong thư mục `.vscode`**

![11_LI](https://user-images.githubusercontent.com/48942146/135857823-78577227-6aaf-4ba4-bcb4-a999d42153e8.jpg)

### DEBUG TIME Bước 10: Các bạn chọn tab có biểu tượng như hình:

![13](https://user-images.githubusercontent.com/48942146/135857384-9be86db4-6157-42bc-8edd-0cbde34d0a89.png)

### Bước 11: Chọn BUILD AND DEBUG và bấm hình tam giác kế bên để chạy chương trình

![14](https://user-images.githubusercontent.com/48942146/135857487-6465db2f-708b-4ef9-8e16-b14eb23856cc.png)

### Bước 12: Các bạn chọn Tab Terminal bên dưới để xem kết quả

![16](https://user-images.githubusercontent.com/48942146/135867962-6060c1f6-9321-4ce7-a26e-e7c8e4fcd516.png)

**SAU KHI CÀI ĐẶT CÁC BẠN CÓ THỂ NHẤN PHÍM F5 TRONG FILE CODE CPP ĐỂ BUILD VÀ DEBUG** 

#### Nếu bạn không debug được bạn có thể cài thêm [Visual C++ Redistributable 2015->2019](https://aka.ms/vs/16/release/vc_redist.x64.exe)

Email liên lạc: thanhtuvo135@gmail.com
