# DHMT
B1. Download Project từ Github và giải nén. Chạy file DoAnDHMT.sln

B2. Chuột phải vào Project chọn mục Properties

B3. Trong mục C/C++, chọn mục General và thêm đường dẫn đến file include ( file include đã có sẵn trong project ) trong phần Additional Include Directories từ máy bạn

B4. Trong mục Linker, chọn mục General và thêm đường dẫn đến file lib ( file lib đã có sẵn trong project ) trong phần Additional Library Directories từ máy bạn

B5. Kiểm tra trong phần Linker mục Input, mục Additional Dependencies đã add các tên file:

Glaux.lib

GLU32.LIB

glut32.lib

OPENGL32.LIB

glui32.lib

Nếu chưa có thì ta add các tên file này vào sau đó nhấn 'OK' để lưu.

B6. Sau đó click 'OK' để lưu và Build Project.
