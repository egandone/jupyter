To get this requirements to install you need to create the venv environment with the system installed packages available:
```python3 -m venv --prompt jupyter --system-site-packages --symlinks .venv```

Then install the requirements with caching diabled to save disk space:
```. .venv/bin/activate```
```pip install --no-cache-dir -r requirements.txt```

Then run the jupyter server:
```jupyter-notebook```

