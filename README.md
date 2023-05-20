# python_cpp
Exemple d'utilisation d'un composant en python
Utilise pybind11
apres git clone, faire:
```
cd python_cpp
git submodule init
git submodule update
```

Pour compiler

```
cd hello
make
```

Pour utiliser
```
python3
>>> import hello_component
>>> hello_component.greet()
'hello, world'
>>> hello_component.getVersion()
'1.0'
>>> 
```

Here the output correction :

![Capture d’écran 2023-05-20 à 10 53 11](https://github.com/rafikhdj/python_cpp_2023/assets/26821093/1b024d15-3d1a-4aab-aacb-94197c2d41c2)

