

# VS Code ES7 React snippets

JavaScript and React/Redux snippets in ES7+ with Babel plugin features for  [VS Code](https://code.visualstudio.com/ "https://code.visualstudio.com/")

## Installation

## Installation

### Visual Studio Marketplace

Launch  _Quick Open_:

-   [_Linux_](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-linux.pdf "https://code.visualstudio.com/shortcuts/keyboard-shortcuts-linux.pdf"):  `Ctrl+P`
-   [_macOS_](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-macos.pdf "https://code.visualstudio.com/shortcuts/keyboard-shortcuts-macos.pdf"):  `⌘P`
-   [_Windows_](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf "https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf"):  `Ctrl+P`

Paste the following command and press  `Enter`:

```js
ext install naqvi.es7-react-snippets
``` 
### Visual Studio Marketplace

Launch  _Quick Open_:

-   [_Linux_](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-linux.pdf "https://code.visualstudio.com/shortcuts/keyboard-shortcuts-linux.pdf"):  `Ctrl+P`
-   [_macOS_](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-macos.pdf "https://code.visualstudio.com/shortcuts/keyboard-shortcuts-macos.pdf"):  `⌘P`
-   [_Windows_](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf "https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf"):  `Ctrl+P`


## Supported languages (file extensions)

-   JavaScript (.js)
-   JavaScript React (.jsx)

## Snippets info

Every space inside  `{ }`  and  `( )`  means that this is pushed into next line :)  `$`  represent each step after  `tab`.

React 17 is currently supported by  `_`  prefix.



### React

|Prefix  | Description  |
|--|--|
|`cfc→ `  | create react functional component |
|`ccc→ `  | create react class component |
|`cafc→ `  | create arrow functional component |
|`cpc→ `  | create pure component |
|`cmc→ `  | create memo component |


### Imports
|Prefix  | Description  |
|--|--|
|`impd→ `  | import default export |
|`impn→ `  | import named export |

### React lifeCycle Methods
|Prefix  | Description  |
|--|--|
|`ccdm→ `  | create componentDidMount method |
|`cscu→ `  |create shouldComponentUpdate method  |
|`ccdu→ `  | create componentDidUpdate method |
|`ccwu→ `  | create componentWillUnmount method |
|`cgd→ `  | create getDerivedStateFromProps method |
|`cgsbu→ `  | create getSnapshotBeforeUpdate method |
|`crc→ `  | create react constructor component |

### React Hooks
|Prefix  | Description  |
|--|--|
|`us→ `  | useState hook |
|`ue→ `  | useEffect hook |


### React Components

`cfc`

```js
import React from 'react'

export default function Example() {
    return (
        <div>
            
        </div>
    )
}
``` 

`ccc`

```js
import React, { Component } from 'react'

export default class Example extends Component {
    render() {
        return (
            <div>
                
            </div>
        )
    }
}
``` 

`cafc`

```js
import React from 'react'

export const Example = () => {
    return (
        <div>
            
        </div>
    )
}
``` 

`cpc`

```js
import React, { PureComponent } from 'react'

export class Example extends PureComponent {
    render() {
        return (
            <div>
                
            </div>
        )
    }
}
``` 
`cmc`

```js

import React, { memo } from 'react'

const Example = memo(function Example(props) {
    return (
        <div>
            
        </div>
    )
})
``` 