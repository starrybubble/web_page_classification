This repository contains Deep learning algorithms for web page classification written in Tensorflow (Python).

## Requirements
```
mkvirtualenv --python=`which python3` --system-site-packages wpc
pip install -r requirements.txt
```
- Python 3.2+
- numpy
- TensorFlow 0.8+
- [NLTK 3.0](http://www.nltk.org/install.html)
- [google 1.9.1+](https://pypi.python.org/pypi/google)

## Running
```
python -m collect --data_dir ~/Downloads/wpc --pages_per_file 3
python -m collect --data_dir ~/Downloads/wpc --pages_per_file 100 --max_file_num 5

python -m convert --data_dir ~/Downloads/wpc --html_folder html_1
```


## Modules

## License
MIT

##Note
### googlescraper
put chromedriver under ~/work/py-envs/wpc/bin/
