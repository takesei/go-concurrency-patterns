# Golang Concurrency Patterns
Common and useful golang concurrency patterns I implemented from Rob Pike's famous 2012 Google I/O talk.

### Common Patterns
- Generator: function that runs goroutine and returns channel
- Multiplexing (fan-in): function that takes multiple channels and pipes to one channel, so that the returned channel receives both outputs
- Daisychaining: functions whose I/O are daisy-chained with channels together

### References
- [Google I/O Talk](https://www.youtube.com/watch?v=f6kdp27TYZs)
- [Slide](https://go.dev/talks/2012/concurrency.slide)
