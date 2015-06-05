# ecs-haproxy-cassandra-cluster-cookbook


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
    <td><tt>['ecs-haproxy-cassandra-cluster']['bacon']</tt></td>
    <td>Boolean</td>
    <td>whether to include bacon</td>
    <td><tt>true</tt></td>
  </tr>
</table>

## Usage

### ecs-haproxy-cassandra-cluster::default

Include `ecs-haproxy-cassandra-cluster` in your node's `run_list`:

```json
{
  "run_list": [
    "recipe[ecs-haproxy-cassandra-cluster::default]"
  ]
}
```

## License and Authors

Author:: Vinay Selvaraj (vinay@selvaraj.com)
