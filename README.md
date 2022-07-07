# Kong with Docker

Pastikan sudah install [docker](https://docs.docker.com/engine/install/) dan [docker-compose](https://docs.docker.com/compose/install/) di VM/PC

## Kong without Database

Untuk menggunakan kong yang tanpa database bisa masuk ke `cd dbless`

```
docker-compose up -d --build
```

## Kong with Postgresql

Untuk menggunakan kong dengan database postgresql bisa masuk ke `cd postgres`

```
docker-compose up -d --build
```

## Testing Kong

Silahkan download dan install aplikasi [Insomnia](https://insomnia.rest/download)

Silahkan import file `Insomnia_testing.yaml`
