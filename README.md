# Map in Go

```bash
var colors map[string]string
colors := map[string]string{
    "red":   "#ff0000",
    "green": "#4bf745",
}
```

```
colors := make(map[int]string)
colors[10] = "#ffffff"
delete(colors, 10)
```

```
colors := map[string]string{
    "red":   "#ff0000",
    "green": "#4bf745",
}
```

### Map vs Struct
![Map vs Struct image](https://github.com/alytvynov/go-map/blob/main/doc/map-vs-structs.png)