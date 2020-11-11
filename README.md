# FieldtypeConfigForm

ProcessWire Module Fieldtype container for multiple inputfields in JSON format.

## About

Main target for this fieldtype was to store multiple configurations and setup values in JSON format in a single DB table cell.
ConfigForm filedtype can contain multiple different fieldtypes and can help to save DB storage space and reduce DB queries.
This fieldtype can be used to store text content (eg. like "body" field),and also multilanguage content, but please note that was not primary target for this fieldtype.  


## Installation

1. Download and unzip installation folder and place it in site/modules/.
2. In PW administration, go to "Modules" and press "Refresh" button.
3. Install "ConfigForm FieldType" module

## Field setup

4. Create field using type "ConfigForm FieldType".
5. Go to new created field and select "Input" tab. 
6. Inside "Input" drag and drop desired subfields.

6.1 Click on "pencil" icon and set field "Label" and write some intuitive field "Name".
*** Field "Name" setup is important (just like in native PW field setup) and do not skip that part!
*** Field name can contain special character "-" as words separator. Other special characters in field names are not available beacuse of used js library.  

7. Ignore blue "Save" button (use default PW "Save" button).


## Usage

It's on you how and for what to use ConfigForm fieldtype. 
In my case, I use it mostly to store various setup values, and for small text content (eg. "widgets").

Some examples "what to set" and "what to get":

	- "children per page", or "limit"
	- "number of columns"	
	- "show or hide ..."
	- "select layout"
	- if (X == Y) than ...		
	- for small text content blocks (eg. "widgets")
	- etc...

## Multilanguage

Text and textarea field types provide options to store multilanguage content.
