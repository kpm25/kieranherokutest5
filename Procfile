web: java -Dserver.port=$PORT -jar build/libs/myGiflib-heroku-0.0.1-SNAPSHOT.jar
web: target/start -Dhttp.port=$PORT -DapplyEvolutions.default=true -Ddb.default.driver=org.postgresql.Driver -Ddb.default.url=$DATABASE_URL


