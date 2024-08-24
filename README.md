# Comandos avanzados para git

Este repositorio contiene comandos avanzados para git 

# Instrucciones

Para configurar y agregar los comandos avanzados para git, sigue estos pasos:

- Paso 1)

Inicializa un nuevo repositorio de git, solo en caso de no existir.

```shell
$ git init repo-git-avanzado
```

- Paso 2)

Abre el archivo de configuración de git, en la ruta ``.git/config``

- Paso 3)

Copia todo el contenido del archivo `config` disponible en este repositorio, y pegalo dentro del archivo ``.git/config``

- Paso 4)

Establecer nombre de usuario y correo electrónico asociando a cuenta de GitHub o GitLab

```text
[user]
    name = your_username
    email  = your_email
```

# **Nota: Advertencia**

**\*\*Advertencia**** No utilice ningún comando, sin previos conocimientos sobre git.

Los comandos *# Alias basic* son comandos que no manipula los commits y el flujo de trabajo dentro del repositorio, por lo que no representa un peligro al momento de usarlos.

Los comandos *# Alias Advance* son comandos avanzados que sirve para  manipular los commits y el flujo de trabajo dentro del repositorio, por lo que se recomienda utilizarlos con precaución.

# Como usarlo

## # Alias basic

- l
- ll
- s
- aliasg
- aliasl
- store
- flog
- lookup
- save
- sw
- br

## # Alias advance

- __pco__ \<remote> \<branch-name> (create branch local and remote)
- __pbd__ \<remote> \<rama-rename> \<branch-main> (delete branch local and remote)
- __pbr__ \<remote> \<branch-old> \<branch-new-name> (rename branch local and remote)
- __psync__ \<remote> \<branch-main> (download changes remote)
- __pup-br__ \<remote> \<branch-name> (upload changes local)
- __pup__ \<remote> \<branch-main> (push all branches using filter grep)
- __pcl__ \<remote> \<branch-main> (delete all branches using filter grep)
- __pcr__ \<remote> \<branch-main> (delete all branches does not exists from repository remote)
- __pscan__ \<remote> (check out for changes from repository remote)
- __psave__ \<subject> \<message> (register commit with subject and message)
- confg
- confl
- ctlz
- ctly
- bfor
- query
- lg
- see
- resumen
