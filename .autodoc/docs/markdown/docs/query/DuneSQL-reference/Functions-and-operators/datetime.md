[View code on GitHub](https://dune.com/docs/query/DuneSQL-reference/Functions-and-operators/datetime.md)

The app technical guide covers various date and time functions and operators that can be used to manipulate date and time data types. It is divided into several sections, each focusing on a specific aspect of date and time manipulation.

1. **Date and time operators**: This section provides a table of various arithmetic operators that can be used to perform operations on date and time data types, such as addition and subtraction of intervals.

2. **Time zone conversion**: This section explains how to use the `AT TIME ZONE` operator to set the time zone of a timestamp.

3. **Date and time functions**: This section covers various functions that can be used to extract and manipulate date and time values, such as `current_date`, `current_time`, `current_timestamp`, and `current_timezone`.

4. **Truncation function**: This section explains the `date_trunc` function, which can be used to truncate a timestamp to a specified unit, such as day, month, or year.

5. **Interval functions**: This section covers functions that can be used to add or subtract intervals of time, such as `date_add` and `date_diff`.

6. **Duration function**: This section explains the `parse_duration` function, which can be used to parse a string representing a duration into an interval.

7. **Human-readable seconds**: This section covers the `human_readable_seconds` function, which can be used to format a double value of seconds into a human-readable string.

8. **MySQL date functions**: This section covers functions that use a format string compatible with MySQL's `date_parse` and `str_to_date` functions, such as `date_format` and `date_parse`.

9. **Java date functions**: This section covers functions that use a format string compatible with JodaTime's DateTimeFormat pattern format, such as `format_datetime` and `parse_datetime`.

10. **Extraction function**: This section explains the `extract` function, which can be used to extract various fields from date and time values, such as year, month, and day.

11. **Convenience extraction functions**: This section covers various convenience functions that can be used to extract specific fields from date and time values, such as `day`, `month`, and `year`.
## Questions: 
 1. **Question:** How can I perform time zone conversion using this app technical guide?
   **Answer:** You can use the `AT TIME ZONE` operator to set the time zone of a timestamp. For example, `SELECT timestamp '2012-10-31 01:00 UTC' AT TIME ZONE 'America/Los_Angeles';` will convert the given timestamp to the specified time zone.

2. **Question:** What are the supported units for the `date_trunc` function?
   **Answer:** The `date_trunc` function supports the following units: `second`, `minute`, `hour`, `day`, `week`, `month`, `quarter`, and `year`.

3. **Question:** How can I parse a date string in ISO 8601 format using this app technical guide?
   **Answer:** You can use the `from_iso8601_date()` function to parse an ISO 8601 formatted date string into a `date`. For example, `SELECT from_iso8601_date('2020-05-11');` will parse the given date string and return the date `2020-05-11`.