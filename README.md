# This is Manim simple project example

[Manim docs](https://docs.manim.community/en/stable/index.html#)
```shell
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
uv init manimations
uv add manim
$env:Path = "C:\Users\inimatic\.local\bin;$env:Path"
./.venv/scripts/activate.bat
./.venv/scripts/pip install importlib_metadata
uv run manim checkhealth 
uv run manimce -pql main.py CreateCircle
```