---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


I am Dang Van Trong, a Ph.D. student at the Human Robotics Laboratory, Division of Information Science, Nara Institute of Science and Technology (NAIST), Japan, advised by Prof. [Takahiro Wada](https://scholar.google.com/citations?hl=vi&user=AMyuZtQAAAAJ). I am expected to receive my doctoral degree in September 2026.

I obtained both BS and MS in Control Engineering and Automation at Hanoi University of Science and Technology, supervised by Prof. [Dao Phuong Nam](https://scholar.google.com/citations?user=vXl3j2wAAAAJ&hl=vi) and Prof. [Nguyen Tung Lam](https://scholar.google.com/citations?user=MlJ_2-wAAAAJ&hl=vi). 


<h1><a href="/publications/" class="title-link">Selected Publications</a></h1>

<div markdown="0">

<style>
/* Ép ghi đè hiệu ứng link mặc định của theme */
.title-link {
  color: inherit !important; 
  text-decoration: none !important; 
  border-bottom: none !important; /* Xóa cái vạch ngang dày mặc định của trang */
}

.title-link:hover {
  text-decoration: underline !important; /* Chỉ gạch chân mỏng khi di chuột vào */
  color: inherit !important; /* Giữ nguyên màu xám/đen của tiêu đề, không đổi màu */
}
/* 1. Cấu trúc chung */
.pub-list {
  max-width: 900px;
  margin: 20px auto 0; /* Giảm margin-top vì không có tiêu đề to ở trên */
}

/* 2. Cấu trúc từng bài báo (Sao chép từ trang Publications) */
.pub-item {
  display: flex;
  gap: 20px;
  margin-bottom: 30px;
  align-items: flex-start;
}

.pub-image {
  flex: 0 0 130px; /* Ảnh nhỏ 130px giống hệt trang Publications */
}
.pub-image img {
  width: 100%;
  border-radius: 2px;
  border: 1px solid #ddd;
  box-shadow: 0 1px 3px rgba(0,0,0,0.1);
}

/* Cột nội dung bên phải */
.pub-details {
  flex: 1;
  padding-right: 150px; /* Chừa không gian rộng giống hệt trang Publications để độ dài dòng chữ là tương đương */
}

/* 3. Cỡ chữ thu nhỏ (Sao chép từ trang Publications) */
.pub-title {
  font-size: 0.9rem;
  font-weight: 600;
  color: #222;
  margin-bottom: 4px;
  line-height: 1.3;
}

.pub-authors {
  font-size: 0.8rem;
  color: #444;
  margin-bottom: 4px;
}

.pub-venue {
  font-size: 0.8rem;
  color: #555;
  font-style: italic;
  margin-bottom: 12px;
}

/* Nút bấm (Sao chép từ trang Publications) */
.pub-links a {
  display: inline-block;
  margin-right: 8px;
  padding: 2px 8px;
  border: 1px solid #ddd;
  border-radius: 2px;
  color: #555;
  text-decoration: none;
  font-size: 0.65rem;
  text-transform: uppercase;
  transition: all 0.2s;
}

.pub-links a:hover {
  background-color: #f5f5f5;
  color: #222;
  border-color: #aaa;
}

/* Giao diện điện thoại */
@media (max-width: 600px) {
  .pub-item {
    flex-direction: column;
    gap: 15px;
  }
  .pub-image {
    max-width: 150px;
  }
  .pub-details {
      padding-right: 0;
  }
}
</style>

<div markdown="0" class="pub-list">

  <!-- ==================== BÀI BÁO 1 ==================== -->
  <div class="pub-item">
    <div class="pub-image">
      <img src="/images/observer-control.jpg" alt="Observer Control">
    </div>
    <div class="pub-details">
      <div class="pub-title">Observer-based nonlinear cascade control approach of rewinding systems with uncertainties and disturbances compensation</div>
      <div class="pub-authors"><b>Van Trong Dang</b>, Thi Dieu Trinh Tran, Dinh Bao Hung Nguyen, Tung Lam Nguyen</div>
      <div class="pub-venue">International Journal of Automation and Control, 2026</div>
      <div class="pub-links">
        <a href="https://www.inderscienceonline.com/doi/pdf/10.1504/IJAAC.2026.153727" target="_blank">PDF</a>
      </div>
    </div>
  </div>

 <!-- ==================== BÀI BÁO: ADAPTIVE ENERGY-BASED (2026) ==================== -->
  <div class="pub-item">
    <div class="pub-image">
      <!-- Tạm thời dùng ảnh cũ, sau này bạn đổi tên file ở đây nhé -->
      <img src="/images/observer-control.jpg" alt="Adaptive Energy-Based Robot Control">
    </div>
    <div class="pub-details">
      <div class="pub-title">Adaptive Energy-Based Robot Control for Physical Human-Robot Interaction: A Less Conservative Approach</div>
      <div class="pub-authors"><b>Van Trong Dang</b>, Hiroki Kotake, Sumitaka Honji, Takahiro Wada</div>
      <div class="pub-venue">2026 IEEE International Conference on Human-Machine Systems (ICHMS), 2026</div>
      <div class="pub-links">
        <a href="https://ieeexplore.ieee.org/abstract/document/11602247" target="_blank">PDF</a>
      </div>
    </div>
  </div>

</div>
