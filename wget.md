Wget - The non-interactive network downloader.
==============================================
People tend to install `curl` to fresh ubuntu machines to be able to make HTTP
GET requests and redirect to stdout when in fact you can effectively do the
same thing with `wget` using the `-q` and `-O` parameters.

```
wget -qO- http://example.org/
```

The `-q` flag tells wget to fetch the document "quietly" that is without any
UI in the terminal and the `-O` flag tells it to output the results to a
stream, in our case to "-" which is here interpreted as stdout.
