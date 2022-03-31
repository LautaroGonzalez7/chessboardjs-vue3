# Chessboardjs-Vue3


Fork from [chessboardjs-vue](https://github.com/technoo0/chessboardjs-vue) that makes the module work with Vue3

Please see chessboardjs.com for documentation and examples.

## Installation 


```sh
    # NPM
    npm install chessboardjs-vue3
    
```

And add the next code in your config or vite config for avoid errors with global variable.
```
define: {
    global: {},
  },
```

## Example Code

```html
    <div id="board1" style="width: 400px"></div>
```
```js
    //Vue
    import ChessBoard from "chessboardjs-vue3";
    
    export default {
        mounted(){
            ChessBoard('board1', {
                config: {
                    position: 'start',
                    imagesPath: "/wikipedia"
                }
            });
        }
  
}

```

## Images for chess pieces
You need download images to your project and set the images folder path in config.<br>
Default path is ```/wikipedia``` <br>
You can download some theme pieces images from here:
```
https://github.com/oakmac/chessboardjs/tree/master/website/img/chesspieces
```

## Do you want to change the board style?
You need copy this file:
```
node_modules/chessboardjs-vue3/chessboard-1.0.0.css
```
And paste in your project. You can edit the css and import in your components. This will overwrite the default css from node_modules. 

Please see chessboardjs.com for documentation and examples.

## What i did 

- Changes the way to import css .
- Fix error when import images from package, now the images are in consumer project.
- Add config for define path to images.

## Docs and Examples

- Docs - <http://chessboardjs.com/docs>
- Examples - <http://chessboardjs.com/examples>

## License

MIT License


