The entities extension combines a number of changes to refactor organization handling:

* Adding a top-level section called entities which will consist of an array of organization objects. All organizations who are part of a contracting process in any form should be included here.

* Adding an id field to the top level of the organization object. id should be used to cross-reference to the organization whenever it occurs.

* Adding role as a field of organization with a codelist of organization roles (buyer, supplier, procuringEntity, etc.)

* Deprecating the use of full organization blocks in buyer, supplier, procuringEntity and other locations, and replacing with a block containing: id and name. 

Refer to the [Github issue](https://github.com/open-contracting/standard/issues/368) for more details.