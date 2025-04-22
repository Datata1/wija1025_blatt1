required python version: 3.12.9

open terminal and go to this projects root:

1. 
```
uv sync
```

2. 
```
uv run ipython kernel install --user --env VIRTUAL_ENV $(pwd)/.venv --name=blatt-1
```

3. 
```
uv run --with jupyter jupyter lab
```

or 

```
code .
```

4. select `blatt-1` as jupyter kernel