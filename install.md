# biome install

Gehen Sie folgendermaßen vor, um den Parser "biome" für Visual Studio Code zu installieren:

Installieren Sie die biome-Bibliothek als devDependency für Ihr Projekt, indem Sie den folgenden Befehl ausführen:
## projekt bezogen
```powershell

            npm install -D @biomejs/biome

```
## global - nicht empfohlen
```powershell

            npm install -g @biomejs/biome

```
Installieren Sie die Biome-Erweiterung für VSCode:

Öffnen Sie die Ansicht "VScode-Erweiterung" über das Menü **"Ansicht"** oder die Verknüpfung ``` Ctrl+Shift+X ```.

Suchen Sie nach **"biome"** und 
installieren Sie die
Erweiterung **"Biome for JavaScript and TypeScript"** von ```Biome.js```.



![](.\screens\install-biome.png)


## Extension Settings
```biome.lspBin```
The ```biome.lspBin``` option overrides the Biome binary used by the extension. The workspace folder is used as the base path if the path is relative.

```biome.rename```
Enables Biome to handle renames in the workspace (experimental).



![](.\screens\install-biome-2.png)