# Running CMIP6 with Beam on Dask.

1. `pip install -r requirements.txt`
2. `dask-scheduler` (see [dask distributed quickstart](https://distributed.dask.org/en/stable/quickstart.html).)
3. Run the example pipeline:
   ```commandline
   python3 cmpi6_ref_beam.py --dask_client_address localhost:8786
   ```