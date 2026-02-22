# OriON Daily Status

- Updated (UTC): **2026-02-22T23:47:55Z**
- Host: **SHAKIROV-S**

## GitHub
- strategies repo: `https://github.com/bohdan6992/OriON-strategies.git`
- strategies sha: `6076414e2409`
- strategies updated: **True**
- results repo: `https://github.com/bohdan6992/OriON-stats.git`
- results layout: `root`
- results subdir: ``

## Datum API
- ok: **True**
- config: `C:\datum-api-examples-main\datum_api_config.json`
- credentials: `C:\datum-api-examples-main\datum_api_credentials.json`
- staged config: `C:\datum-api-examples-main\OriON\datum_api_config.json`
- staged credentials: `C:\datum-api-examples-main\OriON\datum_api_credentials.json`

## CRACEN
- ok: **True**
- final: `C:\datum-api-examples-main\OriON\CRACEN\final.parquet`

## Strategies
- ❌ **arbitrage** (2s) — Input Notebook:  C:\datum-api-examples-main\OriON\STRATEGIES\notebooks\ArbitRage.ipynb
Output Notebook: C:\datum-api-examples-main\OriON\status\last_ArbitRage_out.ipynb
Passed unknown parameter: run_date
Passed unknown parameter: output_dir
Input notebook does not contain a cell with tag 'parameters'

Executing:   0%|          | 0/6 [00:00<?, ?cell/s]Executing notebook with kernel: orion-venv

Executing:  17%|#6        | 1/6 [00:00<00:04,  1.01cell/s]
Executing:  50%|#####     | 3/6 [00:01<00:01,  2.67cell/s]
Executing:  67%|######6   | 4/6 [00:01<00:00,  3.23cell/s]
Executing: 100%|##########| 6/6 [00:01<00:00,  4.76cell/s]
Executing: 100%|##########| 6/6 [00:01<00:00,  3.23cell/s]
Traceback (most recent call last):
  File "C:\Program Files\Python38\lib\runpy.py", line 194, in _run_module_as_main
    return _run_code(code, main_globals, None,
  File "C:\Program Files\Python38\lib\runpy.py", line 87, in _run_code
    exec(code, run_globals)
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\papermill\__main__.py", line 4, in <module>
    papermill()
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\click\core.py", line 1161, in __call__
    return self.main(*args, **kwargs)
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\click\core.py", line 1082, in main
    rv = self.invoke(ctx)
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\click\core.py", line 1443, in invoke
    return ctx.invoke(self.callback, **ctx.params)
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\click\core.py", line 788, in invoke
    return __callback(*args, **kwargs)
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\click\decorators.py", line 33, in new_func
    return f(get_current_context(), *args, **kwargs)
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\papermill\cli.py", line 235, in papermill
    execute_notebook(
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\papermill\execute.py", line 131, in execute_notebook
    raise_for_execution_errors(nb, output_path)
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\papermill\execute.py", line 251, in raise_for_execution_errors
    raise error
papermill.exceptions.PapermillExecutionError: 
---------------------------------------------------------------------------
Exception encountered at "In [6]":
---------------------------------------------------------------------------
ModuleNotFoundError                       Traceback (most recent call last)
Cell In[6], line 4
      2 import os
      3 import pandas as pd
----> 4 from zoneinfo import ZoneInfo
      5 from datetime import datetime, timedelta
      6 import gzip

ModuleNotFoundError: No module named 'zoneinfo'
- ✅ **chrono** (1s)
- ✅ **opendoor** (1s)
- ✅ **couple** (1s)
