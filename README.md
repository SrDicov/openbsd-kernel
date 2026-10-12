# OpenBSD Kernel

Kernel-only snapshot of [OpenBSD](https://www.openbsd.org): the exact contents of the `sys/` subtree of the official `src` tree — nothing else.

- **Origin:** `https://github.com/openbsd/src.git` (read-only conversion of the official CVS tree; pull requests are not accepted upstream)
- **Subtree:** `sys/`
- **Commit:** `de6b5c3ccec2ff70f86bffaf4a859e92de143d33` (2026-10-12)
- **Integrity:** every file verified byte-for-byte (git blob hash) against upstream.

## Layout

`kern/` core kernel · `sys/` core headers and types · `arch/` machine-dependent code · `dev/` drivers · `scsi/` SCSI stack · `net/`, `netinet/`, `netinet6/` networking · `ufs/`, `nfs/`, `ntfs/`, `msdosfs/`, `tmpfs/`… filesystems · `uvm/` virtual memory · `crypto/` · `conf/` kernel configuration files.

## License

ISC/BSD and other permissive licenses — see the file headers. Canonical terms live in the upstream tree.

## Links

- OpenBSD: <https://www.openbsd.org> · FAQ: <https://www.openbsd.org/faq/> · Code browser: <https://github.com/openbsd/src/tree/master/sys>

*Lee esto en [español](README.es.md) · Legu tion en [Esperanto](README.eo.md).*
