This Repository contains the original as well as derived data for the paper:

Encke, Jörg & Dietz Mathias (2020). The influence of envelope
fluctuations on across-frequency integration in interaural time
difference perception. The Journal of the Acoustical Society of
America. (In review)

The repository contains two files both formated as comma seperated
values. The first line of each file contains the column names with
each following line containg one dataset.

# raw_data.csv
This file contains the raw data of the experiment.

| Column Name | Datatype    | Description                       |
|-------------|---------|-----------------------------------|
| subject     | integer | The subject ID (1-6)              |
| bw          | float   | The stimulus bandwidth in Hz      |
| p_right     | float   | The fraction of "right" responses |
| exp         | string  | Name of the experiment            |
| exp_group   | string  | Group of the experiment           |

# changeover_data.csv
This file contains the changeover points that where derived from the
raw data.

| Column Name  | Datatype | Description                 |
|--------------|----------|-----------------------------|
| subject      | integer  | The subject ID (1-6)        |
| exp          | string   | Name of the experiment      |
| exp_group    | string   | Group of the experiment     |
| change_point | float    | The change over point in Hz |
