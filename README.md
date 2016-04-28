AndroidLangTool
===============

Simple tool to export Android strings resourses to Excel and import them to project after translating.
It will scan Android project and export all strings.xml to Excel file. So you will have a simple way to prepare translations. 

The app supports xml comments. 
Missing translations will have red background in xls file.

To run application, execute: `java -jar LangTool.jar`

Tool has two commands: export to xls and import from xls file
 
`
export: -e <project dir> <output file>
`

**project dir** - path to android project. 

**output file** - name of excel file


`
import: -i <input file>
`

**input file** - name of excel file for importing to project 

link to binary: http://goo.gl/5EaOg

link to eclipse plugin: http://goo.gl/fwEkU