## Get
- `Get` operation is used to get data from the `remote` process and return data to the calling process.
-  `Put` and `Get` calls need to be separated by `MPI.Win_fence` for synchronization.
- Not an **[[Important terms#^atomic|atomic operation]]**.