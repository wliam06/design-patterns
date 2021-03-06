# Factory Pattern
Factory pattern is uses to encapsulates the implementation details of creating objects without knowing how the objects are actually being created.

<p align="center">
  <img src="https://user-images.githubusercontent.com/25744906/75609879-e1a4df00-5b3e-11ea-8b25-4a1197973e0e.png">
</p>

### What is the different between `Factory` and `Abstract Pattern` :
- `Factory Pattern` is a single method and `Abstract Pattern` is an object.
- `Factory Pattern` can be uses inheritences and relies on a subclass.
- `Abstract Pattern` is an object that has multiple factory methods. It means a class delegates the responsibility of object instantiation to another object via `composition`.

### When we should use it:
- Flexibility, it helps to centerized for constructing the object.
