# simple-editor
simple editor with web workers
SPA that evaluates user-entered JavaScript code as the user types and displays the results.
The screen will be composed of four parts:
Top part – the user will enter his “input”
Second part – the user will write his manipulation function
Third part – this is where errors will be displayed to the user
Fourth part – this is where the results will be displayed to the user. It’s ok to simply display JSON.stringify(output).
In the second part, the user only enters the body of the method (the input is always sample and output, where sample is the text from the top part and output is an empty object ({}).
Notes:
Ace editor for the user code input. 
JavaScript styling- the code should be evaluated every time the code or sample changes
the SPA should limit the execution time of the code. If for example the input is while (true) {}- the code should stop after no more than a few seconds and the error should be “Code never completes” (hint – use web workers)
the code should run in Chrome latest version. There’s no need to support older versions or other browsers
