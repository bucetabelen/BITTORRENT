# BitTorrent

Es un protocolo de capa de aplicación de arquitectura P2P que se utiliza para transferencia de archivos entre múltiples dispositivos que se denominan peers. Debido a su arquitectura, BitTorrent es un protocolo escalable ya que no tiene un único punto de falla, más bien todos los peers garantizan la transferencia de un archivo de un nodo de la red a otro. Se denomina torrent al conjunto de peers que participan en la distribución de un archivo en particular.

Para transferir un archivo a este se lo separa en chunks de igual tamaño y varios peers pueden transferir varios chunks de manera simultánea. Cuando un peer se suma a un torrent, inicialmente no tiene el archivo, e irá progresivamente recibiendo chunks hasta tenerlo por completo.

Este proyecto fue llevado a cabo en el año 2022 para la materia Taller de Programación I.
La documentación del trabajo llevado a cabo: https://taller-1-fiuba-rust.github.io/proyecto/22C1/proyecto.html
La documentación oficial del proyecto BitTorrent se encuentra en: https://www.bittorrent.org/.
