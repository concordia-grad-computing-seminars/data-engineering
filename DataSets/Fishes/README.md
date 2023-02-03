# Fish data-set

## Sources
* original source: https://jse.amstat.org/jse_data_archive.htm
* cleaned data set: https://www.kaggle.com/datasets/aungpyaeap/fish-market
* data dictionary: https://jse.amstat.org/datasets/fishcatch.txt

## Explanations of data fields

| Field       | Description                                                |
| ----------- | ---------------------------------------------------------- |
| Species     | Species of the fish                                        |
| Weight      | Weight of the fish (in grams)                              |
| Length1     | Length from the nose to the beginning of the tail (in cm)  |
| Length2     | Length from the nose to the notch of the tail (in cm)      |
| Length3     | Length from the nose to the end of the tail (in cm)        |
| Height      | Maximal height as % of Length3                             |
| Width       | Maximal width as % of Length3                              |

```
          ___/////___                  _
         /           \    ___          |
       /\             \_ /  /          H
     <   )            __)  \           |
       \/_\\_________/   \__\          _

     |------- L1 -------|
     |------- L2 ----------|
     |------- L3 ------------|
```
