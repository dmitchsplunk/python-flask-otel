# python-flask-otel

```` 
python3 -m venv venv
source ./venv/bin/activate
pip install flask
pip install "splunk-opentelemetry[all]" 
splunk-py-trace-bootstrap
export OTEL_SERVICE_NAME=python-flask-otel
splunk-py-trace flask run -p 8080
````