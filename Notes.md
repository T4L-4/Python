# Notlar

- Boşluklu yapı (Girinti - Indentation)

- Case Sensitive

- Yorum bırakma (Comment)

- Tek çift tırnak farkı

- Tür dönüşümü

- Tek satırda birden fazla değişkene farklı değer atama 
    ``` python
    x, y, z = 2, 3, 4 

    # Veya 

    x = 1; y = 2; z = 3 
    ```

- Tek satırda birden fazla değişkene aynı değeri atama 
    ``` python
    x = y = z = 3
    ```
    
- Koleksyon verilerini değişkenlere sırası ile atama:
    ```python
    fruits = ["apple", "banana", "cherry"]
    x, y, z = fruits

    fruits = ["apple", "banana", "cherry"]
    x, *y = fruits
    ```

- Veri tipleri:
    ```
    Text Type: ....... str
    Numeric Types: ... int, float, complex
    Sequence Types: .. list, tuple, range
    Mapping Type: .... dict
    Set Types: ....... set, frozenset
    Boolean Type: .... bool
    Binary Types: .... bytes, bytearray, memoryview
    None Type: ....... None
    ```

- type():
    ```python
    x = 1    # int
    print(type(x)) 
    # Output: <class 'int'>
    ```

- Type Conversion:
    ```python
    print(float(1)) 
    # Output: 1.0

    print(int(2.8)) 
    # Output: 2

    print(float("3"))
    # Output: 3.0

    print(str("Hello"))
    # Output: "Hello"

    print(str("3"))
    # Output: "3"
    ```
- Operatörler:
    ```python
    Aritmetik operatörler:
    (+, -, *, /, %, **, //)

    Atama operatörleri:
    (=, +=, -=, &=, %= ...)

    Karşılaştırma operatörleri:
    (==, !=, >, <, <=, >=)

    Mantıksal operatörler:
    (and, or, not)

    Referans kontrol operatörleri:
    (is, is not)

    Üyelik operatörleri:
    (in, not in)

    Bitsel operatörler:
    (&, |, ^, ~, <<, >>)
    ```

- Strings, Multiline Strings:
    ```python
    a = "Hello"

    a = """Lorem ipsum dolor sit amet,
    consectetur adipiscing elit,
    sed do eiusmod tempor incididunt
    ut labore et dolore magna aliqua."""
    ```

- String indexleri:
    ```python
    a = "Hello, World!"
    print(a[1])

    for x in "banana":
        print(x)
    ```

- len():
    ```python
    print(len("Hello, World!"))
    # Output: 13
    ```

- .. in str, .. not in str:
    ```python
    txt = "The best things in life are free!"
    print("free" in txt)
    # Output: True

    txt = "The best things in life are free!"
    print("expensive" not in txt)
    # Output: True
    ```

- String parçalam:
    ```python
    b = "Hello, World!"
    print(b[2:5])
    # Output: llo
    
    print(b[:5])
    # Output: Hello
    
    print(b[2:])
    # Output: llo, World!

    print(b[-5:-1])
    # Output: orl
    ```

- 


- Scope altında 'global' keyword'ünü anlat

- Random:
    ```python
    import random

    # Random float
    print(random.uniform(10.5, 75.5)) 
    # Output: 61.069611261180235 (Random oluşturulmuştur. Her çalıştırılmada farklı sayı verecektir)

    # Random float (Virgül sonrası 2 basamak verir.)
    print(round(random.uniform(33.33, 66.66), 2))
    # Output: 23.71 (Random oluşturulmuştur. Her çalıştırılmada farklı sayı verecektir)

    # Random int 10, 999 arası
    num = random.randint(10, 999)

    # Random int 10, 1000 arası 2'şer 2'şer artan listeden
    num = random.randrange(10, 1000, 2)
    print(num1, num2)

    # Random liste elemanı seçme
    num = random.choice([-1, 1])
    ```