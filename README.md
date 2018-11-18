# Onliner analyzer

**It is a little Sinatra app, which performs sentiment analyzing of comments on onliner.by technical articles**

It uses Redis database and AZURE text analysis API, which needs access key, which should be placed to the .key file.

---------------------

**Setup**

```bash
git clone https://github.com/ARtoriouSs/onliner-analyzer.git
cd onliner-analyzer
bundle install
```

Add text analisis API to your AZURE account and put key to the .key file.

```bash
rackup
```

Visit localhost:9292 or deploy it somewhere

---------------------

[**Usage**](https://youtu.be/BU_ZneEe4Ik "Video demonstration")
