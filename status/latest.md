# OriON Daily Status

- Updated (UTC): **2026-11-24T23:48:19Z**
- Host: **DESKTOP-AIAN4TG**

## Run
- phase: **finished**
- notebook: `PairFlux`
- started: `2026-11-24T21:56:49Z`
- elapsed: **25439.3s**
- out notebook: `C:\datum-api-examples-main\OriOn\status\last_PairFlux_out.ipynb`
- out notebook size: `209728`

## GitHub
- strategies repo: `https://github.com/bohdan6992/OriON-strategies.git`
- strategies sha: `fd1fc20924ef`
- strategies updated: **True**
- results repo: `https://github.com/bohdan6992/OriON-stats.git`
- results commit: `4a64ee43664bebf249ee68ee3d5e091d17b9d9e0`
- results pushed: **False**
- results error: `git push failed: remote: warning: File signals/daytwo/onefile.jsonl.gz is 70.18 MB; this is larger than GitHub's recommended maximum file size of 50.00 MB        
remote: warning: File signals/arbitrage/onefile.jsonl.gz is 65.17 MB; this is larger than GitHub's recommended maximum file size of 50.00 MB        
remote: warning: File signals/daytwo/events.jsonl.gz is 83.08 MB; this is larger than GitHub's recommended maximum file size of 50.00 MB        
remote: error: Trace: 75c763924288602cc562f6f33cc2f03e8dfe4d2f189ff44783a3935f9b453df9        
remote: error: See https://gh.io/lfs for more information.        
remote: error: File signals/pairflux/episodes.jsonl.gz is 317.25 MB; this exceeds GitHub's file size limit of 100.00 MB        
remote: error: GH001: Large files detected. You may want to try Git Large File Storage - https://git-lfs.github.com.        
remote: pre-receive hook declined
To https://github.com/bohdan6992/OriON-stats.git
 ! [remote rejected] HEAD -> main (pre-receive hook declined)
error: failed to push some refs to 'https://github.com/bohdan6992/OriON-stats.git'`
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
- ✅ **CLO•reversal** (1746s)
- ✅ **CLO•continuum** (1747s)
- ✅ **LAUNCH•MORNING** (309s)
- ✅ **MARKET-regime** (18s)
- ✅ **LAUNCH•EVENING** (526s)
- ✅ **OPG•continuum** (995s)
- ✅ **OPG•fade** (993s)
- ✅ **OPG•reversal** (949s)
- ✅ **OPG•ride** (997s)
- ✅ **PullBack** (589s)
- ✅ **QUARTERLY** (575s)
- ✅ **SectorCorr** (417s)
- ✅ **ArbitRage** (6735s)
- ✅ **STRETCH•FADE** (1004s)
- ❌ **VWAPBounce** (10s) — Input Notebook:  C:\datum-api-examples-main\OriOn\STRATEGIES\notebooks\VWAPBounce.ipynb
Output Notebook: C:\datum-api-examples-main\OriOn\status\last_VWAPBounce_out.ipynb
C:\datum-api-examples-main\OriOn\.venv\lib\site-packages\nbformat\__init__.py:96: MissingIDFieldWarning: Cell is missing an id field, this will become a hard error in future nbformat versions. You may want to use `normalize()` on your notebooks before validations (available since nbformat 5.1.4). Previous versions of nbformat are fixing this issue transparently, and will stop doing so in the future.
  validate(nb)

Executing:   0%|          | 0/9 [00:00<?, ?cell/s]WARNING: Insecure writes have been enabled via environment variable 'JUPYTER_ALLOW_INSECURE_WRITES'! If this is not intended, remove the variable or set its value to 'False'.
Executing notebook with kernel: python3

Executing:  11%|#1        | 1/9 [00:02<00:20,  2.62s/cell]
Executing:  22%|##2       | 2/9 [00:03<00:10,  1.43s/cell]
Executing:  56%|#####5    | 5/9 [00:03<00:02,  1.85cell/s]Assertion failed: Connection reset by peer [10054] (C:\Users\runneradmin\AppData\Local\Temp\tmpeasux9pb\build\_deps\bundled_libzmq-src\src\signaler.cpp:345)

Executing:  56%|#####5    | 5/9 [00:06<00:05,  1.38s/cell]
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
  File "C:\datum-api-examples-main\OriOn\.venv\lib\site-packages\click\core.py", line 1443, in 
- ✅ **STRETCH•RIDE** (941s)
- ✅ **PairFlux** (6691s)
