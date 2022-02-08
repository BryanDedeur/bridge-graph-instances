# Steel Truss Bridge Problem Instances
 
This is a set of 20 undirected graphs all representing realistic truss bridge structures. Each graph is stored in a .csv adjacency matrix format. Additionally included is .obj files for 2D vertex coordinates.


| Id | Problem Instance | Num Edges | Num Vertices |
|----|------------------|-----------|--------------|
| 1  | howe1            | 37        | 18           |
| 2  | howe2            | 63        | 28           |
| 3  | howe3            | 89        | 38           |
| 4  | howe4            | 115       | 48           |
| 5  | howe5            | 141       | 58           |
| 6  | ktruss1          | 45        | 22           |
| 7  | ktruss2          | 79        | 36           |
| 8  | ktruss3          | 113       | 50           |
| 9  | ktruss4          | 147       | 64           |
| 10 | ktruss5          | 181       | 78           |
| 11 | pratt1           | 37        | 18           |
| 12 | pratt2           | 63        | 28           |
| 13 | pratt3           | 89        | 38           |
| 14 | pratt4           | 115       | 48           |
| 15 | pratt5           | 141       | 58           |
| 16 | warren1          | 59        | 26           |
| 17 | warren2          | 85        | 36           |
| 18 | warren3          | 111       | 46           |
| 19 | warren4          | 137       | 56           |
| 20 | warren5          | 163       | 66           |

To add to your project I recommend [git submodule](https://git-scm.com/book/en/v2/Git-Tools-Submodules).

## Reading .csv files
|      | v_0      | v_1      | v_2      | v_3      | v_4 | v_5 | v_6 | v_7 | v_8      | v_9      | v_10     | v_11     | v_12     | v_13     | v_14     | v_15     | v_16     | v_17     |
|------|----------|----------|----------|----------|-----|-----|-----|-----|----------|----------|----------|----------|----------|----------|----------|----------|----------|----------|
| v_0  | 0        | 0        | 6.5      | 0        | 0   | 4   | 4   | 0   | 0        | 7.632169 | 7.632169 | 0        | 0        | 0        | 0        | 0        | 0        | 0        |
| v_1  | 0        | 0        | 0        | 6.5      | 4   | 0   | 0   | 4   | 7.632169 | 0        | 0        | 7.632169 | 0        | 0        | 0        | 0        | 0        | 0        |
| v_2  | 6.5      | 0        | 0        | 6.4384   | 0   | 0   | 0   | 0   | 0        | 4        | 4        | 0        | 3.789888 | 3.789888 | 0        | 0        | 0        | 0        |
| v_3  | 0        | 6.5      | 6.4384   | 0        | 0   | 0   | 0   | 0   | 4        | 0        | 0        | 4        | 3.789888 | 3.789888 | 0        | 0        | 0        | 0        |
| v_4  | 0        | 4        | 0        | 0        | 0   | 0   | 0   | 0   | 6.5      | 0        | 0        | 0        | 0        | 0        | 4        | 0        | 0        | 0        |
| v_5  | 4        | 0        | 0        | 0        | 0   | 0   | 0   | 0   | 0        | 6.5      | 0        | 0        | 0        | 0        | 0        | 4        | 0        | 0        |
| v_6  | 4        | 0        | 0        | 0        | 0   | 0   | 0   | 0   | 0        | 0        | 6.5      | 0        | 0        | 0        | 0        | 0        | 4        | 0        |
| v_7  | 0        | 4        | 0        | 0        | 0   | 0   | 0   | 0   | 0        | 0        | 0        | 6.5      | 0        | 0        | 0        | 0        | 0        | 4        |
| v_8  | 0        | 7.632169 | 0        | 4        | 6.5 | 0   | 0   | 0   | 0        | 0        | 6.4384   | 0        | 3.789888 | 0        | 7.632169 | 0        | 0        | 0        |
| v_9  | 7.632169 | 0        | 4        | 0        | 0   | 6.5 | 0   | 0   | 0        | 0        | 0        | 6.4384   | 0        | 3.789888 | 0        | 7.632169 | 0        | 0        |
| v_10 | 7.632169 | 0        | 4        | 0        | 0   | 0   | 6.5 | 0   | 6.4384   | 0        | 0        | 0        | 3.789888 | 0        | 0        | 0        | 7.632169 | 0        |
| v_11 | 0        | 7.632169 | 0        | 4        | 0   | 0   | 0   | 6.5 | 0        | 6.4384   | 0        | 0        | 0        | 3.789888 | 0        | 0        | 0        | 7.632169 |
| v_12 | 0        | 0        | 3.789888 | 3.789888 | 0   | 0   | 0   | 0   | 3.789888 | 0        | 3.789888 | 0        | 0        | 0        | 0        | 0        | 0        | 0        |
| v_13 | 0        | 0        | 3.789888 | 3.789888 | 0   | 0   | 0   | 0   | 0        | 3.789888 | 0        | 3.789888 | 0        | 0        | 0        | 0        | 0        | 0        |
| v_14 | 0        | 0        | 0        | 0        | 4   | 0   | 0   | 0   | 7.632169 | 0        | 0        | 0        | 0        | 0        | 0        | 0        | 0        | 0        |
| v_15 | 0        | 0        | 0        | 0        | 0   | 4   | 0   | 0   | 0        | 7.632169 | 0        | 0        | 0        | 0        | 0        | 0        | 0        | 0        |
| v_16 | 0        | 0        | 0        | 0        | 0   | 0   | 4   | 0   | 0        | 0        | 7.632169 | 0        | 0        | 0        | 0        | 0        | 0        | 0        |
| v_17 | 0        | 0        | 0        | 0        | 0   | 0   | 0   | 4   | 0        | 0        | 0        | 7.632169 | 0        | 0        | 0        | 0        | 0        | 0        |

## Reading .obj files
> coming soon
