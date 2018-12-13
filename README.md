# sofia model to csharp
This repo constains a generator, which lets you generate the model code in csharp for [PROtEUS](https://github.com/IoTUDresden/proteus).
All attributes are implemented as properties. Methods are not implemented.

You can use the following tools:
- [genmymodel](https://www.genmymodel.com/) (maybe the easiest)
- [Acceleo](https://www.eclipse.org/acceleo/)

# known issues
The sofia model contains some classes which inherit from more than one base classe. This is not allowed in csharp.
You have to edit these files after creation by hand.
The base classes are:
- Identifiable 
- Nameable