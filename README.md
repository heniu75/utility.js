# Utility.js


## _.parseDate(str) <= [Date|null]
Parse a string in a valid date pattern on current culture. Returns null if string was not a valid date
- `str` (_String_) - Date to parse

## _.parseNumber(str) <= [Number|null]
Parse a string in a valid number pattern on current culture. Returns null if string was not a valid number
- `str` (_String_) - Number to parse

## _.format(value, fmt) <= String
Format a date, number or string (like `String.Format`) into a string using current culture
- `value` (_Date|Number|String_) - Value to be formated
- `fmt` (_String_) - String format. See: 

## _.culture(culture) : [Object]
Get or set object to define current culture
- `culture` (_Object_) - Culture object definition

## _.dateAdd(datepart, number, date)
Add period into a date. Returns new `Date` object
- `datepart` (_String_) - Definition of period (`y`, `M`, `d`, `H`, `m`, `s`, `f`)
- `number` (_Number_) - Amouth of period
- `date` (_Date_) - Date to be added

## _.dateDiff(datepart, start, end)
Returns interval between two dates
- `datepart` (_String_) - Definition of period (`y`, `M`, `d`, `H`, `m`, `s`, `f`)
- `start` (_Date_) - Inital date
- `end` (_Date_) - Final date
