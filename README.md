<p align="center">
 <img width="100px" src="https://raw.githubusercontent.com/hebertcisco/use-os/master/.github/images/favicon512x512-linux.png" align="center" alt=":package: use-os" />
 <h2 align="center">:package: use-os</h2>
 <p align="center">Parses browser user-agent strings for React</p>
</p>

<p align="center">Did you like the project? Please, considerate <a href="https://github.com/hebertcisco/hebertcisco/blob/main/.github/patreon.md">being a supporter</a> and receive exclusive gifts!
 </p>

## Installation

> Clone this repository: `git clone https://github.com/hebertcisco/use-os`

### Open the directory and install the dependencies

```bash
cd use-os
npm install
```

## Using

```js
import useOs from "use-os";
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
