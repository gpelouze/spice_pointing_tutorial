# SPICE offsets tutorial

To run the notebook yourself, run:

```shell
git clone https://github.com/gpelouze/spice_pointing_tutorial.git
```

Then, copy `solo_L2_spice-n-ras_20210914T025031_V07_67109159-000.fits` and
`solo_L2_spice-n-ras_20220325T131648_V01_100663893-000.fits` from the archive
into `spice_pointing_tutorial/data` and run:

```shell
cd spice_pointing_tutorial
virtualenv venv
. venv/bin/activate
pip install jupyterlab
jupyter-lab spice_pointing_tutorial.ipynb
```
