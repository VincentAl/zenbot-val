## Screen
screen -ls
screen -r
screen -S new

## Zenbot

### Backfill
docker-compose exec server zenbot backfill binance.BTC-EUR --days  1500
docker-compose exec server zenbot backfill binance.BTC-EUR --start 1546297200000




docker-compose exec server zenbot sim binance.BTC-EUR --days  1500

docker-compose exec server zenbot sim binance.BTC-EUR --strategy trendline --start 20230101 --end 20230501
