Bước 1: update gói phần mềm 
```sh
apt-get update
apt-get -y install software-properties-common python-software-properties
```
Bước 2: Cài đặt gói pip-3
```sh
sudo apt install python-pip###cài đặt gói tin pip2
sudo apt install python3-pip ###cài đặt gói tin pip3
pip3 --version ###check version
```
Bước 3: Cài đặt scapy-ssl_tls-python3
*pip - tải về bản phát hành mới nhất của gói python<br>
`
pip install scapy-ssl_tls
`
* Từ tập tin nguồn scapy-ssl_tls bạn tải về 
```sh
pip install -r requirements.txt
python setup.py install
```
