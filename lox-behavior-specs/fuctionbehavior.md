 -- no. of arguments

fun add(a, b) { return a + b; }
print add(1, 2); // expect: 3
add(1); // expect: runtime error (wrong argument count)

--return type error 
//out of function return
return 5; // expect: compile-time error
