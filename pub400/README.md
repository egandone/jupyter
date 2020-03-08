To get this requirements to install you need to create the venv environment with the system installed packages available:
```
[egan@PUB400 pub400] $ python3 -m venv --prompt jupyter --system-site-packages --symlinks .venv
```

Then install the requirements with caching diabled to save disk space:
```
[egan@PUB400 pub400] $ . .venv/bin/activate
(jupyter) [egan@PUB400 pub400] $ pip install --no-cache-dir -r requirements.txt
```

Then run the jupyter server:
```
(jupyter) [egan@PUB400 pub400] $ jupyter-notebook
[W 21:22:44.883 NotebookApp] WARNING: The notebook server is listening on all IP addresses and not using encryption. This is not recommended.
[I 21:22:44.895 NotebookApp] Serving notebooks from local directory: /home/EGAN/python/jupyter/pub400
[I 21:22:44.895 NotebookApp] The Jupyter Notebook is running at:
[I 21:22:44.897 NotebookApp] http://PUB400.RZKH.DE:8888/
[I 21:22:44.897 NotebookApp] Use Control-C to stop this server and shut down all kernels (twice to skip confirmation).
```

