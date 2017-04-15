# box_CIs_parallel
Example using CircleCI parallelism 


### Running Notes

* Easy to `push` results as `in-parallel` tests running, but how aggregate coverage files from subset of tests is TBD.
* Tried generating a file during the testing, but was not able to use the `files` modifier to find it?
* The `files` modifier only grabs the 1st entry when the Containers is set to **1**. 
* Articles:

  * [Parallel test builds](http://technology.indiegogo.com/2015/08/how-we-get-coverage-on-parallelized-test-builds/)
  * [simplecov-parallel](https://github.com/increments/simplecov-parallel)
