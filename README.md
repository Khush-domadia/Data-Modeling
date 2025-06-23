# GitHub Repository README

## Overview  
This repository contains a series of labs and practical exercises covering dimensional modeling, slowly changing dimensions, and advanced visualization and analytics in Tableau. The projects demonstrate end-to-end data warehouse design, big-data preparation, and interactive dashboard creation, illustrating both theoretical and hands-on skills required for modern data warehousing and business intelligence [1].

---

## Contents  
- **Lab 1: Dimensional Modeling Design**  
- **Lab 2: Dimensional Modeling Practice**  
- **Lab 3: Tableau Basic & Advanced I**  
- **Lab 4: Advanced Tableau II**  
- **Lab 4.1: Slowly Changing Dimensions (SCD)**  
- **Lab 5: Tableau Advanced III**  
- **Lab 6: Tableau Advanced IV**  
- **Lab 7: Dimension Patterns & Dashboard**  
- **Lab 8: Super/Subtype, Step Dimension & Dashboard II**  

---

## Lab 1: Dimensional Modeling Design  
**Objective:** Design a star schema for an e-wallet service and a global computing sales scenario, identifying dimensions, facts, grain, and measures [1].  
**Key Deliverables:**  
- E-wallet fact and dimension tables: Customer, Product, Payment, Date, Wallet transactions with cancellation, gift, and sorry credits [1].  
- Global Computing schema: Product, Customer, Channel, Promotion, Date, Distribution dimensions, and sales facts with profitability measures [1].  

---

## Lab 2: Dimensional Modeling Practice  
**Objective:** Model the UsedCarInc purchase and sale process using dimensional design with accumulating facts and varying grain levels [1].  
**Key Deliverables:**  
- Car Purchase Fact: Seller, Agent, Car, Purchase price, Inspection and cleaning costs [1].  
- Car Sale Fact: Buyer, Agent, Car, Sale price, Profit margin, and duration between purchase and sale [1].  
- Accumulating fact table suggestions for milestones and turnover analysis [1].  

---

## Lab 3: Tableau Basic & Advanced I  
**Objective:** Connect to data sources and build fundamental and composite visualizations in Tableau Desktop [1].  
**Key Deliverables:**  
- Bar, column, and cross-tab charts; color encoding with profit and sales measures [1].  
- Filtering, manual vs. computed sorting, and dashboard assembly techniques [1].  

---

## Lab 4: Advanced Tableau II  
**Objective:** Enhance data source management, grouping, hierarchies, and dual-axis/combo charts in Tableau [1].  
**Key Deliverables:**  
- Data source editing, default property settings, and live update configurations [1].  
- Grouping model names, creating hierarchy on customer fields, and mapping views [1].  
- Combo and dual-axis charts combining tax, price, and cost measures [1].  

---

## Lab 4.1: Slowly Changing Dimensions (SCD)  
**Objective:** Compare SCD Types 1–3 and implement Type 2 for employee dimension history [1].  
**Key Deliverables:**  
- Pros/cons matrix for Type 1, 2, and 3 SCD designs [1].  
- Design changes: surrogate keys, effective and expiration dates, current/expired flag [1].  
- Guidelines for handling multiple attribute changes per update cycle [1].  

---

## Lab 5: Tableau Advanced III  
**Objective:** Build cross tables, heat maps, and advanced table calculations including running totals and percent-of-total [1].  
**Key Deliverables:**  
- Highlight tables and heat maps with customized color centers [1].  
- Calculated fields: unit profit, total profit, margin, and aggregated profitability [1].  
- Quick table calculations for running totals, ranking, and top-N filtering [1].  

---

## Lab 6: Tableau Advanced IV  
**Objective:** Incorporate analytics features: trend lines, forecasting, clustering, and statistical significance [1].  
**Key Deliverables:**  
- Trend line analysis between cost and weight with confidence intervals [1].  
- Forecast generation for future sales [1].  
- K-means cluster analysis on product cost vs. weight and grouping of clusters [1].  

---

## Lab 7: Dimension Patterns, Hierarchy & Dashboard  
**Objective:** Extend a hospital star schema with pattern and hierarchy modeling; build interactive dashboards with actions [1].  
**Key Deliverables:**  
- New dimensions for Admission Type, Level of Care, Outcome and Transfer status [1].  
- Position hierarchy design with bridge tables for organizational reporting [1].  
- Dashboard layout: floating filters, view-to-view filters, and interactive actions [1].  

---

## Lab 8: Super/Subtype, Step Dimension & Dashboard II  
**Objective:** Implement super/subtype and step dimensions; advanced dashboard filter context and navigation [1].  
**Key Deliverables:**  
- Advanced filters: region selection, top-N product and city filters, and dashboard actions [1].  
- Button navigation views linking multiple dashboards [1].  
- Contextual filter chains: market → top cities → top products [1].  

---

## Getting Started  
1. **Clone the Repository**  
   ```bash  
   git clone https://github.com/username/lab-portfolio.git  
   ```
2. **Review Documentation**  
   Each lab folder contains the respective `.docx` lab instructions and any supporting scripts.  
3. **Tableau Workbooks**  
   Upload your `.twb` or `.twbx` files under each lab’s directory before pushing to the `visualizations/` folder.  
4. **Dependencies**  
   - Tableau Desktop (version 2021.1 or later)  
   - Microsoft Word (for lab instructions)  

---

## License  
This work is provided for educational and portfolio purposes under a Creative Commons Attribution 4.0 International License [1].

[1] https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/46181816/4251a508-62ea-4ae1-8a6a-293182efe85f/Lab-1_Dimensional-Modeling-2.docx
[2] https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/46181816/291f5cd0-5375-4f37-a6cc-4a0f0aafc7a4/Lab-2_Part-1_Dimensional-Modeling-Practice-fr9739.docx
[3] https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/46181816/2192c596-0cf6-4e01-9cb1-f5276872f653/Lab-3_Tableau-Basic-and-Advanced-I.docx
[4] https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/46181816/335e215f-cc97-4303-b651-9fcc0ec034de/Lab-4-Part-2-Advanced-Tableau-II-Updated.docx
[5] https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/46181816/cab06470-d403-4a90-838e-cd94fa1caade/Lab-4_Part1_SCD-fr9739.docx
[6] https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/46181816/62da9f83-39a5-4271-8327-be5cd1fa2e12/Lab-5_Advanced-Tableau-III_v3.docx
[7] https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/46181816/7570e80e-d707-48df-91f7-14fd6d5477c5/Lab-6_Advanced-Tableau-IV_v3-1.docx
[8] https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/46181816/031a69a5-09bb-4a99-8101-7a814ab04c00/Lab-7_Dimension-Pattern-Hierarchy-and-Dashboard.docx
[9] https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/46181816/74128eae-e051-41e0-872a-3a1c2b9d57a4/Lab-8.docx
[10] https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/46181816/5076d726-fa57-4c0f-b310-218de3eac45a/Lab-8_v4.docx
