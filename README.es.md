# Kernel de OpenBSD

Copia exclusiva del kernel de [OpenBSD](https://www.openbsd.org): el contenido exacto del subdirectorio `sys/` del árbol oficial `src` — nada más.

- **Origen:** `https://github.com/openbsd/src.git` (conversión de solo lectura del CVS oficial; allí no se aceptan pull requests)
- **Subdirectorio:** `sys/`
- **Commit:** `de6b5c3ccec2ff70f86bffaf4a859e92de143d33` (2026-10-12)
- **Integridad:** cada archivo verificado byte por byte (hash de blob de git) contra el repositorio oficial.

## Estructura

`kern/` núcleo del kernel · `sys/` cabeceras y tipos centrales · `arch/` código dependiente de máquina · `dev/` controladores · `scsi/` pila SCSI · `net/`, `netinet/`, `netinet6/` red · `ufs/`, `nfs/`, `ntfs/`, `msdosfs/`, `tmpfs/`… sistemas de ficheros · `uvm/` memoria virtual · `crypto/` · `conf/` ficheros de configuración del kernel.

## Licencia

Licencias ISC/BSD y otras licencias permisivas — ver las cabeceras de cada fichero. Los términos canónicos están en el árbol oficial.

## Enlaces

- OpenBSD: <https://www.openbsd.org> · FAQ: <https://www.openbsd.org/faq/> · Navegador de código: <https://github.com/openbsd/src/tree/master/sys>

*Read this in [English](README.md) · Legu tion en [Esperanto](README.eo.md).*
