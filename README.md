# Avaliación Inicial – Educación Infantil

Ferramenta web para rexistrar a avaliación inicial do alumnado de Educación Infantil (2º ciclo, 3-6 anos), seguindo os criterios da programación didáctica e o calendario oficial do curso. Permite tamén distribuír o alumnado nas catro casas de aula a partir dos mesmos rexistros.

## Que fai

- Crea unha ficha individual por alumno ou alumna, identificado só polas súas iniciais.
- Recolle a valoración (Suficiente/Escasamente Progresado/Correctamente Desenvolvido) e observacións en cada área: estado físico, estado emocional, limitacións e coñecementos previos nas tres áreas do currículo (Comunicación, Harmonía, Contorna).
- Rexistra as técnicas de avaliación empregadas en cada ficha.
- Inclúe o cuestionario de "As Catro Casas" para asignar cada alumno ou alumna a unha casa a partir dos seus trazos.
- Amosa unha vista xeral do grupo, coa distribución por casas e o estado de cada ficha.
- Permite exportar os datos en formato CSV.
- Avisa da data límite oficial para completar a avaliación inicial.

## Privacidade

A aplicación non traballa con datos identificables do alumnado: cada rexistro gárdase unicamente coas iniciais. O acceso está protexido por autenticación (correo e contrasinal), de xeito que só a persoa docente que o configura pode ver e modificar os datos.

## Como funciona

É unha aplicación estática (HTML, CSS e JavaScript), sen necesidade de instalación. Os datos gárdanse na base de datos Firestore dun proxecto propio e gratuíto de Firebase, configurado a primeira vez que se abre a aplicación. Non se comparte ningún dato con terceiros alleos a ese proxecto.

## Uso

1. Abrir a aplicación publicada en GitHub Pages.
2. Configurar a aplicación cos datos do propio proxecto de Firebase (obxecto `firebaseConfig`).
3. Iniciar sesión co usuario creado en Firebase Authentication.
4. Engadir o alumnado (por iniciais) e completar cada ficha.

## Licenza

- Código: [MIT](https://opensource.org/licenses/MIT)
- Contidos e materiais: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.gl)

## Autoría

Eva C. Varela · ORCID: [0009-0008-4320-4886](https://orcid.org/0009-0008-4320-4886)
