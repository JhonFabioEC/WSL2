# <b>VENTAJAS DE WSL 2</b>

<text style="display:block; text-align: Justify">

Las principales ventajas de WSL 2 frente a una [<b>máquina virtual</b>][1_0] son:

* WSL 2 está totalmente integrado con Windows, a diferencia de una máquina virtual que está aislado.

* Mientras que una máquina virtual puede ser bastante más lenta a la hora de arrancar el sistema, WSL 2 puede cargar Linux en tan solo un segundo.

* WSL 2 es muy ligero y gasta muy poca memoria RAM, una máquina virtual consume muchos más recursos.

* WSL 2 solo se ejecuta cuando lo necesitamos y solo carga los procesos y servicios necesarios para lo que necesitamos hacer.

* WSL 2 cuenta con un hipervisor nativo que permite ejecutar un Kernel real directamente en Windows.

</text>

[1_0]:https://es.wikipedia.org/wiki/M%C3%A1quina_virtual

## <b>COMPARACIÓN DE WSL 1 CON WSL 2</b>

|     <text style="display:block; text-align: Center"><b>CARACTERÍSTICA</b></text>    |     <b>WSL 1</b> |     <b>WSL 2</b> |
|---|:---:|:---:|
|     Integración entre Windows y Linux |     :white_check_mark:    |     :white_check_mark:    |
|     Tiempos de arranque rápidos |     :white_check_mark:    |     :white_check_mark:    |
|     Huella de recurso pequeña en comparación con las máquinas virtuales tradicionales |     :white_check_mark:    |     :white_check_mark:    |
|     Se ejecuta con las versiones actuales de VMWare y VirtualBox |     :white_check_mark:    |     :white_check_mark:    |
|     VM administradas |     :x:    |     :white_check_mark:    |
|     Kernel de Linux completo |     :x:    |     :white_check_mark:    |
|     Compatibilidad completa con las llamadas del sistema |     :x:    |     :white_check_mark:    |
|     Rendimiento entre sistemas de archivos del sistema operativo    |     :white_check_mark:    |     :x:    |

---

## <b>Mas Información</b>

* [Todo sobre WSL, la mejor forma de instalar Linux en Windows 10][1_1]

* [Comparación de WSL 1 con WSL 2][1_2]

[1_1]:https://di.sld.cu/todo-sobre-wsl-la-mejor-forma-de-instalar-linux-en-windows-10/

[1_2]:https://docs.microsoft.com/es-es/windows/wsl/compare-versions