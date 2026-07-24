---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<style>
/* Giấu tiêu đề CV mặc định của trang web */
.page__title {
  display: none !important;
}

/* Khu vực chứa tiêu đề và icon PDF ngang hàng nhau */
.cv-header {
  display: flex;
  justify-content: space-between; 
  align-items: center;            
  margin-bottom: 40px;            
}

/* Chỉnh lại chữ Trong's CV */
.cv-header h1 {
  margin: 0 !important; 
  padding: 0 !important;
  border-top: none !important; 
  font-size: 2.2rem;
  color: #333;
}

/* Hiệu ứng nhún nhảy nhẹ cho icon PDF khi di chuột vào */
.cv-pdf-icon {
  width: 38px; 
  height: auto;
  transition: transform 0.2s ease-in-out;
}
.cv-pdf-icon:hover {
  transform: scale(1.15); 
}

/* 1. Ép nội dung lùi vào (chừa khoảng trống bên phải giống trang Publications) */
.cv-layout {
  padding-right: 150px; 
}

/* 2. Xóa gạch chân dính sát dưới tiêu đề */
.cv-layout h1 {
  border-bottom: none !important; 
  font-size: 1.7rem;
  margin-bottom: 20px;
}

/* 3. Tạo đường kẻ mờ CHIA CẮT GIỮA CÁC PHẦN */
.cv-layout h1:not(:first-of-type) {
  border-top: 1px solid #eaecef !important; 
  padding-top: 30px; 
  margin-top: 40px;  
}

/* 4. Tinh chỉnh độ thoáng và CỠ CHỮ của danh sách */
.cv-layout ul {
  line-height: 1.6;
  font-size: 0.95rem; /* Đã thêm thu nhỏ cỡ chữ ở đây */
}
.cv-layout li {
  margin-bottom: 12px;
}
.cv-layout p {
  font-size: 0.95rem; /* Đã thêm thu nhỏ cỡ chữ cho chữ thường */
}

/* Chống lỗi hiển thị trên màn hình điện thoại */
@media (max-width: 600px) {
  .cv-layout {
    padding-right: 0;
  }
}
</style>

<div class="cv-layout" markdown="1">

<!-- KHỐI TIÊU ĐỀ TRONG'S CV VÀ NÚT PDF -->
<div class="cv-header">
  <h1>Trong's CV</h1>
  <!-- Đã sửa đường dẫn thêm /files/ vào trước tên file -->
  <a href="/files/DANGVANTRONGCV2025.pdf" target="_blank" title="View full CV">
    <!-- Đổi sang dùng thẻ img với icon chuẩn, không bị cắt viền -->
    <img class="cv-pdf-icon" src="https://upload.wikimedia.org/wikipedia/commons/8/87/PDF_file_icon.svg" alt="PDF Icon">
  </a>
</div>

Education
======
* Ph.D. in Information Science, Nara Institute of Science and Technology, Japan, Sep 2026 (Expected)
* M.Sc. in Control Engineering and Automation, Hanoi University of Science and Technology, Vietnam, Oct 2022
* B.E. in Control Engineering and Automation, Hanoi University of Science and Technology, Vietnam, Jan 2021

Research Experience
======
* **Oct 2023 – now**: Cooperative Frameworks Using Conflict-aware Reference Generator and Semi-passive Control for Safe Physical Human-Robot Interaction
  * Predict human intention using deep learning-based data-driven model.
  * Develop adaptive reference generator to mitigate human-robot conflict.
  * Devise semi-passive control to relax conservative of fully passive control and balance safe interaction and task performance.
  * Analysis passivity, uniform ultimate boundedness, input-to-state stability.
  * Implement human-in-the-loop experiments and analyze experiment data using statistical tests.

* **Oct 2023 – now**: Adaptive Safety-critical Control for Uncertain MIMO Systems with Full-State Constraints and Input Saturation
  * Develop time-varying, asymmetric full-state constraints using barrier Lyapunov function control methods with log-type, tan-type, and universal-type.
  * Relax boundedness assumptions and initial constrained values.
  * Ensure input magnitude and input rate constraints.
  * Analyze uniform ultimate boundedness and uniform asymptotic stability.

* **Jan 2021 – now**: Adaptive Robust Finite-time/Fixed-time Control Approaches for a Class of Underactuated Mechanical Systems
  * Develop nonsingular hierarchical sliding mode control approaches to ensure convergence of both actuated and underactuated errors to zero.
  * Resolve actuator faults, sensor faults, parametric uncertainties, and external disturbances by constructing nonlinear/ neural network/ fuzzy observers, extended state observers, and filters.
  * Analyze practically finite-time/fixed-time stability.

* **Jan 2019 – Jan 2021**: Optimization-based Control Approaches for a Group of Multiple Surface Vehicles
  * Develop a formation control scheme for multi-agent systems.
  * Integrate formation control with an actor-critic reinforcement learning strategy.
  * Analyze uniform ultimate boundedness and asymptotic stability.

Work experience
======
* **Oct 2023 – now**: Research Assistant, Human Robotics Lab, Nara Institute of Science and Technology
  * Construct computational model to predict motion sickness symptoms and identify model parameters using optimization.
  * Analyze experiment data and prediction data through statistical tests.

* **Apr 2021 – Sep 2023**: Teaching Assistant and Research Assistant, Mechatronics Engineering Lab, Hanoi University of Science and Technology
  * Manage, recruit, and train members of Mechatronics Engineering Lab.
  * Complete the university project "Adaptive control for multi-axis drive systems with uncertain parameters and mismatched disturbances" with 01 ISI paper, 03 international conference papers.

* **Jan 2017 – Dec 2019**: Tutor in Student Learning Assistance Club, Hanoi University of Science and Technology
  * Support about 500 students in Mathematics (Calculus, Algebra, Probability and Statistics) and Physical.

Skills
======
* **Language**
  * Full professional proficiency in English.
* **Programming**
  * Proficiency in Matlab, Python, and ControlDesk.
* **Others**
  * Leadership, Time Management, Problem Solving, Data Analysis

</div>
