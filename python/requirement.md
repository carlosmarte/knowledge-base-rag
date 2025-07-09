# Using pipreqs (Only Includes Imported Packages)
- `pip install pipreqs`
- `pipreqs . --savepath requirements.txt`

```sh
pip install uvicorn
pip freeze | grep uvicorn >> requirements.txt
```
