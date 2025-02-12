# Valiant Programming Language Specifications

Thank you for taking an interest in Valiant!
This repository explains the language specifications for the Valiant programming language.
I highly recommend starting with the [Start](#start) node, as it is the root of all Valiant source code.

## `start`
* [`top level definition`](#top_level_definition)`*`

## `top_level_definition`
* [`comment`](#comment)
* [`event_handler`](#event_handler)

## `comment`
* [`multi_line_comment`](#multi_line_comment)
* [`single_line_comment`](#single_line_comment)

## `event_handler`
* `"on"` [`event_name`](#event_name) [`function_body`](#function_body)

## `event_name`
* [`WORD`](#WORD)`*`

## `function_body`
* `"{"` [`statement`](#statement)`*` `"}"`

## `statement`
* [`comment`](#comment)
* [`expression`](#expression)

## `expression`
* [`print_expression`](#print_expression)
* [`function_call_expression`](#function_call_expression)
* [`math_expression`](#math_expression)
* [`variable_expression`](#variable_expression)
* [`literal`](#literal)
