# qa-week-2

#Testing, Planning, Maintenance, and Layers Exercise



## Test Summary:

The app is greatly improved over the previous version. ID discrepancy has been resolved. Field length restrictions and content restrictions have been implemented. Title field still needs length restriction, see below. Overall quite a bit of work has been done, the app is a lot closer to completion.

1. Entering too long a string in the Name field triggers warnings for the Name field and the Title field at the same time

2. Entering too long a string in the Title field does not trigger any warning. Invalid entries are accepted

Boundary Value Analysis: Phone number


|Invalid|Invalid|Valid|Invalid|
|---|---|---|---|
|0 to 9 digits |9 digits |10 digits |11 digits|
