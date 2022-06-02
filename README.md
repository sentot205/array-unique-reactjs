# Array Unique Reactjs
Npm Package for convert data to unique array.
## Example

```js
import getUnique from "array-unique-reactjs";

const prizelips = [
  {
    title: "40M",
    price: 5000,
  },
  {
    title: "100M",
    price: 30000,
  },
  {
    title: "350M",
    price: 100000,
  },
  {
    title: "1B",
    price: 100000,
  },
  {
    title: "2.5B",
    price: 200000,
  },
];

const uniquePrize = getUnique(prizelips, "price");

function Test() {
  return (
    uniquePrize.map((item) => console.log(item.price))
  );
}
```