
<p align="center"><b>Languages:</b><br /><b>English</b> | <a href="https://github.com/markolofsen/py_translator/blob/master/README_es.md">Spanish</a> | <a href="https://github.com/markolofsen/py_translator/blob/master/README_ru.md">Russian</a></p>

---

Hello friend!
Sample variable for repo: [[any_repo_var]]

Version = 1.9.3
Library name = py_translator
Title = Google Translate API (Python 3)
Keywords = Google, Cloude, API

### Hot to install

```sh
pip3 install py_translator==1.9.3
```
                    

### How to use

```python
from py_translator import py_translator

private_key = '-----BEGIN PRIVATE KEY----- *********** -----END PRIVATE KEY-----'
client_email = 'starting-account-***********.iam.gserviceaccount.com'

s = py_translator(private_key=private_key, client_email=client_email).translate(text="Hello new world!", target_language='cn')
print(s.text)

```
                

    

---

