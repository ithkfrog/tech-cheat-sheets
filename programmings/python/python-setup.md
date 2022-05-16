# Local Python environment setup

Due to `python 2` been removed from Mac OS Monterey there will be not `pip` or `python` command anymore. Instead the default Mac OS python is version 3 `pip3` and `python3` commands.

In order to make background compatible use `pip` command a tool can be used call `pyenv` which help to manage python versions.

## pyenv

1. To install

    ```console
    brew install pyenv
    ```

1. To check current versions

    ```console
    pyenv versions
    ```

    ```console
    ➜  ~ pyenv versions
    system
    * 3.9.11 (set by /Users/andy/.pyenv/version)
    ```

1. List available python versions

    ```console
    pyenv install --list
    ```

    Pick versions from below

    ```console
    Available versions:
    2.1.3
    2.2.3
    ...
    2.7.17
    2.7.18
    3.0.1
    3.1.0
    ...
    3.9.0
    3.9-dev
    ...
    3.9.11
    3.10.3
    3.11.0a6
    3.11-dev
    ```

1. Install particular version

    Example version `3.9.11`

    ```console
    pyenv install 3.9.11
    ```

1. Export shims path

    ```console
    echo 'PATH=$(pyenv root)/shims:$PATH' >> ~/.zshrc
    ```

1. Open new terminal

   Try `pip`

   ```console
    $ pip -V
    pip 22.0.4 from /Users/andy/.pyenv/versions/3.9.11/lib/python3.9/site-packages/pip (python 3.9)
   ```

   ```console
   $ pip3 -V
   pip 22.0.4 from /Users/andy/.pyenv/versions/3.9.11/lib/python3.9/site-packages/pip (python 3.9)
   ```
