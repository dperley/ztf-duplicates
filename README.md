# ztf-duplicates

This is an extremely basic schema to tag duplicate ZTF candidate identifiers.  ZTF normally associates all spatially consistent alerts under a 12-letter identifier (for example, ZTF20abcdefg) that serves as the internal name for the transient.  Occasionally (due to bad focus, bad seeing, or astrometric errors), the same transient will be given a second duplicated name.  This can lead to accidental duplication of effort and "double-counting".

To avoid this, the most recently-generated identifier of a duplicated transient/variable source can be tagged as "Duplicate" to prominently indicate that it is a duplicate ID.  If this tag is present on a Fritz source page, the user should refer to the source page under the original identifier instead.  The duplicate ID should be ignored for rate calculations.

This is set up as a tdtax taxonomy, but for the time being it is a trivial taxonomy as only one taxon is present ("Duplicate").

Be careful not to tag both members of a duplicated transient as "Duplicate".  The original identifier should not be tagged under this taxonomy.  Events with no duplicates should also not be tagged.
