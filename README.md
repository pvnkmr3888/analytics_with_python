# Creating functions in python - analytics_with_python (analytics of open source datasets)

This repository contains a simple code with python 'function' to calculate the distribution of channeltype from the top 1000 videos on youtube sorted on number of subscribers.
Going further the extracted data is loaded into a csv file.

Getting Started
The dataset is sorted based on number of subscribers



The function below calls out the number of records in channel type under the top 1000 records
def channeltype(x):
    df3=df2['channeltype'].value_counts()[x]
    print(df3)
    

 to_csv command output is used to export the transformed data to a new csv file ‘Top1000_YT.csv’

## Built With

* [python](https://www.python.org/) 

## Authors

* **Pavan Kumar ** - *Analytics with python* - [pvnkmr3888](https://github.com/pvnkmr3888)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Data Analytics Dept- DURHAM COLLEGE-Oshawa,Ontario
