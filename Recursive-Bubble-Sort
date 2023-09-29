let arr = Array.from({
    length: 100
  },
  (value, index) => {
    return Math.floor(100*Math.random())
})
console.log('arr: ', arr)

let sortArr = (arr, end = arr.length) => {
  if (end === 1) {
    return arr;
  }
  for (let i = 0; i < end; i++) {
    if (arr[i] > arr[i+1]) {
      let temp = arr[i];
      arr[i] = arr[i+1];
      arr[i+1] = temp
    }
  }
  return sortArr(arr, --end)
}

console.log(sortArr(arr));
