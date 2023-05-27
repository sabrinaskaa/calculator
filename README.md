# calculator

```bash
while (true) {
  var a, group;
  a = prompt("Simple Calculator").replace(/[^0-9%^*\/()\-+.]/g, "");
  group = a.split(" ");

  if ((Number.parseInt(group[0]) | Number.parseInt(group[2])) > 1000000) {
    alert("Maksimal angka 1 juta");
  } else {
    alert(eval(a));
  }
}
```
