# ReScript binding to [Heroicons](https://heroicons.com/)

With this binding, heroicons can be used as React Components.

```OCaml
open Heroicons

@react.component
let make = () => {
  <div>
    <Solid.PaperAirplaneIcon className="w-8 h-8" />
    <Outline.PaperAirplaneIcon className="w-8 h-8" />
  </div>
}
// w-8, h-8 are tailwind css classes.
```

### Installation

`yarn add rescript-heroicons` or `npm install rescript-heroicons` <br>
The binding has the following dependencies, and they are needed to install.
- [@rescript/react](https://www.npmjs.com/package/@rescript/react)
- [@heroicons/react](https://www.npmjs.com/package/@heroicons/react)

### <br>Author


Nyi Nyi Than (Jazz)
- LinkedIn: [@nyinyithann](https://www.linkedin.com/in/nyinyithan/)
- Twitter: [@JazzTuyat](https://twitter.com/JazzTuyat)

### License

MIT