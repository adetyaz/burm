# ![Burm](https://raw.githubusercontent.com/William-McGonagle/burm/d570084e5f2105444466b218af9c72628dea82cb/.github/media/cover.svg)

## About

## API

```javascript

import Burm, { Datatype, Condition } from "burm";

const User = Burm.register("User", {
    firstname: Datatype.STRING,
    lastname: Datatype.STRING
})

const userData = User.findOne({
    where: Condition.Equals("id", 1)
})

console.log(userData);

```