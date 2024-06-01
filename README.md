testing out MLMD versions of 1.15.0

# Unable to install using pip and Python 3.11

Example screenshot

![](./Screenshot%20from%202024-06-01%2022-14-52.png)

Example output

```
$ python --version
Python 3.11.9

$ pip install "ml-metadata==0.15.0" -vv
...
  Skipping link: none of the wheel's tags (cp310-cp310-macosx_12_0_x86_64) are compatible (run pip debug --verbose to show compatible tags): https://files.pythonhosted.org/packages/55/5f/17fc4983b443ecaabf7844d33b93137c588f763faed9ba3fa79a0e9e654a/ml_metadata-1.14.0-cp310-cp310-macosx_12_0_x86_64.whl (from https://pypi.org/simple/ml-metadata/) (requires-python:>=3.8,<4)
  Skipping link: none of the wheel's tags (cp310-cp310-manylinux2014_x86_64, cp310-cp310-manylinux_2_17_x86_64) are compatible (run pip debug --verbose to show compatible tags): https://files.pythonhosted.org/packages/56/96/f53d06502ddea0b71992a423bdebce59c666f9dfb50bf380822e168751ca/ml_metadata-1.14.0-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (from https://pypi.org/simple/ml-metadata/) (requires-python:>=3.8,<4)
  Skipping link: none of the wheel's tags (cp310-cp310-win_amd64) are compatible (run pip debug --verbose to show compatible tags): https://files.pythonhosted.org/packages/e9/f9/b1dec7dad8994a50339abad9428b6244cdaa44fd3942ffab68612ca8229f/ml_metadata-1.14.0-cp310-cp310-win_amd64.whl (from https://pypi.org/simple/ml-metadata/) (requires-python:>=3.8,<4)
  Skipping link: none of the wheel's tags (cp38-cp38-macosx_12_0_x86_64) are compatible (run pip debug --verbose to show compatible tags): https://files.pythonhosted.org/packages/2f/22/1fecf967ea169c9ff9e1941eb8d44e14893d5a9c7584ba7ec74cd5d7988d/ml_metadata-1.14.0-cp38-cp38-macosx_12_0_x86_64.whl (from https://pypi.org/simple/ml-metadata/) (requires-python:>=3.8,<4)
  Skipping link: none of the wheel's tags (cp38-cp38-manylinux2014_x86_64, cp38-cp38-manylinux_2_17_x86_64) are compatible (run pip debug --verbose to show compatible tags): https://files.pythonhosted.org/packages/e1/59/5b44a61cfdd52f52a0ac9402b3fbd08fe23cfb8d7a4c84a44dd7002edc3a/ml_metadata-1.14.0-cp38-cp38-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (from https://pypi.org/simple/ml-metadata/) (requires-python:>=3.8,<4)
  Skipping link: none of the wheel's tags (cp38-cp38-win_amd64) are compatible (run pip debug --verbose to show compatible tags): https://files.pythonhosted.org/packages/45/09/9a98b6cc3fca5621aa304a6ae693d5c37ae921e6012a9c4fffc139a6dc08/ml_metadata-1.14.0-cp38-cp38-win_amd64.whl (from https://pypi.org/simple/ml-metadata/) (requires-python:>=3.8,<4)
  Skipping link: none of the wheel's tags (cp39-cp39-macosx_12_0_x86_64) are compatible (run pip debug --verbose to show compatible tags): https://files.pythonhosted.org/packages/db/39/a2c0dd0857515c100d827f6b29854ddaf61dba6ded19ea5fe9818c3e4d26/ml_metadata-1.14.0-cp39-cp39-macosx_12_0_x86_64.whl (from https://pypi.org/simple/ml-metadata/) (requires-python:>=3.8,<4)
  Skipping link: none of the wheel's tags (cp39-cp39-manylinux2014_x86_64, cp39-cp39-manylinux_2_17_x86_64) are compatible (run pip debug --verbose to show compatible tags): https://files.pythonhosted.org/packages/31/7b/705e979c8a26876d2a46bf5f54bf90707b403f7ec439df666ec0f4e53d12/ml_metadata-1.14.0-cp39-cp39-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (from https://pypi.org/simple/ml-metadata/) (requires-python:>=3.8,<4)
  Skipping link: none of the wheel's tags (cp39-cp39-win_amd64) are compatible (run pip debug --verbose to show compatible tags): https://files.pythonhosted.org/packages/ae/05/3a62e5c6103e61484cd538ecd51e8e49d71030ea9a4b7fee2f928b676ac7/ml_metadata-1.14.0-cp39-cp39-win_amd64.whl (from https://pypi.org/simple/ml-metadata/) (requires-python:>=3.8,<4)
  Skipping link: none of the wheel's tags (cp310-cp310-macosx_12_0_x86_64) are compatible (run pip debug --verbose to show compatible tags): https://files.pythonhosted.org/packages/b6/bc/d098c49859de8de390d03fa88ecd0ad548075c7feecb34db7148440bc058/ml_metadata-1.15.0-cp310-cp310-macosx_12_0_x86_64.whl (from https://pypi.org/simple/ml-metadata/) (requires-python:<4,>=3.9)
  Skipping link: none of the wheel's tags (cp310-cp310-manylinux2014_x86_64, cp310-cp310-manylinux_2_17_x86_64) are compatible (run pip debug --verbose to show compatible tags): https://files.pythonhosted.org/packages/93/5f/01eddd4e52605474972040a8cc8124b7b588e20040f853bfe196628005e1/ml_metadata-1.15.0-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (from https://pypi.org/simple/ml-metadata/) (requires-python:<4,>=3.9)
  Skipping link: none of the wheel's tags (cp39-cp39-macosx_12_0_x86_64) are compatible (run pip debug --verbose to show compatible tags): https://files.pythonhosted.org/packages/d4/86/f64e6e3f3df25c8783657c7a4d369b11f1e332bf7fcc87632a4a00c68367/ml_metadata-1.15.0-cp39-cp39-macosx_12_0_x86_64.whl (from https://pypi.org/simple/ml-metadata/) (requires-python:<4,>=3.9)
  Skipping link: none of the wheel's tags (cp39-cp39-manylinux2014_x86_64, cp39-cp39-manylinux_2_17_x86_64) are compatible (run pip debug --verbose to show compatible tags): https://files.pythonhosted.org/packages/b8/5a/238b52803eaccbd2757e8b8a6303ea7048c3079c9475c4ea33607b281070/ml_metadata-1.15.0-cp39-cp39-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (from https://pypi.org/simple/ml-metadata/) (requires-python:<4,>=3.9)
Skipping link: not a file: https://pypi.org/simple/ml-metadata/
Given no hashes to check 0 links for project 'ml-metadata': discarding no candidates
ERROR: Could not find a version that satisfies the requirement ml-metadata==0.15.0 (from versions: 0.12.0.dev0, 0.13.0.dev0, 0.13.1.dev0)
ERROR: No matching distribution found for ml-metadata==0.15.0
Exception information:
Traceback (most recent call last):
  File "/home/tarilabs/git/demo20240601-mlmdversions/venv/lib/python3.11/site-packages/pip/_vendor/resolvelib/resolvers.py", line 397, in resolve
    self._add_to_criteria(self.state.criteria, r, parent=None)
  File "/home/tarilabs/git/demo20240601-mlmdversions/venv/lib/python3.11/site-packages/pip/_vendor/resolvelib/resolvers.py", line 174, in _add_to_criteria
    raise RequirementsConflicted(criterion)
pip._vendor.resolvelib.resolvers.RequirementsConflicted: Requirements conflict: SpecifierRequirement('ml-metadata==0.15.0')

During handling of the above exception, another exception occurred:

Traceback (most recent call last):
  File "/home/tarilabs/git/demo20240601-mlmdversions/venv/lib/python3.11/site-packages/pip/_internal/resolution/resolvelib/resolver.py", line 95, in resolve
    result = self._result = resolver.resolve(
                            ^^^^^^^^^^^^^^^^^
  File "/home/tarilabs/git/demo20240601-mlmdversions/venv/lib/python3.11/site-packages/pip/_vendor/resolvelib/resolvers.py", line 546, in resolve
    state = resolution.resolve(requirements, max_rounds=max_rounds)
            ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "/home/tarilabs/git/demo20240601-mlmdversions/venv/lib/python3.11/site-packages/pip/_vendor/resolvelib/resolvers.py", line 399, in resolve
    raise ResolutionImpossible(e.criterion.information)
pip._vendor.resolvelib.resolvers.ResolutionImpossible: [RequirementInformation(requirement=SpecifierRequirement('ml-metadata==0.15.0'), parent=None)]

The above exception was the direct cause of the following exception:

Traceback (most recent call last):
  File "/home/tarilabs/git/demo20240601-mlmdversions/venv/lib/python3.11/site-packages/pip/_internal/cli/base_command.py", line 180, in exc_logging_wrapper
    status = run_func(*args)
             ^^^^^^^^^^^^^^^
  File "/home/tarilabs/git/demo20240601-mlmdversions/venv/lib/python3.11/site-packages/pip/_internal/cli/req_command.py", line 245, in wrapper
    return func(self, options, args)
           ^^^^^^^^^^^^^^^^^^^^^^^^^
  File "/home/tarilabs/git/demo20240601-mlmdversions/venv/lib/python3.11/site-packages/pip/_internal/commands/install.py", line 377, in run
    requirement_set = resolver.resolve(
                      ^^^^^^^^^^^^^^^^^
  File "/home/tarilabs/git/demo20240601-mlmdversions/venv/lib/python3.11/site-packages/pip/_internal/resolution/resolvelib/resolver.py", line 104, in resolve
    raise error from e
pip._internal.exceptions.DistributionNotFound: No matching distribution found for ml-metadata==0.15.0
Remote version of pip: 24.0
Local version of pip:  24.0
Was pip installed by pip? True
Removed build tracker: '/tmp/pip-build-tracker-m0wgcq63'
```

# Unable to install using pip and Python 3.11

Example screenshot

![](./Screenshot%20from%202024-06-01%2022-13-34.png)

Example output

```
poetry install -v
Using virtualenv: /home/tarilabs/.cache/pypoetry/virtualenvs/demo20240601-mlmdversions-bB4weZxo-py3.11
Installing dependencies from lock file

Finding the necessary packages for the current system

Package operations: 6 installs, 0 updates, 0 removals

  • Installing absl-py (1.4.0)
  • Installing attrs (23.2.0)
  • Installing grpcio (1.64.0)
  • Installing protobuf (4.25.3)
  • Installing six (1.16.0)
  • Installing ml-metadata (1.15.0): Failed

  RuntimeError

  Unable to find installation candidates for ml-metadata (1.15.0)

  at /usr/lib/python3.12/site-packages/poetry/installation/chooser.py:73 in choose_for
       69│ 
       70│             links.append(link)
       71│ 
       72│         if not links:
    →  73│             raise RuntimeError(f"Unable to find installation candidates for {package}")
       74│ 
       75│         # Get the best link
       76│         chosen = max(links, key=lambda link: self._sort_key(package, link))
       77│ 

Cannot install ml-metadata.

```