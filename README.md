# TOP 100 ENGINEERING COLLEGES ON ANDHRA PRADESH
## Project Objective
Create an interactive analytics platform to evaluate and compare Andhra Pradesh's top 100 engineering colleges across key performance metrics including NIRF rankings, NAAC accreditation, placement rates, fees structure, and university affiliation patterns.

## Dataset Used 
- <a href="https://github.com/VarshithDev/AP_College_Data_Analysis_Dashboard/blob/main/AP_Top_100_project_data.xlsx">Dataset</a>

## Questions (KPIs) 
- Which colleges lead NIRF rankings by district?
- What's the best value college (high placement/low fees)?
- Which ownership type dominates top rankings?
- What NAAC grade distribution across 100 colleges?
- Which university has most affiliated colleges?
- Top 5 colleges by average CTC?
- District-wise placement rate leaders?
- Fees vs placement ROI ranking?
- Public vs Private performance gap?

   Dashboard Interaction <a href="https://github.com/VarshithDev/AP_College_Data_Analysis_Dashboard/blob/main/project_college.pdf">View Dashboard</a>

## Process
Raw Excel data (NIRF rankings, NAAC grades, placements, fees) 

↓ PostgreSQL ETL pipeline (pgAdmin) 

↓ Power BI DirectQuery connection 

↓ 3-page interactive dashboard:
  
  • Page 1: Overview KPIs + slicers 
  
  • Page 2: Single college performance
  
  • Page 3: Head-to-head comparison
  
↓ Native visuals + mobile layout 

↓ Publish to Power BI Service 

↓ GitHub portfolio repo

## Dashboard 
### Main Page : 
- Describes Colleges in Andhra Pradesh

<img width="755" height="448" alt="Screenshot 2026-01-13 000552" src="https://github.com/user-attachments/assets/cbfae9ad-59a2-4faa-a56f-af7951ef5a7c" />


### College Performance page : 
- Describes every feature about College like Ranking , Courses , Seats & EAMCET Ranks , Fees , Placements , etc 

<img width="749" height="435" alt="Screenshot 2026-01-13 000608" src="https://github.com/user-attachments/assets/90296d71-7819-4c6d-966a-02e2021d4ee1" />


### College Comparison Page : 
- Compare the two colleges with visuals and insights , so one can know which college is better

<img width="954" height="564" alt="Screenshot 2026-01-13 000626" src="https://github.com/user-attachments/assets/799d0438-e30a-4079-9569-3c1fccf2187d" />


## Project Insights 
🏆 **AU University dominates NIRF rankings** 

💰 **Vishnu IT = Best value**: NIRF #8 + 62% placement + affordable

📊 **Private colleges lead placements** (65% avg vs Public 52%)

📍 **22 districts covered** - uneven distribution (3 districts = 45 colleges)

🎓 **NAAC A++ rare** (only 8 colleges) - quality gap exists

💼 **CTC leaders ≠ NIRF leaders** - Vishnu outperforms on ROI

## Final Conclusion
This project successfully delivers a production-grade analytics platform that transforms fragmented NIRF rankings, NAAC accreditation data, placement statistics, and fee structures from 100+ Andhra Pradesh engineering colleges into a sophisticated 3-page interactive Power BI dashboard with PostgreSQL backend.

🏆 **Students**: Vishnu IT identified as highest ROI (NIRF #8 + 62% placement + affordable fees vs expensive NIRF leaders)

💼 **Recruiters**: 22-district talent mapping with placement rate filters and college benchmarking

📊 **Colleges**: Competitive analysis reveals private institutions outperform public (65% vs 52% placements)

📈 **Government**: Geographic insights showing 45% colleges concentrated in 3 districts

