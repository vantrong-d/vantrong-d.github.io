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
  justify-content: space-between; /* Đẩy chữ sang trái, icon sang phải */
  align-items: center;            /* Căn giữa theo chiều dọc */
  margin-bottom: 40px;            /* Khoảng cách xuống phần Education */
}

/* Chỉnh lại chữ Trong's CV */
.cv-header h1 {
  margin: 0 !important; 
  padding: 0 !important;
  border-top: none !important; /* Xóa vạch kẻ nếu có */
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
  padding-right: 150px; /* Bạn có thể tăng số này lên 180px hoặc 200px nếu muốn lùi sâu vào thêm nữa */
}

/* 2. Xóa gạch chân dính sát dưới tiêu đề */
.cv-layout h1 {
  border-bottom: none !important; 
  font-size: 1.7rem;
  margin-bottom: 20px;
}

/* 3. Tạo đường kẻ mờ CHIA CẮT GIỮA CÁC PHẦN (Vạch kẻ sẽ nằm ở giữa phần cũ và phần mới) */
.cv-layout h1:not(:first-of-type) {
  border-top: 1px solid #eaecef !important; /* Đường kẻ mờ phân cách */
  padding-top: 30px; /* Khoảng cách từ vạch kẻ xuống chữ tiêu đề mới */
  margin-top: 40px;  /* Khoảng cách từ phần nội dung bên trên xuống vạch kẻ */
}

/* 4. Tinh chỉnh độ thoáng của chữ */
.cv-layout ul {
  line-height: 1.6;
}
.cv-layout li {
  margin-bottom: 12px;
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
  <!-- Bạn nhớ thay đổi link href dưới đây trỏ tới đúng file PDF của bạn nhé -->
  <a href="/DANGVANTRONGCV2025.pdf" target="_blank" title="View full CV">
    <!-- Mã vẽ icon PDF màu đỏ chuẩn -->
    <svg class="cv-pdf-icon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 384 512" fill="#d93838">
      <path d="M181.9 256.1c-5-16-4.9-46.9-2-46.9 8.4 0 7.6 36.9 2 46.9zm-1.7 47.2c-7.7 20.2-17.3 43.3-28.4 62.7 18.3-7 39-17.2 62.9-21.9-12.7-9.6-24.9-23.4-34.5-40.8zM86.1 428.1c0 .8 13.2-5.4 34.9-40.2-6.7 6.3-29.1 24.5-34.9 40.2zM248 160h136v328c0 13.3-10.7 24-24 24H24c-13.3 0-24-10.7-24-24V24C0 10.7 10.7 0 24 0h200v136c0 13.2 10.8 24 24 24zm-8 171.8c-20-12.2-33.3-29-42.7-53.8 4.5-18.5 11.6-46.6 6.2-64.2-4.7-29.4-42.4-26.5-47.8-6.8-5 18.3-.4 44.1 8.1 77-11.6 27.6-28.7 64.6-40.8 85.8-.1 0-.1.1-.2.1-27.1 25.3-52.6 57.2-46.8 74.4 1.5 4.5 4.9 7.1 9.4 7.1 22.4 0 50-28.3 73.3-63.6 21.4-7.1 46-13.2 70.1-17.1 22.4 11.5 45.9 22.4 60.4 22.4 15.4 0 23.9-10.9 20.5-22.1-4.7-15.4-22.7-18.5-49.8-19.2zM384 121.9v8.1H256V2l8.1.1c6.4 0 12.5 2.5 17 7l96 96c4.5 4.5 7 10.6 7 17z"/>
    </svg>
  </a>
</div>

Education
======

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
