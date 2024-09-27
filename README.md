# simple_blog
Это пример блога на Django
в домашнем каталоге:

wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
bash Miniconda3-latest-Linux-x86_64.sh
source /home/"имя пользователя"/miniconda3/bin/activate
conda create -n djenv python=3.12
conda activate djenv

git clone git@github.com:alexandervashurin/simple_blog.git
cd simple_blog/
python -m pip install -r requirements.txt
touch .env с реквизитами из settings.py
