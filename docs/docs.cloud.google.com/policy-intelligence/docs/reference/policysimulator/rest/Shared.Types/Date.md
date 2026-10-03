---
name: documents/docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/Shared.Types/Date
uri: https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/Shared.Types/Date
title: Date
description: A suite of tools to help you understand and manage your policies to proactively improve your security configuration.
data_source: docs.cloud.google.com
---

- [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/Shared.Types/Date#SCHEMA_REPRESENTATION)

Represents a whole or partial calendar date, such as a birthday. The time of day and time zone are either specified elsewhere or are insignificant. The date is relative to the Gregorian Calendar. This can represent one of the following:

- A full date, with non-zero year, month, and day values.
- A month and day, with a zero year (for example, an anniversary).
- A year on its own, with a zero month and a zero day.
- A year and month, with a zero day (for example, a credit card expiration date).

Related types:

- `google.type.TimeOfDay`
- `google.type.DateTime`
- [`google.protobuf.Timestamp`](https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp)

**JSON representation**

```
{
  "year": integer,
  "month": integer,
  "day": integer
}
```

| Fields  |                                                                                                                                                                        |
|---------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `year`  | `integer` Year of the date. Must be from 1 to 9999, or 0 to specify a date without a year.                                                                             |
| `month` | `integer` Month of a year. Must be from 1 to 12, or 0 to specify a year without a month and day.                                                                       |
| `day`   | `integer` Day of a month. Must be from 1 to 31 and valid for the year and month, or 0 to specify a year by itself or a year and month where the day isn't significant. |
