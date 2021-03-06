4d-plugin-opc
=============
A plugin to read and write DOCX, XLSX, PPTX files in 4D.

Implementation of [libopc](http://libopc.codeplex.com) by Florian Reuter.

How to use
----------
Please consult the [wiki](https://github.com/miyako/4d-plugin-opc/wiki).

##Platform

| carbon | cocoa | win32 | win64 |
|:------:|:-----:|:---------:|:---------:|
|🆗|🚫|🆗|🆗|

Commands
---

```c
// --- OPC Constants
OPC_Document_type
OPC_Relation_type

// --- OPC Resource
OPC_Get_resource
OPC_RESOURCE_LIST
OPC_Get_resource_size
OPC_Delete_resource
OPC_Set_resource
OPC_EXTERNAL_RESOURCE_LIST

// --- OPC Relation
OPC_Create_relation
OPC_Remove_relation
OPC_Create_external_relation
OPC_RELATION_LIST

// --- OPC Document
OPC_Get_document_type
OPC_RESOURCE_TYPE_LIST
OPC_EXTERNAL_TARGET_LIST
OPC_EXTENSION_LIST
OPC_Register_resource_type
OPC_RELATION_TYPE_LIST
```

Dependency
----------
Modified libopc, to accept Unicode file paths on Windows.  
Standard libiconv, libxml2, zlib included in package.
