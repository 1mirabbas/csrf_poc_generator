# Csrf_Poc_Generator
 Csrf Poc Generator
 
## Installation Steps

1. Clone csrf_poc_generator from git:
```
git clone https://github.com/1mirabbas/csrf_poc_generator.git
```
2. Change the directory:
```
cd csrf_poc_generator
```

3. Install the requirements:

```
python3 -m pip install yattag
```
4. Enjoy the Tool.



## Usage

Short Form    | Description
------------- |----------------------------------------------------------
-h            | help
-m            | method
-u            | url
-p            | parameters
-a            | author
-e            | enctype


## Examples

* To list help about the tool:
```
python3 csrf_poc_generator.py -h
```
* To create poc
```
python3 csrf_poc_generator.py -u http://test.com -m post -p "new_password=hacker&re_new_password=hacker" -a "Miri"
python3 csrf_poc_generator.py -u http://test.com -m post -p "new_password=hacker&re_new_password=hacker" -e "text/plain"
python3 csrf_poc_generator.py -u http://test.com -m post -p '{new_password: "hacker", re_password: "hacker", extra": =extra}' -e "text/plain"


```


