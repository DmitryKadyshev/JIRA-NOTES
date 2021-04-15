ADD originalEstimate {issue.originalEstimate} to start date {issue.cf10203} without SATURDAY & SUNDAY
```
dateToString(addTimeSkippingWeekends({issue.cf10203}, {issue.originalEstimate} * (60 * 60 * 40 ), LOCAL,{SATURDAY}, {SUNDAY}), LOCAL, SERVER_LANG)
```