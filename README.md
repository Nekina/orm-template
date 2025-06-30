# orm-template
Standalone Django ORM App as starting template

### How to use/setup (for Linux)
1. Install necessary packages before setting up the environment to access postgres  
```  
pip install --upgrade distro-info  
pip3 install --upgrade pip==23.2.1  
```  
2. Setup virtual environment  
```  
pip install virtualenv  
virtualenv djangoenv  
source djangoenv/bin/activate  
```  
3. Install required packages in virtual environment  
```  
pip install django==4.2.4 psycopg2-binary==2.9.7  
```  
4. Run migration  
```  
python3 manage.py migrate  
```  
5. Run test.py (optional, clears Test table and add a new row)  
```  
python3 test.py  
```