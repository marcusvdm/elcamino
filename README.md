# holy-grail.css web template

This is the holy-grail.css web template; the wrapper for the
[holy-grail.css](https://github.com/herzinger/holy-grail.css) framework.

This template is a barebones and unopinionated directory structure which simply
allows you to include the holy-grail.css core library in your builds as an updatable
Git submodule.

To quickly install holy-grail.css, run the following commands:

```bash
	$ git clone --recursive git@github.com:herzinger/holy-grail.css-web-template.git your-project
	$ cd your-project
	$ ./go
```

What we are doing here is cloning an instance of the holy-grail.css-web-template and
its submodules (that’s what the `--recursive` does) into a directory which you
specify. Next we `cd` into that directory and run [our `go` script](https://github.com/herzinger/holy-grail.css-web-template/blob/master/go).
This script (courtesy of [Nick Payne](http://twitter.com/makeusabrew)) simply
removes the web template’s Git instance and replaces it with a fresh one for
your project, whilst also maintaining your holy-grail.css submodule.

For a more detailed overview on what holy-grail.css is, and how to install and use
it, please refer to the documentation in the README in
[the main holy-grail.css repository](https://github.com/herzinger/holy-grail.css).


## About this and inuit.css

Holy-grail.css started as a fork from [inuit.css](http://inuitcss.com/). While it's
still mainly identical right now, I decided to start a new project, with a new name,
because I want to rewrite it completely. The differences at the end of this process should be
a lot, including some different approaches and filosofies.

Ditto that, this web template is completely the same and I don't think it's going to chance anytime soon.
The only difference is, this one points to my own version of the framework, and not the original one.
