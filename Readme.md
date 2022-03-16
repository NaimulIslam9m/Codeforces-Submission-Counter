
# CFTracer

A command line utility for checking real time submission count of each problem according to rank of participants


## Deployment

To deploy this project run

```powershell
  python -m pip install --upgrade pip
  pip install psycopg2
  pip install bs4
  pip install requests
```

You need to have postgresql as database.

In the CFTracer folder create database.ini file and put the following lines

```
[postgresql]
host=localhost
database=codeforces
user=postgres
password=<<YOUR postgres USER PASSWORD>>
```
## Demo

[![Demo]({https://drive.google.com/file/d/1tzsS9XjO0WOnZ6eRtWh-jS6qAZHOBRoV/view?usp=sharing})]({https://drive.google.com/file/d/1RI5OTv_CeqwqqhDRXvoWi-mjK3uCbhZt/view?usp=sharing} "Link Title")