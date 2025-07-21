# PyVenice

## Development

```sh
docker-compose up # or postman-compose up
```

If something is not updated,

```sh
rm -rf _site .jekyll-cache .jekyll-metadata
touch .jekyll-metadata; chmod 777 .jekyll-metadata
```

Not commit (there are also in the .gitignore file)

* _site
* .jekyll-cache
* .jekyll-metadata
* Gemfile.lock

## License

This code is released under the MIT license. See [LICENSE](LICENSE) for details.
