# #react-auto-import
#step 1.1 Open vscode settings.json file
#step 1.2 added some code settings.json file
## settings.json

```sh
"json.schemas": [
			{
				"exclude": ["node_modules"]
			}
		],
"files.associations": {
		"*.react.js": "javascriptreact",
		"*.jsx": "javascriptreact",
		"*.js": "javascriptreact"
	}		
```
## jsconfig.json
> Note: `#step 2.1 also open react app path {src} folder open then creating new file {jsconfig.json} file put the some code `
```sh 
   	 {
		"exclude": ["node_modules"]
	}
```
#write react app code automatically path importing executing react code
