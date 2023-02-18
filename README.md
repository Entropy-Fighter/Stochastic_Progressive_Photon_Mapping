# Stochastic Progressive Photon Mapping

## Introduction

This is the final project for the Fall22 Computer Graphics course, based on Toshiya Hachisuka and Henrik Wann Jensen's paper "Stochastic Progressive Photon Mapping" on SIGGRAPH Asia (2009). You can see more details about SPPM in the report and presentation slides. 

I do the project with my teammates, thy and swl.

## How to use

Note: Remember to replace the paths with yours in the source code!

You can modify parameters in main.cpp main() function.

1. The first parameter of scene->render() is the round number to execute, and the second is the number of photons. The default is (600,200000), more rounds would lead to better performance.
2. The size of the output picture is 800\*600 by default.
3. Coding is done on Windows10, using compiler VS2022 amd64.
4. We use eigen3, stb_image, json. All added in libs directory.
