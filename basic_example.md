# Canvas API

> Canvas API는 그래픽을 그리기 위한 수단으로 제공한다.
>
> > 주로 2D그래픽에 중점을 두고 있다.

**기본예시**

-   HTML
    ```
    <canvas id="canvas"></canvas>
    ```
-   JavaScript

    ```
    const canvas = document.querySelector('#canvas');
    const ctx = canvas.getContext('2d');

    ctx.fillstyle = 'black';
    ctx.fillRect(10, 10, 150, 100);
    ```
