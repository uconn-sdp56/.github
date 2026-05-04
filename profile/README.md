# UConn Senior Design 2026 - Group 56 - MenuMatch

<img width="2880" height="2160" alt="team image" src="https://github.com/user-attachments/assets/cb6cdfd6-b7f8-4c44-9365-0f7903c471a9" />

## Overview

**MenuMatch** is a senior design project focused on making dining hall nutrition tracking easier for UConn students.

Users can take a photo of their plate, and our system uses dining hall menu context, nutritional data, computer vision models, and LLM-based reasoning to classify food items, estimate serving sizes, and generate a complete nutritional breakdown.

The project combines mobile development, backend infrastructure, dining hall menu scraping, image segmentation, monocular depth estimation, volume estimation, and nutritional reasoning into a full end-to-end application.

## Senior Design Day

MenuMatch placed **3rd out of 72 teams** at UConn 2026 Senior Design Day in the School of Computing section.

We were especially proud to be the **only self-proposed project to place in the top 3**.

## Project Links

- [Official Project Page](https://seniordesignday.engr.uconn.edu/seniorprojectpt/senior-design-2026-school-of-computing-team-56/)
- [Final Project Video](https://www.youtube.com/watch?v=GmUCTYO05eY)

## System Overview

MenuMatch works by combining multiple sources of context and estimation:

1. **Dining Hall Context**  
   The user selects a dining hall, date, and meal time. MenuMatch retrieves the available menu items for that dining hall.

2. **Food Classification**  
   The uploaded meal image is matched against the dining hall menu to determine which foods are present on the plate.

3. **Segmentation and Depth Estimation**  
   Computer vision models identify food regions and estimate relative depth from the image.

4. **Volume and Serving Estimation**  
   Plate geometry, segmented food regions, and depth information are used to estimate food volume and serving size.

5. **Nutrition Calculation**  
   Nutrition data and LLM-based reasoning are used to convert estimated servings into calories and macronutrients.

<img width="1574" height="394" alt="poster system overview" src="https://github.com/user-attachments/assets/7c1b9bce-747c-46df-a3bc-67bd5a8eab9b" />


## Team Members

| Name | Links |
|---|---|
| Alexander Manos | [![LinkedIn](https://img.shields.io/badge/LinkedIn-Alexander%20Manos-blue?logo=linkedin)](https://www.linkedin.com/in/manos-alex/) [![GitHub](https://img.shields.io/badge/GitHub-manos--alex-black?logo=github)](https://github.com/manos-alex) |
| Yaohui Liu | [![LinkedIn](https://img.shields.io/badge/LinkedIn-Yaohui%20Liu-blue?logo=linkedin)](https://www.linkedin.com/in/yaohui-liu-314442266/) [![GitHub](https://img.shields.io/badge/GitHub-YaohuiLiu10-black?logo=github)](https://github.com/YaohuiLiu10) |
| Josef Karpinski | [![LinkedIn](https://img.shields.io/badge/LinkedIn-Josef%20Karpinski-blue?logo=linkedin)](https://www.linkedin.com/in/josefkarpinski/) [![GitHub](https://img.shields.io/badge/GitHub-josef--karpinski-black?logo=github)](https://github.com/josef-karpinski) |
| Himanshu Thakur | [![LinkedIn](https://img.shields.io/badge/LinkedIn-Himanshu%20Thakur-blue?logo=linkedin)](https://www.linkedin.com/in/himanshu-thakur-324678221/) [![GitHub](https://img.shields.io/badge/GitHub-hthak-black?logo=github)](https://github.com/hthak) |

## Faculty Advisor

Special thanks to **Professor Wei Wei** for advising our team and pushing us to make MenuMatch as strong as it could be.

## Acknowledgements

Thank you to the **UConn College of Engineering** and the **UConn School of Computing** for organizing Senior Design Day and giving us the opportunity to present MenuMatch.
