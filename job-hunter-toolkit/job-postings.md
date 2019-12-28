To actually search the hundreds of job sources, we will use the following command:

> **Note:** this could take several minutes depending on your internet connection. In many cases it is best to redirect the program's output to a file to cache the results.

### Run Commands

`job-hunter-toolkit job-postings`{{execute}}

To redirect the output of the application to a file:

`job-hunter-toolkit job-postings > /tmp/job-postings`{{execute}}

Then we can use tools like [`cat`](https://en.wikipedia.org/wiki/Cat_(Unix) and [`grep`](https://en.wikipedia.org/wiki/Grep) the file to filter the results:

`cat /tmp/job-postings | grep -i "python"`{{execute}}
