```js
let user = {
  name: 'Arya',
  sibling: ['Robb', 'Ryan', 'John'],
};
let allBrothers = ['Robb', 'Ryan', 'John'];
let brothersCopy = user.sibling;
let usename = user.name;
let newUser = user;
```

1. Memory representation

- Create the memory representation of the above snippet on notebook.
- Take a photo/screenshot and add it to the folder `code`

<!-- To add this image here use ![name](./hello.jpg) -->
//check the image in files

2. Answer the following with reason:

- `user == newUser;` // true have the same address value
- `user === newUser;` //true have the same address value
- `user.name === newUser.name;` //true have the same address value
- `user.name == newUser.name;` //true have the same address value
- `user.sibling == newUser.sibling;` //true
- `user.sibling === newUser.sibling;` //true
- `user.sibling == allBrothers;` // false have different address stored
- `user.sibling === allBrothers;` //false have different address stored
- `brothersCopy === allBrothers;` //false have different address stored
- `brothersCopy == allBrothers;` //false have different address stored
- `brothersCopy == user.sibling;` //true
- `brothersCopy === user.sibling;` //true
- `brothersCopy[0] === user.sibling[0];` //true
- `brothersCopy[1] === user.sibling[1];` //true
- `user.sibling[1] === newUser.sibling[1];` //true
