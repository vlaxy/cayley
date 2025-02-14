<div align="center">
  <a href="https://github.com/cayleygraph/cayley">
    <img width="200" src="https://github.com/cayleygraph/branding/raw/master/cayley_bottom.png" alt="Cayley">
  </a>
</div>

[![Build Status](https://api.travis-ci.com/cayleygraph/cayley.svg?branch=master)](https://app.travis-ci.com/github/cayleygraph/cayley)
[![Container Repository](https://img.shields.io/docker/cloud/build/cayleygraph/cayley "Container Repository")](https://hub.docker.com/r/cayleygraph/cayley)

Cayley is an open-source database for [Linked Data](https://www.w3.org/standards/semanticweb/data). It is inspired by the graph database behind Google's [Knowledge Graph](https://en.wikipedia.org/wiki/Knowledge_Graph) (formerly [Freebase](https://en.wikipedia.org/wiki/Freebase_(database))).

[![Get it from the Snap Store](https://snapcraft.io/static/images/badges/en/snap-store-white.svg)](https://snapcraft.io/cayley)

## [Documentation](https://cayley.gitbook.io/cayley/)

## Features

- Built-in query editor, visualizer and REPL
- Multiple query languages:
  - [Gizmo](./docs/gizmoapi.md): query language inspired by [Gremlin](https://tinkerpop.apache.org/gremlin.html)
  - [GraphQL](./docs/graphql.md)-inspired query language
  - [MQL](./docs/mql.md): simplified version for [Freebase](https://en.wikipedia.org/wiki/Freebase_(database)) fans
- Modular: easy to connect to your favorite programming languages and back-end stores
- Production ready: well tested and used by various companies for their production workloads
- Fast: optimized specifically for usage in applications

### Performance

Rough performance testing shows that, on 2014 consumer hardware and an average disk, 134m quads in LevelDB is no problem and a multi-hop intersection query -- films starring X and Y -- takes ~150ms.

## Community

- Website: [cayley.io](https://cayley.io)
- Slack: [cayleygraph.slack.com](https://cayleygraph.slack.com) -- Invite [here](https://cayley-slackin.herokuapp.com/)
- Discourse list: [discourse.cayley.io](https://discourse.cayley.io) (Also acts as mailing list, enable mailing list mode)
- Twitter: [@cayleygraph](https://twitter.com/cayleygraph)
- Involvement: [Contribute](./docs/contributing.md)
