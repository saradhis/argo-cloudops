## argo-cloudops sync

Syncs a project target using a manifest in git

```
  argo-cloudops sync [flags]
```

### Flags

```
  -h, --help                  help for sync
  -p, --path string           Path to manifest within git repository
  -n, --project_name string   Name of project
  -s, --sha string            Commit sha to use when creating workflow through git
  -t, --target string         Name of target
```