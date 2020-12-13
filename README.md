# Basis reduction (LLL and Gauss)

Python3 implementation of LLL and Gaussian method.

## Installation
```bash
python3 -m pip install basis_reduction
```

```python
import basis_reduction.basis_reduction as basis_reduction
import basis_reduction.basis_reduction as br

reduced_basis_lll = basis_reduction.lll_reduction([
  [1, 1, 1],
  [-1, 0, 2],
  [3, 5, 6],
], 0.75)

print(reduced_basis_lll)
# [[0, 1, 0], [1, 0, 1], [-1, 0, 2]]
```

## Author
Artur Buriev(@arturburiev)

## License
MIT

## Reference
https://wiki2.org/ru/%D0%90%D0%BB%D0%B3%D0%BE%D1%80%D0%B8%D1%82%D0%BC_%D0%9B%D0%B5%D0%BD%D1%81%D1%82%D1%80%D1%8B_%E2%80%94_%D0%9B%D0%B5%D0%BD%D1%81%D1%82%D1%80%D1%8B_%E2%80%94_%D0%9B%D0%BE%D0%B2%D0%B0%D1%81%D0%B0
