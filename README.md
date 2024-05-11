# T3 drizzle-kit 0.21.0 db:push deprecation bug

## Steps to reproduce

```
git clone git@github.com:didoarellano/t3-drizzle-test.git
cd t3-drizzle-test
pnpm install
./start-database.sh
pnpm db:push
```

## Error message

```
Err: This command is deprecated, please use updated 'push' command (see https://orm.drizzle.team/kit-docs/upgrade-21#how-to-migrate-to-0210)
```
