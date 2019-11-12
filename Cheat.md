Pull all subdirectory
```sh
find . -type d -depth 1 -exec git --git-dir={}/.git --work-tree=$PWD/{} pull origin master \;
```

Reformat in vim for a nice column layout CSV
```sh
pip3 install tablign
```

```
:'<,'>:!tablign
```
