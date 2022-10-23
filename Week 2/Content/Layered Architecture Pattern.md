- Commonly used in practice
#### Properties
- Components are sorted into layers.
- Upper layers can access lower layers.
- Lower layers cannot access upper layers.

> [!NOTE] 
> In some variants of the layered architecture pattern, upper layers can only access one layer directly below it.

- With stricter access to lower layers, we achieve low coupling.
	- However, this can impair performance. Strict access can lead to a bigger chain of calling that could be avoided by access to lower levels.
- A typical application looks like this:
![[Drawing 2022-10-19 22.55.46.excalidraw]]
#### Advantages of Layered Architectures
- Easy to understand
- Clear and concise organization of dependencies between layers
- Components are through definition less coupled
- Abstraction levels are similar throughout layers and layers usually have one goal
- Modularity: layers can be switched out if a cleaner layer can be defined