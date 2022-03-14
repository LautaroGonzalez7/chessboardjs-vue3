# Chessboardjs-Vue3


Fork from [chessboardjs-vue](https://github.com/technoo0/chessboardjs-vue) that makes the module work with Vue3

Please see chessboardjs.com for documentation and examples.

## Installation 


```sh
    # NPM
    npm install chessboardjs-vue3
    
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
            ChessBoard('board1',"start");
        }
  
}

```
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


