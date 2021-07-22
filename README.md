# Dockerized frontend application

## Intergrations done
1. codemirror6: https://github.com/codemirror/CodeMirror
2. python language server (pyls - palantir): https://github.com/palantir/python-language-server
3. jsonrpc to server pyls over websocket for interactive codemirror linting: https://github.com/palantir/python-jsonrpc-server
4. updated state management so that both ls and editorView state


## To setup
```
user@computer:~/$ git clone <GITHUB_URL>  
user@computer:~/codemirror-react-test$ docker-compose up -d --build
```

## Demo output
![alt text](https://github.com/guanyou-git/codemirror-react-test/blob/master/readme_image/intellisense.png)