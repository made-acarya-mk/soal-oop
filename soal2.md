# Latihan OOP Python — Class Smartphone

## Tujuan
Membuat class `Smartphone` beserta method dan instance-nya.

---

## Instruksi

### 1. Buat Class
Buat class bernama `Smartphone`.

---

### 2. Tambahkan Attribute
Gunakan constructor `__init__()` untuk menyimpan:
- `brand`
- `model`
- `battery`

---

### 3. Buat 3 Method

#### `display_info()`
Menampilkan informasi smartphone.

Contoh output:
```python id="9f20ff"
Brand  : Samsung
Model  : S24
Battery: 80%

## `charge(amount)`

Menambahkan baterai sesuai jumlah yang diberikan.

### Contoh
```python
phone.charge(10)
```

### Output
```python
Battery is now 90%
```

---

## `use(hours)`

Mengurangi baterai saat smartphone digunakan.

### Contoh
```python
phone.use(20)
```

### Output
```python
Battery remaining: 70%
```

---

# Membuat Instance

Buat object berikut:

```python
phone1 = Smartphone("Samsung", "S24", 80)
```

---

# Panggil Method

```python
phone1.display_info()
phone1.charge(10)
phone1.use(20)
```

---

# Challenge 

1. Buat `phone2`
2. Tambahkan attribute `storage`
3. Tambahkan method `power_off()`
