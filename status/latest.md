# OriON Daily Status

- Updated (UTC): **2026-07-17T15:00:25Z**
- Host: **SHAKIROV-S**

## Run
- phase: **finished**
- notebook: `OpenDoor`
- started: `2026-07-17T14:56:37Z`
- elapsed: **36022.7s**
- out notebook: `C:\datum-api-examples-main\OriON\status\last_OpenDoor_out.ipynb`
- out notebook size: `224813`
- last output: `Executing: 100%|##########| 4/4 [03:46<00:00, 56.71s/cell]`

## GitHub
- strategies repo: `https://github.com/bohdan6992/OriON-strategies.git`
- strategies sha: `b4f3b6060243`
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
- ✅ **ArbitRage** (289s)
- ✅ **ChronoFlow** (2s)
- ❌ **CoupleDating** (0s) — Input Notebook:  C:\datum-api-examples-main\OriON\STRATEGIES\notebooks\CoupleDating.ipynb
Output Notebook: C:\datum-api-examples-main\OriON\status\last_CoupleDating_out.ipynb
Traceback (most recent call last):
  File "C:\datum-api-examples-main\.env\lib\site-packages\nbformat\reader.py", line 19, in parse_json
    nb_dict = json.loads(s, **kwargs)
  File "C:\Program Files\Python38\lib\json\__init__.py", line 337, in loads
    raise JSONDecodeError("Unexpected UTF-8 BOM (decode using utf-8-sig)",
json.decoder.JSONDecodeError: Unexpected UTF-8 BOM (decode using utf-8-sig): line 1 column 1 (char 0)

The above exception was the direct cause of the following exception:

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
  File "C:\datum-api-examples-main\.env\lib\site-packages\papermill\execute.py", line 89, in execute_notebook
    nb = load_notebook_nod
- ✅ **OpenDoor** (227s)
