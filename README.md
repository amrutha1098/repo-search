# repo_search_automation

The git hub repo for repo-search [link](https://github.com/kesavan-rangan/repo-search)

The original repo for automation this can be found in https://github.com/amrutha1098/repo_search_auto

Automated framework for repository Search [Github](https://github.com/kesavan-rangan/repo-search)

### Installation

```console

pip install selenium
pip install html-testRunner
pip install requests

 **************** or ******************
 
 pip install -r requirements.txt
 
```
1 . Please follow following instruction ( changes to be done in html-testRunner module ) to generate proper html report [link](https://stackoverflow.com/questions/71858651/attributeerror-htmltestresult-object-has-no-attribute-count-relevant-tb-lev)

2 . Copy the required chrome webdriver to repo_search_automation/input folder [link](https://chromedriver.chromium.org/downloads).
    To check which chromedriver to be downloaded open google chrome, click the three dots in the upper-right corner of the window and click on help. 

3 . If subprocess module is not installed , install python3 subprocess module.

### Run

Move to the foder <strong>/repo-search</strong> and execute the following command 

```console 
python3 setup.py [-t [smoke | full_regression ]] 

```

smoke : runs somke test cases
full_regression : runs full fledged test


To run individauly 

```console
python3 scripts/test_suites/repo_search.py

```

### Where do we find the report and logs 

```console

report > repo_search_automation/reports/MyReport.html
logs >  repo_search_automation/logs
```
