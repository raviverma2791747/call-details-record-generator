# call-details-record-generator

## Maven Project

### Dependencies

- [junit](https://mvnrepository.com/artifact/junit/junit)
- [joda-time](https://mvnrepository.com/artifact/joda-time/joda-time)
- [datafactory](https://mvnrepository.com/artifact/org.fluttercode.datafactory/datafactory)

### Build

```cmd
mvn package
```

### Run

```cmd
java -jar  "target\generator-1.0-SNAPSHOT-jar-with-dependencies.jar"
```

### Output

Format ID, CALLING_NUM, CALLED NUMBER, START TIME, END TIME, CALL TYPE, CHARGE, CALL RESULT

```cmd
8908dfca-06b7-4e29-ac4f-59122abdde14|9917618284|5084342972|2021-12-25T11:31:53.819+05:30|2021-12-25T11:31:53.819+05:30|SMS|0.47806346|ANSWERED
834132fe-dfe0-4a2c-be0d-1c07c4a5778b|8131166797|3470914600|2022-01-05T15:44:44.983+05:30|2022-01-05T15:44:44.983+05:30|SMS|0.67377365|ANSWERED
49852bee-da6a-4c20-84d5-04ec8aa55c6f|9149565512|3539212588|2022-01-27T08:32:11.058+05:30|2022-01-27T08:34:32.033+05:30|VOICE|0.07600087|ANSWERED
79c083e6-c908-4068-aa9c-93eda8bca4da|3917407842|3976557336|2021-12-22T13:39:41.548+05:30|2021-12-22T13:39:41.548+05:30|SMS|0.4627056|ANSWERED
1c0d7b1c-12e0-4d62-b5a2-b43f4f462f39|1190111696|4794533137|2022-01-16T18:37:35.679+05:30|2022-01-16T18:37:35.679+05:30|SMS|0.6598766|ANSWERED
06f32c91-d377-45ff-bd47-db9f4537df7f|4947005879|5596524704|2022-02-01T09:35:49.745+05:30|2022-02-01T09:38:27.464+05:30|VOICE|0.88263625|ANSWERED
```
