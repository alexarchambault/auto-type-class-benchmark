Run the benchmark with
```
$ util/shapeless-publish-local
$ util/run-benchmark
$ util/parse-results results > results.csv
```

Then plot the distributions of the compilation times in `results.csv` with
the tool of your choice. See `util/commits` for descriptions of the
commits of shapeless / upickle used.

I'd be really interested in runs of the benchmarks on configs other than mine. If you ran them, feel free to submit their result (CSV file) as a PR to this repository.
