# Kursovaya
Курсовая за третий курс (не завершена)

## POST type=register
| in | out | 
|---|---|
|userName| |
|password| | 

## POST type=login
| in | out |
|---|---|
|userName|token |
|password| |

## POST type=newdevice
| in | out |
|---|---|
|deviceName||
|token| |

## GET type=deviceData
| in | out |
|---|---|
|token|JSON|

## GET type=deviceDataUUID
| in | out |
|---|---|
|token|JSON|
|UUID||

## DELETE type=deletedevice
| in | out |
|---|---|
|token||
|UUID||

## PUT type=putdata
| in | out |
|---|---|
|token||
|UUID||
