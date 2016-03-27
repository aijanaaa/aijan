git clone https://github.com/zuberok/bs_demo.git

cd bs_demo
virtualenv env --no-site-packages

source env/bin/activate  5555

pip install -r requirements.txt

python run.py
