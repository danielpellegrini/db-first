# Used car dealer database


| Field               | Type        | Attribute   |         |                       |
|---------------------|-------------|-------------|---------|-----------------------|
| car_id              | INT         | PRIMARY KEY |         |                       |
| brand               | VARCHAR(20) | NOT NULL    |         |                       |
| model               | VARCHAR(70) | NOT NULL    |         |                       |
| kilometers          | MEDIUMINT   | NOT NULL    |         |                       |
| engine_displacement | SMALLINT    | NOT NULL    |         |                       |
| horse_power         | SMALLINT    | NULL        |         |                       |
| shift               | VARCHAR(3)  | NOT NULL    | DEFAULT | MT                    |
| year                | YEAR        | NOT NULL    |         |                       |
| price               | FLOAT(9,2)  | NOT NULL    |         |                       |
| picture             | TEXT        | NOT NULL    | DEFAULT | PREDEFINED IMAGE PATH |
| warranty            | TINYINT     | NULL        |         |                       |
| vin/chassis_nr      | VARCHAR(17) | NOT NULL    | UNIQUE  |                       |