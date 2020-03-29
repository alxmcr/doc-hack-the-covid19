# Comandos para crear las entidades

## Ruta

```bash
npx sequelize-cli model:generate --name Ruta --attributes ru_codigo:string,ru_lugar_partida:string,ru_lugar_destino:string,bu_estado:string
```

## Bus

```bash
npx sequelize-cli model:generate --name Bus --attributes bu_codigo:string,bu_placa:integer,ru_ruta:integer,bu_estado:string
```

## Pasajero

```bash
npx sequelize-cli model:generate --name Pasajero --attributes pa_codigo:string,pa_nombre:string,pa_apellido_paterno:string,pa_apellido_materno:string,pa_carnet_identidad:integer,pa_carnet_lugar_exp:string,pa_direccion_domicilio:string,pa_telefono_fijo:number,pa_telefono_movil:number,pa_telefono_emergency:number,pa_status_covid:string,pa_estado:string
```

## Conductor

```bash
npx sequelize-cli model:generate --name Conductor --attributes co_codigo:string,co_nombre:string,co_apellido_paterno:string,co_apellido_materno:string,co_carnet_identidad:integer,co_carnet_lugar_exp:string,co_direccion_domicilio:string,co_telefono_fijo:number,co_telefono_movil:number,co_telefono_emergency:number,co_estado:string
```

## Viaje

```bash
npx sequelize-cli model:generate --name Viaje --attributes vi_codigo:string,vi_fecha_viaje:date,vi_hora_partida:time,vi_hora_llegada:time,bu_bus:integer,co_conductor:integer,vi_estado:string
```