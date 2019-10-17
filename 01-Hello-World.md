# Hello World

1. Memulai mengenal Java dengan membuat kode sederhana yang akan menghasilkan output "Hello World". Ketik kode berikut lewat code editor dan simpan dengan nama `HelloWorld.java`,

```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```

2. Penamaan file harus sama dengan nama _class_ dalam hal ini HelloWorld. Pada folder yang berisi file `HelloWorld.java` ketik perintah berikut pada console,

```bash
javac HelloWorld.java
```

Maka akan terbentuk sebuah file hasil kompilasi bernama `HelloWorld.class`

3. Jalankan file `HelloWorld.class` dengan perintah berikut,

```bash
java HelloWorld
```

Maka akan keluar output console berupa `Hello, World!`
