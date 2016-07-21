# UIB

This is a set of components to use Interbase and FireBird with Delphi or Freepascal.

# Changes from Upstream:

* Firebird 3 Release headers translated to Pascal (probably catched up by hgourvest, did not compared yet)
* Firebird 3 BOOLEAN support (probably catched up by hgourvest, did not compared yet)
* support for BLOBs in SP-like statements: INSERT-RETURNING, UPDATE-RETURNING, DELETE-RETURNING, UPDATE-OR-INSERT-RETURNING
* fixed AV when UIBQuery used in some VCL DB-Aware grids
