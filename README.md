## A lib gather some useful data types

## Features

Currently support: StandardEmailType, GmailType


## Use example

type example
```ts
import type { EmailType } from "extra-data-types";

const exampleEmail: EmailType.StandardType = 'example@example.com';
const exampleGmail: EmailType.GmailType = 'example@gmail.com';
```

function example
```ts
import { isStandardEmailType, isGmailType } from "extra-data-types";

if(isStandardEmailType("example.example@example.com")){
  //do something when is valid of standard email type
}else{
  //...
}

if(isStandardEmailType("example.example@gmail.com")){
  //do something when is valid of gmail type
}else{
  //...
}

```

## Contributing

Any type of contribution is welcome.

- Use extra-data-types in your daily work.
- Submit [issues](https://github.com/chen1415/extra-data-types/issues) to report bugs or ask questions.
- Propose [pull requests](https://github.com/chen1415/extra-data-types/pulls) to improve our code.
