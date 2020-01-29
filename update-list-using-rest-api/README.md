# Update a SharePoint List using REST API

## Summary
An alternate way to update a SharePoint list especially when there are required columns on the list and only one or two columns are to be updated.

![Update s SharePoint List using REST API](./update-list-using-rest-api.png)

## Requirements
Make sure to change the following:
1. **`Uri`** field
   1. Change `listItem` to the name of your list. If the list's name has spaces, use %20 for each space

1. **`Body`**
   1. `SP.Data.listNameListItem` - change the `listName` part to your list name
   1. `columnName1` to the first column name
   1. `value1` to the desired value for column 1
   1. you can continue listing more columns. Make sure to use commas to separate the pairs. Make sure to remove the comma if you are updating just one column.

### Authors
- Riu Baring

## Version History
Version|Date|Comments
-------|----|--------
1.0|January 8, 2020|Initial release

## Disclaimer
**THIS CODE IS PROVIDED *AS IS* WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING ANY IMPLIED WARRANTIES OF FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR NON-INFRINGEMENT.**

## Additional Notes
None
