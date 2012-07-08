# `timestep.ui.Cell`

## Inheritence

1. [timestep.View](./timestep-view.html)
2. [lib.PubSub](./lib-pubsub.html)

## Methods

* __remove__ ---Remove this View from the superview.

* __getHeight__
	* @return `{number}` ---Returns `this.style.height`.

* __getWidth__
	* @return `{number}` ---Returns `this.style.width`.

* __setData (data)__ ---This needs to be redefined if you
  want to use this data in your view.
	* @param `{object} data`

* __setPosition (pos)__
	* @param `{object} pos` ---Object with `x` and `y` properties.


## Properties

* __model__ `{squill.models.Cell}` ---[`squill.models.Cell`](./squill-models-cell.html).


## Messages

`Recycle` ---When `this.model` receives a `Recycle` event, this
`Cell` is removed from it's superview.