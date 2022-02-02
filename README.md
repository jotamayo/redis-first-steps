# redis-first-steps

- Install kafka in mac with brew

```
brew install kafka
```

- Installation paht

```
/usr/local/Cellar/zookeeper
/usr/local/Cellar/kafka
```

- File configuration path

```
/usr/local/etc/kafka/server.properties
/usr/local/etc/kafka/zookeeper.properties
```

- Running zookeeper and kafka with brwe

```
brew services start zookeeper
brew services start kafka
```

- View list service

```
brew services list

kafka          started main ~/Library/LaunchAgents/homebrew.mxcl.kafka.plist
zookeeper      started main ~/Library/LaunchAgents/homebrew.mxcl.zookeeper.plist
```
