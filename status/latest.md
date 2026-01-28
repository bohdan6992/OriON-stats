# OriON Daily Status

- Updated (UTC): **2026-01-28T18:00:39Z**
- Host: **MALIAR-B**

## GitHub
- strategies repo: `https://github.com/bohdan6992/OriON-strategies.git`
- strategies sha: `73f0f7c65b0c`
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
- error: `skipped by ops config`
- final: `C:\datum-api-examples-main\OriON\CRACEN\final.parquet`

## Strategies
- ❌ **arbitrage** (0s) — *ctx.params)
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\click\core.py", line 788, in invoke
    return __callback(*args, **kwargs)
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\click\decorators.py", line 33, in new_func
    return f(get_current_context(), *args, **kwargs)
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\papermill\cli.py", line 235, in papermill
    execute_notebook(
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\papermill\execute.py", line 116, in execute_notebook
    nb = papermill_engines.execute_notebook_with_engine(
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\papermill\engines.py", line 48, in execute_notebook_with_engine
    return self.get_engine(engine_name).execute_notebook(nb, kernel_name, **kwargs)
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\papermill\engines.py", line 370, in execute_notebook
    cls.execute_managed_notebook(nb_man, kernel_name, log_output=log_output, **kwargs)
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\papermill\engines.py", line 442, in execute_managed_notebook
    return PapermillNotebookClient(nb_man, **final_kwargs).execute()
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\papermill\clientwrap.py", line 43, in execute
    with self.setup_kernel(**kwargs):
  File "C:\Program Files\Python38\lib\contextlib.py", line 113, in __enter__
    return next(self.gen)
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\nbclient\client.py", line 600, in setup_kernel
    self.start_new_kernel(**kwargs)
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\jupyter_core\utils\__init__.py", line 158, in wrapped
    return loop.run_until_complete(inner)
  File "C:\Program Files\Python38\lib\asyncio\base_events.py", line 616, in run_until_complete
    return future.result()
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\nbclient\client.py", line 550, in async_start_new_kernel
    await ensure_async(self.km.start_kernel(extra_arguments=self.extra_arguments, **kwargs))
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\jupyter_core\utils\__init__.py", line 197, in ensure_async
    result = await obj
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\jupyter_client\manager.py", line 96, in wrapper
    raise e
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\jupyter_client\manager.py", line 87, in wrapper
    out = await method(self, *args, **kwargs)
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\jupyter_client\manager.py", line 435, in _async_start_kernel
    kernel_cmd, kw = await self._async_pre_start_kernel(**kw)
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\jupyter_client\manager.py", line 400, in _async_pre_start_kernel
    kw = await self.provisioner.pre_launch(**kw)
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\jupyter_client\provisioning\local_provisioner.py", line 195, in pre_launch
    km.write_connection_file()
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\jupyter_client\connect.py", line 500, in write_connection_file
    self.connection_file, cfg = write_connection_file(
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\jupyter_client\connect.py", line 156, in write_connection_file
    with secure_write(fname) as f:
  File "C:\Program Files\Python38\lib\contextlib.py", line 113, in __enter__
    return next(self.gen)
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\jupyter_core\paths.py", line 1070, in secure_write
    win32_restrict_file_to_user(fname)
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\jupyter_core\paths.py", line 614, in win32_restrict_file_to_user
    user, _domain, _type = win32security.LookupAccountName(
pywintypes.error: (1332, 'LookupAccountName', 'No mapping between account names and security IDs was done.')
- ❌ **chrono** (0s) — *ctx.params)
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\click\core.py", line 788, in invoke
    return __callback(*args, **kwargs)
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\click\decorators.py", line 33, in new_func
    return f(get_current_context(), *args, **kwargs)
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\papermill\cli.py", line 235, in papermill
    execute_notebook(
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\papermill\execute.py", line 116, in execute_notebook
    nb = papermill_engines.execute_notebook_with_engine(
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\papermill\engines.py", line 48, in execute_notebook_with_engine
    return self.get_engine(engine_name).execute_notebook(nb, kernel_name, **kwargs)
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\papermill\engines.py", line 370, in execute_notebook
    cls.execute_managed_notebook(nb_man, kernel_name, log_output=log_output, **kwargs)
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\papermill\engines.py", line 442, in execute_managed_notebook
    return PapermillNotebookClient(nb_man, **final_kwargs).execute()
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\papermill\clientwrap.py", line 43, in execute
    with self.setup_kernel(**kwargs):
  File "C:\Program Files\Python38\lib\contextlib.py", line 113, in __enter__
    return next(self.gen)
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\nbclient\client.py", line 600, in setup_kernel
    self.start_new_kernel(**kwargs)
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\jupyter_core\utils\__init__.py", line 158, in wrapped
    return loop.run_until_complete(inner)
  File "C:\Program Files\Python38\lib\asyncio\base_events.py", line 616, in run_until_complete
    return future.result()
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\nbclient\client.py", line 550, in async_start_new_kernel
    await ensure_async(self.km.start_kernel(extra_arguments=self.extra_arguments, **kwargs))
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\jupyter_core\utils\__init__.py", line 197, in ensure_async
    result = await obj
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\jupyter_client\manager.py", line 96, in wrapper
    raise e
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\jupyter_client\manager.py", line 87, in wrapper
    out = await method(self, *args, **kwargs)
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\jupyter_client\manager.py", line 435, in _async_start_kernel
    kernel_cmd, kw = await self._async_pre_start_kernel(**kw)
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\jupyter_client\manager.py", line 400, in _async_pre_start_kernel
    kw = await self.provisioner.pre_launch(**kw)
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\jupyter_client\provisioning\local_provisioner.py", line 195, in pre_launch
    km.write_connection_file()
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\jupyter_client\connect.py", line 500, in write_connection_file
    self.connection_file, cfg = write_connection_file(
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\jupyter_client\connect.py", line 156, in write_connection_file
    with secure_write(fname) as f:
  File "C:\Program Files\Python38\lib\contextlib.py", line 113, in __enter__
    return next(self.gen)
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\jupyter_core\paths.py", line 1070, in secure_write
    win32_restrict_file_to_user(fname)
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\jupyter_core\paths.py", line 614, in win32_restrict_file_to_user
    user, _domain, _type = win32security.LookupAccountName(
pywintypes.error: (1332, 'LookupAccountName', 'No mapping between account names and security IDs was done.')
- ❌ **opendoor** (0s) — *ctx.params)
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\click\core.py", line 788, in invoke
    return __callback(*args, **kwargs)
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\click\decorators.py", line 33, in new_func
    return f(get_current_context(), *args, **kwargs)
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\papermill\cli.py", line 235, in papermill
    execute_notebook(
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\papermill\execute.py", line 116, in execute_notebook
    nb = papermill_engines.execute_notebook_with_engine(
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\papermill\engines.py", line 48, in execute_notebook_with_engine
    return self.get_engine(engine_name).execute_notebook(nb, kernel_name, **kwargs)
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\papermill\engines.py", line 370, in execute_notebook
    cls.execute_managed_notebook(nb_man, kernel_name, log_output=log_output, **kwargs)
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\papermill\engines.py", line 442, in execute_managed_notebook
    return PapermillNotebookClient(nb_man, **final_kwargs).execute()
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\papermill\clientwrap.py", line 43, in execute
    with self.setup_kernel(**kwargs):
  File "C:\Program Files\Python38\lib\contextlib.py", line 113, in __enter__
    return next(self.gen)
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\nbclient\client.py", line 600, in setup_kernel
    self.start_new_kernel(**kwargs)
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\jupyter_core\utils\__init__.py", line 158, in wrapped
    return loop.run_until_complete(inner)
  File "C:\Program Files\Python38\lib\asyncio\base_events.py", line 616, in run_until_complete
    return future.result()
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\nbclient\client.py", line 550, in async_start_new_kernel
    await ensure_async(self.km.start_kernel(extra_arguments=self.extra_arguments, **kwargs))
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\jupyter_core\utils\__init__.py", line 197, in ensure_async
    result = await obj
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\jupyter_client\manager.py", line 96, in wrapper
    raise e
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\jupyter_client\manager.py", line 87, in wrapper
    out = await method(self, *args, **kwargs)
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\jupyter_client\manager.py", line 435, in _async_start_kernel
    kernel_cmd, kw = await self._async_pre_start_kernel(**kw)
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\jupyter_client\manager.py", line 400, in _async_pre_start_kernel
    kw = await self.provisioner.pre_launch(**kw)
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\jupyter_client\provisioning\local_provisioner.py", line 195, in pre_launch
    km.write_connection_file()
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\jupyter_client\connect.py", line 500, in write_connection_file
    self.connection_file, cfg = write_connection_file(
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\jupyter_client\connect.py", line 156, in write_connection_file
    with secure_write(fname) as f:
  File "C:\Program Files\Python38\lib\contextlib.py", line 113, in __enter__
    return next(self.gen)
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\jupyter_core\paths.py", line 1070, in secure_write
    win32_restrict_file_to_user(fname)
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\jupyter_core\paths.py", line 614, in win32_restrict_file_to_user
    user, _domain, _type = win32security.LookupAccountName(
pywintypes.error: (1332, 'LookupAccountName', 'No mapping between account names and security IDs was done.')
- ❌ **couple** (0s) — *ctx.params)
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\click\core.py", line 788, in invoke
    return __callback(*args, **kwargs)
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\click\decorators.py", line 33, in new_func
    return f(get_current_context(), *args, **kwargs)
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\papermill\cli.py", line 235, in papermill
    execute_notebook(
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\papermill\execute.py", line 116, in execute_notebook
    nb = papermill_engines.execute_notebook_with_engine(
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\papermill\engines.py", line 48, in execute_notebook_with_engine
    return self.get_engine(engine_name).execute_notebook(nb, kernel_name, **kwargs)
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\papermill\engines.py", line 370, in execute_notebook
    cls.execute_managed_notebook(nb_man, kernel_name, log_output=log_output, **kwargs)
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\papermill\engines.py", line 442, in execute_managed_notebook
    return PapermillNotebookClient(nb_man, **final_kwargs).execute()
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\papermill\clientwrap.py", line 43, in execute
    with self.setup_kernel(**kwargs):
  File "C:\Program Files\Python38\lib\contextlib.py", line 113, in __enter__
    return next(self.gen)
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\nbclient\client.py", line 600, in setup_kernel
    self.start_new_kernel(**kwargs)
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\jupyter_core\utils\__init__.py", line 158, in wrapped
    return loop.run_until_complete(inner)
  File "C:\Program Files\Python38\lib\asyncio\base_events.py", line 616, in run_until_complete
    return future.result()
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\nbclient\client.py", line 550, in async_start_new_kernel
    await ensure_async(self.km.start_kernel(extra_arguments=self.extra_arguments, **kwargs))
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\jupyter_core\utils\__init__.py", line 197, in ensure_async
    result = await obj
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\jupyter_client\manager.py", line 96, in wrapper
    raise e
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\jupyter_client\manager.py", line 87, in wrapper
    out = await method(self, *args, **kwargs)
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\jupyter_client\manager.py", line 435, in _async_start_kernel
    kernel_cmd, kw = await self._async_pre_start_kernel(**kw)
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\jupyter_client\manager.py", line 400, in _async_pre_start_kernel
    kw = await self.provisioner.pre_launch(**kw)
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\jupyter_client\provisioning\local_provisioner.py", line 195, in pre_launch
    km.write_connection_file()
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\jupyter_client\connect.py", line 500, in write_connection_file
    self.connection_file, cfg = write_connection_file(
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\jupyter_client\connect.py", line 156, in write_connection_file
    with secure_write(fname) as f:
  File "C:\Program Files\Python38\lib\contextlib.py", line 113, in __enter__
    return next(self.gen)
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\jupyter_core\paths.py", line 1070, in secure_write
    win32_restrict_file_to_user(fname)
  File "C:\datum-api-examples-main\OriON\.venv\lib\site-packages\jupyter_core\paths.py", line 614, in win32_restrict_file_to_user
    user, _domain, _type = win32security.LookupAccountName(
pywintypes.error: (1332, 'LookupAccountName', 'No mapping between account names and security IDs was done.')
