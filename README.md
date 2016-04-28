AndroidLangTool
===============

Simple tool to export Android strings resourses to Excel and import them to project after translating.
It will scan Android project and export all strings.xml to Excel file. So you will have a simple way to prepare translations. 

The app supports xml comments. 
Missing translations will have red background in xls file.

To run application, execute: `java -jar LangTool.jar`

Tool has two commands: *export* to xls and *import* from xls file
 
`
export: -e <project dir> <output file>
`

**project dir** - Path to Android project. 

**output file** - Name of Excel file


`
import: -i <input file>
`

**input file** - Name of Excel file to import to the project 

Link to binary: http://goo.gl/5EaOg

Link to eclipse plugin: http://goo.gl/fwEkU
