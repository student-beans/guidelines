# RSpec

In general, we try to adhere to the [BetterSpecs
guidelines](http://betterspecs.org/).

## Key points

- Make liberal use of [`describe`](http://betterspecs.org/#describe) and
  [`context`](http://betterspecs.org/#contexts) blocks
- Only use the [`expect`](http://betterspecs.org/#expect) and
  `is_expected.to` syntax
- Create only the [data you need](http://betterspecs.org/#data)
- In unit tests, avoid touching the database, objects should be built in memory
- Never mock the object under test, only objects which it talks to
- Use shared examples carefully and only where it makes sense. [Duplication is
  far cheaper than the wrong
  abstraction](https://www.sandimetz.com/blog/2016/1/20/the-wrong-abstraction)
