<p align="center">
 <img width="100px" src="https://raw.githubusercontent.com/hebertcisco/react-useOs/master/.github/images/favicon512x512-linux.png" align="center" alt=":package: react-useOs" />
 <h2 align="center">:package: react-useOs</h2>
 <p align="center">React Package to show OS type</p>
</p>

<p align="center">Did you like the project? Please, considerate <a href="https://github.com/hebertcisco/hebertcisco/blob/main/.github/patreon.md">being a supporter</a> and receive exclusive gifts!
 </p>

## Installation

> Clone this repository: `git clone https://github.com/hebertcisco/react-useOs`

### Open the directory and install the dependencies

```bash
cd react-useOs
npm install
```

## Using

```js
import useOs from "react-useOs";
```

In react component:

```js
export default function HomePage() {
  const os = useOs();

  return (
    <div>
      {os === "windows" ? (
        <>
          <b>Windows</b> (.exe)
        </>
      ) : (
        <></>
      )}
    </div>
  );
}
```
