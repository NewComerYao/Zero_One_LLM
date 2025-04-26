# Step 1 Install UV Package Manager
pip install uv

# Step 2 Create a Virtual Environment
uv venv --python=3.11.8

# Step 3 Activate a Virtual Environment
source .venv/bin/activate

# Step 4 Install Dependencies
uv pip install torch
uv pip install packages
uv pip install -r requirements.txt