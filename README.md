# demo-drf
Demo Django Rest Framework

# Create un virtualenv para aislar la instalación de dependencias 
virtualenv env
source env/bin/activate  # On Windows use `env\Scripts\activate`

# Instalar requisitos
pip install -r requirements.txt

# Ejecutar migraciones en sqlite
python manage.py migrate

# Crear un usuario de administración (por ejemplo user: admin, password: password123)
python manage.py createsuperuser

# Ejecutar servicio en
python manage.py runserver
