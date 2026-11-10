# PgBolt

SQLBolt-style interactive tutorial for the PostgreSQL features that generic SQL tutorials skip. 21 lessons, zero setup: a real PostgreSQL engine ([PGlite](https://pglite.dev), Postgres compiled to WASM) runs in your browser.

Live: https://afloresescarcega.github.io/pgbolt/

Lessons cover ILIKE, regex operators, `::` casts, `IS DISTINCT FROM`, `DISTINCT ON`, aggregate `FILTER`, `string_agg`, arrays (`ANY`, `@>`, `unnest`), JSONB (`->>`, `@>`, `?`), `generate_series`, window functions, CTEs and `WITH RECURSIVE`, `LATERAL`, `RETURNING`, `ON CONFLICT`, `UPDATE … FROM`, and expression indexes.

The checker compares your result rows with the reference solution's, so any correct query passes. The data resets before every run.

## Run locally

```
python3 -m http.server
```
