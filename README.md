python -m pip install --upgrade pip
pip install -r requirements.txt

venv\\Scripts\\activate
python -m venv venv
python training\train.py
python app.py