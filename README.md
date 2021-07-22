# Tips on Elastic Certified Engineer Exam

![outline full mapping](./artwork/outline.png)

Relationships among `Elastic Training Lessons`, `Elastic Exam Objectives`, and `Elastic Docs`

## Presentations
[📝 Tips on Elastic Certified Engineer Exam (Chinese Version)](Tips%20on%20Elastic%20Certified%20Engineer%20Exam%20-%20CN.pdf)

[📝 Tips on Elastic Certified Engineer Exam (English Version)](Tips%20on%20Elastic%20Certified%20Engineer%20Exam%20-%20EN.pdf)

## Self-Learning Path
[📝 Reorder Exam Objectives (XLSX Version)](./outline/outline.xlsx)

[📝 Reorder Exam Objectives (PDF Version)](./outline/outline.pdf)
## Docker Environments

| File                        | Description
| ---                         | --
| `single_node.yml`           | simple node env
| `node_role.yml `            | cluster and node role env
| `elastic_security.yml`      | elastic stack security env
| `backup_and_recovery.yml`   | backup and recovery env
| `cross_cluster_search.yml`  | cross cluster search env
| `shard_allocation.yml`      | shard allocation env

## How to Use

Startup a testing environment in foreground:

```
docker-compose -f your_config_file.yml up
```

Or Startup a testing environment in background:

```
docker-compose -f your_config_file.yml up -d
```

Shutdown a testing environment:

```
docker-compose -f your_config_file.yml down
```
Or Shutdown a test environment and delete all data:

```
docker-compose -f your_config_file.yml down -v
```