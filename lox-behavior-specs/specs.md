#  Lox Specification Test Cases

##  Truthiness
  --lox
if (0) print "truthy"; // expect: truthy
if ("") print "truthy"; // expect: truthy
if (false) print "no"; else print "false is falsy"; // expect: false is falsy
if (nil) print "no"; else print "nil is falsy"; // expect: nil is falsy
