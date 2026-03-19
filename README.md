# ICC Men’s Cricket World Cup 2023 Analysis

## Project Overview
This project presents a comprehensive analysis of the **ICC Men’s Cricket World Cup 2023** using Python.  
The objective is to transform raw cricket match and player data into meaningful insights about:

- Player performance
- Team dominance
- Match-level top performers
- Stadium behavior
- Proxy Player of the Match analysis
- Advanced batting and bowling insights

The project is built in **Jupyter Notebook / Google Colab** and focuses on delivering a clean, presentation-ready sports analytics workflow.

---

## Objectives
The main goals of this project are:

- Identify the **best scorer in each match**
- Identify the **best bowler in each match**
- Find the **top batsmen and bowlers of the tournament**
- Analyze **team-wise performance and dominance**
- Evaluate **batting-friendly and bowling-friendly stadiums**
- Perform **Proxy Player of the Match (MoM) analysis**
- Study **player roles, batting styles, and bowling styles**
- Generate **advanced insights** like:
  - Most explosive batter
  - Most reliable anchor
  - Most underrated player
  - Best combined batting-bowling impact candidate (proxy-based)

---

## Dataset Information
This project uses **4 CSV files**:

1. **batting_summary.csv**  
   Contains player-wise batting performance for each match.

2. **bowling_summary.csv**  
   Contains player-wise bowling performance for each match.

3. **match_schedule_results.csv**  
   Contains match schedule, date, venue, teams, and match winner.

4. **world_cup_players_info.csv**  
   Contains player profile details such as team, role, batting style, and bowling style.

---

## Tools & Technologies Used

- **Python**
- **Pandas** – data cleaning and manipulation
- **NumPy** – numerical calculations
- **Matplotlib** – static visualizations
- **Seaborn** – statistical charts
- **Jupyter Notebook / Google Colab** – project development environment

---

## Project Workflow

### 1. Data Loading
- Loaded all 4 datasets into Python using Pandas
- Verified shapes, columns, and sample records

### 2. Data Cleaning & Preprocessing
- Removed duplicate records
- Handled missing values
- Converted numeric columns to proper data types
- Converted date columns into datetime format
- Standardized team names and text columns
- Removed extra spaces and formatting inconsistencies

### 3. Match-Level Top Performers
- Identified the **best scorer in each match**
- Identified the **best bowler in each match**
- Found players who appeared most frequently as top performers

### 4. Batting Analysis
- Top 10 run scorers
- Highest individual score
- Most centuries and fifties
- Best strike rate (qualified players)
- Most fours and sixes
- Team-wise batting strength
- Most explosive batter
- Most reliable anchor

### 5. Bowling Analysis
- Top 10 wicket takers
- Best economy bowlers (qualified players)
- Most maidens
- Best bowling spell
- Team-wise bowling strength

### 6. Team Performance Analysis
- Team-wise wins and losses
- Win percentage
- Strongest batting team
- Strongest bowling team
- Most dominant team

### 7. Stadium / Venue Analysis
- Batting-friendly venue analysis
- Bowling-friendly venue analysis
- Venue-wise match count

**Note:** Venue insights are based on available match-level proxy logic due to limited toss / innings-order details in the dataset.

### 8. Proxy Player of the Match (MoM) Analysis
- Created a proxy method for Player of the Match because official MoM data was not directly available
- Compared best scorer and best bowler match impact
- Analyzed:
  - Top proxy MoM winners
  - MoM distribution by player role
  - Team-wise MoM counts

### 9. Player Profile Analysis
- Playing role distribution
- Team-wise squad size
- Team composition by role
- Batting style distribution
- Bowling style distribution

### 10. Advanced Insights
- Best combined batting-bowling impact candidate (proxy-based)
- Most underrated player
- Most explosive batter
- Most reliable anchor
- Team dominance score

---

## Key Insights

- **Virat Kohli** was the **top run scorer** of the tournament with **765 runs**
- **Mohammed Shami** was the **top wicket taker** with **24 wickets**
- **Glenn Maxwell** recorded the **highest individual score** with **201**
- **Quinton de Kock** scored the **most centuries** with **5 hundreds**
- **Rohit Sharma** was the **most frequent best scorer in matches**
- **Australia** emerged as the **most dominant team**
- **South Africa** was the **strongest batting team**
- **India** was the **strongest bowling team**
- **Hyderabad** appeared as the **most batting-friendly venue**
- **Dharamsala** appeared as the **most bowling-friendly venue**
- **Rohit Sharma** emerged as the **top Proxy Player of the Match winner**
- **Top Order Batter** was the most dominant role in Proxy MoM analysis
- **Glenn Maxwell** stood out as the **most explosive batter**
- **Virat Kohli** stood out as the **most reliable anchor**

---

## Project Structure

bash  
ICC-World-Cup-2023-Analysis/  
│  
├── ICC_WC_Dashborad.ipynb  
├── batting_summary.csv  
├── bowling_summary.csv  
├── match_schedule_results.csv  
├── world_cup_players_info.csv  
└── README.md  

## Author
Aman K  
Data Analytics Project | Sports Analytics Portfolio  
