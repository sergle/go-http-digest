# go-http-digest
Imported code from https://code.google.com/p/mlab-ns2/

This repo exctacted only used module (digest) without other files from mlab-ns2 repo

Used for digest HTTP authentication.
Issue fixed:
- POST request lost Body content:  http: Request.ContentLength=... with Body length 0
- goroutine leak

