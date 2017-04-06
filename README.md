# api documentation for  [formsy-react (v0.19.2)](https://github.com/christianalfoni/formsy-react#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-formsy-react.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-formsy-react) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-formsy-react.svg)](https://travis-ci.org/npmdoc/node-npmdoc-formsy-react)
#### A form input builder and validator for React JS

[![NPM](https://nodei.co/npm/formsy-react.png?downloads=true)](https://www.npmjs.com/package/formsy-react)

[![apidoc](https://npmdoc.github.io/node-npmdoc-formsy-react/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-formsy-react_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-formsy-react/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-formsy-react/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-formsy-react/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Christian Alfoni"
    },
    "bugs": {
        "url": "https://github.com/christianalfoni/formsy-react/issues"
    },
    "dependencies": {
        "form-data-to-object": "^0.2.0"
    },
    "description": "A form input builder and validator for React JS",
    "devDependencies": {
        "babel-cli": "^6.6.5",
        "babel-loader": "^6.2.4",
        "babel-preset-es2015": "^6.6.0",
        "babel-preset-react": "^6.5.0",
        "babel-preset-stage-2": "^6.5.0",
        "jsdom": "^6.5.1",
        "nodeunit": "^0.9.1",
        "react": "^15.0.0",
        "react-addons-pure-render-mixin": "^15.0.0",
        "react-addons-test-utils": "^15.0.0",
        "react-dom": "^15.0.0",
        "sinon": "^1.17.3",
        "webpack": "^1.12.14",
        "webpack-dev-server": "^1.14.1"
    },
    "directories": {},
    "dist": {
        "shasum": "7fa818ff93c8c07195486c4d2e42b6da0c0ee4a3",
        "tarball": "https://registry.npmjs.org/formsy-react/-/formsy-react-0.19.2.tgz"
    },
    "gitHead": "0628d9787954d93111f7e47286ccb3f5afa5e00e",
    "homepage": "https://github.com/christianalfoni/formsy-react#readme",
    "keywords": [
        "react",
        "form",
        "forms",
        "validation",
        "react-component"
    ],
    "license": "MIT",
    "main": "lib/main.js",
    "maintainers": [
        {
            "name": "aesopwolf",
            "email": "aesopwolf@gmail.com"
        },
        {
            "name": "christianalfoni",
            "email": "christianalfoni@gmail.com"
        },
        {
            "name": "semigradsky",
            "email": "semigradskyd@gmail.com"
        }
    ],
    "name": "formsy-react",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": "^0.14.0 || ^15.0.0"
    },
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/christianalfoni/formsy-react.git"
    },
    "scripts": {
        "deploy": "NODE_ENV=production webpack -p --config webpack.production.config.js",
        "examples": "webpack-dev-server --config examples/webpack.config.js --content-base examples",
        "prepublish": "babel ./src/ -d ./lib/",
        "test": "babel-node testrunner"
    },
    "version": "0.19.2"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module formsy-react](#apidoc.module.formsy-react)
1.  [function <span class="apidocSignatureSpan">formsy-react.</span>Decorator ()](#apidoc.element.formsy-react.Decorator)
1.  [function <span class="apidocSignatureSpan">formsy-react.</span>Form (props, context, updater)](#apidoc.element.formsy-react.Form)
1.  [function <span class="apidocSignatureSpan">formsy-react.</span>HOC (Component)](#apidoc.element.formsy-react.HOC)
1.  [function <span class="apidocSignatureSpan">formsy-react.</span>addValidationRule (name, func)](#apidoc.element.formsy-react.addValidationRule)
1.  [function <span class="apidocSignatureSpan">formsy-react.</span>defaults (passedOptions)](#apidoc.element.formsy-react.defaults)
1.  object <span class="apidocSignatureSpan">formsy-react.</span>Form.childContextTypes
1.  object <span class="apidocSignatureSpan">formsy-react.</span>Form.defaultProps
1.  object <span class="apidocSignatureSpan">formsy-react.</span>Form.prototype
1.  object <span class="apidocSignatureSpan">formsy-react.</span>Form.prototype.__reactAutoBindMap
1.  object <span class="apidocSignatureSpan">formsy-react.</span>Mixin
1.  object <span class="apidocSignatureSpan">formsy-react.</span>Mixin.contextTypes
1.  object <span class="apidocSignatureSpan">formsy-react.</span>utils
1.  object <span class="apidocSignatureSpan">formsy-react.</span>validationRules

#### [module formsy-react.Form](#apidoc.module.formsy-react.Form)
1.  [function <span class="apidocSignatureSpan">formsy-react.</span>Form (props, context, updater)](#apidoc.element.formsy-react.Form.Form)
1.  [function <span class="apidocSignatureSpan">formsy-react.Form.</span>getDefaultProps ()](#apidoc.element.formsy-react.Form.getDefaultProps)
1.  object <span class="apidocSignatureSpan">formsy-react.Form.</span>childContextTypes
1.  object <span class="apidocSignatureSpan">formsy-react.Form.</span>defaultProps
1.  string <span class="apidocSignatureSpan">formsy-react.Form.</span>displayName

#### [module formsy-react.Form.childContextTypes](#apidoc.module.formsy-react.Form.childContextTypes)
1.  [function <span class="apidocSignatureSpan">formsy-react.Form.childContextTypes.</span>formsy ()](#apidoc.element.formsy-react.Form.childContextTypes.formsy)

#### [module formsy-react.Form.defaultProps](#apidoc.module.formsy-react.Form.defaultProps)
1.  boolean <span class="apidocSignatureSpan">formsy-react.Form.defaultProps.</span>preventExternalInvalidation
1.  [function <span class="apidocSignatureSpan">formsy-react.Form.defaultProps.</span>onChange ()](#apidoc.element.formsy-react.Form.defaultProps.onChange)
1.  [function <span class="apidocSignatureSpan">formsy-react.Form.defaultProps.</span>onError ()](#apidoc.element.formsy-react.Form.defaultProps.onError)
1.  [function <span class="apidocSignatureSpan">formsy-react.Form.defaultProps.</span>onInvalid ()](#apidoc.element.formsy-react.Form.defaultProps.onInvalid)
1.  [function <span class="apidocSignatureSpan">formsy-react.Form.defaultProps.</span>onInvalidSubmit ()](#apidoc.element.formsy-react.Form.defaultProps.onInvalidSubmit)
1.  [function <span class="apidocSignatureSpan">formsy-react.Form.defaultProps.</span>onSubmit ()](#apidoc.element.formsy-react.Form.defaultProps.onSubmit)
1.  [function <span class="apidocSignatureSpan">formsy-react.Form.defaultProps.</span>onSuccess ()](#apidoc.element.formsy-react.Form.defaultProps.onSuccess)
1.  [function <span class="apidocSignatureSpan">formsy-react.Form.defaultProps.</span>onValid ()](#apidoc.element.formsy-react.Form.defaultProps.onValid)
1.  [function <span class="apidocSignatureSpan">formsy-react.Form.defaultProps.</span>onValidSubmit ()](#apidoc.element.formsy-react.Form.defaultProps.onValidSubmit)
1.  object <span class="apidocSignatureSpan">formsy-react.Form.defaultProps.</span>validationErrors

#### [module formsy-react.Form.prototype](#apidoc.module.formsy-react.Form.prototype)
1.  [function <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>attachToForm (component)](#apidoc.element.formsy-react.Form.prototype.attachToForm)
1.  [function <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>componentDidMount ()](#apidoc.element.formsy-react.Form.prototype.componentDidMount)
1.  [function <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>componentDidUpdate ()](#apidoc.element.formsy-react.Form.prototype.componentDidUpdate)
1.  [function <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>componentWillMount ()](#apidoc.element.formsy-react.Form.prototype.componentWillMount)
1.  [function <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>componentWillUpdate ()](#apidoc.element.formsy-react.Form.prototype.componentWillUpdate)
1.  [function <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>constructor (props, context, updater)](#apidoc.element.formsy-react.Form.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>detachFromForm (component)](#apidoc.element.formsy-react.Form.prototype.detachFromForm)
1.  [function <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>getChildContext ()](#apidoc.element.formsy-react.Form.prototype.getChildContext)
1.  [function <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>getCurrentValues ()](#apidoc.element.formsy-react.Form.prototype.getCurrentValues)
1.  [function <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>getDOMNode ()](#apidoc.element.formsy-react.Form.prototype.getDOMNode)
1.  [function <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>getInitialState ()](#apidoc.element.formsy-react.Form.prototype.getInitialState)
1.  [function <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>getModel ()](#apidoc.element.formsy-react.Form.prototype.getModel)
1.  [function <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>getPristineValues ()](#apidoc.element.formsy-react.Form.prototype.getPristineValues)
1.  [function <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>isChanged ()](#apidoc.element.formsy-react.Form.prototype.isChanged)
1.  [function <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>isFormDisabled ()](#apidoc.element.formsy-react.Form.prototype.isFormDisabled)
1.  [function <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>mapModel (model)](#apidoc.element.formsy-react.Form.prototype.mapModel)
1.  [function <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>render ()](#apidoc.element.formsy-react.Form.prototype.render)
1.  [function <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>reset (data)](#apidoc.element.formsy-react.Form.prototype.reset)
1.  [function <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>resetModel (data)](#apidoc.element.formsy-react.Form.prototype.resetModel)
1.  [function <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>runRules (value, currentValues, validations)](#apidoc.element.formsy-react.Form.prototype.runRules)
1.  [function <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>runValidation (component, value)](#apidoc.element.formsy-react.Form.prototype.runValidation)
1.  [function <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>setFormPristine (isPristine)](#apidoc.element.formsy-react.Form.prototype.setFormPristine)
1.  [function <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>setInputValidationErrors (errors)](#apidoc.element.formsy-react.Form.prototype.setInputValidationErrors)
1.  [function <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>submit (event)](#apidoc.element.formsy-react.Form.prototype.submit)
1.  [function <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>updateInputsWithError (errors)](#apidoc.element.formsy-react.Form.prototype.updateInputsWithError)
1.  [function <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>validate (component)](#apidoc.element.formsy-react.Form.prototype.validate)
1.  [function <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>validateForm ()](#apidoc.element.formsy-react.Form.prototype.validateForm)
1.  object <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>__reactAutoBindMap
1.  object <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>childContextTypes
1.  object <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>componentWillReceiveProps
1.  object <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>componentWillUnmount
1.  object <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>contextTypes
1.  object <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>getDefaultProps
1.  object <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>mixins
1.  object <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>propTypes
1.  object <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>shouldComponentUpdate
1.  object <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>statics
1.  object <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>updateComponent

#### [module formsy-react.Form.prototype.__reactAutoBindMap](#apidoc.module.formsy-react.Form.prototype.__reactAutoBindMap)
1.  [function <span class="apidocSignatureSpan">formsy-react.Form.prototype.__reactAutoBindMap.</span>attachToForm (component)](#apidoc.element.formsy-react.Form.prototype.__reactAutoBindMap.attachToForm)
1.  [function <span class="apidocSignatureSpan">formsy-react.Form.prototype.__reactAutoBindMap.</span>detachFromForm (component)](#apidoc.element.formsy-react.Form.prototype.__reactAutoBindMap.detachFromForm)
1.  [function <span class="apidocSignatureSpan">formsy-react.Form.prototype.__reactAutoBindMap.</span>getCurrentValues ()](#apidoc.element.formsy-react.Form.prototype.__reactAutoBindMap.getCurrentValues)
1.  [function <span class="apidocSignatureSpan">formsy-react.Form.prototype.__reactAutoBindMap.</span>getDOMNode ()](#apidoc.element.formsy-react.Form.prototype.__reactAutoBindMap.getDOMNode)
1.  [function <span class="apidocSignatureSpan">formsy-react.Form.prototype.__reactAutoBindMap.</span>getModel ()](#apidoc.element.formsy-react.Form.prototype.__reactAutoBindMap.getModel)
1.  [function <span class="apidocSignatureSpan">formsy-react.Form.prototype.__reactAutoBindMap.</span>getPristineValues ()](#apidoc.element.formsy-react.Form.prototype.__reactAutoBindMap.getPristineValues)
1.  [function <span class="apidocSignatureSpan">formsy-react.Form.prototype.__reactAutoBindMap.</span>isChanged ()](#apidoc.element.formsy-react.Form.prototype.__reactAutoBindMap.isChanged)
1.  [function <span class="apidocSignatureSpan">formsy-react.Form.prototype.__reactAutoBindMap.</span>isFormDisabled ()](#apidoc.element.formsy-react.Form.prototype.__reactAutoBindMap.isFormDisabled)
1.  [function <span class="apidocSignatureSpan">formsy-react.Form.prototype.__reactAutoBindMap.</span>mapModel (model)](#apidoc.element.formsy-react.Form.prototype.__reactAutoBindMap.mapModel)
1.  [function <span class="apidocSignatureSpan">formsy-react.Form.prototype.__reactAutoBindMap.</span>reset (data)](#apidoc.element.formsy-react.Form.prototype.__reactAutoBindMap.reset)
1.  [function <span class="apidocSignatureSpan">formsy-react.Form.prototype.__reactAutoBindMap.</span>resetModel (data)](#apidoc.element.formsy-react.Form.prototype.__reactAutoBindMap.resetModel)
1.  [function <span class="apidocSignatureSpan">formsy-react.Form.prototype.__reactAutoBindMap.</span>runRules (value, currentValues, validations)](#apidoc.element.formsy-react.Form.prototype.__reactAutoBindMap.runRules)
1.  [function <span class="apidocSignatureSpan">formsy-react.Form.prototype.__reactAutoBindMap.</span>runValidation (component, value)](#apidoc.element.formsy-react.Form.prototype.__reactAutoBindMap.runValidation)
1.  [function <span class="apidocSignatureSpan">formsy-react.Form.prototype.__reactAutoBindMap.</span>setFormPristine (isPristine)](#apidoc.element.formsy-react.Form.prototype.__reactAutoBindMap.setFormPristine)
1.  [function <span class="apidocSignatureSpan">formsy-react.Form.prototype.__reactAutoBindMap.</span>setInputValidationErrors (errors)](#apidoc.element.formsy-react.Form.prototype.__reactAutoBindMap.setInputValidationErrors)
1.  [function <span class="apidocSignatureSpan">formsy-react.Form.prototype.__reactAutoBindMap.</span>submit (event)](#apidoc.element.formsy-react.Form.prototype.__reactAutoBindMap.submit)
1.  [function <span class="apidocSignatureSpan">formsy-react.Form.prototype.__reactAutoBindMap.</span>updateInputsWithError (errors)](#apidoc.element.formsy-react.Form.prototype.__reactAutoBindMap.updateInputsWithError)
1.  [function <span class="apidocSignatureSpan">formsy-react.Form.prototype.__reactAutoBindMap.</span>validate (component)](#apidoc.element.formsy-react.Form.prototype.__reactAutoBindMap.validate)
1.  [function <span class="apidocSignatureSpan">formsy-react.Form.prototype.__reactAutoBindMap.</span>validateForm ()](#apidoc.element.formsy-react.Form.prototype.__reactAutoBindMap.validateForm)

#### [module formsy-react.Mixin](#apidoc.module.formsy-react.Mixin)
1.  [function <span class="apidocSignatureSpan">formsy-react.Mixin.</span>componentDidUpdate (prevProps)](#apidoc.element.formsy-react.Mixin.componentDidUpdate)
1.  [function <span class="apidocSignatureSpan">formsy-react.Mixin.</span>componentWillMount ()](#apidoc.element.formsy-react.Mixin.componentWillMount)
1.  [function <span class="apidocSignatureSpan">formsy-react.Mixin.</span>componentWillReceiveProps (nextProps)](#apidoc.element.formsy-react.Mixin.componentWillReceiveProps)
1.  [function <span class="apidocSignatureSpan">formsy-react.Mixin.</span>componentWillUnmount ()](#apidoc.element.formsy-react.Mixin.componentWillUnmount)
1.  [function <span class="apidocSignatureSpan">formsy-react.Mixin.</span>getDefaultProps ()](#apidoc.element.formsy-react.Mixin.getDefaultProps)
1.  [function <span class="apidocSignatureSpan">formsy-react.Mixin.</span>getErrorMessage ()](#apidoc.element.formsy-react.Mixin.getErrorMessage)
1.  [function <span class="apidocSignatureSpan">formsy-react.Mixin.</span>getErrorMessages ()](#apidoc.element.formsy-react.Mixin.getErrorMessages)
1.  [function <span class="apidocSignatureSpan">formsy-react.Mixin.</span>getInitialState ()](#apidoc.element.formsy-react.Mixin.getInitialState)
1.  [function <span class="apidocSignatureSpan">formsy-react.Mixin.</span>getValue ()](#apidoc.element.formsy-react.Mixin.getValue)
1.  [function <span class="apidocSignatureSpan">formsy-react.Mixin.</span>hasValue ()](#apidoc.element.formsy-react.Mixin.hasValue)
1.  [function <span class="apidocSignatureSpan">formsy-react.Mixin.</span>isFormDisabled ()](#apidoc.element.formsy-react.Mixin.isFormDisabled)
1.  [function <span class="apidocSignatureSpan">formsy-react.Mixin.</span>isFormSubmitted ()](#apidoc.element.formsy-react.Mixin.isFormSubmitted)
1.  [function <span class="apidocSignatureSpan">formsy-react.Mixin.</span>isPristine ()](#apidoc.element.formsy-react.Mixin.isPristine)
1.  [function <span class="apidocSignatureSpan">formsy-react.Mixin.</span>isRequired ()](#apidoc.element.formsy-react.Mixin.isRequired)
1.  [function <span class="apidocSignatureSpan">formsy-react.Mixin.</span>isValid ()](#apidoc.element.formsy-react.Mixin.isValid)
1.  [function <span class="apidocSignatureSpan">formsy-react.Mixin.</span>isValidValue (value)](#apidoc.element.formsy-react.Mixin.isValidValue)
1.  [function <span class="apidocSignatureSpan">formsy-react.Mixin.</span>resetValue ()](#apidoc.element.formsy-react.Mixin.resetValue)
1.  [function <span class="apidocSignatureSpan">formsy-react.Mixin.</span>setValidations (validations, required)](#apidoc.element.formsy-react.Mixin.setValidations)
1.  [function <span class="apidocSignatureSpan">formsy-react.Mixin.</span>setValue (value)](#apidoc.element.formsy-react.Mixin.setValue)
1.  [function <span class="apidocSignatureSpan">formsy-react.Mixin.</span>showError ()](#apidoc.element.formsy-react.Mixin.showError)
1.  [function <span class="apidocSignatureSpan">formsy-react.Mixin.</span>showRequired ()](#apidoc.element.formsy-react.Mixin.showRequired)
1.  object <span class="apidocSignatureSpan">formsy-react.Mixin.</span>contextTypes

#### [module formsy-react.Mixin.contextTypes](#apidoc.module.formsy-react.Mixin.contextTypes)
1.  [function <span class="apidocSignatureSpan">formsy-react.Mixin.contextTypes.</span>formsy ()](#apidoc.element.formsy-react.Mixin.contextTypes.formsy)

#### [module formsy-react.utils](#apidoc.module.formsy-react.utils)
1.  [function <span class="apidocSignatureSpan">formsy-react.utils.</span>arraysDiffer (a, b)](#apidoc.element.formsy-react.utils.arraysDiffer)
1.  [function <span class="apidocSignatureSpan">formsy-react.utils.</span>find (collection, fn)](#apidoc.element.formsy-react.utils.find)
1.  [function <span class="apidocSignatureSpan">formsy-react.utils.</span>isSame (a, b)](#apidoc.element.formsy-react.utils.isSame)
1.  [function <span class="apidocSignatureSpan">formsy-react.utils.</span>objectsDiffer (a, b)](#apidoc.element.formsy-react.utils.objectsDiffer)

#### [module formsy-react.validationRules](#apidoc.module.formsy-react.validationRules)
1.  [function <span class="apidocSignatureSpan">formsy-react.validationRules.</span>equals (values, value, eql)](#apidoc.element.formsy-react.validationRules.equals)
1.  [function <span class="apidocSignatureSpan">formsy-react.validationRules.</span>equalsField (values, value, field)](#apidoc.element.formsy-react.validationRules.equalsField)
1.  [function <span class="apidocSignatureSpan">formsy-react.validationRules.</span>isAlpha (values, value)](#apidoc.element.formsy-react.validationRules.isAlpha)
1.  [function <span class="apidocSignatureSpan">formsy-react.validationRules.</span>isAlphanumeric (values, value)](#apidoc.element.formsy-react.validationRules.isAlphanumeric)
1.  [function <span class="apidocSignatureSpan">formsy-react.validationRules.</span>isDefaultRequiredValue (values, value)](#apidoc.element.formsy-react.validationRules.isDefaultRequiredValue)
1.  [function <span class="apidocSignatureSpan">formsy-react.validationRules.</span>isEmail (values, value)](#apidoc.element.formsy-react.validationRules.isEmail)
1.  [function <span class="apidocSignatureSpan">formsy-react.validationRules.</span>isEmptyString (values, value)](#apidoc.element.formsy-react.validationRules.isEmptyString)
1.  [function <span class="apidocSignatureSpan">formsy-react.validationRules.</span>isExisty (values, value)](#apidoc.element.formsy-react.validationRules.isExisty)
1.  [function <span class="apidocSignatureSpan">formsy-react.validationRules.</span>isFalse (values, value)](#apidoc.element.formsy-react.validationRules.isFalse)
1.  [function <span class="apidocSignatureSpan">formsy-react.validationRules.</span>isFloat (values, value)](#apidoc.element.formsy-react.validationRules.isFloat)
1.  [function <span class="apidocSignatureSpan">formsy-react.validationRules.</span>isInt (values, value)](#apidoc.element.formsy-react.validationRules.isInt)
1.  [function <span class="apidocSignatureSpan">formsy-react.validationRules.</span>isLength (values, value, length)](#apidoc.element.formsy-react.validationRules.isLength)
1.  [function <span class="apidocSignatureSpan">formsy-react.validationRules.</span>isNumeric (values, value)](#apidoc.element.formsy-react.validationRules.isNumeric)
1.  [function <span class="apidocSignatureSpan">formsy-react.validationRules.</span>isSpecialWords (values, value)](#apidoc.element.formsy-react.validationRules.isSpecialWords)
1.  [function <span class="apidocSignatureSpan">formsy-react.validationRules.</span>isTrue (values, value)](#apidoc.element.formsy-react.validationRules.isTrue)
1.  [function <span class="apidocSignatureSpan">formsy-react.validationRules.</span>isUndefined (values, value)](#apidoc.element.formsy-react.validationRules.isUndefined)
1.  [function <span class="apidocSignatureSpan">formsy-react.validationRules.</span>isUrl (values, value)](#apidoc.element.formsy-react.validationRules.isUrl)
1.  [function <span class="apidocSignatureSpan">formsy-react.validationRules.</span>isWords (values, value)](#apidoc.element.formsy-react.validationRules.isWords)
1.  [function <span class="apidocSignatureSpan">formsy-react.validationRules.</span>matchRegexp (values, value, regexp)](#apidoc.element.formsy-react.validationRules.matchRegexp)
1.  [function <span class="apidocSignatureSpan">formsy-react.validationRules.</span>maxLength (values, value, length)](#apidoc.element.formsy-react.validationRules.maxLength)
1.  [function <span class="apidocSignatureSpan">formsy-react.validationRules.</span>minLength (values, value, length)](#apidoc.element.formsy-react.validationRules.minLength)



# <a name="apidoc.module.formsy-react"></a>[module formsy-react](#apidoc.module.formsy-react)

#### <a name="apidoc.element.formsy-react.Decorator"></a>[function <span class="apidocSignatureSpan">formsy-react.</span>Decorator ()](#apidoc.element.formsy-react.Decorator)
- description and source-code
```javascript
Decorator = function () {
  return function (Component) {
    return React.createClass({
      mixins: [Mixin],
      render: function render() {
        return React.createElement(Component, _extends({
          setValidations: this.setValidations,
          setValue: this.setValue,
          resetValue: this.resetValue,
          getValue: this.getValue,
          hasValue: this.hasValue,
          getErrorMessage: this.getErrorMessage,
          getErrorMessages: this.getErrorMessages,
          isFormDisabled: this.isFormDisabled,
          isValid: this.isValid,
          isPristine: this.isPristine,
          isFormSubmitted: this.isFormSubmitted,
          isRequired: this.isRequired,
          showRequired: this.showRequired,
          showError: this.showError,
          isValidValue: this.isValidValue
        }, this.props));
      }
    });
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.Form"></a>[function <span class="apidocSignatureSpan">formsy-react.</span>Form (props, context, updater)](#apidoc.element.formsy-react.Form)
- description and source-code
```javascript
Form = function (props, context, updater) {
  // This constructor is overridden by mocks. The argument is used
  // by mocks to assert on what gets mounted.

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(this instanceof Constructor, 'Something is calling a React component directly
. Use a factory or ' + 'JSX instead. See: https://fb.me/react-legacyfactory') : undefined;
  }

  // Wire up auto-binding
  if (this.__reactAutoBindMap) {
    bindAutoBindMethods(this);
  }

  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  this.updater = updater || ReactNoopUpdateQueue;

  this.state = null;

  // ReactClasses doesn't have constructors. Instead, they use the
  // getInitialState and componentWillMount methods for initialization.

  var initialState = this.getInitialState ? this.getInitialState() : null;
  if (process.env.NODE_ENV !== 'production') {
    // We allow auto-mocks to proceed as if they're returning null.
    if (typeof initialState === 'undefined' && this.getInitialState._isMockFunction) {
      // This is probably bad practice. Consider warning here and
      // deprecating this convenience.
      initialState = null;
    }
  }
  !(typeof initialState === 'object' && !Array.isArray(initialState)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '%
s.getInitialState(): must return an object or null', Constructor.displayName || 'ReactCompositeComponent') : invariant(false) :
undefined;

  this.state = initialState;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.HOC"></a>[function <span class="apidocSignatureSpan">formsy-react.</span>HOC (Component)](#apidoc.element.formsy-react.HOC)
- description and source-code
```javascript
HOC = function (Component) {
  return React.createClass({
    displayName: 'Formsy(' + getDisplayName(Component) + ')',
    mixins: [Mixin],

    render: function render() {
      var innerRef = this.props.innerRef;

      var propsForElement = _extends({
        setValidations: this.setValidations,
        setValue: this.setValue,
        resetValue: this.resetValue,
        getValue: this.getValue,
        hasValue: this.hasValue,
        getErrorMessage: this.getErrorMessage,
        getErrorMessages: this.getErrorMessages,
        isFormDisabled: this.isFormDisabled,
        isValid: this.isValid,
        isPristine: this.isPristine,
        isFormSubmitted: this.isFormSubmitted,
        isRequired: this.isRequired,
        showRequired: this.showRequired,
        showError: this.showError,
        isValidValue: this.isValidValue
      }, this.props);

      if (innerRef) {
        propsForElement.ref = innerRef;
      }
      return React.createElement(Component, propsForElement);
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.addValidationRule"></a>[function <span class="apidocSignatureSpan">formsy-react.</span>addValidationRule (name, func)](#apidoc.element.formsy-react.addValidationRule)
- description and source-code
```javascript
addValidationRule = function (name, func) {
  validationRules[name] = func;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.defaults"></a>[function <span class="apidocSignatureSpan">formsy-react.</span>defaults (passedOptions)](#apidoc.element.formsy-react.defaults)
- description and source-code
```javascript
defaults = function (passedOptions) {
  options = passedOptions;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.formsy-react.Form"></a>[module formsy-react.Form](#apidoc.module.formsy-react.Form)

#### <a name="apidoc.element.formsy-react.Form.Form"></a>[function <span class="apidocSignatureSpan">formsy-react.</span>Form (props, context, updater)](#apidoc.element.formsy-react.Form.Form)
- description and source-code
```javascript
Form = function (props, context, updater) {
  // This constructor is overridden by mocks. The argument is used
  // by mocks to assert on what gets mounted.

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(this instanceof Constructor, 'Something is calling a React component directly
. Use a factory or ' + 'JSX instead. See: https://fb.me/react-legacyfactory') : undefined;
  }

  // Wire up auto-binding
  if (this.__reactAutoBindMap) {
    bindAutoBindMethods(this);
  }

  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  this.updater = updater || ReactNoopUpdateQueue;

  this.state = null;

  // ReactClasses doesn't have constructors. Instead, they use the
  // getInitialState and componentWillMount methods for initialization.

  var initialState = this.getInitialState ? this.getInitialState() : null;
  if (process.env.NODE_ENV !== 'production') {
    // We allow auto-mocks to proceed as if they're returning null.
    if (typeof initialState === 'undefined' && this.getInitialState._isMockFunction) {
      // This is probably bad practice. Consider warning here and
      // deprecating this convenience.
      initialState = null;
    }
  }
  !(typeof initialState === 'object' && !Array.isArray(initialState)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '%
s.getInitialState(): must return an object or null', Constructor.displayName || 'ReactCompositeComponent') : invariant(false) :
undefined;

  this.state = initialState;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.Form.getDefaultProps"></a>[function <span class="apidocSignatureSpan">formsy-react.Form.</span>getDefaultProps ()](#apidoc.element.formsy-react.Form.getDefaultProps)
- description and source-code
```javascript
function getDefaultProps() {
  return {
    onSuccess: function onSuccess() {},
    onError: function onError() {},
    onSubmit: function onSubmit() {},
    onValidSubmit: function onValidSubmit() {},
    onInvalidSubmit: function onInvalidSubmit() {},
    onValid: function onValid() {},
    onInvalid: function onInvalid() {},
    onChange: function onChange() {},
    validationErrors: null,
    preventExternalInvalidation: false
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.formsy-react.Form.childContextTypes"></a>[module formsy-react.Form.childContextTypes](#apidoc.module.formsy-react.Form.childContextTypes)

#### <a name="apidoc.element.formsy-react.Form.childContextTypes.formsy"></a>[function <span class="apidocSignatureSpan">formsy-react.Form.childContextTypes.</span>formsy ()](#apidoc.element.formsy-react.Form.childContextTypes.formsy)
- description and source-code
```javascript
formsy = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.formsy-react.Form.defaultProps"></a>[module formsy-react.Form.defaultProps](#apidoc.module.formsy-react.Form.defaultProps)

#### <a name="apidoc.element.formsy-react.Form.defaultProps.onChange"></a>[function <span class="apidocSignatureSpan">formsy-react.Form.defaultProps.</span>onChange ()](#apidoc.element.formsy-react.Form.defaultProps.onChange)
- description and source-code
```javascript
function onChange() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.Form.defaultProps.onError"></a>[function <span class="apidocSignatureSpan">formsy-react.Form.defaultProps.</span>onError ()](#apidoc.element.formsy-react.Form.defaultProps.onError)
- description and source-code
```javascript
function onError() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.Form.defaultProps.onInvalid"></a>[function <span class="apidocSignatureSpan">formsy-react.Form.defaultProps.</span>onInvalid ()](#apidoc.element.formsy-react.Form.defaultProps.onInvalid)
- description and source-code
```javascript
function onInvalid() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.Form.defaultProps.onInvalidSubmit"></a>[function <span class="apidocSignatureSpan">formsy-react.Form.defaultProps.</span>onInvalidSubmit ()](#apidoc.element.formsy-react.Form.defaultProps.onInvalidSubmit)
- description and source-code
```javascript
function onInvalidSubmit() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.Form.defaultProps.onSubmit"></a>[function <span class="apidocSignatureSpan">formsy-react.Form.defaultProps.</span>onSubmit ()](#apidoc.element.formsy-react.Form.defaultProps.onSubmit)
- description and source-code
```javascript
function onSubmit() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.Form.defaultProps.onSuccess"></a>[function <span class="apidocSignatureSpan">formsy-react.Form.defaultProps.</span>onSuccess ()](#apidoc.element.formsy-react.Form.defaultProps.onSuccess)
- description and source-code
```javascript
function onSuccess() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.Form.defaultProps.onValid"></a>[function <span class="apidocSignatureSpan">formsy-react.Form.defaultProps.</span>onValid ()](#apidoc.element.formsy-react.Form.defaultProps.onValid)
- description and source-code
```javascript
function onValid() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.Form.defaultProps.onValidSubmit"></a>[function <span class="apidocSignatureSpan">formsy-react.Form.defaultProps.</span>onValidSubmit ()](#apidoc.element.formsy-react.Form.defaultProps.onValidSubmit)
- description and source-code
```javascript
function onValidSubmit() {}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.formsy-react.Form.prototype"></a>[module formsy-react.Form.prototype](#apidoc.module.formsy-react.Form.prototype)

#### <a name="apidoc.element.formsy-react.Form.prototype.attachToForm"></a>[function <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>attachToForm (component)](#apidoc.element.formsy-react.Form.prototype.attachToForm)
- description and source-code
```javascript
function attachToForm(component) {

  if (this.inputs.indexOf(component) === -1) {
    this.inputs.push(component);
  }

  this.validate(component);
}
```
- example usage
```shell
...
  },

  componentWillMount: function () {
var configure = function () {
  this.setValidations(this.props.validations, this.props.required);

  // Pass a function instead?
  this.context.formsy.attachToForm(this);
  //this.props._attachToForm(this);
}.bind(this);

if (!this.props.name) {
  throw new Error('Form Input requires a name property when used');
}
...
```

#### <a name="apidoc.element.formsy-react.Form.prototype.componentDidMount"></a>[function <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>componentDidMount ()](#apidoc.element.formsy-react.Form.prototype.componentDidMount)
- description and source-code
```javascript
function componentDidMount() {
  this.validateForm();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.Form.prototype.componentDidUpdate"></a>[function <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>componentDidUpdate ()](#apidoc.element.formsy-react.Form.prototype.componentDidUpdate)
- description and source-code
```javascript
function componentDidUpdate() {

  if (this.props.validationErrors && _typeof(this.props.validationErrors) === 'object' && Object.keys(this.props.validationErrors
).length > 0) {
    this.setInputValidationErrors(this.props.validationErrors);
  }

  var newInputNames = this.inputs.map(function (component) {
    return component.props.name;
  });
  if (utils.arraysDiffer(this.prevInputNames, newInputNames)) {
    this.validateForm();
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.Form.prototype.componentWillMount"></a>[function <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>componentWillMount ()](#apidoc.element.formsy-react.Form.prototype.componentWillMount)
- description and source-code
```javascript
function componentWillMount() {
  this.inputs = [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.Form.prototype.componentWillUpdate"></a>[function <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>componentWillUpdate ()](#apidoc.element.formsy-react.Form.prototype.componentWillUpdate)
- description and source-code
```javascript
function componentWillUpdate() {
  // Keep a reference to input names before form updates,
  // to check if inputs has changed after render
  this.prevInputNames = this.inputs.map(function (component) {
    return component.props.name;
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.Form.prototype.constructor"></a>[function <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>constructor (props, context, updater)](#apidoc.element.formsy-react.Form.prototype.constructor)
- description and source-code
```javascript
constructor = function (props, context, updater) {
  // This constructor is overridden by mocks. The argument is used
  // by mocks to assert on what gets mounted.

  if (process.env.NODE_ENV !== 'production') {
    process.env.NODE_ENV !== 'production' ? warning(this instanceof Constructor, 'Something is calling a React component directly
. Use a factory or ' + 'JSX instead. See: https://fb.me/react-legacyfactory') : undefined;
  }

  // Wire up auto-binding
  if (this.__reactAutoBindMap) {
    bindAutoBindMethods(this);
  }

  this.props = props;
  this.context = context;
  this.refs = emptyObject;
  this.updater = updater || ReactNoopUpdateQueue;

  this.state = null;

  // ReactClasses doesn't have constructors. Instead, they use the
  // getInitialState and componentWillMount methods for initialization.

  var initialState = this.getInitialState ? this.getInitialState() : null;
  if (process.env.NODE_ENV !== 'production') {
    // We allow auto-mocks to proceed as if they're returning null.
    if (typeof initialState === 'undefined' && this.getInitialState._isMockFunction) {
      // This is probably bad practice. Consider warning here and
      // deprecating this convenience.
      initialState = null;
    }
  }
  !(typeof initialState === 'object' && !Array.isArray(initialState)) ? process.env.NODE_ENV !== 'production' ? invariant(false, '%
s.getInitialState(): must return an object or null', Constructor.displayName || 'ReactCompositeComponent') : invariant(false) :
undefined;

  this.state = initialState;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.Form.prototype.detachFromForm"></a>[function <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>detachFromForm (component)](#apidoc.element.formsy-react.Form.prototype.detachFromForm)
- description and source-code
```javascript
function detachFromForm(component) {
  var componentPos = this.inputs.indexOf(component);

  if (componentPos !== -1) {
    this.inputs = this.inputs.slice(0, componentPos).concat(this.inputs.slice(componentPos + 1));
  }

  this.validateForm();
}
```
- example usage
```shell
...
if (!utils.isSame(this.props.validations, prevProps.validations) || !utils.isSame(this.props.required, prevProps.required)) {
  this.context.formsy.validate(this);
}
  },

  // Detach it when component unmounts
  componentWillUnmount: function () {
this.context.formsy.detachFromForm(this);
//this.props._detachFromForm(this);
  },

  setValidations: function (validations, required) {

// Add validations to the store itself as the props object can not be modified
this._validations = convertValidationsToObject(validations) || {};
...
```

#### <a name="apidoc.element.formsy-react.Form.prototype.getChildContext"></a>[function <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>getChildContext ()](#apidoc.element.formsy-react.Form.prototype.getChildContext)
- description and source-code
```javascript
function getChildContext() {
  var _this = this;

  return {
    formsy: {
      attachToForm: this.attachToForm,
      detachFromForm: this.detachFromForm,
      validate: this.validate,
      isFormDisabled: this.isFormDisabled,
      isValidValue: function isValidValue(component, value) {
        return _this.runValidation(component, value).isValid;
      }
    }
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.Form.prototype.getCurrentValues"></a>[function <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>getCurrentValues ()](#apidoc.element.formsy-react.Form.prototype.getCurrentValues)
- description and source-code
```javascript
function getCurrentValues() {
  return this.inputs.reduce(function (data, component) {
    var name = component.props.name;
    data[name] = component.state._value;
    return data;
  }, {});
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.Form.prototype.getDOMNode"></a>[function <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>getDOMNode ()](#apidoc.element.formsy-react.Form.prototype.getDOMNode)
- description and source-code
```javascript
getDOMNode = function () {
  process.env.NODE_ENV !== 'production' ? warning(this.constructor[didWarnKey], '%s.getDOMNode(...) is deprecated. Please use ' + '
ReactDOM.findDOMNode(instance) instead.', ReactInstanceMap.get(this).getName() || this.tagName || 'Unknown') : undefined;
  this.constructor[didWarnKey] = true;
  return findDOMNode(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.Form.prototype.getInitialState"></a>[function <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>getInitialState ()](#apidoc.element.formsy-react.Form.prototype.getInitialState)
- description and source-code
```javascript
function getInitialState() {
  return {
    isValid: true,
    isSubmitting: false,
    canChange: false
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.Form.prototype.getModel"></a>[function <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>getModel ()](#apidoc.element.formsy-react.Form.prototype.getModel)
- description and source-code
```javascript
function getModel() {
  var currentValues = this.getCurrentValues();
  return this.mapModel(currentValues);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.Form.prototype.getPristineValues"></a>[function <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>getPristineValues ()](#apidoc.element.formsy-react.Form.prototype.getPristineValues)
- description and source-code
```javascript
function getPristineValues() {
  return this.inputs.reduce(function (data, component) {
    var name = component.props.name;
    data[name] = component.props.value;
    return data;
  }, {});
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.Form.prototype.isChanged"></a>[function <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>isChanged ()](#apidoc.element.formsy-react.Form.prototype.isChanged)
- description and source-code
```javascript
function isChanged() {
  return !utils.isSame(this.getPristineValues(), this.getCurrentValues());
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.Form.prototype.isFormDisabled"></a>[function <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>isFormDisabled ()](#apidoc.element.formsy-react.Form.prototype.isFormDisabled)
- description and source-code
```javascript
function isFormDisabled() {
  return this.props.disabled;
}
```
- example usage
```shell
...
  var messages = this.getErrorMessages();
  return messages.length ? messages[0] : null;
},
getErrorMessages: function () {
  return !this.isValid() || this.showRequired() ? (this.state._externalError || this.state._validationError || []) : [];
},
isFormDisabled: function () {
  return this.context.formsy.isFormDisabled();
  //return this.props._isFormDisabled();
},
isValid: function () {
  return this.state._isValid;
},
isPristine: function () {
  return this.state._isPristine;
...
```

#### <a name="apidoc.element.formsy-react.Form.prototype.mapModel"></a>[function <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>mapModel (model)](#apidoc.element.formsy-react.Form.prototype.mapModel)
- description and source-code
```javascript
function mapModel(model) {

  if (this.props.mapping) {
    return this.props.mapping(model);
  } else {
    return formDataToObject.toObj(Object.keys(model).reduce(function (mappedModel, key) {

      var keyArray = key.split('.');
      var base = mappedModel;
      while (keyArray.length) {
        var currentKey = keyArray.shift();
        base = base[currentKey] = keyArray.length ? base[currentKey] || {} : model[key];
      }

      return mappedModel;
    }, {}));
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.Form.prototype.render"></a>[function <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>render ()](#apidoc.element.formsy-react.Form.prototype.render)
- description and source-code
```javascript
function render() {
  var _props = this.props,
      mapping = _props.mapping,
      validationErrors = _props.validationErrors,
      onSubmit = _props.onSubmit,
      onValid = _props.onValid,
      onValidSubmit = _props.onValidSubmit,
      onInvalid = _props.onInvalid,
      onInvalidSubmit = _props.onInvalidSubmit,
      onChange = _props.onChange,
      reset = _props.reset,
      preventExternalInvalidation = _props.preventExternalInvalidation,
      onSuccess = _props.onSuccess,
      onError = _props.onError,
      nonFormsyProps = _objectWithoutProperties(_props, ['mapping', 'validationErrors', 'onSubmit', 'onValid', 'onValidSubmit', '
onInvalid', 'onInvalidSubmit', 'onChange', 'reset', 'preventExternalInvalidation', 'onSuccess', 'onError']);

  return React.createElement(
    'form',
    _extends({}, nonFormsyProps, { onSubmit: this.submit }),
    this.props.children
  );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.Form.prototype.reset"></a>[function <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>reset (data)](#apidoc.element.formsy-react.Form.prototype.reset)
- description and source-code
```javascript
function reset(data) {
  this.setFormPristine(true);
  this.resetModel(data);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.Form.prototype.resetModel"></a>[function <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>resetModel (data)](#apidoc.element.formsy-react.Form.prototype.resetModel)
- description and source-code
```javascript
function resetModel(data) {
  this.inputs.forEach(function (component) {
    var name = component.props.name;
    if (data && data.hasOwnProperty(name)) {
      component.setValue(data[name]);
    } else {
      component.resetValue();
    }
  });
  this.validateForm();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.Form.prototype.runRules"></a>[function <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>runRules (value, currentValues, validations)](#apidoc.element.formsy-react.Form.prototype.runRules)
- description and source-code
```javascript
function runRules(value, currentValues, validations) {

  var results = {
    errors: [],
    failed: [],
    success: []
  };
  if (Object.keys(validations).length) {
    Object.keys(validations).forEach(function (validationMethod) {

      if (validationRules[validationMethod] && typeof validations[validationMethod] === 'function') {
        throw new Error('Formsy does not allow you to override default validations: ' + validationMethod);
      }

      if (!validationRules[validationMethod] && typeof validations[validationMethod] !== 'function') {
        throw new Error('Formsy does not have the validation rule: ' + validationMethod);
      }

      if (typeof validations[validationMethod] === 'function') {
        var validation = validations[validationMethod](currentValues, value);
        if (typeof validation === 'string') {
          results.errors.push(validation);
          results.failed.push(validationMethod);
        } else if (!validation) {
          results.failed.push(validationMethod);
        }
        return;
      } else if (typeof validations[validationMethod] !== 'function') {
        var validation = validationRules[validationMethod](currentValues, value, validations[validationMethod]);
        if (typeof validation === 'string') {
          results.errors.push(validation);
          results.failed.push(validationMethod);
        } else if (!validation) {
          results.failed.push(validationMethod);
        } else {
          results.success.push(validationMethod);
        }
        return;
      }

      return results.success.push(validationMethod);
    });
  }

  return results;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.Form.prototype.runValidation"></a>[function <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>runValidation (component, value)](#apidoc.element.formsy-react.Form.prototype.runValidation)
- description and source-code
```javascript
function runValidation(component, value) {

  var currentValues = this.getCurrentValues();
  var validationErrors = component.props.validationErrors;
  var validationError = component.props.validationError;
  value = arguments.length === 2 ? value : component.state._value;

  var validationResults = this.runRules(value, currentValues, component._validations);
  var requiredResults = this.runRules(value, currentValues, component._requiredValidations);

  // the component defines an explicit validate function
  if (typeof component.validate === "function") {
    validationResults.failed = component.validate() ? [] : ['failed'];
  }

  var isRequired = Object.keys(component._requiredValidations).length ? !!requiredResults.success.length : false;
  var isValid = !validationResults.failed.length && !(this.props.validationErrors && this.props.validationErrors[component.props
.name]);

  return {
    isRequired: isRequired,
    isValid: isRequired ? false : isValid,
    error: function () {

      if (isValid && !isRequired) {
        return emptyArray;
      }

      if (validationResults.errors.length) {
        return validationResults.errors;
      }

      if (this.props.validationErrors && this.props.validationErrors[component.props.name]) {
        return typeof this.props.validationErrors[component.props.name] === 'string' ? [this.props.validationErrors[component.props
.name]] : this.props.validationErrors[component.props.name];
      }

      if (isRequired) {
        var error = validationErrors[requiredResults.success[0]];
        return error ? [error] : null;
      }

      if (validationResults.failed.length) {
        return validationResults.failed.map(function (failed) {
          return validationErrors[failed] ? validationErrors[failed] : validationError;
        }).filter(function (x, pos, arr) {
          // Remove duplicates
          return arr.indexOf(x) === pos;
        });
      }
    }.call(this)
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.Form.prototype.setFormPristine"></a>[function <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>setFormPristine (isPristine)](#apidoc.element.formsy-react.Form.prototype.setFormPristine)
- description and source-code
```javascript
function setFormPristine(isPristine) {
  this.setState({
    _formSubmitted: !isPristine
  });

  // Iterate through each component and set it as pristine
  // or "dirty".
  this.inputs.forEach(function (component, index) {
    component.setState({
      _formSubmitted: !isPristine,
      _isPristine: isPristine
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.Form.prototype.setInputValidationErrors"></a>[function <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>setInputValidationErrors (errors)](#apidoc.element.formsy-react.Form.prototype.setInputValidationErrors)
- description and source-code
```javascript
function setInputValidationErrors(errors) {
  this.inputs.forEach(function (component) {
    var name = component.props.name;
    var args = [{
      _isValid: !(name in errors),
      _validationError: typeof errors[name] === 'string' ? [errors[name]] : errors[name]
    }];
    component.setState.apply(component, args);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.Form.prototype.submit"></a>[function <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>submit (event)](#apidoc.element.formsy-react.Form.prototype.submit)
- description and source-code
```javascript
function submit(event) {

  event && event.preventDefault();

  // Trigger form as not pristine.
  // If any inputs have not been touched yet this will make them dirty
  // so validation becomes visible (if based on isPristine)
  this.setFormPristine(false);
  var model = this.getModel();
  this.props.onSubmit(model, this.resetModel, this.updateInputsWithError);
  this.state.isValid ? this.props.onValidSubmit(model, this.resetModel, this.updateInputsWithError) : this.props.onInvalidSubmit
(model, this.resetModel, this.updateInputsWithError);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.Form.prototype.updateInputsWithError"></a>[function <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>updateInputsWithError (errors)](#apidoc.element.formsy-react.Form.prototype.updateInputsWithError)
- description and source-code
```javascript
function updateInputsWithError(errors) {
  var _this2 = this;

  Object.keys(errors).forEach(function (name, index) {
    var component = utils.find(_this2.inputs, function (component) {
      return component.props.name === name;
    });
    if (!component) {
      throw new Error('You are trying to update an input that does not exist. ' + 'Verify errors object with input names. ' + JSON
.stringify(errors));
    }
    var args = [{
      _isValid: _this2.props.preventExternalInvalidation || false,
      _externalError: typeof errors[name] === 'string' ? [errors[name]] : errors[name]
    }];
    component.setState.apply(component, args);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.Form.prototype.validate"></a>[function <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>validate (component)](#apidoc.element.formsy-react.Form.prototype.validate)
- description and source-code
```javascript
function validate(component) {

  // Trigger onChange
  if (this.state.canChange) {
    this.props.onChange(this.getCurrentValues(), this.isChanged());
  }

  var validation = this.runValidation(component);
  // Run through the validations, split them up and call
  // the validator IF there is a value or it is required
  component.setState({
    _isValid: validation.isValid,
    _isRequired: validation.isRequired,
    _validationError: validation.error,
    _externalError: null
  }, this.validateForm);
}
```
- example usage
```shell
...
  // internally update, and this will never run
  if (!utils.isSame(this.props.value, prevProps.value)) {
    this.setValue(this.props.value);
  }

  // If validations or required is changed, run a new validation
  if (!utils.isSame(this.props.validations, prevProps.validations) || !utils.isSame(this.props.required, prevProps.required)) {
    this.context.formsy.validate(this);
  }
},

// Detach it when component unmounts
componentWillUnmount: function () {
  this.context.formsy.detachFromForm(this);
  //this.props._detachFromForm(this);
...
```

#### <a name="apidoc.element.formsy-react.Form.prototype.validateForm"></a>[function <span class="apidocSignatureSpan">formsy-react.Form.prototype.</span>validateForm ()](#apidoc.element.formsy-react.Form.prototype.validateForm)
- description and source-code
```javascript
function validateForm() {
  var _this3 = this;

  // We need a callback as we are validating all inputs again. This will
  // run when the last component has set its state
  var onValidationComplete = function () {
    var allIsValid = this.inputs.every(function (component) {
      return component.state._isValid;
    });

    this.setState({
      isValid: allIsValid
    });

    if (allIsValid) {
      this.props.onValid();
    } else {
      this.props.onInvalid();
    }

    // Tell the form that it can start to trigger change events
    this.setState({
      canChange: true
    });
  }.bind(this);

  // Run validation again in case affected by other inputs. The
  // last component validated will run the onValidationComplete callback
  this.inputs.forEach(function (component, index) {
    var validation = _this3.runValidation(component);
    if (validation.isValid && component.state._externalError) {
      validation.isValid = false;
    }
    component.setState({
      _isValid: validation.isValid,
      _isRequired: validation.isRequired,
      _validationError: validation.error,
      _externalError: !validation.isValid && component.state._externalError ? component.state._externalError : null
    }, index === _this3.inputs.length - 1 ? onValidationComplete : null);
  });

  // If there are no inputs, set state where form is ready to trigger
  // change event. New inputs might be added later
  if (!this.inputs.length && this.isMounted()) {
    this.setState({
      canChange: true
    });
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.formsy-react.Form.prototype.__reactAutoBindMap"></a>[module formsy-react.Form.prototype.__reactAutoBindMap](#apidoc.module.formsy-react.Form.prototype.__reactAutoBindMap)

#### <a name="apidoc.element.formsy-react.Form.prototype.__reactAutoBindMap.attachToForm"></a>[function <span class="apidocSignatureSpan">formsy-react.Form.prototype.__reactAutoBindMap.</span>attachToForm (component)](#apidoc.element.formsy-react.Form.prototype.__reactAutoBindMap.attachToForm)
- description and source-code
```javascript
function attachToForm(component) {

  if (this.inputs.indexOf(component) === -1) {
    this.inputs.push(component);
  }

  this.validate(component);
}
```
- example usage
```shell
...
  },

  componentWillMount: function () {
var configure = function () {
  this.setValidations(this.props.validations, this.props.required);

  // Pass a function instead?
  this.context.formsy.attachToForm(this);
  //this.props._attachToForm(this);
}.bind(this);

if (!this.props.name) {
  throw new Error('Form Input requires a name property when used');
}
...
```

#### <a name="apidoc.element.formsy-react.Form.prototype.__reactAutoBindMap.detachFromForm"></a>[function <span class="apidocSignatureSpan">formsy-react.Form.prototype.__reactAutoBindMap.</span>detachFromForm (component)](#apidoc.element.formsy-react.Form.prototype.__reactAutoBindMap.detachFromForm)
- description and source-code
```javascript
function detachFromForm(component) {
  var componentPos = this.inputs.indexOf(component);

  if (componentPos !== -1) {
    this.inputs = this.inputs.slice(0, componentPos).concat(this.inputs.slice(componentPos + 1));
  }

  this.validateForm();
}
```
- example usage
```shell
...
if (!utils.isSame(this.props.validations, prevProps.validations) || !utils.isSame(this.props.required, prevProps.required)) {
  this.context.formsy.validate(this);
}
  },

  // Detach it when component unmounts
  componentWillUnmount: function () {
this.context.formsy.detachFromForm(this);
//this.props._detachFromForm(this);
  },

  setValidations: function (validations, required) {

// Add validations to the store itself as the props object can not be modified
this._validations = convertValidationsToObject(validations) || {};
...
```

#### <a name="apidoc.element.formsy-react.Form.prototype.__reactAutoBindMap.getCurrentValues"></a>[function <span class="apidocSignatureSpan">formsy-react.Form.prototype.__reactAutoBindMap.</span>getCurrentValues ()](#apidoc.element.formsy-react.Form.prototype.__reactAutoBindMap.getCurrentValues)
- description and source-code
```javascript
function getCurrentValues() {
  return this.inputs.reduce(function (data, component) {
    var name = component.props.name;
    data[name] = component.state._value;
    return data;
  }, {});
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.Form.prototype.__reactAutoBindMap.getDOMNode"></a>[function <span class="apidocSignatureSpan">formsy-react.Form.prototype.__reactAutoBindMap.</span>getDOMNode ()](#apidoc.element.formsy-react.Form.prototype.__reactAutoBindMap.getDOMNode)
- description and source-code
```javascript
getDOMNode = function () {
  process.env.NODE_ENV !== 'production' ? warning(this.constructor[didWarnKey], '%s.getDOMNode(...) is deprecated. Please use ' + '
ReactDOM.findDOMNode(instance) instead.', ReactInstanceMap.get(this).getName() || this.tagName || 'Unknown') : undefined;
  this.constructor[didWarnKey] = true;
  return findDOMNode(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.Form.prototype.__reactAutoBindMap.getModel"></a>[function <span class="apidocSignatureSpan">formsy-react.Form.prototype.__reactAutoBindMap.</span>getModel ()](#apidoc.element.formsy-react.Form.prototype.__reactAutoBindMap.getModel)
- description and source-code
```javascript
function getModel() {
  var currentValues = this.getCurrentValues();
  return this.mapModel(currentValues);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.Form.prototype.__reactAutoBindMap.getPristineValues"></a>[function <span class="apidocSignatureSpan">formsy-react.Form.prototype.__reactAutoBindMap.</span>getPristineValues ()](#apidoc.element.formsy-react.Form.prototype.__reactAutoBindMap.getPristineValues)
- description and source-code
```javascript
function getPristineValues() {
  return this.inputs.reduce(function (data, component) {
    var name = component.props.name;
    data[name] = component.props.value;
    return data;
  }, {});
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.Form.prototype.__reactAutoBindMap.isChanged"></a>[function <span class="apidocSignatureSpan">formsy-react.Form.prototype.__reactAutoBindMap.</span>isChanged ()](#apidoc.element.formsy-react.Form.prototype.__reactAutoBindMap.isChanged)
- description and source-code
```javascript
function isChanged() {
  return !utils.isSame(this.getPristineValues(), this.getCurrentValues());
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.Form.prototype.__reactAutoBindMap.isFormDisabled"></a>[function <span class="apidocSignatureSpan">formsy-react.Form.prototype.__reactAutoBindMap.</span>isFormDisabled ()](#apidoc.element.formsy-react.Form.prototype.__reactAutoBindMap.isFormDisabled)
- description and source-code
```javascript
function isFormDisabled() {
  return this.props.disabled;
}
```
- example usage
```shell
...
  var messages = this.getErrorMessages();
  return messages.length ? messages[0] : null;
},
getErrorMessages: function () {
  return !this.isValid() || this.showRequired() ? (this.state._externalError || this.state._validationError || []) : [];
},
isFormDisabled: function () {
  return this.context.formsy.isFormDisabled();
  //return this.props._isFormDisabled();
},
isValid: function () {
  return this.state._isValid;
},
isPristine: function () {
  return this.state._isPristine;
...
```

#### <a name="apidoc.element.formsy-react.Form.prototype.__reactAutoBindMap.mapModel"></a>[function <span class="apidocSignatureSpan">formsy-react.Form.prototype.__reactAutoBindMap.</span>mapModel (model)](#apidoc.element.formsy-react.Form.prototype.__reactAutoBindMap.mapModel)
- description and source-code
```javascript
function mapModel(model) {

  if (this.props.mapping) {
    return this.props.mapping(model);
  } else {
    return formDataToObject.toObj(Object.keys(model).reduce(function (mappedModel, key) {

      var keyArray = key.split('.');
      var base = mappedModel;
      while (keyArray.length) {
        var currentKey = keyArray.shift();
        base = base[currentKey] = keyArray.length ? base[currentKey] || {} : model[key];
      }

      return mappedModel;
    }, {}));
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.Form.prototype.__reactAutoBindMap.reset"></a>[function <span class="apidocSignatureSpan">formsy-react.Form.prototype.__reactAutoBindMap.</span>reset (data)](#apidoc.element.formsy-react.Form.prototype.__reactAutoBindMap.reset)
- description and source-code
```javascript
function reset(data) {
  this.setFormPristine(true);
  this.resetModel(data);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.Form.prototype.__reactAutoBindMap.resetModel"></a>[function <span class="apidocSignatureSpan">formsy-react.Form.prototype.__reactAutoBindMap.</span>resetModel (data)](#apidoc.element.formsy-react.Form.prototype.__reactAutoBindMap.resetModel)
- description and source-code
```javascript
function resetModel(data) {
  this.inputs.forEach(function (component) {
    var name = component.props.name;
    if (data && data.hasOwnProperty(name)) {
      component.setValue(data[name]);
    } else {
      component.resetValue();
    }
  });
  this.validateForm();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.Form.prototype.__reactAutoBindMap.runRules"></a>[function <span class="apidocSignatureSpan">formsy-react.Form.prototype.__reactAutoBindMap.</span>runRules (value, currentValues, validations)](#apidoc.element.formsy-react.Form.prototype.__reactAutoBindMap.runRules)
- description and source-code
```javascript
function runRules(value, currentValues, validations) {

  var results = {
    errors: [],
    failed: [],
    success: []
  };
  if (Object.keys(validations).length) {
    Object.keys(validations).forEach(function (validationMethod) {

      if (validationRules[validationMethod] && typeof validations[validationMethod] === 'function') {
        throw new Error('Formsy does not allow you to override default validations: ' + validationMethod);
      }

      if (!validationRules[validationMethod] && typeof validations[validationMethod] !== 'function') {
        throw new Error('Formsy does not have the validation rule: ' + validationMethod);
      }

      if (typeof validations[validationMethod] === 'function') {
        var validation = validations[validationMethod](currentValues, value);
        if (typeof validation === 'string') {
          results.errors.push(validation);
          results.failed.push(validationMethod);
        } else if (!validation) {
          results.failed.push(validationMethod);
        }
        return;
      } else if (typeof validations[validationMethod] !== 'function') {
        var validation = validationRules[validationMethod](currentValues, value, validations[validationMethod]);
        if (typeof validation === 'string') {
          results.errors.push(validation);
          results.failed.push(validationMethod);
        } else if (!validation) {
          results.failed.push(validationMethod);
        } else {
          results.success.push(validationMethod);
        }
        return;
      }

      return results.success.push(validationMethod);
    });
  }

  return results;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.Form.prototype.__reactAutoBindMap.runValidation"></a>[function <span class="apidocSignatureSpan">formsy-react.Form.prototype.__reactAutoBindMap.</span>runValidation (component, value)](#apidoc.element.formsy-react.Form.prototype.__reactAutoBindMap.runValidation)
- description and source-code
```javascript
function runValidation(component, value) {

  var currentValues = this.getCurrentValues();
  var validationErrors = component.props.validationErrors;
  var validationError = component.props.validationError;
  value = arguments.length === 2 ? value : component.state._value;

  var validationResults = this.runRules(value, currentValues, component._validations);
  var requiredResults = this.runRules(value, currentValues, component._requiredValidations);

  // the component defines an explicit validate function
  if (typeof component.validate === "function") {
    validationResults.failed = component.validate() ? [] : ['failed'];
  }

  var isRequired = Object.keys(component._requiredValidations).length ? !!requiredResults.success.length : false;
  var isValid = !validationResults.failed.length && !(this.props.validationErrors && this.props.validationErrors[component.props
.name]);

  return {
    isRequired: isRequired,
    isValid: isRequired ? false : isValid,
    error: function () {

      if (isValid && !isRequired) {
        return emptyArray;
      }

      if (validationResults.errors.length) {
        return validationResults.errors;
      }

      if (this.props.validationErrors && this.props.validationErrors[component.props.name]) {
        return typeof this.props.validationErrors[component.props.name] === 'string' ? [this.props.validationErrors[component.props
.name]] : this.props.validationErrors[component.props.name];
      }

      if (isRequired) {
        var error = validationErrors[requiredResults.success[0]];
        return error ? [error] : null;
      }

      if (validationResults.failed.length) {
        return validationResults.failed.map(function (failed) {
          return validationErrors[failed] ? validationErrors[failed] : validationError;
        }).filter(function (x, pos, arr) {
          // Remove duplicates
          return arr.indexOf(x) === pos;
        });
      }
    }.call(this)
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.Form.prototype.__reactAutoBindMap.setFormPristine"></a>[function <span class="apidocSignatureSpan">formsy-react.Form.prototype.__reactAutoBindMap.</span>setFormPristine (isPristine)](#apidoc.element.formsy-react.Form.prototype.__reactAutoBindMap.setFormPristine)
- description and source-code
```javascript
function setFormPristine(isPristine) {
  this.setState({
    _formSubmitted: !isPristine
  });

  // Iterate through each component and set it as pristine
  // or "dirty".
  this.inputs.forEach(function (component, index) {
    component.setState({
      _formSubmitted: !isPristine,
      _isPristine: isPristine
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.Form.prototype.__reactAutoBindMap.setInputValidationErrors"></a>[function <span class="apidocSignatureSpan">formsy-react.Form.prototype.__reactAutoBindMap.</span>setInputValidationErrors (errors)](#apidoc.element.formsy-react.Form.prototype.__reactAutoBindMap.setInputValidationErrors)
- description and source-code
```javascript
function setInputValidationErrors(errors) {
  this.inputs.forEach(function (component) {
    var name = component.props.name;
    var args = [{
      _isValid: !(name in errors),
      _validationError: typeof errors[name] === 'string' ? [errors[name]] : errors[name]
    }];
    component.setState.apply(component, args);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.Form.prototype.__reactAutoBindMap.submit"></a>[function <span class="apidocSignatureSpan">formsy-react.Form.prototype.__reactAutoBindMap.</span>submit (event)](#apidoc.element.formsy-react.Form.prototype.__reactAutoBindMap.submit)
- description and source-code
```javascript
function submit(event) {

  event && event.preventDefault();

  // Trigger form as not pristine.
  // If any inputs have not been touched yet this will make them dirty
  // so validation becomes visible (if based on isPristine)
  this.setFormPristine(false);
  var model = this.getModel();
  this.props.onSubmit(model, this.resetModel, this.updateInputsWithError);
  this.state.isValid ? this.props.onValidSubmit(model, this.resetModel, this.updateInputsWithError) : this.props.onInvalidSubmit
(model, this.resetModel, this.updateInputsWithError);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.Form.prototype.__reactAutoBindMap.updateInputsWithError"></a>[function <span class="apidocSignatureSpan">formsy-react.Form.prototype.__reactAutoBindMap.</span>updateInputsWithError (errors)](#apidoc.element.formsy-react.Form.prototype.__reactAutoBindMap.updateInputsWithError)
- description and source-code
```javascript
function updateInputsWithError(errors) {
  var _this2 = this;

  Object.keys(errors).forEach(function (name, index) {
    var component = utils.find(_this2.inputs, function (component) {
      return component.props.name === name;
    });
    if (!component) {
      throw new Error('You are trying to update an input that does not exist. ' + 'Verify errors object with input names. ' + JSON
.stringify(errors));
    }
    var args = [{
      _isValid: _this2.props.preventExternalInvalidation || false,
      _externalError: typeof errors[name] === 'string' ? [errors[name]] : errors[name]
    }];
    component.setState.apply(component, args);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.Form.prototype.__reactAutoBindMap.validate"></a>[function <span class="apidocSignatureSpan">formsy-react.Form.prototype.__reactAutoBindMap.</span>validate (component)](#apidoc.element.formsy-react.Form.prototype.__reactAutoBindMap.validate)
- description and source-code
```javascript
function validate(component) {

  // Trigger onChange
  if (this.state.canChange) {
    this.props.onChange(this.getCurrentValues(), this.isChanged());
  }

  var validation = this.runValidation(component);
  // Run through the validations, split them up and call
  // the validator IF there is a value or it is required
  component.setState({
    _isValid: validation.isValid,
    _isRequired: validation.isRequired,
    _validationError: validation.error,
    _externalError: null
  }, this.validateForm);
}
```
- example usage
```shell
...
  // internally update, and this will never run
  if (!utils.isSame(this.props.value, prevProps.value)) {
    this.setValue(this.props.value);
  }

  // If validations or required is changed, run a new validation
  if (!utils.isSame(this.props.validations, prevProps.validations) || !utils.isSame(this.props.required, prevProps.required)) {
    this.context.formsy.validate(this);
  }
},

// Detach it when component unmounts
componentWillUnmount: function () {
  this.context.formsy.detachFromForm(this);
  //this.props._detachFromForm(this);
...
```

#### <a name="apidoc.element.formsy-react.Form.prototype.__reactAutoBindMap.validateForm"></a>[function <span class="apidocSignatureSpan">formsy-react.Form.prototype.__reactAutoBindMap.</span>validateForm ()](#apidoc.element.formsy-react.Form.prototype.__reactAutoBindMap.validateForm)
- description and source-code
```javascript
function validateForm() {
  var _this3 = this;

  // We need a callback as we are validating all inputs again. This will
  // run when the last component has set its state
  var onValidationComplete = function () {
    var allIsValid = this.inputs.every(function (component) {
      return component.state._isValid;
    });

    this.setState({
      isValid: allIsValid
    });

    if (allIsValid) {
      this.props.onValid();
    } else {
      this.props.onInvalid();
    }

    // Tell the form that it can start to trigger change events
    this.setState({
      canChange: true
    });
  }.bind(this);

  // Run validation again in case affected by other inputs. The
  // last component validated will run the onValidationComplete callback
  this.inputs.forEach(function (component, index) {
    var validation = _this3.runValidation(component);
    if (validation.isValid && component.state._externalError) {
      validation.isValid = false;
    }
    component.setState({
      _isValid: validation.isValid,
      _isRequired: validation.isRequired,
      _validationError: validation.error,
      _externalError: !validation.isValid && component.state._externalError ? component.state._externalError : null
    }, index === _this3.inputs.length - 1 ? onValidationComplete : null);
  });

  // If there are no inputs, set state where form is ready to trigger
  // change event. New inputs might be added later
  if (!this.inputs.length && this.isMounted()) {
    this.setState({
      canChange: true
    });
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.formsy-react.Mixin"></a>[module formsy-react.Mixin](#apidoc.module.formsy-react.Mixin)

#### <a name="apidoc.element.formsy-react.Mixin.componentDidUpdate"></a>[function <span class="apidocSignatureSpan">formsy-react.Mixin.</span>componentDidUpdate (prevProps)](#apidoc.element.formsy-react.Mixin.componentDidUpdate)
- description and source-code
```javascript
function componentDidUpdate(prevProps) {

  // If the value passed has changed, set it. If value is not passed it will
  // internally update, and this will never run
  if (!utils.isSame(this.props.value, prevProps.value)) {
    this.setValue(this.props.value);
  }

  // If validations or required is changed, run a new validation
  if (!utils.isSame(this.props.validations, prevProps.validations) || !utils.isSame(this.props.required, prevProps.required)) {
    this.context.formsy.validate(this);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.Mixin.componentWillMount"></a>[function <span class="apidocSignatureSpan">formsy-react.Mixin.</span>componentWillMount ()](#apidoc.element.formsy-react.Mixin.componentWillMount)
- description and source-code
```javascript
function componentWillMount() {
  var configure = function () {
    this.setValidations(this.props.validations, this.props.required);

    // Pass a function instead?
    this.context.formsy.attachToForm(this);
    //this.props._attachToForm(this);
  }.bind(this);

  if (!this.props.name) {
    throw new Error('Form Input requires a name property when used');
  }

<span class="apidocCodeCommentSpan">  /*
  if (!this.props._attachToForm) {
    return setTimeout(function () {
      if (!this.isMounted()) return;
      if (!this.props._attachToForm) {
        throw new Error('Form Mixin requires component to be nested in a Form');
      }
      configure();
    }.bind(this), 0);
  }
  */
</span>  configure();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.Mixin.componentWillReceiveProps"></a>[function <span class="apidocSignatureSpan">formsy-react.Mixin.</span>componentWillReceiveProps (nextProps)](#apidoc.element.formsy-react.Mixin.componentWillReceiveProps)
- description and source-code
```javascript
function componentWillReceiveProps(nextProps) {
  this.setValidations(nextProps.validations, nextProps.required);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.Mixin.componentWillUnmount"></a>[function <span class="apidocSignatureSpan">formsy-react.Mixin.</span>componentWillUnmount ()](#apidoc.element.formsy-react.Mixin.componentWillUnmount)
- description and source-code
```javascript
function componentWillUnmount() {
  this.context.formsy.detachFromForm(this);
  //this.props._detachFromForm(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.Mixin.getDefaultProps"></a>[function <span class="apidocSignatureSpan">formsy-react.Mixin.</span>getDefaultProps ()](#apidoc.element.formsy-react.Mixin.getDefaultProps)
- description and source-code
```javascript
function getDefaultProps() {
  return {
    validationError: '',
    validationErrors: {}
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.Mixin.getErrorMessage"></a>[function <span class="apidocSignatureSpan">formsy-react.Mixin.</span>getErrorMessage ()](#apidoc.element.formsy-react.Mixin.getErrorMessage)
- description and source-code
```javascript
function getErrorMessage() {
  var messages = this.getErrorMessages();
  return messages.length ? messages[0] : null;
}
```
- example usage
```shell
...
// when the value is empty and the required prop is
// passed to the input. showError() is true when the
// value typed is invalid
const className = this.showRequired() ? 'required' : this.showError() ? 'error' : null;

// An error message is returned ONLY if the component is invalid
// or the server has returned an error message
const errorMessage = this.getErrorMessage();

return (
  <div className={className}>
    <input type="text" onChange={this.changeValue} value={this.getValue()}/>
    <span>{errorMessage}</span>
  </div>
);
...
```

#### <a name="apidoc.element.formsy-react.Mixin.getErrorMessages"></a>[function <span class="apidocSignatureSpan">formsy-react.Mixin.</span>getErrorMessages ()](#apidoc.element.formsy-react.Mixin.getErrorMessages)
- description and source-code
```javascript
function getErrorMessages() {
  return !this.isValid() || this.showRequired() ? this.state._externalError || this.state._validationError || [] : [];
}
```
- example usage
```shell
...
getValue: function () {
  return this.state._value;
},
hasValue: function () {
  return this.state._value !== '';
},
getErrorMessage: function () {
  var messages = this.getErrorMessages();
  return messages.length ? messages[0] : null;
},
getErrorMessages: function () {
  return !this.isValid() || this.showRequired() ? (this.state._externalError || this.state._validationError || []) : [];
},
isFormDisabled: function () {
  return this.context.formsy.isFormDisabled();
...
```

#### <a name="apidoc.element.formsy-react.Mixin.getInitialState"></a>[function <span class="apidocSignatureSpan">formsy-react.Mixin.</span>getInitialState ()](#apidoc.element.formsy-react.Mixin.getInitialState)
- description and source-code
```javascript
function getInitialState() {
  return {
    _value: this.props.value,
    _isRequired: false,
    _isValid: true,
    _isPristine: true,
    _pristineValue: this.props.value,
    _validationError: [],
    _externalError: null,
    _formSubmitted: false
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.Mixin.getValue"></a>[function <span class="apidocSignatureSpan">formsy-react.Mixin.</span>getValue ()](#apidoc.element.formsy-react.Mixin.getValue)
- description and source-code
```javascript
function getValue() {
  return this.state._value;
}
```
- example usage
```shell
...

      // An error message is returned ONLY if the component is invalid
      // or the server has returned an error message
      const errorMessage = this.getErrorMessage();

      return (
        <div className={className}>
          <input type="text" onChange={this.changeValue} value={this.getValue()}/>
          <span>{errorMessage}</span>
        </div>
      );
    }
  });
'''
The form element component is what gives the form validation functionality to whatever you want to put inside this wrapper. You
do not have to use traditional inputs, it can be anything you want and the value of the form element can also be anything you want
. As you can see it is very flexible, you just have a small API to help you identify the state of the component and set its value
.
...
```

#### <a name="apidoc.element.formsy-react.Mixin.hasValue"></a>[function <span class="apidocSignatureSpan">formsy-react.Mixin.</span>hasValue ()](#apidoc.element.formsy-react.Mixin.hasValue)
- description and source-code
```javascript
function hasValue() {
  return this.state._value !== '';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.Mixin.isFormDisabled"></a>[function <span class="apidocSignatureSpan">formsy-react.Mixin.</span>isFormDisabled ()](#apidoc.element.formsy-react.Mixin.isFormDisabled)
- description and source-code
```javascript
function isFormDisabled() {
  return this.context.formsy.isFormDisabled();
  //return this.props._isFormDisabled();
}
```
- example usage
```shell
...
  var messages = this.getErrorMessages();
  return messages.length ? messages[0] : null;
},
getErrorMessages: function () {
  return !this.isValid() || this.showRequired() ? (this.state._externalError || this.state._validationError || []) : [];
},
isFormDisabled: function () {
  return this.context.formsy.isFormDisabled();
  //return this.props._isFormDisabled();
},
isValid: function () {
  return this.state._isValid;
},
isPristine: function () {
  return this.state._isPristine;
...
```

#### <a name="apidoc.element.formsy-react.Mixin.isFormSubmitted"></a>[function <span class="apidocSignatureSpan">formsy-react.Mixin.</span>isFormSubmitted ()](#apidoc.element.formsy-react.Mixin.isFormSubmitted)
- description and source-code
```javascript
function isFormSubmitted() {
  return this.state._formSubmitted;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.Mixin.isPristine"></a>[function <span class="apidocSignatureSpan">formsy-react.Mixin.</span>isPristine ()](#apidoc.element.formsy-react.Mixin.isPristine)
- description and source-code
```javascript
function isPristine() {
  return this.state._isPristine;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.Mixin.isRequired"></a>[function <span class="apidocSignatureSpan">formsy-react.Mixin.</span>isRequired ()](#apidoc.element.formsy-react.Mixin.isRequired)
- description and source-code
```javascript
function isRequired() {
  return !!this.props.required;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.Mixin.isValid"></a>[function <span class="apidocSignatureSpan">formsy-react.Mixin.</span>isValid ()](#apidoc.element.formsy-react.Mixin.isValid)
- description and source-code
```javascript
function isValid() {
  return this.state._isValid;
}
```
- example usage
```shell
...
  return this.state._value !== '';
},
getErrorMessage: function () {
  var messages = this.getErrorMessages();
  return messages.length ? messages[0] : null;
},
getErrorMessages: function () {
  return !this.isValid() || this.showRequired() ? (this.state._externalError || this.state._validationError || []) : [];
},
isFormDisabled: function () {
  return this.context.formsy.isFormDisabled();
  //return this.props._isFormDisabled();
},
isValid: function () {
  return this.state._isValid;
...
```

#### <a name="apidoc.element.formsy-react.Mixin.isValidValue"></a>[function <span class="apidocSignatureSpan">formsy-react.Mixin.</span>isValidValue (value)](#apidoc.element.formsy-react.Mixin.isValidValue)
- description and source-code
```javascript
function isValidValue(value) {
  return this.context.formsy.isValidValue.call(null, this, value);
  //return this.props._isValidValue.call(null, this, value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.Mixin.resetValue"></a>[function <span class="apidocSignatureSpan">formsy-react.Mixin.</span>resetValue ()](#apidoc.element.formsy-react.Mixin.resetValue)
- description and source-code
```javascript
function resetValue() {
  this.setState({
    _value: this.state._pristineValue,
    _isPristine: true
  }, function () {
    this.context.formsy.validate(this);
    //this.props._validate(this);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.Mixin.setValidations"></a>[function <span class="apidocSignatureSpan">formsy-react.Mixin.</span>setValidations (validations, required)](#apidoc.element.formsy-react.Mixin.setValidations)
- description and source-code
```javascript
function setValidations(validations, required) {

  // Add validations to the store itself as the props object can not be modified
  this._validations = convertValidationsToObject(validations) || {};
  this._requiredValidations = required === true ? { isDefaultRequiredValue: true } : convertValidationsToObject(required);
}
```
- example usage
```shell
...
  validationError: '',
  validationErrors: {}
};
  },

  componentWillMount: function () {
var configure = function () {
  this.setValidations(this.props.validations, this.props.required);

  // Pass a function instead?
  this.context.formsy.attachToForm(this);
  //this.props._attachToForm(this);
}.bind(this);

if (!this.props.name) {
...
```

#### <a name="apidoc.element.formsy-react.Mixin.setValue"></a>[function <span class="apidocSignatureSpan">formsy-react.Mixin.</span>setValue (value)](#apidoc.element.formsy-react.Mixin.setValue)
- description and source-code
```javascript
function setValue(value) {
  this.setState({
    _value: value,
    _isPristine: false
  }, function () {
    this.context.formsy.validate(this);
    //this.props._validate(this);
  }.bind(this));
}
```
- example usage
```shell
...

// Add the Formsy Mixin
mixins: [Formsy.Mixin],

// setValue() will set the value of the component, which in
// turn will validate it and the rest of the form
changeValue(event) {
  this.setValue(event.currentTarget.value);
},

render() {
  // Set a specific className based on the validation
  // state of this component. showRequired() is true
  // when the value is empty and the required prop is
  // passed to the input. showError() is true when the
...
```

#### <a name="apidoc.element.formsy-react.Mixin.showError"></a>[function <span class="apidocSignatureSpan">formsy-react.Mixin.</span>showError ()](#apidoc.element.formsy-react.Mixin.showError)
- description and source-code
```javascript
function showError() {
  return !this.showRequired() && !this.isValid();
}
```
- example usage
```shell
...

    render() {
// Set a specific className based on the validation
// state of this component. showRequired() is true
// when the value is empty and the required prop is
// passed to the input. showError() is true when the
// value typed is invalid
const className = this.showRequired() ? 'required' : this.showError() ? 'error' : null;

// An error message is returned ONLY if the component is invalid
// or the server has returned an error message
const errorMessage = this.getErrorMessage();

return (
  <div className={className}>
...
```

#### <a name="apidoc.element.formsy-react.Mixin.showRequired"></a>[function <span class="apidocSignatureSpan">formsy-react.Mixin.</span>showRequired ()](#apidoc.element.formsy-react.Mixin.showRequired)
- description and source-code
```javascript
function showRequired() {
  return this.state._isRequired;
}
```
- example usage
```shell
...

    render() {
// Set a specific className based on the validation
// state of this component. showRequired() is true
// when the value is empty and the required prop is
// passed to the input. showError() is true when the
// value typed is invalid
const className = this.showRequired() ? 'required' : this.showError() ? 'error' : null;

// An error message is returned ONLY if the component is invalid
// or the server has returned an error message
const errorMessage = this.getErrorMessage();

return (
  <div className={className}>
...
```



# <a name="apidoc.module.formsy-react.Mixin.contextTypes"></a>[module formsy-react.Mixin.contextTypes](#apidoc.module.formsy-react.Mixin.contextTypes)

#### <a name="apidoc.element.formsy-react.Mixin.contextTypes.formsy"></a>[function <span class="apidocSignatureSpan">formsy-react.Mixin.contextTypes.</span>formsy ()](#apidoc.element.formsy-react.Mixin.contextTypes.formsy)
- description and source-code
```javascript
formsy = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.formsy-react.utils"></a>[module formsy-react.utils](#apidoc.module.formsy-react.utils)

#### <a name="apidoc.element.formsy-react.utils.arraysDiffer"></a>[function <span class="apidocSignatureSpan">formsy-react.utils.</span>arraysDiffer (a, b)](#apidoc.element.formsy-react.utils.arraysDiffer)
- description and source-code
```javascript
function arraysDiffer(a, b) {
  var isDifferent = false;
  if (a.length !== b.length) {
    isDifferent = true;
  } else {
    a.forEach(function (item, index) {
      if (!this.isSame(item, b[index])) {
        isDifferent = true;
      }
    }, this);
  }
  return isDifferent;
}
```
- example usage
```shell
...
return isDifferent;
  },

  isSame: function isSame(a, b) {
if ((typeof a === 'undefined' ? 'undefined' : _typeof(a)) !== (typeof b === 'undefined' ? 'undefined' : _typeof(b))) {
  return false;
} else if (Array.isArray(a) && Array.isArray(b)) {
  return !this.arraysDiffer(a, b);
} else if (typeof a === 'function') {
  return a.toString() === b.toString();
} else if ((typeof a === 'undefined' ? 'undefined' : _typeof(a)) === 'object' && a !== null && b !== null) {
  return !this.objectsDiffer(a, b);
}

return a === b;
...
```

#### <a name="apidoc.element.formsy-react.utils.find"></a>[function <span class="apidocSignatureSpan">formsy-react.utils.</span>find (collection, fn)](#apidoc.element.formsy-react.utils.find)
- description and source-code
```javascript
function find(collection, fn) {
  for (var i = 0, l = collection.length; i < l; i++) {
    var item = collection[i];
    if (fn(item)) {
      return item;
    }
  }
  return null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.utils.isSame"></a>[function <span class="apidocSignatureSpan">formsy-react.utils.</span>isSame (a, b)](#apidoc.element.formsy-react.utils.isSame)
- description and source-code
```javascript
function isSame(a, b) {
  if ((typeof a === 'undefined' ? 'undefined' : _typeof(a)) !== (typeof b === 'undefined' ? 'undefined' : _typeof(b))) {
    return false;
  } else if (Array.isArray(a) && Array.isArray(b)) {
    return !this.arraysDiffer(a, b);
  } else if (typeof a === 'function') {
    return a.toString() === b.toString();
  } else if ((typeof a === 'undefined' ? 'undefined' : _typeof(a)) === 'object' && a !== null && b !== null) {
    return !this.objectsDiffer(a, b);
  }

  return a === b;
}
```
- example usage
```shell
...
module.exports = {
arraysDiffer: function arraysDiffer(a, b) {
  var isDifferent = false;
  if (a.length !== b.length) {
    isDifferent = true;
  } else {
    a.forEach(function (item, index) {
      if (!this.isSame(item, b[index])) {
        isDifferent = true;
      }
    }, this);
  }
  return isDifferent;
},
...
```

#### <a name="apidoc.element.formsy-react.utils.objectsDiffer"></a>[function <span class="apidocSignatureSpan">formsy-react.utils.</span>objectsDiffer (a, b)](#apidoc.element.formsy-react.utils.objectsDiffer)
- description and source-code
```javascript
function objectsDiffer(a, b) {
  var isDifferent = false;
  if (Object.keys(a).length !== Object.keys(b).length) {
    isDifferent = true;
  } else {
    Object.keys(a).forEach(function (key) {
      if (!this.isSame(a[key], b[key])) {
        isDifferent = true;
      }
    }, this);
  }
  return isDifferent;
}
```
- example usage
```shell
...
  if ((typeof a === 'undefined' ? 'undefined' : _typeof(a)) !== (typeof b === 'undefined' ? 'undefined' : _typeof(b))) {
    return false;
  } else if (Array.isArray(a) && Array.isArray(b)) {
    return !this.arraysDiffer(a, b);
  } else if (typeof a === 'function') {
    return a.toString() === b.toString();
  } else if ((typeof a === 'undefined' ? 'undefined' : _typeof(a)) === 'object' && a !== null && b !== null) {
    return !this.objectsDiffer(a, b);
  }

  return a === b;
},

find: function find(collection, fn) {
  for (var i = 0, l = collection.length; i < l; i++) {
...
```



# <a name="apidoc.module.formsy-react.validationRules"></a>[module formsy-react.validationRules](#apidoc.module.formsy-react.validationRules)

#### <a name="apidoc.element.formsy-react.validationRules.equals"></a>[function <span class="apidocSignatureSpan">formsy-react.validationRules.</span>equals (values, value, eql)](#apidoc.element.formsy-react.validationRules.equals)
- description and source-code
```javascript
function equals(values, value, eql) {
  return !_isExisty(value) || isEmpty(value) || value == eql;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.validationRules.equalsField"></a>[function <span class="apidocSignatureSpan">formsy-react.validationRules.</span>equalsField (values, value, field)](#apidoc.element.formsy-react.validationRules.equalsField)
- description and source-code
```javascript
function equalsField(values, value, field) {
  return value == values[field];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.validationRules.isAlpha"></a>[function <span class="apidocSignatureSpan">formsy-react.validationRules.</span>isAlpha (values, value)](#apidoc.element.formsy-react.validationRules.isAlpha)
- description and source-code
```javascript
function isAlpha(values, value) {
  return validations.matchRegexp(values, value, /^[A-Z]+$/i);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.validationRules.isAlphanumeric"></a>[function <span class="apidocSignatureSpan">formsy-react.validationRules.</span>isAlphanumeric (values, value)](#apidoc.element.formsy-react.validationRules.isAlphanumeric)
- description and source-code
```javascript
function isAlphanumeric(values, value) {
  return validations.matchRegexp(values, value, /^[0-9A-Z]+$/i);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.validationRules.isDefaultRequiredValue"></a>[function <span class="apidocSignatureSpan">formsy-react.validationRules.</span>isDefaultRequiredValue (values, value)](#apidoc.element.formsy-react.validationRules.isDefaultRequiredValue)
- description and source-code
```javascript
function isDefaultRequiredValue(values, value) {
  return value === undefined || value === '';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.validationRules.isEmail"></a>[function <span class="apidocSignatureSpan">formsy-react.validationRules.</span>isEmail (values, value)](#apidoc.element.formsy-react.validationRules.isEmail)
- description and source-code
```javascript
function isEmail(values, value) {
  return validations.matchRegexp(values, value, /^((([a-z]|\d|[!#\$%&'\*\+\-\/=\?\^_'{\|}~]|[\u00A0-\uD7FF\uF900-\uFDCF\uFDF0-\uFFEF
])+(\.([a-z]|\d|[!#\$%&'\*\+\-\/=\?\^_'{\|}~]|[\u00A0-\uD7FF\uF900-\uFDCF\uFDF0-\uFFEF])+)*)|((\x22)((((\x20|\x09)*(\x0d\x0a))?(\x20|\x09)+)?(([\x01-\x08\x0b\x0c\x0e-\x1f\x7f]|\x21|[\x23-\x5b]|[\x5d-\x7e]|[\u00A0-\uD7FF\uF900-\uFDCF\uFDF0-\uFFEF])|(\\([\x01-\x09\x0b\x0c\x0d-\x7f]|[\u00A0-\uD7FF\uF900-\uFDCF\uFDF0-\uFFEF]))))*(((\x20|\x09)*(\x0d\x0a))?(\x20|\x09)+)?(\x22)))@((([a-z]|\d|[\u00A0-\uD7FF\uF900-\uFDCF\uFDF0-\uFFEF])|(([a-z]|\d|[\u00A0-\uD7FF\uF900-\uFDCF\uFDF0-\uFFEF])([a-z]|\d|-|\.|_|~|[\u00A0-\uD7FF\uF900-\uFDCF\uFDF0-\uFFEF])*([a-z]|\d|[\u00A0-\uD7FF\uF900-\uFDCF\uFDF0-\uFFEF])))\.)+(([a-z]|[\u00A0-\uD7FF\uF900-\uFDCF\uFDF0-\uFFEF])|(([a-z]|[\u00A0-\uD7FF\uF900-\uFDCF\uFDF0-\uFFEF])([a-z]|\d|-|\.|_|~|[\u00A0-\uD7FF\uF900-\uFDCF\uFDF0-\uFFEF])*([a-z]|[\u00A0-\uD7FF\uF900-\uFDCF\uFDF0-\uFFEF])))$/i);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.validationRules.isEmptyString"></a>[function <span class="apidocSignatureSpan">formsy-react.validationRules.</span>isEmptyString (values, value)](#apidoc.element.formsy-react.validationRules.isEmptyString)
- description and source-code
```javascript
function isEmptyString(values, value) {
  return isEmpty(value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.validationRules.isExisty"></a>[function <span class="apidocSignatureSpan">formsy-react.validationRules.</span>isExisty (values, value)](#apidoc.element.formsy-react.validationRules.isExisty)
- description and source-code
```javascript
function isExisty(values, value) {
  return _isExisty(value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.validationRules.isFalse"></a>[function <span class="apidocSignatureSpan">formsy-react.validationRules.</span>isFalse (values, value)](#apidoc.element.formsy-react.validationRules.isFalse)
- description and source-code
```javascript
function isFalse(values, value) {
  return value === false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.validationRules.isFloat"></a>[function <span class="apidocSignatureSpan">formsy-react.validationRules.</span>isFloat (values, value)](#apidoc.element.formsy-react.validationRules.isFloat)
- description and source-code
```javascript
function isFloat(values, value) {
  return validations.matchRegexp(values, value, /^(?:[-+]?(?:\d+))?(?:\.\d*)?(?:[eE][\+\-]?(?:\d+))?$/);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.validationRules.isInt"></a>[function <span class="apidocSignatureSpan">formsy-react.validationRules.</span>isInt (values, value)](#apidoc.element.formsy-react.validationRules.isInt)
- description and source-code
```javascript
function isInt(values, value) {
  return validations.matchRegexp(values, value, /^(?:[-+]?(?:0|[1-9]\d*))$/);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.validationRules.isLength"></a>[function <span class="apidocSignatureSpan">formsy-react.validationRules.</span>isLength (values, value, length)](#apidoc.element.formsy-react.validationRules.isLength)
- description and source-code
```javascript
function isLength(values, value, length) {
  return !_isExisty(value) || isEmpty(value) || value.length === length;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.validationRules.isNumeric"></a>[function <span class="apidocSignatureSpan">formsy-react.validationRules.</span>isNumeric (values, value)](#apidoc.element.formsy-react.validationRules.isNumeric)
- description and source-code
```javascript
function isNumeric(values, value) {
  if (typeof value === 'number') {
    return true;
  }
  return validations.matchRegexp(values, value, /^[-+]?(?:\d*[.])?\d+$/);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.validationRules.isSpecialWords"></a>[function <span class="apidocSignatureSpan">formsy-react.validationRules.</span>isSpecialWords (values, value)](#apidoc.element.formsy-react.validationRules.isSpecialWords)
- description and source-code
```javascript
function isSpecialWords(values, value) {
  return validations.matchRegexp(values, value, /^[A-Z\s\u00C0-\u017F]+$/i);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.validationRules.isTrue"></a>[function <span class="apidocSignatureSpan">formsy-react.validationRules.</span>isTrue (values, value)](#apidoc.element.formsy-react.validationRules.isTrue)
- description and source-code
```javascript
function isTrue(values, value) {
  return value === true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.validationRules.isUndefined"></a>[function <span class="apidocSignatureSpan">formsy-react.validationRules.</span>isUndefined (values, value)](#apidoc.element.formsy-react.validationRules.isUndefined)
- description and source-code
```javascript
function isUndefined(values, value) {
  return value === undefined;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.validationRules.isUrl"></a>[function <span class="apidocSignatureSpan">formsy-react.validationRules.</span>isUrl (values, value)](#apidoc.element.formsy-react.validationRules.isUrl)
- description and source-code
```javascript
function isUrl(values, value) {
  return validations.matchRegexp(values, value, /^(https?|s?ftp):\/\/(((([a-z]|\d|-|\.|_|~|[\u00A0-\uD7FF\uF900-\uFDCF\uFDF0-\uFFEF
])|(%[\da-f]{2})|[!\$&'\(\)\*\+,;=]|:)*@)?(((\d|[1-9]\d|1\d\d|2[0-4]\d|25[0-5])\.(\d|[1-9]\d|1\d\d|2[0-4]\d|25[0-5])\.(\d|[1-9]\d|1\d\d|2[0-4]\d|25[0-5])\.(\d|[1-9]\d|1\d\d|2[0-4]\d|25[0-5]))|((([a-z]|\d|[\u00A0-\uD7FF\uF900-\uFDCF\uFDF0-\uFFEF])|(([a-z]|\d|[\u00A0-\uD7FF\uF900-\uFDCF\uFDF0-\uFFEF])([a-z]|\d|-|\.|_|~|[\u00A0-\uD7FF\uF900-\uFDCF\uFDF0-\uFFEF])*([a-z]|\d|[\u00A0-\uD7FF\uF900-\uFDCF\uFDF0-\uFFEF])))\.)+(([a-z]|[\u00A0-\uD7FF\uF900-\uFDCF\uFDF0-\uFFEF])|(([a-z]|[\u00A0-\uD7FF\uF900-\uFDCF\uFDF0-\uFFEF])([a-z]|\d|-|\.|_|~|[\u00A0-\uD7FF\uF900-\uFDCF\uFDF0-\uFFEF])*([a-z]|[\u00A0-\uD7FF\uF900-\uFDCF\uFDF0-\uFFEF])))\.?)(:\d*)?)(\/((([a-z]|\d|-|\.|_|~|[\u00A0-\uD7FF\uF900-\uFDCF\uFDF0-\uFFEF])|(%[\da-f]{2})|[!\$&'\(\)\*\+,;=]|:|@)+(\/(([a-z]|\d|-|\.|_|~|[\u00A0-\uD7FF\uF900-\uFDCF\uFDF0-\uFFEF])|(%[\da-f]{2})|[!\$&'\(\)\*\+,;=]|:|@)*)*)?)?(\?((([a-z]|\d|-|\.|_|~|[\u00A0-\uD7FF\uF900-\uFDCF\uFDF0-\uFFEF])|(%[\da-f]{2})|[!\$&'\(\)\*\+,;=]|:|@)|[\uE000-\uF8FF]|\/|\?)*)?(#((([a-z]|\d|-|\.|_|~|[\u00A0-\uD7FF\uF900-\uFDCF\uFDF0-\uFFEF])|(%[\da-f]{2})|[!\$&'\(\)\*\+,;=]|:|@)|\/|\?)*)?$/i);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.validationRules.isWords"></a>[function <span class="apidocSignatureSpan">formsy-react.validationRules.</span>isWords (values, value)](#apidoc.element.formsy-react.validationRules.isWords)
- description and source-code
```javascript
function isWords(values, value) {
  return validations.matchRegexp(values, value, /^[A-Z\s]+$/i);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.validationRules.matchRegexp"></a>[function <span class="apidocSignatureSpan">formsy-react.validationRules.</span>matchRegexp (values, value, regexp)](#apidoc.element.formsy-react.validationRules.matchRegexp)
- description and source-code
```javascript
function matchRegexp(values, value, regexp) {
  return !_isExisty(value) || isEmpty(value) || regexp.test(value);
}
```
- example usage
```shell
...
isUndefined: function isUndefined(values, value) {
  return value === undefined;
},
isEmptyString: function isEmptyString(values, value) {
  return isEmpty(value);
},
isEmail: function isEmail(values, value) {
  return validations.matchRegexp(values, value, /^((([a-z]|\d|[!#\$%&'\*\+\-\/=\?\^_'{\|}~]|[\u00A0-\uD7FF\uF900-\uFDCF\uFDF0-\uFFEF
])+(\.([a-z]|\d|[!#\$%&'\*\+\-\/=\?\^_'{\|}~]|[\u00A0-\uD7FF\uF900-\uFDCF\uFDF0-\uFFEF])+)*)|((\x22)((((\x20|\x09)*(\x0d\x0a))?(\x20|\x09)+)?(([\x01-\x08\x0b\x0c\x0e-\x1f\x7f]|\x21|[\x23-\x5b]|[\x5d-\x7e]|[\u00A0-\uD7FF\uF900-\uFDCF\uFDF0-\uFFEF])|(\\([\x01-\x09\x0b\x0c\x0d-\x7f]|[\u00A0-\uD7FF\uF900-\uFDCF\uFDF0-\uFFEF]))))*(((\x20|\x09)*(\x0d\x0a))?(\x20|\x09)+)?(\x22)))@((([a-z]|\d|[\u00A0-\uD7FF\uF900-\uFDCF\uFDF0-\uFFEF])|(([a-z]|\d|[\u00A0-\uD7FF\uF900-\uFDCF\uFDF0-\uFFEF])([a-z]|\d|-|\.|_|~|[\u00A0-\uD7FF\uF900-\uFDCF\uFDF0-\uFFEF])*([a-z]|\d|[\u00A0-\uD7FF\uF900-\uFDCF\uFDF0-\uFFEF])))\.)+(([a-z]|[\u00A0-\uD7FF\uF900-\uFDCF\uFDF0-\uFFEF])|(([a-z]|[\u00A0-\uD7FF\uF900-\uFDCF\uFDF0-\uFFEF])([a-z]|\d|-|\.|_|~|[\u00A0-\uD7FF\uF900-\uFDCF\uFDF0-\uFFEF])*([a-z]|[\u00A0-\uD7FF\uF900-\uFDCF\uFDF0-\uFFEF])))$/i);
},
isUrl: function isUrl(values, value) {
  return validations.matchRegexp(values, value, /^(https?|s?ftp):\/\/(((([a-z]|\d|-|\.|_|~|[\u00A0-\uD7FF\uF900-\uFDCF\uFDF0-\uFFEF
])|(%[\da-f]{2})|[!\$&'\(\)\*\+,;=]|:)*@)?(((\d|[1-9]\d|1\d\d|2[0-4]\d|25[0-5])\.(\d|[1-9]\d|1\d\d|2[0-4]\d|25[0-5])\.(\d|[1-9]\d|1\d\d|2[0-4]\d|25[0-5])\.(\d|[1-9]\d|1\d\d|2[0-4]\d|25[0-5]))|((([a-z]|\d|[\u00A0-\uD7FF\uF900-\uFDCF\uFDF0-\uFFEF])|(([a-z]|\d|[\u00A0-\uD7FF\uF900-\uFDCF\uFDF0-\uFFEF])([a-z]|\d|-|\.|_|~|[\u00A0-\uD7FF\uF900-\uFDCF\uFDF0-\uFFEF])*([a-z]|\d|[\u00A0-\uD7FF\uF900-\uFDCF\uFDF0-\uFFEF])))\.)+(([a-z]|[\u00A0-\uD7FF\uF900-\uFDCF\uFDF0-\uFFEF])|(([a-z]|[\u00A0-\uD7FF\uF900-\uFDCF\uFDF0-\uFFEF])([a-z]|\d|-|\.|_|~|[\u00A0-\uD7FF\uF900-\uFDCF\uFDF0-\uFFEF])*([a-z]|[\u00A0-\uD7FF\uF900-\uFDCF\uFDF0-\uFFEF])))\.?)(:\d*)?)(\/((([a-z]|\d|-|\.|_|~|[\u00A0-\uD7FF\uF900-\uFDCF\uFDF0-\uFFEF])|(%[\da-f]{2})|[!\$&'\(\)\*\+,;=]|:|@)+(\/(([a-z]|\d|-|\.|_|~|[\u00A0-\uD7FF\uF900-\uFDCF\uFDF0-\uFFEF])|(%[\da-f]{2})|[!\$&'\(\)\*\+,;=]|:|@)*)*)?)?(\?((([a-z]|\d|-|\.|_|~|[\u00A0-\uD7FF\uF900-\uFDCF\uFDF0-\uFFEF])|(%[\da-f]{2})|[!\$&'\(\)\*\+,;=]|:|@)|[\uE000-\uF8FF]|\/|\?)*)?(#((([a-z]|\d|-|\.|_|~|[\u00A0-\uD7FF\uF900-\uFDCF\uFDF0-\uFFEF])|(%[\da-f]{2})|[!\$&'\(\)\*\+,;=]|:|@)|\/|\?)*)?$/i);
},
isTrue: function isTrue(values, value) {
  return value === true;
},
...
```

#### <a name="apidoc.element.formsy-react.validationRules.maxLength"></a>[function <span class="apidocSignatureSpan">formsy-react.validationRules.</span>maxLength (values, value, length)](#apidoc.element.formsy-react.validationRules.maxLength)
- description and source-code
```javascript
function maxLength(values, value, length) {
  return !_isExisty(value) || value.length <= length;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.formsy-react.validationRules.minLength"></a>[function <span class="apidocSignatureSpan">formsy-react.validationRules.</span>minLength (values, value, length)](#apidoc.element.formsy-react.validationRules.minLength)
- description and source-code
```javascript
function minLength(values, value, length) {
  return !_isExisty(value) || isEmpty(value) || value.length >= length;
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
