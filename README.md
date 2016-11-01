# ng2-daterangepicker
> **NOTE:** this project was intended to be an internal prototype for us. As such, everyone is welcome to use it for their own purposes, we just will not be supporting it.

A simple Angular 2 directive that wraps the Bootstrap date range picker found at http://www.daterangepicker.com/. To use this directive, you must include jQuery, momentJS, and Bootstrap CSS.

## Installing
To install as an NPM package, run `npm i onehungrymind/ng2-daterangepicker --save`. Make sure to include the provided css file.

## Usage
Import the directive and provide it in the `directives` array on your component. In your template, use `daterangepicker` as an attribute on an `input` element. There is one input binding of `options` that expects an object of any options available at http://www.daterangepicker.com/#options.

If you would like to see the picker in action, take a look at the [ng2-daterangepicker-example](https://github.com/onehungrymind/ng2-daterangepicker-example).
