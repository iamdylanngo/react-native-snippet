# VS Code React Native, React Native Typescript, StyleSheet, ReactJS, Redux Snippet

[![Version](https://vsmarketplacebadge.apphb.com/version-short/jundat95.react-native-snippet.svg)](https://marketplace.visualstudio.com/items?itemName=jundat95.react-native-snippet)
[![Install](https://vsmarketplacebadge.apphb.com/installs-short/jundat95.react-native-snippet.svg)](https://marketplace.visualstudio.com/items?itemName=jundat95.react-native-snippet)
[![Ratings](https://vsmarketplacebadge.apphb.com/rating-short/jundat95.react-native-snippet.svg)](https://marketplace.visualstudio.com/items?itemName=jundat95.react-native-snippet)

This extension provide you Javascript and React/Redux snippets in ES6, ES7, Typescript with babel plugins features for [Vs Code](https://code.visualstudio.com/)

Here is direct link to marketplace [React Native, StyleSheet, ReactJS, Redux Snippet](https://marketplace.visualstudio.com/items?itemName=jundat95.react-native-snippet)

## Tutorial 


![Snippet React Native Example](https://media.giphy.com/media/3ohc18h5gpGws53koE/giphy.gif)

![Snippet React Native Component](https://media.giphy.com/media/xULW8KaGHOPhUJmCDm/giphy.gif)


## Supported languages (file extensions)

* JavaScript (.js)
* ReactJs (.js)
* Redux (.js)
* React Native (.jsx)
* React Native StyleSheet (.jsx)
* Typescript ReactJS (.tsx)
* Typescript React Native (.tsx)


## Snippets info

Every space inside `{ };` and `( )` means that this is pushed into next line :)
`$` represent each step after `tab`.


## Basic Methods

|Prefix|Method|
|-------:|-------|
|`imp→`|`import moduleName from 'module';`|
|`imn→`|`import 'module';`|
|`imd→`|`import { destructuredModule } from 'module';`|
|`ime→`|`import * as alias from 'module';`|
|`ima→`|`import { originalName as aliasName} from 'module';`|
|`exp→`|`export default moduleName`|
|`exd→`|`export { destructuredModule } from 'module';`|
|`exa→`|`export { originalName as aliasName} from 'module';`|
|`enf→`|`export const functionName = (params) => { };`|
|`edf→`|`export default (params) => { };`|
|`met→`|`methodName = (params) => { };`|
|`fre→`|`arrayName.forEach(element => { };`|
|`fof→`|`for(let itemName of objectName { };`|
|`fin→`|`for(let itemName in objectName { };`|
|`anfn→`|`(params) => { };`|
|`nfn→`|`const functionName = (params) => { };`|
|`dob→`|`const {propName} = objectToDescruct`|
|`dar→`|`const [propName] = arrayToDescruct`|
|`sti→`|`setInterval(() => { }, intervalTime`|
|`sto→`|`setTimeout(() => { }, delayTime`|
|`prom→`|`return new Promise((resolve, reject) => { };`|
|`cmmb→`|`comment block`|


## React Native JavaScript

|Prefix|Method|
|-------:|-------|
|`imr→`|`import React from 'react';`|
|`imrc→`|`import React, { Component } from 'react';`|
|`imrn→`|`import { $1 } from 'react-native';`|
|`imrpc→`|`import React, { PureComponent } from 'react';`|


## StyleSheet

|Prefix|Method|
|-------:|-------|
|`just→`|`justifyContent: '';`|
|`align→`|`alignItems: '${1}';`|
|`as→`|`aspectRatio: '';`|
|`bor→`|`borderWidth: ;`|
|`flex→`|`flexDirection: '';`|
|`h→`|`height: ;`|
|`w→`|`width: ;`|
|`l→`|`left: '';`|
|`mar→`|`marginHorizontal: '';`|
|`max→`|`maxWidth: ;`|
|`min→`|`minWidth: ;`|
|`over→`|`overflow: ;`|
|`padding→`|`paddingHorizontal: ;`|
|`pos→`|`position: ;`|
|`ri→`|`right: ;`|
|`z→`|`zIndex: ;`|
|`di→`|`direction: ;`|
|`back→`|`backgroundColor: ;`|
|`sha→`|`shadowColor: ;`|
|`op→`|`opacity: ;`|
|`e→`|`elevation: ;`|

## React

|Prefix|Method|
|-------:|-------|
|`imr→`|`import React from 'react';`|
|`imrc→`|`import React, { Component } from 'react';`|
|`imrcp→`|`import React, { Component } from 'react' & import PropTypes from 'prop-types';`|
|`imrpc→`|`import React, { PureComponent } from 'react';`|
|`imrpcp→`|`import React, { PureComponent } from 'react' & import PropTypes from 'prop-types';`|
|`redux→`|`import { connect } from 'react-redux';`|
|`rconst→`|`constructor(props) with this.state`|
|`rconc→`|`constructor(props, context) with this.state`|
|`est→`|`this.state = { };`|
|`cwm→`|`componentWillMount = () => { };`|
|`cdm→`|`componentDidMount = () => { };`|
|`cwr→`|`componentWillReceiveProps = (nextProps) => { };`|
|`scu→`|`shouldComponentUpdate = (nextProps, nextState) => { };`|
|`cwup→`|`componentWillUpdate = (nextProps, nextState) => { };`|
|`cdup→`|`componentDidUpdate = (prevProps, prevState) => { };`|
|`cwun→`|`componentWillUnmount = () => { };`|
|`ren→`|`render() { return( ) };`|
|`sst→`|`this.setState({ })`|
|`ssf→`|`this.setState((state, props) => return { })`|
|`props→`|`this.props.propName`|
|`state→`|`this.state.stateName`|


## Redux

|Prefix|Method|
|-------:|-------|
|`rxaction→`|`redux action template`|
|`rxconst→`|`export const $1 = '$1';`|
|`rxreducer→`|`redux reducer template`|
|`rxselect→`|`redux selector template`|


## PropTypes

|Prefix|Method|
|-------:|-------|
|`ipt`|`import PropTypes from 'prop-types';`|
|`pt→`|`Component.PropTypes = {};`|
|`dfp`|`Component.defaultProps = {};`|
|`pta→`|`PropTypes.array`|
|`ptar→`|`PropTypes.array.isRequired`|
|`ptb→`|`PropTypes.bool`|
|`ptbr→`|`PropTypes.bool.isRequired`|
|`ptf→`|`PropTypes.func`|
|`ptfr→`|`PropTypes.func.isRequired`|
|`ptn→`|`PropTypes.number`|
|`ptnr→`|`PropTypes.number.isRequired`|
|`pto→`|`PropTypes.object`|
|`ptor→`|`PropTypes.object.isRequired`|
|`pts→`|`PropTypes.string`|
|`ptsr→`|`PropTypes.string.isRequired`|
|`ptnd→`|`PropTypes.node`|
|`ptndr→`|`PropTypes.node.isRequired`|
|`ptel→`|`PropTypes.element`|
|`ptelr→`|`PropTypes.element.isRequired`|
|`pti→`|`PropTypes.instanceOf(name)`|
|`ptir→`|`PropTypes.instanceOf(name).isRequired`|
|`pte→`|`PropTypes.oneOf([name])`|
|`pter→`|`PropTypes.oneOf([name]).isRequired`|
|`ptet→`|`PropTypes.oneOfType([name])`|
|`ptetr→`|`PropTypes.oneOfType([name]).isRequired`|
|`ptao→`|`PropTypes.arrayOf(name)`|
|`ptaor→`|`PropTypes.arrayOf(name).isRequired`|
|`ptoo→`|`PropTypes.objectOf(name)`|
|`ptoor→`|`PropTypes.objectOf(name).isRequired`|
|`ptsh→`|`PropTypes.shape({ })`|
|`ptshr→`|`PropTypes.shape({ }).isRequired`|

## GraphQL
|`graphql→`|`import { compose, graphql } from 'react-apollo';`|
### `expgql`
```js
export default compose(
  graphql($1, { name: $2 })
)($3)
```

## Console

|Prefix|Method|
|-------:|-------|
|`clg→`|`console.log(object)`|
|`cas→`|`console.assert(expression,object)`|
|`ccl→`|`console.clear()`|
|`cco→`|`console.count(label)`|
|`cdi→`|`console.dir`|
|`cer→`|`console.error(object)`|
|`cgr→`|`console.group(label)`|
|`cge→`|`console.groupEnd()`|
|`ctr→`|`console.trace(object)`|
|`cwa→`|`console.warn`|
|`cin→`|`console.info`|

## React Components

### `rcc`

```javascript
import React, { Component } from 'react'

export default class $1 extends Component {
  render() {
    return (
      <div>
        $2
      </div>
    )
  }
}
```

### `rce`

```javascript
import React, { Component } from 'react'

export class $1 extends Component {
  render() {
    return (
      <div>
        $2
      </div>
    )
  }
}

export default $1
```

### `rcep`

```javascript
import React, { Component } from 'react'
import PropTypes from 'prop-types'

export class $1 extends Component {
  static propTypes = {

  }

  render() {
    return (
      <div>
        $2
      </div>
    )
  }
}

export default $1
```

### `rpc`

```javascript
import React, { PureComponent } from 'react'

export default class $1 extends PureComponent {
  render() {
    return (
      <div>
        $2
      </div>
    )
  }
}
```

### `rpcp`

```javascript
import React, { PureComponent } from 'react'
import PropTypes from 'prop-types'

export default class $1 extends PureComponent {
  static propTypes = {

  }

  render() {
    return (
      <div>
        $2
      </div>
    )
  }
}
```

### `rccp`

```javascript
import React, { Component } from 'react'
import PropTypes from 'prop-types'

export default class $1 extends Component {
  static propTypes = {
    $2: $3
  }

  render() {
    return (
      <div>
        $4
      </div>
    )
  }
}
```

### `rfe`

```javascript
import React from 'react'

const $1 = (props) => {
  return (
    <div>
      $0
    </div>
  )
}

export default $1
```

### `rfep`

```javascript
import React from 'react'
import PropTypes from 'prop-types'

const $1 = (props) => {
  return (
    <div>
      $0
    </div>
  )
}

$1.propTypes = {

}

export default $1
```

### `rfc`

```javascript
import React from 'react'

export default () => {
  return (
    <div>
      $0
    </div>
  )
}
```

### `rfcp`

```javascript
import React from 'react'
import PropTypes from 'prop-types'

export default () => {
  return (
    <div>
      $0
    </div>
  )
}

$1.propTypes = {

}
```

### `rcredux`

```javascript
import React, { Component } from 'react'
import PropTypes from 'prop-types'
import { connect } from 'react-redux'

export class $1 extends Component {
  static propTypes = {
    $2: $3
  }

  render() {
    return (
      <div>
        $4
      </div>
    )
  }
}

const mapStateToProps = (state) => ({

})

const mapDispatchToProps = {

}

export default connect(mapStateToProps, mapDispatchToProps)($1)
```

### `reduxmap`

```javascript
const mapStateToProps = (state) => ({

})

const mapDispatchToProps = {

}
```

## React Native Components

### `rnc`

```javascript
import React, { Component } from 'react'
import { Text, View } from 'react-native'

export default class $1 extends Component {
  render() {
    return (
      <View>
        <Text> $2 </Text>
      </View>
    )
  }
}
```

### `rnce`

```javascript
import React, { Component } from 'react'
import { Text, View } from 'react-native'

export class $1 extends Component {
  render() {
    return (
      <View>
        <Text> $2 </Text>
      </View>
    )
  }
}

export default $1
```


## Typescript React Native

### `tsrnc`

```javascript
import * as React from 'react';
import { View, StyleSheet, Text, } from 'react-native';

export interface $1Props {
}

export default class $1 extends React.Component<$1Props, any> {
  render() {
    return (
      <View>
         <Text>
           
         </Text>
      </View>
    );
  }
}
```


### `tsrnc`

```javascript
import * as React from 'react';
import { View, StyleSheet, Text, } from 'react-native';

export interface $1Props {
}

export interface $1State {
}

export default class $1 extends React.Component<$1Props, $1State> {
  constructor(props: $1Props) {
    super(props);
        this.state = {
    }
  }

  render() {
    return (
      <View>
         <Text>
           $1
         </Text>
      </View>
    );
  }
}
```


### `tsrnpc`

```javascript
import * as React from 'react';
import { View, StyleSheet, Text, } from 'react-native';

export interface $1Props {
}

export interface $1State {
}

export default class $1 extends React.Component<$1Props, $1State> {
  constructor(props: $1Props) {
    super(props);
        this.state = {
    }
  }

  render() {
    return (
      <View>
         <Text>
           $1
         </Text>
      </View>
    );
  }
}
```


### `tsrnc`

```javascript
import * as React from 'react';
import { View, StyleSheet, Text, } from 'react-native';
import { connect } from 'react-redux';

export interface $1Props {
}

class $1 extends React.Component<$1Props, any> {
    render() {
        return (
            <View>
                <Text>$1</Text>
            </View>
        );
    }
}

const mapState2Props = state => {
    return {
    };
}

export default connect(mapState2Props)($1);
```


## Others

### `cmmb`

```JS
/**
|--------------------------------------------------
| $1
|--------------------------------------------------
*/
```

### `desc`

```javascript
describe('$1', () => {
  $2
})
```

### `test`

```javascript
test('should $1', () => {
  $2
})
```

### `tit`

```javascript
it('should $1', () => {
  $2
})
```

### `stest`

```javascript
import { ${1: ComponentName }, mapStateToProps, mapDispatchToProps } from '${2:path}/${1:ComponentName}'

describe('<${1:ComponentName} />', () => {
  const defaultProps = {

  }

  const setup = buildSetup(${1: ComponentName }, defaultProps)

  test('render', () => {
    expect(setup().wrapper).toMatchSnapshot()
  })
})
```

### `sjtest`

```javascript
import toJson from 'enzyme-to-json'
import { ${1:ComponentName} }, mapStateToProps, mapDispatchToProps } from '${2:path}/${1:ComponentName}'

describe('<${1:ComponentName} />', () => {
  const defaultProps = {

  }

  const setup = buildSetup(${1: ComponentName }, defaultProps)

  test('render', () => {
    expect(toJson(setup().wrapper)).toMatchSnapshot()
  })
})
```

### `sntest`

```javascript
import 'react-native'
import React from 'react'
import renderer from 'react-test-renderer'

import ${1:ComponentName} from '../${1:ComponentName}'

it('renders correctly', () => {
  const tree = renderer.create(<${1:ComponentName} />).toJSON()

  expect(tree).toMatchSnapshot()
})
```

### `hocredux`

```javascript
import React from 'react'
import PropTypes from 'prop-types'
import { connect } from 'react-redux'

export const mapStateToProps = state => ({

})

export const mapDispatchToProps = {

}

export const ${1:hocComponentName} = (WrappedComponent) => {
  const hocComponent = ({ ...props }) => <WrappedComponent {...props} />

  hocComponent.propTypes = {
  }

  return hocComponent
}

export default WrapperComponent => connect(mapStateToProps, mapDispatchToProps)(${1:hocComponentName}(WrapperComponent))
```

### `hoc`

``` javascript
import React from 'react'
import PropTypes from 'prop-types'

export default (WrappedComponent) => {
  const hocComponent = ({ ...props }) => <WrappedComponent {...props} />

  hocComponent.propTypes = {
  }

  return hocComponent
}
```