# StackOverflow question tag prediction

### Requirements

- [gsutil](https://cloud.google.com/storage/docs/gsutil) to download the dataset
- [TensorFlow-Metal plugin setup](https://developer.apple.com/metal/tensorflow-plugin/) (if you use macOS)

### Running

1. Setup your virtual environment

2. Install the requirements (If you don't use macOS, change `tensorflow-macos` and `tensorflow-metal` to `tensorflow`)

```
pip install -r requirements.txt
```

3. Download the dataset

```
gsutil cp 'gs://cloudml-demo-lcm/SO_ml_tags_avocado_188k_v2.csv' ./
```

4. Run the cells in `notebook.ipynb`