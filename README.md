# internship-assignment
###  System Utility (Mandatory)
- Detects:
  - Disk encryption status
  - OS update status (dummy check for quick implementation)
  - Antivirus status
  - Sleep settings
- Runs periodically in the background
- Sends data to backend only when a change is detected

###  Backend (Optional)
- FastAPI server with:
  - `POST /report` – Accepts data from utility
  - `GET /machines` – Lists latest status for all machines
- In-memory storage for simplicity
- CORS enabled for frontend


---

##  Tech Stack
- **Language:** Python 3
- **Backend:** FastAPI, Uvicorn
- **Frontend:** HTML, CSS, JavaScript
- **Libraries:** requests, platform, subprocess, uuid

---

## 🚀 How to Run

###  Clone or Extract Project

###  Run Backend
  -cd backend
  -source venv/Scripts/activate   # Git Bash/Windows
  -pip install -r requirements.txt
  -uvicorn main:app --reload

###  Run System Utility
  -cd system-monitor
  -source venv/Scripts/activate
  -pip install -r requirements.txt
  -python monitor.py


### View Machine Data  : http://localhost:8000/machines


unzip CrossPlatformSystemUtility.zip
cd CrossPlatformSystemUtility
