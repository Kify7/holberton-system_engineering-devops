# Shell Permissions

Learning the shell commands for managing permissions.

## Commands

En el repositorio se encuentra un archivo por cada comando cuya funcionalidad se explica a continuación

 0-iam_betty
```bash
$ su - USERNAME    permite cambiar de usuario
```

1-who_am_i
```bash
$ whoami           permite identifcar en nombre de usuario
```

2-groups
```bash
$ groups           permite identifcar los nombres en los que el usuario está
```

3-new_owner
```bash
$ chown USERNAME  FILE         cambia el dueño del archivo al username establecido
```

4-empty
```bash
$ touch 	   crea un archivo vacío
```

5-execute
```bash
$ chmod 744 FILE     Permiso para ejecutar,  al dueño del archivo establecido
```

6-multiple_permissions
```bash
$ chmod 754 FILE     Permiso de ejecución al dueño y dueño del grupo, permiso de lectura a otros
```

7-everybody
```bash
$ chmod  FILE     Ejecuta permiso al dueño del archivo establecido
```

8-James_Bond
```bash
$ chmod 007  FILE     User y grupo sin permisos, todos los permisos paa otros
```

File: 9-John_Doe
```bash
$ chmod 744 FILE     Ejecuta permiso al dueño del archivo establecido
```