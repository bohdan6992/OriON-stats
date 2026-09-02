# OriON Daily Status

- Updated (UTC): **2026-09-02T00:01:18Z**
- Host: **CY-7GT-PC-020**

## Run
- phase: **finished**
- notebook: `SectorCorr`
- started: `2026-09-01T23:58:49Z`
- elapsed: **7276.8s**
- out notebook: `C:\datum-api-examples-main\OriON\status\last_SectorCorr_out.ipynb`
- out notebook size: `1100121`
- last output: `Executing: 100%|##########| 14/14 [02:28<00:00, 10.59s/cell]`

## GitHub
- strategies repo: `https://github.com/bohdan6992/OriON-strategies.git`
- strategies sha: `88ebdff435ac`
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
- ✅ **ArbitRage** (539s)
- ✅ **DayTwo** (984s)
- ✅ **OpenDoor** (774s)
- ❌ **PairFlux** (3s) — Input Notebook:  C:\datum-api-examples-main\OriON\STRATEGIES\notebooks\PairFlux.ipynb
Output Notebook: C:\datum-api-examples-main\OriON\status\last_PairFlux_out.ipynb

Executing:   0%|          | 0/5 [00:00<?, ?cell/s]WARNING: Insecure writes have been enabled via environment variable 'JUPYTER_ALLOW_INSECURE_WRITES'! If this is not intended, remove the variable or set its value to 'False'.
Executing notebook with kernel: python3

Executing:  20%|##        | 1/5 [00:01<00:04,  1.16s/cell]
Executing:  40%|####      | 2/5 [00:01<00:01,  1.65cell/s]
Executing:  80%|########  | 4/5 [00:01<00:00,  3.88cell/s]
Executing: 100%|##########| 5/5 [00:01<00:00,  2.55cell/s]
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
    raise_for_execution_error
- ✅ **PumpDump** (1542s)
- ✅ **SectorCorr** (149s)
