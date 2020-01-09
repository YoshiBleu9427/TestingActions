# TestingActions
Testing CI for making zips and artifacts

The goal is to setup CI in such a way that you can download a specific directory (files_to_zip) as a zip archive.

---

### Use case

Given directory `files_to_zip`, like this:
```
files_to_zip
 |_ hello.txt
 \_ main.c
```
Person modifies file `files_to_zip/hello.txt`; then pushes

Then using an unchanging link, Person downloads `files_to_zip.zip`
```
files_to_zip.zip
 |_ hello.txt
 \_ main.c
```
