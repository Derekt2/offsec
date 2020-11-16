# offsec
handy things i may need

# Server.py

python server that logs headers to stdout in addition to source ip, date, time, etc.

Make a new directory, place an image in it, and run server.py. When making maldocs place a internet loaded image in it loading the url to the image. This will reveal who opens the doc (in case they don't activate macros or it's caught by AV).

Remember to kill the server after you're done hosting it.
```
Go to Insert - Quick Parts - Field...
In Field Names, select "InsertPicture".
In the field "Filename or URL", put the URL to your image.
Check "Data not stored in document". 
```

```
python3 server.py |tee server_logs.txt
```

