* What was the bug? - `num1` and `num2` get interpreted as strings and so doing the `+` operation simply concatenates the string.
* How would you fix it? Include a screenshot of your fix. - Replace `num1` with `(num1-0)` and `num2` with `(num2-0)` in the calculation of `result` (see bug_fix.png)

## Part 2
* What is the name of the new json file?  
`citylots.json`
* Which file initiated the download of the new file?  
  `part2.js`
* What is its file size?  
  `11.7MB`
* How long did it take to download?  
  `1.28s`
* What was your User-Agent for the browser that made the request?
  `Chrome/87.0.4280.141`
* In the response, what type of server did it come from?  
  `Apache`
* When was the file last modified?  
  `Tue, 26 Jan 2021 22:14:13 GMT`
* What was the Content-Type of the file  
  `application/json`
* Which method inside the initiating file made the request?  
  `fetchData`