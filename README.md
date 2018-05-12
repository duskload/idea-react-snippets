# idea-react-snippets

React snippets (live templates) for idea.

## Install

1. Download `settings.jar`
2. Click on "File" -> "Importing Settings..." select `settings.jar` and click OK.

## Usage description

### `cdc`

```js
componentDidCatch() {
  $END$
}
```

### `cdm`
```js
componentDidMount() {
  $END$
}
```

### `cdu`
```js
componentDidUpdate(prevProps, prevState) {
  $END$
}
```

### `cef`
```js
const $NAME$ = () => {
  $END$
};
```

### `cem`
```js
$NAME$ = () => {
  $END$
}
```

### `cfp`
```js
const $NAME$ = ($PARAMS$) => {
  $END$
};
```

### `cmp`

```js
$NAME$ = ($PARAM$) => {
  $END$
}
```

### `con`

```js
constructor(props) {
  super(props);
  
  $END$
}
```

### `cpts`

```js
$COMPONENT$.propTypes = {
  $START$: PropTypes.$END$,
};
```

### `ctor`

```js
constructor(props) {
  super(props);
  
  this.state = { $START$ };
  $END$
}
```

### `cwm`

```js
componentWillMount() {
  $END$
}
```

### `cwr`

```js
componentWillReceiveProps(nextProps$START$) {
  $END$
}
```

### `cwu`

```js
componentWillUpdate(nextProps, nextState) {
  $END$
}
```
### `cwun`

```js
componentWillUnmount() {
  $END$
}
```

### `drp`

```js
const { $END$ } = this.props;
```

### `dst`

```js
const { $END$ } = this.state;
```

### `ecc`

```js
export default connect($PARAM$, $PARAM2$)($COMPONENT$);
```

### `gb`

```js
getSnapshotBeforeUpdate(prevProps, prevState) {
  $END$
}
```

### `im`

```js
import $START$ from '$END$';
```

### `imp`

```js
import { $START$ } from '$END$';
```

### `imr`

```js
import React, { Component } from 'react';
$END$
```

### `ims`

```js
import '$END$';
```

### `mdp`

```js
const mapDispatchToProps = dispatch => {
  return {
    $END$
  };
};
```

### `mst`

```js
const mapStateToProps = state => {
  return {
    $END$
  };
};
```

### `pst`

```js
state = {
  $START$: $END$,
};
```

### `pt`

```js
$START$: PropTypes.$END$,
```

### `rcc`

```js
import React, { Component } from 'react';
import PropTypes from 'prop-types';

export default class $COMPONENT$ extends Component {
  render() {
    return (
      <div>$END$</div>
    );
  }
}

$COMPONENT$.defaultProps = {};
$COMPONENT$.propTypes = {};
```

### `re`

```js
render() {
  return (
    <div>$END$</div>
  );
}
```

### `rf`

```js
ref={$PROPERTY$ => this.$END$ = $PROPERTY$}
```

### `rfc`

```js
import React from 'react';
import PropTypes from 'prop-types';

const $COMPONENT$ = ($PARAMETER$) => {
  return (
    <div>$END$</div>
  );
}

$COMPONENT$.defaultProps = {};
$COMPONENT$.propTypes = {};

export default $COMPONENT$;

```

### `rfc5`

```js
import React from 'react';
import PropTypes from 'prop-types';

function $COMPONENT$($PARAMETER$) {
  return (
    <div>$END$</div>
  );
}

$COMPONENT$.propTypes = {};
$COMPONENT$.defaultProps = {};

export default $COMPONENT$;
```

### `rpc`

```js
import React, { PureComponent } from 'react';
import PropTypes from 'prop-types';

export default class $COMPONENT$ extends PureComponent {
  render() {
    return (
      <div>$END$</div>
    );
  }
}

$COMPONENT$.defaultProps = {};
$COMPONENT$.propTypes = {};
```

### `scu`

```js
shouldComponentUpdate(nextProps, nextState) {
  $END$
}
```

### `sdp`

```js
static defaultProps = {
  $START$: $END$,
};
```

### `spts`

```js
static propTypes = {
  $START$: PropTypes.$END$,
};
```

### `sst`

```js
this.setState({ $START$: $END$ });
```

### `tpr`

```js
this.props.$END$
```

### `tst`

```js
this.state.$END$
```
