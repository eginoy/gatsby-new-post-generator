# gatsby_new_post_script
# Features
gatsby new post generate script
# Installation
`cd ${your_gatsby_website_dir} && mkdir script && cd script`  

`svn export https://github.com/eginoy/gatsby_new_post_script/trunk/newpost`  

package.json add script  
`"scripts": {
    "newpost": "node ./script/newpost/index.js",
    "build": "gatsby build",  
    ...
`
# Usage
`npm newpost ${post_title}`