# Vim React Snippets

Fork of [epilande/vim-react-snippets](https://github.com/epilande/vim-react-snippets) that match StandardJS rules.
Requires [UltiSnips](https://github.com/SirVer/ultisnips).

Just removed semicolons and added space on function declaration

A Vim snippet library for React in ES6. You may also want to check out [vim-es2015-snippets](https://github.com/paupalou/vim-es2015-snippets).

## Installation

Using [vim-plug](https://github.com/junegunn/vim-plug):

```vim
" ES2015 code snippets (Optional)
Plug 'paupalou/vim-es2015-snippets'

" React code snippets
Plug 'paupalou/vim-react-snippets'

" Ultisnips
Plug 'SirVer/ultisnips'
```

## Snippets

#### Skeleton

| Trigger  | Content |
| -------: | ------- |
| `rrcc→`  | React Redux Class Component |
| `rcc→`   | React Class Component |
| `rfc→`   | React Functional Component |
| `rsc→`   | React Styled Component |


#### Lifecycle

| Trigger  | Content |
| -------: | ------- |
| `cwm→`   | `componentWillMount () {...}` |
| `cdm→`   | `componentDidMount () {...}` |
| `cwrp→`  | `componentWillReceiveProps (nextProps) {...}` |
| `scup→`  | `shouldComponentUpdate (nextProps, nextState) {...}` |
| `cwup→`  | `componentWillUpdate (nextProps, nextState) {...}` |
| `cdup→`  | `componentDidUpdate (prevProps, prevState) {...}` |
| `cwu→`   | `componentWillUnmount () {...}` |
| `ren→`   | `render () {...}` |


#### PropTypes

| Trigger    | Content |
| -------:   | ------- |
| `pt→`      | `propTypes {...}` |
| `pt.a→`    | `PropTypes.array` |
| `pt.b→`    | `PropTypes.bool` |
| `pt.f→`    | `PropTypes.func` |
| `pt.n→`    | `PropTypes.number` |
| `pt.o→`    | `PropTypes.object` |
| `pt.s→`    | `PropTypes.string` |
| `pt.no→`   | `PropTypes.node` |
| `pt.e→`    | `PropTypes.element` |
| `pt.io→`   | `PropTypes.instanceOf` |
| `pt.one→`  | `PropTypes.oneOf` |
| `pt.onet→` | `PropTypes.oneOfType (Union)` |
| `pt.ao→`   | `PropTypes.arrayOf (Instances)` |
| `pt.oo→`   | `PropTypes.objectOf` |
| `pt.sh→`   | `PropTypes.shape` |
| `ir→`      | `isRequired` |

#### Others

| Trigger  | Content |
| -------: | ------- |
| `props→` | `this.props` |
| `state→` | `this.state` |
| `set→`   | `this.setState(...)` |
| `dp→`    | `defaultProps {...}` |
| `cn→`    | `className` |
| `ref→`   | `ref` |
| `pp→`    | `${props => props}` |
