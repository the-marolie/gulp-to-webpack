Gulp to Webpack CLI
===================

Overview
--------

The Gulp to Webpack CLI is a command-line tool designed to streamline the process of migrating from Gulp to Webpack in your projects. If you've been using Gulp for task automation and want to transition to Webpack, this tool simplifies the conversion by generating Webpack configuration files based on your existing Gulpfile.

Features
--------

*   **Automated Migration:** Quickly generate Webpack configurations based on your existing Gulpfile.
*   **Task Mapping:** Map Gulp tasks to their equivalent Webpack configurations effortlessly.
*   **Customization:** Fine-tune the generated Webpack files to match your project's specific needs.
*   **Efficient Workflow:** Smoothly transition from Gulp to Webpack without starting from scratch.

Getting Started
---------------

### Installation


```
npm install -g gulp-to-webpack
```

### Usage


```
g2w --input <path-to-gulpfile> --output <output-directory>
```

*   `<path-to-gulpfile>`: Path to your existing Gulpfile.
*   `<output-directory>`: Directory where the generated Webpack files will be saved.

Example
-------


```
g2w --input path/to/your/gulpfile.js --output path/to/output
```

Contributing
------------

We welcome contributions! If you encounter any issues, have suggestions, or want to contribute to the development, feel free to open an issue or submit a pull request.

License
-------

This project is licensed under the [MIT License](LICENSE).

* * *
