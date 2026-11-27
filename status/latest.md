# OriON Daily Status

- Updated (UTC): **2026-11-27T21:33:38Z**
- Host: **DESKTOP-AIAN4TG**

## Run
- phase: **finished**
- notebook: `LAUNCH•MORNING`
- started: `2026-11-27T21:29:16Z`
- elapsed: **23616.3s**
- out notebook: `C:\datum-api-examples-main\OriOn\status\last_LAUNCH•MORNING_out.ipynb`
- out notebook size: `34746`

## GitHub
- strategies repo: `https://github.com/bohdan6992/OriON-strategies.git`
- strategies sha: `493b8254ed43`
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
- ❌ **VWAPBounce** (7s) — Input Notebook:  C:\datum-api-examples-main\OriOn\STRATEGIES\notebooks\VWAPBounce.ipynb
Output Notebook: C:\datum-api-examples-main\OriOn\status\last_VWAPBounce_out.ipynb
C:\datum-api-examples-main\OriOn\.venv\lib\site-packages\nbformat\__init__.py:96: MissingIDFieldWarning: Cell is missing an id field, this will become a hard error in future nbformat versions. You may want to use `normalize()` on your notebooks before validations (available since nbformat 5.1.4). Previous versions of nbformat are fixing this issue transparently, and will stop doing so in the future.
  validate(nb)

Executing:   0%|          | 0/9 [00:00<?, ?cell/s]WARNING: Insecure writes have been enabled via environment variable 'JUPYTER_ALLOW_INSECURE_WRITES'! If this is not intended, remove the variable or set its value to 'False'.
Executing notebook with kernel: python3

Executing:  11%|#1        | 1/9 [00:02<00:20,  2.52s/cell]
Executing:  22%|##2       | 2/9 [00:03<00:10,  1.48s/cell]
Executing:  44%|####4     | 4/9 [00:03<00:02,  1.71cell/s]
Executing:  56%|#####5    | 5/9 [00:03<00:02,  1.80cell/s]
Executing:  56%|#####5    | 5/9 [00:04<00:03,  1.19cell/s]
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
  File "C:\datum-api-examples-main\OriOn
- ✅ **ARB•FADE** (6892s)
- ✅ **ARB•RIDE** (6955s)
- ✅ **PairFlux** (7872s)
- ✅ **CLO•reversal** (1808s)
- ✅ **CLO•continuum** (1797s)
- ✅ **OPG•ride** (1072s)
- ✅ **OPG•continuum** (1096s)
- ✅ **OPG•fade** (1106s)
- ✅ **OPG•reversal** (1054s)
- ✅ **PullBack** (654s)
- ✅ **STRETCH•FADE** (1034s)
- ✅ **STRETCH•RIDE** (1045s)
- ✅ **LAUNCH•EVENING** (490s)
- ✅ **SectorCorr** (447s)
- ✅ **MARKET-regime** (16s)
- ✅ **QUARTERLY** (390s)
- ✅ **LAUNCH•MORNING** (263s)
