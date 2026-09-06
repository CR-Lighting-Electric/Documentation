---
title: Vehicle Database
description: Main page for the Vehicle Database.
function:
type: docs
obstype: page
related:
next:
prev:
sidebar:
open: true
date: 2026-09-05
---

![](/images/logo-pickup-truck.png)

_Welcome to the Vehicle Database documentation!_

- **Who?** The vehicle database is meant for any individual that provides or maintains the related data, requires access to review the data, or requires a higher level of reporting on the data.
- **What?** The database includes related data on all vehicles, trailers, equipment, and any other asset with wheels worth accounting for.
- **When?** The database requires an estimated weekly maintenance interval basis, or whenever any relevant data becomes available for recording. Reviewing the data or providing reports on the data is available at any time.
- **Where?** The workbook itself is currently saved and stored on the workbook owner's One Drive account and shared with appropriate team members.
- **Why?** Recording and maintaining all available vehicle data allows an organization to make more informed decisions about its fleet and drivers. Identifying areas where costs can be trimmed, investments worth or not making, trends over time, are just a few of the numerous benefits of the exercise.

## Overview

The workbook aims to be as simple as possible with organizing and reporting on the data.  All data is stored in Excel Tables, which creates structure, automatic table calculation, and more readable function definitions on cells. Each worksheet divides the data and contains its own table and table search function at the bottom, further outlined in the [Tables](#Tables) section.

The `Overview` page will most likely have most of the information you need. Take a look at the _Directory_  for a list of available filters and views. Otherwise, you can sort and review whatever data you need in the specific sheet or table you require.

If you require a specific filter or view to be built from the data that does not exist, contact the workbook editor or owner to get your idea created, displayed, and added to the directory.

#### Directory

The directory section serves as a table of contents and table for useful links inside the workbook. The links here purposefully have an order to capture the order of which the existing filters and table views exist in the overview page. 

#### Quick Statistics

This section provides the user with a list of useful statistics on the tables themselves, which could include averages, medians, modes, etc. The list here is color coded with tables themselves. Refer to the legend to understand the coloring scheme for the workbook.

#### Roles & Responsibilities

To avoid stepping on each other's toes and to ensure that the data isn't duplicated, removed, or erroneously modified, there are specific roles and responsibilities that are assigned to personnel in this table on the `Overview` page. 

#### Legend

The legend provides the viewer with a section for understanding what colors and formats represent across the workbook. Tables are all color coded to their areas, so anywhere that color is used within the workbook, it relates to that table/area.

### Data Retention

The workbook was designed to continuously store all vehicle data over an extending period of time. This means that records _should not be deleted_ unless the workbook owner is in agreement that a specific row or area of data can be.

All vehicles and drivers have a `Status` column where editors can immediately change wether the table row is active or not, sold, or whatever the correct value may be. Deleting a row simply because we no longer user or maintain that vehicle or driver any more is lost data to the overall picture.

### Sheets

Here's a rundown of all the available sheets and what their purposes are.

| Sheet           | Purpose                                                                        |
| --------------- | ------------------------------------------------------------------------------ |
| `Overview`      | Provide a broad look at quick views of each table, analysis, and instruction.  |
| `Vehicles`      | Store all vehicle instances, providing aggregate data from other tables.       |
| `Drivers`       | Store all drivers and users, providing aggregate data from other tables.       |
| `Registration`  | Provide a continuous log of all registration occurrences with current links.   |
| `Maintenance`   | Provide a continuous log of all maintenances occurrences on all vehicles.      |
| `Repairs`       | Provide a continuous log of all repair occurrences on all vehicles.            |
| `Inspections`   | Provide a continuous log of all inspection occurrences on all vehicles.        |
| `Recalls`       | Provide a continuous log of all recall notices issued on all vehicles.         |
| `Accidents`     | Provide a continuous log of all accidents on all vehicles and related drivers. |
| `Maverik`       | Store the Maverik Fleet Management transaction reporting data.                 |
| `Locations`     | Store a list of currently available job site and other locations for vehicles. |
| `Configuration` | Provide a configuration table with values for filters, views, and data.        |
| `Dropdowns`     | Provide a table for data validation purposes across all tables and sheets.     |

Each sheet utilizes a full table search box to quickly pull up any text that may exist in any row. The purpose of this is to provide viewers an extremely quick and easy way to check the review or check the existence of data. 

{{< callout >}}
  Replace any text in the table search text box with a tick mark (\`) to clear the filter.
{{< /callout >}}

### Data Sources

1. **File Documentation:** sources that are physical paper, invoiced, or exist as a digital document; the information and data on these files can be manually or in some cases, digitally extracted and inserted into the database. These include the following within the database:
	- Receipts
	- Invoices
	- Registration
	- Maintenance
	- Repairs
	- Inspections
	- Recalls
	- Accidents
2. **Reporting Exports:** sources that are exported from another resource that contain a large volume of data. The information and data on these exported files can be easily integrated or copied into the database. These include the following within the database:
	- Maverik Fleet Reports
	- Maintenance
	- Repairs
3. **Employee Knowledge:** sources of information that are understood and known by the maintainers about vehicles within the database. This includes the following:
	- Notes
	- Pictures
	- Characteristics

>[!INFORMATION]
>_Mileage Numbers_ - Drivers sometimes do not record accurate odometer readings. The data from Maverik Fleet has been trimmed and cleaned for obvious outliers, but the data isn't 100% reliable due to this fact.

## Tables

Other than the overview page, each sheet within the workbook will have an Excel table that captures the data related to the sheet. Tables in Excel provide quick lookups across columns, built-in statistical analysis options, and come with a set of operations out of the box that make them extremely useful for vehicle data.

Each sheet's table is named, which means you can call its name when creating functions or references without having to remember cell addresses. Each table is named exactly the sheet name. This also makes existing functions and references more human-readable. Refer to the [Microsoft Overview of Tables](https://support.microsoft.com/en-us/excel/overview-of-excel-tables) to get a better understanding.

### Adding Rows to Tables

To add additional rows to an existing table, you have a few options:

1. Find the corner right end arrow and drag down to increase table rows.
2. Insert a row somewhere within the table row space to expand the table.

If there is data directly below or if there isn't enough space to expand the table to the desired size by dragging the corner angle on the table, simply insert more rows below the table and then perform the table size increase.

![Excel Table Add](/images/excel-table-add.gif)

Once an available row has opened up, fill out all the possible information available pertaining to the table, under the uncolored columns. Remember, the color coded columns contain data that is calculated or referenced, do not change data in these columns! Maintainers are always welcome to come back to a table or row and continue entering necessary data.

### Deleting Rows to Tables

To delete rows to an existing table, you have a few options:

1. Find the corner right end arrow and drag up, clearing its data, deleting the bottom row.
2. Clear the row's data at the bottom row, then drag up to eliminate the empty row
3. Clear a row's data, sort by a column to get the empty row at the bottom, and drag up.

> [!WARNING]
> When deleting an existing row in the middle of a table, ensure that there is no other data to the sides in the sheet that could be affected by the row deletion.

![Excel Table Delete](/images/excel-table-delete.gif)

### Updating Data in Tables

Data in tables simply exist. This means you can edit any value at any time in an Excel table. Keep in mind for the Vehicle Database, any column data that is colored is data that is calculated, referenced, or includes a function.

> [!CAUTION]
> Colored column headers in the Vehicle Database refer to data that is calculated, referenced, or includes a function. Do not edit data within these columns!

![Excel Table Update](/images/excel-table-update.gif)

### Sorting by Columns

Tables can utilize a dropdown button that automatically pulls up a filter menu for users to customize. The ascending and descending options are commonly utilized, but users can select or deselect specific values within that column to filter by.

Filtering a table does not affect or change any of the data inside of it, Excel is just sorting it based on the criteria entered in the filter menu. Users can always `CTRL + z` to undo a filter they accidentally applied. Feel free to use filters across all database tables.

![Excel Table Filter](/images/excel-table-filter.gif)

### Column Information

Almost every column of every table are self-explanatory and should be immediately obvious what they mean or do. However, there are a few columns where the data source or purpose may not be clear. The following table aims to explain those columns and what they do.

| Table(s)                                             | Column Name          | Purpose                                                                                      |
| ---------------------------------------------------- | -------------------- | -------------------------------------------------------------------------------------------- |
| `Vehicles`                                           | `Type`               | Designate a specific type of vehicle, more specific than class                               |
| `Vehicles`                                           | `Class`              | Broad class of the vehicle, i.e. Car, Truck, Trailer, Equipment.                             |
| `Vehicles`                                           | `CC`                 | Engine size, in Cubic Centimeters (CC).                                                      |
| `Vehicles`                                           | `Maverik`            | Vehicle-specific associated Maverik pin or number.                                           |
| `Vehicles`                                           | `Registration URL`   | The actual web address of the registration file.                                             |
| `Vehicles`                                           | `IMEI`               | GPS enabled vehicle tracking number.                                                         |
| `Vehicles`                                           | `Delimited`          | Helper column for creating key tag labels.                                                   |
| `Drivers`                                            | `Maverik Standalone` | If the driver has their own Maverik card, separate from any assigned vehicle.                |
| `Maintenance`, `Recalls`                             | `Highlight`          | Highlight the row in the Vehicles table where applicable, purely for visualization purposes. |
| `Maintenance`, `Inspections`, `Recalls`, `Accidents` | `Follow-Up`          | Checkbox meaning the assigned viewer or user should follow up on this item.                  |
| `Repairs`                                            | `Case ID`            | The case ID of an accident if this repair is related to that accident.                       |
| `Inspections`                                        | `Inspector`          | Name of the individual who inspected.                                                        |
| `Recalls`                                            | `Recall ID`          | Any ID number associated with the recall.                                                    |
| `Recalls`                                            | `Reconciled`         | Checkbox for understanding if the recall has been handled for associated vehicles.           |
| `Accidents`                                          | `Case URL`           | The web address of the police case docs for the accident if stored.                          |
| `Accidents`                                          | `Insurance URL`      | The web address for the insurance claim docs for the accident if stored.                     |

## Data Analysis Date Window

On the `Overview` page, every filtered table view with a header that includes an asterisk (\*), calculates data from today's date, back through the date that is configured in the `Configuration` table under the `Data Age` value. If users wish to see data through a specific date window, modify this value.

{{< callout type="info" >}}
  Modify the `Data Age` value to modify the data window across the workbook!
{{< /callout >}}

## Excel Filter/Array Spills

On the `Overview` page, there are numerous pre-built filtered views that incorporate data from all the database tables. When the database grows, more rows can be found in each one of those filtered views, and may run into the data that is below it. Excel will show this as a `#SPILL!` error. 

To overcome this error on the `Overview` page, simply insert more rows below the `#SPILL!` error until there is enough room for the filter or array to occupy.

![Excel Table & Array Spill](/images/excel-table-spill.gif)

## Conclusion

Should any users or viewers have any recommendations or questions about navigating the workbook, making sense of the data, or anything about the Vehicle Database itself, direct those to the workbook owner, as listed in the `Roles & Permissions` section of the overview page.

_Thank you for visiting!_