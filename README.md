# Sitio de Valuaplus

Páginas públicas de la app [Valuaplus](https://github.com/LucaLuzzi-03/Valuaplus): presentación, política de
privacidad, términos de uso y soporte. Se publican con GitHub Pages en <https://lucaluzzi-03.github.io/>.

| Archivo | Para qué |
|---|---|
| `index.html` | Presentación de la app y enlaces. Es el "sitio web del desarrollador" de la ficha de Play. |
| `privacidad.html` | La política de privacidad que exige Google Play. **Se actualiza antes** de publicar una versión que cambie qué datos usa la app (por ejemplo, al sumar informes de fallos), junto con la declaración de seguridad de los datos en Play Console. |
| `terminos.html` | Términos de uso, la suscripción y el aviso de que los simuladores son orientativos. |
| `soporte.html` | Cómo reportar un problema. El correo de contacto de la ficha de Play. |
| `version.json` | La versión más antigua de la app que todavía se puede usar (`minVersionCode`, el versionCode de Play). La app lo lee al abrirse; si la instalada es más vieja y Play ya ofrece una que lo cumple, pide actualizar y no deja seguir. **Subirlo es exigir la actualización a todos**: solo ante un error grave o un cambio que rompa la versión vieja. Esta dirección no se puede mudar: las versiones instaladas la tienen escrita. |
| `app-ads.txt` | Autoriza a AdMob a vender publicidad en la app. Tiene que estar en la **raíz** del dominio y ese dominio tiene que coincidir con el sitio web declarado en la ficha de Play. |

Cualquier cambio se publica solo: al pushear a `main`, GitHub Pages lo republica en un minuto.
