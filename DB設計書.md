# データベース設計図

## Foodstuff
|項目名|型|PK|NN|FK|
|-----|--|--|--|--|
|foodstuff_id|bigint(100)|○|○||
|foodstuff_name|varchar(50)||○|
|category|bigint(10)||○|
|flag|int(1)||||
|image_data|varchar(50)||○|
|image_name|varchar(50)||○|

## recipe
|項目名|型|PK|NN|FK|
|-----|--|--|--|--|
|recipe_id|bigint(100)|○|○||
|recipe_name|varchar(50)||○||
|recipe_deta|varchar(50)||○|


## recipe_detail
|項目名|型|PK|NN|FK|
|-----|--|--|--|--|
|recipe_id|bigint(100)|○|○||
|recipe_name|varchar(50)||○||
|recipe_deta|varchar(50)||○|
