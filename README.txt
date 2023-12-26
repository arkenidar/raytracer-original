===== TypeScript Sample: Raytracer =====

https://github.com/microsoft/TypeScriptSamples

=== Overview ===

This sample shows a raytracer implementation in TypeScript.

- Original, (archived) from Microsoft:
https://github.com/microsoft/TypeScriptSamples/tree/master/raytracer

- Another, derived from this Original:
* https://github.com/arkenidar/raycache/commits/master/
* https://arkenidar.github.io/raycache/raytracer/raytracer.html

=== Running ===

# for "tsc" ("which tsc" test) (also without "sudo")
sudo npm install --global typescript

# produces raytracer.js
tsc raytracer.ts

# uses raytracer.js # "xdg-open" or "start"
xdg-open raytracer.html
