# Profile Type 
By default, this SA only looks at the `IoT` device profile. This may or may not be the profile name required in your environment. 
To edit it, first clone the default search (see [Clone Saved Search](clone-search.md)) and then edit the first line. For example, if
you want *all* device profiles, change the line from:

```python
`pan_iot_index` sourcetype="pan:iot_device" profile_type=IoT
```
to:
```python
`pan_iot_index` sourcetype="pan:iot_device" profile_type=*
```
