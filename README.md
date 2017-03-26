# api documentation for  [react-router (v4.0.0)](https://github.com/reacttraining/react-router#readme)  [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-react-router.svg)](https://travis-ci.org/npmdoc/node-npmdoc-react-router)
#### Declarative routing for React

[![NPM](https://nodei.co/npm/react-router.png?downloads=true)](https://www.npmjs.com/package/react-router)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-router/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-react-router_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-router/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-react-router/build/screen-capture.npmPackageListing.svg)



# package.json

```json

{
    "authors": [
        "Michael Jackson",
        "Ryan Florence"
    ],
    "browserify": {
        "transform": [
            "loose-envify"
        ]
    },
    "bugs": {
        "url": "https://github.com/reacttraining/react-router/issues"
    },
    "dependencies": {
        "history": "^4.6.0",
        "invariant": "^2.2.2",
        "loose-envify": "^1.3.1",
        "path-to-regexp": "^1.5.3",
        "warning": "^3.0.0"
    },
    "description": "Declarative routing for React",
    "devDependencies": {
        "babel-cli": "^6.18.0",
        "babel-eslint": "^6.0.4",
        "babel-loader": "^6.2.10",
        "babel-plugin-dev-expression": "^0.2.1",
        "babel-plugin-transform-react-remove-prop-types": "^0.2.11",
        "babel-preset-es2015": "^6.14.0",
        "babel-preset-react": "^6.5.0",
        "babel-preset-stage-1": "^6.5.0",
        "eslint": "^2.13.1",
        "eslint-plugin-import": "^1.15.0",
        "eslint-plugin-react": "^5.2.2",
        "expect": "^1.20.1",
        "gzip-size": "^3.0.0",
        "in-publish": "^2.0.0",
        "karma": "^0.13.22",
        "karma-browserstack-launcher": "^1.0.1",
        "karma-chrome-launcher": "^1.0.1",
        "karma-mocha": "^1.0.1",
        "karma-mocha-reporter": "^2.0.4",
        "karma-sourcemap-loader": "^0.3.7",
        "karma-webpack": "^1.7.0",
        "mocha": "^2.5.3",
        "pretty-bytes": "^3.0.1",
        "react": "^15.4.2",
        "react-addons-test-utils": "^15.4.2",
        "react-dom": "^15.3.0",
        "readline-sync": "^1.4.4",
        "webpack": "^1.13.1",
        "webpack-dev-server": "^1.14.1"
    },
    "directories": {},
    "dist": {
        "shasum": "6532075231f0bb5077c2005c1d417ad6165b3997",
        "tarball": "https://registry.npmjs.org/react-router/-/react-router-4.0.0.tgz"
    },
    "files": [
        "MemoryRouter.js",
        "Prompt.js",
        "Redirect.js",
        "Route.js",
        "Router.js",
        "StaticRouter.js",
        "Switch.js",
        "index.js",
        "matchPath.js",
        "withRouter.js",
        "README.md",
        "es",
        "umd"
    ],
    "homepage": "https://github.com/reacttraining/react-router#readme",
    "keywords": [
        "react",
        "router",
        "route",
        "routing",
        "history",
        "link"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "mjackson",
            "email": "mjijackson@gmail.com"
        },
        {
            "name": "ryanflorence",
            "email": "rpflorence@gmail.com"
        },
        {
            "name": "timdorr",
            "email": "timdorr@timdorr.com"
        }
    ],
    "module": "es/index.js",
    "name": "react-router",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": "^15"
    },
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/reacttraining/react-router.git"
    },
    "scripts": {
        "build": "node ./tools/build.js",
        "clean": "git clean -e '!node_modules' -fdX .",
        "lint": "eslint modules",
        "prepublish": "node ./tools/build.js",
        "test": "karma start --single-run",
        "watch": "babel ./modules -d . --ignore __tests__ --watch"
    },
    "version": "4.0.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module react-router](#apidoc.module.react-router)
1.  boolean <span class="apidocSignatureSpan">react-router.</span>__esModule
1.  [function <span class="apidocSignatureSpan">react-router.</span>MemoryRouter ()](#apidoc.element.react-router.MemoryRouter)
1.  [function <span class="apidocSignatureSpan">react-router.</span>Prompt ()](#apidoc.element.react-router.Prompt)
1.  [function <span class="apidocSignatureSpan">react-router.</span>Redirect ()](#apidoc.element.react-router.Redirect)
1.  [function <span class="apidocSignatureSpan">react-router.</span>Route ()](#apidoc.element.react-router.Route)
1.  [function <span class="apidocSignatureSpan">react-router.</span>Router ()](#apidoc.element.react-router.Router)
1.  [function <span class="apidocSignatureSpan">react-router.</span>StaticRouter ()](#apidoc.element.react-router.StaticRouter)
1.  [function <span class="apidocSignatureSpan">react-router.</span>Switch ()](#apidoc.element.react-router.Switch)
1.  [function <span class="apidocSignatureSpan">react-router.</span>matchPath (pathname)](#apidoc.element.react-router.matchPath)
1.  [function <span class="apidocSignatureSpan">react-router.</span>withRouter (Component)](#apidoc.element.react-router.withRouter)
1.  object <span class="apidocSignatureSpan">react-router.</span>MemoryRouter.propTypes
1.  object <span class="apidocSignatureSpan">react-router.</span>MemoryRouter.prototype
1.  object <span class="apidocSignatureSpan">react-router.</span>Prompt.contextTypes
1.  object <span class="apidocSignatureSpan">react-router.</span>Prompt.propTypes
1.  object <span class="apidocSignatureSpan">react-router.</span>Prompt.prototype
1.  object <span class="apidocSignatureSpan">react-router.</span>Redirect.contextTypes
1.  object <span class="apidocSignatureSpan">react-router.</span>Redirect.propTypes
1.  object <span class="apidocSignatureSpan">react-router.</span>Redirect.prototype
1.  object <span class="apidocSignatureSpan">react-router.</span>Route.childContextTypes
1.  object <span class="apidocSignatureSpan">react-router.</span>Route.contextTypes
1.  object <span class="apidocSignatureSpan">react-router.</span>Route.propTypes
1.  object <span class="apidocSignatureSpan">react-router.</span>Route.prototype
1.  object <span class="apidocSignatureSpan">react-router.</span>Router.childContextTypes
1.  object <span class="apidocSignatureSpan">react-router.</span>Router.contextTypes
1.  object <span class="apidocSignatureSpan">react-router.</span>Router.propTypes
1.  object <span class="apidocSignatureSpan">react-router.</span>Router.prototype
1.  object <span class="apidocSignatureSpan">react-router.</span>StaticRouter.childContextTypes
1.  object <span class="apidocSignatureSpan">react-router.</span>StaticRouter.propTypes
1.  object <span class="apidocSignatureSpan">react-router.</span>StaticRouter.prototype
1.  object <span class="apidocSignatureSpan">react-router.</span>Switch.contextTypes
1.  object <span class="apidocSignatureSpan">react-router.</span>Switch.propTypes
1.  object <span class="apidocSignatureSpan">react-router.</span>Switch.prototype

#### [module react-router.MemoryRouter](#apidoc.module.react-router.MemoryRouter)
1.  [function <span class="apidocSignatureSpan">react-router.</span>MemoryRouter ()](#apidoc.element.react-router.MemoryRouter.MemoryRouter)
1.  object <span class="apidocSignatureSpan">react-router.MemoryRouter.</span>propTypes

#### [module react-router.MemoryRouter.propTypes](#apidoc.module.react-router.MemoryRouter.propTypes)
1.  [function <span class="apidocSignatureSpan">react-router.MemoryRouter.propTypes.</span>children ()](#apidoc.element.react-router.MemoryRouter.propTypes.children)
1.  [function <span class="apidocSignatureSpan">react-router.MemoryRouter.propTypes.</span>getUserConfirmation ()](#apidoc.element.react-router.MemoryRouter.propTypes.getUserConfirmation)
1.  [function <span class="apidocSignatureSpan">react-router.MemoryRouter.propTypes.</span>initialEntries ()](#apidoc.element.react-router.MemoryRouter.propTypes.initialEntries)
1.  [function <span class="apidocSignatureSpan">react-router.MemoryRouter.propTypes.</span>initialIndex ()](#apidoc.element.react-router.MemoryRouter.propTypes.initialIndex)
1.  [function <span class="apidocSignatureSpan">react-router.MemoryRouter.propTypes.</span>keyLength ()](#apidoc.element.react-router.MemoryRouter.propTypes.keyLength)

#### [module react-router.MemoryRouter.prototype](#apidoc.module.react-router.MemoryRouter.prototype)
1.  [function <span class="apidocSignatureSpan">react-router.MemoryRouter.prototype.</span>render ()](#apidoc.element.react-router.MemoryRouter.prototype.render)

#### [module react-router.Prompt](#apidoc.module.react-router.Prompt)
1.  [function <span class="apidocSignatureSpan">react-router.</span>Prompt ()](#apidoc.element.react-router.Prompt.Prompt)
1.  object <span class="apidocSignatureSpan">react-router.Prompt.</span>contextTypes
1.  object <span class="apidocSignatureSpan">react-router.Prompt.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-router.Prompt.</span>propTypes

#### [module react-router.Prompt.contextTypes](#apidoc.module.react-router.Prompt.contextTypes)
1.  [function <span class="apidocSignatureSpan">react-router.Prompt.contextTypes.</span>router ()](#apidoc.element.react-router.Prompt.contextTypes.router)

#### [module react-router.Prompt.propTypes](#apidoc.module.react-router.Prompt.propTypes)
1.  [function <span class="apidocSignatureSpan">react-router.Prompt.propTypes.</span>message ()](#apidoc.element.react-router.Prompt.propTypes.message)
1.  [function <span class="apidocSignatureSpan">react-router.Prompt.propTypes.</span>when ()](#apidoc.element.react-router.Prompt.propTypes.when)

#### [module react-router.Prompt.prototype](#apidoc.module.react-router.Prompt.prototype)
1.  [function <span class="apidocSignatureSpan">react-router.Prompt.prototype.</span>componentWillMount ()](#apidoc.element.react-router.Prompt.prototype.componentWillMount)
1.  [function <span class="apidocSignatureSpan">react-router.Prompt.prototype.</span>componentWillReceiveProps (nextProps)](#apidoc.element.react-router.Prompt.prototype.componentWillReceiveProps)
1.  [function <span class="apidocSignatureSpan">react-router.Prompt.prototype.</span>componentWillUnmount ()](#apidoc.element.react-router.Prompt.prototype.componentWillUnmount)
1.  [function <span class="apidocSignatureSpan">react-router.Prompt.prototype.</span>disable ()](#apidoc.element.react-router.Prompt.prototype.disable)
1.  [function <span class="apidocSignatureSpan">react-router.Prompt.prototype.</span>enable (message)](#apidoc.element.react-router.Prompt.prototype.enable)
1.  [function <span class="apidocSignatureSpan">react-router.Prompt.prototype.</span>render ()](#apidoc.element.react-router.Prompt.prototype.render)

#### [module react-router.Redirect](#apidoc.module.react-router.Redirect)
1.  [function <span class="apidocSignatureSpan">react-router.</span>Redirect ()](#apidoc.element.react-router.Redirect.Redirect)
1.  object <span class="apidocSignatureSpan">react-router.Redirect.</span>contextTypes
1.  object <span class="apidocSignatureSpan">react-router.Redirect.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-router.Redirect.</span>propTypes

#### [module react-router.Redirect.contextTypes](#apidoc.module.react-router.Redirect.contextTypes)
1.  [function <span class="apidocSignatureSpan">react-router.Redirect.contextTypes.</span>router ()](#apidoc.element.react-router.Redirect.contextTypes.router)

#### [module react-router.Redirect.propTypes](#apidoc.module.react-router.Redirect.propTypes)
1.  [function <span class="apidocSignatureSpan">react-router.Redirect.propTypes.</span>from ()](#apidoc.element.react-router.Redirect.propTypes.from)
1.  [function <span class="apidocSignatureSpan">react-router.Redirect.propTypes.</span>push ()](#apidoc.element.react-router.Redirect.propTypes.push)
1.  [function <span class="apidocSignatureSpan">react-router.Redirect.propTypes.</span>to ()](#apidoc.element.react-router.Redirect.propTypes.to)

#### [module react-router.Redirect.prototype](#apidoc.module.react-router.Redirect.prototype)
1.  [function <span class="apidocSignatureSpan">react-router.Redirect.prototype.</span>componentDidMount ()](#apidoc.element.react-router.Redirect.prototype.componentDidMount)
1.  [function <span class="apidocSignatureSpan">react-router.Redirect.prototype.</span>componentWillMount ()](#apidoc.element.react-router.Redirect.prototype.componentWillMount)
1.  [function <span class="apidocSignatureSpan">react-router.Redirect.prototype.</span>isStatic ()](#apidoc.element.react-router.Redirect.prototype.isStatic)
1.  [function <span class="apidocSignatureSpan">react-router.Redirect.prototype.</span>perform ()](#apidoc.element.react-router.Redirect.prototype.perform)
1.  [function <span class="apidocSignatureSpan">react-router.Redirect.prototype.</span>render ()](#apidoc.element.react-router.Redirect.prototype.render)

#### [module react-router.Route](#apidoc.module.react-router.Route)
1.  [function <span class="apidocSignatureSpan">react-router.</span>Route ()](#apidoc.element.react-router.Route.Route)
1.  object <span class="apidocSignatureSpan">react-router.Route.</span>childContextTypes
1.  object <span class="apidocSignatureSpan">react-router.Route.</span>contextTypes
1.  object <span class="apidocSignatureSpan">react-router.Route.</span>propTypes

#### [module react-router.Route.childContextTypes](#apidoc.module.react-router.Route.childContextTypes)
1.  [function <span class="apidocSignatureSpan">react-router.Route.childContextTypes.</span>router ()](#apidoc.element.react-router.Route.childContextTypes.router)

#### [module react-router.Route.contextTypes](#apidoc.module.react-router.Route.contextTypes)
1.  [function <span class="apidocSignatureSpan">react-router.Route.contextTypes.</span>router ()](#apidoc.element.react-router.Route.contextTypes.router)

#### [module react-router.Route.propTypes](#apidoc.module.react-router.Route.propTypes)
1.  [function <span class="apidocSignatureSpan">react-router.Route.propTypes.</span>children ()](#apidoc.element.react-router.Route.propTypes.children)
1.  [function <span class="apidocSignatureSpan">react-router.Route.propTypes.</span>component ()](#apidoc.element.react-router.Route.propTypes.component)
1.  [function <span class="apidocSignatureSpan">react-router.Route.propTypes.</span>computedMatch ()](#apidoc.element.react-router.Route.propTypes.computedMatch)
1.  [function <span class="apidocSignatureSpan">react-router.Route.propTypes.</span>exact ()](#apidoc.element.react-router.Route.propTypes.exact)
1.  [function <span class="apidocSignatureSpan">react-router.Route.propTypes.</span>location ()](#apidoc.element.react-router.Route.propTypes.location)
1.  [function <span class="apidocSignatureSpan">react-router.Route.propTypes.</span>path ()](#apidoc.element.react-router.Route.propTypes.path)
1.  [function <span class="apidocSignatureSpan">react-router.Route.propTypes.</span>render ()](#apidoc.element.react-router.Route.propTypes.render)
1.  [function <span class="apidocSignatureSpan">react-router.Route.propTypes.</span>strict ()](#apidoc.element.react-router.Route.propTypes.strict)

#### [module react-router.Route.prototype](#apidoc.module.react-router.Route.prototype)
1.  [function <span class="apidocSignatureSpan">react-router.Route.prototype.</span>componentWillMount ()](#apidoc.element.react-router.Route.prototype.componentWillMount)
1.  [function <span class="apidocSignatureSpan">react-router.Route.prototype.</span>componentWillReceiveProps (nextProps, nextContext)](#apidoc.element.react-router.Route.prototype.componentWillReceiveProps)
1.  [function <span class="apidocSignatureSpan">react-router.Route.prototype.</span>computeMatch (_ref, _ref2)](#apidoc.element.react-router.Route.prototype.computeMatch)
1.  [function <span class="apidocSignatureSpan">react-router.Route.prototype.</span>getChildContext ()](#apidoc.element.react-router.Route.prototype.getChildContext)
1.  [function <span class="apidocSignatureSpan">react-router.Route.prototype.</span>render ()](#apidoc.element.react-router.Route.prototype.render)

#### [module react-router.Router](#apidoc.module.react-router.Router)
1.  [function <span class="apidocSignatureSpan">react-router.</span>Router ()](#apidoc.element.react-router.Router.Router)
1.  object <span class="apidocSignatureSpan">react-router.Router.</span>childContextTypes
1.  object <span class="apidocSignatureSpan">react-router.Router.</span>contextTypes
1.  object <span class="apidocSignatureSpan">react-router.Router.</span>propTypes

#### [module react-router.Router.childContextTypes](#apidoc.module.react-router.Router.childContextTypes)
1.  [function <span class="apidocSignatureSpan">react-router.Router.childContextTypes.</span>router ()](#apidoc.element.react-router.Router.childContextTypes.router)

#### [module react-router.Router.contextTypes](#apidoc.module.react-router.Router.contextTypes)
1.  [function <span class="apidocSignatureSpan">react-router.Router.contextTypes.</span>router ()](#apidoc.element.react-router.Router.contextTypes.router)

#### [module react-router.Router.propTypes](#apidoc.module.react-router.Router.propTypes)
1.  [function <span class="apidocSignatureSpan">react-router.Router.propTypes.</span>children ()](#apidoc.element.react-router.Router.propTypes.children)
1.  [function <span class="apidocSignatureSpan">react-router.Router.propTypes.</span>history ()](#apidoc.element.react-router.Router.propTypes.history)

#### [module react-router.Router.prototype](#apidoc.module.react-router.Router.prototype)
1.  [function <span class="apidocSignatureSpan">react-router.Router.prototype.</span>componentWillMount ()](#apidoc.element.react-router.Router.prototype.componentWillMount)
1.  [function <span class="apidocSignatureSpan">react-router.Router.prototype.</span>componentWillReceiveProps (nextProps)](#apidoc.element.react-router.Router.prototype.componentWillReceiveProps)
1.  [function <span class="apidocSignatureSpan">react-router.Router.prototype.</span>componentWillUnmount ()](#apidoc.element.react-router.Router.prototype.componentWillUnmount)
1.  [function <span class="apidocSignatureSpan">react-router.Router.prototype.</span>computeMatch (pathname)](#apidoc.element.react-router.Router.prototype.computeMatch)
1.  [function <span class="apidocSignatureSpan">react-router.Router.prototype.</span>getChildContext ()](#apidoc.element.react-router.Router.prototype.getChildContext)
1.  [function <span class="apidocSignatureSpan">react-router.Router.prototype.</span>render ()](#apidoc.element.react-router.Router.prototype.render)

#### [module react-router.StaticRouter](#apidoc.module.react-router.StaticRouter)
1.  [function <span class="apidocSignatureSpan">react-router.</span>StaticRouter ()](#apidoc.element.react-router.StaticRouter.StaticRouter)
1.  object <span class="apidocSignatureSpan">react-router.StaticRouter.</span>childContextTypes
1.  object <span class="apidocSignatureSpan">react-router.StaticRouter.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-router.StaticRouter.</span>propTypes

#### [module react-router.StaticRouter.childContextTypes](#apidoc.module.react-router.StaticRouter.childContextTypes)
1.  [function <span class="apidocSignatureSpan">react-router.StaticRouter.childContextTypes.</span>router ()](#apidoc.element.react-router.StaticRouter.childContextTypes.router)

#### [module react-router.StaticRouter.propTypes](#apidoc.module.react-router.StaticRouter.propTypes)
1.  [function <span class="apidocSignatureSpan">react-router.StaticRouter.propTypes.</span>basename ()](#apidoc.element.react-router.StaticRouter.propTypes.basename)
1.  [function <span class="apidocSignatureSpan">react-router.StaticRouter.propTypes.</span>context ()](#apidoc.element.react-router.StaticRouter.propTypes.context)
1.  [function <span class="apidocSignatureSpan">react-router.StaticRouter.propTypes.</span>location ()](#apidoc.element.react-router.StaticRouter.propTypes.location)

#### [module react-router.StaticRouter.prototype](#apidoc.module.react-router.StaticRouter.prototype)
1.  [function <span class="apidocSignatureSpan">react-router.StaticRouter.prototype.</span>getChildContext ()](#apidoc.element.react-router.StaticRouter.prototype.getChildContext)
1.  [function <span class="apidocSignatureSpan">react-router.StaticRouter.prototype.</span>render ()](#apidoc.element.react-router.StaticRouter.prototype.render)

#### [module react-router.Switch](#apidoc.module.react-router.Switch)
1.  [function <span class="apidocSignatureSpan">react-router.</span>Switch ()](#apidoc.element.react-router.Switch.Switch)
1.  object <span class="apidocSignatureSpan">react-router.Switch.</span>contextTypes
1.  object <span class="apidocSignatureSpan">react-router.Switch.</span>propTypes

#### [module react-router.Switch.contextTypes](#apidoc.module.react-router.Switch.contextTypes)
1.  [function <span class="apidocSignatureSpan">react-router.Switch.contextTypes.</span>router ()](#apidoc.element.react-router.Switch.contextTypes.router)

#### [module react-router.Switch.propTypes](#apidoc.module.react-router.Switch.propTypes)
1.  [function <span class="apidocSignatureSpan">react-router.Switch.propTypes.</span>children ()](#apidoc.element.react-router.Switch.propTypes.children)
1.  [function <span class="apidocSignatureSpan">react-router.Switch.propTypes.</span>location ()](#apidoc.element.react-router.Switch.propTypes.location)

#### [module react-router.Switch.prototype](#apidoc.module.react-router.Switch.prototype)
1.  [function <span class="apidocSignatureSpan">react-router.Switch.prototype.</span>componentWillReceiveProps (nextProps)](#apidoc.element.react-router.Switch.prototype.componentWillReceiveProps)
1.  [function <span class="apidocSignatureSpan">react-router.Switch.prototype.</span>render ()](#apidoc.element.react-router.Switch.prototype.render)



# <a name="apidoc.module.react-router"></a>[module react-router](#apidoc.module.react-router)

#### <a name="apidoc.element.react-router.MemoryRouter"></a>[function <span class="apidocSignatureSpan">react-router.</span>MemoryRouter ()](#apidoc.element.react-router.MemoryRouter)
- description and source-code
```javascript
function MemoryRouter() {
  var _temp, _this, _ret;

  _classCallCheck(this, MemoryRouter);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = _possibleConstructorReturn(this, _React$Component.call.apply(_React$Component, [this].concat(args
))), _this), _this.history = (0, _createMemoryHistory2.default)(_this.props), _temp), _possibleConstructorReturn(_this, _ret);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router.Prompt"></a>[function <span class="apidocSignatureSpan">react-router.</span>Prompt ()](#apidoc.element.react-router.Prompt)
- description and source-code
```javascript
function Prompt() {
  _classCallCheck(this, Prompt);

  return _possibleConstructorReturn(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router.Redirect"></a>[function <span class="apidocSignatureSpan">react-router.</span>Redirect ()](#apidoc.element.react-router.Redirect)
- description and source-code
```javascript
function Redirect() {
  _classCallCheck(this, Redirect);

  return _possibleConstructorReturn(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router.Route"></a>[function <span class="apidocSignatureSpan">react-router.</span>Route ()](#apidoc.element.react-router.Route)
- description and source-code
```javascript
function Route() {
  var _temp, _this, _ret;

  _classCallCheck(this, Route);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = _possibleConstructorReturn(this, _React$Component.call.apply(_React$Component, [this].concat(args
))), _this), _this.state = {
    match: _this.computeMatch(_this.props, _this.context.router)
  }, _temp), _possibleConstructorReturn(_this, _ret);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router.Router"></a>[function <span class="apidocSignatureSpan">react-router.</span>Router ()](#apidoc.element.react-router.Router)
- description and source-code
```javascript
function Router() {
  var _temp, _this, _ret;

  _classCallCheck(this, Router);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = _possibleConstructorReturn(this, _React$Component.call.apply(_React$Component, [this].concat(args
))), _this), _this.state = {
    match: _this.computeMatch(_this.props.history.location.pathname)
  }, _temp), _possibleConstructorReturn(_this, _ret);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router.StaticRouter"></a>[function <span class="apidocSignatureSpan">react-router.</span>StaticRouter ()](#apidoc.element.react-router.StaticRouter)
- description and source-code
```javascript
function StaticRouter() {
  var _temp, _this, _ret;

  _classCallCheck(this, StaticRouter);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = _possibleConstructorReturn(this, _React$Component.call.apply(_React$Component, [this].concat(args
))), _this), _this.createHref = function (path) {
    return (0, _PathUtils.addLeadingSlash)(_this.props.basename + createURL(path));
  }, _this.handlePush = function (location) {
    var _this$props = _this.props,
        basename = _this$props.basename,
        context = _this$props.context;

    context.action = 'PUSH';
    context.location = addBasename(basename, createLocation(location));
    context.url = createURL(context.location);
  }, _this.handleReplace = function (location) {
    var _this$props2 = _this.props,
        basename = _this$props2.basename,
        context = _this$props2.context;

    context.action = 'REPLACE';
    context.location = addBasename(basename, createLocation(location));
    context.url = createURL(context.location);
  }, _this.handleListen = function () {
    return noop;
  }, _this.handleBlock = function () {
    return noop;
  }, _temp), _possibleConstructorReturn(_this, _ret);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router.Switch"></a>[function <span class="apidocSignatureSpan">react-router.</span>Switch ()](#apidoc.element.react-router.Switch)
- description and source-code
```javascript
function Switch() {
  _classCallCheck(this, Switch);

  return _possibleConstructorReturn(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router.matchPath"></a>[function <span class="apidocSignatureSpan">react-router.</span>matchPath (pathname)](#apidoc.element.react-router.matchPath)
- description and source-code
```javascript
function matchPath(pathname) {
  var options = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : {};

  if (typeof options === 'string') options = { path: options };

  var _options = options,
      _options$path = _options.path,
      path = _options$path === undefined ? '/' : _options$path,
      _options$exact = _options.exact,
      exact = _options$exact === undefined ? false : _options$exact,
      _options$strict = _options.strict,
      strict = _options$strict === undefined ? false : _options$strict;

  var _compilePath = compilePath(path, { end: exact, strict: strict }),
      re = _compilePath.re,
      keys = _compilePath.keys;

  var match = re.exec(pathname);

  if (!match) return null;

  var url = match[0],
      values = match.slice(1);

  var isExact = pathname === url;

  if (exact && !isExact) return null;

  return {
    path: path, // the path pattern used to match
    url: path === '/' && url === '' ? '/' : url, // the matched portion of the URL
    isExact: isExact, // whether or not we matched exactly
    params: keys.reduce(function (memo, key, index) {
      memo[key.name] = values[index];
      return memo;
    }, {})
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router.withRouter"></a>[function <span class="apidocSignatureSpan">react-router.</span>withRouter (Component)](#apidoc.element.react-router.withRouter)
- description and source-code
```javascript
function withRouter(Component) {
  var C = function C(props) {
    return _react2.default.createElement(_Route2.default, { render: function render(routeComponentProps) {
        return _react2.default.createElement(Component, _extends({}, props, routeComponentProps));
      } });
  };

  C.displayName = 'withRouter(' + (Component.displayName || Component.name) + ')';

  return C;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-router.MemoryRouter"></a>[module react-router.MemoryRouter](#apidoc.module.react-router.MemoryRouter)

#### <a name="apidoc.element.react-router.MemoryRouter.MemoryRouter"></a>[function <span class="apidocSignatureSpan">react-router.</span>MemoryRouter ()](#apidoc.element.react-router.MemoryRouter.MemoryRouter)
- description and source-code
```javascript
function MemoryRouter() {
  var _temp, _this, _ret;

  _classCallCheck(this, MemoryRouter);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = _possibleConstructorReturn(this, _React$Component.call.apply(_React$Component, [this].concat(args
))), _this), _this.history = (0, _createMemoryHistory2.default)(_this.props), _temp), _possibleConstructorReturn(_this, _ret);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-router.MemoryRouter.propTypes"></a>[module react-router.MemoryRouter.propTypes](#apidoc.module.react-router.MemoryRouter.propTypes)

#### <a name="apidoc.element.react-router.MemoryRouter.propTypes.children"></a>[function <span class="apidocSignatureSpan">react-router.MemoryRouter.propTypes.</span>children ()](#apidoc.element.react-router.MemoryRouter.propTypes.children)
- description and source-code
```javascript
children = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router.MemoryRouter.propTypes.getUserConfirmation"></a>[function <span class="apidocSignatureSpan">react-router.MemoryRouter.propTypes.</span>getUserConfirmation ()](#apidoc.element.react-router.MemoryRouter.propTypes.getUserConfirmation)
- description and source-code
```javascript
getUserConfirmation = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router.MemoryRouter.propTypes.initialEntries"></a>[function <span class="apidocSignatureSpan">react-router.MemoryRouter.propTypes.</span>initialEntries ()](#apidoc.element.react-router.MemoryRouter.propTypes.initialEntries)
- description and source-code
```javascript
initialEntries = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router.MemoryRouter.propTypes.initialIndex"></a>[function <span class="apidocSignatureSpan">react-router.MemoryRouter.propTypes.</span>initialIndex ()](#apidoc.element.react-router.MemoryRouter.propTypes.initialIndex)
- description and source-code
```javascript
initialIndex = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router.MemoryRouter.propTypes.keyLength"></a>[function <span class="apidocSignatureSpan">react-router.MemoryRouter.propTypes.</span>keyLength ()](#apidoc.element.react-router.MemoryRouter.propTypes.keyLength)
- description and source-code
```javascript
keyLength = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-router.MemoryRouter.prototype"></a>[module react-router.MemoryRouter.prototype](#apidoc.module.react-router.MemoryRouter.prototype)

#### <a name="apidoc.element.react-router.MemoryRouter.prototype.render"></a>[function <span class="apidocSignatureSpan">react-router.MemoryRouter.prototype.</span>render ()](#apidoc.element.react-router.MemoryRouter.prototype.render)
- description and source-code
```javascript
function render() {
  return _react2.default.createElement(_Router2.default, { history: this.history, children: this.props.children });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-router.Prompt"></a>[module react-router.Prompt](#apidoc.module.react-router.Prompt)

#### <a name="apidoc.element.react-router.Prompt.Prompt"></a>[function <span class="apidocSignatureSpan">react-router.</span>Prompt ()](#apidoc.element.react-router.Prompt.Prompt)
- description and source-code
```javascript
function Prompt() {
  _classCallCheck(this, Prompt);

  return _possibleConstructorReturn(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-router.Prompt.contextTypes"></a>[module react-router.Prompt.contextTypes](#apidoc.module.react-router.Prompt.contextTypes)

#### <a name="apidoc.element.react-router.Prompt.contextTypes.router"></a>[function <span class="apidocSignatureSpan">react-router.Prompt.contextTypes.</span>router ()](#apidoc.element.react-router.Prompt.contextTypes.router)
- description and source-code
```javascript
router = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-router.Prompt.propTypes"></a>[module react-router.Prompt.propTypes](#apidoc.module.react-router.Prompt.propTypes)

#### <a name="apidoc.element.react-router.Prompt.propTypes.message"></a>[function <span class="apidocSignatureSpan">react-router.Prompt.propTypes.</span>message ()](#apidoc.element.react-router.Prompt.propTypes.message)
- description and source-code
```javascript
message = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router.Prompt.propTypes.when"></a>[function <span class="apidocSignatureSpan">react-router.Prompt.propTypes.</span>when ()](#apidoc.element.react-router.Prompt.propTypes.when)
- description and source-code
```javascript
when = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-router.Prompt.prototype"></a>[module react-router.Prompt.prototype](#apidoc.module.react-router.Prompt.prototype)

#### <a name="apidoc.element.react-router.Prompt.prototype.componentWillMount"></a>[function <span class="apidocSignatureSpan">react-router.Prompt.prototype.</span>componentWillMount ()](#apidoc.element.react-router.Prompt.prototype.componentWillMount)
- description and source-code
```javascript
function componentWillMount() {
  if (this.props.when) this.enable(this.props.message);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router.Prompt.prototype.componentWillReceiveProps"></a>[function <span class="apidocSignatureSpan">react-router.Prompt.prototype.</span>componentWillReceiveProps (nextProps)](#apidoc.element.react-router.Prompt.prototype.componentWillReceiveProps)
- description and source-code
```javascript
function componentWillReceiveProps(nextProps) {
  if (nextProps.when) {
    if (!this.props.when || this.props.message !== nextProps.message) this.enable(nextProps.message);
  } else {
    this.disable();
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router.Prompt.prototype.componentWillUnmount"></a>[function <span class="apidocSignatureSpan">react-router.Prompt.prototype.</span>componentWillUnmount ()](#apidoc.element.react-router.Prompt.prototype.componentWillUnmount)
- description and source-code
```javascript
function componentWillUnmount() {
  this.disable();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router.Prompt.prototype.disable"></a>[function <span class="apidocSignatureSpan">react-router.Prompt.prototype.</span>disable ()](#apidoc.element.react-router.Prompt.prototype.disable)
- description and source-code
```javascript
function disable() {
  if (this.unblock) {
    this.unblock();
    this.unblock = null;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router.Prompt.prototype.enable"></a>[function <span class="apidocSignatureSpan">react-router.Prompt.prototype.</span>enable (message)](#apidoc.element.react-router.Prompt.prototype.enable)
- description and source-code
```javascript
function enable(message) {
  if (this.unblock) this.unblock();

  this.unblock = this.context.router.history.block(message);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router.Prompt.prototype.render"></a>[function <span class="apidocSignatureSpan">react-router.Prompt.prototype.</span>render ()](#apidoc.element.react-router.Prompt.prototype.render)
- description and source-code
```javascript
function render() {
  return null;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-router.Redirect"></a>[module react-router.Redirect](#apidoc.module.react-router.Redirect)

#### <a name="apidoc.element.react-router.Redirect.Redirect"></a>[function <span class="apidocSignatureSpan">react-router.</span>Redirect ()](#apidoc.element.react-router.Redirect.Redirect)
- description and source-code
```javascript
function Redirect() {
  _classCallCheck(this, Redirect);

  return _possibleConstructorReturn(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-router.Redirect.contextTypes"></a>[module react-router.Redirect.contextTypes](#apidoc.module.react-router.Redirect.contextTypes)

#### <a name="apidoc.element.react-router.Redirect.contextTypes.router"></a>[function <span class="apidocSignatureSpan">react-router.Redirect.contextTypes.</span>router ()](#apidoc.element.react-router.Redirect.contextTypes.router)
- description and source-code
```javascript
router = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-router.Redirect.propTypes"></a>[module react-router.Redirect.propTypes](#apidoc.module.react-router.Redirect.propTypes)

#### <a name="apidoc.element.react-router.Redirect.propTypes.from"></a>[function <span class="apidocSignatureSpan">react-router.Redirect.propTypes.</span>from ()](#apidoc.element.react-router.Redirect.propTypes.from)
- description and source-code
```javascript
from = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router.Redirect.propTypes.push"></a>[function <span class="apidocSignatureSpan">react-router.Redirect.propTypes.</span>push ()](#apidoc.element.react-router.Redirect.propTypes.push)
- description and source-code
```javascript
push = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router.Redirect.propTypes.to"></a>[function <span class="apidocSignatureSpan">react-router.Redirect.propTypes.</span>to ()](#apidoc.element.react-router.Redirect.propTypes.to)
- description and source-code
```javascript
to = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-router.Redirect.prototype"></a>[module react-router.Redirect.prototype](#apidoc.module.react-router.Redirect.prototype)

#### <a name="apidoc.element.react-router.Redirect.prototype.componentDidMount"></a>[function <span class="apidocSignatureSpan">react-router.Redirect.prototype.</span>componentDidMount ()](#apidoc.element.react-router.Redirect.prototype.componentDidMount)
- description and source-code
```javascript
function componentDidMount() {
  if (!this.isStatic()) this.perform();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router.Redirect.prototype.componentWillMount"></a>[function <span class="apidocSignatureSpan">react-router.Redirect.prototype.</span>componentWillMount ()](#apidoc.element.react-router.Redirect.prototype.componentWillMount)
- description and source-code
```javascript
function componentWillMount() {
  if (this.isStatic()) this.perform();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router.Redirect.prototype.isStatic"></a>[function <span class="apidocSignatureSpan">react-router.Redirect.prototype.</span>isStatic ()](#apidoc.element.react-router.Redirect.prototype.isStatic)
- description and source-code
```javascript
function isStatic() {
  return this.context.router && this.context.router.staticContext;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router.Redirect.prototype.perform"></a>[function <span class="apidocSignatureSpan">react-router.Redirect.prototype.</span>perform ()](#apidoc.element.react-router.Redirect.prototype.perform)
- description and source-code
```javascript
function perform() {
  var history = this.context.router.history;
  var _props = this.props,
      push = _props.push,
      to = _props.to;


  if (push) {
    history.push(to);
  } else {
    history.replace(to);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router.Redirect.prototype.render"></a>[function <span class="apidocSignatureSpan">react-router.Redirect.prototype.</span>render ()](#apidoc.element.react-router.Redirect.prototype.render)
- description and source-code
```javascript
function render() {
  return null;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-router.Route"></a>[module react-router.Route](#apidoc.module.react-router.Route)

#### <a name="apidoc.element.react-router.Route.Route"></a>[function <span class="apidocSignatureSpan">react-router.</span>Route ()](#apidoc.element.react-router.Route.Route)
- description and source-code
```javascript
function Route() {
  var _temp, _this, _ret;

  _classCallCheck(this, Route);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = _possibleConstructorReturn(this, _React$Component.call.apply(_React$Component, [this].concat(args
))), _this), _this.state = {
    match: _this.computeMatch(_this.props, _this.context.router)
  }, _temp), _possibleConstructorReturn(_this, _ret);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-router.Route.childContextTypes"></a>[module react-router.Route.childContextTypes](#apidoc.module.react-router.Route.childContextTypes)

#### <a name="apidoc.element.react-router.Route.childContextTypes.router"></a>[function <span class="apidocSignatureSpan">react-router.Route.childContextTypes.</span>router ()](#apidoc.element.react-router.Route.childContextTypes.router)
- description and source-code
```javascript
router = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-router.Route.contextTypes"></a>[module react-router.Route.contextTypes](#apidoc.module.react-router.Route.contextTypes)

#### <a name="apidoc.element.react-router.Route.contextTypes.router"></a>[function <span class="apidocSignatureSpan">react-router.Route.contextTypes.</span>router ()](#apidoc.element.react-router.Route.contextTypes.router)
- description and source-code
```javascript
router = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-router.Route.propTypes"></a>[module react-router.Route.propTypes](#apidoc.module.react-router.Route.propTypes)

#### <a name="apidoc.element.react-router.Route.propTypes.children"></a>[function <span class="apidocSignatureSpan">react-router.Route.propTypes.</span>children ()](#apidoc.element.react-router.Route.propTypes.children)
- description and source-code
```javascript
children = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router.Route.propTypes.component"></a>[function <span class="apidocSignatureSpan">react-router.Route.propTypes.</span>component ()](#apidoc.element.react-router.Route.propTypes.component)
- description and source-code
```javascript
component = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router.Route.propTypes.computedMatch"></a>[function <span class="apidocSignatureSpan">react-router.Route.propTypes.</span>computedMatch ()](#apidoc.element.react-router.Route.propTypes.computedMatch)
- description and source-code
```javascript
computedMatch = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router.Route.propTypes.exact"></a>[function <span class="apidocSignatureSpan">react-router.Route.propTypes.</span>exact ()](#apidoc.element.react-router.Route.propTypes.exact)
- description and source-code
```javascript
exact = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router.Route.propTypes.location"></a>[function <span class="apidocSignatureSpan">react-router.Route.propTypes.</span>location ()](#apidoc.element.react-router.Route.propTypes.location)
- description and source-code
```javascript
location = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router.Route.propTypes.path"></a>[function <span class="apidocSignatureSpan">react-router.Route.propTypes.</span>path ()](#apidoc.element.react-router.Route.propTypes.path)
- description and source-code
```javascript
path = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router.Route.propTypes.render"></a>[function <span class="apidocSignatureSpan">react-router.Route.propTypes.</span>render ()](#apidoc.element.react-router.Route.propTypes.render)
- description and source-code
```javascript
render = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router.Route.propTypes.strict"></a>[function <span class="apidocSignatureSpan">react-router.Route.propTypes.</span>strict ()](#apidoc.element.react-router.Route.propTypes.strict)
- description and source-code
```javascript
strict = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-router.Route.prototype"></a>[module react-router.Route.prototype](#apidoc.module.react-router.Route.prototype)

#### <a name="apidoc.element.react-router.Route.prototype.componentWillMount"></a>[function <span class="apidocSignatureSpan">react-router.Route.prototype.</span>componentWillMount ()](#apidoc.element.react-router.Route.prototype.componentWillMount)
- description and source-code
```javascript
function componentWillMount() {
  var _props = this.props,
      component = _props.component,
      render = _props.render,
      children = _props.children;


  (0, _warning2.default)(!(component && render), 'You should not use <Route component> and <Route render> in the same route; <Route
 render> will be ignored');

  (0, _warning2.default)(!(component && children), 'You should not use <Route component> and <Route children> in the same route; <
Route children> will be ignored');

  (0, _warning2.default)(!(render && children), 'You should not use <Route render> and <Route children> in the same route; <Route
 children> will be ignored');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router.Route.prototype.componentWillReceiveProps"></a>[function <span class="apidocSignatureSpan">react-router.Route.prototype.</span>componentWillReceiveProps (nextProps, nextContext)](#apidoc.element.react-router.Route.prototype.componentWillReceiveProps)
- description and source-code
```javascript
function componentWillReceiveProps(nextProps, nextContext) {
  (0, _warning2.default)(!(nextProps.location && !this.props.location), '<Route> elements should not change from uncontrolled to
 controlled (or vice versa). You initially used no "location" prop and then provided one on a subsequent render.');

  (0, _warning2.default)(!(!nextProps.location && this.props.location), '<Route> elements should not change from controlled to uncontrolled
 (or vice versa). You provided a "location" prop initially but omitted it on a subsequent render.');

  this.setState({
    match: this.computeMatch(nextProps, nextContext.router)
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router.Route.prototype.computeMatch"></a>[function <span class="apidocSignatureSpan">react-router.Route.prototype.</span>computeMatch (_ref, _ref2)](#apidoc.element.react-router.Route.prototype.computeMatch)
- description and source-code
```javascript
function computeMatch(_ref, _ref2) {
  var computedMatch = _ref.computedMatch,
      location = _ref.location,
      path = _ref.path,
      strict = _ref.strict,
      exact = _ref.exact;
  var route = _ref2.route;

  if (computedMatch) return computedMatch; // <Switch> already computed the match for us

  var pathname = (location || route.location).pathname;

  return path ? (0, _matchPath2.default)(pathname, { path: path, strict: strict, exact: exact }) : route.match;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router.Route.prototype.getChildContext"></a>[function <span class="apidocSignatureSpan">react-router.Route.prototype.</span>getChildContext ()](#apidoc.element.react-router.Route.prototype.getChildContext)
- description and source-code
```javascript
function getChildContext() {
  var router = this.context.router;

  return {
    router: _extends({}, this.context.router, {
      route: {
        location: this.props.location || this.context.router.route.location,
        match: this.state.match
      }
    })
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router.Route.prototype.render"></a>[function <span class="apidocSignatureSpan">react-router.Route.prototype.</span>render ()](#apidoc.element.react-router.Route.prototype.render)
- description and source-code
```javascript
function render() {
  var match = this.state.match;
  var _props2 = this.props,
      children = _props2.children,
      component = _props2.component,
      render = _props2.render;
  var _context$router = this.context.router,
      history = _context$router.history,
      route = _context$router.route,
      staticContext = _context$router.staticContext;

  var location = this.props.location || route.location;
  var props = { match: match, location: location, history: history, staticContext: staticContext };

  return component ? // component prop gets first priority, only called if there's a match
  match ? _react2.default.createElement(component, props) : null : render ? // render prop is next, only called if there's a match
  match ? render(props) : null : children ? // children come last, always called
  typeof children === 'function' ? children(props) : !Array.isArray(children) || children.length ? // Preact defaults to empty children
 array
  _react2.default.Children.only(children) : null : null;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-router.Router"></a>[module react-router.Router](#apidoc.module.react-router.Router)

#### <a name="apidoc.element.react-router.Router.Router"></a>[function <span class="apidocSignatureSpan">react-router.</span>Router ()](#apidoc.element.react-router.Router.Router)
- description and source-code
```javascript
function Router() {
  var _temp, _this, _ret;

  _classCallCheck(this, Router);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = _possibleConstructorReturn(this, _React$Component.call.apply(_React$Component, [this].concat(args
))), _this), _this.state = {
    match: _this.computeMatch(_this.props.history.location.pathname)
  }, _temp), _possibleConstructorReturn(_this, _ret);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-router.Router.childContextTypes"></a>[module react-router.Router.childContextTypes](#apidoc.module.react-router.Router.childContextTypes)

#### <a name="apidoc.element.react-router.Router.childContextTypes.router"></a>[function <span class="apidocSignatureSpan">react-router.Router.childContextTypes.</span>router ()](#apidoc.element.react-router.Router.childContextTypes.router)
- description and source-code
```javascript
router = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-router.Router.contextTypes"></a>[module react-router.Router.contextTypes](#apidoc.module.react-router.Router.contextTypes)

#### <a name="apidoc.element.react-router.Router.contextTypes.router"></a>[function <span class="apidocSignatureSpan">react-router.Router.contextTypes.</span>router ()](#apidoc.element.react-router.Router.contextTypes.router)
- description and source-code
```javascript
router = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-router.Router.propTypes"></a>[module react-router.Router.propTypes](#apidoc.module.react-router.Router.propTypes)

#### <a name="apidoc.element.react-router.Router.propTypes.children"></a>[function <span class="apidocSignatureSpan">react-router.Router.propTypes.</span>children ()](#apidoc.element.react-router.Router.propTypes.children)
- description and source-code
```javascript
children = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router.Router.propTypes.history"></a>[function <span class="apidocSignatureSpan">react-router.Router.propTypes.</span>history ()](#apidoc.element.react-router.Router.propTypes.history)
- description and source-code
```javascript
history = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-router.Router.prototype"></a>[module react-router.Router.prototype](#apidoc.module.react-router.Router.prototype)

#### <a name="apidoc.element.react-router.Router.prototype.componentWillMount"></a>[function <span class="apidocSignatureSpan">react-router.Router.prototype.</span>componentWillMount ()](#apidoc.element.react-router.Router.prototype.componentWillMount)
- description and source-code
```javascript
function componentWillMount() {
  var _this2 = this;

  var _props = this.props,
      children = _props.children,
      history = _props.history;


  (0, _invariant2.default)(children == null || _react2.default.Children.count(children) === 1, 'A <Router> may have only one child
 element');

  // Do this here so we can setState when a <Redirect> changes the
  // location in componentWillMount. This happens e.g. when doing
  // server rendering using a <StaticRouter>.
  this.unlisten = history.listen(function () {
    _this2.setState({
      match: _this2.computeMatch(history.location.pathname)
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router.Router.prototype.componentWillReceiveProps"></a>[function <span class="apidocSignatureSpan">react-router.Router.prototype.</span>componentWillReceiveProps (nextProps)](#apidoc.element.react-router.Router.prototype.componentWillReceiveProps)
- description and source-code
```javascript
function componentWillReceiveProps(nextProps) {
  (0, _warning2.default)(this.props.history === nextProps.history, 'You cannot change <Router history>');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router.Router.prototype.componentWillUnmount"></a>[function <span class="apidocSignatureSpan">react-router.Router.prototype.</span>componentWillUnmount ()](#apidoc.element.react-router.Router.prototype.componentWillUnmount)
- description and source-code
```javascript
function componentWillUnmount() {
  this.unlisten();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router.Router.prototype.computeMatch"></a>[function <span class="apidocSignatureSpan">react-router.Router.prototype.</span>computeMatch (pathname)](#apidoc.element.react-router.Router.prototype.computeMatch)
- description and source-code
```javascript
function computeMatch(pathname) {
  return {
    path: '/',
    url: '/',
    params: {},
    isExact: pathname === '/'
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router.Router.prototype.getChildContext"></a>[function <span class="apidocSignatureSpan">react-router.Router.prototype.</span>getChildContext ()](#apidoc.element.react-router.Router.prototype.getChildContext)
- description and source-code
```javascript
function getChildContext() {
  return {
    router: _extends({}, this.context.router, {
      history: this.props.history,
      route: {
        location: this.props.history.location,
        match: this.state.match
      }
    })
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router.Router.prototype.render"></a>[function <span class="apidocSignatureSpan">react-router.Router.prototype.</span>render ()](#apidoc.element.react-router.Router.prototype.render)
- description and source-code
```javascript
function render() {
  var children = this.props.children;

  return children ? _react2.default.Children.only(children) : null;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-router.StaticRouter"></a>[module react-router.StaticRouter](#apidoc.module.react-router.StaticRouter)

#### <a name="apidoc.element.react-router.StaticRouter.StaticRouter"></a>[function <span class="apidocSignatureSpan">react-router.</span>StaticRouter ()](#apidoc.element.react-router.StaticRouter.StaticRouter)
- description and source-code
```javascript
function StaticRouter() {
  var _temp, _this, _ret;

  _classCallCheck(this, StaticRouter);

  for (var _len = arguments.length, args = Array(_len), _key = 0; _key < _len; _key++) {
    args[_key] = arguments[_key];
  }

  return _ret = (_temp = (_this = _possibleConstructorReturn(this, _React$Component.call.apply(_React$Component, [this].concat(args
))), _this), _this.createHref = function (path) {
    return (0, _PathUtils.addLeadingSlash)(_this.props.basename + createURL(path));
  }, _this.handlePush = function (location) {
    var _this$props = _this.props,
        basename = _this$props.basename,
        context = _this$props.context;

    context.action = 'PUSH';
    context.location = addBasename(basename, createLocation(location));
    context.url = createURL(context.location);
  }, _this.handleReplace = function (location) {
    var _this$props2 = _this.props,
        basename = _this$props2.basename,
        context = _this$props2.context;

    context.action = 'REPLACE';
    context.location = addBasename(basename, createLocation(location));
    context.url = createURL(context.location);
  }, _this.handleListen = function () {
    return noop;
  }, _this.handleBlock = function () {
    return noop;
  }, _temp), _possibleConstructorReturn(_this, _ret);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-router.StaticRouter.childContextTypes"></a>[module react-router.StaticRouter.childContextTypes](#apidoc.module.react-router.StaticRouter.childContextTypes)

#### <a name="apidoc.element.react-router.StaticRouter.childContextTypes.router"></a>[function <span class="apidocSignatureSpan">react-router.StaticRouter.childContextTypes.</span>router ()](#apidoc.element.react-router.StaticRouter.childContextTypes.router)
- description and source-code
```javascript
router = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-router.StaticRouter.propTypes"></a>[module react-router.StaticRouter.propTypes](#apidoc.module.react-router.StaticRouter.propTypes)

#### <a name="apidoc.element.react-router.StaticRouter.propTypes.basename"></a>[function <span class="apidocSignatureSpan">react-router.StaticRouter.propTypes.</span>basename ()](#apidoc.element.react-router.StaticRouter.propTypes.basename)
- description and source-code
```javascript
basename = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router.StaticRouter.propTypes.context"></a>[function <span class="apidocSignatureSpan">react-router.StaticRouter.propTypes.</span>context ()](#apidoc.element.react-router.StaticRouter.propTypes.context)
- description and source-code
```javascript
context = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router.StaticRouter.propTypes.location"></a>[function <span class="apidocSignatureSpan">react-router.StaticRouter.propTypes.</span>location ()](#apidoc.element.react-router.StaticRouter.propTypes.location)
- description and source-code
```javascript
location = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-router.StaticRouter.prototype"></a>[module react-router.StaticRouter.prototype](#apidoc.module.react-router.StaticRouter.prototype)

#### <a name="apidoc.element.react-router.StaticRouter.prototype.getChildContext"></a>[function <span class="apidocSignatureSpan">react-router.StaticRouter.prototype.</span>getChildContext ()](#apidoc.element.react-router.StaticRouter.prototype.getChildContext)
- description and source-code
```javascript
function getChildContext() {
  return {
    router: {
      staticContext: this.props.context
    }
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router.StaticRouter.prototype.render"></a>[function <span class="apidocSignatureSpan">react-router.StaticRouter.prototype.</span>render ()](#apidoc.element.react-router.StaticRouter.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props,
      basename = _props.basename,
      context = _props.context,
      location = _props.location,
      props = _objectWithoutProperties(_props, ['basename', 'context', 'location']);

  var history = {
    createHref: this.createHref,
    action: 'POP',
    location: stripBasename(basename, createLocation(location)),
    push: this.handlePush,
    replace: this.handleReplace,
    go: staticHandler('go'),
    goBack: staticHandler('goBack'),
    goForward: staticHandler('goForward'),
    listen: this.handleListen,
    block: this.handleBlock
  };

  return _react2.default.createElement(_Router2.default, _extends({}, props, { history: history }));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-router.Switch"></a>[module react-router.Switch](#apidoc.module.react-router.Switch)

#### <a name="apidoc.element.react-router.Switch.Switch"></a>[function <span class="apidocSignatureSpan">react-router.</span>Switch ()](#apidoc.element.react-router.Switch.Switch)
- description and source-code
```javascript
function Switch() {
  _classCallCheck(this, Switch);

  return _possibleConstructorReturn(this, _React$Component.apply(this, arguments));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-router.Switch.contextTypes"></a>[module react-router.Switch.contextTypes](#apidoc.module.react-router.Switch.contextTypes)

#### <a name="apidoc.element.react-router.Switch.contextTypes.router"></a>[function <span class="apidocSignatureSpan">react-router.Switch.contextTypes.</span>router ()](#apidoc.element.react-router.Switch.contextTypes.router)
- description and source-code
```javascript
router = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-router.Switch.propTypes"></a>[module react-router.Switch.propTypes](#apidoc.module.react-router.Switch.propTypes)

#### <a name="apidoc.element.react-router.Switch.propTypes.children"></a>[function <span class="apidocSignatureSpan">react-router.Switch.propTypes.</span>children ()](#apidoc.element.react-router.Switch.propTypes.children)
- description and source-code
```javascript
children = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router.Switch.propTypes.location"></a>[function <span class="apidocSignatureSpan">react-router.Switch.propTypes.</span>location ()](#apidoc.element.react-router.Switch.propTypes.location)
- description and source-code
```javascript
location = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-router.Switch.prototype"></a>[module react-router.Switch.prototype](#apidoc.module.react-router.Switch.prototype)

#### <a name="apidoc.element.react-router.Switch.prototype.componentWillReceiveProps"></a>[function <span class="apidocSignatureSpan">react-router.Switch.prototype.</span>componentWillReceiveProps (nextProps)](#apidoc.element.react-router.Switch.prototype.componentWillReceiveProps)
- description and source-code
```javascript
function componentWillReceiveProps(nextProps) {
  (0, _warning2.default)(!(nextProps.location && !this.props.location), '<Switch> elements should not change from uncontrolled to
 controlled (or vice versa). You initially used no "location" prop and then provided one on a subsequent render.');

  (0, _warning2.default)(!(!nextProps.location && this.props.location), '<Switch> elements should not change from controlled to
uncontrolled (or vice versa). You provided a "location" prop initially but omitted it on a subsequent render.');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-router.Switch.prototype.render"></a>[function <span class="apidocSignatureSpan">react-router.Switch.prototype.</span>render ()](#apidoc.element.react-router.Switch.prototype.render)
- description and source-code
```javascript
function render() {
  var route = this.context.router.route;
  var children = this.props.children;

  var location = this.props.location || route.location;

  var match = void 0,
      child = void 0;
  _react2.default.Children.forEach(children, function (element) {
    var _element$props = element.props,
        pathProp = _element$props.path,
        exact = _element$props.exact,
        strict = _element$props.strict,
        from = _element$props.from;

    var path = pathProp || from;

    if (match == null) {
      child = element;
      match = path ? (0, _matchPath2.default)(location.pathname, { path: path, exact: exact, strict: strict }) : route.match;
    }
  });

  return match ? _react2.default.cloneElement(child, { location: location, computedMatch: match }) : null;
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
