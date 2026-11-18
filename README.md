# Trabajo práctico integrador – Computación Aplicada

Universidad de Palermo · Profesor: Matias Chiesa · 2026

## Integrantes

- Jorge Escalante
- Lautaro Randazzo

## Contenido

| Archivo                    | Directorio de la VM       |
|----------------------------|---------------------------|
| root.tar.gz                | /root                     |
| etc.tar.gz                 | /etc                      |
| opt.tar.gz                 | /opt                      |
| www_dir.tar.gz             | /www_dir                  |
| backup_dir.tar.gz          | /backup_dir               |
| var.tar.gz.part-aa, -ab, … | /var (dividido en partes) |

## Cómo reconstruir /var

```bash
cat var.tar.gz.part-* > var.tar.gz
tar -xzf var.tar.gz
```
