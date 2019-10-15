# Intro to Objects

What are Objects?

An object is data that contains **key-value pairs**.

You can create objects by writing these key-value pairs within curly braces.

If you intend to create multiple key-value pairs, you need to separate each pair with commas.

```javascript
const anObject = {
  key1: "value1",
  key2: "value2",
  key3: "value3"
};
```

Each key gives you a reference to a _value_, If you imagine an English dictionary, the keys are the words while the values are the definition of each word.

```javascript
const macbook = {
  operatingSystem: "macOS Sierra",
  screenResolution: "2880x1800",
  screenSize: "15.4 inch",
  usbPorts: 2,
  storage: "512gb"
};
```

## Object values

Objects can contain any value that is valid in JavaScript. This means you can store primitives (like Strings and Numbers) and other objects.

```javascript
const anObject = {
    string: 'Yay',
    number: 1,
    boolean: true,
    anotherObject:{},
    aFunction:function(){},
    anArray:()
}
```

## Getting value of a property

Object keys are called **properties**. You can use two methods to get the value of a property.

The first method is through the **dot notation**, where you write the name of the object, followed by **.**, followed by the property name:

```javascript
const prop = object.property;
```

If you want to get to the **storage** property of the macbook we declared above, you can write **macbook.storage**.

```javascript
const macbookStorage = macbook.storage;
console.log(macbookStorage); // 512gb
```
