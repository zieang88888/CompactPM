# Data

This minimal release does not redistribute raw datasets.

## GridSet-22 source-reference dataset

Source project: PowerMamba  
Original data record: https://doi.org/10.5281/zenodo.14451473  
Source-code repository: https://github.com/alimenati/PowerMamba  
Expected file: `GridSet_no_pred.csv`

The frozen R38 file used for the reported 100-seed validation study has:

- 43,824 rows
- 22 modeled series
- SHA256: `137c13d2b7bf1d1c721597619741f39d2d06e0af29923abebec7ebea8072a10d`
- train rows: 30,676
- validation rows: 4,382
- held-out rows: 8,766

The R38 source-reference protocol loads only the first 80% of rows after
counting the file length. The final 20% is not loaded or evaluated.

Expected modeled columns:

`COAST, EAST, FWEST, NORTH, NCENT, SOUTH, SCENT, WEST, REGDN, REGUP,
RRS, NSPIN, WIND_ACTUAL_SYSTEM_WIDE, SOLAR_ACTUAL_SYSTEM_WIDE,
LZ_AEN, LZ_CPS, LZ_HOUSTON, LZ_LCRA, LZ_NORTH, LZ_RAYBN,
LZ_SOUTH, LZ_WEST`

The dataset remains subject to the source project's terms and provenance.
