# Table of Contents

Here you can find the complete list of decorators, however we encourage you to read [`Introduction`](Introduction.md) section as first step.

- Components
  - [`@component`](components/component.md)
  - [`@pureComponent`](components/pureComponent.md)
  - [`@hoc(HOC: function, ...params)`](components/hoc.md)
  - [`@displayName(name: string)`](components/displayName.md)
  - [`@propTypes(propTypes: propTypes)`](components/propTypes.md)
  - [`@initialState(state: Object)`](components/initialState.md)
  - [`@defaultProps(props: Object)`](components/defaultProps.md)
  - [`@bindProps(props: Object)`](components/bindProps.md)
  - [`@computedProps(props: Object)`](components/computedProps.md)
  - [`@renameProps(config: Object)`](components/renameProps.md)
  - [`@mapProps(callback: function)`](components/mapProps.md)
  - [`@transferProps`](components/transferProps.md)
  - [`@clone(component: React.Component)`](components/clone.md)
  - [`@withStyles(styles: Object)`](components/withStyles.md)
- Functions
  - [`@autobind`](functions/autobind.md)
  - [`@inject(attribute: string)`](functions/inject.md)
  - [`@injectProps`](functions/injectProps.md)
  - [`@injectState`](functions/injectState.md)
- Context
  - [`@context(childContextTypes: contextTypes, childContext: Object)`](context/context.md)
  - [`@contextTypes(contextTypes: contextTypes)`](context/contextTypes.md)
  - [`@childContext(childContext: Object)`](context/childContext.md)
  - [`@childContextTypes(childContextTypes: contextTypes)`](context/childContextTypes.md)
- Events
  - [`@stopPropagation`](events/stopPropagation.md)
  - [`@preventDefault`](events/preventDefault.md)
  - [`@killEvent`](events/killEvent.md)
  - [`@extractFromEvent(attribute: string)`](events/extractFromEvent.md)
  - [`@extractValue`](events/extractValue.md)
  - [`@extractTarget`](events/extractTarget.md)
  - [`@extractCurrentTarget`](events/extractCurrentTarget.md)
  - [`@extractNativeEvent`](events/extractNativeEvent.md)
- Lifecycle
  - [`@componentWillMount(callback: componentWillMount)`](lifecycle/componentWillMount.md)
  - [`@componentDidMount(callback: componentDidMount)`](lifecycle/componentDidMount.md)
  - [`@componentWillUpdate(callback: componentWillUpdate)`](lifecycle/componentWillUpdate.md)
  - [`@componentDidUpdate(callback: componentDidUpdate)`](lifecycle/componentDidUpdate.md)
  - [`@componentWillReceiveProps(callback: componentWillReceiveProps)`](lifecycle/componentWillReceiveProps.md)
  - [`@shouldComponentUpdate(callback: shouldComponentUpdate)`](lifecycle/shouldComponentUpdate.md)
  - [`@componentWillUnmount(callback: componentWillUnmount)`](lifecycle/componentWillUnmount.md)
- Others
  - [`@property(name: string, value: any)`](others/property.md)