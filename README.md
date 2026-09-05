# ifm — Python API for FEFLOW

Documentation, tutorials and examples for `ifm`, the Python interface to FEFLOW,
DHI's groundwater modelling system.

**Documentation: https://dhi.github.io/ifm/**

The `ifm` package is not in this repository — it ships with FEFLOW and is
installed by the FEFLOW installer, with the Python API option selected. What
lives here is the source of the documentation site above, plus the tutorials,
examples and model data that go with it.

```python
import ifm

doc = ifm.loadDocument("myModel.fem")
print(doc.getNumberOfNodes())
```

Requires FEFLOW 11.0 and Python 3.11 or newer.

## Layout

- `docs/` — the documentation site published at dhi.github.io/ifm
- `tutorials/` — getting started, data wrangling, plotting, what's new per release
- `examples/` — short, focused snippets
- `extensions/`, `benchmarks/` — longer worked cases
- `data/` — FEFLOW models used by the notebooks

## License

[MIT](LICENSE), covering the documentation, tutorials and example code in this
repository. FEFLOW and the `ifm` package itself are proprietary DHI software and
are not covered by it.
