# Latihan OOP Python — Inheritance

## Tujuan
Mempelajari konsep inheritance (pewarisan class) di Python.

---

# Studi Kasus

Buat sebuah class induk bernama `Animal`.

Kemudian buat class turunan:
- `Cat`
- `Dog`

---

# Instruksi

## 1. Buat Class Parent `Animal`

### Attribute
Gunakan constructor `__init__()` untuk menyimpan:
- `name`
- `age`

---

## 2. Buat Method pada `Animal`

### `display_info()`
Menampilkan data hewan.

### Contoh Output
```python
Name : Milo
Age  : 3

## `sleep()`

Menampilkan bahwa hewan sedang tidur.

### Contoh Output
```python
Milo is sleeping
```

---

# Membuat Inheritance

## 3. Buat Class `Cat`

Class `Cat` harus mewarisi (`inherit`) dari `Animal`.

### Hint
```python
class Cat(Animal):
```

---

## 4. Tambahkan Method pada `Cat`

### `meow()`

### Contoh Output
```python
Milo says Meow!
```

---

# Membuat Class `Dog`

## 5. Buat Class `Dog`

Class `Dog` harus mewarisi dari `Animal`.

---

## 6. Tambahkan Method pada `Dog`

### `bark()`

### Contoh Output
```python
Buddy says Woof!
```

---

# Membuat Instance

## 7. Buat Object

```python
cat1 = Cat("Milo", 3)
dog1 = Dog("Buddy", 5)
```

---

# Panggil Method

```python
cat1.display_info()
cat1.sleep()
cat1.meow()

dog1.display_info()
dog1.sleep()
dog1.bark()
```

---

# Challenge 

1. Tambahkan attribute `color`
2. Tambahkan method `eat(food)`
3. Buat class baru bernama `Bird`
4. Tambahkan method `fly()`
