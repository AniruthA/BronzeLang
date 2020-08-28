```
; Comment

# integer = 1 ; Integer
$ string = "Hello world" ; String 
% boolean = false ; boolean

# MATH = 1+1/1%2*100


; If statements
? integer == 1 
  ; is one
.

; For loop
; goes from the range of 1 - 4
@ i 1|4

.

; increment is optional
@ i 1|20|2

.

; While loop
# a = 0
@@ a < 10
  a = a + 10
.

;Functions

^ # add(#a, #b) ; the # means that this function will return either null or an integer
  >> a + b; return statement
.

; Function call
#sum = add(1,2);

; Standard Library
; Bronze has a simple standard library and access to the cpp standard library
--> ./bronze/std.brz

; Print function
; displays text on the screen
write("Hello Bronze!")

; Get function
; gets user input
$ name = "John"
write("What is your name")
name = get()
; saying hello!
write("Hello "+name)
```