# Machine name
Machine description
<pre>
  pip install machine-name
</pre>
Then:
```Python
  # Python
  import machine_name
```
Or:
```bash
  echo '[{"role": "user", "content": "I have a question..."}]' | \
  uvx machine-name \
    --PROVIDER_API_KEY=sk-ant-api... \
    --GITHUB_TOKEN=ghp_... \
    --mode=single
```
