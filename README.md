# SIDEBFLMS DIT · Releases

Solo binarios de cada versión publicada de [SIDEBFLMS DIT](https://github.com/sidebflms/sidebflms-dit) (repo privado) -- sin código fuente aquí.

Existe para que la propia app pueda comprobar si hay una versión nueva sin necesitar acceso al repo privado ni ningún token: lee la API pública de GitHub (`GET /repos/sidebflms/sidebflms-dit-releases/releases/latest`) y, si hay una versión más nueva, ofrece el enlace de descarga del `.dmg` de esa release.

No se instala nada desde aquí a mano -- las releases se publican con `packaging/publish_release.py` del repo privado.
