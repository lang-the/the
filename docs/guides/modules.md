# Modules

## Module import
```the
import Math from math
import Thing1, thing2 from my-module
```

## Local file Import
```the
import Thing1, Thing2 from ./things
import formatCurrency, formatTime from ../formatters/index
```

## Delayed export
```the
obj SuperObject {
}

enum SuperEnum {
  op_one,
  op_two
}

export SuperEnum, SuperObject
```

## Instant export
```the
export class Thing {
}

export fn calc () {
}
```