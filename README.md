# Module 3 Project Folder

**This contains all the work I have done on this Module 3 final

---

## Technologies 
`print("jupyter lab")`
---
*Built using Python 3.7.9 64-bi(On Jupyter Lab)


---

For this assignment, we sorted through historical trade data for Bitcoin on two exchanges: Bitstamp and Coinbase. Our task was to apply the three phases of financial analysis to determine if any arbitrage opportunities exist for Bitcoin. The following Libraries need import and vary from the traditional methods.

## Installation Guide and Examples

```
import pandas as pd
from pathlib import Path
%matplotlib inline
```

*Single line DataFrame and Path 

```
df = pd.read_csv(
    Path('./Resources/df.csv'),
    index_col="Timestamp", 
    parse_dates=True, 
    infer_datetime_format=True
)
```
