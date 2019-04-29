# focusout-issue
1. On initial page load you see Success label
2. Open developer tools
3. Press cmd + R
4. You’ll either see Success or Fail (usually it’s a Fail). Press cmd + R.
5. You’ll stop on a debugger statement in js code. Hit Continue script execution.
6. The result will be success. Every time you press cmd + R after that will lead you to Success in case you continue script execution every time in-between.
BUT if you press cmd + R during the stop on the debugger statement you’ll definitely get a Fail.
7. Click on the refresh button in the address panel OR click the address field and hit enter
8. You’ll stop on the debugger and get a Success, which gets you to the situation in step #6.
