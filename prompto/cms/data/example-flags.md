This is the representation of glazed flags in a YAML file
describing a command.

These flags are used to configure command line flags.

```yaml
  - name: order_number
    type: stringList
    help: Order number
  - name: from
    type: date
    help: From date
  - name: to
    type: date
    help: To date
  - name: status
    type: stringList
    help: Order status
  - name: created_via
    type: stringList
    help: Created via
  - name: created_by
    type: stringList
    help: Created by
  - name: customer
    type: stringList
    help: Customer email
  - name: limit
    type: int
    default: 50
    help: Limit
  - name: offset
    type: int
    default: 0
    help: Offset
  - name: order_by
    type: string
    default: order_date DESC
    help: Order by
  - name: type
    type: choice
    choices:
      - prime
      - scheduled
      - normal
```
