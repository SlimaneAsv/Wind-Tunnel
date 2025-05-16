# Wind-Tunnel
Wind Tunnel is a project that allows users to upload their own 3D models and visualize airflow around them in a simulated wind tunnel environment. 

# Features
🌀 Upload .obj or .stl 3D models

💨 Visualize airflow using streamlines, arrows, or pressure maps

⚙️ Choose between realistic simulation (via OpenFOAM) or fast demo mode (fake vector fields)

🌐 Works as a lightweight web app or Python desktop tool

🔁 Modular: swap simulation backends, customize flow parameters

🔧 Technologies
Python version: PyVista, Streamlit, NumPy, Perlin noise (for fake airflow)

Web version: Three.js, GLTFLoader, custom vector fields

Optional backend: OpenFOAM or SU2 for CFD accuracy

🚀 Use Cases
Quick airflow testing around 3D prototypes

Teaching CFD concepts interactively

Visualizing aerodynamic behavior in an accessible way
