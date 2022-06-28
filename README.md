# CodingQuestions
Common coding questions resolved


***1. Count number of occurence of a character in String without using if-else condition [String]***

String s = "ioieimi";
char c = 'i';
Expected result: 4;

Ans:
String s2 = s.replace("i", "");  // oem
int res = s.length() - s2.length();  // 7-3 = 4


