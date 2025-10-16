# 🛡️ SIEM-Lite

**EduSIEM** is a simple educational project that shows how security logs can be collected, analyzed, and visualized.  
It is a lightweight version of a SIEM (Security Information and Event Management) system.

---

## 🔧 Technologies

- **Python 3.10+** – main programming language  
- **pandas** – data analysis  
- **sqlite3** *(built-in)* – local database  
- **Streamlit** – web dashboard  
- **Plotly** – interactive charts  
- **re**, **datetime**, **csv** *(built-in)* – parsing log files

---

## 🧠 Project Description

The program reads log files (e.g. `auth.log`, `nginx_access.log`) from the `data/` folder,  
analyzes them, and shows the results in an interactive dashboard.  

You can see:
- number of login attempts over time,  
- top IP addresses,  
- failed and successful logins,  
- simple alerts for suspicious activity.

---
