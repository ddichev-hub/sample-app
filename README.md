# sample-app
Sample FLASK app with bash script for docker container.


Password-evolution.py
nohup python password-evolution.py &

curl -k -X POST -F 'username=alice' -F 'password=mypassword' 'https://localhost:5000/login/v1'

pkill -f password-evolution.py