Herramienta CLI interactiva para instalar y actualizar whaticket

### descarga y configuración

En primer lugar, necesitas descargarlo:


```bash
sudo apt -y update && apt -y upgrade
sudo apt install -y git
git clone https://github.com/elboga5/whaticket-install.git
```

Ahora, todo lo que tienes que hacer es hacerlo ejecutable:

```bash
sudo chmod +x ./whaticket-install/whaticket
```

###uso

Después de descargarlo y hacerlo ejecutable, debe **navegar hasta** el directorio del instalador y **ejecutar el script con sudo**:

```bash
cd ./whaticket-install
```

```bash
sudo ./whaticket
```
