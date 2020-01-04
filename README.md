# 301-practice-2

__Q1- In a Handlebars template, what does {{city}} refer to?__
### The Answer : It's a handlebar expression and the value of the city inside will be replaced once code running and take the value from the needed object as an input . 

### The answer From __https://handlebarsjs.com/guide/#simple-expressions__ is : A handlebars expression is a {{, some contents, followed by a }}. When the template is executed, these expressions are replaced with values from an input object.

__Q2- Explain how the following code in a Node-express server is triggered to run, and what it's output is ?__

server.get('/list', (request, response) => {
   let animals = ['Cat','Dog','Sheep'];
   response.send(200).json(animals);
});

### The Answer : Create route with name "list" and print out the array of animals since the status is "200" which means the code runs succesfully .


__Q3- Write a Constructor function that can create an instance of a person, with a name and an age, given 2 arguments__

### The Answer :

function Person (name,age) 
{
    this.name = name;
    this.age = age;
}

let person = new Person ('nawal',31);
console.log(person);
