dexer
=====

A document lexer for coffeescript files

# Purpose

source code of your api

```coffeescript
# I'll drop everything to the limbo
# @param x {String} {required} x man
# @param y {Mixed} {optional} y chromosome
# @return null
devNull = (x, y) -> null
```

dexer compile to this
```
# foo

## summary
I'll drop everything to the limbo

## params
<table>
  <thead>
    <tr>
      <th>key</th>
      <th>type</th>
      <th>required</th>
      <th>description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>x</td>
      <td>String</td>
      <td>true</td>
      <td>x man</td>
    </tr>
    <tr>
      <td>y</td>
      <td>String</td>
      <td>false</td>
      <td>y chromosome</td>
    </tr>
  </tbody>
</table>
```

## return

null
```


