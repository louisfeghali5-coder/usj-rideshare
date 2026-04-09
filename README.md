USJ RideShare - Beirut
​A real-time carpooling solution designed specifically for the Saint Joseph University of Beirut (USJ) community.
​📝 Project Overview
​USJ RideShare is a web-based application built with Python that helps students share rides to various campuses, including CST (Mar Roukoz), CSM, and CIS. The goal is to reduce traffic congestion in Beirut and help students save on transportation costs.
​🚀 Key Features
​Live Passenger Map: Students can toggle their "Looking for a ride" status to appear on a real-time map.
​Driver Dashboard: Verified student drivers can see nearby passengers and pick them up along their route.
​Campus-Specific Logic: Focused on the unique geography of USJ campuses in Lebanon.
​Tech Stack: Built using FastAPI (Backend), Streamlit (Frontend), and SQLAlchemy (Database).
​🛠️ Installation & Setup
​To run this project locally, follow these steps:
​Clone the repository:
git clone https://github.com/louisfeghali5-coder/usj-rideshare.git
​Install dependencies:
pip install fastapi streamlit uvicorn requests pandas pydeck
​Run the Backend:
uvicorn main:app --reload
​Run the Frontend:
streamlit run app.py
