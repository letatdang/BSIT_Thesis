# BSIT_Thesis
Monitoring System of multi-camera based on heterogenous computing environment

Tiến độ:
- Giai đoạn 1 (giữa tháng 2 - 20/3): Lý thuyết sơ bộ
  + Thiết lập vắn tắt dàn ý, đề cương báo cáo
  + Lý thuyết sơ bộ về mô hình Cluster (Master - Slave), Grid.
  + Lý thuyết sơ bộ về các môi trường lập trình : MPI, OpenMP, GPU - CUDA,...

===============================================================================

- Giai đoạn 2 (20/3 - 27/4): Lập Trình MPI
  + Thử nghiệm:
    Demo: chương trình giao tiếp đơn giản giữa slave và master trên cluster
    Môi trường: hđh Ubuntu Desktop, LAN
	* 2 máy ảo riêng biệt trên máy cá nhân
        * 2 máy ảo + 1 máy thật
  + Cài đặt:
    Laptop: Tạo 2 máy ảo, 1 cái là Master và 1 cái là Slave. Cài Ubuntu Desktop trên 2 máy này.
    Desktop: Tạo 1 máy ảo. cả máy thật và ảo đều cài Ubuntu Desktop

===============================================================================

- Giai đoạn 3 (28/4 - 31/5): Lập Trình GPU
  + Lý thuyết
    Lâp trình GPU & framework CUDA: chương trình + demo đơn giản.
  + Thử nghiệm:
    Demo:
    Môi trường: hđh Ubuntu Desktop, LAN
        * Cluster không đồng nhất trong đó có 2 máy tính ảo trên Laptop (máy cá nhân) và 1 máy desktop có gắn đồ họa ASUS (cài hđh Ubuntu trên máy thật)
  + Cài đặt:
    Desktop: cài đặt Ubuntu, sau đó CUDA

===============================================================================

- Giai đoạn 4 (20/5 - 20/6): Thử Nghiệm Ứng Dụng của Hoàng-Thưởng trên Cluster
  + Lý thuyết:
    Tìm hiểu kỹ hơn lý thuyết về MPI - CUDA - OpenCv
    Tìm hiểu mã nguồn cũ bao gồm MPI, CUDA (Hoàng) và OpenCv (Hoàng)
    Phát triển kịch bản MPI cho toàn bộ cluster
  + Cài đặt:
    Desktop 1 & 2: MPI, CUDA 6.0, OpenCv 2.4.5
    Ubuntu máy ảo 1 & 2: MPI
  + Thử nghiệm:
    Demo MPI đơn giản trên Desktop 1 & 2 và ubuntu máy ảo 1 & 2
    Demo OpenCV 2.4.5 trên Desktop 1 & 2
    Demo lại CUDA 6.0 trên Desktop 1 & 2

p/s:
 lv1 (tại trường): cài đặt/demo
 lv2 (từ xa): lý thuyết/demo