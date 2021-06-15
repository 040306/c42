**object oriented programming concepts**
_class_:a class is a blueprint for an object/multiple objects. a class contains a constructor that passes the properties of the object, and contains functions of the object.
_object_: any entity in the real world. objects have properties and functions, and are instances of a class.
_abstraction_:hiding data
_inheritance_:passing properties and/or functions from one class to another. keyword used is "extends". for deriving properties from the constructor to the child the keyword "super" is used.

**data types**
_numbers_
_string_: anything written in a thread
_Boolean_: true or false
_undefined_: unknown datatype
_null_: nothing

**Array**
_array_: data structure used to store multiple datatypes in a single variable. values inside an array can be accessed with index. arrays are zero index based. an array's length is based on how many elements are stored inside it.
_push operation_: adds an element to an array as the last element.
_pop operation_: removes the last element of an array.

**logical operators**
&&: AND operator. will give output only when all conditions are true.
||: OR operator. will give output if any of the conditions are true.
!=: NOT operator. will give output if the condition is false.

**arithmetic operators**
%: modulus operator: gives remainder of division as an output.
_comparison operators_
=== checks if both sides of the equation are equal
//>: checks if the left side is greater than the right side
//<: checks if the left side is less than the right side
!==: checks if both sides are not equal
_concatenation_: combining a variable/string/number with a string using +

**loops**
_for loop_:for loops repeat code as long as the conditions provided remain true. they contain 3 expressions.
for(var i; i = 1; i++){
*does stuff*
}

**ASCII code**
_ascii_:american standard code for information interchange. every key on our keyboard including special characters corresponds to an number. ex: SPACE key corresponds to the number 32. A key corresponds to 65. a corresponds to 67.

**JSON & API**
_api_: application programming interface. api's are used to connect a client to the server, like a two way messenger.
_json_:javascript object notation. translates the data from the server into a readable data structure.

**database**
_database_:used for synchronising different browsers/applications. data is stored in JSON format.
_realtime_:changes are reflected instantly
_functions_
.ref(): refers to the database
.on(): synchronous listener which is used for detecting changes in the database
.once(): asynchronous listener which is used for detecting changes in the database
.val(): gets data from the database
.set(): used for making changes inside a database
_static functions_: object created with the static function will pass the value. syntax: static function(), static functions are called with the class name.
_arrow operator_: used for pointing to one object at a time created with a class.

**functions**
tint(): used for making the object transparent to the background. syntax: tint(255,[alpha:184])
ellipse(): creates a circular object. syntax: ellipse(x,y,radiusX,radiusY)
rect(): creates a rectangular object. syntax: rect(x,y,width,height)
image(): adds an image to an object.syntax:image(var,x,y,width,height)
translate(): moves the object to the right of the canvas(clockwise direction). syntax: translate(x,y)
rotate(): rotates the object on its axis. syntax: rotate(angle)
push(): trigger the changes 
pop():stop & revert the changes

