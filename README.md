python-mot-sls
==============

Plugin to the `python-msc` library to handle DAB Slideshow encoding as per ETSI TS 101 499.

# Dependencies

* `python-mot`

# Utilities

# Examples

Creating an MOT object and adding parameters

```python
from mot import MotObject

object = MotObject(data, ContentType.IMAGE_JFIF)
object.add_parameter(Trigger(trigger))
object.add_parameter(AlternativeLocation(url))
```
