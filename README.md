# JS_BY_SELF
## MAP
map is used to get data from the array of objects,Map will not modify the original array but it will copy the array for performing operations.<br>

let person=[{name:"ali"},{name:"abbas"}] <br>
const a=person.map((res)=>res.name) <br>
-
here we are making a callback function inside a map function and calling name through res argument.
