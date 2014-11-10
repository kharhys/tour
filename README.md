# &lt;https://github.com/kharhys/tour&gt;

> My awesome Custom Element

## Demo

[Check it live!](http://kharhys.github.io/https://github.com/kharhys/tour)

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install https://github.com/kharhys/tour --save
```

Or [download as ZIP](https://github.com/kharhys/https://github.com/kharhys/tour/archive/master.zip).

## Usage

1. Import Web Components' polyfill:

    ```html
    <script src="bower_components/platform/platform.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="bower_components/https://github.com/kharhys/tour/dist/tour-app.html">
    ```

3. Start using it!

    ```html
    <tour-app></tour-app>
    ```

## Options

Attribute     | Options     | Default      | Description
---           | ---         | ---          | ---
`foo`         | *string*    | `bar`        | Lorem ipsum dolor.

## Methods

Method        | Parameters   | Returns     | Description
---           | ---          | ---         | ---
`unicorn()`   | None.        | Nothing.    | Magic stuff appears.

## Events

Event         | Description
---           | ---
`onsomething` | Triggers when something happens.

## Development

In order to run it locally you'll need to fetch some dependencies and a basic server setup.

* Install [Bower](http://bower.io/) & [Gulp](http://gulpjs.com/):

    ```sh
    $ [sudo] npm install -g bower gulp
    ```

* Install local dependencies:

    ```sh
    $ bower install && npm install
    ```

* To test your project, start the development server and open `http://localhost:8000`.

    ```sh
    $ gulp server
    ```

* To build the distribution files before releasing a new version.

    ```sh
    $ gulp build
    ```

* To provide a live demo, send everything to `gh-pages` branch.

    ```sh
    $ gulp deploy
    ```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

For detailed changelog, check [Releases](https://github.com/kharhys/https://github.com/kharhys/tour/releases).

## License

[MIT License](http://opensource.org/licenses/MIT)
