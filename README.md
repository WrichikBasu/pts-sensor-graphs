# pts-sensor-graphs
A python function to plot sensor data generated by Phoronix Test Suite during a stress run.

## Installation

Simply clone the repository.

```bash
git clone git@github.com:WrichikBasu/pts-sensor-graphs.git
cd pts-sensor-graphs/
```

Make sure you have the required packages installed via `pip`:

```bash
pip install --upgrade xmltodict numpy matplotlib seaborn
```

## Usage

```python
>>> from phoronix_res_plot import plot_phoronix_result
>>> plot_phoronix_result("<TEST_RESULT_NAME>", ('cpu.temp', 'cpu.usage', 'gpu.usage', 'gpu.temp'))
```

Make sure to replace the `<TEST_RESULT_NAME>` with the result name you had set.

See the documentation for more information.

```python
>>> help(plot_phoronix_result)
```
