Thought for a couple of seconds


## Configuration

By default, the code expects preprocessed data files to be located in a directory specified by the `data_dir` variable. Update this path to point to your local copy of the `preprocessed_data` folder before running any scripts or notebooks.

```python
# In your script or notebook, set:
data_dir = r"<YOUR_FILE_PATH>/preprocessed_data"
```

For example, if you cloned the repository to `C:\Projects\DL_gtzan`, you would write:

```python
data_dir = r"C:\Projects\DL_gtzan\preprocessed_data"
```

Make sure that:

* The `preprocessed_data` folder contains all required `.pkl` (or other) files.
* The path string correctly uses forward slashes (`/`) or raw backslashes (`\\`) on Windows.

The path for the features_3_sec.csv file is set as:
"data_path = r"D:\Projects\music_genre_classification\music_genre_classification\data\features_3_sec.csv"


I apologize for the incovenience this might cause.