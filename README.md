Sapient Machine
<pre>
  pip install sapient-machine
</pre>
Then:
```Python
  # Python
  import sapient_machine
```
Or:
```bash
  echo '[{"role": "user", "content": "I have a question..."}]' | \
  uvx sapient-machine \
    --PROVIDER_API_KEY=sk-ant-api... \
    --GITHUB_TOKEN=ghp_... \
    --mode=single
```
