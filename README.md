# How to use AutoSuggestEdit with InfiniteAsyncSource

This example demonstrates how to use [GridControl](https://docs.devexpress.com/WPF/DevExpress.Xpf.Grid.GridControl) with [InfiniteAsyncSource](https://docs.devexpress.com/WPF/10803/controls-and-libraries/data-grid/binding-to-data/binding-to-any-data-source-with-virtual-sources) as a drop-down control. We set [FixedFilter](https://docs.devexpress.com/WPF/DevExpress.Xpf.Grid.DataControlBase.FixedFilter) to filter the **GridControl** items. The current filter value depends on the text entered by a user. We create the filter in the **GetFilter** method, and you can change this method implementation according to your needs. 

See also:

[How to populate AutoSuggestEdit asynchronously](https://github.com/DevExpress-Examples/How-to-populate-AutoSuggestEdit-asynchronously)
