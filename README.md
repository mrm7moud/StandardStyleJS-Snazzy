# How to install JavaScript Semi-Standard Style and snazzy package

## Why Semi-Standard?

**This module saves you (and others!) time in three ways:**

* **No configuration.** The easiest way to enforce consistent style in your project. Just drop it in.
* **Automatically format code.** Just run ```standard --fix``` and say goodbye to messy or inconsistent code.
* **Catch style issues & programmer errors early.** Save precious code review time by eliminating back-and-forth between reviewer & contributor.


## Why snazzy?
**Format JavaScript Standard Style as Stylish output**

# install

1. **Open your Terminal**
2. **write this line ```sudo su``` to  to enable the super user (root)**
3. **write your user password**

![before](/img/root.png)

4. **write this line ```npm install semistandard```**
5. **if you want to run this package open your project and write this line ```semistandard```**

* **this is the error in your code**<br>

![before](/img/before.png)

6. **If you want prettier output, just install this package snazzy write this line:**<br>
```npm install -g snazzy```



* **to run two package write this line:**
```semistandard --verbose | snazzy```

* **with snazzy the error look like this:**<br>

![after](/img/after.png)

7. **if you have an error when you run the atom, you should Install the dependencies inside Atom by searching for linter and linter-ui-default, or you can install them with the terminal installer:**<br>
```apm install linter``` <br>
```apm install linter-ui-default```<br>
```npm install -g semistandard-format```



## Usage

**The easiest way to use JavaScript Semi-Standard Style to check your code is to install it globally as a Node command line program. To do so, simply run the following command in your terminal (flag -g installs semistandard globally on your system, omit it if you want to install in the current working directory):**<br>

``` npm install semistandard -g ```


### Editor plugins

- **Sublime users**: Try [SublimeLinter-contrib-semistandard](https://github.com/Flet/SublimeLinter-contrib-semistandard) for linting in your editor!
- **Atom users** - Install [linter-js-standard](https://atom.io/packages/linter-js-standard)
- **VSCode users** - Install [vscode-standardjs](https://marketplace.visualstudio.com/items?itemName=chenxsan.vscode-standardjs)


##### for more information:<br>
[`snazzy`](https://github.com/standard/snazzy)<br>
[`semistandard`](https://github.com/Flet/semistandard)<br>
[`feross/standard`](https://github.com/standard/standard)<br>
[`semistandard-format`](https://github.com/ricardofbarros/semistandard-format)
