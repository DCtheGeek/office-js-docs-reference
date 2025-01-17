| Class | Fields | Description |
|:---|:---|:---|
|[BindingCollection](/javascript/api/excel/excel.bindingcollection)|[getCount()](/javascript/api/excel/excel.bindingcollection#getcount--)|Gets the number of bindings in the collection.|
||[getItemOrNullObject(id: string)](/javascript/api/excel/excel.bindingcollection#getitemornullobject-id-)|Gets a binding object by ID.|
|[ChartCollection](/javascript/api/excel/excel.chartcollection)|[getCount()](/javascript/api/excel/excel.chartcollection#getcount--)|Returns the number of charts in the worksheet.|
||[getItemOrNullObject(name: string)](/javascript/api/excel/excel.chartcollection#getitemornullobject-name-)|Gets a chart using its name.|
|[ChartPointsCollection](/javascript/api/excel/excel.chartpointscollection)|[getCount()](/javascript/api/excel/excel.chartpointscollection#getcount--)|Returns the number of chart points in the series.|
|[ChartSeriesCollection](/javascript/api/excel/excel.chartseriescollection)|[getCount()](/javascript/api/excel/excel.chartseriescollection#getcount--)|Returns the number of series in the collection.|
|[NamedItem](/javascript/api/excel/excel.nameditem)|[comment](/javascript/api/excel/excel.nameditem#comment)|Specifies the comment associated with this name.|
||[delete()](/javascript/api/excel/excel.nameditem#delete--)|Deletes the given name.|
||[getRangeOrNullObject()](/javascript/api/excel/excel.nameditem#getrangeornullobject--)|Returns the range object that is associated with the name.|
||[scope](/javascript/api/excel/excel.nameditem#scope)|Specifies if the name is scoped to the workbook or to a specific worksheet.|
||[worksheet](/javascript/api/excel/excel.nameditem#worksheet)|Returns the worksheet on which the named item is scoped to.|
||[worksheetOrNullObject](/javascript/api/excel/excel.nameditem#worksheetornullobject)|Returns the worksheet on which the named item is scoped to.|
|[NamedItemCollection](/javascript/api/excel/excel.nameditemcollection)|[add(name: string, reference: Range \| string, comment?: string)](/javascript/api/excel/excel.nameditemcollection#add-name--reference--comment-)|Adds a new name to the collection of the given scope.|
||[addFormulaLocal(name: string, formula: string, comment?: string)](/javascript/api/excel/excel.nameditemcollection#addformulalocal-name--formula--comment-)|Adds a new name to the collection of the given scope using the user's locale for the formula.|
||[getCount()](/javascript/api/excel/excel.nameditemcollection#getcount--)|Gets the number of named items in the collection.|
||[getItemOrNullObject(name: string)](/javascript/api/excel/excel.nameditemcollection#getitemornullobject-name-)|Gets a NamedItem object using its name.|
|[PivotTableCollection](/javascript/api/excel/excel.pivottablecollection)|[getCount()](/javascript/api/excel/excel.pivottablecollection#getcount--)|Gets the number of pivot tables in the collection.|
||[getItemOrNullObject(name: string)](/javascript/api/excel/excel.pivottablecollection#getitemornullobject-name-)|Gets a PivotTable by name.|
|[Range](/javascript/api/excel/excel.range)|[getIntersectionOrNullObject(anotherRange: Range \| string)](/javascript/api/excel/excel.range#getintersectionornullobject-anotherrange-)|Gets the range object that represents the rectangular intersection of the given ranges.|
||[getUsedRangeOrNullObject(valuesOnly?: boolean)](/javascript/api/excel/excel.range#getusedrangeornullobject-valuesonly-)|Returns the used range of the given range object.|
|[RangeViewCollection](/javascript/api/excel/excel.rangeviewcollection)|[getCount()](/javascript/api/excel/excel.rangeviewcollection#getcount--)|Gets the number of RangeView objects in the collection.|
|[Setting](/javascript/api/excel/excel.setting)|[delete()](/javascript/api/excel/excel.setting#delete--)|Deletes the setting.|
||[key](/javascript/api/excel/excel.setting#key)|The key that represents the id of the Setting.|
||[value](/javascript/api/excel/excel.setting#value)|Represents the value stored for this setting.|
|[SettingCollection](/javascript/api/excel/excel.settingcollection)|[add(key: string, value: string \| number \| boolean \| Date \| Array<any> \| any)](/javascript/api/excel/excel.settingcollection#add-key--value-)|Sets or adds the specified setting to the workbook.|
||[getCount()](/javascript/api/excel/excel.settingcollection#getcount--)|Gets the number of Settings in the collection.|
||[getItem(key: string)](/javascript/api/excel/excel.settingcollection#getitem-key-)|Gets a Setting entry via the key.|
||[getItemOrNullObject(key: string)](/javascript/api/excel/excel.settingcollection#getitemornullobject-key-)|Gets a Setting entry via the key.|
||[items](/javascript/api/excel/excel.settingcollection#items)|Gets the loaded child items in this collection.|
||[onSettingsChanged](/javascript/api/excel/excel.settingcollection#onsettingschanged)|Occurs when the Settings in the document are changed.|
|[SettingsChangedEventArgs](/javascript/api/excel/excel.settingschangedeventargs)|[settings](/javascript/api/excel/excel.settingschangedeventargs#settings)|Gets the Setting object that represents the binding that raised the SettingsChanged event|
|[TableCollection](/javascript/api/excel/excel.tablecollection)|[getCount()](/javascript/api/excel/excel.tablecollection#getcount--)|Gets the number of tables in the collection.|
||[getItemOrNullObject(key: string)](/javascript/api/excel/excel.tablecollection#getitemornullobject-key-)|Gets a table by Name or ID.|
|[TableColumnCollection](/javascript/api/excel/excel.tablecolumncollection)|[getCount()](/javascript/api/excel/excel.tablecolumncollection#getcount--)|Gets the number of columns in the table.|
||[getItemOrNullObject(key: number \| string)](/javascript/api/excel/excel.tablecolumncollection#getitemornullobject-key-)|Gets a column object by Name or ID.|
|[TableRowCollection](/javascript/api/excel/excel.tablerowcollection)|[getCount()](/javascript/api/excel/excel.tablerowcollection#getcount--)|Gets the number of rows in the table.|
|[Workbook](/javascript/api/excel/excel.workbook)|[settings](/javascript/api/excel/excel.workbook#settings)|Represents a collection of Settings associated with the workbook.|
|[Worksheet](/javascript/api/excel/excel.worksheet)|[getUsedRangeOrNullObject(valuesOnly?: boolean)](/javascript/api/excel/excel.worksheet#getusedrangeornullobject-valuesonly-)|The used range is the smallest range that encompasses any cells that have a value or formatting assigned to them.|
||[names](/javascript/api/excel/excel.worksheet#names)|Collection of names scoped to the current worksheet.|
|[WorksheetCollection](/javascript/api/excel/excel.worksheetcollection)|[getCount(visibleOnly?: boolean)](/javascript/api/excel/excel.worksheetcollection#getcount-visibleonly-)|Gets the number of worksheets in the collection.|
||[getItemOrNullObject(key: string)](/javascript/api/excel/excel.worksheetcollection#getitemornullobject-key-)|Gets a worksheet object using its Name or ID.|
