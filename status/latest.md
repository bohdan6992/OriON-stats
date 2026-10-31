# OriON Daily Status

- Updated (UTC): **2026-10-31T01:46:22Z**
- Host: **CY-7GT-PC-020**

## Run
- phase: **finished**
- notebook: `VWAPBounce`
- started: `2026-10-31T01:46:20Z`
- elapsed: **13580.7s**
- out notebook: `C:\datum-api-examples-main\OriON\status\last_VWAPBounce_out.ipynb`
- out notebook size: `91638`
- last output: `Input Notebook:  C:\datum-api-examples-main\OriON\STRATEGIES\notebooks\VWAPBounce.ipynb
Output Notebook: C:\datum-api-examples-main\OriON\status\last_VWAPBounce_out.ipynb
C:\datum-api-examples-main\.env\lib\site-packages\nbformat\__init__.py:96: MissingIDFieldWarning: Cell is missing an id field, this will become a hard error in future nbformat versions. You may want to use `normalize()` on your notebooks before validations (available since nbformat 5.1.4). Previous versions of nbformat are fixing this issue transparently, and will stop doing so in the future.
  validate(nb)

Executing:   0%|          | 0/9 [00:00<?, ?cell/s]WARNING: Insecure writes have been enabled via environment variable 'JUPYTER_ALLOW_INSECURE_WRITES'! If this is not intended, remove the variable or set its value to 'False'.
Executing notebook with kernel: python3

Executing:  11%|#1        | 1/9 [00:00<00:07,  1.04cell/s]
Executing:  22%|##2       | 2/9 [00:01<00:03,  2.06cell/s]
Executing:  56%|#####5    | 5/9 [00:01<00:00,  5.16cell/s]
Executing:  56%|#####5    | 5/9 [00:01<00:01,  3.40cell/s]
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
 `

## GitHub
- strategies repo: `https://github.com/bohdan6992/OriON-strategies.git`
- strategies sha: `f9cba833c154`
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
- ✅ **ArbitRage** (2999s)
- ✅ **CLO•continuum** (426s)
- ✅ **CLO•reversal** (427s)
- ✅ **DayTwo** (1006s)
- ✅ **LAUNCH•EVENING** (110s)
- ✅ **LAUNCH•MORNING** (89s)
- ✅ **OpenDoor** (785s)
- ✅ **OPG•continuum** (376s)
- ✅ **OPG•fade** (365s)
- ✅ **OPG•reversal** (370s)
- ✅ **OPG•ride** (369s)
- ✅ **PairFlux** (752s)
- ✅ **PullBack** (180s)
- ✅ **PumpDump** (1587s)
- ✅ **SectorCorr** (459s)
- ❌ **VWAPBounce** (2s) — Input Notebook:  C:\datum-api-examples-main\OriON\STRATEGIES\notebooks\VWAPBounce.ipynb
Output Notebook: C:\datum-api-examples-main\OriON\status\last_VWAPBounce_out.ipynb
C:\datum-api-examples-main\.env\lib\site-packages\nbformat\__init__.py:96: MissingIDFieldWarning: Cell is missing an id field, this will become a hard error in future nbformat versions. You may want to use `normalize()` on your notebooks before validations (available since nbformat 5.1.4). Previous versions of nbformat are fixing this issue transparently, and will stop doing so in the future.
  validate(nb)

Executing:   0%|          | 0/9 [00:00<?, ?cell/s]WARNING: Insecure writes have been enabled via environment variable 'JUPYTER_ALLOW_INSECURE_WRITES'! If this is not intended, remove the variable or set its value to 'False'.
Executing notebook with kernel: python3

Executing:  11%|#1        | 1/9 [00:00<00:07,  1.04cell/s]
Executing:  22%|##2       | 2/9 [00:01<00:03,  2.06cell/s]
Executing:  56%|#####5    | 5/9 [00:01<00:00,  5.16cell/s]
Executing:  56%|#####5    | 5/9 [00:01<00:01,  3.40cell/s]
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
 
