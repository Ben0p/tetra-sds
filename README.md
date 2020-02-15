# tetra-sds
Decoding Tetra Terrestrial Trunked Radio Location Data

Based on the ETSI Standard:
https://www.etsi.org/deliver/etsi_ts/100300_100399/1003921801/01.03.01_60/ts_1003921801v010301p.pdf

## Overview
*NOTE: Using dictionaries rather than classes due to personal preference, performance gains and easier to insert into MongoDB.*

Input a hex string, outputs a dictionary with location information. String can be from a database binary blob or directly from a Tetra Air Interface API.

See the location_model.py for dictionary layout.

