# How to install JavaScript Semi-Standard Style package

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
[`feross/standard`](https://github.com/standard/standard)
