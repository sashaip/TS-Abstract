
# Project Title

Ts Abstract

Абстрактные класса - представляют классы, опредеделенность ключевым словом абстракт.Но мы не можем создать напрямую объект абстрактного класса.

Например, если мы создадим abstract class Control и попытаемся создать его экземпляр, то у нас выведиться ошибка.Если у нас есть abstract метод, то мы должны вызвать его в дочернем классе .

Примеры:
abstract class Geometry{
    width:string;
    color:string;
    
    abstract draw(): void
}

class Line extends Geometry{
    x1:number;
    draw(){}
}

bstract class "Название"{
    model:string;

    abstract go(): void;
    abstract stop(): void;
    abstract start(): void;
}

class Af extends "Название"{
    go(){}
    stop(){}
    start(){}
}

let gfg: Af = new Af()



