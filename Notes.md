- [ ] Section 10: Modules In JavaScript 00/07 | 53min
	- [ ] 144. Section Overview | 3min Resources
	  - Modules are a very important concept
		- Color palettes
		- Book chapters
	- [ ] 145. What Is A Module? | 11min Resources
	  - script sourcing
		- Sometimes the order matters
	- [ ] 146. Module Pattern | 13min
		- IIFEs

		```javascript
		var moduleVariable = (function() {

		})()
		```

	- [ ] 147. Module Pattern Pros and Cons | 5min
	- [ ] 148. CommonJS, AMD, UMD | 10min
	  - CommonJS
		- Node.js is still using CommonJS
		```javascript
		var module1 = require('module1');
		```

		- With CommonJS, modules are meant to be loaded synchronously. That's not optimal for Browser code.

	  - Browserify, Webpack
		  - Traverse the dependency tree, bundles them up in a single file, no global namespace pollution, order doesn't matter anymore

		- AMD
		  - loads scripts asynchronously
			- pre-JS-Native-Modules
			- require.js (confusing, with CommonJS' use of the 'require' keyword)

	- [ ] 149. ES6 Modules | 9min Resources

	```javascript
	import module1 from 'module1'
	import module2 from 'module2'

	function jump() { // Private Function

	}

	export function fight() {

	}
	```

	- Import a named, exported function
	```javascript
	// <script type="module">

	import { fight } from './script.js'
	```

	- Import a default, exported function
	```javascript
	import fight from './script.js'
	```

	- [ ] 150. Section Review | 2min

- [ ] Section 11: Error Handling 00/08 | 43min
	- [ ] 151. Section Overview | 1min Resources
	- [ ] 152. Errors In JavaScript | 9min Resources
	- [ ] 153. Try Catch | 10min Resources
	- [ ] 154. Async Error Handling | 13min Resources
	- [ ] 155. Async Error Handling 2 | 4min Resources
	- [ ] 156. Exercise: Error Handling | 1min Resources
	- [ ] 157. Extending Errors | 5min Resources
	- [ ] 158. Section Review | 1min
