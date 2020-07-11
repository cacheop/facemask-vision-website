## Installing Project
* Start by installing dependencies to start this project.
```
npm install
```

* After finished with installation, run locally
```
node app.local.js
```

* To upload to AWS Lambda:
```
# Put your AWS credential on `~/.aws/credentials`
> more ~/.aws/credentials
[default]
aws_access_key_id = xxxxxxxxxxxx
aws_secret_access_key = yyyyyyyyyyyy

# Then, run below commands sequentially:
npm start
> generate_lambda

npm start
> deploy
```

## Authors

* [Anton Rifco](https://github.com/antonrifco)

## License

MIT -- see [LICENSE](LICENSE)

## Thanks To
Creator of New Age Template: https://startbootstrap.com/themes/new-age/
