# OriON Daily Status

- Updated (UTC): **2026-11-26T20:35:51Z**
- Host: **DESKTOP-AIAN4TG**

## Run
- phase: **finished**
- notebook: `QUARTERLY`
- started: `2026-11-26T20:29:32Z`
- elapsed: **20149.7s**
- out notebook: `C:\datum-api-examples-main\OriOn\status\last_QUARTERLY_out.ipynb`
- out notebook size: `66219`

## GitHub
- strategies repo: `https://github.com/bohdan6992/OriON-strategies.git`
- strategies sha: `fbb33699f746`
- strategies updated: **True**
- results repo: `https://github.com/bohdan6992/OriON-stats.git`
- results layout: `root`
- results subdir: ``

## Datum API
- ok: **True**
- config: `C:\datum-api-examples-main\datum_api_config.json`
- credentials: `C:\datum-api-examples-main\datum_api_credentials.json`
- staged config: `C:\datum-api-examples-main\OriOn\datum_api_config.json`
- staged credentials: `C:\datum-api-examples-main\OriOn\datum_api_credentials.json`

## CRACEN
- ok: **True**
- final: `C:\datum-api-examples-main\OriOn\CRACEN\final.parquet`

## Strategies
- ❌ **VWAPBounce** (5s) — Input Notebook:  C:\datum-api-examples-main\OriOn\STRATEGIES\notebooks\VWAPBounce.ipynb
Output Notebook: C:\datum-api-examples-main\OriOn\status\last_VWAPBounce_out.ipynb
C:\datum-api-examples-main\OriOn\.venv\lib\site-packages\nbformat\__init__.py:96: MissingIDFieldWarning: Cell is missing an id field, this will become a hard error in future nbformat versions. You may want to use `normalize()` on your notebooks before validations (available since nbformat 5.1.4). Previous versions of nbformat are fixing this issue transparently, and will stop doing so in the future.
  validate(nb)

Executing:   0%|          | 0/9 [00:00<?, ?cell/s]WARNING: Insecure writes have been enabled via environment variable 'JUPYTER_ALLOW_INSECURE_WRITES'! If this is not intended, remove the variable or set its value to 'False'.
Executing notebook with kernel: python3

Executing:  11%|#1        | 1/9 [00:01<00:15,  1.88s/cell]
Executing:  22%|##2       | 2/9 [00:02<00:07,  1.14s/cell]
Executing:  56%|#####5    | 5/9 [00:03<00:01,  2.23cell/s]
Executing:  56%|#####5    | 5/9 [00:03<00:02,  1.53cell/s]
Traceback (most recent call last):
  File "C:\Program Files\Python38\lib\runpy.py", line 194, in _run_module_as_main
    return _run_code(code, main_globals, None,
  File "C:\Program Files\Python38\lib\runpy.py", line 87, in _run_code
    exec(code, run_globals)
  File "C:\datum-api-examples-main\OriOn\.venv\lib\site-packages\papermill\__main__.py", line 4, in <module>
    papermill()
  File "C:\datum-api-examples-main\OriOn\.venv\lib\site-packages\click\core.py", line 1161, in __call__
    return self.main(*args, **kwargs)
  File "C:\datum-api-examples-main\OriOn\.venv\lib\site-packages\click\core.py", line 1082, in main
    rv = self.invoke(ctx)
  File "C:\datum-api-examples-main\OriOn\.venv\lib\site-packages\click\core.py", line 1443, in invoke
    return ctx.invoke(self.callback, **ctx.params)
  File "C:\datum-api-examples-main\OriOn\.venv\lib\site-packages\click\core.py", line 788, in invok
- ✅ **ARB•RIDE** (6194s)
- ✅ **ARB•FADE** (6210s)
- ✅ **PairFlux** (6945s)
- ✅ **OPG•fade** (1135s)
- ✅ **CLO•reversal** (1910s)
- ✅ **CLO•continuum** (1895s)
- ✅ **STRETCH•RIDE** (1074s)
- ✅ **OPG•reversal** (1117s)
- ✅ **OPG•ride** (1180s)
- ✅ **PullBack** (674s)
- ✅ **STRETCH•FADE** (1084s)
- ✅ **OPG•continuum** (1177s)
- ✅ **LAUNCH•EVENING** (539s)
- ✅ **SectorCorr** (446s)
- ✅ **MARKET-regime** (16s)
- ✅ **LAUNCH•MORNING** (268s)
- ✅ **QUARTERLY** (380s)
