# my cheatsheet 

## commands
### help
sudo in mac
`npm help <cmd>`
`npm <cmd> -h`
`npm help-search jquery`

### config
`npm config get init-author-name`
`npm config delete init-author-name`
`npm config set init-author-name Jogesh`

### initialize 
`npm init`
`npm init --yes`

### installing packages
`npm install moment --save`
`npm install moment --save-dev` | `npm i moment -D`
`npm install --global tsc` | `npm i g tsc`

`npm i chance-cli`

`npx chance phone`

`npm install moment lodash`
`const _ = require('lodash')`

### uninstallilng package
`npm uninstall moment` | ` rm ` | `remove` | `un`
`npm uninstall -g  | --save-dev `

### Maintaining

`npm update lodash`
`npm update tsc --save-dev`
`npm update -g gulp`
`npm update -g gulp`

`npm install lodash@latest -g`

`npm list`
`npm list lodash`
`npm list --depth 0`
`npm list -g --depth 0`
`npm view lodash version`

`npm prune`


### scripts
npm run test-script

### versions 
Major.minor.patch 

Semantic Versioning semver
Rules: 
^2.5.5 
<ul>
  <li> `^`   fix major </li>
`~`   fix major and minor
`>`   greater than specified version
`>=`
`<`
`<=`
`=`   
`-`   range from - to
`||`  `>2.4.0 || < 1.3.0`
                         </ul>
