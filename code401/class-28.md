#  RecyclerView

## Create dynamic lists with RecyclerView

Facilitate displaying large sets of data.

***Recycles*** those individual elements. When an item scrolls off the screen, RecyclerView doesn't destroy its view. Instead, RecyclerView reuses the view for new items that have scrolled onscreen. This reuse vastly improves performance, improving your app's responsiveness and reducing power consumption.

`ViewGroup` -> `RecyclerView` -> `ViewHolder` -> `Adapter` -> `LayoutManager`.

#### You can arrange items 
1. `LinearLayoutManager`; one dimensional list.
2. `GridLayoutManager ` or `StaggeredGridLayoutManager`; two dimensional list.

#### Defining adapter ,, overriding:
1. `onCreateViewHolder()`
2. `onBindViewHolder()`
3. `getItemCount()`



Reference:

* [RecyclerView for displaying lists of data](https://developer.android.com/guide/topics/ui/layout/recyclerview#java)