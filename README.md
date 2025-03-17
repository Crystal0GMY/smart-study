# smart-study-simple

### Start Backend
```bash
cd backend
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
cd frontend
npm install
npm run start
```

### Contributors:
- xukunzh Blaire_xukun
- learnerInTheFirstStage Allen Guo
- Crystal0GMY
- DucianX Yitian
- cristiipan Yuzheng Pan
