---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "4rem"

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: biography
    content:
      username: admin
      # Show a call-to-action button under your biography? (optional)
      button:
        text: 下载简历
        url: uploads/resume.pdf
    design:
      banner:
        # Upload your cover image to the `assets/media/` folder and reference it here
        filename: kalen-emsley-Bkci_8qcdvQ-unsplash.jpg
      biography:
        # Customize the style of your biography text
        style: 'text-align: justify; font-size: 0.8em;'
  - block: experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: '2006年1月'
      # Education or Experience section first?
      is_education_first: true
  - block: awards
    content:
      title: 竞赛获奖
      username: admin
    design:
      # Hugo date format
      date_format: '2006年1月'
  - block: markdown
    content:
      title: 论文专利
      subtitle: My subtitle
      text: >
        <div style="font-size: 0.8em; line-height: 1.5; text-align: justify; margin-bottom: 0.5em;">
        [1] Yang, K., Bai, C. G., She, Z. K. & Quan, Q. High-speed interception multicopter control by image-based visual servoing [J]. IEEE Transactions on Control Systems Technology. 
        </div>

        <div style="font-size: 0.8em; line-height: 1.5; text-align: justify; margin-bottom: 0.5em;">
        [2] Yang, K., Bai, C. G. & Quan, Q. Line-of-sight constrained multicopter interceptability [J]. Journal of Guidance Control and Dynamics.
        </div>

        <div style="font-size: 0.8em; line-height: 1.5; text-align: justify; margin-bottom: 0.5em;">
        [3] Yang, K., & Quan, Q. An autonomous intercept drone with image-based visual servo. In 2020 IEEE International Conference on Robotics and Automation (ICRA) (pp. 2230-2236). IEEE.
        </div>

        <div style="font-size: 0.8em; line-height: 1.5; text-align: justify; margin-bottom: 0.5em;">
        [4] Deng, H., Yang, K., Quan, Q., & Cai, K. Y. (2019). Accurate and flexible calibration method for a class of visual sensor networks. IEEE Sensors Journal.
        </div>

        <div style="font-size: 0.8em; line-height: 1.5; text-align: justify; margin-bottom: 0.5em;">
        [5] Che, J. X., Yang, K., Zhou, Z. M., Ding, Y., Zhang, H. T., & Quan, Q. (2022, November). Hi-Speed Visual Servo Docking for Multicopter UAV based on Velocity Control Mode. In 2022 China Automation Congress (CAC). IEEE.
        </div>
---
