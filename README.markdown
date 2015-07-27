NAME
===

datatables-bootstrap3


SYNOPSIS
===

    // Preferred.. Extend your project's shared jQuery;
    var $ = require('jquery');
		$ = require('datatables')($);
    $ = require('datatables-bootstrap3')($);

		// Alternatively, use your projects shared DataTable
		var $ = require('datatables')();
    $ = require('datatables-bootstrap3')($);
    
		// Alternatively, do everything and return a new modified jQuery
    var $ = require('datatables-bootstrap3')();

The more explicit you are, the less likely you are to have multiple copies of jQuery.

DESCRIPTION
===

This module expands jQuery in such a fashion that makes it support the
bootstrap classes. DataTables, utilizing jQuery, will magically work with it.
