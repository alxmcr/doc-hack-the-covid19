# Comandos para crear las entidades

## Ruta

```bash
npx sequelize-cli model:generate --name Ruta --attributes ru_codigo:string,ru_lugar_partida:string,ru_lugar_destino:string,ru_estado:boolean
```

## Bus

```bash
npx sequelize-cli model:generate --name Bus --attributes bu_codigo:string,bu_placa:string,ru_ruta:integer,bu_estado:boolean
```

## Viaje

```bash
npx sequelize-cli model:generate --name Viaje --attributes vi_codigo:string,vi_fecha_viaje:date,vi_hora_partida:time,vi_hora_llegada:time,bu_bus:integer,vi_estado:boolean
```

## Usuario

```bash
npx sequelize-cli model:generate --name Usuario --attributes us_tipo_usuario:string,us_codigo:string,us_nombre:string,us_apellido_paterno:string,us_apellido_materno:string,us_carnet_identidad:bigint,us_carnet_lugar_exp:string,us_direccion_domicilio:string,us_telefono_fijo:bigint,us_telefono_movil:bigint,us_telefono_emergency:bigint,us_avatar:string,us_email:string,us_username:string,us_password:string,us_licencia_conducir:string,us_categoria_licencia:string,us_status_covid:boolean,us_estado:boolean
```

## UsuarioEnfermo

```bash
npx sequelize-cli model:generate --name UsuarioEnfermo --attributes ue_tipo_enfermedad:string,ue_codigo:string,ue_nombre:string,ue_apellido_paterno:string,ue_apellido_materno:string,ue_carnet_identidad:bigint,ue_carnet_lugar_exp:string,ue_direccion_domicilio:string,ue_telefono_fijo:bigint,ue_telefono_movil:bigint,ue_telefono_emergency:bigint,us_avatar:string,ue_status_covid:boolean,ue_estado:boolean
```

