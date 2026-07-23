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
