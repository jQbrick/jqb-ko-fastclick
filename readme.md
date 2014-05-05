# KnockoutJS FastClick
----------------------

Add a `fastclick` custom data binding to KnockoutJS.

> `fastclick` reduces the 300ms delay problem when clicking on touch 
> devices.

This module is just a KnockoutJS wrapper around [`ftlabs/fastclick`](https://github.com/ftlabs/fastclick) library.


## Install into a Workspace project

Install this module via `NPM`:

    npm install jqm-ko-fastklick --save
    
Then just load it into your `src/index.js` entry point:

    require('jqb-ko-fastclick');
    
> There is no initialisation options or procedures for this module. 


## Use in a Template

`fastclick` is just a plain wrapper for the `click` binding so you use it exactly the same way:

    <button data-bind="fastclick:handler">ClickMe!</button>
    
[Click here for KnockoutJS `click`'s documentation](http://knockoutjs.com/documentation/click-binding.html).