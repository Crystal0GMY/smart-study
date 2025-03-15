# smart-study-simple

### Start Backend
```bash
cd server
python -m venv venv
source venv/bin/activate  # For WSL
pip install -r requirements.txt

# Set Qualcomm hardware flags
export QNN_GPU_OPERATIONS=1
export HEXAGON_NPU=1

python app.py
```

### Start Frontend
```bash
cd client
npm install
npm start
```