# NVIDIA GPU System Monioring Tool 

Influx , Python , Grafana  

Influx 설치  
mkdir ~/Downloads  
cd ~/Downloads  
wget https://dl.influxdata.com/influxdb/releases/influxdb_1.1.1_amd64.deb  
dpkg -i influxdb_1.1.1_amd64.deb    
  
Python 모듈   
cd ~/choinv  
python setup.py bdist_wheel -- universal   
pip install choinv-0.1-py2.py3-none-any.whl
twine upload dist/choinv-0.1-py2.py3-none-any.whl  

Grafana 설치  
wget https://dl.grafana.com/oss/release/grafana_6.4.1_amd64.deb   
dpkg -i grafana_6.4.1_amd64.deb  
service grafana-server start  
