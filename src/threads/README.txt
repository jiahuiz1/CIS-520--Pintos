To write a new test program to generate more alarms, I made changes to these files:
Rubric.alarm: add 4 alarm_mega for the Functionality and robustness of alarm clock
Make.tests: add a new test name, alarm-mega
tests.c: add another constant(test_alarm_mega) inside the tests struct
tests.h: add an extern test_func test_alarm_mega
alarm-wait: add a new function test_alarm_mega() and make the iteration to 70, thread count to 5.
