# unity-empty-template

## Contributing
Fork the `main` branch and clone your fork. Setup [git lfs](https://git-lfs.github.com) by running `git lfs install`. Setup Unity's merge tool in your local repository's git config (`.git\config`):

```
[merge]
	tool = unityyamlmerge
[mergetool "unityyamlmerge"]
	trustExitCode = false
	# Replace with your editor's installation path
	cmd = 'C:\\Program Files\\Unity\\Hub\\Editor\\UNITY_VERSION\\Editor\\Data\\Tools\\UnityYAMLMerge.exe' merge -p "$BASE" "$REMOTE" "$LOCAL" "$MERGED"
```
