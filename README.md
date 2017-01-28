<p align="center">
  <h1 align="center">default-datasources</h1>
  <p align="center">A Collections of Datasources for the develop of website's using <a href="https://www.storyblok.com" target="_blank">Storyblok</a>.</p>
</p>
<br>

## What is default-datasources
Datasources enables you to use a specific set of data (countrylists, grid-widths or any other key/value paired source) in a single & multi choice field type in the [Storyblok](https://www.storyblok.com) component part editor.


## Format
The format for the key / value pairs in [Storyblok](https://www.storyblok.com) looks like this:

```
[
 {
   "name":"DISPLAYED_NAME",
   "value":"SAVED/DELIVERED_VALUE"
 }
]
```

## How to use a Datasource
<p align="center">
<img src="https://a.storyblok.com/f/40044/3a239450ea/ezgif-com-10707cd7eb.gif" alt="How to use a datasource">
</p>

## What about the `Datasources` in [Storyblok](https://www.storyblok.com) itself?
If you have Datasources which should be only for one project and will change for the next (catgories, ...). You can also use those Datasources in single & multi choices and access it using the Delivery API as descriped in our [Delivery API / Datasource Entries Documentation](https://www.storyblok.com/docs/Delivery-Api/Datasource-Entries).
