# Commonly used library for Android
I'm Ster Linh, I created this repo just to save the List of most used libraries for Android application development (build.gradle.kts)

# Timber:
*Timber là một thư viện nhẹ dùng để ghi log (logging) trong quá trình phát triển ứng dụng. Nó giúp dễ dàng ghi lại các thông tin debug, thông báo lỗi, và các sự kiện trong ứng dụng Android. Timber giúp thay thế Log của Android với các tính năng mạnh mẽ hơn, như tự động quản lý mức độ log, hỗ trợ ghi log theo lớp (tag) và có thể mở rộng cho các mục đích khác như gửi log đến server hoặc ghi vào file.*
## implementation ("com.jakewharton.timber:timber:5.0.1")

# Gson :  
*Gson là một thư viện Java được phát triển bởi Google, dùng để chuyển đổi (serializing) và phân tích (deserializing) đối tượng Java thành JSON và ngược lại. Gson giúp đơn giản hóa việc làm việc với dữ liệu JSON trong ứng dụng Java, cho phép bạn dễ dàng chuyển đổi giữa các đối tượng Java và định dạng JSON mà không cần phải viết quá nhiều mã. Thực hiện:*
## implementation("com.google.code.gson:gson:2.11.0")

# Glide :
*Glide là một thư viện hình ảnh mạnh mẽ và hiệu quả cho Android, giúp tải và hiển thị hình ảnh trong ứng dụng một cách nhanh chóng và dễ dàng. Glide hỗ trợ tải hình ảnh từ nhiều nguồn khác nhau như URL, tài nguyên trong ứng dụng, hoặc bộ nhớ cache. Thư viện này tự động tối ưu hóa hình ảnh để giảm tải bộ nhớ và tăng hiệu suất, đặc biệt khi làm việc với hình ảnh có kích thước lớn hoặc tải hình ảnh từ internet.*
## implementation("com.github.bumptech.glide:glide:4.16.0")

# Lifecycle :
*Giúp quản lý vòng đời của các thành phần trong ứng dụng Android, đặc biệt là các Activity, Fragment, và các thành phần khác có vòng đời phức tạp. Mục tiêu chính của thư viện này là giúp lập trình viên xử lý vòng đời của các thành phần một cách dễ dàng và an toàn hơn, tránh các lỗi thường gặp như memory leaks (rò rỉ bộ nhớ) hoặc IllegalStateException (ngoại lệ trạng thái không hợp lệ).*
## implementation("androidx.lifecycle:lifecycle-viewmodel-ktx:2.8.7")
## implementation("androidx.lifecycle:lifecycle-extensions:2.2.0")
## implementation("androidx.lifecycle:lifecycle-runtime-ktx:2.8.7")
## implementation("androidx.lifecycle:lifecycle-livedata-ktx:2.8.7")

# Retrofit:
*Retrofit là một thư viện HTTP mạnh mẽ và dễ sử dụng trong Android để giao tiếp với các dịch vụ web thông qua API RESTful. Nó cung cấp cách thức đơn giản và hiệu quả để gửi yêu cầu HTTP (GET, POST, PUT, DELETE, v.v.) và nhận dữ liệu từ server dưới dạng JSON, XML, hoặc bất kỳ định dạng nào bạn yêu cầu. Retrofit chuyển các phản hồi từ server thành các đối tượng Java (hoặc Kotlin) thông qua sự chuyển đổi (conversion) tự động.*
## implementation("com.squareup.retrofit2:retrofit:2.11.0")
## implementation("com.squareup.retrofit2:converter-gson:2.11.0")



