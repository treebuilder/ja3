ja3.py is a python tool for generating JA3 fingerprints from pcaps.

## Installation
```
$ pip install dpkt
```
Ensure dpkt is >= v1.9.0

## Usage
```
$ python ja3.py [pcap]
```

## Example
```
$ python ja3.py example.pcap  
[65.55.184.155:443] JA3: 769,47-53-5-10-49161-49162-49171-49172-50-56-19-4,0-10-11,23-24-25,0 --> ada70206e40642a3e4461f35503241d5  
[65.55.184.16:443] JA3: 769,4-5-10-9-100-98-3-6-19-18-99,,, --> de350869b8c85de67a350c8d186f11e6
```

___  
### Python Script Written by
[Tommy Stallings](mailto:tommy.stallings@salesforce.com)

### JA3 Created by

[John B. Althouse](mailto:jalthouse@salesforce.com)  
[Jeff Atkinson](mailto:jatkinson@salesforce.com)  
[Josh Atkins](mailto:j.atkins@salesforce.com)  

Please send questions and comments to **[John B. Althouse](mailto:jalthouse@salesforce.com)**.
