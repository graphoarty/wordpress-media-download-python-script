# Download all Media from Wordpress Website

A python script to download all media from a Wordpress website.

# How to use?

Open the file in a code editor.

Edit the global variables.

```python
website_url = 'http://your-wordpress-site.com'
time_betweendownload_requests = 1 # second - use this to not wreck havoc on the website.
output_directory = 'C:/your/output/directory'
```

```python
pip install -r requirements.txt
```

```python
python root.py
```

---0.0.1 - Tested to support images
