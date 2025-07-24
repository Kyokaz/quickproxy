# QuickProxy
Automates proxy creation with decimate modifiers

<img width="404" height="370" alt="image" src="https://github.com/user-attachments/assets/210f2d67-bfe1-4561-8b35-3e355fc12a70" />

QuickProxy allows you to automatically create proxy version of meshes by duplicating them into another collection and applying decimate modifier while also removing any performance taxing modifier. Ideal for environment scene.

### Auto
Auto setting make sure to consider the poly count of the mesh and tries to decimate the object for the best possible performance while maintaining the necessary amount of detail.
### Manual
Manual allows you to set overall ratio of the decimate which will be applied to all/selected objetcs.

### How to use
1. Create a dedicated collection for the proxy and assign them accordingly.
2. Use any of the two modes.
3. There are 3 button operators to generate the proxy: All, Collection, and Selected. (The collection requires you to select the collection from the outliner)
4. Whenever you updated the final mesh, you can re-run the operator again to regenerate the proxy.
5. Use the Show Proxy button to toggle the proxy visibility.
