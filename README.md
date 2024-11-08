# mia_libreria

Una semplice libreria di esempio per Python.

#### Build
'''bash
python setup.py sdist bdist_wheel
'''
#### Installazione
'''bash
pip install dist/mia_libreria-0.1-py3-none-any.whl
'''
#### Usage
'''python
import libTemplate
print(libTemplate.saluta("Pollo"))
'''

#### Verify in pip
'''bash
pip list
'''
mi espetto di trovare nei pacchetti installati il nome definito in setup.py: "mia_libreria"