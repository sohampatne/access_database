# Database

Database is a collection of data organised in such a manner so that it is easily accessible, retrievable and usable.
In a manual database, you might store or record data in a physical book/file, which is then stored in a bookshelf or filing cabinet respectively.
Database softwares like Access, MySQL, PostgreSQL, Oracle allows us to create, access and manage database on a computer.

## Microsoft Access

Microsoft Access is a Relational Database Management System(RDBMS) which allows you to access, create and manage data in multiple tables.

### Components of Access

#### Tables, Records and Fields

In MS-Access, a database consists of a collection of tables organized in a row and column format. A record is a row in a table that contains information about a specific product, person or an event. A field is a column in a table that contains a specific piece of information of the records. Fields are the smallest unit of data in a database.

#### Datasheet and Forms

Each table appears as a spreadsheet grid called a datasheet. You can type directly into a datasheet, You can also add forms, which are like dialog boxes that prompt the user to make a field entry, making data entry more convinient.

#### Filter and Queries

You can filter a table to show the records and fields that you want. You can also create queries, an easy way to understand is that they are like saved filters. Queries also enable you to combine data from different tables into a single datasheet of results.

#### Reports

Reports are an easy way of expressing data from tables and queries in an attractive and presentable format, complete with titles, headers, footers and graphics.

## Starting Access

Click on the Start Button on TaskBar or the Windows Key on the Keyboard and search for 'Access', then open the software - 'Access 2016'.

### Design View

You can also view your table in design view for greater control over the structure of the table. You can describe the structure of the table before creating it. You can enter your own field names, description and the type of data entry to associate it with each field.

In design view, the window is divided into two panes: UPPER PANE for creating field name, specifying data types, and entering field descriptions and lower pane for specifying field properties, For each field, you need to specify the following:

#### Field Name

There must be a unique name for each field in the table. For example, in a Student's Details table, the field names are Student-ID, Name, Class, Transportation, Fees, etc.

#### Data Type

Each field has a data type assigned to it that defines that what data can be entered in that field and what you can store in it. Data Entry is restricted to valid entries for the type you choose. For example, you cannot enter a letters in a field set to Number.

#### Description

You can enter detailed or brief information of all the fields within the table.

## Datatypes available in Access 2016

### Short Text

This is a general-purpose field containing any data. It has a limit of 255 characters and cannot be used for numeric calculations. Use this type for numeric entries that will not have calculations performed on them, such as telephone numbers and zip codes.

### Long Text

This type has a limit of 63,999 characters; it is used for detailed descriptive fields.

### Number

This type stores numeric data that you can use in calculations. It can also hold stmbols, such as decimal points and commas.

### Date/Time

This type only stores numbers representing valid dates and times.

### Currency

It stores currency data that you can store in calculations.

### Auto Number

It stores a sequential number for each record

### Yes/No

The value '1' represents 'Yes' and the value '0' represents 'No', but the field can be formatted to display values as True/False or Yes/No.

### OLE object

It stores objects created in another application such as Word or Excel that you can link to or fix in a Access table.

### HyperLink

You can link to websites, e-mail addresses, files on your computer, files on the LAN or virtually any other location.

### Attachment

This type is available only in Microsoft Access version 2007 and 2016 databases. You can attach data files frow word processing programs, spreadsheets, graphic editing programs and so on.

### Calculated

You can use it to create calculated fields directly in a table. In the earlier verisions, you could create calculated fields only in queries.

### Lookup Wizard

Depending on the usage, this type creates either a lookup list from the data that you specify or a lookup list from the values in another talble. It can also be used to set up multivalued lists.