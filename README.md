# submodule-link-bug
Github submodules bug, no relalitive submodules link

## How reproduce
Add a submodule using full path

```
git submodule add git@github.com:DavidUser/submodule-link-bug-reference.git full-path-url
```

Add a submodulel using a relative path
```
git submodule add ../submodule-link-bug-reference relative-path-url
```

On git both submodule links will brigh the repository https://github.com/DavidUser/submodule-link-bug-reference, but on github that not create a link to a natural navigation.
