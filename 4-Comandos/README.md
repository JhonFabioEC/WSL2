# <b>COMANDOS BÁSICOS DE WSL 2</b>

|     <b>COMANDO</b>    |     <text style="display:block; text-align: Justify"><b>DESCRIPCIÓN</b></text>    |
|:---:|---|
|     `wsl --list --online`    |     Sirve para consultar una lista de las distribuciones de Linux   disponibles a través de la tienda en línea. Este comando también se puede   especificar como `wsl -l -o`.    |
|     `wsl --list --verbose` |     Sirve para consultar una lista de las distribuciones de Linux   instaladas en la máquina Windows, incluido el estado y la versión de WSL que   ejecuta la distribución. Este comando también se puede especificar como `wsl   -l -v`.    |
|     `wsl --update`    |     Sirve para actualizar manualmente la versión del núcleo de Linux de   WSL. También puede usar el comando `wsl --update rollback` para revertir a una   versión anterior del kernel de Linux de WSL.    |
|     `wsl --install   --distribution <Distribution Name>`    |     Sirve para designar una distribución de Linux para la instalación   además de la predeterminada (Ubuntu) reemplazando <b>&lt;Distribution Name&gt;</b>   por el nombre de la distribución. Este comando también se puede especificar   como `wsl -d <Distribution Name>`.    |

---

## <b>Mas Información</b>

* [Comandos básicos para WSL][1_0]

[1_0]:https://docs.microsoft.com/es-es/windows/wsl/basic-commands