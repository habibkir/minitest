# easytest
a stupidly barebone unit testing tool, for whenever you just need a fancy way to check "is this ok?" and not much more

test suites are declared as
```
test_suite(test suite name)
//whatever
end_suite
```
or
```
test_suite(test suite name){
`//whatever
}end_suite
```

test cases are declared as
```
test_case(test case name)
//whatever
end_case
```
or
```
test_case(test case name){
  //whatever
}end_case
```

assertions are
```
ass_eq(expected, actual) //aborts on unequal
exp_eq(expected, actual) //doesn't
ass_t(value) //aborts on false
exp_t(value) //doesn't
```
that's it
