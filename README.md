### Chapar Data Structure Sample

This repository contains a sample of Chapar data structure. its in yaml format. and do not have any real data. just a sample of how chapar data structure looks like.

This data is located in `chapar` directory. which base on your os you can find it in :

Linux and MacOS
```
    $HOME/.config/chapar
```

Windows
```
    %APPDATA%\chapar
```

for more information it please check [Chapar filesystem code](https://github.com/chapar-rest/chapar/blob/bb514d1d539c0cbd8e0dd2c89c592c74e31c1871/internal/repository/filesystem.go#L694)

### Repostory File Structure

```
.
├── Default Workspace
│   ├── _workspace.yaml
│   ├── collections
│   ├── envs
│   ├── preferences
│   │   └── preferences.yaml
│   └── requests
├── Personal Workspace
│   ├── _workspace.yaml
│   ├── collections
│   │   ├── Auth API
│   │   │   ├── Login.yaml
│   │   │   ├── Register User (copy).yaml
│   │   │   ├── Register User.yaml
│   │   │   └── _collection.yaml
│   │   ├── Certs API
│   │   │   ├── Get Private Keys.yaml
│   │   │   ├── Get Public Keys.yaml
│   │   │   └── _collection.yaml
│   │   ├── ID API
│   │   │   ├── Generate ID.yaml
│   │   │   ├── Get Types.yaml
│   │   │   └── _collection.yaml
│   │   ├── Todo API
│   │   │   ├── Create Comment.yaml
│   │   │   ├── Create Task.yaml
│   │   │   ├── Delete Comment.yaml
│   │   │   ├── Delete Task.yaml
│   │   │   ├── Get Comment.yaml
│   │   │   ├── Get Comments.yaml
│   │   │   ├── Get Task.yaml
│   │   │   ├── Get Tasks.yaml
│   │   │   ├── Update Comment.yaml
│   │   │   ├── Update Task.yaml
│   │   │   └── _collection.yaml
│   │   └── WhoAmI
│   │       ├── _collection.yaml
│   │       └── whoami.yaml
│   ├── envs
│   │   ├── Local.yaml
│   │   └── Stage.yaml
│   ├── preferences
│   │   └── preferences.yaml
│   └── requests
│       ├── New Request.yaml
│       └── New Request1.yaml
└── config.yaml
```

