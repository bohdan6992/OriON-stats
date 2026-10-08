# OriON Daily Status

- Updated (UTC): **2026-10-08T01:35:24Z**
- Host: **CY-7GT-PC-020**

## Run
- phase: **finished**
- notebook: `VWAPBounce`
- started: `2026-10-08T01:35:22Z`
- elapsed: **12922.5s**
- out notebook: `C:\datum-api-examples-main\OriON\status\last_VWAPBounce_out.ipynb`
- out notebook size: `82324`
- last output: `Input Notebook:  C:\datum-api-examples-main\OriON\STRATEGIES\notebooks\VWAPBounce.ipynb
Output Notebook: C:\datum-api-examples-main\OriON\status\last_VWAPBounce_out.ipynb

Executing:   0%|          | 0/8 [00:00<?, ?cell/s]WARNING: Insecure writes have been enabled via environment variable 'JUPYTER_ALLOW_INSECURE_WRITES'! If this is not intended, remove the variable or set its value to 'False'.
Executing notebook with kernel: python3

Executing:  12%|#2        | 1/8 [00:00<00:06,  1.05cell/s]
Executing:  25%|##5       | 2/8 [00:01<00:02,  2.04cell/s]
Executing:  62%|######2   | 5/8 [00:01<00:00,  5.13cell/s]
Executing:  62%|######2   | 5/8 [00:01<00:00,  3.37cell/s]
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
    raise_for_execution_e`

## GitHub
- strategies repo: `https://github.com/bohdan6992/OriON-strategies.git`
- strategies sha: `4e8876dd86ca`
- strategies updated: **False**
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
- ✅ **ArbitRage** (2860s)
- ✅ **CLO•continuum** (449s)
- ✅ **CLO•reversal** (446s)
- ✅ **DayTwo** (976s)
- ✅ **OpenDoor** (759s)
- ✅ **OPG•continuum** (344s)
- ✅ **OPG•reversal** (344s)
- ✅ **PairFlux** (730s)
- ✅ **Pullback** (1266s)
- ✅ **PumpDump** (1520s)
- ✅ **SectorCorr** (158s)
- ❌ **VWAPBounce** (2s) — Input Notebook:  C:\datum-api-examples-main\OriON\STRATEGIES\notebooks\VWAPBounce.ipynb
Output Notebook: C:\datum-api-examples-main\OriON\status\last_VWAPBounce_out.ipynb

Executing:   0%|          | 0/8 [00:00<?, ?cell/s]WARNING: Insecure writes have been enabled via environment variable 'JUPYTER_ALLOW_INSECURE_WRITES'! If this is not intended, remove the variable or set its value to 'False'.
Executing notebook with kernel: python3

Executing:  12%|#2        | 1/8 [00:00<00:06,  1.05cell/s]
Executing:  25%|##5       | 2/8 [00:01<00:02,  2.04cell/s]
Executing:  62%|######2   | 5/8 [00:01<00:00,  5.13cell/s]
Executing:  62%|######2   | 5/8 [00:01<00:00,  3.37cell/s]
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
    raise_for_execution_e
