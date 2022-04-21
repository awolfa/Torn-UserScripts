## TORN TIME

Formatts the Time in LARGE RED for EST for blind ass ppl like me

[Direct Link](https://github.com/awolfa/Torn-UserScripts/raw/main/Torn%20Time/Add%20Time.user.js)

added the following from Ed

4/21/2022

const format = (date, tz) => date.toLocaleTimeString('en-US', {hourCycle: 'h23', timeZone: tz});
 toLocalTimeString() takes as a second parameter, an 'options' object

Here's a more full options object:
 const options = { timeZone: 'Europe/Moscow', hourCycle: 'h23', year: "numeric", month: "2-digit", day: "2-digit", hour: "2-digit", minute: "2-digit", second: "2-digit" }
 Just need to add the hourCylce in your case.
