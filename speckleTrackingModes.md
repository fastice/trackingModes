Modifications and critical values flagged with `X` (where X has the code shading).

References for changes: [Doc](https://docs.google.com/document/d/1NIgrXiXkr6X4nU28Ke79xIbugi23mwtm4PZyPvb8Dpo/edit?usp=share_link), [Drive file](https://drive.google.com/file/d/1NC3Yq9tmmI_y2iyhs50FrAB-_0oEELDs/view?usp=share_link)

## ice_sheets

The azimuth range is halved to approximately match the range range.

| Processor | Bandwidth | Level | Win Range | Win Azimuth | Search Range | Search Azimuth |
| --- | --- | --- | --- | --- | --- | --- |
| GPU | 20 | L1 | 32 | 32 | 16 | 16 |
| GPU | 20 | L2 | 64 | 64 | 16 | 16 |
| GPU | 20 | L3 | 128 | 128 | 16 | 16 |
| GPU | 40 | L1 | 32 | 32 | 16 | 16 |
| GPU | 40 | L2 | 64 | 64 | 16 | 16 |
| GPU | 40 | L3 | 128 | 128 | 16 | 16 |
| GPU | 80 | L1 | 64 | 32 | 64 | `32` |
| GPU | 80 | L2 | 96 | 64 | 64 | `32` |
| GPU | 80 | L3 | 196 | 128 | 32 | `16` |

| Processor | Bandwidth | L1 Win Range | L1 Win Azimuth | L1 Search Range | L1 Search Azimuth | L2 Win Range | L2 Win Azimuth | L2 Search Range | L2 Search Azimuth | L3 Win Range | L3 Win Azimuth | L3 Search Range | L3 Search Azimuth |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| GPU | 20 | 32 | 32 | 16 | 16 | 64 | 64 | 16 | 16 | 128 | 128 | 16 | 16 |
| GPU | 40 | 32 | 32 | 16 | 16 | 64 | 64 | 16 | 16 | 128 | 128 | 16 | 16 |
| GPU | 80 | 64 | 32 | 64 | `32` | 96 | 64 | 64 | `32` | 196 | 128 | 32 | `16` |

## ice_sheet_very_fast

| Processor | Bandwidth | Level | Win Range | Win Azimuth | Search Range | Search Azimuth |
| --- | --- | --- | --- | --- | --- | --- |
| GPU | 20 | L1 | 32 | 32 | 16 | 16 |
| GPU | 20 | L2 | 64 | 64 | 16 | 16 |
| GPU | 20 | L3 | 128 | 128 | 16 | 16 |
| GPU | 40 | L1 | 32 | 32 | 16 | 16 |
| GPU | 40 | L2 | 64 | 64 | 16 | 16 |
| GPU | 40 | L3 | 128 | 128 | 16 | 16 |
| GPU | 80 | L1 | 64 | 32 | `178` | `88` |
| GPU | 80 | L2 | 96 | 64 | `178` | `88` |
| GPU | 80 | L3 | 196 | 128 | 32 | `16` |

| Processor | Bandwidth | L1 Win Range | L1 Win Azimuth | L1 Search Range | L1 Search Azimuth | L2 Win Range | L2 Win Azimuth | L2 Search Range | L2 Search Azimuth | L3 Win Range | L3 Win Azimuth | L3 Search Range | L3 Search Azimuth |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| GPU | 20 | 32 | 32 | 16 | 16 | 64 | 64 | 16 | 16 | 128 | 128 | 16 | 16 |
| GPU | 40 | 32 | 32 | 16 | 16 | 64 | 64 | 16 | 16 | 128 | 128 | 16 | 16 |
| GPU | 80 | 64 | 32 | `178` | `88` | 96 | 64 | `178` | `88` | 196 | 128 | 32 | `16` |

## ice_sheet_fast

| Processor | Bandwidth | Level | Win Range | Win Azimuth | Search Range | Search Azimuth |
| --- | --- | --- | --- | --- | --- | --- |
| GPU | 20 | L1 | 32 | 32 | 16 | 16 |
| GPU | 20 | L2 | 64 | 64 | 16 | 16 |
| GPU | 20 | L3 | 128 | 128 | 16 | 16 |
| GPU | 40 | L1 | 32 | 32 | `32` | `32` |
| GPU | 40 | L2 | 64 | 64 | `32` | `32` |
| GPU | 40 | L3 | 128 | 128 | 16 | 16 |
| GPU | 80 | L1 | 64 | 32 | 64 | `32` |
| GPU | 80 | L2 | 96 | 64 | 64 | `32` |
| GPU | 80 | L3 | 196 | 128 | 32 | `16` |

| Processor | Bandwidth | L1 Win Range | L1 Win Azimuth | L1 Search Range | L1 Search Azimuth | L2 Win Range | L2 Win Azimuth | L2 Search Range | L2 Search Azimuth | L3 Win Range | L3 Win Azimuth | L3 Search Range | L3 Search Azimuth |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| GPU | 20 | 32 | 32 | 16 | 16 | 64 | 64 | 16 | 16 | 128 | 128 | 16 | 16 |
| GPU | 40 | 32 | 32 | `32` | `32` | 64 | 64 | `32` | `32` | 128 | 128 | 16 | 16 |
| GPU | 80 | 64 | 32 | 64 | `32` | 96 | 64 | 64 | `32` | 196 | 128 | 32 | `16` |
