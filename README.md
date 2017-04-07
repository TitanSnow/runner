# runner
A cross-platform python subprocess module with accurate timer

## require

* pypiwin32 if on Windows

## usage

```python
from runner import Runner,get_total_time
process=Runner("a.out")
process.run("Hello Runner!")
output=process.get_output()
total_time=get_total_time()
```

## feature

* cross platform
* *accurate user time getter*
