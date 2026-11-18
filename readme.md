<h1>Test Automation Tutorial</h1>


<h2>Prerequisites</h2>
<ul>
  <li>Python 3.12</li>
</ul>


<h2>Installation</h2>
1. Clone the repository:

```
git clone https://github.com/ThomasJanssen-tech/Test_Automation_Tutorial.git
cd Test_Automation_Tutorial
```

2. Create a virtual environment

```
python -m venv venv
```

3. Activate the virtual environment

```
venv\Scripts\Activate
(or on Mac): source venv/bin/activate
```

4. Install libraries

```
pip install -r requirements.txt
```

5. Test the script

```
pytest -v test_main.py
```