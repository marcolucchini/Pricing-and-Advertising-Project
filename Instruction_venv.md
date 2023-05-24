# Instruction for virtual environment

Run all the comand from a terminal inside the folder of the project

To create a virtual environment:
    python3 -m venv venvOLA  

To activate a virtual environment:
    source venvOLA/bin/activate || venvOLA\Source\activate

To deactivate a virtual environment:
    deactivate

Inside the virtual environment:

The first time you create a venv (or when requirements.txt changes) install required packages:
    pip install -r requirements.txt

To create requirements when you add new packages:    
    pip freeze > requirements.txt

