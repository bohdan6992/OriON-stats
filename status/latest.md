# OriON Daily Status

- Updated (UTC): **2026-06-29T03:12:33Z**
- Host: **SHAKIROV-S**

## Run
- phase: **finished**
- notebook: `OpenDoor`
- started: `2026-06-29T03:09:59Z`
- elapsed: **9750.6s**
- out notebook: `C:\datum-api-examples-main\OriON\status\last_OpenDoor_out.ipynb`
- out notebook size: `196530`
- last output: `Executing: 100%|##########| 4/4 [02:33<00:00, 38.31s/cell]`

## GitHub
- strategies repo: `https://github.com/bohdan6992/OriON-strategies.git`
- strategies sha: `9fb1416e2a66`
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
- ❌ **ArbitRage** (3s) — Input Notebook:  C:\datum-api-examples-main\OriON\STRATEGIES\notebooks\ArbitRage.ipynb
Output Notebook: C:\datum-api-examples-main\OriON\status\last_ArbitRage_out.ipynb

Executing:   0%|          | 0/5 [00:00<?, ?cell/s]WARNING: Insecure writes have been enabled via environment variable 'JUPYTER_ALLOW_INSECURE_WRITES'! If this is not intended, remove the variable or set its value to 'False'.
Executing notebook with kernel: python3

Executing:  20%|##        | 1/5 [00:02<00:08,  2.16s/cell]
Executing:  40%|####      | 2/5 [00:02<00:03,  1.03s/cell]
Executing:  60%|######    | 3/5 [00:02<00:01,  1.58cell/s]
Executing:  60%|######    | 3/5 [00:02<00:01,  1.12cell/s]
Traceback (most recent call last):
  File "C:\Program Files\Python38\lib\runpy.py", line 194, in _run_module_as_main
    return _run_code(code, main_globals, None,
  File "C:\Program Files\Python38\lib\runpy.py", line 87, in _run_code
    exec(code, run_globals)
  File "C:\datum-api-examples-main\.env\lib\site-packages\papermill\__main__.py", line 4, in <module>
    papermill()
  File "C:\datum-api-examples-main\.env\lib\site-packages\click\core.py", line 1161, in __call__
    return self.main(*args, **kwargs)
  File "C:\datum-api-examples-main\.env\lib\site-packages\click\core.py", line 1082, in main
    rv = self.invoke(ctx)
  File "C:\datum-api-examples-main\.env\lib\site-packages\click\core.py", line 1443, in invoke
    return ctx.invoke(self.callback, **ctx.params)
  File "C:\datum-api-examples-main\.env\lib\site-packages\click\core.py", line 788, in invoke
    return __callback(*args, **kwargs)
  File "C:\datum-api-examples-main\.env\lib\site-packages\click\decorators.py", line 33, in new_func
    return f(get_current_context(), *args, **kwargs)
  File "C:\datum-api-examples-main\.env\lib\site-packages\papermill\cli.py", line 235, in papermill
    execute_notebook(
  File "C:\datum-api-examples-main\.env\lib\site-packages\papermill\execute.py", line 131, in execute_notebook
    raise_for_execution_err
- ✅ **ChronoFlow** (2s)
- ✅ **CoupleDating** (2s)
- ✅ **OpenDoor** (154s)
