# A list of gems that have memory leaks

Links to issues, pull requests or articles demonstrating memory leaks:
- [therubyracer < 0.12.2](https://github.com/cowboyd/therubyracer/pull/336)
- [sidekiq < 3.5.1](https://github.com/mperham/sidekiq/pull/2598)
- [celluloid > 0.16.0, < 0.17.2](https://github.com/celluloid/celluloid/pull/678)
- [zipruby <= 0.3.6](https://packetstormsecurity.com/files/111242/libzip-0.10-Heap-Overflow-Information-Leak.html)
- [redcarpet < 3.3.3](https://github.com/vmg/redcarpet/pull/516)
- [grape < 0.2.5](https://github.com/ruby-grape/grape/pull/291#issuecomment-11725614)
- [oj < 2.12.4](https://github.com/ohler55/oj/issues/229)
- [newrelic_rpm < 3.9.8](https://discuss.newrelic.com/t/client-using-large-amount-of-memory/9307)

Your Ruby app leaks memory if you see gems above in your _Gemfile.lock_. The list above may save you a week or more of your personal life.  

# Contributing
Feel free to submit a PR if you find any memory leaks in gems.  
The format is the following:
- `[leaky gem name and versions affected](link to confirm)`

Thanks!
