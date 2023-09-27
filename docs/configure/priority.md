# Priority Field

!!!primary To update the `priority` field modify the `Palo Alto IoT Devices - Lookup Gen` saved search. It is recommended to clone the default search before making changes (see [Clone Saved Search](clone-search.md)).
!!!

The priority field is very generic by default and should be updated to suit your environment. The following table describes how this field is set.

Default priority field definition

```python
priority=lower(risk_level)
```
The risk_level field is a default field provided by the Palo Alto IoT data feed - it represents how "risky" the IoT Asset is considered.
