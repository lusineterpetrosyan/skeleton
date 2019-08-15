This project allows to create simple module for publishing to npmjs

## Available Scripts

In the project directory, you can run:
*Note: Files will be compiled to dist folder*
##### `npm run prepublish`


****************

Then, for testing locally, need to run the commands 

##### `nvm use <your_node_version>`
##### `npm link`

The message like this `/<users>/.nvm/versions/node/v<your_node_version>/lib/node_modules/skeleton -> /<users>/<your_folder>/skeleton`
means the module linked in global node_modules
Use command `npm link skeleton` to use it in your/test project.

## How to use

```
...
import { ComponentExample } from 'skeleton';
...
render() {
	return <>
		...
		<ComponentExample />
		...
	</>
}
```