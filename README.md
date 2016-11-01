# ng2-daterangepicker
A simple Angular 2 directive that wraps the Bootstrap date range picker found at http://www.daterangepicker.com/. To use this directive, you must include jQuery, momentJS, and Bootstrap CSS.

## Installing
To install as an NPM package, run `npm i onehungrymind/ng2-daterangepicker --save`. Make sure to include the provided css file.

## Usage
Import the directive and provide it in the `directives` array on your component. In your template, use `daterangepicker` as an attribute on an `input` element. There is one input binding of `options` that expects an object of any options available at http://www.daterangepicker.com/#options.
