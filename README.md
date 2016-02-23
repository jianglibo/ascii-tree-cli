# ascii-tree-cli

convert one asciitree.

```shell
npm install -g ascii-tree-cli

//to file
asciitree -i demo.txt -o demo.processed.txt

//to console,then copy and paster.
asciitree -i demo.txt
```

## input format

```
-start-
firstlevel
-sec
--third
-sec
--third
---fourth
firstlevel
-end-
```

out:
```
├── firstlevel
|   ├── sec
|   |   └── third
|   └── sec
|       └── third
|           └── fourth
└── firstlevel
```
