# 🏞️ Park Injury Reporting System

## Overview
A Shiny web application for tracking and reporting park injury incidents. The app allows users to submit injury reports through a web form and view real-time statistics stored in a Supabase PostgreSQL database.

**Author:** Luobing Wang  
**Date:** 2026
**Course:** [SYSEN 5460]

---

## 🚀 Quick Start

### Prerequisites
- R (version 4.0 or higher)
- RStudio (recommended)
- Supabase account (free tier works)

### Step 1: Install Required Packages
```r
install.packages(c("shiny", "DBI", "RPostgres", "dplyr"))

### Step 2: check your connection
####My Supabase connection is Not IPv4 compatible. If the Wi-Fi does not work, try to use a hotspot.

### Step 3: RUN the code in app.R

### Note: after you submit a new report, please reload the page so that the new input will be included in the recent 10 records
