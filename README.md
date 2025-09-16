# fullstack-ws

python3 -m venv env/arrayshop  
source env/arrayshop/bin/activate
source /home/tikkazar/learn/fullstack-ws/env/arrayshop/bin/activate


CELERY:  в папке fullstack-ws/ -> celery -A main worker -l debug
STRIPE:  stripe listen --forward-to localhost:8000/payment/webhook/