# Dataproc Persistent History Server
This repo houses the example code for a blog post on using a persistent history
server to retain infomation about your Spark and Hadoop jobs that ran on short-lived
clusters.

## Directory structure

- `cluster_templates/`
  - `history_server.yaml`
  - `ephemeral_cluster.yaml` 
- `init_actions`
  - `disable_history_servers.sh`
- `workflow_templates`
  - `spark_mr_workflow_template.yaml`
