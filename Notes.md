Notes:

Start page = level 0;
-p works alone; -l without -r → clear error

- We'll use venv (virtual environment). So the program will be isolated, reproductable and we won't need sudo (not alowed in ecole 42 pcs).

- use gitignore: 
venv/
data/
__pycache__/


- Include on README:
Once per fresh clone (new machine, or new copy of the repo), create the venv and install from requirements.txt instead of naming packages one by one:

bash
git clone <repo> arachnida && cd arachnida
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt

Every new terminal, run only the activation:

bash
source venv/bin/activate

