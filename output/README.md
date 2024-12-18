Normally, BIDS derivatives are stored in the `sourcedata` folder.

In the init_bids_study.ipynb file, the root_location is set to the `output` folder as NeuroLibre does not allow writing to the `sourcedata` folder.

```python
root_location = '../output' # Path to the root, don't change unless very certain
```

This means that the BIDS derivatives will be stored in the `output` folder.

Outside the neurolibre environment, you can set the root_location to the `sourcedata` folder.

```python
root_location = '..' # Path to the root, don't change unless very certain
```

This means that the BIDS derivatives will be stored in the `sourcedata` folder.