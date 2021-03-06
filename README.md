# react-nepal-map

> React component for Nepal Map

[![NPM](https://img.shields.io/npm/v/react-nepal-map.svg)](https://www.npmjs.com/package/react-nepal-map) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

## Install

```bash
npm install --save react-nepal-map
```

## Usage

```jsx
import React from 'react'
import { ProvinceMap, ZonalMap, DistrictMap } from 'react-nepal-map'

const App = () => {
  return (
    <div>
      <ProvinceMap
        hoverColor='red'
        stroke='#000'
        provinceColor=['red', 'green', 'blue']
        strokeWidth={1}
        onMapClick={(val) => console.log(val)}
      />
      <ZonalMap
        hoverColor='red'
        onMapClick={(val) => console.log(val)}
        stroke='#000'
        strokeWidth={1}
      />
      <DistrictMap
        hoverColor='red'
        stroke='#000'
        strokeWidth={1}
        onMapClick={(val) => console.log(val)}
      />
    </div>
  )
}

export default App
```

## TypeScript

TypeScript type definition was add to the [DefinitelyTyped repository](https://github.com/DefinitelyTyped/DefinitelyTyped)

contributed by: [ashiishme](https://github.com/ashiishme)

```bash
npm install --save @types/react-nepal-map
```

## Contributors

<a href="https://github.com/ashiishme"><img src="https://avatars1.githubusercontent.com/u/18111862?s=460&u=2f3e78032c535d11cf6c6be111ed4042e88326c9&v=4" title="ashiishme" width="60" height="60"></a>

## License

MIT © [keyrunpay](https://github.com/keyrunpay)
