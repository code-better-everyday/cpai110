Hello World Notebook

- Kernel: Python (.venv cpai110) — select this kernel in your editor's kernel selector.
- To run the notebook from the command line using the workspace venv:

```powershell
c:\Users\abhis\git\cpai110\.venv\Scripts\python.exe -m nbconvert --to notebook --execute test/hello_world.ipynb --output hello_world_executed.ipynb --output-dir test
```

- Executed copy produced: `test/hello_world_executed.ipynb` (may contain outputs after successful execution).