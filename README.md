# YUIDoc Snippets for [Atom Editor](http://atom.io)

A collection of YUIDoc snippets for Atom Editor. Works in both **Javascript** and **Coffeescript**.

## Snippets

- \*attr (js) or #attr (coffee)
		###*
		description
		
		@attribute MY_ATTRIBUTE
		@readOnly
		@type {Boolean}
		@default "false"
		###

- \*class (js) or #class (coffee)
		###*
		description
		
		@class MyClass
		@param {Object} options description
		@constructor
		@static
		@extends
		@for
		@module
		@namespace
		@uses
		@example
			myClass = new MyClass()
		###

- \*elem (js) or #elem (coffee)
		###*
		description
		
		@element <div>
		@parents <body>
		@contents <span>
		@interface MyElement
		###

- \*event (js) or #event (coffee)
		###*
		Event triggered when 
		
		@event error
		@param {Object} options description
		###

- \*main (js) or #main (coffee)
		###*
		description
		
		@main widget
		@module widget
		@submodule widget-foo
		###

- \*meth (js) or #meth (coffee)
		###*
		description
		
		@method MyMethod
		@param {Object} options description
		@param {String options.name description
		@param {Function} callback callback function
		@param {String} callback.error error message
		@param {Object} callback.result result}
		@constructor
		@throws
		@static
		@async
		@chainable
		@private
		@return {Object}
		###

- \*mod (js) or #mod (coffee)
		###*
		description
		
		@module widget
		@class
		@for
		@main
		@submodule
		###

- \*prop (js) or #prop (coffee)
		###*
		description
		
		@property myProperty
		@type {Boolean}
		@default "false"
		@static
		@readOnly
		@writeOnce
		@optional
		@required
		###
