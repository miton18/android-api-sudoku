# android-api-sudoku

This container is just here to serve you a grid ( a string ) of Sudoku
I use it to get a grid in my school android app.

## Install

    git clone https://github.com/miton18/android-api-sudoku.git
    cd android-api-sudoku
    docker build -t api-sudoku .
    docker run -p 8080:80 --name api-sudoku-instance api-sudoku
    
    
## Usage

    curl http://127.0.0.1
    
## response

It will send you a JSON with an error `err` your ip `from` and the grid `grid`


Licence MIT
