# DateFormatConverter
Date Formatter For Java

## Usage Example
```java
new DateFormatConverter().withDate("2019-01-01 10:45:44")
                        .withPatternConvert(DateFormatConverter.PATTERN_DATE_SQL
                        , DateFormatConverter.PATTERN_DATE_SPELL_COMMON
                        , Locale.getDefault())
                        .doConvert()
```
