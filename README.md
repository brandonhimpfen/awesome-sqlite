# Awesome SQLite [![Awesome Lists](https://srv-cdn.himpfen.io/badges/awesome-lists/awesomelists-flat.svg)](https://github.com/brandonhimpfen/awesome-lists)

[![Support Open Work](https://img.shields.io/badge/Support-Open%20Work-0A0A0A?style=flat&logo=github)](https://github.com/brandonhimpfen/support) 
[![GitHub Sponsor](https://srv-cdn.himpfen.io/badges/github/github-flat.svg)](https://github.com/sponsors/brandonhimpfen) 
[![Buy Me a Coffee](https://srv-cdn.himpfen.io/badges/buymeacoffee/buymeacoffee-flat.svg)](https://buymeacoffee.com/brandonhimpfen) 
[![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://ko-fi.com/brandonhimpfen) 
[![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://www.paypal.com/donate/?hosted_button_id=3LLKRXJU44EJJ) <br />
[![X](https://srv-cdn.himpfen.io/badges/twitter/twitter-flat.svg)](https://x.com/ListsAwesome) 
[![Facebook](https://srv-cdn.himpfen.io/badges/facebook-pages/facebook-pages-flat.svg)](https://www.facebook.com/awesomelists)

> A curated list of tools, extensions, utilities, clients, libraries, and resources for SQLite — the world’s most widely deployed embedded database.

## Contents

- [Core Tools](#core-tools)
- [Extensions](#extensions)
- [GUI Clients](#gui-clients)
- [Command-Line Tools](#command-line-tools)
- [Libraries](#libraries)
- [Full-Text Search & Search Extensions](#full-text-search--search-extensions)
- [ORMs & Query Builders](#orms--query-builders)
- [Backup, Sync & Replication](#backup-sync--replication)
- [Learning Resources](#learning-resources)
- [Related Awesome Lists](#related-awesome-lists)

## Core Tools

- [SQLite](https://sqlite.org/) – Official SQLite database engine and documentation.
- [DB Browser for SQLite](https://github.com/sqlitebrowser/sqlitebrowser) – Open-source visual editor for SQLite databases.
- [SQLiteStudio](https://github.com/pawelsalawa/sqlitestudio) – Advanced SQLite database manager with plugin support.

## Extensions

- [SQLite Extensions (Official)](https://sqlite.org/loadext.html) – Core extension mechanisms and dynamic loading.
- [SQLCipher](https://github.com/sqlcipher/sqlcipher) – High-security encrypted SQLite database.
- [SQLite JSON1](https://sqlite.org/json1.html) – JSON storage, querying, and manipulation.
- [SQLite FTS5](https://sqlite.org/fts5.html) – Full-text search extension.
- [sqlite-vss](https://github.com/asg017/sqlite-vss) – Vector search extension for embeddings and similarity lookup.
- [sqlite-wasm](https://github.com/sqlite/sqlite-wasm) – SQLite compiled to WebAssembly for browsers.
- [libSQL Extensions](https://github.com/tursodatabase/lsm-extension) – LSM storage engine variants.

## GUI Clients

- [Beekeeper Studio](https://github.com/beekeeper-studio/beekeeper-studio) – Modern SQL editor supporting SQLite.
- [DBeaver](https://github.com/dbeaver/dbeaver) – Universal database client with SQLite support.
- [TablePlus](https://tableplus.com/) – Commercial, polished DB client with SQLite compatibility.
- [DataGrip](https://www.jetbrains.com/datagrip/) – JetBrains IDE for SQL and databases, supports SQLite.

## Command-Line Tools

- [LiteCLI](https://github.com/dbcli/litecli) – Enhanced CLI for SQLite with autocompletion and syntax highlighting.
- [sqlean CLI Tools](https://github.com/nalgeon/sqlean) – Collection of useful SQLite extensions packaged as commands.
- [sqlite-utils](https://github.com/simonw/sqlite-utils) – Python-based utilities for manipulating SQLite databases.

## Libraries

### Python
- [sqlite3 (Standard Library)](https://docs.python.org/3/library/sqlite3.html) – Built-in SQLite interface.
- [apsw](https://github.com/rogerbinns/apsw) – Thin wrapper directly exposing SQLite’s C API.
- [Dataset](https://github.com/pudo/dataset) – Simplified database access layer.

### JavaScript / Node.js
- [better-sqlite3](https://github.com/WiseLibs/better-sqlite3) – Fast, synchronous SQLite for Node.
- [sqlite3](https://github.com/TryGhost/node-sqlite3) – Asynchronous SQLite bindings.
- [wa-sqlite](https://github.com/rhashimoto/wa-sqlite) – SQLite in WebAssembly.

### Go
- [mattn/go-sqlite3](https://github.com/mattn/go-sqlite3) – Primary Go driver for SQLite.
- [modernc.org/sqlite](https://gitlab.com/cznic/sqlite) – Pure Go SQLite implementation.

### Rust
- [rusqlite](https://github.com/rusqlite/rusqlite) – Idiomatic SQLite bindings for Rust.
- [libsql-client](https://github.com/tursodatabase/libsql-client-rs) – Client for libSQL/Turso.

### Java / Kotlin
- [SQLite JDBC](https://github.com/xerial/sqlite-jdbc) – SQLite JDBC driver.

## Full-Text Search & Search Extensions

- [FTS4 / FTS5 (Official)](https://sqlite.org/fts5.html) – True full-text search extensions.
- [sqlite-vss](https://github.com/asg017/sqlite-vss) – Vector search extension.
- [bm25 ranking for FTS](https://sqlite.org/fts5.html#the_bm25_algorithm) – Built-in scoring support for ranked search.

## ORMs & Query Builders

### Python
- [SQLModel](https://github.com/tiangolo/sqlmodel) – SQLAlchemy + Pydantic hybrid with SQLite-first support.
- [Peewee](http://docs.peewee-orm.com/) – Lightweight, SQLite-friendly ORM.
- [SQLAlchemy](https://www.sqlalchemy.org/) – Extensive ORM used across many SQLite projects.

### JavaScript / TypeScript
- [Prisma](https://github.com/prisma/prisma) – Modern ORM with SQLite support.
- [Drizzle ORM](https://github.com/drizzle-team/drizzle-orm) – TypeScript ORM optimized for SQLite.
- [Kysely](https://github.com/koskimas/kysely) – Type-safe SQL query builder.

### Go
- [GORM](https://github.com/go-gorm/gorm) – Popular Go ORM with SQLite support.
- [sqlc](https://github.com/sqlc-dev/sqlc) – Type-safe code generation from raw SQL.

### Rust
- [Diesel](https://github.com/diesel-rs/diesel) – Type-safe ORM supporting SQLite.
- [SeaORM](https://github.com/SeaQL/sea-orm) – Async ORM with SQLite compatibility.

## Backup, Sync & Replication

- [Litestream](https://github.com/benbjohnson/litestream) – Streaming, continuous, real-time replication for SQLite.
- [LiteFS](https://github.com/superfly/litefs) – Distributed SQLite file system used in Fly.io apps.
- [rqlite](https://github.com/rqlite/rqlite) – Distributed SQLite over Raft for clustering.
- [libSQL + Turso](https://github.com/tursodatabase/libsql) – Fork of SQLite with replication and HTTP-based access.

## Learning Resources

- [SQLite Documentation](https://sqlite.org/docs.html) – Official, thorough documentation.
- [The SQLite Handbook](https://sqlite.org/whentouse.html) – Usage recommendations and guidance.
- [SQLite Query Planner](https://sqlite.org/queryplanner.html) – Deep dive into query planning.
- [SQLite Internals](https://fly.io/blog/sqlite-internals/) – Guide to understanding SQLite’s architecture.
- [Designing with SQLite](https://www.sqlite.org/different.html) – Best practices for when and how to use SQLite.

## Related Awesome Lists

- [Awesome Databases](https://github.com/brandonhimpfen/awesome-db)
- [Awesome SQL](https://github.com/brandonhimpfen/awesome-sql)
- [Awesome SQLite Extensions](https://github.com/brandonhimpfen/awesome-sqlite-extensions)
- [Awesome Rust](https://github.com/brandonhimpfen/awesome-rust)
- [Awesome Go](https://github.com/brandonhimpfen/awesome-go)

## Contribute

Contributions are welcome. Please ensure your submission fully follows the requirements outlined in [`CONTRIBUTING.md`](CONTRIBUTING.md), including formatting, scope alignment, and category placement.

Pull requests that do not adhere to the contribution guidelines may be closed.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)
