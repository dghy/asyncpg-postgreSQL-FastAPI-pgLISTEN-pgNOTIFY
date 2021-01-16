# asyncpg-postgreSQL-FastAPI-pgLISTEN-pgNOTIFY


# TODO:
1. Use PostgreSQL, alembic, SQLAlchemy, GINO to setup DB and connect app with it. Use async connector only!
2. Create socket handlers in the app so later it's possible to use Postgres pgLISTEN-pgNOTIFY events.
3. Create alembic migration with required Postgres plugin (hstore: https://www.postgresql.org/docs/13/hstore.html)installation and proper SQL triggers.
4. Handle LRU cache within BE app. Update cache when data in DB is being updated - socket pgLISTEN / pgNOTIFY.
5. Create some CRUD endpoints and perform performacne testing (by hand or with tool - ex. Locust).