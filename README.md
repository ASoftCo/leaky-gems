# A list of gems that have memory leaks:
- [therubyracer < 0.12.2](https://github.com/cowboyd/therubyracer/pull/336)
- [sidekiq < 3.5.1](https://github.com/mperham/sidekiq/pull/2598)
- [celluloid > 0.16.0, < 0.17.2](https://github.com/celluloid/celluloid/pull/678)
- [zipruby <= 0.3.6](https://packetstormsecurity.com/files/111242/libzip-0.10-Heap-Overflow-Information-Leak.html)
- [redcarpet < 3.3.3](https://github.com/vmg/redcarpet/pull/516)

Your Ruby app leaks memory if you see gems above in your _Gemfile.lock_.  

# Contributing
Feel free to submit a PR if you find any memory leaks in gems.  
The format is the following:
- [leaky gem name and versions affected](link to confirm)

Thanks!
