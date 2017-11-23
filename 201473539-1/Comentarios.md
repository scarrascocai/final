# Tópicos

| Tema | Descripción | Comandos importantes |
|:--|:--|:--|
| 1 | Versionado lineal. | Presentación del taller. Historia de `git`. Instalación. Inicialización y clonado. Grabar cambios. Ver la historia. Deshacer cambios. Tags y versionado semántico. | `config`, `init`, `clone`, `status`, `add`, `commit`, `log`, `revert`, `tag` |
| 2 | Trabajo en equipo. | Remotos. Ramificación y fusionado. Manejo de ramas. Flujo de trabajo. Ramas remotas. Rebase. Supresión de versionado con `.gitignore`. | `branch`, `remote`, `push`, `pull`, `merge`, `fetch`, `rebase`, `checkout`, `stash` |
| 3 | Modelo centralizado. | Protocolo `SSH` `HTTP/S` `smart`. Instaweb. Demonio. Hosting de terceros. | `init --bare`, `instaweb`, `daemon` |
| 4 | Modelo distribuido. | Flujo de trabajo distribuido. Contribución/Mantención de un proyecto distribuido. | `diff`, `request-pull`, `am`, `shortlog`, `cherry-pick`, `format-patch`, `apply` |
| 5 | Hosting. & Configuración. Creación de proyectos. Pull requests. Issue tracker. Planes para estudiantes. GitLab Community Edition. Gitolite. CGit. |  |
| 6 | Herramientas. & Revisión. Historia. Firmas digitales. Búsqueda en la historia. Reescribir la historia. Fusionado avanzado. Debugging. | `log`, `blame`, `grep`, `bisect`, `commit-S`, `tag-s`, `rebase--interactive` |
| 7 | Herramientas. & Submódulos. Subárboles. Árboles de trabajo. Hooks. | `subtree`, `worktree`, `submodule` |
| 8 | Plomería. & Comandos de porcelana/plomería. Referencias. Objetos. Packs. Reflog. Recuperación de datos. Recolección de basura. | `gc`, `reflog`, `rev-parse`, `rev-list`, `write-tree`, `cat-file`, `update-index`, `commit-tree`, `fsck` |
| 9 | Archivos gigantes. Personalización. Aliasing. | `git-lfs`, `git-config-alias` |
| 10 | GUIs. & GUIs para `git` (`gitk`, GitKraken, Atom). | `gitg`, `gitk`, `giggle` |

# Comentarios

Buen taller en general, se nota que hay harta preparación por detrás. Didáctico con hartos ejercicios en las clases. Creo que el taller debería ser enseñado quizás a estudiantes de años menores (2do o 3ero), así están preparados para ramos como Análisis y Diseño de Software, entre otros.

# Recomendaciones

Los últimos ejercicios eran un poco simples, por lo que la gente no se quedaba con las ideas en la cabeza. Quizás se podría reducir la teoría y aplicar más la práctica para estos.

# Flujo de Trabajo

Usar la terminal y el editor de texto Atom. Así no dependo de un programa y puedo trabajar con la menor cantidad de recursos posibles (aunque atom pida más que un editor de texto simple).

En '.gitconfig' agrego:
	[credential]
		helper = cache --timeout=3600
