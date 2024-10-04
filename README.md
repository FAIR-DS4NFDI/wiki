# FAIR Dataspaces wiki

Repository for the documentation of the BMBF funded project FAIR Dataspaces.

A rendered version of the wiki can be found here: 

https://fair-ds4nfdi.github.io/wiki/

## Deploy Locally with Docker for Testing

* In the repository's root directory, run `docker run -v $PWD:/book -p 3000:3000 peaceiris/mdbook serve --hostname 0.0.0.0`
* Browse to http://localhost:3000
* You can edit the content while the container is running and see the results immediately.


## Contributing

The contribution to the wiki is done via pull requests. The book is rendered as markdown via the `src` directory.

[SUMMARY.md](./src/SUMMARY.md) contains the table of content for the book.

## License

This work is Licensed under the CC BY-ND 4.0 see [LICENSE](./LICENSE) for more information.
