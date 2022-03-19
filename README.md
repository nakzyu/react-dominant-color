### Steps

1. Upload image
2. Convert image binary to array
3. Extract color from image
   - Extracting options
     - Weighted average of items
     - Top 1
     - ...

### Usage Example

```js
const options = {
  extract: "average",
};

const Profile = () => {
  const { color } = useDoimantColor("image-sourc-url/image", options);
  return <div style={{ color }}>User Profile</div>;
};
```
