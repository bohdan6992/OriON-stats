# OriON Daily Status

- Updated (UTC): **2026-02-26T19:42:52Z**
- Host: **SHAKIROV-S**

## GitHub
- strategies repo: `https://github.com/bohdan6992/OriON-strategies.git`
- strategies sha: `7b43e2b524ba`
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
- ✅ **arbitrage** (443s)
- ✅ **chrono** (2s)
- ❌ **opendoor** (263s) — utput_dir, time_col, ticker_col, price_col, stack_col, bench_col, devsig_col, pre_from, pre_to, open_from, open_to, class_minutes, end_tolerance_minutes, min_move_abs, n_bins_1d, n_bins_2d, minRateTop, minTotalTop, peak_time_bin_minutes)
    305     summary = rows[0]
    306     for r in rows[1:]:
--> 307         summary = summary.merge(r, on=ticker_col, how="outer")
    309     summary.to_csv(summary_path, index=False, mode="a", header=False)
    311 # =========================
    312 # ===== JSONL WRITE =======
    313 # =========================

File C:\datum-api-examples-main\OriON\.venv\lib\site-packages\pandas\core\frame.py:9843, in DataFrame.merge(self, right, how, on, left_on, right_on, left_index, right_index, sort, suffixes, copy, indicator, validate)
   9824 @Substitution("")
   9825 @Appender(_merge_doc, indents=2)
   9826 def merge(
   (...)
   9839     validate: str | None = None,
   9840 ) -> DataFrame:
   9841     from pandas.core.reshape.merge import merge
-> 9843     return merge(
   9844         self,
   9845         right,
   9846         how=how,
   9847         on=on,
   9848         left_on=left_on,
   9849         right_on=right_on,
   9850         left_index=left_index,
   9851         right_index=right_index,
   9852         sort=sort,
   9853         suffixes=suffixes,
   9854         copy=copy,
   9855         indicator=indicator,
   9856         validate=validate,
   9857     )

File C:\datum-api-examples-main\OriON\.venv\lib\site-packages\pandas\core\reshape\merge.py:162, in merge(left, right, how, on, left_on, right_on, left_index, right_index, sort, suffixes, copy, indicator, validate)
    131 @Substitution("\nleft : DataFrame or named Series")
    132 @Appender(_merge_doc, indents=0)
    133 def merge(
   (...)
    146     validate: str | None = None,
    147 ) -> DataFrame:
    148     op = _MergeOperation(
    149         left,
    150         right,
   (...)
    160         validate=validate,
    161     )
--> 162     return op.get_result(copy=copy)

File C:\datum-api-examples-main\OriON\.venv\lib\site-packages\pandas\core\reshape\merge.py:811, in _MergeOperation.get_result(self, copy)
    807     self.left, self.right = self._indicator_pre_merge(self.left, self.right)
    809 join_index, left_indexer, right_indexer = self._get_join_info()
--> 811 result = self._reindex_and_concat(
    812     join_index, left_indexer, right_indexer, copy=copy
    813 )
    814 result = result.__finalize__(self, method=self._merge_type)
    816 if self.indicator:

File C:\datum-api-examples-main\OriON\.venv\lib\site-packages\pandas\core\reshape\merge.py:763, in _MergeOperation._reindex_and_concat(self, join_index, left_indexer, right_indexer, copy)
    760 left = self.left[:]
    761 right = self.right[:]
--> 763 llabels, rlabels = _items_overlap_with_suffix(
    764     self.left._info_axis, self.right._info_axis, self.suffixes
    765 )
    767 if left_indexer is not None and not is_range_indexer(left_indexer, len(left)):
    768     # Pinning the index here (and in the right code just below) is not
    769     #  necessary, but makes the `.take` more performant if we have e.g.
    770     #  a MultiIndex for left.index.
    771     lmgr = left._mgr.reindex_indexer(
    772         join_index,
    773         left_indexer,
   (...)
    778         use_na_proxy=True,
    779     )

File C:\datum-api-examples-main\OriON\.venv\lib\site-packages\pandas\core\reshape\merge.py:2640, in _items_overlap_with_suffix(left, right, suffixes)
   2638     dups.extend(rlabels[(rlabels.duplicated()) & (~right.duplicated())].tolist())
   2639 if dups:
-> 2640     raise MergeError(
   2641         f"Passing 'suffixes' which cause duplicate columns {set(dups)} is "
   2642         f"not allowed.",
   2643     )
   2645 return llabels, rlabels

MergeError: Passing 'suffixes' which cause duplicate columns {'median_move_x', 'total_x', 'mean_stack_delta_x', 'up_x', 'down_x', 'mean_move_x', 'median_stack_delta_x'} is not allowed.
- ✅ **couple** (2s)
