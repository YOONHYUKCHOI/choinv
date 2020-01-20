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
twine upload dist/jmon-0.260-py2.py3-none-any.whl  
