<img width="956" height="714" alt="Screenshot 2026-02-01 031534" src="https://github.com/user-attachments/assets/b2946fd4-ab4b-4a63-ae52-8b32da3ee656" /># IPL-Data-Analysis-Matches-Ball-by-Ball-

## 📌 Project Title

Comprehensive Analysis of Indian Premier League (IPL) Matches using Match-Level and Ball-by-Ball Data

## 📖 Project Overview

This project performs a comprehensive exploratory data analysis (EDA) on the Indian Premier League (IPL) using both match-level data and ball-by-ball delivery data.

The objective is to uncover patterns, trends, and strategic insights related to:

Toss decisions

Venue conditions

Team performance

Batting vs fielding strategies

Match outcomes

This project demonstrates strong skills in data cleaning, analysis, visualization, and analytical thinking, making it highly relevant for Data Analyst, Business Analyst, and Sports Analytics roles.

## 🎯 Problem Statement

Cricket teams often make decisions based on intuition (e.g., toss decision, batting order, chasing strategy).
This project answers:

Does winning the toss really increase chances of winning?

Is batting first or chasing more successful?

How do venues influence match results?

What patterns emerge from ball-by-ball data?

Can historical data guide better strategic decisions?

## 🧾 Datasets Used
1️⃣ Matches Dataset (matches.csv)

Contains match-level information.

Key Columns:

id – Match ID

season – IPL season year

city – Match city

venue – Match venue

team1, team2 – Competing teams

toss_winner – Team that won the toss

toss_decision – Bat / Field

winner – Match winner

result, win_by_runs, win_by_wickets – Match outcome details

## 2️⃣ Deliveries Dataset (deliveries.csv)

Contains ball-by-ball data, giving granular insight into each match.

Key Columns:

match_id – Match reference

inning – Inning number

batting_team, bowling_team

over, ball

batsman, bowler

batsman_runs, extra_runs, total_runs

dismissal_kind, player_dismissed

## 🛠 Tools & Technologies

Python

Pandas – Data manipulation & aggregation

NumPy – Numerical computations

Matplotlib & Seaborn – Data visualization

Jupyter Notebook – Analysis & reporting

## Data Cleaning & Preparation

Handled missing and null values

Standardized team and venue names

Removed abandoned/no-result matches where required

Merged match-level and delivery-level data using match_id

Created derived columns for better insights

## 📊 Exploratory Data Analysis (EDA)
Match-Level Analysis

Matches played per season

Venue-wise match distribution

Toss winner vs match winner analysis

Toss decision (bat/field) impact on winning

Team-wise performance trends

Ball-by-Ball Analysis

Runs scored per over

Boundary frequency (4s & 6s)

Wicket patterns across overs

Team scoring behavior in powerplay, middle overs & death overs

## Key Insights

Winning the toss does not guarantee winning the match

Chasing teams tend to perform better at certain venues

Some teams show venue-specific dominance

Death overs contribute significantly to match results

Strategic adaptability is more impactful than fixed decisions

These insights prove how data-driven strategies outperform intuition.

## Visualizations

Bar charts for team & venue performance

Pie charts for toss decisions

Line plots for run progression

Comparative plots for batting vs chasing success

All visualizations are designed to be clear, interpretable, and decision-focused.

## Screenshot
<img width="1672" height="668" alt="Screenshot 2026-02-01 031108" src="https://github.com/user-attachments/assets/82d023aa-6c52-448c-8dcd-f5f7d2da696f" />

## Screenshot
<img width="956" height="714" alt="Screenshot 2026-02-01 031534" src="https://github.com/user-attachments/assets/fe42a8af-9d9b-4268-aba6-4a4d82b3d193" />
