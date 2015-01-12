# consul_do-cookbook

TODO: Enter the cookbook description here.

## Supported Platforms

TODO: List your supported platforms.

## Attributes

<table>
  <tr>
    <th>Key</th>
    <th>Type</th>
    <th>Description</th>
    <th>Default</th>
  </tr>
  <tr>
    <td><tt>['consul_do']['bacon']</tt></td>
    <td>Boolean</td>
    <td>whether to include bacon</td>
    <td><tt>true</tt></td>
  </tr>
</table>

## Usage

### consul_do::default

Include `consul_do` in your node's `run_list`:

```json
{
  "run_list": [
    "recipe[consul_do::default]"
  ]
}
```

## License and Authors

Author:: Burberry, LTD (<fraser.scott@burberry.com
>)
