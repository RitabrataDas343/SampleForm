# Sample FORM

## Installation guide

1. Clone repository

    `
    git clone https://github.com/Ritabratadas343/SampleForm.git
    `

2. cd to repository.

3. Create a virtualenv by following command

    `
    virtualenv -p python3 .
    `

   Note for windows users, use python instead of python3.

4. Activate virtualenv

    For linux/mac

    `
    source bin/activate
    `
    
    For windows users

    `
    .\Scripts\activate
    `

5. Install required packages

    `
    pip3 install -r requirements.txt
    `

    Note for windows users, use pip instead of pip3

6. cd to src and run the server

    `
    python3 manage.py runserver
    `
    
    Note for windows users, use python instead of python3.
