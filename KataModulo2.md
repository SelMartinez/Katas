Last login: Sat Feb 19 03:36:33 on ttys001
minisel@Mac-mini-de-SELENE ~ % python3 -m venv env 
minisel@Mac-mini-de-SELENE ~ % source env/bin/activate
(env) minisel@Mac-mini-de-SELENE ~ % pip freeze
(env) minisel@Mac-mini-de-SELENE ~ % pip install python-dateutil
Collecting python-dateutil
  Using cached python_dateutil-2.8.2-py2.py3-none-any.whl (247 kB)
Collecting six>=1.5
  Using cached six-1.16.0-py2.py3-none-any.whl (11 kB)
Installing collected packages: six, python-dateutil
Successfully installed python-dateutil-2.8.2 six-1.16.0
WARNING: You are using pip version 21.3.1; however, version 22.0.3 is available.
You should consider upgrading via the '/Users/minisel/env/bin/python3.9 -m pip install --upgrade pip' command.
(env) minisel@Mac-mini-de-SELENE ~ % /Users/minisel/env/bin/python3.9 -m pip install --upgrade pip
Requirement already satisfied: pip in ./env/lib/python3.9/site-packages (21.3.1)
Collecting pip
  Using cached pip-22.0.3-py3-none-any.whl (2.1 MB)
Installing collected packages: pip
  Attempting uninstall: pip
    Found existing installation: pip 21.3.1
    Uninstalling pip-21.3.1:
      Successfully uninstalled pip-21.3.1
Successfully installed pip-22.0.3
(env) minisel@Mac-mini-de-SELENE ~ % pip freeze
python-dateutil==2.8.2
six==1.16.0
(env) minisel@Mac-mini-de-SELENE ~ % deactivate
minisel@Mac-mini-de-SELENE ~ % 
