# Recyclable-coffeecup-classification

### Model flow
![conv_image_80](https://user-images.githubusercontent.com/76892271/200021532-f5956ae0-0060-48be-a561-a8222cd02dee.png)


## Quick Start
### Data preparation
In our experiments, we use custom dataset. The datasets should be put in data, respecting the following tree directory:
```
${ROOT}
|-- data
`-- |-- coffeecup
    `-- |-- train
        |   |-- plastic
        |   |-- paper
        |   |-- paper_in
        |   |-- waste
        `-- valid
            |-- plastic
            |-- paper
            |-- paper_in
            |-- waste
        `-- test
            |-- plastic
            |-- paper
            |-- paper_in
            |-- waste
```
