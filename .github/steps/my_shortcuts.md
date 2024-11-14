## Uninstall the packages in the  `pip freeze`



```
pip freeze | grep -v ' @ ' | xargs pip uninstall -y
```
