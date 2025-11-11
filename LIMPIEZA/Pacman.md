# Limpiar paquetes de pacman

# Lista número de paquetes en caché
sudo ls /var/cache/pacman/pkg | wc -l

# Cuánto pesa todo
du -sh /var/vache/pacman/pkg/

# Borramos (Dejamos la ultima versión anterior a la actual)
sudo paccache -rk 1