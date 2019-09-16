# Avro to PHP

:construction: This is a work-in-progress! :construction:

Compile Avro .avsc files into usable PHP classes.

### Installation
```bash
composer require chasdevs/avro-to-php
```

### Usage
```bash
vendor/bin/avro-to-php compile dir/with/avsc/
```

### Roadmap

- [x] Basic Records
- [x] Arrays
- [x] Unions
- [x] CLI
- [x] Defaults
- [x] Enums
- [x] Logical types (only tested with timestamp-millis)
- [ ] Maps
- [ ] Fixed
- [ ] Sort Order
- [ ] Aliases
- [ ] Serialization Tests