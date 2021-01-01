# twitter_follow
======================

## Purpose
Subscribe to twitter users by selenium webdriver

## Usage
run pip to ensure all requirements are fulfilled
 
```bash
pip3 install -r requirements.txt
```

You also need ChromeDriver, which you can download [here](https://chromedriver.chromium.org/downloads) and store the execuable in the script folder.

If you prefer Firefox, download geckodriver [here](https://github.com/mozilla/geckodriver/releases).
and adjust the following line in main.py
```python
browser = base_path / 'geckodriver.exe'
```

now you can run the script:
```bash
main.py
```

## License
This code is licensed under the [GNU General Public License v3.0](https://choosealicense.com/licenses/gpl-3.0/). 
For more details, please take a look at the [LICENSE file](https://github.com/argv1/twitter_follow/blob/master/LICENSE).
