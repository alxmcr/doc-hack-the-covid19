# Comandos para crear las entidades

## Ruta

```bash
npx sequelize-cli model:generate --name Ruta --attributes ru_codigo:string,ru_lugar_partida:string,ru_lugar_destino:string,ru_estado:string
```

## Bus

```bash
npx sequelize-cli model:generate --name Bus --attributes bu_codigo:string,bu_placa:string,ru_ruta:integer,bu_estado:string
```

## Viaje

```bash
npx sequelize-cli model:generate --name Viaje --attributes vi_codigo:string,vi_fecha_viaje:date,vi_hora_partida:time,vi_hora_llegada:time,bu_bus:integer,vi_estado:string
```

## Usuario

```bash
npx sequelize-cli model:generate --name Usuario --attributes us_tipo_usuario:string,us_codigo:string,us_nombre:string,us_apellido_paterno:string,us_apellido_materno:string,us_carnet_identidad:bigint,us_carnet_lugar_exp:string,us_direccion_domicilio:string,us_telefono_fijo:bigint,us_telefono_movil:bigint,us_telefono_emergency:bigint,us_email:string,us_username:string,us_password:string,us_licencia_conducir:string,us_categoria_licencia:string,us_status_covid:string,us_estado:string
```

## UsuarioEnfermo

```bash
npx sequelize-cli model:generate --name UsuarioEnfermo --attributes uf_tipo_enfermedad:string,uf_codigo:string,uf_nombre:string,uf_apellido_paterno:string,uf_apellido_materno:string,uf_carnet_identidad:bigint,uf_carnet_lugar_exp:string,uf_direccion_domicilio:string,uf_telefono_fijo:bigint,uf_telefono_movil:bigint,uf_telefono_emergency:bigint,uf_status_covid:string,uf_estado:string
```

