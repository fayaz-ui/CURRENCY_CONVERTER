# CURRENCY_CONVERTER
Frankfurter
Build

Frankfurter is a free and open-source currency data API that tracks reference exchange rates published by the European Central Bank.

api.frankfurter.app hosts a public instance of the API.

Getting Started
Get the latest exchange rates.

https://api.frankfurter.app/latest
Get rates for a past date.

https://api.frankfurter.app/2000-01-03
Get rates for a period.

https://api.frankfurter.app/2010-01-01..2010-01-31
For more examples, read the docs.

Deployment
You can self-host Frankfurter with Docker.

docker run -d -p 8080:8080 \
  -e "DATABASE_URL=<postgres_url>" \
  --name frankfurter hakanensari/frankfurter
Miscellaneous
Frankfurter was known as Fixer between 2012 and 2018. After selling the original domain, I relaunched under this name.
