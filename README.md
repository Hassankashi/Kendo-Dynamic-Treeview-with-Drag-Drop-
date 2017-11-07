# Kendo-Dynamic-Treeview-with-Drag-Drop-
Dynamic Treeview with Drag and Drop by Kendo
I strongly recommend you to read this article:
https://www.codeproject.com/Articles/799559/Dynamic-Treeview-with-Drag-and-Drop-by-Kendo


Dynamic treeview with drag and drop is useful whenever you need to arrange employer or documents according to particular nested hierarchy. Assume one personnel in organization should report his or her tasks to upper manager and this manager has another upper manager and so on. In the other example, you want to arrange documents and define their parents such as { Finance -->Salary -->Personal} or { office -->letter -->import }. Kendoui treeview has the ability for drag and drop but in their example they used static string in json format such as [{ id: "1", text: "P1", items: [{ id: "5", text: "P2"}] }] that you should pass this string to kendo treeview data source. I write a method to generate these json to pass data source and after you change node location (parent), it will be saved.

