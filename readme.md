# JavaScript Objects 01

## assignments

1. What is Objects?

   - A collection of keys = pairs.Objects are used to store data in key-value pairs.

2. How to create Objects

   - objects are created using the Object literal syntax.

   ```javascript
   const person = {
     name: "John",
     age: 30,
     city: "New York",
   };
   ```

3. How to access Object properties

   - Object properties are accessed using dot notation.

   ```javascript
   console.log(person.name); // "John"
   console.log(person.age); // 30
   console.log(person.city); // "New York"
   ```

   - Object properties are accessed using bracket notation.

   ```javascript
   console.log(person["name"]); // "John"
   console.log(person["age"]); // 30
   console.log(person["city"]); // "New York"
   ```

4. How to update Object properties

   - Object properties are updated using dot notation.

   ```javascript
   person.name = "Jane";
   person.age = 25;
   person.city = "Los Angeles";
   ```

   - Object properties are updated using bracket notation.

   ```javascript
   person["name"] = "Jane";
   person["age"] = 25;
   person["city"] = "Los Angeles";
   ```

5. How to delete Object properties

   - Object properties are deleted using the delete keyword.

   ```javascript
   delete person.name;
   delete person.age;
   delete person.city;
   ```

   - Object properties are deleted using the delete operator.

   ```javascript
   delete person["name"];
   delete person["age"];
   delete person["city"];
   ```

6. How to add new Object properties

   - Object properties are added using the dot notation.

   ```javascript
   person.newProperty = "value";
   ```

   - Object properties are added using the bracket notation.

   ```javascript
   person["newProperty"] = "value";
   ```
