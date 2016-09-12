# A list of gems that have memory leaks

Links to issues, pull requests or articles demonstrating known memory leaks (gems are listed alphabetically):
- [celluloid > 0.16.0, < 0.17.2](https://github.com/celluloid/celluloid/pull/678)
- [csspool < 4.0.3](https://github.com/sparklemotion/csspool/issues/59)
- [grape < 0.2.5](https://github.com/ruby-grape/grape/pull/291#issuecomment-11725614)
- [oj < 2.12.4](https://github.com/ohler55/oj/issues/229)
- [redcarpet < 3.3.3](https://github.com/vmg/redcarpet/pull/516)
- [redis = 3.3.0](https://github.com/redis/redis-rb/issues/612)
- [sidekiq < 3.5.1](https://github.com/mperham/sidekiq/pull/2598)
- [sidekiq-statistic](https://github.com/davydovanton/sidekiq-statistic/issues/73)
- [therubyracer < 0.12.2](https://github.com/cowboyd/therubyracer/pull/336)
- [zipruby <= 0.3.6](https://packetstormsecurity.com/files/111242/libzip-0.10-Heap-Overflow-Information-Leak.html)

Your Ruby app leaks memory if you see gems above in your _Gemfile.lock_. The list above may save you a week or more of your personal life.

# A list of gems that have memory issues (but not actual leaks)

It appears some contributors submit gems with known memory issues, but not actual leaks. While those issues don't qualify as leaks they may still be important. I prefer listing them here to help other developers rather than just hiding them.

Links to known memory issues (gems are listed alphabetically):
- [axlsx](https://github.com/randym/axlsx/issues/276)
- [delayed_job >= 4.06](https://github.com/collectiveidea/delayed_job/issues/776)
- [libxml-ruby > 2.8.0 with Nokogiri RC3](http://webuild.envato.com/blog/tracking-down-ruby-heap-corruption/)
- [newrelic_rpm >= 3.9.4, <= 3.9.7](https://discuss.newrelic.com/t/client-using-large-amount-of-memory/9307)
- [sequel >= 2.12.0](https://github.com/jeremyevans/sequel/issues/1139)


# Contributing
Feel free to submit a PR if you find any memory leaks in gems.
The format is the following:
- `[leaky gem name and versions affected](link to confirm)`

Thanks!

# Contributors
- [Graham Conzett @conzett](https://github.com/conzett)
- [Jacob Oakes @oakesja](https://github.com/oakesja)
- [Juan Ignacio Sánchez Lara @juanignaciosl](https://github.com/juanignaciosl)
- [Ilya Vassilevsky @vassilevsky](https://github.com/vassilevsky)
- [Sebastiaan Pouyet @srpouyet](https://github.com/srpouyet)
- [Michal Kulesza @mic-kul](https://github.com/mic-kul)
- [Benoit Tigeot @benoittgt](https://github.com/benoittgt)
- [Jolyon Pawlyn @jpawlyn](https://github.com/jpawlyn)
- [Shai Coleman @shaicoleman](https://github.com/shaicoleman)
