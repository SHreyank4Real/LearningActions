# LearningActions
this repo is used to learn GitHub actions
test-1

- name: Setup Python
  uses: actions/setup-python@v2.2.2
  with:
    # Version range or exact version of a Python version to use, using SemVer's version range syntax.
    python-version: # optional, default is 3.x
    # The target architecture (x86, x64) of the Python interpreter.
    architecture: # optional
    # Used to pull python distributions from actions/python-versions. Since there's a default, this is typically not supplied by the user.
    token: # optional, default is ${{ github.token }}
