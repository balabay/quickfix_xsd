# quickfix_xsd
XML Schema for QuickFIX XML Specifications

QuickFIX is available at https://github.com/quickfix/quickfix

Schema is for the version v1.15.1

Results of the validation:

```
quickfix/spec$ xmllint --schema ../../quickfix_xsd/quickfix.xsd --noout FIX*.xml 
FIX40.xml validates
FIX41.xml validates
FIX42.xml validates
FIX43.xml validates
FIX44.xml validates
FIX50SP1.xml validates
FIX50SP2.xml validates
FIX50.xml validates
FIXT11.xml validates

```
