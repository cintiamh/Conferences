# A Full Stack Websocket Deep Dive

# Profiling and Optimizing WebGL

GPU Zen: Volume 01 Advanced Rendering Techniques.

WebGL vs native applications

GLSL 1

Profile => Optimize until fast enough.

* Pick the chunk of code the is slower first and optimize that part.

Independents:
- GPU
- CPU

V-sync interval (vertical sync)

Profiling the in Chrome browser.

Measuring framerate

https://www.chromium.org/developers/how-tos/trace-event-profiling-tool

Categories:

blink
blink.console
v8
ipc
gpu
devtools.timeline

```
console.time('stuff');
doStuff();
console.timeEnd('end of stuff');
window.requestAnimationFrame(...)
```

* https://www.html5rocks.com/en/tutorials/canvas/inspection/

www.axum.graphics
