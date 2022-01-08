#  fron here:

https://www.serverless.com/blog/flask-python-rest-api-serverless-lambda-dynamodb/


Serverless: Running docker run --rm -v /Users/marilynwaldman/Library/Caches/serverless-python-requirements/726f7f9aab2be99d8b6530264c27dddd4bacf3c0528b62467ff495a5afeb087d_x86_64_slspyc\:/var/task\:z -v /Users/marilynwaldman/Library/Caches/serverless-python-requirements/downloadCacheslspyc\:/var/useDownloadCache\:z -u 0 lambci/lambda\:build-python3.6 python3.6 -m pip install -t /var/task/ -r /var/task/requirements.txt --cache-dir /var/useDownloadCache...
 
 Error ---------------------------------------------------
 
  Error: `docker run --rm -v /Users/marilynwaldman/Library/Caches/serverless-python-requirements/726f7f9aab2be99d8b6530264c27dddd4bacf3c0528b62467ff495a5afeb087d_x86_64_slspyc:/var/task:z -v /Users/marilynwaldman/Library/Caches/serverless-python-requirements/downloadCacheslspyc:/var/useDownloadCache:z -u 0 lambci/lambda:build-python3.6 python3.6 -m pip install -t /var/task/ -r /var/task/requirements.txt --cache-dir /var/useDownloadCache` Exited with code 1
      at ChildProcess.<anonymous> (/Users/marilynwaldman/my-flask-application/node_modules/child-process-ext/spawn.js:38:8)
      at ChildProcess.emit (node:events:378:20)
      at ChildProcess.EventEmitter.emit (node:domain:470:12)
      at maybeClose (node:internal/child_process:1067:16)
      at Process.ChildProcess._handle.onexit (node:internal/child_process:301:5)
 
     For debugging logs, run again after setting the "SLS_DEBUG=*" environment variable.
 



