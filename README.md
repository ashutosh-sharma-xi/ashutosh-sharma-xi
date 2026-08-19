## hey, I'm Ashutosh

Data engineer in Mumbai. I build things that move data around and then
spend most of my time on the part where it breaks.

### the day job

Marketing attribution at Fospha. Ad platform data in, models out.

Most of it is dbt and AWS. We've got a big dbt project — big enough that
it stopped being one project and had to become four, which I spent a
chunk of last year doing. Turns out splitting a monorepo is 20% modelling
and 80% getting people to agree on who owns what. Nobody warns you about
that part.

The other half is ingestion. Fivetran where it works, custom Lambda
connectors where it doesn't. I've written enough of these to have gotten
opinionated about keeping vendor-specific weirdness at the edges, because
every ad platform API is strange in its own particular way and you really
don't want that leaking into your core logic.

Things I've ended up caring about:

- monitoring and freshness checks — I'd rather my alerting tell me a
  table is stale than have a client tell me the numbers look wrong
- fast CI, because slow CI quietly changes how people work
- the gap between "the pipeline ran" and "the pipeline was correct"

`Python` `SQL` `dbt` `AWS` `Databricks` `PySpark` `Fivetran` `Docker`

### the other thing

I'm building a D2C setup for FMCG staples — flour, oil, spices. The
premise is that the distributor → super-stockist → retailer chain adds a
lot of markup for people who are buying almost purely on price. Go
direct, let software handle the parts middlemen were being paid for —
demand signals, replenishment, routing orders to the right fulfilment
point — and some of that margin can go back to the customer.

That's the theory, anyway. Distribution networks do real work — credit,
breaking bulk, last mile — so it's a premise I'm testing rather than one
I've proven. In practice I've spent most of my time on unglamorous
things: catalog data, SEO, and learning how people actually search for
atta.

It's been a useful reality check on the day job. Having your own revenue
depend on a data pipeline changes how you feel about data quality.

### otherwise

Messing with local LLMs and voice interfaces lately — mostly to find out
how far you can get without an API bill. Bikes, when there's time. I
started a data science club at university that got to 400-odd people, and
I still do interviews and code reviews at work, which I like more than I
expected to.

### repos

Mostly older personal projects — a serverless ETL pipeline on AWS, a
collaborative filtering recommender, some clustering work on Netflix
data. Day job code isn't public.

ashutosh0626@gmail.com · [LinkedIn](https://linkedin.com/in/ashutoshsharma-xi)
