# JavaScript

## Object-01 Assignments

1. What are objects?

   - A collection of keys = pairs.Objects are used to store data in key-value pairs.

2. How to create Objects?

   - objects are created using the Object literal syntax.

   ```JavaScript
   const person = {
     name: "John",
     age: 30,
     city: "New York",
   };
   ```

3. How to access Object properties?

   - Object properties are accessed using dot notation.

   ```JavaScript
   console.log(person.name); // "John"
   console.log(person.age); // 30
   console.log(person.city); // "New York"
   ```

   - Object properties are accessed using bracket notation.

   ```JavaScript
   console.log(person["name"]); // "John"
   console.log(person["age"]); // 30
   console.log(person["city"]); // "New York"
   ```

4. How to update Object properties?

   - Object properties are updated using dot notation.

   ```JavaScript
   person.name = "Jane";
   person.age = 25;
   person.city = "Los Angeles";
   ```

   - Object properties are updated using bracket notation.

   ```JavaScript
   person["name"] = "Jane";
   person["age"] = 25;
   person["city"] = "Los Angeles";
   ```

5. How to delete Object properties?

   - Object properties are deleted using the delete keyword.

   ```JavaScript
   delete person.name;
   delete person.age;
   delete person.city;
   ```

   - Object properties are deleted using the delete operator.

   ```JavaScript
   delete person["name"];
   delete person["age"];
   delete person["city"];
   ```

6. How to add new Object properties?

   - Object properties are added using the dot notation.

   ```JavaScript
   person.newProperty = "value";
   ```

   - Object properties are added using the bracket notation.

   ```javascript
   person["newProperty"] = "value";
   ```
