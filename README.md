# CodingQuestions
Common coding questions resolved


***1. Count number of occurence of a character in String without using if-else condition [String]***

  String s = "ioieimi"; <br/>
  char c = 'i'; <br/>
  Expected result: 4; <br/>

  Ans: <br/>
  String s2 = s.replace("i", "");  // oem  <br/>
  int res = s.length() - s2.length();  // 7-3 = 4


