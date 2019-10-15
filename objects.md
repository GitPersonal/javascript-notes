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
