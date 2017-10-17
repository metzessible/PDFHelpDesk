# *Problem*: Tables
Technically, tables are considered [Text](Problems/Text.md), but they have a tendency to create such a headache for remediators that they need their own category to deal with them. Tables are used to represent tabular data where every row has the same set of column headers and/or every column has the same set of row headers.

## What kinds of Tables are there?

There are 3 common types of tables in a PDF:

- [Layout Tables](#layout-tables)
- [Simple Tables](#simple-tables)
- [Complex Tables](#complex-tables)
- [Irregular Tables](#irregular-tables)

When referring to tables as an issue, it can be helpful (but not necessary) to provide us with some detail about what kind of table you're dealing with. If your *Problem* is that you're not sure what kind of table something is, just refer to it as **Problem: Tables**. 

Another thing to note is that this *Problem* category doesn't refer to **Tables of Content**. Depending on how your Table of Contents is structured, it's best to refer to them based on whether they're [interactive](Problems/Interactivity.md) or simply static [text](Problems/Text.md). 

### Layout Tables
Essentially, layout tables are any type of table that is used for laying out a page. Many novice Microsoft Word users (as well as experts who are frustrated with getting an image to sit alongside content correctly) rely on layout tables to design a page. While frowned upon in web design circles, a document created in Word using a layout table is perfectly fine to do, as long as the mark-up of the tags doesn't reflect an actual table. For example, Layout Tables are often used to create PDF Forms.

### Simple Tables
A simple table is a table that contains data cells that are controlled by one header cell. Headers in a simple table include **Row Headers** (a single header that controls a horizontal row of data), **Column Headers** ((a single header that controls a vertical column of data), or both a single column header and a row header. 

#### Example Simple Table
| Roll | Side Effect of Remediating PDF files |
| :---- | :----------  |
| 01-20 | Dizziness, nausea, general discombobulation |
| 21-45 | Vomiting, shakes, convulsions |
| 46-80 | Seizures, brain trauma |
| 81-00 | Complete Madness: roll on the Random Insanity table below |

### Complex Tables
Complex tables are tables where the **data cells are controlled by more than one header cell**. Special formatting of the tag structure must be implemented when using complex tables.

*\* I don't actually know how to provide row spans and more than one heading rows in markdown table to provide an example, or even if it's possible in Github.*

### Irregular Tables

An irregular table is a table that doesn't have an equal number of cells to make up a rectangle. 
