# What's next

* Install a syntax highlighting package for your text editor. We have packages for SublimeText and VSCode. See  [cooklang.org](https://cooklang.org/docs/syntax-highlighting/) for full instructions.
* Add your own recipes. Dive into the Cook ecoysystem and discover how easy it is to write in CookLang. It's the best way to learn the [CookLang syntax](https://cooklang.org/docs/spec/).
* Check out our [tips and tricks](https://cooklang.org/docs/best-practices/) page.

### Read the recipe

```sh
cook recipe read "Root Vegetable Tray Bake.cook"
```

### Create shopping list

```sh
cook shopping-list \
  "Neapolitan Pizza.cook" \
  "Root Vegetable Tray Bake.cook" \
  "Snack Basket I.cook"
```

### Run a server

In directory where you have your recipes run:

```sh
cook server
```

Then open [http://127.0.0.1:9080](http://127.0.0.1:9080) in your browser.

### Automate something

Explore [the docs](https://cooklang.org/cli/help/), which describe how to use CookCLI's automation tools.

### Customize your instance

Add aisle configuration information to the `config/aisle.conf` file to tailor your shopping list experience.

## TODO：设计
- [ ] 支持中文（目前的cooklang只支持Ingredients使用中文，而Steps中使用中文会把中文ingredient的数量吞掉）
- [ ] 目前的菜谱只是静态的导出shopping list，以及静态的step。可以考虑针对于做菜弄一个流水线，而每个step都是流水线中的一个步骤。
- [ ] 流水线的步骤可以并行


