## `ptr` Change History

Each release to PyPI I'm going to give a codename as to where I am or was in the world 🌏.

### 2019.10.22

Codename: **Cairo, Egypt 🇪🇬**

*@adhaamehab who first time contributed is from there! Thanks!*

- Print more helpful error when file does not exist for coverage check - PR: #51
- Officially Support Python 3.8 and enforce tests passing
- Disable pyre-check for >=3.8 due to no support
  - Issue to Track: https://github.com/facebook/pyre-check/issues/213

### 2019.10.6

Codename: **Stanford, CA**

*@cooperlees tailgated there yesterday 🚐🏈*

- Handle OSX /private in coverage report - PR: #60

### 2019.9.14

Codename: **Clowntown 🤡**

- Fix bad bool passing for `--print-cov` + `--error-on-warnings`

### 2019.9.11

Codename: **Rathbone Square**

*@cooperlees is releasing this release from FB London Office*

- Add CLI option to enable erroring on all [warnings](https://docs.python.org/3/library/warnings.html) - Issue: #57

### 2019.8.7

Codename: **Ellicott City**

*@omikader who reported and tested the fix for AST parsing is from there.*
*Ellicott City is also home to one of the oldest surving train stations in the US!*

- Fix AST parsing to ignore AST targets that do not have an `id` attribute - Issue: #54
- Renable `black` by default on 3.7 now that it runs on > 3.7.2 - Issue: #41
- Fix --venv-timeout to store ints
- Refactor _get_test_modules function to remove lint error - PR: #53 - *Thanks @TomasFeeney*

### 2019.7.16

Codename: **California City**

*An over developed desert with infrastructure and little [people](https://en.wikipedia.org/wiki/California_City,_California)*

- Add `--print-non-configured` to find non `ptr` modules in repos - Issue: #50

### 2019.6.15

Codename: **Concord**

*🛫 @cooperlees is playing Aussie Football @ Concord, CA today 🏈*

- Add ability to `disable` test suites and add a `--run-disabled` option to force the run - Issue: #46
- Azure CI now runs on Mac and Windows again

### 2019.5.3

Codename: **Cleveland**

*🇺🇸 @cooperlees + @jreese are at PyCon US in Cleveland, OH 🦅*

- Print step name in failue output - Issue: #31
- Add in `pyre` Type Checking step support - Issue: #38 + #40

**Known Bug:** `black.exe` does not run in Windows 3.7 - **disabled** by *default* on Python 3.7 on Windows

### 2019.3.5

Codename: **Jaipur**

*🇮🇳 @cooperlees releasing whilst in Jaipur, India for a wedding 💒*

- Preliminary Windows support now ready for testing - Issue: #2
- Run tests/mypy/flake8 etc. in CWD of setup.py path - Issue #23 - Thanks @jreese
- Add support for linting with flake8 and pylint - Issue #20 - Thanks @jreese
- Ignore dotted directories when running black - PR #19 - Thanks @jreese

**Known Bug:** `black.exe` does not run in Windows 3.7 - **disabled** by *default* on Python 3.7 on Windows

### 2019.2.12

Codename: **Forbes**

*[Forbes, NSW, Australia](https://en.wikipedia.org/wiki/Forbes,_New_South_Wales) is the home of @aijayadams 👨🏻‍🦰🇦🇺*

- Added suite file coverage % to statistics JSON file - Issue: #16 - *Thanks @aijayadams*
- Ignore hidden '.' (dot) directories when running black - PR: #19 - *Thanks @jreese*

### 2019.2.10

Codename: **Carnival**

*🇧🇷 @cooperlees was in Rio de Janeiro, Brazil for Carnival 3 years ago today 🇧🇷*

- Added ptr `setup.cfg` support for ptr_params - Issue: #1
- Added JSON stats validation to `ci.py` - Issue: #7
- Fixed bug that allowed a step to run by default - Issue: #11

### 2019.2.8.post1/2

- Fix `setup.py` URL to ptr GitHub
- Other various `setup.py` fixes - e.g. Classifiers + License information

### 2019.2.8

Codename: **Snowbird**

*Recent shredding of Snowbird, UT, USA took place 🏂 🇺🇸*

- Initial Release to the world!
