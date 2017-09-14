# JSONListModel
JsonListModel QML component

A collection of utilities for QML

Contents:

*** JSONListModel

A QML ListModel for JSON data.
Features:
  - API matching with XMLListModel, for ease of use
  - file-based and string-based data
  - Automatic model roles from JSON element properties
  - Complex JSON document handling with JSONPath, XPath for JSON (http://goessner.net/articles/JsonPath/)
  - Advanced querying and filtering expressions

Keith Kyzivat Addendum:
2017-07-19 - pulled this in from
https://github.com/ubuntudroid/qml-utils/tree/patch-1 SHA 2332d17e8c21348b203db5d2d33391ae945f5ead from 2014-03-30
Changes from Romain's initial code by Ubuntudroid include handling different HTTP request types, handling clear better, and better handling when the model changes.
